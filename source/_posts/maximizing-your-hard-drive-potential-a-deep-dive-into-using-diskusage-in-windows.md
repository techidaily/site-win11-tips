---
title: "Maximizing Your Hard Drive Potential: A Deep Dive Into Using DiskUsage in Windows"
date: 2024-11-04T16:13:38.816Z
updated: 2024-11-07T06:47:15.436Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximizing Your Hard Drive Potential: A Deep Dive Into Using DiskUsage in Windows"
excerpt: "This Article Describes Maximizing Your Hard Drive Potential: A Deep Dive Into Using DiskUsage in Windows"
keywords: Hard Drive Optimization,DiskSpace Management,Windows Disk Usage,Storage Capacity,File System Efficiency,Data Utilization Tips,Maxing Out HDD Potential
thumbnail: https://thmb.techidaily.com/24c0edcba484cab644836ae0bb31bb9d7220262ab1b4fd8d660fcbd9d1d07966.jpg
---

## Maximizing Your Hard Drive Potential: A Deep Dive Into Using DiskUsage in Windows

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
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
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
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972693/19272" target="_top" id="1972693">
  <img src="//a.impactradius-go.com/display-ad/19272-1972693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972693/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-windows-best-facsimile-software-for-ps3-games/"><u>[New] 2024 Approved Windows' Best Facsimile Software for PS3 Games</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-recommended-set-17-apps-that-make-picture-fixing-easier/"><u>[New] Recommended Set 17 Apps That Make Picture Fixing Easier</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-premier-6-platforms-for-video-localization/"><u>2024 Approved Premier 6 Platforms for Video Localization</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-streamlining-ad-revenue-for-youtube-channels-post-monetization/"><u>2024 Approved Streamlining Ad Revenue for YouTube Channels Post-Monetization</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-repair-a-malfunctioning-turtle-beach-headset-mic-for-optimal-performance/"><u>How to Repair a Malfunctioning Turtle Beach Headset Mic for Optimal Performance</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-through-high-performance-tech-with-tom-at-the-helm-toms-hardware-haven/"><u>Navigating Through High-Performance Tech with Tom at the Helm - Tom's Hardware Haven</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-access-setup-boosting-morning-routine-windows-and-notepad/"><u>Optimal Access Setup: Boosting Morning Routine, Windows & Notepad</u></a></li>
<li><a href="https://data-wizards.techidaily.com/optimizing-playback-seamlessness-in-vlc/"><u>Optimizing Playback Seamlessness in VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-guide-to-discovering-your-pcs-gpu-version/"><u>Rapid Guide to Discovering Your PC's GPU Version</u></a></li>
<li><a href="https://network-issues.techidaily.com/seamlessly-update-intels-graphic-driver-for-windows-11/"><u>Seamlessly Update Intel's Graphic Driver for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-back-in-time-windows-11-makeover-for-98-fans/"><u>Step Back in Time: Windows 11 Makeover for '98 Fans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-vlc-file-read-error/"><u>Tackling Windows VLC: File Read Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-methods-to-address-windows-sign-in-rejections/"><u>Top Methods to Address Windows Sign-In Rejections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-persistent-steam-login-delays-rust-solution/"><u>Unraveling the Mystery of Persistent Steam Login Delays: Rust Solution</u></a></li>
<li><a href="https://extra-information.techidaily.com/vmiospluswindows-harmony-hub/"><u>VMiOS+Windows Harmony Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-warmth-and-coolness-in-windows-colors/"><u>Winning over Warmth and Coolness in Windows Colors</u></a></li>
</ul></div>

