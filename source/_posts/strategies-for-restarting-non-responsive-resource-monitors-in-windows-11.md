---
title: Strategies for Restarting Non-Responsive Resource Monitors in Windows 11
date: 2024-07-12T17:28:04.703Z
updated: 2024-07-13T17:28:04.703Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Restarting Non-Responsive Resource Monitors in Windows 11
excerpt: This Article Describes Strategies for Restarting Non-Responsive Resource Monitors in Windows 11
keywords: Win11 Resource Fix,Responsive Monitor Strategy,Non-Response Repair Tips,Resource Monitor Recovery,Windows Monitors Troubleshoot,Non-Responsive Fixes for Win11,Quick Monitor Restart Guide
thumbnail: https://thmb.techidaily.com/e5896cf8bd138a267d00eafc99f462dd02faf3099304ebd5a4c58885b5043e0a.jpg
---

## Strategies for Restarting Non-Responsive Resource Monitors in Windows 11

 Resource Monitor is a Windows utility that monitors the use and performance of your computer's hardware resources. Unfortunately, it sometimes stops working or encounters issues, making it difficult to track system performance and manage resource usage.

 So, if you're having trouble getting the Resource Monitor tool working on your computer, check out the steps below to troubleshoot any issues and get it up and running again.

## What Causes the Resource Monitor App to Stop Working?

 Before we dive into solving the problem, let's first check what causes the Resource Monitor app to stop working correctly. There are a few potential causes you should consider.

 The most common cause of Resource Monitor not working is corrupted or outdated drivers. Outdated or incorrect drivers can prevent the software from running properly and cause functionality errors. Additionally, if there are hardware issues with your computer, such as a faulty power supply or RAM, problems with Resource Monitor could also arise.

 Finally, if you have recently installed new antivirus software on your computer, it could block access to the Resource Monitor program.

So, let's move on to the solution and fix this problem.

## 1\. Restart the Computer
![windows restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restart.jpg)

 When troubleshooting software-related issues, a computer restart can often resolve them without resorting to complex solutions. Doing so refreshes all running programs and services while also clearing out any temporary files that might be causing problems.

 In most cases, this can get things back up and running without requiring extra effort. Plus, this solution is usually quick and easy since you only need to shut down your PC and wait for it to boot back up again. If you're having trouble restarting your PC, you can check out our guide on the [different ways you can restart Windows](https://www.makeuseof.com/windows-restart-methods/) .

## 2\. Change the DPI Settings

 Another possible fix for Resource Monitor not working on Windows is to change your DPI settings. Changing the scaling from 100% to 125% or higher on some computers can cause issues with Resource Monitor. Therefore, try adjusting it back to its original setting and check if the tool works again.

To change the DPI scale to its default settings, follow these steps:

1. Press**Win + I** on your keyboard to [open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. From the left pane, select**System** .
3. Then click**Display** on the right.
4. Under the**Scale & layout** section, click the drop-down menu next to the**Scale** option.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
5. Choose the recommended value.

 Once you have made the changes, close the Settings window and run the Resource Monitor app to see if the problem is resolved.

## 3\. Run the System File Checker

 If restarting your computer and changing the DPI settings didn't work, running an SFC scan can often detect and repair any corrupted system files that might be causing problems.

To do this, follow these steps:

1. Right-click on Start and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. When the UAC popup appears on the screen, click**Yes** to open Command Prompt with admin access. If you want in-depth information, read our guide on [running the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. Now in the elevated Command Prompt window, type in the command below and press Enter:  
sfc /scannow
5. Wait for the process to complete, then restart your PC.

## 4\. Check for Windows Updates

 It is also possible for an outdated version of Windows to cause this issue, so [manually check for any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) and install them.

 Microsoft regularly releases new versions of Windows that fix bugs and improve performance, which makes updating worthwhile. Here's how to do it:

1. Press**Win + I** on your keyboard to launch the System Settings.
2. From the left side of the Settings menu, click**Windows Update** .
3. When Windows Update opens, click the**Check for updates** button.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)

 If there are any updates available, it will download and install them automatically. After the download completes, install the updates and restart your computer. After that, check to see if Resource Monitor is working.

## 5\. Uninstall the Latest Windows Updates

 If you recently updated your OS and there are no newer updates for it, the last update might have caused the issue. So, try uninstalling any recent update you may have installed, which could help resolve conflicts between the updates and existing system files that are causing problems with Resource Monitor.

1. Press**Win + I** on your keyboard to open the Settings menu
2. Select**Windows Update** from the left pane
3. Now go to the right and click on**Update history** .  
![Update history in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-history-in-windows-update.jpg)
4. Scroll down to Related settings and click**Uninstall updates** .  
![Uninstall the latest Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-the-latest-windows-update.jpg)

 Then select any recent updates that you want to uninstall. After that, restart your computer and check if Resource Monitor is now working properly.

## 6\. Create a New User Account

 If you're still having issues, try [creating a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) and see if that fixes the issue. This can be helpful if corrupted user profile data or settings cause the problem. To do so, follow the steps below:

1. Open the Settings app on your computer.
2. From the left, select**Accounts** .
3. Click**Other users** under Account settings.
4. Next to Add other users, click**Add account** .  
![Create a New User Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-a-new-user-account.jpg)
5. On the Microsoft account page, click **I don't have this person's sign-in information** .

 Then follow the instructions to add a new user account and then sign in with that account. Now open Resource Monitor and see if it's working properly.

## 7\. Troubleshoot in Clean Boot State

 When all else fails, try starting your computer in safe mode and see if the problem persists. If it does not, then background services and applications are possibly conflicting with startup items and causing this error to occur.

In such a case, you need to perform a clean boot as instructed below:

1. Open the**Run** dialog box.
2. Type**MSConfig** in the text box and hit Enter.
3. Check the**Selective startup** box on the General tab.  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
4. Uncheck the**Load startup items** box.
5. Switch to the**Services** tab and check the**Hide all Microsoft services** box.  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
6. Then click**Disable All** .
7. Go to the Startup tab and click the**Open Task Manager** link
8. Disable any services or programs that are active in Startup apps.

 Once you have done this, close Task Manager, then click**OK** on the MSConfig window to save these changes. Now restart your computer for them to take effect, then try using Resource Monitor to see if they work now.

## Resolve Resource Monitor Issues in Windows 11

 Resource Monitor helps you monitor the performance and usage of your system's resources, including memory, disk, and network activity. If you're having trouble accessing this tool, this guide may help.


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
<li><a href="https://youtube-sure.techidaily.com/ed-harness-the-power-of-playback-speed-control-in-youtube-for-2024/"><u>[Updated] Harness the Power of Playback Speed Control in YouTube for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-windows-10s-prime-video-grabbing-solutions-ranked/"><u>[New] In 2024, Windows 10'S Prime Video Grabbing Solutions Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-door-on-stuck-wow-61-patches/"><u>Unlocking the Door on Stuck WoW 6.1 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/put-a-halt-on-application-start-tracking-in-windows/"><u>Put a Halt on Application Start-Tracking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-csgo-launch-failures-on-w11/"><u>Troubleshooting CS:GO Launch Failures on W11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-tailor-made-video-cuts-macs-top-mp4-slicers-revealed/"><u>[New] In 2024, Tailor-Made Video Cuts  Mac's Top MP4 Slicers Revealed</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-make-a-slow-motion-video-in-wondershare-filmora/"><u>How to Make a Slow Motion Video in Wondershare Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-mute-microphone-issue-during-video-recordings/"><u>Tackling Mute Microphone Issue During Video Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-disabling-xbox-game-pass-error/"><u>Mastering the Art of Disabling Xbox Game Pass Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-window-into-evolution-noteworthy-windows-11-file-enhancements/"><u>A Window Into Evolution: Noteworthy Windows 11 File Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-magic-automating-archive-creation-in-windows/"><u>Command Line Magic: Automating Archive Creation in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Motorola Edge 40 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-reactivating-deactivated-voice-command/"><u>Addressing Windows 11: Reactivating Deactivated Voice Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surreptitious-shutdown-strategy-for-windows-11/"><u>Surreptitious Shutdown Strategy for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-the-dxgidll-file-missing-in-windows-11-heres-how-to-fix-it/"><u>Is the Dxgi.dll File Missing in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-external-disk-into-explorer-nav-pane/"><u>Incorporating External Disk Into Explorer Nav Pane</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-up-your-device-instantly-mastering-win-11s-double-clicked-apk-method/"><u>Power Up Your Device Instantly: Mastering Win 11'S Double-Clicked APK Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-depths-of-diablos-first-adventure/"><u>Navigating the Depths of Diablo's First Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-page-lockout-in-windows-systems/"><u>Overcoming Page Lockout in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-widely-used-directx-classics-through-dxvk/"><u>Upgrading Widely-Used DirectX Classics Through DXVK</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-initiate-sfc-process-in-windows-1087/"><u>Steps to Initiate SFC Process in Windows 10/8/7</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlock-your-youtube-shorts-earnings-potential/"><u>[New] Unlock Your YouTube Shorts Earnings Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-terminal-configuration-basics/"><u>Mastering Windows Terminal Configuration Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-spectrum-mastering-windows-network-adapter-assessment-methods/"><u>Speed Spectrum: Mastering Windows' Network Adapter Assessment Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-hurdles-of-xbox-game-pass-error-code-0-essential-tips-for-windows-11-users/"><u>Avoiding the Hurdles of Xbox Game Pass Error Code 0: Essential Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-spot-and-dismantle-unused-windows-folders-easily/"><u>How to Spot & Dismantle Unused Windows Folders Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-fixing-the-msvcr110dll-gap/"><u>Uncovering & Fixing the Msvcr110.dll Gap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/income-streams-from-windows-11-an-examination/"><u>Income Streams From Windows 11: An Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resetting-windows-settings-on-reboot/"><u>Steps for Resetting Windows Settings on Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-variance-in-procedures-for-local-and-remote-windows-reinstallations/"><u>Analyzing the Variance in Procedures for Local and Remote Windows Reinstallations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-routes-to-windows-control-panel-entry/"><u>Unveiling the Routes to Windows Control Panel Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-windows-safety-edge-context-menu-firewall-customization-guide/"><u>Sharpen Windows Safety Edge: Context Menu Firewall Customization Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-nubia-red-magic-9-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Nubia Red Magic 9 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-15-pro-max-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 15 Pro Max To Other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-lost-dxgidll-with-these-win11-hacks/"><u>Restore Your Lost Dxgi.dll with These Win11 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Avoidance of Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-the-delay-in-windows-11-adoption/"><u>Unpacking the Delay in Windows 11 Adoption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-mouse-controls-in-win11-effortlessly/"><u>Navigating Mouse Controls in Win11 Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovate-your-experience-avoiding-common-pitfalls-in-windows-11/"><u>Innovate Your Experience: Avoiding Common Pitfalls in Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-picsnapper-app-testimonials-and-feedback/"><u>[Updated] In 2024, PicSnapper App Testimonials & Feedback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-window-11-screens-a-comprehensive-wallpaper-plan/"><u>Tailoring Window 11 Screens: A Comprehensive Wallpaper Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-pathways-open-directory-games-in-windows/"><u>The Hidden Pathways: Open Directory Games in Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-10-tiktok-trends-in-video-responses/"><u>In 2024, 10 TikTok Trends in Video Responses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-file-denial-in-steam-for-windows-11-users/"><u>Tackling File Denial in Steam for Windows 11 Users</u></a></li>
</ul></div>
