---
title: Essential Guide to Fixing Authentication in Windows OS
date: 2024-08-16T02:46:50.865Z
updated: 2024-08-17T02:46:50.865Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Guide to Fixing Authentication in Windows OS
excerpt: This Article Describes Essential Guide to Fixing Authentication in Windows OS
keywords: WinAuth Fix Guide,Auth Error Resolution,Windows Login Repair,Credential Validation Help,OS Security Adjustment,Passwd Recovery Steps,User Authentication Update
thumbnail: https://thmb.techidaily.com/d2b04d63fd86cc82b6222341c74adf6327b494c09e7a92e5a7589ca57209ebbc.jpg
---

## Essential Guide to Fixing Authentication in Windows OS

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-efficient-backup-of-camera-roll-to-share-via-snapchat-for-2024/"><u>[New] Efficient Backup of Camera Roll to Share via Snapchat for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-generating-a-signature-tiktok-keyphrase/"><u>[New] Generating a Signature TikTok Keyphrase</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-navigating-common-video-downloadupload-pitfalls-on-fb-for-2024/"><u>[New] Navigating Common Video Download/Upload Pitfalls on FB for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-podcasting-from-afar-a-guide/"><u>[New] Podcasting From Afar  A Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-top-ranked-apps-for-video-conferencing-and-collaboration/"><u>[Updated] 2024 Approved  Top-Ranked Apps for Video Conferencing and Collaboration</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-strategies-for-tackling-copyright-claims-on-youtube-for-2024/"><u>[Updated] Expert Strategies for Tackling Copyright Claims on YouTube for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-iphones-premier-video-tools-pick-cameo-over-filmorago/"><u>[Updated] IPhone's Premier Video Tools  Pick Cameo Over FilmoraGo?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-complete-guide-to-captivating-your-audience-on-snapchat-for-2024/"><u>[Updated] The Complete Guide to Captivating Your Audience on Snapchat for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-download-mastery-quick-tiktok-video-retrieval/"><u>2024 Approved  Download Mastery  Quick TikTok Video Retrieval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-open-disk-management-in-windows-11-and-11/"><u>4 Ways to Open Disk Management in Windows 11 and 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/big-catch-bigger-views-top-5-aquatic-cameras/"><u>Big Catch, Bigger Views - Top 5 Aquatic Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-admin-restrictions-on-windows-safety-settings/"><u>Bypassing Admin Restrictions on Windows Safety Settings</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-honor-100-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Honor 100 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-obstacles-for-secure-memory-settings-in-new-windows-11/"><u>Clearing Obstacles for Secure Memory Settings in New Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/dissecting-obs-technology-for-top-level-recording/"><u>Dissecting OBS Technology for Top-Level Recording</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/echo-dot-vs-homepod-mini-face-off-identifying-critical-contrasts/"><u>Echo Dot Vs. HomePod Mini Face-Off: Identifying Critical Contrasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-cleaning-for-a-functional-windows-11-space/"><u>Effortless Cleaning for a Functional Windows 11 Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-keyboard-commands-to-sharpen-your-3d-skills/"><u>Essential Keyboard Commands to Sharpen Your 3D Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-fixes-for-non-responsive-backlight-on-windows-pcs/"><u>Five Fixes for Non-Responsive Backlight on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fn-key-techniques-for-efficient-windows-use/"><u>Fn Key Techniques for Efficient Windows Use</u></a></li>
<li><a href="https://tech-haven.techidaily.com/four-primary-techniques-for-state-regulation-of-advanced-ai-systems/"><u>Four Primary Techniques for State Regulation of Advanced AI Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-camera-saving-errors/"><u>Guiding Through Windows Camera Saving Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-build-custom-text-transcription-software-on-windows-with-whisper/"><u>How to Build Custom Text Transcription Software on Windows with Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-windows-applications-without-admin-rights/"><u>How to Manage Windows Applications Without Admin Rights</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-captivate-audiences-with-these-top-20-tiktok-captions/"><u>In 2024, Captivate Audiences with These Top 20 TikTok Captions</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mini-2-and-air-2s-luts-free-trial-then-paid-upgrade/"><u>In 2024, Mini 2 & Air 2S LUTS - Free Trial, Then Paid Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insiders-look-at-windows-boot-configuration-management/"><u>Insider's Look at Windows Boot Configuration Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-directories-a-breeze-with-win11-essentials/"><u>Making Directories a Breeze with Win11 Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-resolution-of-windows-error-1132-in-zoom/"><u>Master the Resolution of Window's Error 1132 in Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-disconnects-and-fixes-javascript-issues-in-discord-win-11/"><u>Mastering Disconnects & Fixes: JavaScript Issues in Discord Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-windows-file-not-found-error/"><u>Methods to Overcome Windows 'File Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-windows-11-shutdown-time-for-tasks-in-progress/"><u>Modifying Windows 11 Shutdown Time for Tasks in Progress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-security-faults-and-fixes/"><u>Navigating Through Windows Security Faults & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-overcoming-d3d11-gpu-hurdles-in-w11w10/"><u>Quick Guide to Overcoming D3D11 GPU Hurdles in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-writing-rights-denied-on-windows-devices/"><u>Remedying Writing Rights Denied on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-empty-folder-error-message-on-win-11/"><u>Removing the 'Empty Folder' Error Message on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-glitches-with-ps/"><u>Resolving Windows Glitches with PS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-offline-lsa-warning/"><u>Steps to Address Offline LSA Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-dual-user-microsoft-errors/"><u>Strategies to Resolve Dual User Microsoft Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-patch-up-reviving-synapse-in-latest-windows/"><u>System Patch-Up: Reviving Synapse in Latest Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-case-for-how-win11-wins-over-macos/"><u>The Case For: How Win11 Wins over macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-11-password-strategy/"><u>Transforming Windows 11 Password Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-chkdsk-sfc-vs-dism-in-os-maintenance/"><u>Understanding CHKDSK, SFC Vs. DISM in OS Maintenance</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/unpacking-the-latest-tech-marvel-from-minisforum-dual-display-support-amd-ryzen-9-cpu-and-rtx-graphics-powered-mini-pc/"><u>Unpacking the Latest Tech Marvel From Minisforum – Dual Display Support, AMD Ryzen 9 CPU and RTX Graphics Powered Mini PC</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unraveling-computer-secrets-with-insights-from-toms-hardware-hub/"><u>Unraveling Computer Secrets with Insights From Tom's Hardware Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-to-optimal-windows-audios-through-driver-revision/"><u>Upgrading to Optimal Windows Audios Through Driver Revision</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>