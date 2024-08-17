---
title: Mending the Corrupted File Issue in Windows 11 OS (Error 0X80070570)
date: 2024-08-16T02:25:35.810Z
updated: 2024-08-17T02:25:35.810Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mending the Corrupted File Issue in Windows 11 OS (Error 0X80070570)
excerpt: This Article Describes Mending the Corrupted File Issue in Windows 11 OS (Error 0X80070570)
keywords: Windows 11 Error Code 0X80070570,Fix File Corruption Error,OS Windows File Repair,Win11 File Compatibility Issue,Troubleshoot Windows File Problems,Resolve 0X80070570 Error,Mend Windows Files Error 0X8007
thumbnail: https://thmb.techidaily.com/a6603b4c8e64882a75258ea91034b33184d3edc319264524a7b728bfe67ef7f7.jpg
---

## Mending the Corrupted File Issue in Windows 11 OS (Error 0X80070570)

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
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

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-how-to-blur-faces-or-objects-in-youtube-videos/"><u>[New] 2024 Approved  How to Blur Faces or Objects in YouTube Videos</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-mirrorless-innovation-taking-over-dslr-in-videos/"><u>[New] 2024 Approved  Mirrorless Innovation Taking Over DSLR in Videos?</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-elite-soundtrack-choices-for-film-and-vlogs-for-2024/"><u>[New] Elite Soundtrack Choices for Film & Vlogs for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-leveraging-whiteboards-across-ios-android-and-desktop-zoom-sessions/"><u>[New] In 2024, Leveraging Whiteboards Across iOS, Android & Desktop Zoom Sessions</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-restore-missing-watch-artwork/"><u>[New] In 2024, Restore Missing Watch Artwork</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-dichotomy-of-digital-immersion-in-vr/"><u>[New] The Dichotomy of Digital Immersion in VR</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-dynamics-of-youtubes-creator-payments/"><u>[New] The Dynamics of YouTube's Creator Payments</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-how-to-fix-live-video-interrupted-on-facebook-in-2024/"><u>[Updated] How to Fix Live Video Interrupted on Facebook, In 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-smooth-transitions-with-illustrators-blur-effects/"><u>[Updated] Smooth Transitions with Illustrator's Blur Effects</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-the-best-6-gopro-mounts-for-seamless-capture/"><u>[Updated] Unveiling the Best 6 GoPro Mounts for Seamless Capture</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-unlock-the-full-potential-of-group-video-conferencing-on-your-android-device-zoom/"><u>2024 Approved  Unlock the Full Potential of Group Video Conferencing on Your Android Device (Zoom)</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveil-gadgets-top-15-unboxing-clips/"><u>2024 Approved  Unveil Gadgets  Top 15 Unboxing Clips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-warning-indicators-that-call-for-a-full-reboot/"><u>5 Warning Indicators That Call For a Full Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-batch-installing-apps-using-winstall-in-windows-11/"><u>A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-chrome-clock-error-ahead-or-behind-windows-edition/"><u>Adjusting Chrome Clock Error: Ahead or Behind? (Windows Edition)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818172681-amds-graphics-evolution-upgraded-hd-6950-windows-10-driver/"><u>AMD's Graphics Evolution: Upgraded HD 6950 Windows 10 Driver!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-prose-with-these-5-pc-apps/"><u>Boost Your Prose with These 5 PC Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-path-to-successful-screen-startup-post-update/"><u>Clearing the Path to Successful Screen Startup Post-Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-office-365-issue-code-30015-26/"><u>Correcting Office 365 Issue: Code 30015-26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrease-overhead-memory-use-by-antivirus-programs/"><u>Decrease Overhead Memory Use by Antivirus Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-mobility-control-deactivation-win-11/"><u>Dive Into Mobility Control Deactivation (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-monitoring-ram-gpu-and-cpu-status-guide/"><u>Efficient System Monitoring: RAM, GPU, and CPU Status Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-language-skills-quick-translate-via-windows-key-combinations/"><u>Elevate Language Skills: Quick Translate via Windows Key Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-note-taking-with-obsidians-artistic-touch/"><u>Elevate Note-Taking with Obsidian's Artistic Touch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-communication-translate-foreign-words-with-hotkeys/"><u>Enhance Communication: Translate Foreign Words with Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-webp-visualization-with-these-excellent-tools/"><u>Enhance WebP Visualization with These Excellent Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-digital-desktop-with-engaging-time-themed-screensavers-using-these-5-tools/"><u>Enhance Your Digital Desktop with Engaging Time-Themed Screensavers Using These 5 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-finest-windows-11-drawers-here/"><u>Explore the Finest Windows 11 Drawers Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-csgo-start-problems-on-w11/"><u>Fixing CS:GO Start Problems on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-message-display-on-discord-desktop/"><u>Fixing Failed Message Display on Discord Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-move-and-copy-to-folder-context-menu-options-in-windows-11-and-11/"><u>How to Add a Move and Copy to Folder Context Menu Options in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-bluetooth-pin-verification-hitch-on-win11w10-pcs/"><u>How To Fix Bluetooth PIN Verification Hitch on Win11/W10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-unopened-sharing-error-on-w10w11/"><u>How to Rectify Unopened Sharing Error on W10/W11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-on-apple-iphone-15-pro-max-by-drfone-ios/"><u>How To Remove the Two Factor Authentication On Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/impact-analysis-removal-of-windows-11-taskbars-chatting-function/"><u>Impact Analysis: Removal of Windows 11 Taskbar's Chatting Function</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-nubia-red-magic-9-pro-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-4-methods-to-turn-off-life-360-on-honor-magic-vs-2-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Methods to Turn off Life 360 On Honor Magic Vs 2 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-motorola-moto-g04-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-from-iphone-14-plus-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account From iPhone 14 Plus?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-quick-iphone-photo-fixes-expert-hacks-for-better-snapshots/"><u>In 2024, Quick iPhone Photo Fixes  Expert Hacks for Better Snapshots</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-uncovering-average-earnings-podcaster-edition/"><u>In 2024, Uncovering Average Earnings  Podcaster Edition</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/navigating-easy-cross-posting-of-tiktok-videos-on-fb-for-2024/"><u>Navigating Easy Cross-Posting of TikTok Videos on FB for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-window-11-mails-default-html-settings-for-clarity/"><u>Overhauling Window 11 Mail's Default HTML Settings for Clarity</u></a></li>
<li><a href="https://screen-capture.techidaily.com/real-time-broadcasting-obs-to-instagram/"><u>Real-Time Broadcasting  OBS to Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-not-enough-memory-available-problem-windows-vmware/"><u>Remedies for 'Not Enough Memory Available' Problem (Windows VmWare)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-overlapping-app-images-in-os-interface/"><u>Removing Overlapping App Images in OS Interface</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/s-most-popular-video-reversal-websites-for-2024/"><u>S Most Popular Video Reversal Websites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correctly-installing-an-ms-store-app/"><u>Steps for Correctly Installing an MS Store App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-enabling-non-standard-windows-apps/"><u>Strategies for Enabling Non-Standard Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-gaming-how-to-fix-the-error-code-0x000-in-xbox-game-pass-on-windows-11/"><u>Streamlining Your Gaming: How to Fix the Error Code 0X000_ in Xbox Game Pass on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-up-with-microsoft-sql-on-malwarebytes-after-disconnect/"><u>Syncing Up with Microsoft SQL on Malwarebytes After Disconnect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-mystery-of-win11s-disconnected-5g-wi-fi/"><u>Tackling the Mystery of Win11's Disconnected 5G Wi-Fi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-pcs-display-lock-settings/"><u>Tailor Your PC's Display Lock Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-clear-microsofts-watchdog-logs-on-windows/"><u>Techniques to Clear Microsoft's Watchdog Logs on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-rise-of-autonomous-computing-with-windows/"><u>The Rise of Autonomous Computing with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-windows-tips-top-20-cmd-commands/"><u>Transformative Windows Tips: Top 20 CMD Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-mending-exception-error-on-win-os/"><u>Understanding and Mending Exception Error on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-winservicesexe-deciphering-windows-process/"><u>Understanding WinServices.exe: Deciphering Windows Process</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unleashing-creativity-with-aes-best-text-presets-for-2024/"><u>Unleashing Creativity with AE's Best Text Presets for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/unlocking-iphone-x-secrets-restoring-face-id-functionality/"><u>Unlocking iPhone X Secrets  Restoring Face ID Functionality</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Huawei P60 | Dr.fone</u></a></li>
</ul></div>
