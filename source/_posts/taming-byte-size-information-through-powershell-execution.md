---
title: Taming Byte-Size Information Through PowerShell Execution
date: 2024-08-28T01:10:45.583Z
updated: 2024-08-29T01:10:45.583Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Taming Byte-Size Information Through PowerShell Execution
excerpt: This Article Describes Taming Byte-Size Information Through PowerShell Execution
keywords: PowerShell Data Management,Byte-Size Info Control,IT Command Scripting,Execute Code Efficiency,Server Optimization Tools,Automated System Tasks,Leverage Scripting Powe
thumbnail: https://thmb.techidaily.com/19529825bc864f6a7105eee056c51264b322fc80a0ff9dab5d25b004c909ef6a.jpg
---

## Taming Byte-Size Information Through PowerShell Execution

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

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Get the Subfolder Size in a Table Format Using PowerShell

![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
![powershell ise start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-ise-start-menu.jpg)
2. Next, copy and paste the following command into the PowerShell ISE console. Make sure to change the directory from c:\\ to your preferred directory.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
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
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-rpg-heritage-clashing-with-new-age-designs/"><u>[New] 2024 Approved  RPG Heritage Clashing with New-Age Designs</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/iscover-variety-50-complimentary-youtube-banners-available-for-2024/"><u>[New] Discover Variety – 50 Complimentary YouTube Banners Available for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-exploring-tech-worlds-dissecting-ar-mr-and-vr-for-2024/"><u>[New] Exploring Tech Worlds  Dissecting AR, MR, & VR for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-innovative-ways-to-control-your-iphones-picture-angles-for-2024/"><u>[New] Innovative Ways to Control Your iPhone's Picture Angles for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-the-quintessential-list-of-top-15-masterpieces-in-stop-motion-for-2024/"><u>[New] The Quintessential List of Top 15 Masterpieces in Stop Motion for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-wheres-the-community-twitch-and-youtube-side-by-side-for-2024/"><u>[New] Where's the Community? Twitch & YouTube Side by Side for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-accelerating-instagram-videos-mobile-and-desktop-tips/"><u>[Updated] Accelerating Instagram Videos  Mobile & Desktop Tips</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-building-a-brand-in-the-metaverse-ecosystem/"><u>[Updated] Building a Brand in the Metaverse Ecosystem</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-essential-guide-to-producing-quality-igtv-on-smartphonesdslrs/"><u>[Updated] In 2024, Essential Guide to Producing Quality IGTV on Smartphones/DSLRs</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-learn-how-to-directly-control-your-iphones-orientation/"><u>[Updated] In 2024, Learn How to Directly Control Your iPhone's Orientation</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-tips-for-drone-racing-enthusiasts-and-premium-fpv-units/"><u>2024 Approved  Expert Tips for Drone Racing Enthusiasts & Premium FPV Units</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unveiling-top-9-webcam-filters-for-professional-streamers/"><u>2024 Approved  Unveiling Top 9 Webcam Filters for Professional Streamers</u></a></li>
<li><a href="https://blog-min.techidaily.com/6-ways-to-transfer-contacts-from-google-pixel-8-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>6 Ways To Transfer Contacts From Google Pixel 8 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/can-you-unlock-apple-iphone-8-plus-after-forgetting-the-passcode-by-drfone-ios/"><u>Can You Unlock Apple iPhone 8 Plus After Forgetting the Passcode?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-concoctions-5-hilarious-tricks-at-work/"><u>Command Line Concoctions: 5 Hilarious Tricks at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correction-of-windows-1011-zoom-failure-code-1132/"><u>Correction of Windows 10/11 Zoom Failure - Code 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-error-on-windows-no-more-blank-screens/"><u>Fixing Steam Error on Windows: No More Blank Screens</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nokia-c12-pro-bootloader-easily-by-drfone-android/"><u>How to Unlock Nokia C12 Pro Bootloader Easily</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-xiaomi-redmi-a2plus-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Xiaomi Redmi A2+ online without jailbreak</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-and-update-your-logitech-c920-webcam-drivers-on-windows-11/"><u>Install and Update Your Logitech C920 Webcam Drivers on Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/instant-access-to-samsung-c460-drivers-secure-your-free-download-today/"><u>Instant Access to Samsung C460 Drivers - Secure Your Free Download Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-install-hyper-v-on-your-windows-11-homesystem/"><u>Instantly Install Hyper-V on Your Windows 11 Homesystem</u></a></li>
<li><a href="https://extra-support.techidaily.com/investigating-ffmpeg-for-intact-audio-preservation-for-2024/"><u>Investigating FFmpeg for Intact Audio Preservation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fingertip-input-windows-tutorial/"><u>Mastering Fingertip Input: Windows Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mobility-control-deactivation-in-w11/"><u>Mastering Mobility Control Deactivation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-guide-to-bypass-ms-teams-error-80080300-on-windows-11/"><u>Mastery Guide to Bypass MS Teams Error 80080300 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-charmap-problems-with-ease/"><u>Mending Windows CharMap Problems with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-graphics-shortage-on-enchanted-magic-school-platform/"><u>Overcoming Graphics Shortage on Enchanted Magic School Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-steams-non-syncing-library-files/"><u>Quick Fix for Steam's Non-Syncing Library Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-disk-read-failure-issue-in-windows/"><u>Remedying the Disk Read Failure Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-unresponsive-windows-webcam/"><u>Remedying Unresponsive Windows Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-disconnected-win-ethernet/"><u>Resurrecting Disconnected Win Ethernet</u></a></li>
<li><a href="https://driver-install.techidaily.com/secure-dell-sound-with-updated-realtek-driver-implementation/"><u>Secure Dell Sound with Updated Realtek Driver Implementation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-optimal-windows-options-for-switch-gaming-enthusiasts/"><u>Selecting Optimal Windows Options for Switch Gaming Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-taskbar-customization-with-portables/"><u>Simplifying Taskbar Customization with Portables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-locate-and-open-windowsstore-folder/"><u>Steps to Locate and Open WindowsStore Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-22h2-windows-setbacks/"><u>Swift Solutions to 22H2 Windows Setbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-halt-windows-shutdown-clock/"><u>Techniques to Halt Windows Shutdown Clock</u></a></li>
<li><a href="https://fox-links.techidaily.com/the-ultimate-resource-for-morphvox-audio-transformation-for-2024/"><u>The Ultimate Resource for MorphVOX Audio Transformation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-issue-code-30005-failed-file-creation-on-windows/"><u>Troubleshooting Issue Code 30005 - Failed File Creation on Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-restoring-deleted-messages-on-gmail/"><u>Ultimate Guide: Restoring Deleted Messages on Gmail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-gpu-potential-win-friendly-tools-ranked-1-6/"><u>Unleash GPU Potential: Win-Friendly Tools Ranked #1-#6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-optimized-web-linkage-in-your-windows-applications-today/"><u>Unlock Optimized Web Linkage in Your Windows Applications Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-windows-11s-auto-hdr-effectively/"><u>Utilizing Windows 11'S Auto HDR Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-wisdom-secrets-to-instant-dossiers-creation/"><u>Win11 Wisdom: Secrets to Instant Dossiers Creation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>