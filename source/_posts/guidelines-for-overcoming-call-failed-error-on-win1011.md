---
title: Guidelines for Overcoming 'Call Failed' Error on Win10/11
date: 2024-08-16T01:54:53.674Z
updated: 2024-08-17T01:54:53.674Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines for Overcoming 'Call Failed' Error on Win10/11
excerpt: This Article Describes Guidelines for Overcoming 'Call Failed' Error on Win10/11
keywords: Call Fail Fix Guide,Windows Phone Error Solution,Resolve Call Error 512,Win10 Call Fail Fix Tips,Overcome Call Failed on Windows,Troubleshoot Mobile Call Issue,Windows 10/11 Call Problems
thumbnail: https://thmb.techidaily.com/d6abae0f7e3d8fb5f7c3d204845ee10283f20e49e0d3d6312bf5d54b51961985.jpg
---

## Guidelines for Overcoming 'Call Failed' Error on Win10/11

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer
![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## 2\. Run the SFC and DISM Tools in Command Prompt
![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Check For Disk Errors With CHKDSK

 A failing hard drive is another potential cause of the “system call failed” error. You can check for and repair disk errors with the Check Disk (CHKDSK) tool on Windows.

 Our [how to run CHKDSK](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) guide explains how you can utilize the Check Disk tool.

## 4\. Initiate a Malwarebytes Scan

 Malware can cause many kinds of crashes to occur on Windows. The “system call failed” error could be occurring because of malware on your PC.

 You can scan for malware with many antivirus apps, including Windows Security. However, Malwarebytes is one of the [best free antivirus software for Windows](https://www.makeuseof.com/tag/ten-best-antivirus-programs/). So, try running a Malwarebytes scan like this:

1. Go to the [Malwarebytes download page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2028435/https://www.malwarebytes.com/mwb-download) and download the tool from there.
2. Open the **MBSetup** file from your Downloads folder and click **Install**.
3. Next, click **Skip** if you don’t want to install the additional software offered.
4. Select **Open Malwarebytes** to run the software.
5. Click **Scan** to initiate a malware scan.  
![The Scan option in Malwarebytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-scan-option.jpg)
6. Select **Quarantine** and **Yes** if Malwarebytes detects malware.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-infinite-save-instagram-stories-secret-weapon/"><u>[New] 2024 Approved  Infinite Save  Instagram Stories' Secret Weapon</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-smiles-snorts-and-sighs-the-finest-meme-accounts-on-ig/"><u>[New] 2024 Approved  Smiles, Snorts & Sighs  The Finest Meme Accounts on IG</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-best-cameras-elevating-podcast-engagement/"><u>[New] Best Cameras Elevating Podcast Engagement</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-boost-creativity-with-free-audio-effects-online-for-2024/"><u>[New] Boost Creativity with Free Audio Effects Online for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-making-dreams-real-steps-towards-becoming-a-vtuber-for-2024/"><u>[New] From Making Dreams Real  Steps Towards Becoming a VTuber for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-maximize-your-setup-with-best-8-5k-tvs/"><u>[New] Maximize Your Setup with Best 8 5K Tvs</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-rapid-video-filming-techniques-for-tiktok-success/"><u>[New] Rapid Video Filming Techniques for TikTok Success</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-a-step-by-step-path-to-authentic-selfie-verification-on-ig/"><u>[Updated] 2024 Approved  A Step-by-Step Path to Authentic Selfie Verification on IG</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-rise-of-the-alternative-top-3-video-sharing-websites/"><u>[Updated] 2024 Approved  Rise of the Alternative  Top 3 Video Sharing Websites</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-expanding-reach-fb-live-on-broadcast-networks/"><u>[Updated] Expanding Reach  FB Live on Broadcast Networks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-secrets-to-procuring-gratis-picture-frame-media/"><u>[Updated] Secrets to Procuring Gratis Picture Frame Media</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-gopro-hero5-session-review/"><u>2024 Approved  GoPro Hero5 Session Review</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-quick-guide-eliminating-photo-viewer-crashes-on-windows-10/"><u>2024 Approved  Quick Guide  Eliminating Photo Viewer Crashes on Windows 10</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-scout-platforms-securing-partnerships-with-youtube-content-creators/"><u>2024 Approved  Scout Platforms  Securing Partnerships with YouTube Content Creators</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/audience-wow-factor-how-to-create-spectacular-live-streams/"><u>Audience Wow Factor  How to Create Spectacular Live Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-to-resetting-faulty-google-nearby-share/"><u>Comprehensible Guide to Resetting Faulty Google Nearby Share</u></a></li>
<li><a href="https://win11-tips.techidaily.com/core-applications-of-visual-cplusplus-redistributables/"><u>Core Applications of Visual C++ Redistributables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-malfunctioning-windows-diagnostic-tools/"><u>Correcting Malfunctioning Windows Diagnostic Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-7-indicative-windows-activities-of-malware/"><u>Deciphering 7 Indicative Windows Activities of Malware</u></a></li>
<li><a href="https://program-issues.techidaily.com/effortless-fixes-to-tackle-discord-javascripter-bugs/"><u>Effortless Fixes to Tackle Discord JavaScripter Bugs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pen-performance-tackling-issues-in-windows-tablets/"><u>Enhance Pen Performance: Tackling Issues in Windows Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focused-file-exploring-unleash-windowed-space-potential/"><u>Focused File Exploring: Unleash Windowed Space Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-tackle-windows-11s-0x800f0922-update-error/"><u>Guide to Tackle Windows 11'S 0X800F0922 Update Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-the-dns-client-service-in-windows-11/"><u>How to Configure the DNS Client Service in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-blank-login-screen-in-windows-10-and-11/"><u>How to Fix a Blank Login Screen in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-attach-the-usb-device-error-in-virtualbox-on-windows/"><u>How to Fix the Failed to Attach the USB Device Error in VirtualBox on Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-lock-apps-on-poco-m6-pro-5g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Poco M6 Pro 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-off-high-contrast-mode-on-windows/"><u>How to Turn Off High Contrast Mode on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increase-your-productivity-in-windows-with-flow-launcher/"><u>Increase Your Productivity in Windows With Flow Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-advanced-tactics-for-group-policy-optimization/"><u>Leveraging Advanced Tactics for Group Policy Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-efficiency-in-windows-1011-with-top-rated-productivity-tools/"><u>Master Efficiency in Windows 10/11 with Top-Rated Productivity Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-reactivating-explore-in-windows-11os/"><u>Mastery over Reactivating Explore in Windows 11OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-operation-failure-error-0x0000011b-in-windows-11/"><u>Mitigating Operation Failure (Error: 0X0000011B) in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-the-basics-of-window-aids-with-ease/"><u>Navigate the Basics of Window Aids with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-asana-compatibility-hurdles-with-windows/"><u>Overcoming Asana Compatibility Hurdles with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-responsive-input-devices-in-windows/"><u>Overcoming Non-Responsive Input Devices in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-irritating-steam-error-code-e84/"><u>Quick Fixes for the Irritating Steam Error Code E84</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silencing-the-disruptive-noise-irq-tuning-guide/"><u>Silencing the Disruptive Noise: IRQ Tuning Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-mbs-unable-to-link-error-on-win11/"><u>Strategies to Resolve MB's Unable to Link Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-finding-your-missing-steam-controllers/"><u>The Ultimate Guide to Finding Your Missing Steam Controllers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-way-to-cut-out-unwanted-onedrive-in-explorer/"><u>The Way to Cut Out Unwanted OneDrive in Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-techniques-for-resolving-failed-image-import-from-ios-devices/"><u>Tips and Techniques for Resolving Failed Image Import From iOS Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-resolving-windows-7-bsod-with-stop-code-0x0000007e/"><u>Troubleshooting Guide: Resolving Windows 7 BSOD with Stop Code 0X0000007E</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-compilation-prime-top-10-android-apps-for-facebook-video-download/"><u>Updated Compilation  Prime Top 10 Android Apps for Facebook Video Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-isnt-ideal-for-computer-renovation/"><u>Why Windows Isn't Ideal for Computer Renovation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-pro-key-grab-the-best-offers-and-save-money/"><u>Windows 11 Pro Key: Grab the Best Offers and Save Money</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-not-working-quick-windows-solution-guide/"><u>Xbox Not Working: Quick Windows Solution Guide</u></a></li>
</ul></div>
