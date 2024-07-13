---
title: "Blue Screen Errors: Finding Their Windows Footprint"
date: 2024-07-12T18:08:21.001Z
updated: 2024-07-13T18:08:21.001Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Blue Screen Errors: Finding Their Windows Footprint"
excerpt: "This Article Describes Blue Screen Errors: Finding Their Windows Footprint"
keywords: Blue Screens Woes,Win Error Fixing,Debugging Blues,System Crash Guide,PC Blue Outage,Fixing Screen Fail,Windows Troubleshoot
thumbnail: https://thmb.techidaily.com/14af88c4727edfc68754682f8d9e5a16b4632ead51b56f451896cf5d83dd52e4.jpg
---

## Blue Screen Errors: Finding Their Windows Footprint

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ffmpeg-and-its-role-in-preserving-natural-auditory-formats/"><u>2024 Approved  FFmpeg and Its Role in Preserving Natural Auditory Formats</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-how-to-add-music-to-instagram-story/"><u>2024 Approved  How to Add Music to Instagram Story?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-file-management-using-checkbox-for-selections-in-win11/"><u>Boost File Management: Using Checkbox for Selections in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-your-quake-experience-via-terminal/"><u>Beginning Your Quake Experience via Terminal</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oppo-find-n3-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Oppo Find N3 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-guide-to-extend-windows-10-shutdown-duration/"><u>Advanced Guide to Extend Windows 10 Shutdown Duration</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/cultivating-a-thriving-business-model-with-snapchat-insights-for-2024/"><u>Cultivating a Thriving Business Model with Snapchat Insights for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-broadcast-your-xbox-adventures-online/"><u>In 2024, Broadcast Your Xbox Adventures Online</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-lost-files-from-xiaomi-redmi-k70-by-fonelab-android-recover-data/"><u>How to retrieve lost files from Xiaomi Redmi K70?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-closing-powerhouses-free-top-6-video-closers-for-2024/"><u>[Updated] Closing Powerhouses  Free Top 6 Video Closers for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-elevate-zoom-outputs-top-3-transformer-tactics/"><u>[Updated] In 2024, Elevate Zoom Outputs  Top 3 Transformer Tactics</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-social-media-success-strategies-for-effective-facebook-reel-creation-for-2024/"><u>[New] Social Media Success  Strategies for Effective Facebook Reel Creation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-winerror-740-easy-to-follow-tips-for-windows-users/"><u>Avoiding WinError 740: Easy-to-Follow Tips for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-shortcuts-fast-paste-of-set-text/"><u>Advanced Shortcuts: Fast Paste of Set Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/app-aesthetics-the-hidden-culprits-in-windows-11-performance-drop/"><u>App Aesthetics: The Hidden Culprits in Windows 11 Performance Drop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-insight-with-elevated-task-manager-access-on-win11/"><u>Boosting System Insight with Elevated Task Manager Access on Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/easy-guide-to-youtube-livestreaming-from-google-meet-for-2024/"><u>Easy Guide to YouTube Livestreaming From Google Meet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-steam-authentication-setbacks-in-rust-for-windows-users/"><u>Avoiding Steam Authentication Setbacks in Rust for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-to-the-latest-windows-11-maintain-linux-subsystem-efficiency/"><u>Adjusting to the Latest Windows 11, Maintain Linux Subsystem Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-in-win11-with-custom-cmd-commands/"><u>Boosting Efficiency in Win11 with Custom Cmd Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-by-rebooting-windows-11-ram/"><u>Boost Performance by Rebooting Windows 11 RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-network-settings-a-guide-for-win11/"><u>Adjust Network Settings: A Guide for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-privilege-levels-for-non-administrators-on-windows-os/"><u>Altering Privilege Levels for Non-Administrators on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-file-disposal-in-windows-for-efficiency-gains/"><u>Automate File Disposal in Windows for Efficiency Gains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-pen-tablet-glitches-and-freezes/"><u>Addressing Windows PEN Tablet Glitches and Freezes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-for-picture-adjustment-on-windows-11-unveiled/"><u>Advanced Techniques for Picture Adjustment on Windows 11 Unveiled</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-ways-to-recover-deleted-files-from-xiaomi-redmi-note-13-proplus-5g-by-fonelab-android-recover-data/"><u>Possible ways to recover deleted files from Xiaomi Redmi Note 13 Pro+ 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-search-and-highlight-settings/"><u>Adjusting Your Window's Search and Highlight Settings</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-voice-reinvention-with-technology-rankings-of-7-innovative-audio-tools/"><u>In 2024, Voice Reinvention with Technology  Rankings of 7 Innovative Audio Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-insights-into-income-average-earnings-per-advertisement-playback/"><u>[New] Insights Into Income  Average Earnings per Advertisement Playback?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-digital-experience-adding-directories-to-taskbar-menu/"><u>Amplify Your Digital Experience: Adding Directories to Taskbar Menu</u></a></li>
<li><a href="https://youtube-web.techidaily.com/igh-performance-gpu-picks-for-quality-video-streaming/"><u>[New] High-Performance GPU Picks for Quality Video Streaming</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-nokia-105-classic-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-comprehensive-list-of-free-outro-music-archives-no-copyright-for-2024/"><u>Updated Comprehensive List of Free Outro Music Archives (No Copyright) for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-prohero-vs-nikkor-km-170-which-reigns-supreme/"><u>[Updated] ProHero vs Nikkor KM-170  Which Reigns Supreme?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-s15-oled-experience-merging-chic-and-versatile-features/"><u>Asus S15 OLED Experience: Merging Chic & Versatile Features</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-slash-length-amplify-impact-youtube-video-editing-for-2024/"><u>[Updated] Slash Length, Amplify Impact  YouTube Video Editing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-code-ai-reshaping-windows-tech-landscape/"><u>Beyond Code: AI Reshaping Windows Tech Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unauthorized-profiles-on-pcs-win1011-guide/"><u>Addressing Unauthorized Profiles on PCs: Win10/11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-fn-key-behavior-for-efficiency/"><u>Altering Windows Fn Key Behavior for Efficiency</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-making-history-shine-again-instagram-effects-for-your-archive/"><u>[New] In 2024, Making History Shine Again  Instagram Effects for Your Archive</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/maximizing-data-retrieval-total-facebook-archive-acquisition/"><u>Maximizing Data Retrieval: Total Facebook Archive Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-crashing-keep-your-file-explorer-fixed-in-windows-11/"><u>Avoid Crashing: Keep Your File Explorer Fixed in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/technical-tangle-printer-reconfigured-incorrectly/"><u>Technical Tangle: Printer Reconfigured Incorrectly</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>