---
title: How to Tackle File Corruption Problems (Error 0X80070570) on Windows 11
date: 2024-08-08T11:07:30.769Z
updated: 2024-08-09T11:07:30.769Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Tackle File Corruption Problems (Error 0X80070570) on Windows 11
excerpt: This Article Describes How to Tackle File Corruption Problems (Error 0X80070570) on Windows 11
keywords: Fixing Error 0X80070570,Windows 11 Corruption Solve,Win11 File Recovery Steps,Stop Windows Error 70570,Tackle X70 Corruption Issue,Addressing XP07 Corrupted Files,Troubleshoot 0X80070570 on Win11
thumbnail: https://thmb.techidaily.com/b461869fdc65b7a58affdd23329a3336b55cdb42a5e0550c353e9047546c19d2.jpg
---

## How to Tackle File Corruption Problems (Error 0X80070570) on Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-precision-timing-crafting-your-ideal-video-conference/"><u>[New] 2024 Approved  Precision Timing  Crafting Your Ideal Video Conference</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-pick-and-personalize-gospel-ringtones-effectively/"><u>[New] How to Pick and Personalize Gospel Ringtones Effectively</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-harnessing-viral-potential-the-20-best-tiktok-caption-insights/"><u>[New] In 2024, Harnessing Viral Potential  The 20 Best TikTok Caption Insights</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-a-comprehensive-guide-to-capturing-your-hp-pcs-display/"><u>[Updated] 2024 Approved  A Comprehensive Guide to Capturing Your HP PC's Display</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-streaming-stations-beyond-ustream-reviews/"><u>[Updated] 2024 Approved  Streaming Stations  Beyond Ustream Reviews</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-optimize-your-video-consumption-the-guide-to-auto-play-youtube-on-facebook/"><u>[Updated] In 2024, Optimize Your Video Consumption  The Guide to Auto-Play Youtube on Facebook</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-overcoming-grey-screens-in-gaming-recording/"><u>[Updated] In 2024, Overcoming Grey Screens in Gaming Recording</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-srt-file-conversion-simplified-with-os-support/"><u>[Updated] SRT File Conversion Simplified with OS Support</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-syncopated-mix-management-in-sonar-by-platinum-for-2024/"><u>[Updated] Syncopated Mix Management in Sonar by Platinum for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-transforming-your-facebook-history-a-look-back-video-guide-for-2024/"><u>[Updated] Transforming Your Facebook History  A Look Back Video Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-put-a-windows-computer-to-sleep/"><u>9 Ways to Put a Windows Computer to Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-via-cli-registry-edition/"><u>Advanced Windows Customization via CLI: Registry Edition</u></a></li>
<li><a href="https://video-capture.techidaily.com/alter-macs-screen-capture-store-path-for-2024/"><u>Alter Mac's Screen Capture Store Path for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/best-practices-in-setting-up-your-playstation-4s-webcam-location/"><u>Best Practices in Setting Up Your PlayStation 4'S Webcam Location</u></a></li>
<li><a href="https://extra-information.techidaily.com/breaking-code-seeing-covert-user-reactions/"><u>Breaking Code  Seeing Covert User Reactions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-your-path-upgrading-outdated-windows-driver-tech/"><u>Clear Your Path: Upgrading Outdated Windows Driver Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-non-successful-updates-in-windows-discord/"><u>Dealing with Non-Successful Updates in Windows Discord</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/dissecting-vidmas-recording-features-a-technical-breakdown/"><u>Dissecting Vidma's Recording Features - A Technical Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-windows-subsystem-enhance-linux-presence/"><u>Does Windows Subsystem Enhance Linux Presence?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/easy-steps-on-how-to-create-a-new-apple-id-account-on-apple-iphone-8-plus-by-drfone-ios/"><u>Easy Steps on How To Create a New Apple ID Account On Apple iPhone 8 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-mouse-game-with-cross-border-powertoys-techniques/"><u>Elevate Your Mouse Game with Cross-Border PowerToys Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-update-faults-windows-xp-x8019/"><u>Eradicating Update Faults: Windows XP, X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evaluating-the-need-for-maintaining-pagefilesys-filespace/"><u>Evaluating the Need for Maintaining Pagefile.sys Filespace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-0x0000004e-in-windows-a-quick-guide/"><u>Fixing Error 0X0000004E in Windows: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-eliminate-path-error-in-windows/"><u>Guide to Eliminate PATH Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-failures-from-windows-memory-tool/"><u>How To Rectify Failures From Windows Memory Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-speed-up-epic-games-launcher-downloads-on-windows/"><u>How to Speed Up Epic Games Launcher Downloads on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-nubia-red-magic-9-proplus-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Nubia Red Magic 9 Pro+ to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-14-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 14 Plus without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-boosting-youtube-descriptions-with-expert-templates/"><u>In 2024, Boosting YouTube Descriptions with Expert Templates</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-apple-iphone-13-mini-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From Apple iPhone 13 mini Lock Screen | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sony-s6700-latest-features-reviewed/"><u>In 2024, Sony S6700  Latest Features Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-find-feature-in-windows-11-taskbar-activation-guide/"><u>Instant Find Feature in Windows 11 Taskbar – Activation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-craft-of-simultaneous-unzipping-with-windows-tools/"><u>Master the Craft of Simultaneous Unzipping with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restarting-windows-updates/"><u>Mastering the Art of Restarting Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-lockout-try-these-hacks/"><u>Microsoft Store Lockout? Try These Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-challenges-in-full-screen-snip-and-sketch-capturing/"><u>Overcoming Challenges in Full-Screen Snip & Sketch Capturing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/plotting-prime-promotional-summaries-for-2024/"><u>Plotting Prime Promotional Summaries for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-time-shifts-on-windows-a-guide/"><u>Preventing Time Shifts on Windows: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-efficient-task-management-in-ms-project/"><u>Quick and Efficient Task Management in MS Project</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-c55-video-recovery-recover-deleted-videos-from-realme-c55-by-fonelab-android-recover-video/"><u>Realme C55 Video Recovery - Recover Deleted Videos from Realme C55</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recognizing-unseen-sd-card-fix-for-windows-explorer/"><u>Recognizing Unseen SD Card: Fix for Windows Explorer</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-play-8t-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Play 8T</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-domain-services-error-printer-issues-in-windows-11/"><u>Repairing Domain Services Error: Printer Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-fatal-0xf0831-bug/"><u>Resolving Windows 11'S Fatal 0xF0831 Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-0x800713f-mail-glitch/"><u>Resolving Windows' 0X800713F Mail Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-data-flow-from-non-responsive-usb-devices-win-os/"><u>Restoring Data Flow From Non-Responsive USB Devices (Win OS)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-switching-on-updated-widget-selection-interface-in-windows-11/"><u>Seamlessly Switching on Updated Widget Selection Interface in Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-poco-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Poco C55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stuck-battlenet-login-screen/"><u>Solutions for Stuck Battle.net Login Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-captioning-hurdles-on-windows-10-devices/"><u>Solving Common Captioning Hurdles on Windows 10 Devices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-by-step-mastery-windows-11-media-import-simplified/"><u>Step-by-Step Mastery  Windows 11 Media Import Simplified</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-operations-7-easy-tips-for-advanced-windows-11-users/"><u>Streamline Operations: 7 Easy Tips for Advanced Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-full-advantage-of-windows-11-features/"><u>Take Full Advantage of Windows 11 Features</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/top-10-screen-capture-solutions-to-enhance-instruction-for-2024/"><u>Top 10 Screen Capture Solutions to Enhance Instruction for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-your-onedrive-to-a-desired-spot-on-win10/"><u>Transitioning Your OneDrive to a Desired Spot on Win10</u></a></li>
<li><a href="https://program-issues.techidaily.com/ultimate-fix-for-spellbreak-no-more-pc-freezing-or-crashing-issues/"><u>Ultimate Fix for Spellbreak - No More PC Freezing or Crashing Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-users-should-anticipate-sudo/"><u>Why Windows Users Should Anticipate Sudo</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>