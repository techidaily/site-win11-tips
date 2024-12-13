---
title: Eradicating Error 0X80070570 & Repairing Files in Windows 11 OS
date: 2024-12-07T22:43:57.170Z
updated: 2024-12-12T23:11:22.336Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating Error 0X80070570 & Repairing Files in Windows 11 OS
excerpt: This Article Describes Eradicating Error 0X80070570 & Repairing Files in Windows 11 OS
keywords: Fix Windows 11 ZeroError,Eradicate Win11 FS Error,Resolve WinXPatch_070570,Eliminate WinOS 11 Fail,Correct Windows FS Error,Rectify 0X80070570 Issue,Cure XP11 File Corruption
thumbnail: https://thmb.techidaily.com/75e496d7d03af882c809a7273c9e1eb1d9baeae9a3a5a4a6ed566b778061c9ff.png
---

## Eradicating Error 0X80070570 & Repairing Files in Windows 11 OS

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-cross-platform-iptv-adaptability/"><u>[New] In 2024, Cross-Platform IPTV Adaptability</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-breaking-down-the-barriers-to-knowing-your-fans/"><u>[Updated] Breaking Down the Barriers to Knowing Your Fans</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-top-video-editors-for-youtube-on-the-houseno-cost-included/"><u>2024 Approved Top Video Editors for YouTube on the House—No Cost Included</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-google-docs-transcription-your-complete-manual/"><u>2024 Approved Unlocking Google Docs Transcription Your Complete Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-turning-off-geforce-visual-boost-effects/"><u>Command: Turning Off GeForce Visual Boost Effects</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/e-identity-a-quick-walkthrough-of-customizing-your-youtube-url/"><u>Create Identity A Quick Walkthrough of Customizing Your YouTube Url</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-did-your-iphone-7-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>In 2024, Did Your iPhone 7 Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-in-ar-games-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Simulate GPS Movement in AR games On Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-task-manager-from-rearranging-programs/"><u>Prevent Task Manager From Rearranging Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-implementing-a-text-bar-with-an-icon-in-windows-11/"><u>Re-Implementing a Text Bar with an Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sprinter-mouse-click-techniques-for-speedy-dual-taps/"><u>Sprinter Mouse Click Techniques for Speedy Dual Taps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-steam-functionality-fixing-errors-in-win11/"><u>Streamlining Steam Functionality: Fixing Errors in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-crucial-role-of-bsod-in-system-restoration/"><u>The Crucial Role of BSoD in System Restoration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-strategies-to-unstall-verification-errors-in-windows-setup/"><u>Top 9 Strategies to Unstall Verification Errors in Windows Setup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-what-to-do-when-xinput13dll-is-unavailable/"><u>Troubleshooting: What To Do When 'xinput1_3.dll' Is Unavailable?</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-powerhouse-2020-apple-mac-mini-m1-chip-surpassing-rival-computers/"><u>Unveiling the Powerhouse: 2020 Apple Mac Mini (M1 Chip) - Surpassing Rival Computers</u></a></li>
</ul></div>

