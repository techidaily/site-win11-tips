---
title: Avoid Unwanted Updates in Windows 11 with Proactive Measures
date: 2024-07-12T18:08:27.609Z
updated: 2024-07-13T18:08:27.609Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoid Unwanted Updates in Windows 11 with Proactive Measures
excerpt: This Article Describes Avoid Unwanted Updates in Windows 11 with Proactive Measures
keywords: Win11 Update Prevention,Avoiding WS11 Changes,Proactive PC Tips,Guarding Updates WS11,Secure Windows Updates,Stable OS Maintenance,Minimize WS11 Fixes
thumbnail: https://thmb.techidaily.com/657c6ed7c4c5009fda7b9debb5d0440f9ba124b99f1e715f38abd38365f6151e.png
---

## Avoid Unwanted Updates in Windows 11 with Proactive Measures

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.
9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/boost-windows-flexibility-with-additional-menus/"><u>Boost Windows Flexibility with Additional Menus</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-universal-approach-how-to-record-any-youtube-stream-on-different-devices/"><u>[Updated] 2024 Approved  Universal Approach  How To Record Any YouTube Stream on Different Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-essential-wsl-2-approaches-for-win-users/"><u>Boost Performance: Essential WSL 2 Approaches for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-network-settings-a-guide-for-win11/"><u>Adjust Network Settings: A Guide for Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-essential-ios-resources-for-enjoying-psp-games/"><u>2024 Approved  Essential iOS Resources for Enjoying PSP Games</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/egies-for-securely-amassing-one-million-video-watches-for-2024/"><u>Strategies for Securely Amassing One Million Video Watches for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-for-picture-adjustment-on-windows-11-unveiled/"><u>Advanced Techniques for Picture Adjustment on Windows 11 Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-guide-to-extend-windows-10-shutdown-duration/"><u>Advanced Guide to Extend Windows 10 Shutdown Duration</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-oppo-find-x7-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Oppo Find X7 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-s15-oled-experience-merging-chic-and-versatile-features/"><u>Asus S15 OLED Experience: Merging Chic & Versatile Features</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-mastering-aspect-ratio-compliance-in-micro-video-tweets/"><u>[New] In 2024, Mastering Aspect Ratio Compliance in Micro-Video Tweets</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-flip-your-tiktok-videos-a-comprehensive-guide-to-reversing-clips/"><u>New 2024 Approved Flip Your TikTok Videos A Comprehensive Guide to Reversing Clips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-privilege-levels-for-non-administrators-on-windows-os/"><u>Altering Privilege Levels for Non-Administrators on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-file-disposal-in-windows-for-efficiency-gains/"><u>Automate File Disposal in Windows for Efficiency Gains</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-vrecorder-integration-from-download-to-deployment/"><u>In 2024, VRecorder Integration  From Download to Deployment</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/reset-itunes-backup-password-of-apple-iphone-6-prevention-and-solution-drfone-by-drfone-ios/"><u>Reset iTunes Backup Password Of Apple iPhone 6 Prevention & Solution | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-automatic-windows-updates/"><u>Banishing Automatic Windows Updates</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/constructing-chat-hangout-zones-on-whatsapp/"><u>Constructing Chat Hangout Zones on WhatsApp</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-ultimate-5-choice-of-online-meeting-recorder-gadgets-for-2024/"><u>[New] Ultimate 5 Choice of Online Meeting Recorder Gadgets for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-digital-experience-adding-directories-to-taskbar-menu/"><u>Amplify Your Digital Experience: Adding Directories to Taskbar Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-these-5-unique-windows-pc-time-saver-tools/"><u>Boost Productivity with These 5 Unique Windows PC Time Saver Tools</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-leading-edge-top-10-advanced-vimeo-video-extraction-sites/"><u>2024 Approved  Leading Edge  Top 10 Advanced Vimeo Video Extraction Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-winerror-740-easy-to-follow-tips-for-windows-users/"><u>Avoiding WinError 740: Easy-to-Follow Tips for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-file-management-using-checkbox-for-selections-in-win11/"><u>Boost File Management: Using Checkbox for Selections in Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtubes-next-gen-streaming-made-easy-with-obs-tutorial/"><u>2024 Approved  Youtube's Next Gen Streaming Made Easy with OBS Tutorial</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/best-voice-conversion-tools-for-vlogging-professionals-for-2024/"><u>Best Voice Conversion Tools for Vlogging Professionals for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-step-by-step-an-essential-tutorial-on-editing-your-first-podcast/"><u>2024 Approved Step-by-Step An Essential Tutorial on Editing Your First Podcast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-code-ai-reshaping-windows-tech-landscape/"><u>Beyond Code: AI Reshaping Windows Tech Landscape</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-make-your-comments-pop-with-emojis-in-youtube/"><u>2024 Approved  Make Your Comments Pop with Emojis in YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-insight-with-elevated-task-manager-access-on-win11/"><u>Boosting System Insight with Elevated Task Manager Access on Win11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/perfecting-subtitles-in-media-ultimate-list-of-on-line-aid-sources/"><u>Perfecting Subtitles in Media  Ultimate List of On-Line Aid Sources</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blue-screen-errors-finding-their-windows-footprint/"><u>Blue Screen Errors: Finding Their Windows Footprint</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-essential-5-chrome-extensions-seamlessly-access-facebook-videos-for-2024/"><u>[Updated] Essential 5 Chrome Extensions  Seamlessly Access Facebook Videos for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-phone-without-google-account-by-drfone-android/"><u>How to Unlock Realme Phone without Google Account?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/androidwindows-twinning-effortless-sync-instructions/"><u>Android/Windows Twinning: Effortless Sync Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-to-the-latest-windows-11-maintain-linux-subsystem-efficiency/"><u>Adjusting to the Latest Windows 11, Maintain Linux Subsystem Efficiency</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-evaluating-the-efficacy-of-aurora-hdr-technology/"><u>In 2024, Evaluating the Efficacy of Aurora HDR Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-shortcuts-fast-paste-of-set-text/"><u>Advanced Shortcuts: Fast Paste of Set Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-pen-tablet-glitches-and-freezes/"><u>Addressing Windows PEN Tablet Glitches and Freezes</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Motorola G24 Power? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>