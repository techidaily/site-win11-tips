---
title: Strategizing DiskSpace Management with Disc Usage Insights in Windows
date: 2025-01-13T17:53:06.863Z
updated: 2025-01-18T16:27:36.488Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategizing DiskSpace Management with Disc Usage Insights in Windows
excerpt: This Article Describes Strategizing DiskSpace Management with Disc Usage Insights in Windows
keywords: Space Optimization Strategy,Disk Inspection Tips,Managing Disk Storage,Tracking File Size,Utilizing Disc Usage Insights,Windows Data Management,Efficient Space Planning
thumbnail: https://thmb.techidaily.com/4552dd09d3248cdc2d2f0b5a8866485e28d07f676a831c6174ae4d9651da8ef0.jpg
---

## Strategizing DiskSpace Management with Disc Usage Insights in Windows

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-djs-guide-to-elevating-visual-narratives-with-soundtracks-fb-for-2024/"><u>[Updated] The DJ's Guide to Elevating Visual Narratives with Soundtracks (FB) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-printer-settings-for-secure-edge-environment/"><u>Configuring Printer Settings for Secure Edge Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-proactive-tactics-to-rectify-network-key-errors-on-windows-11-systems/"><u>Five Proactive Tactics to Rectify Network Key Errors on Windows 11 Systems</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-fix-the-blue-screen-error-caused-by-tcpipsys-in-windows-11-7-and-8/"><u>How to Fix the Blue Screen Error Caused by TCP/IP.sys in Windows 11, 7 & 8</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-tecno-spark-20-proplus-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Tecno Spark 20 Pro+ FRP Without Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-archive-integration-win1011-imaging-strategies/"><u>Invisible Archive Integration: WIN10/11 Imaging Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-awareness-in-pc-sleep-states/"><u>Mastering Device Awareness in PC Sleep States</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-the-art-of-video-from-still-photos-through-pixiz-techniques/"><u>Mastering the Art of Video From Still Photos Through Pixiz Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-non-responsive-windows-services-manager/"><u>Overcoming The Challenges of Non-Responsive Windows Services Manager</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reactive-solutions-for-your-turtle-beach-mic-not-working-problems/"><u>Reactive Solutions for Your Turtle Beach Mic Not Working Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-reclaiming-microsoft-store-on-windows-11/"><u>Regaining Control: Reclaiming Microsoft Store on Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/securing-privacy-for-group-posters-without-identifiers/"><u>Securing Privacy for Group Posters without Identifiers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-setting-up-outlook-preview-on-winos/"><u>Simplified Guide: Setting Up Outlook Preview on WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-ps4-joystick-disconnections-in-windows-environment/"><u>Solving PS4 Joystick Disconnections in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-insufficient-usb-resource-allocation/"><u>Tackling Insufficient USB Resource Allocation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Oppo A18? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-motorola-edge-2023-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Motorola Edge 2023 Device</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-guide-top-7-solutions-when-wireless-charger-fails-with-iphone/"><u>Troubleshooting Guide: Top 7 Solutions When Wireless Charger Fails with iPhone</u></a></li>
</ul></div>

