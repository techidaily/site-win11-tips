---
title: Remedy for File Damage Error (Code 0X80070570) in Windows 11
date: 2024-12-16T05:50:10.304Z
updated: 2024-12-22T01:20:58.531Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for File Damage Error (Code 0X80070570) in Windows 11
excerpt: This Article Describes Remedy for File Damage Error (Code 0X80070570) in Windows 11
keywords: WinErrorCode_0X80070570,FixFileDamage_Windows11,Code70ErrorRepair,Windows11FileIssue,Error0x8070570Fix,DataLossCorrectionWin,0X8007DedupErrorResolution
thumbnail: https://thmb.techidaily.com/802df3d91ab6daf6d905273698ce2644dd2e6aa605c087ae0dc1d7ad5065d08f.jpg
---

## Remedy for File Damage Error (Code 0X80070570) in Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-the-early-birds-guide-to-youtube-skip-these-8-potential-pitfalls/"><u>[Updated] 2024 Approved The Early Bird's Guide to YouTube Skip These 8 Potential Pitfalls</u></a></li>
<li><a href="https://fox-making.techidaily.com/easily-set-up-your-merge-module-a-step-by-step-guide/"><u>Easily Set Up Your Merge Module: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-for-eradicating-roblox-error-262/"><u>Efficient Methods for Eradicating Roblox Error 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-continuity-a-guide-to-safekeeping-your-game-progress/"><u>Ensuring Continuity: A Guide to Safekeeping Your Game Progress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-flip-functionality-in-windows-11-snap-feature/"><u>Fast-Flip Functionality in Windows 11 Snap Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-wifi-disconnection-issue-on-windows-laptopspcs/"><u>Fixing WiFi Disconnection Issue on Windows Laptops/PCs</u></a></li>
<li><a href="https://fox-access.techidaily.com/freeaudvault-review-unveiling-the-full-potential-of-2024/"><u>FreeAudVault Review Unveiling the Full Potential of 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/guarding-web-data-privacy-strategies-to-deter-automated-scraper-bots-including-openai/"><u>Guarding Web Data Privacy: Strategies to Deter Automated Scraper Bots Including OpenAI</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-tecno-spark-20-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Tecno Spark 20 Lock Screen Password?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-mastering-iphones-ringtone-personalization/"><u>In 2024, Mastering iPhone's Ringtone Personalization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-maze-of-robloxs-error-262/"><u>Navigating Through the Maze of Roblox's Error 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reveal-elusive-cameras-from-windows-dm-interface/"><u>Reveal Elusive Cameras From Windows' DM Interface</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-reads-on-wheels-exploring-the-convenient-world-of-kobo-clara-hd-for-avid-readers/"><u>Top Reads on Wheels: Exploring the Convenient World of Kobo Clara HD for Avid Readers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-improvements-the-latest-microsoft-paint-edition/"><u>Transformative Improvements: The Latest Microsoft Paint Edition</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-constraints-why-chatgpt-falls-short-in-crypto-forecasts/"><u>Understanding the Constraints: Why ChatGPT Falls Short in Crypto Forecasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-a-comprehensive-guide-to-reading-qr-codes-in-windows-os/"><u>Unlocking the Potential: A Comprehensive Guide to Reading QR Codes in Windows OS</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1899462-9781626251038-unlocking-the-secrets-of-self-esteem/"><u>Unlocking the Secrets of Self-Esteem | Free Book</u></a></li>
</ul></div>

