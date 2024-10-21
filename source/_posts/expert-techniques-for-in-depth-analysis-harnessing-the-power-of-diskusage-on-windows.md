---
title: "Expert Techniques for In-Depth Analysis: Harnessing the Power of DiskUsage on Windows"
date: 2024-10-15T01:53:09.722Z
updated: 2024-10-20T19:53:48.185Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Expert Techniques for In-Depth Analysis: Harnessing the Power of DiskUsage on Windows"
excerpt: "This Article Describes Expert Techniques for In-Depth Analysis: Harnessing the Power of DiskUsage on Windows"
keywords: DiskUsage Insight,UsageAnalysis Windows,DiskSpace Monitoring,Performance Metrics,System Utility Analysis,Resource Management Windows,Storage Efficiency Windows
thumbnail: https://thmb.techidaily.com/4cdd8afbaa8b657928993c65ff49e85d13ed5759387c65adfd46afd484910746.jpg
---

## Expert Techniques for In-Depth Analysis: Harnessing the Power of DiskUsage on Windows

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-automate-your-snapshot-backup-from-snapchat-app/"><u>[New] In 2024, Automate Your Snapshot Backup From Snapchat App</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-instagrams-time-constraints-for-video-content-explored/"><u>[New] In 2024, Instagram's Time Constraints for Video Content Explored</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-streaming-showdown-the-podcast-challenge-to-youtubes-dominance/"><u>[New] In 2024, Streaming Showdown The Podcast Challenge to YouTube’s Dominance</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-exclusive-moba-selection-for-android-gamers-for-2024/"><u>[Updated] Exclusive MOBA Selection for Android Gamers for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/achieve-your-fitness-goals-easier-using-the-built-in-gps-and-wellness-apps-on-fitbit-versa-3/"><u>Achieve Your Fitness Goals Easier Using the Built-In GPS and Wellness Apps on Fitbit Versa 3</u></a></li>
<li><a href="https://games-able.techidaily.com/asus-rog-ally-vs-steam-deck-comparative-analysis/"><u>ASUS ROG Ally Vs. Steam Deck: Comparative Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-screens-enhance-performance-on-windows-11/"><u>Clear Screens, Enhance Performance on Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/efficient-video-compression-techniques-boosting-your-websites-speed-and-quality/"><u>Efficient Video Compression Techniques: Boosting Your Website's Speed and Quality</u></a></li>
<li><a href="https://vp-tips.techidaily.com/extend-your-iphones-lifespan-effective-solutions-for-boosting-battery-performance/"><u>Extend Your iPhone's Lifespan: Effective Solutions for Boosting Battery Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reestablish-offline-steam-connection-with-servers-on-pc/"><u>How to Reestablish Offline Steam Connection with Servers on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-hardware-4-techniques-for-opening-the-disk-editor-in-win11/"><u>Master Hardware: 4 Techniques for Opening the Disk Editor in Win11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-updating-your-windows-11-hardware-drivers-with-ease/"><u>Step-by-Step Guide: Updating Your Windows 11 Hardware Drivers with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enable-driver-verifier-in-windows-11/"><u>Steps to Enable Driver Verifier in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-webcam-malfunction-in-windows-11-fixing-error-0xa00f4289/"><u>Streamlining Webcam Malfunction in Windows 11: Fixing Error 0xA00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-pc-the-process-of-reverting-with-system-restore/"><u>Streamlining Your PC: The Process of Reverting with System Restore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-resolving-blue-screen-error-interrupt-not-handled/"><u>Techniques for Resolving Blue Screen Error: Interrupt Not Handled</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/king-the-power-of-thumbnails-creating-visual-appeal-for-youtube-content-for-2024/"><u>Unlocking the Power of Thumbnails Creating Visual Appeal for YouTube Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-fix-unraveling-error-0x30017/"><u>Win11 Fix: Unraveling Error 0X30017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-workspace-wizardry-mastering-direct-file-exchange-in-clouds/"><u>Windows Workspace Wizardry: Mastering Direct File Exchange in Clouds</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    