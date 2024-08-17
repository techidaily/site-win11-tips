---
title: Mastering the Science of Storage Sizing in Windows Through Powershell
date: 2024-08-16T01:34:39.701Z
updated: 2024-08-17T01:34:39.701Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Science of Storage Sizing in Windows Through Powershell
excerpt: This Article Describes Mastering the Science of Storage Sizing in Windows Through Powershell
keywords: WinStorageSizeOptimization,PowerShellStorageSizing,StoragePlanningPSWindows,StorageEfficiencyPS,PSStorageConfigWin,SizingScriptsWindowsPowerShell,OptimalStoragePowershell
thumbnail: https://thmb.techidaily.com/f7008ec86977e694421ef724a35a33c6fec32d45741490d50d66c52b24ae9074.jpg
---

## Mastering the Science of Storage Sizing in Windows Through Powershell

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

## How to Calculate a Folder's Size Using PowerShell on Windows
![powershell cmdlet to view folder size bytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-bytes.jpg)

 To calculate a folder's size, you'll need to use the two PowerShell cmdlets, Get-ChildItem and Measure-Object, followed by the Length property and Sum parameter.

 The cmdlet Get-ChildItem lets you retrieve information from a specified directory and its sub-directories. The Measure-Object cmdlet and the associated properties and parameters calculate the sum of the length property for the items returned by the Get-ChildItem (alias 'cgi') cmdlet.

 If you are new to PowerShell, you may want to read our explainer on [essential PowerShell cmdlets](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to understand the basics of PowerShell.

 Now that you are familiar with the PowerShell commands, here is how to use them to get any folder size.

1. Press the **Win** key and type **powershell**.
2. Next, right-click on **Windows PowerShell** and select **Run as administrator**. Click **Yes** if prompted by **User Account Control**.
3. In the PowerShell window, type the following command:  
`Get-ChildItem FolderPath | Measure-Object -Property Length -sum`
4. In the above command, replace **FolderPath** with the directory path where your folder is saved. For example, if you want to calculate the size of the Download folder located in the **E:\\** drive, then the full command will look like this:  
`Get-ChildItem E:\Download | Measure-Object -Property Length -sum`
5. The return will show the item count in the folder and its size in bytes. You'll need to divide the total sum by **1024** to get the size in **KBs** (Kilobytes). Divide it by **1024** again to get the size in **MBs** (Megabytes) and so on.

 Alternatively, you can use the .sum property to retrieve the total size and divide it by 1 million or billion to convert it into megabytes or gigabytes.

![powershell cmdlet to view folder size megabytes gigabytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-megabytes-gigabytes.jpg)

 For example, if you want to know the value in gigabytes (MBs), type the following command and press **Enter**:

`(gci E:\Download | measure Length -s).sum / 1Mb`

 Similarly, replace **1Mb** with **1Gb** to retrieve the folder size in gigabytes.

`(gci E:\Download | measure Length -s).sum / 1Gb`

 If you want to identify the size of specific types of files in a directory, you can use the wildcard character **\*** followed by the file extension type. It will only show the file size for the specified file type.

 For example, to find how much space is taken by the images in a folder, use the following command:

![powershell cmdlet to view folder by file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-by-file-type.jpg)

`(gci E:\download *.jpg | measure Length -s).sum / 1Mb`

 Adding a wildcard character lets you determine if a specific file type takes the most space in the folder. You can then filter the contents based on the file extension and delete or move them if necessary.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Get the Subfolder Size Using PowerShell
![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Get the Subfolder Size in a Table Format Using PowerShell
![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
![powershell ise start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-ise-start-menu.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
2. Next, copy and paste the following command into the PowerShell ISE console. Make sure to change the directory from c:\\ to your preferred directory.  
`$targetfolder = 'C:\'  
$dataColl = Get-ChildItem -Force $targetfolder -Directory -ErrorAction SilentlyContinue | ForEach-Object {  
   $len = Get-ChildItem -Recurse -Force $_.FullName -File -ErrorAction SilentlyContinue | Measure-Object -Property Length -Sum | Select-Object -ExpandProperty Sum  
   $foldername = $_.FullName  
   $foldersize = '{0:N2} GB' -f ($len / 1Gb)  
   [PSCustomObject]@{  
       foldername = $foldername  
       foldersizeGb = $foldersize  
   }  
}  
$dataColl | Out-GridView -Title "Size of Subdirectories in $targetfolder"`
3. Next, click **Run Script** or press **F5** and wait for the script to execute. Depending on the folder size, you'll see a "**Size Of Subdirectories**" dialog listing all the subdirectories with their size.

 In addition to this, you can make use of the PowerShell comparison operators to filter results. For example, to get file size for folders created between June 2023 and July 2023, you can use the following command:

`(gci -force E:\Download &ndash;Recurse -ErrorAction SilentlyContinue | ? {$_.CreationTime -gt '01/23/23' -AND $_.CreationTime -lt '02/23/23'}| measure Length -s).sum / 1Gb`

 In the above command, **"?"** is an alias for the **Where-Object** cmdlet, **\-gt, -AND, -It** are comparison operators, and **CreationTime** is a condition. The command checks if the CreationTime of files in the subdirectory falls within the specified date range and shows output only if the condition is satisfied. If you get an error, ensure your date and time format in the command matches the system's format and try again.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-mastering-background-removal-in-figma-step-by-step-tutorial/"><u>[New] 2024 Approved  Mastering Background Removal in Figma  Step-by-Step Tutorial</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-streamline-storage-solutions-the-20-finest-free-online-spaces/"><u>[New] Streamline Storage Solutions  The 20 Finest FREE Online Spaces</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-from-novice-to-pro-your-complete-guide-to-instagrams-latest-feature-reels/"><u>[Updated] In 2024, From Novice to Pro – Your Complete Guide to Instagram's Latest Feature, Reels</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-prime-platforms-for-asmr-experience-for-2024/"><u>[Updated] Prime Platforms for ASMR Experience for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-unbind-from-discord-on-all-platforms-for-2024/"><u>[Updated] Unbind From Discord on All Platforms for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-mastering-video-best-practices-in-game-recording-and-streaming/"><u>2024 Approved  Mastering Video  Best Practices in Game Recording & Streaming</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-understanding-cultural-influences-on-consumer-behavior-in-global-markets/"><u>2024 Approved  Understanding Cultural Influences on Consumer Behavior in Global Markets</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlock-creative-potential-smart-b-roll-incorporation/"><u>2024 Approved  Unlock Creative Potential  Smart B Roll Incorporation</u></a></li>
<li><a href="https://fox-links.techidaily.com/best-no-entry-price-voice-transformation-for-valorant-gamers/"><u>Best No-Entry Price Voice Transformation for Valorant Gamers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-play-mkv-movies-on-samsung-galaxy-m34-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Can I play MKV movies on Samsung Galaxy M34?</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-poco-x5-pro-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-no-display-available-on-windows-11/"><u>Counteracting 'No Display Available' On Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-one-way-outlook-on-secure-windows-operating-system/"><u>Dealing with One-Way Outlook on Secure Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-red-x-symbols-in-computer-file-systems/"><u>Demystifying Red “X” Symbols in Computer File Systems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discovering-the-heartbeat-of-creativity-in-chatgpts-world/"><u>Discovering the Heartbeat of Creativity in ChatGPT's World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-unparalleled-windows-software-selection/"><u>Dive Into Unparalleled Windows Software Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriching-context-menus-adding-a-diskspace-analyzer-feature/"><u>Enriching Context Menus: Adding a DiskSpace Analyzer Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eternal-trash-bin-configurations-in-your-windows-1011-dock/"><u>Eternal Trash Bin Configurations in Your Windows 10/11 Dock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-depths-of-0x0000003b-bsod-error-in-windows-pcs/"><u>Exploring the Depths of 0X0000003B BSOD Error in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-a-head-start-at-gameplay-with-winning-tactics-fc-style/"><u>Get a Head Start at Gameplay with Winning Tactics, FC Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-wingetui-for-w11-package-management/"><u>Harnessing the Potential of WingetUI for W11 Package Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-expand-your-playnite-digital-library-on-windows-pcs/"><u>How to Expand Your Playnite Digital Library on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-spotlight-images-on-your-pcs-lock-screen/"><u>How to Manage Spotlight Images on Your PC's Lock Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-systemsettings-glitches-in-win11/"><u>How to Repair SystemSettings Glitches in Win11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-excellence-in-image-making-via-premium-grid-makers/"><u>In 2024, Excellence in Image Making via Premium Grid Makers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-infinix-note-30-5g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Infinix Note 30 5G</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-samsung-galaxy-a15-5g-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-lava-agni-2-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Lava Agni 2 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-information-on-windows-components-framework-admin-center/"><u>Key Information on Windows' Components Framework Admin Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-non-windows-programs-as-substitutes-for-the-windows-snip-tool/"><u>Leading Non-Windows Programs as Substitutes for the Window’s Snip Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microphone-windows-11-recording-guide/"><u>Mastering Microphone: Windows 11 Recording Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-repair-tools-crafting-troubleshooter-shortcuts/"><u>Mastering Windows Repair Tools: Crafting Troubleshooter Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-next-leap-after-cortana/"><u>Microsoft's Next Leap After Cortana</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-mkv-to-mp4-transformation-on-windows/"><u>Navigating Through MKV-to-MP4 Transformation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nircmd-guide-for-power-users-optimize-win-commands/"><u>NirCmd Guide for Power Users: Optimize Win Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-your-non-responsive-windows-digital-scribe/"><u>Reigniting Your Non-Responsive Windows Digital Scribe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-functional-wastebin-icon-in-windows-11/"><u>Reinstating Functional Wastebin Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seal-the-gap-with-6-key-strategies-reviving-disappearing-windows-in-windows-11/"><u>Seal the Gap with 6 Key Strategies: Reviving Disappearing Windows in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-activating-user-defined-file-access-controls-in-win1011/"><u>Steps for Activating User-Defined File Access Controls in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-windows-service-non-responder-error/"><u>Strategies for Fixing Windows Service Non-Responder Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-system-efficiency-incorporating-law-filters-into-your-workflow/"><u>Streamlining System Efficiency: Incorporating LAW Filters Into Your Workflow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-try-connection-bluetooth-misfire/"><u>Swift Solution to 'Try Connection' Bluetooth Misfire</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-complicated-update-to-v22h2-process/"><u>Tackling Windows 11'S Complicated Update to V22H2 Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-weather-apps-for-windows-11-and-11/"><u>The Best Weather Apps for Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-launching-windows-ea-quickly/"><u>The Ultimate Guide to Launching Windows EA Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-win11-guide-to-crafting-extractable-sfxs/"><u>The Win11 Guide to Crafting Extractable SFXs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-4-innovations-microsoft-paint-revamped/"><u>Top 4 Innovations: Microsoft Paint Revamped</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-5-tracking-apps-to-track-apple-iphone-15-plus-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>Top 5 Tracking Apps to Track Apple iPhone 15 Plus without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-down-image-files-for-windows-11-backgrounds/"><u>Tracking Down Image Files for Windows 11 Backgrounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-computers-and-phones-with-samsung-flow/"><u>Uniting Computers & Phones with Samsung Flow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-optimizing-your-system-with-intel-drivers/"><u>Unlocking Potential: Optimizing Your System with Intel Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-wordpad-a-window-guide-to-access/"><u>Unlocking WordPad: A Window Guide to Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-profile-management-new-folder-titles/"><u>Win 11 Profile Management: New Folder Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-timeline-6-ways-to-get-your-systems-timer-running/"><u>Windows Timeline: 6 Ways to Get Your System's Timer Running</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-loaded-screen-woes-lol/"><u>Winning Strategies for Loaded-Screen Woes (LOL)</u></a></li>
</ul></div>
