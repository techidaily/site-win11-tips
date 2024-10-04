---
title: Strategies to Overcome Corrupted File (Error Code 0X80070570) on Windows 11
date: 2024-09-27T18:46:07.382Z
updated: 2024-10-03T18:08:37.780Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Overcome Corrupted File (Error Code 0X80070570) on Windows 11
excerpt: This Article Describes Strategies to Overcome Corrupted File (Error Code 0X80070570) on Windows 11
keywords: Fixing Windows Error 0X80070570,Resolve Corrupted Files in Win11,Overcoming File Error 0X80070570,Eradicate XP Error on Windows 11,Troubleshoot Error Code 0X80070570,Remedying Win11 Corruption Issues,Eliminate File Errors in Win11
thumbnail: https://thmb.techidaily.com/a15aaf86d9e6f286629da1a62d56aaff3df86baa99afaf09eec0439a28bfe3f5.jpg
---

## Strategies to Overcome Corrupted File (Error Code 0X80070570) on Windows 11

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
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

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
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-essential-10-capture-hardware-recommendations-for-online-videos/"><u>[New] 2024 Approved Essential 10 Capture Hardware Recommendations for Online Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-srt-breakdown-core-concepts-and-applications/"><u>[New] SRT Breakdown Core Concepts and Applications</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-building-captivating-online-media-summaries/"><u>[Updated] In 2024, Building Captivating Online Media Summaries</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-stealth-and-honor-find-your-favorite-games-like-tsushi-for-2024/"><u>[Updated] Stealth and Honor Find Your Favorite Games Like Tsushi for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-steam-downloads-halting-speed-fluctuations/"><u>Enhance Steam Downloads: Halting Speed Fluctuations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-typing-adjusting-keyboards-on-windows-11-os/"><u>Enhance Typing: Adjusting Keyboards on Windows 11 OS</u></a></li>
<li><a href="https://solve-popular.techidaily.com/harnessing-the-power-of-cookiebot-for-advanced-site-personalization-and-analytics/"><u>Harnessing the Power of Cookiebot for Advanced Site Personalization and Analytics</u></a></li>
<li><a href="https://win-solutions.techidaily.com/master-the-art-of-troubleshooting-paladins-fixing-crash-issues-with-2024s-best-tips/"><u>Master the Art of Troubleshooting Paladins: Fixing Crash Issues with 2024'S Best Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-javascript-failure-resolution-in-windows-11s-discord/"><u>Mastering JavaScript Failure Resolution in Windows 11'S Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-troubled-waters-help-for-your-windows-woes/"><u>Navigating Troubled Waters: Help for Your Windows Woes</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-rhythmic-revelation-an-online-journey-to-single-out-the-beat-for-2024/"><u>New Rhythmic Revelation An Online Journey to Single Out the Beat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-malfunctioning-windows-rules-for-outlook-emails/"><u>Realigning Malfunctioning Windows Rules for Outlook Emails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setup-a-new-baseline-for-touch-input-on-your-win-11-pc/"><u>Setup a New Baseline for Touch Input on Your Win 11 PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/transforming-videos-for-twitter-success-expert-convertors-guide/"><u>Transforming Videos for Twitter Success Expert Convertors Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-gaming-with-yuzus-speeds/"><u>Turbocharge Windows Gaming with Yuzu's Speeds</u></a></li>
</ul></div>

