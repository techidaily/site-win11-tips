---
title: "Biometric Permissions: Managing Domain Users in W11"
date: 2024-08-08T10:56:49.162Z
updated: 2024-08-09T10:56:49.162Z
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

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-how-to-see-every-participant-in-google-meet/"><u>[New] How to See Every Participant in Google Meet?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-thriving-in-the-social-media-jungle-facebooks-essentials-for-2024/"><u>[New] Thriving in the Social Media Jungle  Facebook's Essentials for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-efficient-strategies-for-instagram-to-mp3-transformation/"><u>[Updated] 2024 Approved  Efficient Strategies for Instagram to Mp3 Transformation</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-project-pics-blend-outside-focus-with-radial-filters-psx/"><u>[Updated] 2024 Approved  Project Pics  Blend Outside Focus with Radial Filters PSX</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-boost-your-instagram-videos-watchability-and-speed-for-2024/"><u>[Updated] Boost Your Instagram Videos' Watchability and Speed for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-building-effective-product-sponsor-relationships-for-2024/"><u>[Updated] Building Effective Product-Sponsor Relationships for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-flipping-photos-for-followers-a-rotational-approach-for-insta-success-for-2024/"><u>[Updated] Flipping Photos for Followers  A Rotational Approach for Insta Success for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-forging-strategic-alliances-on-youtube-through-famebit-wisdom/"><u>[Updated] In 2024, Forging Strategic Alliances on YouTube Through FameBit Wisdom</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-quick-chuckles-on-iphone/"><u>[Updated] Quick Chuckles on iPhone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-saving-powerpoint-presentation-to-video/"><u>[Updated] Saving PowerPoint Presentation to Video</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-empty-directory-mistake-code-0x80070091-guide/"><u>Clearing Up Empty Directory Mistake: Code 0X80070091 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/critical-steps-for-a-complete-operating-system-wipe/"><u>Critical Steps for a Complete Operating System Wipe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-command-prompt-integrating-folders-into-context-menu/"><u>Elevate Your Command Prompt: Integrating Folders Into Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-seamless-execution-of-power-users-commands/"><u>Enabling Seamless Execution of Power Users Commands</u></a></li>
<li><a href="https://facebook.techidaily.com/engaging-viewers-like-never-before-a-step-by-step-guide-to-creating-viral-facebook-reels/"><u>Engaging Viewers Like Never Before: A Step-by-Step Guide to Creating Viral Facebook Reels</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/enhance-your-instagram-presence-with-obs-based-streaming-for-2024/"><u>Enhance Your Instagram Presence with OBS-Based Streaming for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/erase-past-windows-decor-three-methods/"><u>Erase Past Windows Decor: Three Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-remedies-for-server-miss-on-pc-apex-(156-chars/"><u>Essential Remedies for Server Miss on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://howto.techidaily.com/fix-motorola-g24-power-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Motorola G24 Power Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-extract-to-temp-folder-error-1152-on-win/"><u>Fixing 'Extract to Temp Folder Error 1152' On Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-zero-error-in-windows-sandbox-missing-hypervisor-solution/"><u>Fixing Zero Error in Windows Sandbox - Missing Hypervisor Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fractured-fort-knox-continue-current-cybersecurity/"><u>Fractured Fort Knox? Continue Current Cybersecurity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-invalid-captcha-on-steam/"><u>Guide to Correcting Invalid CAPTCHA on Steam</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-does-a-whole-sphere-video-work-for-2024/"><u>How Does a Whole-Sphere Video Work for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-xiaomi-redmi-a2-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Xiaomi Redmi A2 in Minutes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-unfreeze-steam-and-resume-gaming-on-windows-11/"><u>How To Swiftly Unfreeze Steam and Resume Gaming on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-vivo-y100t-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Vivo Y100t? Fix Now | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-passfab-iphone-15-pro-max-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>In 2024, PassFab iPhone 15 Pro Max Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transfer-techniques-securely-moving-data-to-desktop/"><u>In 2024, Transfer Techniques  Securely Moving Data to Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-identifying-devices-with-windows-tools/"><u>In-Depth Analysis: Identifying Devices with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-admin-level-command-prompt-in-windows-11-pro/"><u>Initiating Admin-Level Command Prompt in Windows 11 Pro</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/innovating-with-technology-advanced-gopro-4k-editing-techniques/"><u>Innovating with Technology  Advanced GoPro 4K Editing Techniques</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mondly-at-expo-2020-dubai-the-future-of-language-learning/"><u>Mondly At Expo 2020 Dubai: The Future Of Language Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-upgrading-old-pcs-to-22h2/"><u>Navigating New Horizons: Upgrading Old PCs to 22H2</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-best-4-eminem-voice-generator-apps-for-pc-mac-mobile-and-online/"><u>New Best 4 Eminem Voice Generator Apps for PC, Mac, Mobile, and Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-gen-teams-meeting-demands-efficiently/"><u>Next-Gen Teams Meeting Demands Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/post-update-failure-navigating-disconnect-in-windows-discord/"><u>Post-Update Failure: Navigating Disconnect in Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-the-top-6-win-tracking-software-choices/"><u>Propel Productivity: The Top 6 Win Tracking Software Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realign-subtitles-in-prime-video-elevate-your-windows-11-experience/"><u>Realign Subtitles in Prime Video, Elevate Your Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rearrange-screen-alignment-for-windows-users/"><u>Rearrange Screen Alignment for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-lost-window-pans-in-windows-11/"><u>Reconnecting Lost Window Pans in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-usb-connection-in-windows-11/"><u>Reestablishing USB Connection in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-the-clipboard-in-windows-11-with-user-centric-features/"><u>Reimagining the Clipboard in Windows 11 with User-Centric Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-this-device-is-being-used-by-someone-else-in-sound/"><u>Resolving 'This Device Is Being Used By Someone Else' In Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-always-seeing-your-sticky-notes-in-windows/"><u>Secrets to Always Seeing Your Sticky Notes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-addressing-windows-update-errors/"><u>Step-by-Step: Addressing Windows Update Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-file-download-problems-in-windows/"><u>Strategies to Overcome File Download Problems in WIndows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-taskbar-in-windows-11/"><u>Tailoring Your Taskbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-a-neat-system-restart-in-windows-11/"><u>The Essential Guide to a Neat System Restart in Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-ultimate-guide-to-hassle-free-scansnap-driver-downloads-and-updates-on-windows-systems/"><u>The Ultimate Guide to Hassle-Free ScanSnap Driver Downloads and Updates on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-warmup-latency-top-tips-for-a-quicker-boot-up/"><u>Trim Down Warmup Latency – Top Tips for a Quicker Boot-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-error-0xc00000f-in-windows-pcs/"><u>Understanding and Resolving Error 0Xc00000f in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlink-others-login-on-win-11/"><u>Unlink Others' Login on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-faster-file-transfers-with-utorrent-on-win-computers/"><u>Unlock Faster File Transfers with uTorrent on Win Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-in-hand-typing-enable-steps-on-windows/"><u>Unlock the Power of In-Hand Typing: Enable Steps on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-the-secret-dark-mode-setting-in-win-11s-notepad/"><u>Unveil the Secret: Dark Mode Setting in Win 11'S Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-enhanced-functionality-with-ai-for-windows-11-users/"><u>Unveiling Enhanced Functionality with AI for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vivetool-blueprint-engaging-windows-companion/"><u>ViveTool Blueprint: Engaging Windows Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-files-directories-for-game-access/"><u>Winning at Files: Directories for Game Access</u></a></li>
</ul></div>
