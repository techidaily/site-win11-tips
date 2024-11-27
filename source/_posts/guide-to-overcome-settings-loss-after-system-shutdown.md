---
title: Guide to Overcome Settings Loss After System Shutdown
date: 2024-11-22T17:47:57.293Z
updated: 2024-11-27T16:47:13.546Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Overcome Settings Loss After System Shutdown
excerpt: This Article Describes Guide to Overcome Settings Loss After System Shutdown
keywords: Save Settings Post-Shutdown Guide,Recover Lost System Preferences,Restore Default After Offline,Resetting OS Settings Effectively,Reinstating System Configs,Fixing Shutdown Settings Loss,Regain Settings After Power Down
thumbnail: https://thmb.techidaily.com/94f7e6bb0d500f60edc6e34b363527bd47bbfffa481cdc60b824492075830e06.jpg
---

## Guide to Overcome Settings Loss After System Shutdown

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to[create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 6\. Perform Some Generic Windows Fixes

 There are some general Windows-based fixes you can apply to fix this issue.

[Running your Windows computer in a Clean Boot state](https://www.makeuseof.com/clean-boot-windows-11/) is another way to fix the reset settings problem. Clean Boot helps you identify any third-party applications that might be causing the issue. It stops all non-Microsoft services and programs from running during startup, which helps you pinpoint the cause of the issue.

 If the methods mentioned earlier don't fix the issue,[consider doing a System Restore](https://www.makeuseof.com/windows-11-create-restore-point/) . This will take your computer back to a previous state when it was functioning well.

 Keep in mind that all files and applications installed after the selected restore point will be deleted. To avoid losing important data, create a backup before performing a System Restore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-maximizing-hd-playback-on-social-media-fb/"><u>[New] 2024 Approved Maximizing HD Playback on Social Media (FB)</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-your-guide-to-top-6-free-online-video-downloads/"><u>[New] 2024 Approved Your Guide to Top 6 Free, Online Video Downloads</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-arc-architect-suite-for-2024/"><u>[Updated] Arc Architect Suite for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-best-cameras-the-creme-de-la-crop-of-mobile-video-recorders-for-2024/"><u>[Updated] Best Cameras The Crème De La Crop of Mobile Video Recorders for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/best-mp4-video-players-compatible-with-all-devices-top-10-picks/"><u>Best MP4 Video Players Compatible with All Devices - Top 10 Picks</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-ram-limitations-on-your-windows-computer/"><u>Bypassing Ram Limitations on Your Windows Computer</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/comment-recuperer-les-fichiers-supprimes-dans-windows-xp-guide-detaille/"><u>Comment Récupérer Les Fichiers Supprimés Dans Windows XP - Guide Détaillé</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/connecting-apple-wireless-earbuds-to-your-nintendo-gaming-system/"><u>Connecting Apple Wireless Earbuds to Your Nintendo Gaming System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-windows-server-error-8-tips-for-clearing-no-servers-found-in-apex-legends-(156-chars/"><u>Conquer Windows Server Error: 8 Tips for Clearing No Servers Found in Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://tech-haven.techidaily.com/deciphering-codegpt-does-this-innovative-software-actually-compose-quality-code/"><u>Deciphering CodeGPT: Does This Innovative Software Actually Compose Quality Code?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-code-to-exit-s-mode-on-windows-systems/"><u>Deciphering the Code to Exit S Mode on Windows Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-best-ai-chatbot-tools-for-supporting-psychological-health-and-resilience/"><u>Discover the Best AI Chatbot Tools for Supporting Psychological Health and Resilience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-workflow-advanced-hotkeys-for-redoing-windows/"><u>Elevate Workflow: Advanced Hotkeys for Redoing Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-fast-apps-on-windows-11/"><u>Essential Strategies for Fast Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-chrome-back-from-the-dark-side/"><u>Getting Chrome Back From the Dark Side</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-wi-fi-connection-tackling-failed-prompts-on-windows/"><u>Mastering Wi-Fi Connection: Tackling Failed Prompts on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-graphics-memory-deficiency-in-virtual-schools-of-magic-and-sorcery/"><u>Resolving Graphics Memory Deficiency in Virtual Schools of Magic and Sorcery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-ms-store-apps-steps-for-windows-1011-users/"><u>Reviving MS Store Apps: Steps for Windows 10/11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-rockalldlldll-non-existence-on-pc/"><u>Steps to Tackle Rockalldll.dll Non-Existence on PC</u></a></li>
</ul></div>

