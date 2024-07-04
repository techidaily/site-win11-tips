---
title: The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands
date: 2024-06-25T16:37:54.036Z
updated: 2024-06-26T16:37:54.036Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands
excerpt: This Article Describes The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands
keywords: DiskSpace Analysis,DiskUsage Insights,Usage Commands Guide,Drive Space Examination,Storage Utilization,Command Line Tools,Data Snapshot
thumbnail: https://thmb.techidaily.com/0994f11e3b98aa050445b83a923c27f3f286a1f5302c7ff78d5008912b4d02f9.jpg
---

## The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands

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
<li><a href="https://win11-tips.techidaily.com/time-saving-techniques-for-a-functional-windows-time-service/"><u>Time-Saving Techniques for a Functional Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-win11s-alarming-zero-error-alerts/"><u>How to Bypass Win11’s Alarming Zero Error Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-power-of-placement-comments-in-windows-explorer/"><u>Unveiling the Power of Placement Comments in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-vs-powershell-a-closer-look-at-their-differences/"><u>Terminal Vs. PowerShell: A Closer Look at Their Differences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-quick-fix-for-active-directory-domain-services-printer-errors/"><u>Comprehensible Guide: Quick Fix for Active Directory Domain Services Printer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hidden-options-mastery-of-lost-control-configurations/"><u>Explore Hidden Options: Mastery of Lost Control Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-internal-rdp-problems-on-windows-os/"><u>Eliminating Internal RDP Problems on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-game-pass-access-restoration-in-win-oses/"><u>Mastering Game Pass Access Restoration in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-reset-windows-paperwork-service/"><u>Quick Reset Windows' Paperwork Service</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-visionary-video-download-engine-capture-and-save-anywhere/"><u>In 2024, Visionary Video Download Engine - Capture & Save Anywhere</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-avoid-boredom-learn-to-shuffle-youtube-lists-for-2024/"><u>[Updated] Avoid Boredom  Learn to Shuffle YouTube Lists for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-step-by-step-guide-to-boost-your-social-media-presence-with-instagram-hashtags-for-2024/"><u>[New] Step-by-Step Guide to Boost Your Social Media Presence with Instagram Hashtags for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-accessing-and-saving-tweets-visuals-in-your-android-device/"><u>[New] Accessing and Saving Tweets' Visuals in Your Android Device</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-dot-file-online-with-digisigner-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Sign .dot file Online with DigiSigner</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-realme-11-proplus-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Realme 11 Pro+ Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-explore-top-10-premium-free-iosandroid-live-video-platforms/"><u>[New] Explore Top 10 Premium-Free iOS/Android Live Video Platforms</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-cut-the-cost-not-your-content-quality-try-these-top-8-free-tools-for-2024/"><u>[New] Cut The Cost, Not Your Content Quality - Try These Top 8 Free Tools for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-oppo-reno-9afrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Oppo Reno 9AFRP Lock</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-samsung-galaxy-a23-5g-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Samsung Galaxy A23 5G Phone FRP Lock</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>