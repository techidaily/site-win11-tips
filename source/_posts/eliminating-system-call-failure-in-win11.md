---
title: Eliminating System Call Failure in Win11
date: 2024-08-16T02:40:39.963Z
updated: 2024-08-17T02:40:39.963Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating System Call Failure in Win11
excerpt: This Article Describes Eliminating System Call Failure in Win11
keywords: Win11 Call Failures,Fixing Syscalls,Win11 Stability,No Syscall Errors,Win11 Optimize,Call Failure Solutions,Secure Windows 11
thumbnail: https://thmb.techidaily.com/3cdd3221236d54f354b9655c53899223c63a3525ea895a2e29db68bcb7da9bba.jpg
---

## Eliminating System Call Failure in Win11

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
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
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select **Quarantine** and **Yes** if Malwarebytes detects malware.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-how-to-optimize-facebook-seo-with-10-surefire-ways/"><u>[New] 2024 Approved  How to Optimize Facebook SEO with 10 Surefire Ways</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-tailor-videos-for-impact-on-instagram-feed/"><u>[New] 2024 Approved  Tailor Videos for Impact on Instagram Feed</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-become-a-videographer-essentials-of-recording-with-logitech-for-2024/"><u>[New] Become a Videographer  Essentials of Recording with Logitech for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-become-an-expert-in-real-time-streaming-on-facebook-platform/"><u>[New] Become an Expert in Real-Time Streaming on Facebook Platform</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-fb-live-lite-minute-videos-for-you-for-2024/"><u>[New] FB Live Lite  Minute Videos for You for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-safe-sharing-starts-here-the-copyright-check-for-tiktok-videos-for-2024/"><u>[New] Safe Sharing Starts Here  The Copyright Check for TikTok Videos for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-expert-techniques-for-streamers-on-macos/"><u>[Updated] In 2024, Expert Techniques for Streamers on macOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlocking-the-secrets-of-a-captivating-end-episode-note/"><u>[Updated] Unlocking the Secrets of a Captivating End-Episode Note</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-dns-cache-via-steam-settings/"><u>Clearing Windows DNS Cache via Steam Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compute-disk-space-efficiently-via-powershell-commands/"><u>Compute Disk Space Efficiently via PowerShell Commands</u></a></li>
<li><a href="https://extra-hints.techidaily.com/creating-dynamic-time-lapse-with-your-gopro-hero-series/"><u>Creating Dynamic Time-Lapse with Your GoPro Hero Series</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/disable-screen-lock-on-honor-70-lite-5g-by-drfone-android-unlock-android-unlock/"><u>Disable screen lock on Honor 70 Lite 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-audio-recording-the-windows-11-handbook/"><u>Easy Audio Recording: The Windows 11 Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-archived-media-madvr-for-windows-enthusiasts/"><u>Enhance Archived Media: MadVR for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tactics-to-eliminate-isdonedll-errors/"><u>Expert Tactics to Eliminate ISDone.dll Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disk-read-windows-error-immediately/"><u>Fixing 'Disk Read' Windows Error Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-empty-folder-alerts-for-windows-users/"><u>Fixing Empty Folder Alerts for Windows Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/free-gaming-music-archives-no-restrictions-for-2024/"><u>Free Gaming Music Archives (No Restrictions) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-turn-off-microsofts-voice-assistant/"><u>Guide to Turn Off Microsoft's Voice Assistant</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-forbidden-you-dont-have-permission-to-access-on-this-server-error-on-windows/"><u>How to Fix the “Forbidden: You Don’t Have Permission to Access / On This Server” Error on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-oppo-a78-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Oppo A78 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfersync-notes-from-apple-iphone-7-plus-to-ipad-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer/Sync Notes from Apple iPhone 7 Plus to iPad | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-tecno-spark-20-pro-phone-by-drfone-android/"><u>How to Unlock a Network Locked Tecno Spark 20 Pro Phone?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Lava Blaze 2 5G? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-a-thorough-examination-recmeisters-screen-capture-innovations/"><u>In 2024, A Thorough Examination  Recmeister's Screen Capture Innovations</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-on-iphone-15-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock On iPhone 15 You Should Try Out</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-honor-90-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Honor 90 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-logic-how-to-quickly-examine-ethernet-performance/"><u>Latency Logic: How to Quickly Examine Ethernet Performance</u></a></li>
<li><a href="https://screen-recording.techidaily.com/master-class-on-managing-desktopmobile-screens-in-meet-for-2024/"><u>Master Class on Managing Desktop/Mobile Screens in Meet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-system-security-turning-on-controlled-access-in-windows-11/"><u>Mastering System Security: Turning On Controlled Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-directory-management-without-renaming-feature-in-win-11/"><u>Mastering the Art of Directory Management without Renaming Feature in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-pin-gallery-space-in-windows-11/"><u>Maximize Your Pin Gallery Space in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-playtime-configuring-amd-card-in-windows-games/"><u>Perfecting Playtime: Configuring AMD Card in Windows Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-lost-steam-connections-on-pc/"><u>Quick Fixes for Lost Steam Connections on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restart-your-path-ccleaner-woes-on-win11/"><u>Restart Your Path: CCleaner Woes on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-sync-path-for-android-plus-windows-duo/"><u>Step-by-Step Sync Path for Android + Windows Duo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-chrome-freeze-in-windows/"><u>Steps to Overcome Chrome Freeze in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-windows-alt-key-problems/"><u>Strategies to Correct Windows ALT Key Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-temporary-file-extraction-in-windows-os/"><u>Streamlining Temporary File Extraction in Windows OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-asus-rog-phone-8-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Asus ROG Phone 8 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-addressing-faulty-or-missing-device-alerts-win1011/"><u>Tips for Addressing Faulty or Missing Device Alerts, Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-20-essential-cmd-tricks-for-beginners/"><u>Top 20 Essential CMD Tricks for Beginners</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-free-ae-template-packs-for-amateurs/"><u>Top FREE AE Template Packs for Amateurs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-documents-innovative-text-edits-with-snipt-tool/"><u>Transform Your Documents: Innovative Text Edits with Snipt Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-gaming-mastering-playstation-1-titles-on-win-with-duckstations-tips/"><u>Transform Your Gaming: Mastering PlayStation 1 Titles on WIN with Duckstation's Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-a-faulty-windows-enter-keysystem/"><u>Troubleshooting a Faulty Windows 'Enter' Keysystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-from-thx-spatial-issues/"><u>Unblocking Windows From THX Spatial Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-network-potential-through-dns-on-windows-11/"><u>Unlocking Network Potential Through DNS on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-nas-on-smartphones-and-tablets/"><u>Utilizing NAS on Smartphones and Tablets</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/vimeo-vs-youtube-differences-between-vimeo-and-youtube/"><u>Vimeo vs YouTube  Differences Between Vimeo and YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1110-resolving-code-xc0000142-failure/"><u>Windows 11/10: Resolving Code XC0000142 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-folder-confluence-techniques-for-users/"><u>Windows Folder Confluence: Techniques for Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>