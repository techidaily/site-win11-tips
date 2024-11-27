---
title: Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command
date: 2024-11-21T16:29:27.295Z
updated: 2024-11-27T16:30:24.180Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command
excerpt: This Article Describes Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command
keywords: Data Usage Trends,Windows Disk Analysis,Usage Pattern Discovery,DiskStatistics Insight,Data Consumption Tracking,Usage Command Analysis,Uncovered Data Patterns
thumbnail: https://thmb.techidaily.com/0fdf2fa9392d7802826e32aaa7c1f7d7a9d236164e77dff001f4eb865ae62af5.jpg
---

## Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-decoding-twitter-archived-content-for-clarity-for-2024/"><u>[New] Decoding Twitter Archived Content for Clarity for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-earnings-expedition-navigating-your-way-to-wealth-with-youtube-mobile-content/"><u>[New] In 2024, Earnings Expedition Navigating Your Way to Wealth with YouTube Mobile Content</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-join-the-party-your-guide-to-active-tiktok-streaming/"><u>[New] In 2024, Join the Party Your Guide to Active TikTok Streaming</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-graphicgrind-studio/"><u>2024 Approved GraphicGrind Studio</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-video-capture-on-periscope-a-comprehensive-manual/"><u>2024 Approved Mastering Video Capture on Periscope A Comprehensive Manual</u></a></li>
<li><a href="https://extra-tips.techidaily.com/clear-shots-a-guide-to-still-image-stability-for-2024/"><u>Clear Shots A Guide to Still Image Stability for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/crafted-collections-of-ig-pics/"><u>Crafted Collections of IG Pics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-windows-security-learn-about-canary-channel/"><u>Dive Into Windows Security: Learn About Canary Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reclaim-a-non-functional-tab-key-on-windows-10/"><u>How to Reclaim a Non-Functional Tab Key on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-policy-settings-with-three-perspectives/"><u>Mastering Windows Policy Settings with Three Perspectives</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/navigating-the-maze-of-uncertainty-tackling-todays-ai-challenges-in-precision-and-reliability-zdnet/"><u>Navigating the Maze of Uncertainty: Tackling Today's AI Challenges in Precision & Reliability | ZDNet</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-the-best-peter-mckinnon-luts-recommendation/"><u>New 2024 Approved The Best Peter McKinnon LUTs Recommendation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolve-microsoft-office-error-0x80041015/"><u>Quick Guide to Resolve Microsoft Office Error 0X80041015</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rollback-mastery-utilizing-system-restore-in-windows/"><u>Rollback Mastery: Utilizing System Restore in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-down-windows-memory-spikes-from-edge-webview2/"><u>Scaling Down Windows Memory Spikes From Edge WebView2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-video-conversion-turning-mkv-into-mp4-in-windows/"><u>Swift Video Conversion: Turning MKV Into MP4 in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-infinix-note-30i-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Infinix Note 30i Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-additional-protection-defying-ms-defender/"><u>Unlocking Additional Protection: Defying MS Defender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-speech-recognition-addressing-not-launched-problems/"><u>Windows Speech Recognition: Addressing Not Launched Problems</u></a></li>
</ul></div>

