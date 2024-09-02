---
title: Fixing System Call Issues on Windows 11 & 11
date: 2024-09-01T05:16:43.215Z
updated: 2024-09-02T05:16:43.215Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing System Call Issues on Windows 11 & 11
excerpt: This Article Describes Fixing System Call Issues on Windows 11 & 11
keywords: Win11_SystemCalls,FixWindowsCallIssue,Windows11SyscallFix,ResolveWin11CallError,SyscallProblemsWin11,Windows11CallTroubleshoot,Windows11CallsFixSolution
thumbnail: https://thmb.techidaily.com/94567bf4df3b715033d93123bd31d8eb4bb0ab79d545d1676a1f32d06cb990c5.jpg
---

## Fixing System Call Issues on Windows 11 & 11

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-becoming-a-youtube-star-utilizing-the-power-of-featured-channels/"><u>[New] 2024 Approved  Becoming a Youtube Star  Utilizing the Power of Featured Channels</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-ultimate-guide-to-video-capture-obs-versus-bandicam/"><u>[New] 2024 Approved  The Ultimate Guide to Video Capture  OBS versus Bandicam</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-vidgrabmaster-mobilepc-app-downloads/"><u>[New] 2024 Approved  VidGrabMaster  Mobile/PC App Downloads</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-enrich-your-knowledge-student-approved-history-youtubes-to-watch-for-2024/"><u>[New] Enrich Your Knowledge  Student-Approved History YouTubes To Watch for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-facebook-insights-how-to-use-it-for-beginners/"><u>[New] In 2024, Facebook Insights  How to Use It for Beginners</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-top-5-best-ps2-emulator-for-ios-for-2024/"><u>[New] Top 5 Best PS2 Emulator for Ios for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-adding-dimension-to-text-in-adobe-illustrator/"><u>[Updated] Adding Dimension to Text in Adobe Illustrator</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-celebrating-matrimony-the-best-wedding-movies-from-youtube-to-vimeo-for-2024/"><u>[Updated] Celebrating Matrimony  The Best Wedding Movies From YouTube to Vimeo for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-evolving-shopper-behavior-in-vr-realms/"><u>[Updated] Evolving Shopper Behavior in VR Realms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-inside-movavis-innovation-journey-video-editor-pro-2024-review/"><u>[Updated] Inside Movavi's Innovation Journey – Video Editor Pro 2024 Review</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-dynamic-duality-balancing-white-and-black/"><u>2024 Approved  Dynamic Duality  Balancing White and Black</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-optimal-space-stewards-premium-service-review/"><u>2024 Approved  Optimal Space Stewards  Premium Service Review</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-unleashing-revenue-with-review-videos-of-household-items/"><u>2024 Approved  Unleashing Revenue with Review Videos of Household Items</u></a></li>
<li><a href="https://fox-http.techidaily.com/a-comprehensive-tutorial-on-powerpoint-voice-to-text-conversion/"><u>A Comprehensive Tutorial on PowerPoint Voice to Text Conversion</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/bringing-text-to-life-a-guide-to-dynamic-animation-methods-for-2024/"><u>Bringing Text to Life  A Guide to Dynamic Animation Methods for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-activation-lock-from-iphone-14-pro-4-easy-ways-by-drfone-ios/"><u>Bypass Activation Lock From iPhone 14 Pro - 4 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-new-username-assignments-in-windows-11-edition/"><u>Conquering New UserName Assignments in Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-install-failed-disconnect-for-win-11-discord/"><u>Correcting the 'Install Failed' Disconnect for Win 11 Discord</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/decoding-revenue-how-much-do-creators-earn-on-youtube-in-2024/"><u>Decoding Revenue  How Much Do Creators Earn on Youtube, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-hidden-power-of-windows-reliability-and-performance-monitors/"><u>Decoding the Hidden Power of Windows' Reliability & Performance Monitors</u></a></li>
<li><a href="https://win-answers.techidaily.com/defeat-dreamlight-valleys-pc-hiccups-discover-the-top-six-solutions-to-game-crashes/"><u>Defeat Dreamlight Valley's PC Hiccups: Discover the Top Six Solutions to Game Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-action-turning-esd-to-iso-on-windows-instantly/"><u>Efficiency in Action: Turning ESD to ISO on Windows Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-notifications-game-on-windows-11/"><u>Elevate Your Notifications Game on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-driver-failure-error-on-windows-11-pc/"><u>Eliminating Driver Failure Error on Windows 11 PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/embrace-the-art-of-timelapses-a-comprehensive-ipad-tutorial/"><u>Embrace the Art of Timelapses  A Comprehensive iPad Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-with-customized-keyboard-tricks/"><u>Enhance Productivity with Customized Keyboard Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-solve-windows-0x80070141-connectivity-issues/"><u>Essential Tips to Solve Windows' 0X80070141 Connectivity Issues</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-analysis-of-the-samsung-galaxy-s10-the-epitome-of-luxury-and-performance/"><u>Expert Analysis of the Samsung Galaxy S10: The Epitome of Luxury and Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-insight-efficiently-identify-hdd-vs-ssd-type-on-windows/"><u>Expert Insight: Efficiently Identify HDD vs SSD Type on Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-reviews-and-buying-guides-by-toms-technology-hub/"><u>Expert Reviews & Buying Guides by Tom’s Technology Hub</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723011112024-fix-that-frustrating-microsoft-word-error-in-just-five-steps/"><u>Fix That Frustrating Microsoft Word Error in Just Five Steps</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-oneplus-11r-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your OnePlus 11R FRP Locks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-game-ready-nvidia-drivers-for-your-windows-gaming-system/"><u>Get the Newest Game-Ready NVIDIA Drivers for Your Windows Gaming System</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-oppo-f25-pro-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Oppo F25 Pro 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-poco-m6-5g-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Poco M6 5G Fingerprint Lock</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-lock-apps-on-samsung-galaxy-m14-4g-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Samsung Galaxy M14 4G to Protect Your Individual Information</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-to-the-code-how-to-fix-keystrokes-in-win10/"><u>Key to the Code: How to Fix Keystrokes in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11s-entry-point-for-peak-performance/"><u>Maximizing Windows 11'S Entry Point for Peak Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-should-focus-on-making-windows-11-better-not-just-more-fun/"><u>Microsoft Should Focus on Making Windows 11 Better, Not Just More Fun</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-hurdles-restoring-access-to-notepad/"><u>Navigating Through Windows' Hurdles: Restoring Access to Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-visual-impact-activate-windows-11s-color-management/"><u>Optimize Your Visual Impact - Activate Windows 11'S Color Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-gpu-load-with-proven-wm-fixes-on-windows/"><u>Optimizing GPU Load with Proven WM Fixes on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-frozen-pc-lock-screen-wait-time-issue/"><u>Overcoming Frozen PC Lock Screen Wait Time Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-system-hurdle-windows-c0000022-resolution-guide/"><u>Overcoming System Hurdle: Windows C0000022 Resolution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-task-manager-halt-on-pcs/"><u>Overcoming Task Manager Halt on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-warnings-about-unverified-application-in-windows-os/"><u>Overcoming Warnings About Unverified Application in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-windows-11-control-panel/"><u>Overhauling Your Windows 11 Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-windows-zoom-disruptions-fatal-error-1132/"><u>Preventing Windows Zoom Disruptions - Fatal Error 1132</u></a></li>
<li><a href="https://extra-skills.techidaily.com/quick-srt-text-conversion-a-modern-how-to-for-2024/"><u>Quick SRT Text Conversion  A Modern How-To for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-active-state-for-windows-11-context-menu/"><u>Reinstating Active State for Windows 11 Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-error-code-0xc1900101-in-windows-11-update/"><u>Remedying Error Code 0XC1900101 in Windows 11 Update</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723010171379-resolved-issues-with-launching-civilization-vi-on-windows-10-fixed/"><u>Resolved: Issues with Launching Civilization VI on Windows 10 – Fixed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-excessive-cpu-consumption-by-vanguards-ums-in-windows/"><u>Resolving Excessive CPU Consumption by Vanguard's UMS in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-controlled-chromeedge-use-in-enterprise-environments/"><u>Simplifying Controlled Chrome/Edge Use in Enterprise Environments</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/splitcam-examination-camera-quality-showdown-in-2024/"><u>SplitCam Examination - Camera Quality Showdown, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steady-your-system-five-approaches-to-resolve-secure-boot-errors/"><u>Steady Your System: Five Approaches to Resolve Secure Boot Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-way-through-fax-cover-customization-in-win11/"><u>Streamlining Your Way Through Fax Cover Customization in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-disarm-frozen-app-block-on-windows/"><u>Techniques to Disarm Frozen App Block on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-checklist-for-a-premium-4k-lens-buy/"><u>The Ultimate Checklist for a Premium 4K Lens Buy</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-guide-to-adding-effects-in-tiktok-videos/"><u>The Ultimate Guide to Adding Effects in TikTok Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-pc-performance-monitors-in-windows/"><u>Top 6 PC Performance Monitors in Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-failed-iphone-computer-pairing-quick-solutions/"><u>Troubleshoot Failed iPhone-Computer Pairing - Quick Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-stuck-on-size-errors-in-win11-discord-with-ease/"><u>Troubleshooting Stuck-On-Size Errors in Win11 Discord with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-boots-with-5-key-fixes-to-security-errors/"><u>Unlock Windows Boots with 5 Key Fixes to Security Errors</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-over-a-shaky-desktop-pointer-with-these-steps/"><u>Win Over a Shaky Desktop Pointer with These Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-the-war-against-failed-chromebook-file-uploads-win-wise/"><u>Win the War Against Failed Chromebook File Uploads, WIN-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-arm-installation-iso-file-journey/"><u>Windows 11 ARM Installation: ISO File Journey</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>