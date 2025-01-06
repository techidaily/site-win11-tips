---
title: "Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands"
date: 2025-01-04T03:29:05.676Z
updated: 2025-01-06T08:02:15.410Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands"
excerpt: "This Article Describes Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands"
keywords: DriveSpaceOptimization,WindowsDiskManagement,DiskUsageAnalysis,StorageEfficiencyTips,SpaceUtilizationWindows,CommandLineDriveSpace,ManageDiskStorage
thumbnail: https://thmb.techidaily.com/596dd6315d1559e3cb5b3aa52b6f2b9825ab34a39bbf16416336b018124bf2bc.jpg
---

## Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-crafting-a-sports-highlight-step-by-step-tutorial/"><u>[New] 2024 Approved Crafting a Sports Highlight Step-by-Step Tutorial</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-stop-chrome-from-skipping-playback-of-facebook-videos/"><u>[New] Stop Chrome From Skipping Playback of Facebook Videos</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unveiling-the-dynamics-an-in-depth-look-at-luminances-hdr/"><u>[New] Unveiling the Dynamics An In-Depth Look at Luminance's HDR</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-audio-recording-101-from-youtube-playback-to-files/"><u>[Updated] 2024 Approved Audio Recording 101 From YouTube Playback To Files</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-swift-transformations-top-5-no-download-online-gif-to-video-tools/"><u>[Updated] 2024 Approved Swift Transformations Top 5 No-Download, Online GIF to Video Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-tailor-videos-to-instagrams-preferred-format/"><u>[Updated] Tailor Videos to Instagram's Preferred Format</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/138580579-9781450294041-a-manual-for-the-modern-mystic/"><u>A Manual for the Modern Mystic | Free Book</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/convert-your-dvds-to-apple-tv-compatible-formats-with-macx-the-ultimate-free-mac-ripper/"><u>Convert Your DVDs to Apple TV Compatible Formats with MacX - The Ultimate, FREE Mac Ripper!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-display-driver-start-fails-in-windows/"><u>Essential Fixes for “Display Driver Start” Fails in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experts-guide-to-windows-security-crafting-custom-pin-layouts/"><u>Expert's Guide to Windows Security: Crafting Custom PIN Layouts</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/in-depth-yakuza-like-a-dragon-review-top-choice-for-fans-of-japanese-role-playing-games/"><u>In-Depth Yakuza: Like a Dragon Review - Top Choice for Fans of Japanese Role-Playing Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-chatgpt-installation-in-a-windows-environment/"><u>Master ChatGPT Installation in a Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-minecraft-errors-with-ease/"><u>Navigating Windows' Minecraft Errors with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-resetting-issue-with-windows-11s-nvidia-control-panel/"><u>Overcoming Resetting Issue with Windows 11'S NVidia Control Panel</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/rejuvenate-your-pc-in-minutes-mastering-the-factory-reset-of-windows-11s-bios/"><u>Rejuvenate Your PC in Minutes: Mastering the Factory Reset of Windows 11'S BIOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-icon-cache-a-step-by-step-guide/"><u>Resetting Icon Cache: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-function-keys-on-a-win10-laptoppc/"><u>Revive Your Function Keys on a WIN10 Laptop/PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguarding-your-note-applications-on-pcs/"><u>Safeguarding Your Note Applications on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-refresh-win11-terminal-settings/"><u>Steps to Refresh Win11 Terminal Settings</u></a></li>
</ul></div>

