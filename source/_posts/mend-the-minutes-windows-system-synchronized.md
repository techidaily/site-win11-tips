---
title: "Mend the Minutes: Windows System Synchronized"
date: 2024-07-12T16:38:48.288Z
updated: 2024-07-13T16:38:48.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mend the Minutes: Windows System Synchronized"
excerpt: "This Article Describes Mend the Minutes: Windows System Synchronized"
keywords: TimeSync Windows,WinSync Moments,Sync Window OS,TimedSync Windows,Windows SyncedTime,MinuteSync Windows,WindowsMomentSync
thumbnail: https://thmb.techidaily.com/9be41d62e85e6d9d35faed892e42e95be3740ff6798e8e9db724143c55700cdb.png
---

## Mend the Minutes: Windows System Synchronized

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)

 Once the service is restarted, close the window and check the time synchronization.

## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new string value **ServerX**, where X is the server number.
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Now click **Scan now** to initiate a full scan.

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-samsung-galaxy-z-flip-5-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Samsung Galaxy Z Flip 5 to iPod | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-oppo-reno-11-pro-5g-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-xiaomi-redmi-12-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Xiaomi Redmi 12 Phone Screen?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-workflow-paste-and-mouse-jump-techniques/"><u>Accelerate Workflow: Paste & Mouse Jump Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-troubleshooting-steps-for-internal-error-on-windows-1111-pro/"><u>Essential Troubleshooting Steps for Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-laptop-or-desktops-past/"><u>Unraveling Windows Laptop or Desktop's Past</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipmagic-disrupted-methods-to-reset-and-revive/"><u>SnipMagic Disrupted? Methods to Reset and Revive</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/liberate-your-devices-free-macwin-screenshots/"><u>Liberate Your Devices  FREE Mac/Win Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-constant-edge-activity-in-windows-11/"><u>Understanding Constant Edge Activity in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-leading-online-resources-to-elevate-auditory-quality/"><u>New In 2024, Leading Online Resources to Elevate Auditory Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-chrome-on-a-windows-desktop/"><u>Unblocking Chrome on a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-glitches-to-ensure-smooth-gameplay-on-windows-11/"><u>Tackling Steam Glitches to Ensure Smooth Gameplay on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-installation-privilege-denial-problem/"><u>Solving Windows Installation Privilege Denial Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/erase-past-windows-decor-three-methods/"><u>Erase Past Windows Decor: Three Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-faster-file-transfers-with-utorrent-on-win-computers/"><u>Unlock Faster File Transfers with uTorrent on Win Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-task-automation-tackling-scheduler-issues/"><u>Enhance Task Automation: Tackling Scheduler Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-seamless-execution-of-power-users-commands/"><u>Enabling Seamless Execution of Power Users Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/critical-steps-for-a-complete-operating-system-wipe/"><u>Critical Steps for a Complete Operating System Wipe</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-15-plus-3-ways-to-unlock-by-drfone-ios/"><u>How To Unlock iPhone 15 Plus 3 Ways To Unlock</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/how-to-add-audio-to-video-in-magix-movie-edit-pro/"><u>How to Add Audio to Video in Magix Movie Edit Pro</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/twisting-tales-in-photography-the-ultimate-guide-to-angled-spins-on-digital-platforms/"><u>Twisting Tales in Photography  The Ultimate Guide to Angled Spins on Digital Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-command-prompt-integrating-folders-into-context-menu/"><u>Elevate Your Command Prompt: Integrating Folders Into Context Menu</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-unseen-story-access-top-anonymous-tools/"><u>In 2024, Unseen Story Access  Top Anonymous Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-craft-compelling-video-content-using-windows-photos-and-story-remix/"><u>[Updated] Craft Compelling Video Content Using Windows Photos & Story Remix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-editing-text-via-snipping-tool/"><u>Expert Guide: Editing Text via Snipping Tool</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-jailbreak-icloud-locked-iphone-se-2022-by-drfone-ios/"><u>In 2024, How to jailbreak iCloud locked iPhone SE (2022)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-empty-directory-mistake-code-0x80070091-guide/"><u>Clearing Up Empty Directory Mistake: Code 0X80070091 Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-top-6-minecraft-house-ideas-for-beginners/"><u>[Updated] 2024 Approved  Top 6 Minecraft House Ideas for Beginners</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-visionary-studio-guide-detailed-xreviewers-digest/"><u>[New] The Visionary Studio Guide  Detailed XReviewer's Digest</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/maximizing-your-screen-real-estate-with-picture-in-picture-creation-for-2024/"><u>Maximizing Your Screen Real Estate with Picture in Picture Creation for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/unexpected-display-settings-issue-windows-10-fixed/"><u>Unexpected Display Settings Issue: Windows 10 Fixed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-blanking-and-flashing-windows-11-screen/"><u>Stop Blanking and Flashing Windows 11 Screen</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-14-ultra-phone-without-password-by-drfone-android/"><u>How To Unlock Xiaomi 14 Ultra Phone Without Password?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Honor Magic 6 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-beginners-handbook-to-free-chessboard-soccer-management/"><u>The Complete Beginner’s Handbook to Free Chessboard Soccer Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-0x887a0006-device-hang-fixes/"><u>Resolving Error Code 0X887A0006: Device Hang Fixes</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-chromecast-compatibility-how-to-stream-videos-in-any-format/"><u>Updated In 2024, Chromecast Compatibility How to Stream Videos in Any Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-vs-powershell-a-closer-look-at-their-differences/"><u>Terminal Vs. PowerShell: A Closer Look at Their Differences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-error-code-0x80070570-for-corrupted-items/"><u>Steps to Resolve Windows Error Code 0X80070570 for Corrupted Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhinge-your-onedrive-link-from-microsoft-profile-in-windows/"><u>Unhinge Your OneDrive Link From Microsoft Profile in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-default-path-problems-on-windows-1011/"><u>Resolving Default Path Problems on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-software-disposal-adding-context-menu-shortcuts-to-win-1011/"><u>Efficient Software Disposal: Adding Context Menu Shortcuts to Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-bluetooth-issue-here-are-9-quick-cures-to-restore-your-link/"><u>Win 11'S Bluetooth Issue? Here Are 9 Quick Cures to Restore Your Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-remedies-for-server-miss-on-pc-apex-(156-chars/"><u>Essential Remedies for Server Miss on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://games-able.techidaily.com/transforming-your-gaming-identity-on-riot-platform/"><u>Transforming Your Gaming Identity on Riot Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-environment-with-portable-utility-icons/"><u>Streamlining Windows Environment with Portable Utility Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-combat-windows-minimizing-glitches/"><u>Strategies to Combat Windows Minimizing Glitches</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-top-15-free-video-editing-software-for-beginners-easy-to-use/"><u>Updated 2024 Approved Top 15 Free Video Editing Software for Beginners Easy to Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-live-service-disruptions-on-pcs/"><u>Troubleshooting Xbox Live Service Disruptions on PCs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-audience-allure-identifying-the-top-6-video-types/"><u>[Updated] Audience Allure  Identifying the Top 6 Video Types</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/techniques-to-upload-extended-videographics-on-instagram/"><u>Techniques to Upload Extended Videographics on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-not-found-error-in-windows-setup/"><u>Eliminating Not Found Error in Windows Setup</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-fundamentals-of-captivating-video-scripts-for-2024/"><u>The Fundamentals of Captivating Video Scripts for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-reveal-the-best-7-video-streaming-apps-to-go-live-on-youtube-iphoneandroid/"><u>2024 Approved  Reveal the Best 7 Video Streaming Apps to Go Live on YouTube (iPhone/Android)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-best-tiktok-watermark-remover-apps-for-iphone-and-android-for-2024/"><u>[New] Best TikTok Watermark Remover Apps for iPhone and Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stifling-windows-restart-requests/"><u>Stifling Windows Restart Requests</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-the-definitive-list-of-popular-software-for-auditory-disentanglement-from-video-footage/"><u>2024 Approved The Definitive List of Popular Software for Auditory Disentanglement From Video Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-a-neat-system-restart-in-windows-11/"><u>The Essential Guide to a Neat System Restart in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-screen-radiance-on-windows-11-practical-fixes/"><u>Elevate Screen Radiance on Windows 11: Practical Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-the-way-you-search-on-windows-11/"><u>Revamp the Way You Search on Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-x-to-other-iphone-13-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone X To Other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/hunt-for-virtual-assorted-digestive-noises-in-sound-libraries/"><u>Hunt for Virtual Assorted Digestive Noises in Sound Libraries</u></a></li>
<li><a href="https://extra-resources.techidaily.com/deciphering-the-art-of-cd-ripping-via-windows-media-player/"><u>Deciphering the Art of Cd Ripping via Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failure-of-intels-wi-fi-6d-driver-in-os/"><u>Addressing Failure of Intel's Wi-Fi 6D Driver in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-files-directories-for-game-access/"><u>Winning at Files: Directories for Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-streamlining-with-new-folder-placement/"><u>Step-by-Step Guide to Streamlining with New Folder Placement</u></a></li>
</ul></div>
