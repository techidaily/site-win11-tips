---
title: Steps for Resetting Windows Settings on Reboot
date: 2024-07-12T16:31:52.510Z
updated: 2024-07-13T16:31:52.510Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Resetting Windows Settings on Reboot
excerpt: This Article Describes Steps for Resetting Windows Settings on Reboot
keywords: Windows Reset Guide,Reboot Settings Restore,Windows Reboot Fix,System Reset Instructions,Reconfigure Windows Post-Reboot,Restart Options Explanation,Reset PC Windows Procedure
thumbnail: https://thmb.techidaily.com/8ac81d16fe79fad30026aca67e023b34a8f1d9b49b75551b82236c5ce76daa3d
---

## Steps for Resetting Windows Settings on Reboot

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
<li><a href="https://win11-tips.techidaily.com/1719301459575-the-keys-to-free-jumpstart-your-pc-with-unbeatable-windows-11-612lifetime/"><u>The Keys to Free: Jumpstart Your PC with Unbeatable Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/zooms-role-in-professional-podcast-recording-explained-for-2024/"><u>Zoom's Role in Professional Podcast Recording Explained for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-techniques-to-lower-audio-levels-in-os-xwindows/"><u>[New] Techniques to Lower Audio Levels in OS X/Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-workflow-customizing-windows-clipboard/"><u>Accelerated Workflow: Customizing Windows Clipboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ad-free-horizon-your-future-with-w11s-start-menu/"><u>Ad-Free Horizon: Your Future with W11's Start Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-with-efficient-cmd-commands-top-20/"><u>Accelerate Tasks with Efficient CMD Commands (Top 20)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-key-steps-to-reinstall-missing-optional-windows-features/"><u>7 Key Steps to Reinstall Missing Optional Windows Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-obs-studios-failed-to-connect-to-server-error-in-windows/"><u>7 Ways to Fix OBS Studio's Failed to Connect to Server Error in Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/going-against-the-tide-of-tradition-innovative-techniques-for-yt-rewinds-for-2024/"><u>Going Against the Tide of Tradition  Innovative Techniques for YT Rewinds for 2024</u></a></li>
<li><a href="https://ai-voice.techidaily.com/real-time-ai-voice-changer-revolutionizing-communication-for-2024/"><u>Real-Time AI Voice Changer Revolutionizing Communication for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382307115-addressing-wwinplusprint-error-on-your-computer-successfully/"><u>Addressing WWin+Print Error on Your Computer Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-hotkey-hits-unlock-maximum-auto-click-potential/"><u>5 Hotkey Hits: Unlock Maximum Auto Click Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-restoring-your-windows-11-media-softwares-health/"><u>A Guide to Restoring Your Windows 11 Media Software's Health</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-unrivaled-5-non-twitter-communities-online/"><u>[Updated] Unrivaled 5 Non-Twitter Communities Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-fingerprint-authentication-in-windows-11/"><u>Activating Fingerprint Authentication in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-11-safe-mode-6-routes-covered/"><u>Accessing Windows 11 Safe Mode: 6 Routes Covered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-success-winning-strategies-for-windows/"><u>Achieve Academic Success: Winning Strategies for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-temporarily-bypassing-windows-11s-safety-measures/"><u>A Quick Guide: Temporarily Bypassing Windows 11'S Safety Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-premium-zero-cost-windows-media-tools/"><u>7 Premium Zero-Cost Windows Media Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-capture-peak-performance-high-end-webcams-for-quality-live-streams-on-twitch/"><u>[Updated] In 2024, Capture Peak Performance  High-End Webcams for Quality Live Streams on Twitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-11-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreran-analysis-of-8-w11-design-choices/"><u>A Compreran Analysis of 8 W11 Design Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-razers-in-the-synapse-interface-of-win-11/"><u>Addressing Absence of Razers in the Synapse Interface of Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719262774069-your-on-premise-window-to-a-costless-chatgpt-clone-via-gpt4all/"><u>Your On-Premise Window to a Costless ChatGPT Clone via GPT4All.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-single-board-computers-that-run-windows/"><u>4 Single-Board Computers That Run Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-roadmap-for-smoother-files-transfer-in-win11-systems-1/"><u>A Roadmap for Smoother Files Transfer in WIN11 Systems (1)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-easyscreen-videotaker-analysis-plus-other-apps/"><u>[Updated] 2024 Approved  EasyScreen Videotaker Analysis + Other Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-creative-methods-for-cooling-your-pc/"><u>8 Creative Methods for Cooling Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-microsoft-project-keyboard-shortcuts/"><u>A Complete Guide to Microsoft Project Keyboard Shortcuts</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-snap-into-fun-step-by-step-guide-for-adding-gifs-in-conversations/"><u>[New] 2024 Approved  Snap Into Fun  Step-by-Step Guide for Adding Gifs in Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-administrative-control-settings-in-windows-11-devices/"><u>Addressing Administrative Control Settings in Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-high-scores-with-fc-mascot-for-zero-cost/"><u>Achieve High Scores with FC Mascot for Zero Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-loading-device-drivers-in-windows-11/"><u>Addressing Non-Loading Device Drivers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inconsistent-thx-sound-on-pcs/"><u>Addressing Inconsistent THX Sound on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatedarkinterfaceinnotepadwinoses/"><u>ActivateDarkInterfaceInNotepadWinOSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-for-switching-from-pin-to-passwords-in-windows-11-user-interface/"><u>A Guide for Switching From PIN to Passwords in Windows 11 User Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719383078548-unfreeze-handbrake-on-widows-effortlessly/"><u>Unfreeze HandBrake on Widows, Effortlessly!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-hang-error-dxgierrordevicehunk-on-windows/"><u>Addressing the HANG Error: DXGI_ERROR_DEVICE_HUNK on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ancient-windows-features-you-can-still-find-in-windows-11/"><u>7 Ancient Windows Features You Can Still Find in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-and-understanding-windows-component-services-interface/"><u>Accessing & Understanding Windows Component Services Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319856563-turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-hyper-v-on-your-windows-11-pc/"><u>Activating Hyper-V on Your Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-shown-pc-monitor-at-startup/"><u>Addressing Non-Shown PC Monitor at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276634403-microsoft-to-do-not-sync-here-are-easy-solutions/"><u>Microsoft To-Do Not Sync? Here Are Easy Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-harmony-with-googles-cross-platform-tool/"><u>Achieving Harmony with Google's Cross-Platform Tool</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-guide-to-forming-powerful-content-partnerships-on-youtube-for-2024/"><u>Essential Guide to Forming Powerful Content Partnerships on YouTube for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-simplified-process-for-posting-imovie-videos-on-vimeo-for-2024/"><u>[New] Simplified Process for Posting iMovie Videos on Vimeo for 2024</u></a></li>
</ul></div>
