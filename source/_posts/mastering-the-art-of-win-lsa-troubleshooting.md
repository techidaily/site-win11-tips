---
title: Mastering the Art of Win LSA Troubleshooting
date: 2024-07-12T16:57:31.559Z
updated: 2024-07-13T16:57:31.559Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Win LSA Troubleshooting
excerpt: This Article Describes Mastering the Art of Win LSA Troubleshooting
keywords: Art of LSA Fixing,LSA Mastery,LSA Techniques,Win LSA Tips,Resolve LSA Issues,LSA Expertise,LSA Troubleshooting Guide
thumbnail: https://thmb.techidaily.com/cc90cfb91ad0a20c12f9d720fc85b3d9e0382268e1d979284c574fcec450998c.jpg
---

## Mastering the Art of Win LSA Troubleshooting

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
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-the-unsung-heroes-key-contributions-of-each-cinematic-craftsperson/"><u>New 2024 Approved The Unsung Heroes Key Contributions of Each Cinematic Craftsperson</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-history-hiccup-quick-fixes-in-3-steps/"><u>Windows History Hiccup - Quick Fixes in 3 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apps-calm-demeanor-hides-computational-challenges-for-windows-users/"><u>Apps' Calm Demeanor Hides Computational Challenges for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-lav-filters-usage-and-functionality/"><u>Demystifying Windows LAV Filters Usage and Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-tools-for-microsoft-enthusiasts/"><u>Top 8 Cross-Platform Tools for Microsoft Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-ways-for-swift-epic-game-loading/"><u>Unveiling Windows Ways for Swift Epic Game Loading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-error-0xa00f425d-in-windows-camera/"><u>Steps to Eliminate Error 0xA00F425D in Windows Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-review-pcmac-comparison/"><u>ASUS Zenbook 14 OLED Review: PC/Mac Comparison?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-failures-qt-platform-support-error-at-launch/"><u>Correcting Failures: 'Qt Platform Support' Error at Launch</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-advanced-anonymization-techniques-to-blur-faces/"><u>[Updated] Advanced Anonymization  Techniques to Blur Faces</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-acquiring-safe-gratis-vlc-media-player-on-macos-systems/"><u>2024 Approved  Acquiring Safe, Gratis VLC Media Player on macOS Systems</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-revolutionize-playtime-win11s-game-library/"><u>[Updated] In 2024, Revolutionize Playtime  Win11's Game Library</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-accelerate-your-video-content-creation/"><u>[Updated] Accelerate Your Video Content Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-virtualboxs-0x80004005-failure-on-win/"><u>Dealing with VirtualBox's 0X80004005 Failure on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-inactivity-lock-timer/"><u>Adjusting Windows Inactivity Lock Timer</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-broadcasting-how-to-stream-your-twitch-content/"><u>YouTube Broadcasting  How to Stream Your Twitch Content</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-realme-narzo-60-5g-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Realme Narzo 60 5G Screen | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-neo-theater-narratives-virtual-realms/"><u>[Updated] Neo-Theater Narratives  Virtual Realms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-w11-desktop-customization-essentials/"><u>Effortless W11 Desktop Customization Essentials</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-youtube-earnings-per-thousand-views-explained/"><u>In 2024, YouTube Earnings Per Thousand Views Explained</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-systray-with-scroll-lock-and-num-indicators/"><u>Amplify Windows 11 SysTray with Scroll Lock and Num Indicators</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-twitch-vs-youtube-an-in-depth-comparative-analysis/"><u>[Updated] Twitch vs YouTube  An In-Depth Comparative Analysis</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-lava-yuva-2-pro-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Lava Yuva 2 Pro Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-perfecting-the-art-of-capturing-spoken-words-digitally/"><u>[New] Perfecting the Art of Capturing Spoken Words Digitally</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-advanced-live-broadcast-setup-from-obs-to-fb-enthusiasts-for-2024/"><u>[New] Advanced Live Broadcast Setup  From OBS to FB Enthusiasts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-cant-get-mail-errors-windows-11-edition/"><u>Strategies to Overcome Can’t Get Mail Errors, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-windows-11-potential-via-powertoys-install/"><u>Unleashing Windows 11 Potential via PowerToys Install</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-vivo-y55s-5g-2023-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Vivo Y55s 5G (2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-file-sync-solutions-for-windows-users/"><u>Best File Sync Solutions for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-incorrect-parameters-for-winloadlib/"><u>Dealing with Incorrect Parameters for WinLoadLib</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Oppo Reno 8T 5G? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-leading-free-tech-to-share-pc-screens-seamlessly/"><u>[New] Leading Free Tech to Share PC Screens Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-keyways-to-activate-telnet-on-windows-11-pcs/"><u>3 Keyways to Activate Telnet on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-secrets-of-running-imessage-on-windows/"><u>Uncovering the Secrets of Running iMessage on Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-tips-for-faster-vimeo-video-viewing/"><u>In 2024, Tips for Faster Vimeo Video Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-the-gaming-experience-winning-strategies-for-ps1-and-windows-duckstations-guide/"><u>Elevating the Gaming Experience: Winning Strategies for PS1 and Windows - Duckstation's Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-analyzing-online-video-discussions-for-2024/"><u>[Updated] Analyzing Online Video Discussions for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/discover-vitas-full-fledged-video-editor-a-detailed-guide-2024/"><u>Discover Vita's Full-Fledged Video Editor  A Detailed Guide, 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-android-and-iphone-apps-for-free-photo-overlay-artistry/"><u>2024 Approved  Top Android & iPhone Apps for FREE Photo Overlay Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktops-uncluttered-remove-win11s-spotlight-symbol/"><u>Desktops Uncluttered: Remove Win11's Spotlight Symbol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-windows-steam-broadcaster-errors/"><u>Combatting Windows Steam Broadcaster Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-operators-downloading-deadlock-in-windows/"><u>Break Free From Operator's Downloading Deadlock in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-xc0f1103f-issues-with-geforce-now-on-win11/"><u>Correcting Xc0f1103f Issues with GeForce Now on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-approach-to-allocated-ram/"><u>Understanding Windows' Approach to Allocated RAM</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-primary-movie-document-review-and-backup-titles/"><u>In 2024, Primary Movie Document Review and Backup Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-by-unrealcefsubprocess-on-systems/"><u>Strategies to Reduce CPU and RAM Overuse by UnrealCEFSubprocess on Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-file-explorer-menus-with-auto-update-features/"><u>Augmenting File Explorer Menus with Auto-Update Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-downloading-errors-in-microsoft-store/"><u>Addressing Downloading Errors in Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-volume-control-fix-guide/"><u>Windows 10/11 Volume Control Fix Guide</u></a></li>
</ul></div>
