---
title: Expert Guide to Utilizing DiskUsage on Windows Systems
date: 2024-06-25T16:58:53.486Z
updated: 2024-06-26T16:58:53.486Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Guide to Utilizing DiskUsage on Windows Systems
excerpt: This Article Describes Expert Guide to Utilizing DiskUsage on Windows Systems
keywords: DiskSpace Usage Guide,Windows Disk Management,Disk Usage Tips,Tracking Disk Space,System Storage Insight,DiskStats Analysis,Optimizing DiskUsage
thumbnail: https://thmb.techidaily.com/0be1e99c17baad20df818e64c74b29c212a06e76be2a092d41b1fc888150e8a5.jpeg
---

## Expert Guide to Utilizing DiskUsage on Windows Systems

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

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

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/a-buyers-guide-affordable-access-to-windows-11-vcs/"><u>A Buyer’s Guide: Affordable Access to Windows 11 VCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-put-a-windows-computer-to-sleep/"><u>9 Ways to Put a Windows Computer to Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-efficiency-with-these-5-must-have-apps-on-windows-11/"><u>Enhance Efficiency with These 5 Must-Have Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keys-fans-ultimate-guide-to-score-lifetime-windows-11-at-unbeatable-price/"><u>Keys Fans' Ultimate Guide to Score Lifetime Windows 11 at Unbeatable Price</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-visuals-applying-microsoft-store-themes-in-windows/"><u>Reimagining Visuals: Applying Microsoft Store Themes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-8-strategies-for-neutralizing-pink-displays/"><u>Windows Woes: 8 Strategies for Neutralizing Pink Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-activate-educational-themes/"><u>Win 11: Activate Educational Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-format-missing-error-on-pc-windows/"><u>Overcoming 'Format Missing' Error on PC Windows</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-realme-gt-5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pioneering-the-future-workplace-through-virtual-tech/"><u>[Updated] Pioneering the Future Workplace Through Virtual Tech</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-top-5-apps-for-capturing-precise-android-displays/"><u>[New] Top 5 Apps for Capturing Precise Android Displays</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/unravel-the-power-of-live-streaming-with-obs-on-youtube-and-twitch/"><u>Unravel the Power of Live Streaming with OBS on YouTube & Twitch</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-discover-the-unique-aspects-of-twistedwaves-audio-design-software/"><u>New In 2024, Discover the Unique Aspects of TwistedWaves Audio Design Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premiere-pro-quick-fade-magic-1m/"><u>In 2024, Premiere Pro Quick-Fade Magic (1M)</u></a></li>
<li><a href="https://ai-voice.techidaily.com/in-2024-best-4-eminem-voice-generator-apps-for-pc-mac-mobile-and-online/"><u>In 2024, Best 4 Eminem Voice Generator Apps for PC, Mac, Mobile, and Online</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-steer-clear-of-vr-nausea-essential-precautions/"><u>In 2024, Steer Clear of VR Nausea  Essential Precautions</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-success-how-to-make-your-videos-captivate-audiences/"><u>Instagram Success  How to Make Your Videos Captivate Audiences</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>