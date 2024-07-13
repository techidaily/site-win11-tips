---
title: Strategies for Reducing System Resource Utilization by Services
date: 2024-07-12T16:48:27.273Z
updated: 2024-07-13T16:48:27.273Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Reducing System Resource Utilization by Services
excerpt: This Article Describes Strategies for Reducing System Resource Utilization by Services
keywords: Reduce Resource Usage,Service Efficiency Boost,Optimize System Resources,Minimize Service Footprint,Energy-Saving Strategies,Performance Enhancement Tactics,Service Resource Management
thumbnail: https://thmb.techidaily.com/756e6cbc4b4a2e3ac30671657870528bb336d9b2f0f8b2cf5d7bebdde4893059.jpg
---

## Strategies for Reducing System Resource Utilization by Services

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-popular-rainmeter-problems-in-windows-systems/"><u>Troubleshooting Popular Rainmeter Problems in Windows Systems</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-tecno-spark-10-pro-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Tecno Spark 10 Pro to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-affected-device-access-post-error-code-22/"><u>How to Reset Affected Device Access Post-Error Code 22</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/social-syncopation-hot-tiktok-moves-for-everyone/"><u>Social Syncopation  Hot TikTok Moves for Everyone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-comprehensive-guide-to-ios-screenshotting/"><u>[Updated] Comprehensive Guide to iOS Screenshotting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-the-ultimate-guide-to-boosting-tiktok-traction/"><u>In 2024, The Ultimate Guide to Boosting TikTok Traction</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-honor-90-lite-frp-by-drfone-android/"><u>How Can We Bypass Honor 90 Lite FRP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/navigating-the-complexities-of-facebook-slideshow-tools-for-2024/"><u>Navigating the Complexities of Facebook Slideshow Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-install-microsoft-defender-application-guard-for-edge-in-windows-11/"><u>How to Install Microsoft Defender Application Guard for Edge in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-windows-printer-performance/"><u>Turbo-Charging WIndows Printer Performance</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-video-repair-tool-to-fix-and-repair-corrupt-mp4-mov-avi-video-files-of-realme-c67-4g-by-stellar-video-repair-mobile-video-repair/"><u>Best Video Repair tool to Fix and Repair Corrupt MP4,MOV,AVI video files of Realme C67 4G</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-poco-m6-pro-4g-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Poco M6 Pro 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11s-non-functional-function-keys-for-brightness/"><u>Fixing Windows 11'S Non-Functional Function Keys for Brightness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-instant-uninstalling-via-windows-shortcuts/"><u>The Guide to Instant Uninstalling via Windows Shortcuts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-enhancing-meet-visuals-applying-filters-effects-and-masks-for-2024/"><u>[New] Enhancing Meet Visuals  Applying Filters, Effects & Masks for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-innovative-ways-to-earn-on-snapchat/"><u>[New] 2024 Approved  Innovative Ways to Earn on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-shortage-of-physical-storage-space-vm-errors/"><u>Resolving Shortage of Physical Storage Space (VM) Errors</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-1-free-top-10-best-android-video-editors/"><u>New 2024 Approved 1-FREE Top 10 Best Android Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-sound-level-configurations-in-windows/"><u>Restoring Default Sound Level Configurations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-calendar-app-on-windows-11/"><u>How to Use the Calendar App on Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/optimal-hd-video-memory-creators/"><u>Optimal HD Video Memory Creators</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-your-story-with-immersive-youtube-video-editing-tips-for-2024/"><u>Craft Your Story with Immersive YouTube Video Editing Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-no-write-error-a-guide-for-windows-users/"><u>Tackling the No Write Error: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-route-to-your-windows-disk-space-win-1011/"><u>Quick Route to Your Windows Disk Space (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-explorer-onedrive-as-a-launchpad/"><u>Mastering File Explorer: OneDrive as a Launchpad</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-brightening-up-your-online-videos/"><u>2024 Approved  Brightening Up Your Online Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-unveiling-the-finest-free-online-recorders-top-picks/"><u>[Updated] In 2024, Unveiling the Finest Free Online Recorders – Top Picks</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-from-fcp-to-vhs-easy-techniques-for-a-retro-look/"><u>New In 2024, From FCP to VHS Easy Techniques for a Retro Look</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/camera-essentials-for-adventure-videographers/"><u>Camera Essentials for Adventure Videographers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-file-explorer-in-windows-10plus/"><u>Jumpstart File Explorer in Windows 10+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-vlc-unrecognized-media-issue/"><u>Overcoming Windows VLC Unrecognized Media Issue</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/using-srt-audio-on-windows-and-macos-devices-for-2024/"><u>Using SRT Audio on Windows & macOS Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-x80072f30-in-windows/"><u>Resolving Microsoft Store Error X80072F30 in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-a-review-10-most-effective-methods-for-live-cricket-streaming/"><u>[Updated] A Review  10 Most Effective Methods for Live Cricket Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-autofocus-on-iphone-cameras-efficiently/"><u>[Updated] Mastering Autofocus on iPhone Cameras Efficiently</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-14-pro-max-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>How to Unlock Apple iPhone 14 Pro Max With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/your-daily-dose-of-joy-top-15-online-anime-shows/"><u>Your Daily Dose of Joy  Top 15 Online Anime Shows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-outlook-rules-not-working-on-windows/"><u>How to Fix Outlook Rules Not Working on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-clis-for-efficient-task-management-windows-11/"><u>Integrating CLIs for Efficient Task Management (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-disruptions-caused-by-new-windows-updates/"><u>How to Bypass Disruptions Caused by New Windows Updates</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-essential-seo-handbook-for-podcast-success/"><u>[New] The Essential Seo Handbook for Podcast Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-streamline-editing-with-these-10-leading-software-tools/"><u>[Updated] 2024 Approved  Streamline Editing with These 10 Leading Software Tools</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-data-from-iphone-15-pro-max-using-stellar-data-recovery-for-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Data from iPhone 15 Pro Max using Stellar Data Recovery for iPhone? | Stellar</u></a></li>
<li><a href="https://facebook.techidaily.com/is-facebook-set-to-sever-ties-with-giphy-soon/"><u>Is Facebook Set to Sever Ties with Giphy Soon?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-securing-your-pc-gaming-memories-best-techniques/"><u>[New] In 2024, Securing Your PC Gaming Memories  Best Techniques</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-constructing-captivating-youtube-music-selections/"><u>[Updated] Constructing Captivating YouTube Music Selections</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-safest-free-software-download-sites-for-windows/"><u>The 10 Safest Free Software Download Sites for Windows</u></a></li>
</ul></div>
