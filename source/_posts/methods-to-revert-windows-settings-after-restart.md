---
title: Methods to Revert Windows Settings After Restart
date: 2024-07-12T16:42:54.611Z
updated: 2024-07-13T16:42:54.611Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Revert Windows Settings After Restart
excerpt: This Article Describes Methods to Revert Windows Settings After Restart
keywords: Windows Reset Guide,XP Settings Recovery,WinX Restart Restore,Safe Mode Fix Tools,System File Repair Win,Registry Tweaks Windows,Recovery Options Winx
thumbnail: https://thmb.techidaily.com/15566fd0d6cad9f26c793e08c16498fac2c5b48034aed23a907d05190328dc6a.png
---

## Methods to Revert Windows Settings After Restart

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

### 2\. Run Automatic Startup Repair

 If Windows continues to reset its settings upon reboot, you should try running the Automatic Startup Repair feature. This will help fix any system errors or corrupted files that may be causing the issue.

To run Automatic Startup Repair, follow these steps:

1. Press**Win + I** to open the Settings window.
2. From the left-hand menu, click the**System** tab.
3. On the right side of the window, scroll down and click the**Recovery** option.  
![Advanced startup in Recovery options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-startup-in-recovery-options.jpg)
4. Next to**Advanced startup** , click the**Restart now** button.
5. When your PC restarts, select**Troubleshoot** from the Choose an option screen.
6. Select**Advanced options** and then click**Startup Repair** .  
![Startup repair in Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/startup-repair-1.jpg)

 Follow the on-screen instructions to run the automatic repair tool. After you complete the above process, restart your computer and check if it solves the issue.

### 3\. Check Your User Profile

 If the issue persists, check your user profile and make sure it’s not corrupt. If your user profile is corrupted, Windows will reset the settings when you restart. Here’s how to check it:

 Press**Windows + R** to open the Run command. In the dialog box, type**regedit** , and press Enter. If the User Account Control (UAC) window appears, click**Yes** to grant administrative privileges. This will launch the Registry Editor.

On the next screen, navigate to the following path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`

 In the**ProfileList** folder, you should see several profiles starting with**S-1-5** . Each of these profiles corresponds to a user account on your computer. Now you have to identify which profile belongs to your user account.

 To do this, click on each**S-1-5 profile** and look for**ProfileImagePath** in the right pane. Check if anyone of them matches your username.

![Modify Registry to repair user profile](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-registry-to-repair-user-profile.jpg)

 Once you find the correct profile, double-click on the**State** field and change the value from**1 to 0** . Similarly, change the**RefCount** field from**1 to 0** .

 In case the RefCount field is missing in the right pane, you’ll have to create it manually. For this, right-click on the right pane and select**New > DWORD (32-bit) Value** . Name the new value**RefCount** and press**Enter** .

 Then double-click on the newly created RefCount and enter**0** in the Value data field. Click**OK** to save your changes and exit Registry Editor. After this, restart your computer and check whether the settings reset problem is fixed.

### 4\. Create a New User Profile

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to [create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

### 6\. Perform Some Generic Windows Fixes

 There are some general Windows-based fixes you can apply to fix this issue.

[Running your Windows computer in a Clean Boot state](https://www.makeuseof.com/clean-boot-windows-11/) is another way to fix the reset settings problem. Clean Boot helps you identify any third-party applications that might be causing the issue. It stops all non-Microsoft services and programs from running during startup, which helps you pinpoint the cause of the issue.

 If the methods mentioned earlier don't fix the issue,[consider doing a System Restore](https://www.makeuseof.com/windows-11-create-restore-point/) . This will take your computer back to a previous state when it was functioning well.

 Keep in mind that all files and applications installed after the selected restore point will be deleted. To avoid losing important data, create a backup before performing a System Restore.

## Fixing Windows Settings Reset on Reboot

 The Windows settings reset on reboot issue can occur for a number of reasons, including corrupt user profiles, corrupted installed programs or updates, and driver issues. This guide provides several methods to fix this issue. Check out these solutions and see which one work for you.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tackling-dxgi-failure-in-windows-fix-for-removed-devices/"><u>Tackling DXGI Failure in Windows: Fix for Removed Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-up-with-microsoft-sql-on-malwarebytes-after-disconnect/"><u>Syncing Up with Microsoft SQL on Malwarebytes After Disconnect</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-expert-approved-audio-editing-software-for-high-quality-productions-for-2024/"><u>Updated Expert-Approved Audio Editing Software for High-Quality Productions for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-enhance-your-online-skills-a-guide-to-youtube-editing-via-sony-vegas/"><u>[Updated] Enhance Your Online Skills  A Guide to YouTube Editing via Sony Vegas</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-addressing-the-myself-glitch-on-social-media-platforms/"><u>In 2024, Addressing the 'Myself' Glitch on Social Media Platforms</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-elevating-your-unboxing-craft-techniques-for-skyro-written-by-user/"><u>2024 Approved  Elevating Your Unboxing Craft  Techniques for Skyro Written by User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-power-to-edit-and-markup-in-windows-based-pdfs/"><u>Regain Power to Edit and Markup in Windows-Based PDFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-to-standard-power-plans-guide-for-win-11/"><u>Rebooting to Standard Power Plans: Guide for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-fn-key-tasks-in-windows-1011-oses/"><u>Tailoring FN Key Tasks in Windows 10/11 OSes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-techniques-to-effortlessly-record-your-instagram-experiences/"><u>2024 Approved  Techniques to Effortlessly Record Your Instagram Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-data-exchange-safeguarding-files-across-ws11w10/"><u>Silent Data Exchange: Safeguarding Files Across WS11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-languages-change-navigating-hotkeys-in-windows-11-and-11-pro/"><u>Quick Languages Change: Navigating Hotkeys in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlocking-youtubes-full-potential-with-top-video-formats/"><u>[New] Unlocking YouTube's Full Potential with Top Video Formats</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-passcode-from-iphone-14-complete-guide-drfone-by-drfone-ios/"><u>In 2024, How To Remove Passcode From iPhone 14? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-stalling-fixing-microsoft-teams-in-ws11ws10/"><u>Overcoming Stalling: Fixing Microsoft Teams in WS11/WS10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-window-11-interface-for-maximum-efficiency-and-satisfaction/"><u>Tailor Your Window 11 Interface for Maximum Efficiency and Satisfaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-administrative-tasks-a-new-approach-to-windows-uac/"><u>Streamlining Administrative Tasks: A New Approach to Windows UAC</u></a></li>
<li><a href="https://facebook.techidaily.com/analyzing-telegrams-sudden-spurt-amidst-social-media-crisis/"><u>Analyzing Telegram’s Sudden Spurt Amidst Social Media Crisis</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-streamline-team-conferencing-via-discords-screen-sharing/"><u>[New] 2024 Approved  Streamline Team Conferencing via Discord's Screen Sharing</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-your-apple-iphone-xr-from-your-apple-id-by-drfone-ios/"><u>How To Unlink Your Apple iPhone XR From Your Apple ID</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-clear-indicators-of-pc-needs-a-factory-start/"><u>Ten Clear Indicators of PC Needs a Factory Start</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-mastering-discord-stickers-your-ultimate-resource-for-2024/"><u>[New] Mastering Discord Stickers  Your Ultimate Resource for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bypass-oculus-setup-failures-in-windows-1110/"><u>Quick Guide to Bypass Oculus Setup Failures in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-synchronized-note-taking-in-windows-11/"><u>The Art of Synchronized Note-Taking in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-revolutionizing-audience-retention-on-youtube-with-these-top-6-techniques/"><u>[New] Revolutionizing Audience Retention on YouTube with These Top 6 Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-system-freeze-operation-failed-code-0x0000011b/"><u>Resolving System Freeze: Operation Failed Code 0X0000011B</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-silent-audio-devices-pc-edition/"><u>Revive Silent Audio Devices – PC Edition</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-oppo-a18-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Oppo A18 Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-explore-conceal-and-reveal-folders/"><u>Streamlining Windows Explore: Conceal and Reveal Folders</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-create-discord-logo-gif/"><u>Updated How to Create Discord Logo GIF</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-decoding-the-economic-incentives-behind-youtubes-shorts-programme/"><u>[Updated] 2024 Approved  Decoding the Economic Incentives Behind YouTube's Shorts Programme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-missing-d3dx939dll-in-win11/"><u>Steps to Fix Missing D3DX9_39.dll in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-signed-file-barrier-for-system-upgrades/"><u>Overcoming Non-Signed File Barrier for System Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-print-again-in-win11/"><u>Step-By-Step Guide to Print Again in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-common-snip-and-sketch-screenshot-hurdles-4-fixes/"><u>Sidestep Common Snip & Sketch Screenshot Hurdles: 4 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-windows-sound-preferences-intact/"><u>Strategies to Keep Windows Sound Preferences Intact</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-vivo-s17-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-a-guide-to-crafting-effective-youtube-backlinks/"><u>In 2024, A Guide to Crafting Effective YouTube Backlinks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-crafting-standout-youtube-thumbnails-with-ease/"><u>[New] 2024 Approved  Crafting Standout YouTube Thumbnails with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-update-processes-context-menu-update-option-for-win11-users/"><u>Streamlining Update Processes: Context Menu Update Option for Win11 Users</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-ultimate-guide-recording-your-youtube-livestreams/"><u>2024 Approved  Ultimate Guide  Recording Your YouTube Livestreams</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-melodies-meet-graphics-adding-soundtracks-to-powerpoint/"><u>[New] In 2024, Melodies Meet Graphics  Adding Soundtracks to PowerPoint</u></a></li>
</ul></div>
