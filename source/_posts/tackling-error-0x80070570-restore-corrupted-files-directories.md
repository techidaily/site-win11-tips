---
title: "Tackling Error 0X80070570: Restore Corrupted Files, Directories"
date: 2024-09-01T05:13:45.530Z
updated: 2024-09-02T05:13:45.530Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Error 0X80070570: Restore Corrupted Files, Directories"
excerpt: "This Article Describes Tackling Error 0X80070570: Restore Corrupted Files, Directories"
keywords: XboxErrorRestoration,FileCorruptionRecovery,DirectoryErrorsSolve,ErrorCodeX8070570,SystemFileRepair,DataIntegrityMaintain,WindowsErrorHandling
thumbnail: https://thmb.techidaily.com/5dda734007d0cce4f616f2328d041526d598c5a6fb318adf671f70aacd812852.jpg
---

## Tackling Error 0X80070570: Restore Corrupted Files, Directories

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-exploring-whatsapps-sound-transfers/"><u>[New] Exploring WhatsApp's Sound Transfers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-insta-ode-selecting-song-lyrics-and-beats-for-vids/"><u>[New] In 2024, The Insta-Ode  Selecting Song Lyrics and Beats for Vids</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-impact-of-instant-subscribing-on-online-viewing-habits/"><u>[New] The Impact of Instant Subscribing on Online Viewing Habits</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-expert-strategies-for-choosing-ideal-youtube-banner-dimensions/"><u>[Updated] In 2024, Expert Strategies for Choosing Ideal YouTube Banner Dimensions</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-top-7-affordable-solutions-to-watch-movies-on-pcs/"><u>[Updated] In 2024, Top 7 Affordable Solutions to Watch Movies on PCs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-insiders-guide-to-dynamic-and-engaging-tiktok-edits/"><u>[Updated] The Insider's Guide to Dynamic and Engaging TikTok Edits</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-the-blueprint-to-youtube-wealth-smart-strategies-for-facebook-video-marketing/"><u>2024 Approved  The Blueprint to YouTube Wealth  Smart Strategies for Facebook Video Marketing</u></a></li>
<li><a href="https://win-dash.techidaily.com/audigy-fx-graphics-and-audio-drivers-for-enhanced-gaming-experience-download-now/"><u>Audigy FX Graphics & Audio Drivers for Enhanced Gaming Experience - Download Now!</u></a></li>
<li><a href="https://facebook.techidaily.com/breaking-new-structure-for-facebook-interfaces/"><u>Breaking: New Structure for Facebook Interfaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-email-service-failures-on-windows-error-0x800713f/"><u>Correcting Email Service Failures on Windows (Error 0X800713F)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/decoding-why-your-facebook-messages-dont-share-videos-androidios-for-2024/"><u>Decoding Why Your Facebook Messages Don't Share Videos (Android/iOS) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dynamic-wallpaper-integration-a-windows-11-essential-tutorial/"><u>Dynamic Wallpaper Integration: A Windows 11 Essential Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-access-to-bing-ai-via-windows-11-keyboard-shortcuts/"><u>Efficient Access to Bing AI via Windows 11 Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-techniques-to-extract-large-amounts-of-data-at-once/"><u>Efficient Techniques to Extract Large Amounts of Data at Once</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-serene-power-with-the-best-aio-a-comprehensive-look-at-hytes-thicc-q6-similar-problem/"><u>Experience Serene Power with the Best AIO - A Comprehensive Look at Hyte's THICC Q6 # Similar Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-overcoming-the-most-common-update-issues/"><u>Expert Advice: Overcoming the Most Common Update Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-reboot-windows-update-components/"><u>Guidelines to Reboot Windows Update Components</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-dolby-advanced-audio-cannot-be-launched-in-windows-10/"><u>How to Fix 'Dolby Advanced Audio' Cannot Be Launched in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-the-system32-folder-in-windows-11/"><u>How to Open the System32 Folder in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Xiaomi Redmi Note 12 4G? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-comprehensively-capturing-your-messenger-conversations/"><u>In 2024, Comprehensively Capturing Your Messenger Conversations</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-nubia-red-magic-9-proplus-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Nubia Red Magic 9 Pro+</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-screen-mirroring-apple-iphone-x-to-tv-or-pc-drfone-by-drfone-ios/"><u>In 2024, How Screen Mirroring Apple iPhone X to TV or PC? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Tecno Spark Go (2023)? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joyous-jingles-tickling-tech-with-windows-software/"><u>Joyous Jingles: Tickling Tech with Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-profits-with-windows-11-a-closer-look/"><u>Making Profits with Windows 11 - A Closer Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-filters-for-safe-browsing/"><u>Mastering Windows Filters for Safe Browsing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pin-display-in-the-windows-11-menu/"><u>Maximizing Pin Display in the Windows 11 Menu</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/maximizing-screen-real-estate-on-fb-media/"><u>Maximizing Screen Real Estate on Fb Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-hassle-fixing-11-common-windows-11-anomalies/"><u>No More Hassle: Fixing 11 Common Windows 11 Anomalies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-through-pc-problems-master-these-20-cmd-commands/"><u>Power Through PC Problems: Master These 20 CMD Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-windows-systems-into-high-efficiency-video-land-with-tdarr-tools/"><u>Propel Windows Systems Into High-Efficiency Video Land with Tdarr Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-unreliable-keys-on-the-windows-snipper/"><u>Quick Fixes for Unreliable Keys on the Window's Snipper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-address-windows-task-sequence-fails-0x8007000f/"><u>Quick Fixes to Address Windows Task Sequence Fails 0X8007000F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-solution-for-local-sam-service-error-signal/"><u>Quick Solution for 'Local SAM Service' Error Signal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-energy-levels-after-high-living-in-windows/"><u>Reviving Energy Levels After High Living in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-windows-11-temp-directory-functionality/"><u>Secure Windows 11 Temp Directory Functionality</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simplified-steps-comprehensive-method-for-picking-out-selected-messages-on-gmail/"><u>Simplified Steps: Comprehensive Method for Picking Out Selected Messages on Gmail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-non-respectful-windows-11-sticky-notes-sync/"><u>Solving Non-Respectful Windows 11 Sticky Notes Sync</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-flush-methods-for-your-windows-domain-nameservers/"><u>Strategic Flush Methods for Your Windows Domain Nameservers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-implement-spatial-sound-on-windows-11/"><u>Strategies to Implement Spatial Sound on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-keyboard-use-eliminate-delay-in-windows-11s-typing-process/"><u>Swift Keyboard Use: Eliminate Delay in Windows 11'S Typing Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-off-windows-11s-hyper-v-service/"><u>Switching Off Windows 11'S Hyper-V Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-system-for-optimal-performance-with-new-windows-and-linux-blend/"><u>Tailoring Your System for Optimal Performance With New Windows and Linux Blend</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-users-guide-to-task-filtering-and-theme-tweaking-in-windows-11/"><u>The Complete User's Guide to Task Filtering & Theme Tweaking in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essence-of-windows-cab-files-and-execution-procedures/"><u>The Essence of Windows Cab Files & Execution Procedures</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-essentials-of-high-quality-audio-interfaces-in-podcasting-for-2024/"><u>The Essentials of High-Quality Audio Interfaces in Podcasting for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-windows-drawers-eclipsing-procreate/"><u>Top 5 Windows Drawers Eclipsing Procreate</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-picks-the-ultimate-guide-to-the-most-exceptional-mirrorless-camera-lenses/"><u>Top Picks: The Ultimate Guide to the Most Exceptional Mirrorless Camera Lenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-manipulate-windows-11-search-highlights/"><u>Tricks to Manipulate Windows 11 Search Highlights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlock-spark-ars-full-potential-with-personalized-lut-implementations-for-2024/"><u>Unlock Spark AR's Full Potential with Personalized LUT Implementations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-code-0x800f0831-the-troubleshoot-tome/"><u>Unraveling Code 0X800f0831: The Troubleshoot Tome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-another-users-ms-error-issue/"><u>Unraveling the Another User’s MS Error Issue</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-avi-video-editing-on-a-budget-top-5-free-options-for-2024/"><u>Updated AVI Video Editing on a Budget Top 5 Free Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-overcoming-the-hypervisor-bsod-crash/"><u>Win 10/11: Overcoming the HYPERVISOR BSOD Crash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-experience-in-ultraportables/"><u>Windows Experience in Ultraportables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-notes-problem-solver-steps-to-reopen-your-missing-notepad/"><u>Windows Notes Problem Solver: Steps to Reopen Your Missing Notepad</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>