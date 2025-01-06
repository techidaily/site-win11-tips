---
title: Decoding and Overcoming Windows Error Code 0X80070570 for You
date: 2025-01-01T16:18:11.893Z
updated: 2025-01-06T05:50:26.753Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding and Overcoming Windows Error Code 0X80070570 for You
excerpt: This Article Describes Decoding and Overcoming Windows Error Code 0X80070570 for You
keywords: Fixing Window's Error 0X80070570,Resolving 0X80070570 Windows Error,Troubleshooting Error Code 0X80070570,Overcoming Windows Error 0X80070570,Fixing Window's 0X80070570 Issue,Resolving 0X80070570 System Error,Troubleshoot Error 0X80070570 Windows
thumbnail: https://thmb.techidaily.com/18e0761348cb4d28e3480c4ed08a893497db31dc39159b03c85adcc25dd9aaa4.jpg
---

## Decoding and Overcoming Windows Error Code 0X80070570 for You

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-zero.techidaily.com/he-complete-blueprint-to-tally-your-youtube-growth-and-income/"><u>[New] The Complete Blueprint to Tally Your YouTube Growth and Income</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-essential-tags-to-amplify-your-youtube-gaming-channel/"><u>[Updated] Essential Tags to Amplify Your YouTube Gaming Channel</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-complete-beginners-guide-to-utilizing-look-up-tables-luts/"><u>[Updated] The Complete Beginner’s Guide to Utilizing Look-Up Tables (LUTs)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-obtain-exclusive-free-media-from-elite-4-youtube-clips/"><u>2024 Approved Obtain Exclusive Free Media From Elite 4 YouTube Clips</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-never-turns-off-on-windows-11-fix/"><u>Bluetooth Never Turns Off on Windows 11 [Fix]</u></a></li>
<li><a href="https://sound-issues.techidaily.com/breaking-the-silence-effective-fixes-for-world-of-warcrafts-sound-problems/"><u>Breaking the Silence: Effective Fixes for World of Warcraft's Sound Problems</u></a></li>
<li><a href="https://some-tips.techidaily.com/choosing-between-the-macbook-pro-and-macbook-air-a-comprehensive-guide-on-selecting-your-ideal-apple-notebook/"><u>Choosing Between the MacBook Pro and MacBook Air: A Comprehensive Guide on Selecting Your Ideal Apple Notebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-way-activatedeactivate-energy-saving-feature/"><u>Effortless Way: Activate/Deactivate Energy-Saving Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embracing-dark-themes-in-ms-paint/"><u>Embracing Dark Themes in MS Paint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-and-using-the-revamped-widget-picker-toolset/"><u>Enabling and Using the Revamped Widget Picker Toolset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enlarge-pins-display-area-in-win-11/"><u>How to Enlarge Pins Display Area in Win 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/invisible-stories-unveiled-a-complete-snapguide/"><u>Invisible Stories Unveiled A Complete Snapguide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-event-log-repair/"><u>Mastering Windows Event Log Repair</u></a></li>
<li><a href="https://win11.techidaily.com/project-prowess-with-powerful-key-combinations/"><u>Project Prowess with Powerful Key Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-to-reset-failed-windows-discord-updates/"><u>Quick Tips to Reset Failed Windows Discord Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-login-simplified-top-5-fixes-for-key-conflicts-on-windows-11-networks/"><u>Secure Login Simplified: Top 5 Fixes for Key Conflicts on Windows 11 Networks</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-indicator-static-widgets-on-pc-monitor/"><u>Speed Indicator: Static Widgets on PC Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/websites-on-hold-seven-steps-to-resuscitate-them-in-windows/"><u>Websites On Hold? Seven Steps to Resuscitate Them in Windows</u></a></li>
</ul></div>

