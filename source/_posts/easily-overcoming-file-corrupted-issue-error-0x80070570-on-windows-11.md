---
title: Easily Overcoming File Corrupted Issue (Error 0X80070570) on Windows 11
date: 2024-11-22T18:08:32.195Z
updated: 2024-11-27T18:11:20.532Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easily Overcoming File Corrupted Issue (Error 0X80070570) on Windows 11
excerpt: This Article Describes Easily Overcoming File Corrupted Issue (Error 0X80070570) on Windows 11
keywords: Fix Error 0X80070570,Win11 File Corruption Solve,Overcome File Error Windows,Resolve 0X80070570 Issue,Correcting Windows 11 Files,Eliminate Corrupt File Error,Fix XP70 Corrupted Problem
thumbnail: https://thmb.techidaily.com/8404aae8332517e90ea13209ccbcb49d56b9cbe41228f9bbeee698b42d6caf34.jpg
---

## Easily Overcoming File Corrupted Issue (Error 0X80070570) on Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-fine-tune-your-cinematography-mastering-kinemaster-zoom-features/"><u>[New] Fine-Tune Your Cinematography Mastering Kinemaster Zoom Features</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-charting-a-course-to-riches-youtubes-monetary-milestones/"><u>[New] In 2024, Charting a Course to Riches YouTube's Monetary Milestones</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-vector-journey-start-categories-tools-and-initial-steps/"><u>[Updated] In 2024, Vector Journey Start Categories, Tools, & Initial Steps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-science-behind-youtube-video-upload-cycles-and-their-impact-on-engagement/"><u>[Updated] The Science Behind YouTube Video Upload Cycles and Their Impact on Engagement</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-emulating-old-hollywood-style-in-modern-videos/"><u>2024 Approved Emulating Old Hollywood Style in Modern Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-disguise-dos-and-donts-mastering-zip-concealment-windows-11/"><u>Digital Disguise Dos and Don'ts: Mastering ZIP Concealment (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-developer-skills-github-desktop-on-win-11/"><u>Empower Your Developer Skills: Github Desktop on Win 11</u></a></li>
<li><a href="https://solve-help.techidaily.com/get-the-latest-official-version-of-winx-dvd-copy-pro-at-no-cost/"><u>Get the Latest Official Version of WinX DVD Copy Pro at No Cost!</u></a></li>
<li><a href="https://driver-download.techidaily.com/instantly-upgrade-with-razer-mamba-drivers-free-download-available-now/"><u>Instantly Upgrade with Razer Mamba Drivers - Free Download Available Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-ip-and-mac-extraction-in-windows-with-powershell/"><u>Mastering IP & MAC Extraction in Windows with PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-tactics-fixing-blank-login-on-windows-11/"><u>Precision Tactics: Fixing Blank Login on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timely-access-control-with-powertoys-locksmith/"><u>Timely Access Control with PowerToys Locksmith</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-print-management-with-windows-11s-tools-max-56-chars/"><u>Winning at Print Management with Windows 11'S Tools (Max 56 Chars)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    