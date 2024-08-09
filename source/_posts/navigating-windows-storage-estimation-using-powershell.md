---
title: Navigating Windows Storage Estimation Using PowerShell
date: 2024-08-08T11:00:50.301Z
updated: 2024-08-09T11:00:50.301Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Windows Storage Estimation Using PowerShell
excerpt: This Article Describes Navigating Windows Storage Estimation Using PowerShell
keywords: PS Storage Insight,Windows Storage Query,PowerShell Storage Check,Estimate Disk Space PC,Storage Management PSScripts,PowerEstimateStorage,Windows Storage PowerShell
thumbnail: https://thmb.techidaily.com/b40abdafc85906cdf8c505af7da6e2b6de5b2e3882be4cc44ae2eb5b5e3f9c4a.jpg
---

## Navigating Windows Storage Estimation Using PowerShell

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![powershell cmdlet to view folder by file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-by-file-type.jpg)

`(gci E:\download *.jpg | measure Length -s).sum / 1Mb`

 Adding a wildcard character lets you determine if a specific file type takes the most space in the folder. You can then filter the contents based on the file extension and delete or move them if necessary.

## How to Get the Subfolder Size Using PowerShell

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## How to Get the Subfolder Size in a Table Format Using PowerShell

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-quick-and-reliable-mp4-file-capture-tool-for-2024/"><u>[New] Quick & Reliable MP4 File Capture Tool for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-climbing-the-popularity-ladder-with-staff-chosen-videos-at-vimeo/"><u>[Updated] In 2024, Climbing the Popularity Ladder with Staff-Chosen Videos at Vimeo</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tailoring-your-story-a-guide-to-crafting-engaging-podcast-episodes/"><u>[Updated] Tailoring Your Story  A Guide to Crafting Engaging Podcast Episodes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-navigating-instagrams-filter-features-for-high-quality-images/"><u>2024 Approved  Navigating Instagram's Filter Features for High-Quality Images</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-the-sound-sleuths-guide-to-recording-streaming-media/"><u>2024 Approved  The Sound Sleuth's Guide to Recording Streaming Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-upcoming-license-expiration-error-in-w10w11/"><u>Addressing Upcoming License Expiration Error in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-entry-point-issues-on-windows-systems/"><u>Bypassing Entry Point Issues on Windows Systems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/deciphering-the-facts-critical-analysis-in-ai-health-advice/"><u>Deciphering the Facts: Critical Analysis in AI Health Advice</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-the-end-of-yahoo-messenger-a-look-back-at-why-it-was-shut-down/"><u>Decoding the End of Yahoo! Messenger: A Look Back at Why It Was Shut Down</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-failed-operations-code-0x0000011b-fixes/"><u>Eliminating 'Failed' Operations: Code 0X0000011B Fixes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-glitch-fixed-gpu-back-on-track-nvidia/"><u>Graphics Glitch Fixed, GPU Back on Track (NVIDIA)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-files-fix-incessant-file-explorer-opens/"><u>Halt Files: Fix Incessant File Explorer Opens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-store-error-0x80072f17-on-windows/"><u>How to Fix Microsoft Store Error 0X80072F17 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-unfoldable-folders-in-win1110-on-double-clicks/"><u>How to Overcome Unfoldable Folders in Win11/10 on Double-Clicks</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/how-to-record-youtube-videos-for-2024/"><u>How to Record YouTube Videos for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-on-nokia-c12-pro-by-drfone-android/"><u>In 2024, How to Bypass FRP on Nokia C12 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-low-power-mode-options/"><u>Navigating Through Windows' Low-Power Mode Options</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-how-to-add-audio-fade-out-effect-for-2024/"><u>New How to Add Audio Fade Out Effect for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-windows-horizon-surpassing-11s-achievements/"><u>Next Windows Horizon: Surpassing 11'S Achievements</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-vivo-y36i-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Vivo Y36i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-photo-import-discrepancies-between-ios-and-windows-11/"><u>Remedying Photo Import Discrepancies Between iOS and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-hyper-v-feature-from-windows-11-builds/"><u>Removing Hyper-V Feature From Windows 11 Builds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-ragnarok-overcoming-x-script-woes/"><u>Restoring Ragnarok: Overcoming X-Script Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-methods-for-launching-wordpad-in-windows/"><u>Simplified Methods for Launching WordPad in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-9-techniques-for-flawless-powerpoint-prints-in-windows/"><u>Solving the Puzzle: 9 Techniques for Flawless PowerPoint Prints in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unreachable-mb-status-on-windows-11-systems/"><u>Tackling Unreachable MB Status on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-cmd-interface-a-step-by-step-process/"><u>Tailoring CMD Interface: A Step-by-Step Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-techniques-for-analyzing-drive-space-using-diskusage-commands/"><u>The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-plus-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue From Apple iPhone 6 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-potential-of-your-computers-shortcut-keys-for-size-adjustment-on-win11/"><u>Unleash the Potential of Your Computer's Shortcut Keys for Size Adjustment on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-efficiency-crafted-keybinds-for-snippet-pasting-in-windows-11/"><u>Unleashing Efficiency: Crafted Keybinds for Snippet Pasting in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-better-words-best-windows-software-for-scribes/"><u>Unlock Better Words: Best Windows Software for Scribes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unlock-prime-deal-revealed/"><u>Windows 11 Unlock: Prime Deal Revealed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>