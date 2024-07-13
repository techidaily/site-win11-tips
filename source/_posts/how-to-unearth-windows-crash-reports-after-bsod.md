---
title: How to Unearth Windows' Crash Reports After BSOD
date: 2024-07-12T17:00:35.375Z
updated: 2024-07-13T17:00:35.375Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unearth Windows' Crash Reports After BSOD
excerpt: This Article Describes How to Unearth Windows' Crash Reports After BSOD
keywords: Windows BSOD Logs,Find Windows Crash Reports,Access Post-BSOD Data,Post-Crash Diagnostics in Windows,Uncovering Windows Errors,BSOD Incident Investigation,Retrieving Windows Error Files
thumbnail: https://thmb.techidaily.com/4509b58b3a9a19b95f97977ea395ec0191792aea55bdaf18f72a70f3772092da.jpg
---

## How to Unearth Windows' Crash Reports After BSOD

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

### 2\. Find and Read the BSOD Log Files in the Registry Editor

 In case using the Event Viewer does not work for you for some reason, you can use another Windows utility to locate and study the BSOD log files—the Registry Editor.

 Windows Registry Editor is an administrative-level utility that lets you control how Windows operates and interacts with hardware and software. The Registry stores information related to the hardware and software components of your system. This information in the Registry is stored in the form of keys and values, and by modifying these with the dedicated Registry Editor, you can customize the operations of your system.

 Listed below are the steps for finding the BSOD log files in the Registry Editor. Make sure you are logged into your system as an administrator before you proceed.

1. Press the **Win + R** keys to open Run.
2. Type "regedit" in Run and press **Ctrl + Shift + Enter** to launch the Registry Editor as an administrator.
3. Now, select **Yes** in the User Account Prompt.
4. Once you are inside the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\CrashControl`
5. Next, move to the right pane and right-click on an empty space anywhere.
6. Choose **New** \> **DWORD (32-bit) Value**.  
![Create a new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/dword-policies.jpg)
7. Name this value as **DisplayParameters** and double-click on it.
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/easy-steps-enable-and-customize-widgets-on-win11/"><u>Easy Steps: Enable and Customize Widgets on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-latency-windows-discord-tweaks-for-speed/"><u>Clearing Up Latency: Windows Discord Tweaks for Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-interface-quick-menu-install/"><u>Enhancing Windows Interface: Quick Menu Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-in-hand-typing-enable-steps-on-windows/"><u>Unlock the Power of In-Hand Typing: Enable Steps on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-realme-v30-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Realme V30 for Parents | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-how-to-make-a-youtube-intro-video-2-ways/"><u>In 2024, How to Make A YouTube Intro Video [2 Ways]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-user-name-changes-for-w11-enthusiasts/"><u>Direct User Name Changes for W11 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-terminal-for-quake-environment/"><u>Accessing Windows Terminal for Quake Environment</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-interconnecting-platforms-sharing-tiktok-to-facebook/"><u>[New] 2024 Approved  Interconnecting Platforms  Sharing TikTok to Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-editing-the-windows-registry-via-terminal/"><u>Essential Tips for Editing the Windows Registry via Terminal</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-7-free-video-editing-programs-that-work-flawlessly/"><u>[New] 2024 Approved  7 Free Video Editing Programs That Work Flawlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlink-others-login-on-win-11/"><u>Unlink Others' Login on Win 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-c110-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from C110.</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-motorola-moto-g73-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Motorola Moto G73 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-data-security-activating-controlled-folder-access/"><u>Achieve Data Security: Activating Controlled Folder Access</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-journey-through-fantasy-on-android-the-15-best-games/"><u>2024 Approved  Journey Through Fantasy on Android  The 15 Best Games</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitters-guide-to-downloading-gifs-a-step-by-step-approach/"><u>[New] Twitter's Guide to Downloading GIFs  A Step-by-Step Approach</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-hidefake-snapchat-location-on-your-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Honor X50i+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-windows-to-dos-optimal-apps-compared/"><u>Top 6 Windows To-Dos: Optimal Apps Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-warmup-latency-top-tips-for-a-quicker-boot-up/"><u>Trim Down Warmup Latency – Top Tips for a Quicker Boot-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unbootable-windows-vms-via-vmware-in-win11/"><u>Eliminating Unbootable Windows VMs via VMware in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0x800713f-windows-11s-mail-woes/"><u>Unraveling Error Code 0X800713F: Windows 11'S Mail Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-fullscreen-crashes-in-sonic-adventure-for-windows-11/"><u>Combatting Fullscreen Crashes in Sonic Adventure for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-mail-alert-failures-with-9-practical-tips-for-windows-users/"><u>Fixing Mail Alert Failures with 9 Practical Tips for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-window-11-style-hacks-and-themes/"><u>Exclusive Window 11 Style Hacks & Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-improved-windows-tiling/"><u>Boost Productivity with Improved Windows Tiling</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-enhancing-click-through-high-roi-strategies-for-fb-animatons/"><u>[Updated] In 2024, Enhancing Click-Through  High-ROI Strategies for FB Animatons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-routines-to-reactivate-window-explorer/"><u>Easy Routines to Reactivate Window Explorer</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/y-central-the-best-laughter-inducing-channels-online/"><u>Comedy Central  The Best Laughter-Inducing Channels Online</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-inside-twitters-most-impactful-videos-of-the-year/"><u>[Updated] Inside Twitter's Most Impactful Videos of the Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-enhanced-functionality-with-ai-for-windows-11-users/"><u>Unveiling Enhanced Functionality with AI for Windows 11 Users</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-meme-masterpiece-wave/"><u>[Updated] Meme Masterpiece Wave</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-using-netstat-in-windows-11/"><u>A Comprehensive Tutorial: Using Netstat in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-clearsightcapture-straightforward-desktop-to-video-conversion/"><u>[New] In 2024, ClearSightCapture  Straightforward Desktop to Video Conversion</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-within-the-realm-of-graphic-editing-people-also-ask-how-to-add-emoji-to-photo-stay-tuned-to-walk-through-the-best-possible-solutions-in-the-it/"><u>2024 Approved Within the Realm of Graphic Editing, People Also Ask How to Add Emoji to Photo. Stay Tuned to Walk Through the Best Possible Solutions in the IT Market</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-imovie-beats-and-sounds/"><u>Mastering iMovie Beats and Sounds</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-advanced-insights-fullscreen-perfection-with-adobe-premiere/"><u>2024 Approved  Advanced Insights  Fullscreen Perfection with Adobe Premiere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-managing-your-network-proxy/"><u>Windows 11: Managing Your Network Proxy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-to-revive-windows-desktop-icons/"><u>Efficient Methods to Revive Windows Desktop Icons</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-insta-reels-with-tiktok-techniques-for-massive-shares/"><u>[Updated] Mastering Insta Reels with TikTok Techniques for Massive Shares</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-vivo-y77t-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Vivo Y77t to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-oculus-setup-issues-windows-11-and-10-solutions/"><u>Combat Oculus Setup Issues: Windows 11 & 10 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-directory-capacity-assessment-via-windows-powershell/"><u>Demystifying Directory Capacity Assessment via Windows PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-error-0xc00000f-in-windows-pcs/"><u>Understanding and Resolving Error 0Xc00000f in Windows PCs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-leveraging-vimeo-resources-add-excellent-video-content-to-your-ppts/"><u>2024 Approved  Leveraging Vimeo Resources  Add Excellent Video Content to Your PPTs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vivetool-blueprint-engaging-windows-companion/"><u>ViveTool Blueprint: Engaging Windows Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-swiftly-show-and-hide-directories-on-windows-11-pcs/"><u>Tips for Swiftly Show & Hide Directories on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-manage-your-windows-11-administrative-credentials/"><u>Efficiently Manage Your Windows 11 Administrative Credentials</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-the-path-to-profitable-fb-animation-ad-success-stories/"><u>2024 Approved  The Path to Profitable FB Animation Ad Success Stories</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-bring-photos-to-life-8-essential-animation-software/"><u>In 2024, Bring Photos to Life 8 Essential Animation Software</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-mastering-free2x-camera-recorder-features-for-2024/"><u>[Updated] Mastering Free2X Camera Recorder Features for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-nokia-105-classic-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Nokia 105 Classic Devices</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-trusted-recommendations-the-ultimate-10-for-real-time-tennis-and-rugby-viewing/"><u>In 2024, Trusted Recommendations  The Ultimate 10 for Real-Time Tennis and Rugby Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-w11-issues-with-csgo/"><u>Addressing W11 Issues with CS:GO</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/webcam-creation-video-making-for-mac-users/"><u>Webcam Creation  Video Making for Mac Users</u></a></li>
<li><a href="https://apple-account.techidaily.com/everything-to-know-about-apple-id-password-requirements-for-apple-iphone-15-by-drfone-ios/"><u>Everything To Know About Apple ID Password Requirements For Apple iPhone 15</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-the-secret-dark-mode-setting-in-win-11s-notepad/"><u>Unveil the Secret: Dark Mode Setting in Win 11'S Notepad</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-the-most-popular-android-apps-you-need-to-try/"><u>Updated 2024 Approved The Most Popular Android Apps You Need to Try</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-best-of-the-best-12-audio-converters-compared/"><u>The Best of the Best 12 Audio Converters Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-discovery-windows-11-pathway/"><u>Character Discovery: Windows 11 Pathway</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-xr-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone XR Data From iOS iTunes Backup? | Dr.fone</u></a></li>
</ul></div>
