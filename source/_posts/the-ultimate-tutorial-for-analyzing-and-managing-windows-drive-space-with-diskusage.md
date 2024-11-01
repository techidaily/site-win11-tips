---
title: The Ultimate Tutorial for Analyzing and Managing Windows Drive Space with DiskUsage
date: 2024-10-25T18:58:46.905Z
updated: 2024-11-01T17:15:35.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Tutorial for Analyzing and Managing Windows Drive Space with DiskUsage
excerpt: This Article Describes The Ultimate Tutorial for Analyzing and Managing Windows Drive Space with DiskUsage
keywords: DiskSpace Management Guide,Windows Drives Analysis,Disk Usage Monitoring,Drive Space Optimization Tips,Storage Capacity Control,System Drive Efficiency,Data Freeze Prevention
thumbnail: https://thmb.techidaily.com/9d3732c41a53a8a22c767ec42385e845ec206bbdbcdafbf7af2a45ba4a50f286.jpg
---

## The Ultimate Tutorial for Analyzing and Managing Windows Drive Space with DiskUsage

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868586/19272" target="_top" id="1868586">
  <img src="//a.impactradius-go.com/display-ad/19272-1868586" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868586/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/1925484/19272" target="_top" id="1925484">
  <img src="//a.impactradius-go.com/display-ad/19272-1925484" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925484/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/efending-your-youtube-profile/"><u>[New] Defending Your YouTube Profile</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-how-to-use-zoom-in-gmail/"><u>[New] How to Use Zoom in Gmail</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-haste-in-playlist-distribution-youtube-guide-for-2024/"><u>[Updated] Haste in Playlist Distribution YouTube Guide for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-essential-picks-discover-the-top-12-easy-to-use-flipscreen-cams/"><u>[Updated] In 2024, Essential Picks Discover the Top 12 Easy-to-Use Flipscreen Cams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-the-windows-fatal-blue-screen-error-0x8007007e/"><u>Clearing Up the Windows Fatal Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deconstructing-mmc-glitches-resolving-snap-in-crashes/"><u>Deconstructing MMC Glitches: Resolving Snap-In Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-routes-to-activate-windows-11s-calculator/"><u>Efficient Routes to Activate Windows 11'S Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-characters-with-windows-11-map-tool/"><u>Explore Characters with Windows 11 Map Tool</u></a></li>
<li><a href="https://fox-access.techidaily.com/gentle-fading-audio-paths-in-live-for-2024/"><u>Gentle Fading Audio Paths in Live for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-uninstall-wsl-on-windows-11-and-11/"><u>How to Completely Uninstall WSL on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organizing-and-naming-pro-level-windows-approach-max-156/"><u>Organizing & Naming: Pro-Level Windows Approach (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-process-termination-failure-error-window/"><u>Remedying the 'Process Termination Failure' Error Window</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fix-for-hp-notebooks-keyboard-issues-quick-and-easy-troubleshooting-steps-article-title-article-with-phase-descriptions406-chars/"><u>Step-by-Step Fix for HP Notebook's Keyboard Issues — Quick & Easy Troubleshooting Steps (Article Title) – Article with Phase Descriptions—406 Chars</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-the-inability-of-application-to-launch-correctly-error-0xc000007b/"><u>Troubleshooting and Fixing the Inability of Application to Launch Correctly [Error 0XC000007B]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-purpose-of-an-x-symbol-for-your-drives/"><u>Understanding the Purpose of an X Symbol for Your Drives</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726223452341-mka-mp3/"><u>무료 MKA MP3 변환 - 컴퓨터, 스마트폰에서 사용하는 최고의 툴</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    