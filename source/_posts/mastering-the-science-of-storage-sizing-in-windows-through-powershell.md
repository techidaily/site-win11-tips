---
title: Mastering the Science of Storage Sizing in Windows Through Powershell
date: 2024-07-12T17:33:00.980Z
updated: 2024-07-13T17:33:00.980Z
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

## How to Get the Subfolder Size Using PowerShell
![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

## How to Get the Subfolder Size in a Table Format Using PowerShell
![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
![powershell ise start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-ise-start-menu.jpg)
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
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-1011s-trouble-solving-capabilities/"><u>Enhancing Windows 10/11'S Trouble-Solving Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-resetting-windows-11-applications/"><u>Guide to Resetting Windows 11 Applications</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-shopping-highlights-editing-steps-for-hauls-and-collections/"><u>2024 Approved  Shopping Highlights  Editing Steps for Hauls & Collections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-methods-overcoming-defender-engine-outage-in-5-steps/"><u>Essential Methods: Overcoming Defender Engine Outage in 5 Steps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-unveiling-a-simple-yet-powerful-copywriting-model-for-ads/"><u>In 2024, Unveiling a Simple, Yet Powerful Copywriting Model for Ads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhanced-collaboration-on-a-sleeker-platform/"><u>Enhanced Collaboration on a Sleeker Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-update-files-are-missing-error-0x80070003-on-windows/"><u>How to Fix the Update Files Are Missing Error 0X80070003 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disconnections-windows-and-printers/"><u>Overcoming Disconnections: Windows & Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-guide-to-top-7-secure-windows-applications-153-chars/"><u>Exclusive Guide to Top 7 Secure Windows Applications (153 Chars)</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-advanced-strategies-for-precise-vr-gameplay-recording/"><u>[Updated] In 2024, Advanced Strategies for Precise VR Gameplay Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rectifying-dism-failure-0x800f082f/"><u>Mastering the Art of Rectifying DISM Failure: 0X800F082F</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-meizu-21-pro-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Meizu 21 Pro System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-microphone-errors-during-valorant-matches/"><u>Eliminating Microphone Errors During Valorant Matches</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-an-all-inclusive-subtitle-handbook-from-basics-to-advanced-tips/"><u>[New] An All-Inclusive Subtitle Handbook  From Basics to Advanced Tips</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/cutting-edge-mac-accessory-visionplussound-capturing/"><u>Cutting-Edge Mac Accessory  Vision+Sound Capturing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-personalized-cost-free-epilogue-soundscape-creation/"><u>2024 Approved  Personalized, Cost-Free Epilogue Soundscape Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-your-guide-to-repairing-windows-software-glitches/"><u>Immediate Actions: Your Guide to Repairing Windows Software Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-game-capture-denial-due-to-low-specs/"><u>Fixing Windows Game Capture Denial Due to Low Specs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-search-11-key-strategies/"><u>Master Your Windows Search: 11 Key Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-cannot-continue-error-in-amd-installation/"><u>Overcoming the 'Cannot Continue' Error in AMD Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restore-a-non-installed-disk-on-your-win-11-pc/"><u>How to Restore a Non-Installed Disk on Your Win 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-failure-lockout-period-on-sign-in-errors/"><u>Personalizing Failure Lockout Period on Sign In Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fixing-captcha-failed-message/"><u>Guide to Fixing CAPTCHA Failed Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-no-lags-smoother-youtube-videos-on-windows/"><u>Navigate No Lags: Smoother YouTube Videos on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-oneplus-12-screen-sharing-drfone-by-drfone-android/"><u>How To Do OnePlus 12 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-instagram-music-lawfare-summary/"><u>[New] Instagram Music Lawfare Summary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-locate-the-lurking-lost-disk/"><u>How to Locate the Lurking Lost Disk</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-your-browser-eliminating-youtube-stalls-in-chrome/"><u>Expedite Your Browser: Eliminating YouTube Stalls in Chrome</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-ultimate-guide-premium-online-tools-for-high-quality-music-editing-for-2024/"><u>New The Ultimate Guide Premium Online Tools for High-Quality Music Editing for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-16-top-rated-avi-video-cutting-tools-for-windows-mac-android-and-iphone-for-2024/"><u>New 16 Top-Rated AVI Video Cutting Tools for Windows, MAC, Android, and iPhone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gateway-to-your-inner-world-accessing-windows-hidden-char-personality-screen/"><u>Gateway to Your Inner World: Accessing Windows' Hidden Char Personality Screen</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-honor-magic-5-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Honor Magic 5? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-unlocking-stuck-battlenet-login/"><u>Expert Guide to Unlocking Stuck Battle.net Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-10-pricing-with-smart-key-acquisition/"><u>Mastering Windows 10 Pricing with Smart Key Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-differences-between-exe-and-msi-files/"><u>Exploring the Differences Between EXE & MSI Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-check-for-updates-in-system-context-menu/"><u>Integrating Check for Updates in System Context Menu</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-reworking-your-online-identity-comprehensive-tiktok-username-change-protocols/"><u>In 2024, Reworking Your Online Identity  Comprehensive TikTok Username Change Protocols</u></a></li>
</ul></div>
