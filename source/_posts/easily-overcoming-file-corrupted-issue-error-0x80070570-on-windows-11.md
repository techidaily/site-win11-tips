---
title: Easily Overcoming File Corrupted Issue (Error 0X80070570) on Windows 11
date: 2024-12-01T19:47:27.689Z
updated: 2024-12-06T17:28:15.105Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://extra-skills.techidaily.com/new-mastering-selective-sharpening-photo-editing-techniques/"><u>[New] Mastering Selective Sharpening Photo Editing Techniques</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-tranquil-twilight-tales-in-video-form/"><u>[Updated] Tranquil Twilight Tales in Video Form</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-unwrapped-in-depth-look-at-screenflow-v4-on-macos/"><u>[Updated] Unwrapped In-Depth Look at ScreenFlow v4 on macOS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-day-after-evaluation-new-approaches/"><u>2024 Approved Day After Evaluation New Approaches</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-seamless-sharing-linking-youtube-to-insta-stories/"><u>2024 Approved Seamless Sharing Linking YouTube to Insta Stories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dormant-dreams-windows-computers-at-rest/"><u>Dormant Dreams: Windows Computers at Rest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-your-computers-pace-with-enhanced-mouse-speed/"><u>Ease Your Computer’s Pace with Enhanced Mouse Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-video-memory-crashes-in-hogwarts-educational-fantasy-game/"><u>Eliminating Video Memory Crashes in Hogwarts Educational Fantasy Game</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disconnected-print-devices-on-windows-pc/"><u>Fixing Disconnected Print Devices on Windows PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/nailing-your-live-on-facebook-a-recorders-manual-for-2024/"><u>Nailing Your Live on Facebook A Recorder's Manual for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-storage-retention-strategy/"><u>Optimize Windows Storage Retention Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-approach-preventing-unexpected-obs-studio-error/"><u>Proactive Approach: Preventing Unexpected OBS Studio Error</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/resolving-itunes-update-issues-for-a-smooth-music-experience-on-windows-and-macos/"><u>Resolving iTunes Update Issues for a Smooth Music Experience on Windows & macOS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-stop-your-computers-blinking-cursor-issue/"><u>Troubleshooting: Stop Your Computer's Blinking Cursor Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-solutions-to-operation-failure-error-0x0000011b-in-windows-11/"><u>Unlocking Solutions to Operation Failure (Error 0X0000011B) in Windows 11</u></a></li>
</ul></div>

