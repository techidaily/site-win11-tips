---
title: Demystifying Directory Capacity Assessment via Windows PowerShell
date: 2024-06-25T16:17:29.334Z
updated: 2024-06-26T16:17:29.334Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying Directory Capacity Assessment via Windows PowerShell
excerpt: This Article Describes Demystifying Directory Capacity Assessment via Windows PowerShell
keywords: DirCapacityAssessmentWP,WPShieldingTechniques,CapacityEvaluationWS,PowerShellDirectoryChecks,WindowsShieldPower,TechWMDirInspection,PowerShellCapacityTest
thumbnail: https://thmb.techidaily.com/52b4eaebcfcbc6c7fedd891af89526f0d5ee168fe7bb540778411c3fb0605514.jpg
---

## Demystifying Directory Capacity Assessment via Windows PowerShell

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

## How to Calculate a Folder's Size Using PowerShell on Windows ![powershell cmdlet to view folder size bytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-bytes.jpg)

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

## How to Get the Subfolder Size Using PowerShell ![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

## How to Get the Subfolder Size in a Table Format Using PowerShell ![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-updating-username-on-windows-11/"><u>Essential Guide to Updating Username on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-window-placement-with-powertoys/"><u>Personalizing Window Placement with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-browser-heft-comparing-best-options-for-low-ram-usage/"><u>Minimizing Browser Heft: Comparing Best Options for Low RAM Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-lowered-cpu-demand-for-windows-hosts/"><u>Navigating Lowered CPU Demand for Windows Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-image-perfection-with-windows-photos-app/"><u>Effortless Image Perfection with Windows Photos App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-ultimate-toolkit-to-counteract-bsod-on-win10/"><u>Your Ultimate Toolkit to Counteract BSOD on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-effect-of-eliminating-windows-11-taskbar-chat-on-you/"><u>Understanding the Effect of Eliminating Windows 11 Taskbar Chat on You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-files-save-path-problem-easy-fix-guide/"><u>Windows Files' Save Path Problem: Easy Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumph-over-windows-11-theme-lockdown-a-registry-approach/"><u>Triumph Over Windows 11 Theme Lockdown: A Registry Approach</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-depth-look-at-facetune-a-photographers-best-friend-for-2024/"><u>In-Depth Look at Facetune  A Photographer’s Best Friend for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-fcpx-mastery-the-ultimate-guide-to-online-tutorials/"><u>New In 2024, FCPX Mastery The Ultimate Guide to Online Tutorials</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-convert-and-share-simplified-mp3-to-youtube-process-3-phases-for-2024/"><u>[Updated] Convert & Share  Simplified MP3 to YouTube Process [3 Phases] for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-xiaomi-14-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Xiaomi 14 to iPhone | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-best-gif-maker-software-for-windows-and-mac/"><u>Updated Best GIF Maker Software for Windows and Mac</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-honor-x9a-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Honor X9a Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-how-to-cut-audio-from-video-on-iphonemac/"><u>Updated 2024 Approved How to Cut Audio From Video on iPhone/Mac</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-video-spin-a-comprehensive-2023-users-guide-to-youtube-angles/"><u>In 2024, Mastering Video Spin  A Comprehensive 2023 User's Guide to YouTube Angles</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-standout-book-trailer-highlights/"><u>2024 Approved  Standout Book Trailer Highlights</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>