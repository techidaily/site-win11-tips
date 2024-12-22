---
title: Solving Corrupted File Error 0X80070570 on Modern Windows OSes
date: 2024-12-14T19:48:01.482Z
updated: 2024-12-21T23:18:15.239Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Corrupted File Error 0X80070570 on Modern Windows OSes
excerpt: This Article Describes Solving Corrupted File Error 0X80070570 on Modern Windows OSes
keywords: Fix File Error 0X80070570,Uncorrupt Files Windows,Resolve 0X80070570 Error,Troubleshoot File Corruption WinOS,Clear 0X80070570 Error ModernWin,Fixing 0xError on Windows Files,Overcome Corrupted Files 0X80070570
thumbnail: https://thmb.techidaily.com/e8d9fb9f5398f4a792320d2b13c1a57276ee28fb817fc4d294eae20885dd4758.jpg
---

## Solving Corrupted File Error 0X80070570 on Modern Windows OSes

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-glue.techidaily.com/new-expert-analysis-of-sonys-high-definition-video-gear/"><u>[New] Expert Analysis of Sony's High-Definition Video Gear</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/avigating-youtube-music-eclecticism/"><u>[New] Navigating YouTube Music Eclecticism</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-whats-the-best-youtube-thumbnail-size/"><u>[Updated] What's the Best YouTube Thumbnail Size?</u></a></li>
<li><a href="https://discover-cheats.techidaily.com/44cm5asx44kp44km44gf6zplusz5aow44ov44kh44kk44or44ks5yplusw44kk5oi744gz44gf44kb44gu44og44kv44ol44od44kv44go44os44oz44oi44cn/"><u>「失われた音声ファイルを取り戻すためのテクニックとヒント」</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-geforce-now-error-0xc0f1103f-in-windows-10-and-11/"><u>How to Fix the GeForce Now Error 0Xc0f1103f in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-malwarebytes-runtime-error-could-not-call-proc-issue-in-windows-1110/"><u>How to Fix the Malwarebytes Runtime Error: Could Not Call Proc Issue in Windows 11/10</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-the-artisans-code-a-complete-blueprint-for-flawless-windows-tv-recording/"><u>In 2024, The Artisan's Code A Complete Blueprint for Flawless Windows TV Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-server-issue-in-windows-media/"><u>Overcoming Server Issue in Windows Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-deactivated-volume-backups-in-windows/"><u>Reactivating Deactivated Volume Backups in Windows</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/loop-techniques-easy-endless-watching-on-television-for-2024/"><u>Tele-Loop Techniques Easy, Endless Watching on Television for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-guide-to-understanding-android-lightroom/"><u>The Ultimate Guide to Understanding Android Lightroom</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-6-missteps-why-using-chatgpt-could-be-a-bad-idea/"><u>Top 6 Missteps: Why Using ChatGPT Could Be a Bad Idea</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vanquishing-windows-dism-bottlenack-code-0x800f082f/"><u>Vanquishing Windows' DISM Bottlenack: Code 0X800F082F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-vintage-makeover-transform-into-classic-windows-98/"><u>Windows 11 Vintage Makeover: Transform Into Classic Windows 98</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-xbox-not-working-fix-it-fast/"><u>Windows Xbox Not Working? Fix It Fast</u></a></li>
</ul></div>

