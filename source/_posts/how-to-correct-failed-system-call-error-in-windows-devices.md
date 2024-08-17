---
title: How to Correct Failed System Call Error in Windows Devices
date: 2024-08-16T02:42:13.215Z
updated: 2024-08-17T02:42:13.215Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct Failed System Call Error in Windows Devices
excerpt: This Article Describes How to Correct Failed System Call Error in Windows Devices
keywords: Fixing System Calls on Windows,Resolving Device Errors,Troubleshooting WinError,Handling OS System Fails,Correcting Call Failures,Debugging Devices in Windows,Fix Failed System Calls
thumbnail: https://thmb.techidaily.com/907f940c68ac3ee45f8b59683cc047cc04665184817513adef7255fa53df8a70.jpg
---

## How to Correct Failed System Call Error in Windows Devices

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-immediate-strategies-for-enhancing-your-thumbnail-designs/"><u>[New] In 2024, Immediate Strategies for Enhancing Your Thumbnail Designs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pioneering-teams-changing-vrs-course/"><u>[New] Pioneering Teams Changing VR's Course</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-effortless-editing-in-obs-studio-with-top-5-hacks/"><u>[Updated] 2024 Approved  Effortless Editing in OBS Studio with Top 5 Hacks</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-audiovisual-pro-perfect-ppt-presentation-recording/"><u>[Updated] Audiovisual Pro  Perfect PPT Presentation Recording</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-post-a-picture-on-youtube/"><u>[Updated] How to Post a Picture on YouTube</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovative-strategies-to-enhance-tiktoks/"><u>[Updated] Innovative Strategies to Enhance TikToks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-ultimate-top-11-list-excellent-audio-devices-for-2024/"><u>[Updated] Ultimate Top 11 List  Excellent Audio Devices for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-ultimate-guide-to-gopro-karma-performance/"><u>2024 Approved  The Ultimate Guide to GoPro Karma Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-upcoming-license-expiration-error-in-w10w11/"><u>Addressing Upcoming License Expiration Error in W10/W11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/amazon-prime-fan-favorites-highest-likes-and-view-counts-for-2024/"><u>Amazon Prime Fan Favorites  Highest Likes & View Counts for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/best-in-class-vertical-mice-for-enhanced-productivity-and-comfort/"><u>Best-in-Class Vertical Mice for Enhanced Productivity and Comfort</u></a></li>
<li><a href="https://extra-hints.techidaily.com/bridging-worlds-fusing-photos-into-majestic-tiles-for-2024/"><u>Bridging Worlds  Fusing Photos Into Majestic Tiles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-entry-point-issues-on-windows-systems/"><u>Bypassing Entry Point Issues on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-failed-operations-code-0x0000011b-fixes/"><u>Eliminating 'Failed' Operations: Code 0X0000011B Fixes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhancing-microsoft-window-os-render-capabilities/"><u>Enhancing Microsoft Window OS Render Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-hyper-v-enablement-in-win11/"><u>Essential Guide to Hyper-V Enablement in Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-red-to-ready-8-methods-to-mend-your-monochrome-misstep/"><u>From Red to Ready: 8 Methods to Mend Your Monochrome Misstep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-files-fix-incessant-file-explorer-opens/"><u>Halt Files: Fix Incessant File Explorer Opens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-the-widgets-toolbar-in-windows-11/"><u>How to Enable the Widgets Toolbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-store-error-0x80072f17-on-windows/"><u>How to Fix Microsoft Store Error 0X80072F17 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-halt-automatic-windows-11-reboots/"><u>How to Halt Automatic Windows 11 Reboots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-unfoldable-folders-in-win1110-on-double-clicks/"><u>How to Overcome Unfoldable Folders in Win11/10 on Double-Clicks</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-seamlessly-update-your-webcam-software-in-windows-7/"><u>How to Seamlessly Update Your Webcam Software in Windows 7</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-vivo-v30-lite-5g-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Vivo V30 Lite 5G without App | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/master-the-pairing-process-of-a-logitech-mouse-in-simple-steps/"><u>Master the Pairing Process of a Logitech Mouse in Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-low-power-mode-options/"><u>Navigating Through Windows' Low-Power Mode Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-windows-horizon-surpassing-11s-achievements/"><u>Next Windows Horizon: Surpassing 11'S Achievements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-pc-invalid-name-issue-on-windows-11/"><u>Overcoming PC Invalid Name Issue on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-programs-syncing-your-windows-pc-with-android/"><u>Perfect Programs: Syncing Your Windows PC with Android</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quick-fixes-enhancing-images-in-windows-10s-photos-editor/"><u>Quick Fixes  Enhancing Images in Windows 10'S Photos Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-photo-import-discrepancies-between-ios-and-windows-11/"><u>Remedying Photo Import Discrepancies Between iOS and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-hyper-v-feature-from-windows-11-builds/"><u>Removing Hyper-V Feature From Windows 11 Builds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-ragnarok-overcoming-x-script-woes/"><u>Restoring Ragnarok: Overcoming X-Script Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-a-frozen-system-interface/"><u>Resuscitating a Frozen System Interface</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/rewind-and-repeat-mastering-youtube-inversion-for-2024/"><u>Rewind and Repeat  Mastering YouTube Inversion for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-methods-for-launching-wordpad-in-windows/"><u>Simplified Methods for Launching WordPad in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-9-techniques-for-flawless-powerpoint-prints-in-windows/"><u>Solving the Puzzle: 9 Techniques for Flawless PowerPoint Prints in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/space-saving-savvy-master-windows-11s-minimalist-method/"><u>Space-Saving Savvy: Master Windows 11'S Minimalist Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-crashing-drivers-on-modern-windows-oses/"><u>Tackling Crashing Drivers on Modern Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unreachable-mb-status-on-windows-11-systems/"><u>Tackling Unreachable MB Status on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-cmd-interface-a-step-by-step-process/"><u>Tailoring CMD Interface: A Step-by-Step Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-techniques-for-analyzing-drive-space-using-diskusage-commands/"><u>The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-giants-of-online-interaction-understanding-facebook-twitter-instagram-and-youtube/"><u>The Giants of Online Interaction: Understanding Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-erratic-print-device-in-os/"><u>Troubleshooting Erratic Print Device in OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-potential-of-your-computers-shortcut-keys-for-size-adjustment-on-win11/"><u>Unleash the Potential of Your Computer's Shortcut Keys for Size Adjustment on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-efficiency-crafted-keybinds-for-snippet-pasting-in-windows-11/"><u>Unleashing Efficiency: Crafted Keybinds for Snippet Pasting in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-better-words-best-windows-software-for-scribes/"><u>Unlock Better Words: Best Windows Software for Scribes</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-gopro-video-editing-for-dummies-a-free-and-easy-to-follow-guide/"><u>Updated In 2024, GoPro Video Editing for Dummies A Free and Easy-to-Follow Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unlock-prime-deal-revealed/"><u>Windows 11 Unlock: Prime Deal Revealed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>