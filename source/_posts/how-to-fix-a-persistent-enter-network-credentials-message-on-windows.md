---
title: How to Fix a Persistent Enter Network Credentials Message on Windows
date: 2024-07-12T16:55:14.110Z
updated: 2024-07-13T16:55:14.110Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix a Persistent Enter Network Credentials Message on Windows
excerpt: This Article Describes How to Fix a Persistent Enter Network Credentials Message on Windows
keywords: Windows Credential Error Guide,Resolve Login Failures Windows,Fixing Login Prompts in Windows,Stop Windows Login Errors,Clear Credential Messages PC,Overcome Enter Passwords Problem WinXP,Eliminate Windows Sign-In Issues
thumbnail: https://thmb.techidaily.com/4bb09ddf21259f8aa35372dd3bddaab5a52e4c2f70a7e62b027db40747b04fa4.jpeg
---

## How to Fix a Persistent Enter Network Credentials Message on Windows

 The network credentials on your PC are important because they prevent others from using your computer across the network. While this feature is essential to protect your important files and improve the overall security of your system, it can sometimes cause issues as well.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

## 1\. Modify the Advanced Sharing Settings

 An incorrectly set Advanced Sharing setting is one of the most common causes of this error. Ideally, your PC should be allowed to manage homegroup connections. You can also use the Advanced Sharing settings page to disable password-protected sharing, which will allow you to share files without needing to log in.

 Here is how you can configure the Advanced Sharing settings correctly:

1. Locate the network icon on your taskbar and right-click on it.
2. Choose **Network and Internet settings** from the context menu.  
![Network and Internet settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/network-and-internet-settings.jpg)
3. In the following window, select **Network and Sharing Center**.
4. Choose **Change advanced sharing settings** option in the left pane.
5. Now, enable the **Allow Windows to manage homegroup connections (recommended)** option under Homegroup connections.
6. Click **Save changes** (you will need administrative access for this).
7. Now, expand the **All Networks** section and enable the **Turn off password protected sharing** option.  
![Turn off password sharing option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/turn-off-pasword-sharing.jpg)
8. Hit the **Save changes** button to complete the process.

 After you've transferred the files, re-enable password-protected sharing so that others don't get easy access to your PC.

## 2\. Use Your Microsoft Account Credentials or the Computer's Name

 You can also try logging onto the target PC using the Microsoft account credentials instead of the local username and password.

 Alternatively, you can also try using the name of the computer you are using alongside your username in the text field associated with the Username. Do not enter a space, bar, or any other symbol between the names.

 If the problem is associated with the credentials, one of these two methods is likely to help you get rid of it for good.

## 3\. Manually Add the Credentials of the Target Computer to the Credential Manager

 Another way to fix the issue is by manually adding the credentials of the targeted computer in the Credential Manager and seeing if that makes a difference.

 Here is how you can do that:

1. Type "Credential Manager" into Windows Search and click **Open**.
2. Select **Windows Credential** and click on **Add a Windows Credential**.  
![Windows credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-credentials-1.jpg)
3. Now, add the username, computer name, and password of the computer you are trying to access. Check if you can now share files with the other device successfully.

## 4\. Create a New User Account on Both Devices

 There are times when user accounts become corrupt and stop you from performing certain actions. If this has happened, either on your PC or the target computer, it can interrupt the file-sharing process.

 To fix this problem, first, try [switching to a different user account](https://www.makeuseof.com/windows-11-switch-user-accounts/) on your own computer and see if that works. If this strategy fails, then we recommend [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) on both devices with the same username and password. Make sure that both accounts have administrative privileges. While you are at it, we also suggest temporarily disabling any third-party antivirus program that you might be using, as it can sometimes block network access.

 If the root of your issue was a corrupt user account, this should be enough to fix the issue.

## 5\. Restart the Credential Manager Service

 The issue might also be with the Credential Manager service itself instead of the targeted computer or the network settings of your device. In this method, we will first enable the Credential Manager service if the service is disabled.

 If it is working already, then we will proceed with restarting the service and see if that does the trick.

 Here is what you need to do:

1. Press **Win** \+ **R** to open Run.
2. Type services.msc in the Run and click **Enter**.
3. In the following window, look for the Credential Manager service and right-click on it.
4. Choose **Properties** from the context menu.
5. If the service is disabled, click on the **Start button** to enable it.
6. In case it is working already, click on the **Stop button**, wait for a few seconds, and then hit the **Start button**.
7. ![Credential Manager properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-properties.jpg)  
 Make sure that the Startup type is set to **Automatic**.  
![Credential Manager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-service.jpg)
8. Click **Apply** \> **OK** to save the changes.

 Now try connecting to the targeted computer and see if you can do so without any problems.

## 6\. Make Changes to the Local Security Policy

 Several users also managed to fix the problem by modifying the settings of the "Accounts: Limit local account use of blank passwords to console logon only" policy. Here is how you can give it a try too:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "secpol.msc" in Run and click **Enter**.
3. In the following window, navigate to the following location:  
Local Policies > Security Options > Accounts: Limit local account use of blank passwords to console logon only
4. Choose **Disabled** and click **Apply** \> **OK** to save the changes.  
![Make changes to the Local Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-security-policy.jpg)
5. Restart your computer and check if the issue is resolved.

## 7\. Try Using Safe Mode With Networking

 If the credentials you are entering and all the network configurations on the system are correct, something might have gone wrong on a system level.

 In this case, you can boot into Safe Mode to determine the cause of the issue. Safe Mode starts Windows with only the basic set of drivers and apps — the ones that are essential for the operating system to function.

 There are several types of Safe Mode including Minimal, Alternate Shells, Active Directory Repair, and Network. In this method, we will be booting Windows into Safe Mode with Networking. This mode launches Windows with the drivers and programs required to connect the system to the internet or other devices over the network.

 If the error at hand does not appear in Safe Mode, then there is a chance that malware or other software issues are causing the problem.

 Here is what you need to do:

1. Head over to the Start menu and click on the **Power button**.
2. Choose **Restart** while holding the **Shift key**.
3. Wait for the Windows to boot into the recovery mode and then choose **Troubleshoot** \> **Advanced Options**.
4. Navigate to **Startup Settings** \> **Restart**.
5. In the following window, press the **F5 key** on your keyboard to boot into Safe Mode with Networking.  
![Pick safe mode with Networking option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Tweak-Startup-Settings-1.jpg)
6. Once you are logged into Safe Mode, try connecting to the device you were previously trying to connect to. If the error does not appear in Safe Mode, then you might want to report this issue to Microsoft’s official support team and wait for a fix from their side.

 In case you cannot access this Windows state using the steps outlined above, you can try [other ways of booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

## Share Data Over Network Without Issues

 Windows has made it simpler to share your files and other data across networks, but there are times when you run into unexpected errors. Hopefully, one of the methods mentioned above did the trick for you in fixing the issue under consideration.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/step-by-step-secure-your-browsing-with-microsofts-defender-in-win-11/"><u>Step-by-Step: Secure Your Browsing with Microsoft's Defender in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-video-lag-in-vlc-media-player-on-windows/"><u>How to Fix Video Lag in VLC Media Player on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-save-settings-restoration-in-windows-1011s-pubg/"><u>Mastering Save Settings Restoration in Windows 10/11'S PUBG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-from-failed-discord-games-detection-on-windows/"><u>Steps to Recover From Failed Discord Games Detection on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-specific-error-403-in-roblox-space/"><u>Resolving Windows-Specific Error 403 in Roblox Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unsuccessful-nvidia-connect-attempts-in-windows-11/"><u>Resolving Unsuccessful Nvidia Connect Attempts in Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-fb-live-demystified-how-to-watch-2023-update/"><u>[New] 2024 Approved  FB Live Demystified  How to Watch, 2023 Update</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-brand-discover-the-riches-in-our-gallery-of-50-free-youtube-banners-for-2024/"><u>Elevate Your Brand - Discover the Riches in Our Gallery of 50 Free YouTube Banners for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-systemsettings-issue-on-win11/"><u>Strategies to Solve SystemSettings Issue on Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-accurate-speech-to-text-googles-breakthrough-approach/"><u>[Updated] 2024 Approved  Accurate Speech-to-Text  Google's Breakthrough Approach</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-guide-to-mastering-final-cut-pro-essentials/"><u>Ultimate Guide to Mastering Final Cut Pro Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-and-folder-combination-in-windows-11/"><u>Mastering File & Folder Combination in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switchtonightvisioninnotepadwin/"><u>SwitchToNightVisionInNotepadWin</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-your-pc-snipping-guide-the-best-tools-to-try-first/"><u>2024 Approved  Your PC Snipping Guide  The Best Tools to Try First</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-premier-game-chat-platforms-for-enthusiasts/"><u>Updated Premier Game Chat Platforms for Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increase-output-decrease-time-harness-power-of-flow-launcher/"><u>Increase Output, Decrease Time: Harness Power of Flow Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selective-vmm-recommendations-for-windows-11-success/"><u>Selective VMM Recommendations for Windows 11 Success</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/est-low-cost-subtitles-and-downloader-companion/"><u>[New] Best Low-Cost Subtitles & Downloader Companion</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-spotlight-subject-erase-bg-in-photo-editing/"><u>In 2024, Spotlight Subject, Erase Bg in Photo Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-pc-printer-link-fixes/"><u>Mastering PC Printer Link Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rendition-accelerating-prints-on-windows-system/"><u>Rapid Rendition: Accelerating Prints on Windows System</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-the-ultimate-mac-screenshot-strategy-revealed/"><u>[Updated] In 2024, The Ultimate Mac Screenshot Strategy Revealed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/hear-and-heed-free-recognition-and-response-platform/"><u>Hear and Heed  Free Recognition & Response Platform</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-leading-eight-speech-to-text-platforms-for-pc-apple-devices-and-virtual-environments-updated-guide/"><u>New In 2024, Leading Eight Speech-to-Text Platforms for PC, Apple Devices & Virtual Environments - Updated Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-d3dx939dll-error-on-win11/"><u>Recovering D3DX9_39.dll Error on Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/honor-x50i-messages-recovery-recover-deleted-messages-from-honor-x50i-by-fonelab-android-recover-messages/"><u>Honor X50i Messages Recovery - Recover Deleted Messages from Honor X50i</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-focused-communication-tips-for-virtual-teams/"><u>[New] Focused Communication Tips for Virtual Teams</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/maximize-your-access-to-fb-videos-with-our-top-5-picks-for-2024/"><u>Maximize Your Access to FB Videos with Our Top 5 Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-ad-ds-printer-fails-in-win-1011/"><u>Resolving AD DS Printer Fails in Win 10/11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-best-free-online-audio-normalizers/"><u>Updated Best Free Online Audio Normalizers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-low-latency-techniques-for-discord-on-windows/"><u>Mastering Low-Latency Techniques for Discord on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-sony-xperia-5-v-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Sony Xperia 5 V online without jailbreak</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-top-rated-android-apps-to-download-now-for-2024/"><u>Updated Top-Rated Android Apps to Download Now for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-epic-tiktok-gamers-top-10-influencers/"><u>In 2024, Epic TikTok Gamers  Top 10 Influencers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/compreenas-comprehensive-walkthrough-for-creating-a-unified-skype-chat-room-accessible-by-users-of-different-operating-systems/"><u>Compreenas Comprehensive Walkthrough for Creating a Unified Skype Chat Room Accessible by Users of Different Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-sailing-with-these-fixes-for-windows-update/"><u>Smooth Sailing with These Fixes for Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x80072efd-in-windows-devicesstore-apps/"><u>Overcoming Error 0X80072EFD in Windows Devices/Store Apps</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-video-editing-for-kids-made-easy-10-best-apps-with-free-and-paid-options/"><u>New In 2024, Video Editing for Kids Made Easy 10 Best Apps with Free and Paid Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-task-manager-welcome-panel-in-windows-11/"><u>Redefine Task Manager Welcome Panel in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/raising-the-bar-for-user-interface-in-w11-larger-icons/"><u>Raising the Bar for User Interface in W11: Larger Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obscure-yet-outstanding-windows-11-themes/"><u>Obscure yet Outstanding Windows 11 Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/probing-windows-bsod-files-and-their-residues/"><u>Probing Windows BSOD Files & Their Residues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functioning-office-outlook-alerts/"><u>Restoring Functioning Office Outlook Alerts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-vidma-screen-recorder-review-and-alternatives/"><u>[Updated] Vidma Screen Recorder | Review and Alternatives</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-no-more-shakes-top-free-video-stabilizer-apps-for-android-phones-for-2024/"><u>Updated No More Shakes Top Free Video Stabilizer Apps for Android Phones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-no-device-drivers-detected-on-windows-setup/"><u>Resolving 'No Device Drivers Detected' On Windows Setup</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-building-a-strong-introduction-examples-and-methods/"><u>[New] Building a Strong Introduction  Examples & Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-skip-out-of-s-mode-with-ease-for-your-pc/"><u>Swiftly Skip Out of S Mode with Ease for Your PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-samsung-galaxy-a14-4g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Samsung Galaxy A14 4G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-image-id-0x80780119-on-windows-os/"><u>How To Repair Image ID: 0X80780119 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-slow-windows-10-closure-while-tasks-remain-open/"><u>Strategies for Slow Windows 10 Closure While Tasks Remain Open</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-sony-xperia-5-v-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Sony Xperia 5 V to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-system-performance-by-adding-disk-space-analyzer-tool/"><u>Streamline System Performance by Adding Disk Space Analyzer Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-persistent-failures-of-cp-configurations-on-win11/"><u>Mending Persistent Failures of CP Configurations on Win11</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-iphone-macro-and-close-up-photography-tips/"><u>[New] 2024 Approved  IPhone Macro and Close-Up Photography Tips</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-the-ultimate-guide-to-elevating-your-youtube-presence-with-these-20-hacks/"><u>[Updated] In 2024, The Ultimate Guide to Elevating Your YouTube Presence with These 20 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reworking-records-6-windows-applications-for-date-revision/"><u>Reworking Records: 6 Windows Applications for Date Revision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-storage-4-methods-to-tap-into-windows-11s-disk-manager/"><u>Streamline Storage: 4 Methods to Tap Into Windows 11'S Disk Manager</u></a></li>
<li><a href="https://extra-resources.techidaily.com/air-lift-extraordinaire-top-industrial-drones-for-2024/"><u>Air-Lift Extraordinaire  Top Industrial Drones for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-premium-assortment-unmarked-superior-tiktok-extractors/"><u>In 2024, Premium Assortment  Unmarked, Superior TikTok Extractors</u></a></li>
</ul></div>
