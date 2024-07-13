---
title: Resetting Techniques for Faulty Resource Monitors on Windows 11
date: 2024-07-12T17:41:32.762Z
updated: 2024-07-13T17:41:32.762Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Techniques for Faulty Resource Monitors on Windows 11
excerpt: This Article Describes Resetting Techniques for Faulty Resource Monitors on Windows 11
keywords: Reset Resource Pro,Fix Monitor Errors,Win11 Monitor Recal,ReBoot System,Faulty Sysreset,Restore Monitordat,Win11 Techrecycle
thumbnail: https://thmb.techidaily.com/b8cf7f364a0eb33deca5de4b670b31137b8637ef9737c06562bbb999378e5773.jpg
---

## Resetting Techniques for Faulty Resource Monitors on Windows 11

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
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-apple-iphone-11-pro-max-to-computer-drfone-by-drfone-ios/"><u>How to Stream Apple iPhone 11 Pro Max to Computer? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-access-entry-error-in-microsoft-os/"><u>Disabling 'Access Entry' Error in Microsoft OS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-obsudios-analysis-selecting-the-ideal-recording-software/"><u>In 2024, Obsudio's Analysis  Selecting the Ideal Recording Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-3-fix-for-windows-10-nvidia-opengl/"><u>Addressing Error 3: Fix for Windows 10 Nvidia OpenGL</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/top-aspect-ratio-converters-for-a-seamless-viewing-experience-for-2024/"><u>Top Aspect Ratio Converters for a Seamless Viewing Experience for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-netstat-on-windows-11-a-guide-to-tracking-data-flow/"><u>Explore Netstat on Windows 11: A Guide to Tracking Data Flow</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-realme-narzo-n53-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Realme Narzo N53</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-windows-securitys-unexpected-error-in-windows-11-and-11/"><u>How to Fix Windows Security’s “Unexpected Error” In Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-flawed-icons-and-menu-items-on-win-1011/"><u>Mastery Over Flawed Icons and Menu Items on Win 10/11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-video-flip-in-no-time-expert-techniques-made-simple/"><u>New In 2024, Video Flip in No Time Expert Techniques Made Simple</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-quick-tips-for-crafting-and-perfecting-multisnapping-snapchat-stories/"><u>[New] 2024 Approved  Quick Tips for Crafting and Perfecting Multisnapping Snapchat Stories</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-bypass-activation-lock-on-iphone-8-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Bypass Activation Lock on iPhone 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-windows-error-unresponsive-audio-device-stopped/"><u>Eradicating Windows Error: Unresponsive Audio Device Stopped</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-optimal-yt-video-cover-images/"><u>2024 Approved  Optimal YT Video Cover Images</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-elevate-your-meetings-with-teamsnap-expertise/"><u>[New] In 2024, Elevate Your Meetings with TeamSnap Expertise</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-ultimate-guide-6-superior-apps-for-immediate-voice-transformation-for-2024/"><u>New Ultimate Guide 6 Superior Apps for Immediate Voice Transformation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-remote-connection-issues/"><u>Mastering Windows Remote Connection Issues</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-uncovering-inshots-edge-in-the-editing-world/"><u>In 2024, Uncovering InShot's Edge in the Editing World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-setting-up-windows-11s-pc-manager/"><u>A Step-by-Step Approach to Setting Up Windows 11'S PC Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-win-11-adjusting-proxy-preferences/"><u>Navigating Win 11: Adjusting Proxy Preferences</u></a></li>
<li><a href="https://change-location.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-vivo-y28-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-compression-errors-a-guide-to-fixed-zip-files-in-windows-11/"><u>Overcoming Compression Errors: A Guide to Fixed ZIP Files in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-audio-visual-connection-top-music-picks-that-elevate-your-diverse-video-projects-for-2024/"><u>New The Audio-Visual Connection Top Music Picks That Elevate Your Diverse Video Projects for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cross-platform-color-consistency/"><u>Mastering Cross-Platform Color Consistency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-task-managers-dynamic-speed-in-windows-11/"><u>Boost Task Manager's Dynamic Speed in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-lockout-duration-after-failed-logon-attempts-in-windows-11-and-11/"><u>How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-workflow-advanced-filters-and-theme-changes-in-task-manager-windows-11/"><u>Elevate Your Workflow: Advanced Filters & Theme Changes in Task Manager (Windows 11)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-video-directorship-with-powerdirector-24/"><u>[Updated] Mastering Video Directorship with PowerDirector '24</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-adobe-cloud-insights-and-best-non-adobe-choices/"><u>2024 Approved  Navigating Adobe Cloud, Insights & Best Non-Adobe Choices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-tracking-your-followers-departure/"><u>[Updated] Instagram  Tracking Your Followers' Departure</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-budget-friendly-strategies-to-infuse-text-and-video/"><u>[New] 2024 Approved  Budget-Friendly Strategies to Infuse Text & Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-print-spooler-service-is-not-running-error-in-windows/"><u>How to Fix “The Print Spooler Service Is Not Running” Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-adjust-your-photos-on-win-11-top-six-techniques-explored/"><u>Efficiently Adjust Your Photos on Win 11: Top Six Techniques Explored</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-honor-90-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Honor 90 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-pc-failures-due-to-unmet-intel-graphic-standards/"><u>Addressing PC Failures Due to Unmet Intel Graphic Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-11s-advanced-setup/"><u>Decoding Windows 11'S Advanced Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-robust-defense-how-to-upgrade-your-pin-in-windows-11/"><u>Achieving Robust Defense: How to Upgrade Your Pin in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resolve-rpc-fails-on-windows-os/"><u>Essential Steps to Resolve RPC Fails on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-productivity-the-essentials-of-using-flow-launcher/"><u>Accelerate Productivity: The Essentials of Using Flow Launcher</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-network-locked-oppo-f25-pro-5g-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Oppo F25 Pro 5G Phone?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-gateway-3-steps-to-direct-folder-entry-on-pc/"><u>Game Gateway: 3 Steps to Direct Folder Entry on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obsolete-windows-aesthetics-gone-for-good/"><u>Obsolete Windows Aesthetics, Gone for Good</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-gpresult-the-ultimate-gpo-report-tool/"><u>Exploring GPResult: The Ultimate GPO Report Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-11-with-these-top-6-android-apps/"><u>Elevate Your Windows 11 with These Top 6 Android Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-customization-in-windows-11-adding-directories/"><u>Mastering Customization in Windows 11: Adding Directories</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-savvy-screenshot-tactics-for-netflix-on-mac-a-complete-guide-of-six-ways-for-2024/"><u>[New] Savvy Screenshot Tactics for Netflix on Mac - A Complete Guide of Six Ways for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-and-disabling-windows-key-in-windows-os/"><u>Enabling and Disabling Windows Key in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructing-on-windows-copilot-through-vivetool/"><u>Instructing on Windows Copilot Through ViveTool</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-techniques-for-securing-snapchat-content-via-phone/"><u>2024 Approved  Techniques for Securing Snapchat Content via Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-full-battery-charge-notification-to-windows-10-and-11/"><u>How to Add a Full Battery Charge Notification to Windows 10 & 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-tips-for-crafting-professional-slug-line-notations-for-2024/"><u>Expert Tips for Crafting Professional Slug Line Notations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-macos-performance-through-windows-innovations/"><u>Boosting macOS Performance Through Windows Innovations</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-from-raw-audio-to-polished-masterpiece-editing-with-avidemux-2023-edition/"><u>Updated In 2024, From Raw Audio to Polished Masterpiece Editing with Avidemux - 2023 Edition</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-14-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on 14</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-craft-impeccable-sequences-editor-supreme-for-vimeo/"><u>[Updated] 2024 Approved  Craft Impeccable Sequences  Editor Supreme for Vimeo</u></a></li>
</ul></div>
