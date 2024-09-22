---
title: "Unlocking the Secrets of Windows' Drive Space: A Guide to DiskUsage"
date: 2024-09-19T19:38:45.910Z
updated: 2024-09-22T04:07:57.940Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking the Secrets of Windows' Drive Space: A Guide to DiskUsage"
excerpt: "This Article Describes Unlocking the Secrets of Windows' Drive Space: A Guide to DiskUsage"
keywords: WinDiskSpaceTips,DiskUsageOverview,FreeDiskWindows,CleanupDiskWindows,DriveFreeStorage,ManageWinSpace,OptimizeWindowsDrive
thumbnail: https://thmb.techidaily.com/0d5172690106aeb0b1e42f6467812ce6f42bcdb66b69630f22d7099f56101e88.jpeg
---

## Unlocking the Secrets of Windows' Drive Space: A Guide to DiskUsage

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
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://win11-tips.techidaily.com/convertir-video-mkv-a-formato-mp4-online-sin-coste-herramientas-de-movavi/"><u>Convertir Video MKV a Formato MP4 Online Sin Coste: Herramientas De Movavi</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-installation-guide-logitech-brio-webcam-software-for-various-windows-versions/"><u>Easy Installation Guide: Logitech BRIO Webcam Software for Various Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transforming-tga-images-into-bmp-format/"><u>Free Online Converter: Transforming TGA Images Into BMP Format</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722964021443-get-the-newest-epson-xp-440-driver-software-download-instructions-inside/"><u>Get the Newest Epson XP-440 Driver Software - Download Instructions Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratis-online-converteer-3gp-naar-jpeg-efficient-beeldcodeconverting-met-movavi/"><u>Gratis Online Converteer 3GP Naar JPEG: Efficiënt Beeldcodeconverting Met Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratis-wma-in-aac-omzetten-via-onlinemiddel-professioneel-resultaat-movavi/"><u>Gratis WMA in AAC Omzetten Via Onlinemiddel - Professioneel Resultaat Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuit-swf-filament-naar-format-m4v-omzetten-leergids-van-movavi-online/"><u>Gratuit SWF-Filament Naar Format M4V Omzetten: Leergids Van Movavi Online</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-vivo-y100i-power-5g-phone-without-pin-by-drfone-android/"><u>How to Unlock Vivo Y100i Power 5G Phone without PIN</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-realme-narzo-60x-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Realme Narzo 60x 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-video-conversion-free-webm-and-mkv-transformers-at-movavis-digital-library/"><u>Streamline Video Conversion: Free Webm and MKV Transformers at Movavi's Digital Library</u></a></li>
<li><a href="https://extra-resources.techidaily.com/subtlety-in-volume-the-ableton-way/"><u>Subtlety in Volume The Ableton Way</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-net-requirement-issue-in-windows-apps/"><u>Tackling the .NET Requirement Issue in Windows Apps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-top-platform-trio-which-one-triumphs-vimeo-youtube-dailymotion-in-2024/"><u>The Top Platform Trio Which One Triumphs – Vimeo, YouTube, Dailymotion, In 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/upload-and-share-videos-on-twitter-made-easy-for-2024/"><u>Upload & Share Videos on Twitter Made Easy for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/visualizing-google-meet-introduction-to-effects-and-filtering/"><u>Visualizing Google Meet Introduction to Effects & Filtering</u></a></li>
</ul></div>

