---
title: Solving Corrupted File Error 0X80070570 on Modern Windows OSes
date: 2024-12-07T22:18:49.140Z
updated: 2024-12-12T18:43:42.363Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-joke-jamboree-twitters-10-best-comedy-threads/"><u>[Updated] In 2024, Joke Jamboree Twitter's 10 Best Comedy Threads</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/addressing-rpcrt4dll-failures-efficient-solutions-and-preventive-measures/"><u>Addressing rpcrt4.dll Failures - Efficient Solutions and Preventive Measures</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/boosting-your-insta-followers-a-comprehensive-guide-for-engaging-viewers/"><u>Boosting Your Insta-Followers: A Comprehensive Guide for Engaging Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compressao-de-videos-para-e-mailes-melhores-truques-e-dicas-por-expertos/"><u>Compressão De Vídeos Para E-Mailes: Melhores Truques E Dicas Por Expertos!</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/easy-methods-for-archiving-digital-meeting-recordings-for-2024/"><u>Easy Methods for Archiving Digital Meeting Recordings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-avi-to-mkv-upgrade-at-no-cost-discover-the-power-of-movavis-free-video-editing-tool/"><u>Effortless AVI-to-MKV Upgrade at No Cost: Discover the Power of Movavi's Free Video Editing Tool</u></a></li>
<li><a href="https://win-webster.techidaily.com/effortless-guide-convert-and-save-your-favorite-songs-the-complete-tutorial-on-downloading-taylor-swifts-music-as-mp3-and-aac/"><u>Effortless Guide: Convert and Save Your Favorite Songs - The Complete Tutorial on Downloading Taylor Swift's Music as MP3 & AAC</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-channel-studio-upgrade-vs-beta-shift/"><u>Elevate Your Channel Studio Upgrade Vs. Beta Shift</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transform-caf-files-into-ogg-format-with-ease/"><u>Free Online Converter: Transform CAF Files Into Ogg Format with Ease</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-oppo-k11x-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Oppo K11x</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-nord-ce-3-lite-5gs-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Nord CE 3 Lite 5G’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-infinix-note-30-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Infinix Note 30 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-convert-mov-to-mkv-for-free-using-the-movavi-media-converter/"><u>Instantly Convert MOV to MKV for Free Using the Movavi Media Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/kunt-u-wijken-gif-vorm-naar-mpeg-vrijetier-online-en-kostenloos/"><u>Kunt U Wijken Gif-Vorm Naar Mpeg - Vrijetier Online en Kostenloos!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-gratuite-ts-naar-mpeg-convertor-movavi/"><u>Online Gratuite TS Naar MPEG Convertor - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-six-techniques-to-enhance-image-clarity-and-detail/"><u>Top Six Techniques to Enhance Image Clarity and Detail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transferer-un-fichier-wav-a-format-ogg-en-ligne-sans-frais-tutorial-de-conversion-avec-movavi/"><u>Transférer Un Fichier WAV À Format Ogg En Ligne Sans Frais - Tutorial De Conversion Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-presentations-with-primeslide-professional-and-instantly-downloadable/"><u>Upgrade Your Presentations with PrimeSlide: Professional & Instantly Downloadable</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    