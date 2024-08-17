---
title: "Optimizing User Authentication: Windows 11, Domains"
date: 2024-08-16T01:23:26.328Z
updated: 2024-08-17T01:23:26.328Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing User Authentication: Windows 11, Domains"
excerpt: "This Article Describes Optimizing User Authentication: Windows 11, Domains"
keywords: Win11 Auth Optimize,Domain Authentication,Secure Login Windows,Access Control Windows 11,Identity Verification PC,User Credentials Management,Security Windows Protocols
thumbnail: https://thmb.techidaily.com/85be9153d8c81024583588a94ed9e00fc880777ac2a8c7cff5efd5d21044d91c.jpg
---

## Optimizing User Authentication: Windows 11, Domains

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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-speed-dial-for-vimeo-video-loading/"><u>[New] In 2024, Speed Dial for Vimeo Video Loading</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-screengrabzer-facebook-group/"><u>[Updated] 2024 Approved  ScreenGrabzer Facebook Group</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-full-application-evaluation-through-az-video-logger/"><u>[Updated] Full Application Evaluation Through AZ Video Logger</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-ultimate-list-of-9-best-online-mic-recorder-hacks/"><u>[Updated] The Ultimate List of 9 Best Online Mic Recorder Hacks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-x-recorder-your-pcs-audio-capture-companion-for-2024/"><u>[Updated] X-Recorder  Your PC's Audio Capture Companion for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-prime-techniques-perfecting-live-sports-broadcast-recording/"><u>2024 Approved  Prime Techniques  Perfecting Live Sports Broadcast Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-crafting-windows-11-extractable-files/"><u>A Step-by-Step Guide to Crafting Windows 11 Extractable Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-adjustments-nine-fixes-to-smooth-out-windows-11-gaming/"><u>Accelerated Adjustments: Nine Fixes to Smooth Out Windows 11 Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-win1011-blue-screen-crash-issue/"><u>Addressing Win10/11 Blue Screen Crash Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-your-desktop-background-effortlessly-with-win11/"><u>Alter Your Desktop Background Effortlessly with Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-pcs-into-transcoding-hubs-via-tdarr/"><u>Boost Windows PCs Into Transcoding Hubs via Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-code-0x800f0831-the-key-to-smooth-windows/"><u>Decoding Code 0X800F0831: The Key to Smooth Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-usb-drive-errors-windows-tips/"><u>Eliminating USB Drive Errors: Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-starting-wordpad-efficiently-on-windows/"><u>Essential Guide: Starting WordPad Efficiently on Windows</u></a></li>
<li><a href="https://article-helps.techidaily.com/examining-the-unseen-history-of-your-social-media-activity/"><u>Examining the Unseen History of Your Social Media Activity</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/expert-android-guide-to-top-gba-emulators/"><u>Expert Android Guide to Top GBA Emulators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-conquering-system-calls-failure-in-windows-11/"><u>Expert Tips for Conquering System Calls Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/foster-robust-windows-application-connections-with-simple-fixes/"><u>Foster Robust Windows Application Connections with Simple Fixes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-you-cast-your-apple-iphone-14-pro-max-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>How Can You Cast Your Apple iPhone 14 Pro Max to Windows PC With Ease? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-and-disable-the-windows-key/"><u>How to Enable and Disable the Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-disabled-windows-update-service/"><u>Immediate Actions for Disabled Windows Update Service</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-nokia-c22-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Nokia C22? Try These Fixes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-xiaomi-redmi-k70-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Xiaomi Redmi K70 to iPod | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-augment-folder-context-menus/"><u>Innovative Ways to Augment Folder Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-your-windows-overcome-geforce-experience-failures/"><u>Mend Your Windows: Overcome GeForce Experience Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-lag-and-enhance-fps-in-roblox-win-edition/"><u>Minimize Lag & Enhance FPS in Roblox Win Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-access-denied-save-issues-on-windows/"><u>Navigating Through Access Denied Save Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-1110-setup-with-rightful-permissions/"><u>Navigating Windows 11/10 Setup with Rightful Permissions</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-macs-top-rated-mkv-trimming-software/"><u>New Macs Top-Rated MKV Trimming Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-utorrent-performance-in-win-os/"><u>Optimizing uTorrent Performance in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-update-obstacles-with-these-fixes/"><u>Overcome Update Obstacles with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-protection-activating-tpm-and-secure-boot-before-w11-update/"><u>Prioritize Protection: Activating TPM and Secure Boot Before W11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapidly-reach-word-definitions-on-your-system/"><u>Rapidly Reach Word Definitions on Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-broken-system-defragmenter-execution/"><u>Rectifying Broken System Defragmenter Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-functional-headphonesspeakers-in-windows/"><u>Resolving Non-Functional Headphones/Speakers in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-connection-between-windows-11-and-print-devices/"><u>Restoring Connection Between Windows 11 and Print Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-11-admin-details-effectively/"><u>Revamp Your Windows 11 Admin Details Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-emulated-titles-in-playnite/"><u>Seamless Integration of Emulated Titles in Playnite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slick-techniques-for-masking-windows-11-task-view/"><u>Slick Techniques for Masking Windows 11 Task View</u></a></li>
<li><a href="https://tech-hub.techidaily.com/speak-up-5-techniques-to-command-chatgpt-through-voice-commands/"><u>Speak Up: 5 Techniques to Command ChatGPT Through Voice Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-non-detectable-windows-commands/"><u>Strategies for Fixing Non-Detectable Windows Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-roblox-unrecoverable-errors/"><u>Strategies to Overcome Roblox Unrecoverable Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-divine-interface-capabilities-in-windows-11/"><u>Tap Into Divine Interface Capabilities in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-archival-steganography-in-photos-windows-11/"><u>The Art of Archival Steganography in Photos (Windows 11)</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-strength-of-details-why-hdr-triumphs-over-sdr-for-2024/"><u>The Strength of Details  Why HDR Triumphs Over SDR for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-failures-on-older-windows-versions/"><u>Troubleshooting Installer Failures on Older Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unbreakable-passwords-top-four-managers-for-the-new-windows-edition/"><u>Unbreakable Passwords: Top Four Managers for the New Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-speed-minimizing-applications-via-keyboard-shortcuts/"><u>Unleash Speed: Minimizing Applications via Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-media-maker-tool-error-x90017-on-windows/"><u>Unraveling Media Maker Tool Error X.90017 On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-guide-to-opening-quick-capture-utility/"><u>Windows 11 Guide to Opening Quick Capture Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-out-0x800f0831-windows-troubleshoot-guide/"><u>Zeroing Out 0X800F0831: Windows Troubleshoot Guide</u></a></li>
</ul></div>
