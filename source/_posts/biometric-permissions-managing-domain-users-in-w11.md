---
title: "Biometric Permissions: Managing Domain Users in W11"
date: 2024-07-12T18:04:54.652Z
updated: 2024-07-13T18:04:54.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Biometric Permissions: Managing Domain Users in W11"
excerpt: "This Article Describes Biometric Permissions: Managing Domain Users in W11"
keywords: Biometric Access Control,User Authentication W11,Domains User Management,Security W11 Permissions,Authorized Domain Users,Advanced User Verification,Enhanced Privacy W11
thumbnail: https://thmb.techidaily.com/88d3ccdcb9182fe6ab85d78619b5ff79c9f842144c7f0589af82188a3ec75add.jpg
---

## Biometric Permissions: Managing Domain Users in W11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/automate-the-journey-always-command-prompt-admin-style/"><u>Automate the Journey: Always Command Prompt, Admin Style</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-apple-id-activation-lock-from-iphone-6-plus-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID Activation Lock From iPhone 6 Plus?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/top-tier-audio-purge-software-for-videos-on-all-platforms-new-era-of-removal-2024/"><u>Top-Tier Audio Purge Software for Videos on All Platforms (New Era of Removal, 2024)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-terminal-as-favorite-app/"><u>Boost Productivity with Terminal as Favorite App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-application-runtime-to-compensate-for-lack-of-qt-plugins/"><u>Adjusting Application Runtime to Compensate for Lack of Qt Plugins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-black-glare-from-window-8-displays/"><u>Banishing the Black Glare From Window 8 Displays</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-hasty-guide-from-raw-images-to-high-quality-youtube-thumbnail-art/"><u>[Updated] Hasty Guide  From Raw Images to High-Quality YouTube Thumbnail Art</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unveiling-the-simplicity-of-storytelling/"><u>Unveiling the Simplicity of Storytelling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplified-audio-top-4-applications-to-surpass-windows-100-threshold/"><u>Amplified Audio: Top 4 Applications to Surpass Windows’ 100%% Threshold</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-wifi-network-deletion-in-win-11/"><u>Automating Wifi Network Deletion in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-video-transformers-from-the-world-of-windows/"><u>Best Video Transformers From the World of Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-unleash-your-creativity-best-time-lapse-video-apps-for-iphone-and-android/"><u>In 2024, Unleash Your Creativity Best Time-Lapse Video Apps for iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-msc-error-the-printmanagement-glitch/"><u>Addressing Windows MSC Error: The 'Printmanagement' Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-and-controlling-rgb-on-windows-11-pcs/"><u>Adjusting and Controlling RGB on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-winrars-summation-anomalies-with-six-fixes/"><u>Addressing WinRAR's Summation Anomalies with Six Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unviewable-documents-error-in-microsoft-office-mail/"><u>Addressing 'Unviewable' Documents Error in Microsoft Office Mail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ascertain-if-your-computer-meets-11th-gen-os-needs/"><u>Ascertain If Your Computer Meets 11Th Gen OS Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aligning-chrome-and-system-time-windows-sync-tips/"><u>Aligning Chrome and System Time (Windows Sync Tips)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-quick-start-engaging-with-friends-on-insta-chat/"><u>[New] 2024 Approved  Quick Start  Engaging with Friends on Insta Chat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-uninstallation-block-in-win-11-edition/"><u>Addressing Uninstallation Block in Win 11 Edition</u></a></li>
<li><a href="https://extra-tips.techidaily.com/htc-vive-unveiled-mastering-your-3d-world/"><u>HTC Vive Unveiled  Mastering Your 3D World</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-multiperspective-media-expert-guide-to-instagram-video-rotations-for-2024/"><u>[New] Mastering Multiperspective Media  Expert Guide to Instagram Video Rotations for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-updated-scrutiny-of-sony-s3700-high-definition-playback/"><u>[Updated] 2024 Approved  Updated Scrutiny of Sony S3700 High Definition Playback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-a-step-by-step-guide-to-the-taskbars-search-bar-in-windows-11/"><u>Boost Efficiency: A Step-By-Step Guide to the Taskbar’s Search Bar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-disk-space-how-to-use-windows-autodeleting-feature/"><u>Boost Disk Space: How to Use Windows' AutoDeleting Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-and-ranking-video-codecs-for-windows-pcs/"><u>Analyzing and Ranking Video Codecs for Windows PCs</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-inaugural-directors-shorts-for-2024/"><u>[New] Inaugural Director's Shorts for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-craft-compelling-snapchats-on-ios-and-android-top-6-apps-for-2024/"><u>[Updated] Craft Compelling Snapchats on iOS & Android - Top 6 Apps for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-dissecting-luminances-role-in-hdr-imagery/"><u>[New] 2024 Approved  Dissecting Luminance's Role in HDR Imagery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-6-must-have-windows-productivity-tools/"><u>Boosting Efficiency: 6 Must-Have Windows Productivity Tools</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Honor X50i+? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-simplify-your-work-the-best-5-mac-snipper-applications/"><u>[New] In 2024, Simplify Your Work  The Best 5 Mac Snipper Applications</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-how-to-recognize-songs-on-iphone-withwithout-iphone-music-recognition/"><u>2024 Approved How to Recognize Songs on iPhone With/Without iPhone Music Recognition</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-mastering-webcam-and-screen-capture-unison-techniques/"><u>In 2024, Mastering Webcam & Screen Capture  Unison Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-slow-response-times-after-adding-an-additional-screen/"><u>Avoid Slow Response Times After Adding an Additional Screen</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-secrets-to-updating-your-facebook-banner/"><u>In 2024, Secrets to Updating Your Facebook Banner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-epic-game-launcher-stubbornness-on-w11-computers/"><u>Avoid Epic Game Launcher Stubbornness On W11 Computers</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-ballad-barren-builder-create-personal-accompaniment-music/"><u>New In 2024, Ballad Barren Builder Create Personal Accompaniment Music</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-defender-in-windows-11-how-to-turn-it-off/"><u>Avoiding Defender in Windows 11: How to Turn It Off</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>The Most Useful Tips for Pokemon Go Ultra League On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-productivity-windows-task-scheduler-strategies/"><u>Boosting Productivity: Windows Task Scheduler Strategies</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>