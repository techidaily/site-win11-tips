---
title: Correcting Windows Security Account Manager Glitches
date: 2024-07-12T17:04:25.236Z
updated: 2024-07-13T17:04:25.236Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Windows Security Account Manager Glitches
excerpt: This Article Describes Correcting Windows Security Account Manager Glitches
keywords: WINSEC Fix Tips,SAM Hack Prevention,Secure Windows ACM,Windows Security Patch,ACM Error Correction,WinSEC Glitch Solve,Enhance System Security
thumbnail: https://thmb.techidaily.com/64bcba811dca59ee452fde50283dc6af9516c46b5a87dc01f6fa89f4e4093f9a.jpg
---

## Correcting Windows Security Account Manager Glitches

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.
7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/navigating-launchers-security-failures-on-windows-systems/"><u>Navigating Launcher's Security Failures on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-faded-screen-settings-in-uefi/"><u>Restoring Faded Screen Settings in UEFI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-must-have-android-apps-for-windows-users/"><u>Nine Must-Have Android Apps for Windows Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-win11s-ultimate-app-selection-for-quality-recording/"><u>[Updated] In 2024, Win11's Ultimate App Selection for Quality Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-display-at-operating-system-kickoff/"><u>Resolving Non-Display at Operating System Kickoff</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-top-tiktok-tricks-for-desktop-success/"><u>[New] In 2024, Top TikTok Tricks for Desktop Success</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exclusive-soundstage-shows-for-2024/"><u>Exclusive Soundstage Shows for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peering-into-ftdibussys-an-analysis-of-windows-memory-controls/"><u>Peering Into ftdibus.sys: An Analysis of Windows' Memory Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/severing-the-ties-unlink-onedrive-from-your-msid-on-windows/"><u>Severing the Ties: Unlink OneDrive From Your MSID on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-poco-x6-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Poco X6 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-unveiling-tiktoks-anime-phenomenon-a-kaleidoscope-of-choreography-melodies-and-memes/"><u>[Updated] Unveiling TikTok's Anime Phenomenon  A Kaleidoscope of Choreography, Melodies & Memes</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-beyond-reality-boundaries-the-vr-journey-continues/"><u>2024 Approved  Beyond Reality Boundaries  The VR Journey Continues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-winerror-0xc0000005/"><u>Mastering the Art of Fixing WinError 0Xc0000005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-desktop-icon-update-process-on-windows/"><u>Simplifying Desktop Icon Update Process on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stuck-keys-alert-restoring-order-in-windows/"><u>Stuck Keys Alert: Restoring Order in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-fatal-error-c0000022-in-windows/"><u>How to Fix the Fatal Error C0000022 in Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-asus-rog-phone-7-ultimate-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Asus ROG Phone 7 Ultimate FRP Bypass With Best Methods</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-realme-narzo-60-pro-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Realme Narzo 60 Pro 5G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-1053-unresponsive-service-issue/"><u>Tackling Windows Error 1053: Unresponsive Service Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-level-windows-photos-shortcut-guide/"><u>Pro-Level Windows Photos Shortcut Guide</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-4-solutions-to-crop-a-video-on-android-easily/"><u>New In 2024, 4 Solutions to Crop a Video on Android Easily</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-clearscreenstreamer-seamless-easy-w11-screenshots-for-2024/"><u>[New] ClearScreenStreamer  Seamless, Easy W11 Screenshots for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-face-swap-frenzy-the-best-mobile-apps-to-try-for-2024/"><u>New Face Swap Frenzy The Best Mobile Apps to Try for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Lava Blaze 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-instructions-for-installing-chrome-on-windows-11/"><u>Stepwise Instructions for Installing Chrome on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-list-of-windows-note-taking-aids/"><u>Ultimate List of Windows Note-Taking Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rectifying-device-is-unreachable-error-in-windows/"><u>Mastering the Art of Rectifying Device Is Unreachable Error in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-advanced-tips-for-smooth-transitions-and-effects-in-gopro-studio/"><u>2024 Approved  Advanced Tips for Smooth Transitions and Effects in GoPro Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-device-hang-on-windows-11-zerodxgieror/"><u>Overcoming the Device Hang on Windows 11 (ZeroDXGIEror)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-xiaomi-civi-3-disney-100th-anniversary-edition-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Xiaomi Civi 3 Disney 100th Anniversary Edition Phone When You Forget the Password</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-a-compre-cookies-guide-to-marketing-magic-with-20-terms/"><u>2024 Approved  A Compre Cookie's Guide to Marketing Magic with 20 Terms</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-mastering-mac-screenshots-and-screen-recording/"><u>[New] 2024 Approved  Mastering Mac Screenshots & Screen Recording</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-quick-recap-of-chromakey-and-green-screen-processes/"><u>[New] Quick Recap of Chromakey and Green Screen Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-and-permanently-discard-a-partition-on-windows-pc/"><u>How to Swiftly and Permanently Discard a Partition on Windows PC</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagram-to-mp4-perfection-uncover-2-most-effective-techniques-for-2024/"><u>[New] Instagram to MP4 Perfection  Uncover 2 Most Effective Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timely-tactics-effective-execution-of-ping-commands/"><u>Timely Tactics: Effective Execution of Ping Commands</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-linux-premiere-pro-alternatives-top-picks-for-video-editors/"><u>New In 2024, Linux Premiere Pro Alternatives Top Picks for Video Editors</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-experts-guide-to-finding-cheap-sbd-solutions/"><u>2024 Approved  Expert's Guide to Finding Cheap SBD Solutions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-dissecting-youtube-copyright-vs-creative-commons-ethos/"><u>[Updated] 2024 Approved  Dissecting YouTube Copyright Vs. Creative Commons Ethos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-pitch-perfect-promos-mastering-the-art-of-music-in-social-media-for-2024/"><u>[Updated] Pitch-Perfect Promos  Mastering the Art of Music in Social Media for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-psp-emulator-ios-top-5-picks/"><u>[Updated] 2024 Approved  PSP Emulator iOS  Top 5 Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-core-data-an-analysis-of-the-registry/"><u>Unlocking Windows 11'S Core Data: An Analysis of the Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reverse-winerror-exit-point-failure/"><u>Steps to Reverse WinError Exit Point Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-command-prompt-not-running-as-administrator-on-windows/"><u>How to Fix Command Prompt Not Running as Administrator on Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-extensive-review-gecata-recording-device-analysis/"><u>[New] Extensive Review  Gecata Recording Device Analysis</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/perfecting-the-pulse-news-outro-techniques/"><u>Perfecting the Pulse  News Outro Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-non-scrollability-of-ranges-in-excel-windows/"><u>Prevent Non-Scrollability of Ranges in Excel, Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/setting-up-an-online-presence-for-reviews-of-commercial-goods/"><u>Setting Up an Online Presence for Reviews of Commercial Goods</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-smooth-process-incorporating-igtv-in-stories/"><u>[Updated] Smooth Process  Incorporating IGTV in Stories</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-smart-way-to-shop-for-drones-must-know-information/"><u>[Updated] The Smart Way to Shop for Drones  Must-Know Information</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/capture-your-macs-screen-a-step-by-step-walkthrough/"><u>Capture Your Mac's Screen  A Step-by-Step Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-approach-to-editing-windows-registry-with-command-prompt/"><u>Stepwise Approach to Editing Windows Registry with Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-xbox-game-pass-0x00000001-error-in-windows-10-and-11/"><u>How to Fix the Xbox Game Pass 0X00000001 Error in Windows 10 & 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/webm-to-gif-converters-online-and-offline-solutions-for-2024/"><u>WebM to GIF Converters (Online and Offline Solutions) for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unveiling-the-ultimate-list-youtubes-premier-mp3-extractors/"><u>[Updated] Unveiling the Ultimate List  YouTube's Premier MP3 Extractors</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/cutting-edge-strategies-for-efficient-speech-translation-with-google-for-2024/"><u>Cutting Edge Strategies for Efficient Speech Translation with Google for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-code-0xc0000001-on-windows-11-or-11/"><u>How to Fix Error Code 0Xc0000001 on Windows 11 or 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-solving-obs-errors-windows-edition/"><u>Understanding and Solving OBS Errors: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-file-explorer-display-options-windows-11/"><u>How to Control File Explorer Display Options (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-efficiency-guide/"><u>Mastering Windows 11: Efficiency Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-up-output-the-power-of-flow-launcher-unveiled/"><u>Scaling Up Output: The Power of Flow Launcher Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-extend-wait-time-before-shutting-down-in-windows-10/"><u>Tactics to Extend Wait Time Before Shutting Down in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-power-management-features-for-maximum-efficiency/"><u>Unlocking Power Management Features for Maximum Efficiency</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-effortless-keyword-harvesting-explore-the-best-7-no-fee-tag-extractors/"><u>2024 Approved  Effortless Keyword Harvesting  Explore the Best 7 No-Fee Tag Extractors</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtube-mastery-how-to-add-structure-and-subdivisions-for-enhanced-content/"><u>2024 Approved  YouTube Mastery  How to Add Structure and Subdivisions for Enhanced Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-approach-to-bypassing-no-permission-on-pc/"><u>Step-by-Step Approach to Bypassing 'No Permission' On PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-xbox-apps-voice-issues-in-windows/"><u>Understanding Xbox App's Voice Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-on-windows-11-updates/"><u>Solving Error 0X80246007 on Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-access-mastering-network-drives-in-win11/"><u>Seamless File Access: Mastering Network Drives in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-chromes-system-time-a-fix-guide-windows/"><u>Realigning Chrome's System Time: A Fix Guide (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-installation-and-usage-of-ms-store-themes/"><u>Navigate With Style: Installation and Usage of MS Store Themes</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-exploring-the-features-of-vimeos-innovative-recorder/"><u>[New] 2024 Approved  Exploring the Features of Vimeo's Innovative Recorder</u></a></li>
</ul></div>
