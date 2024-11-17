---
title: Steps to Solve Windows 11 Corrupted File (Error Code 0X80070570)
date: 2024-11-12T18:10:03.471Z
updated: 2024-11-17T18:20:51.074Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Solve Windows 11 Corrupted File (Error Code 0X80070570)
excerpt: This Article Describes Steps to Solve Windows 11 Corrupted File (Error Code 0X80070570)
keywords: Fixing Error 0X80070570 in Windows 11,Resolve Win11 Corrupted File Issue,Troubleshoot Error Code 0X80070570,Unblock Windows 11 Files Error,Addressing 0X80070570 in Win11,Mending Windows 11 Corrupted Files,Clearing 0X80070570 File Problems
thumbnail: https://thmb.techidaily.com/2ca46c2a129dc1360b713c04a30f75e3e36c2cb0f971400d44a0a7430d69515d.jpg
---

## Steps to Solve Windows 11 Corrupted File (Error Code 0X80070570)

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-top-25-social-stars-essential-instagram-icons/"><u>[New] Top 25 Social Stars Essential Instagram Icons</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-your-go-to-fb-video-tool-for-desktops-and-phones/"><u>[Updated] Your Go-To FB Video Tool for Desktops and Phones</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-top-tips-acquiring-high-quality-backdrop-visuals/"><u>2024 Approved Top Tips Acquiring High-Quality Backdrop Visuals</u></a></li>
<li><a href="https://screen-recording.techidaily.com/agile-approaches-storing-ppt-speeches-for-2024/"><u>Agile Approaches Storing PPT Speeches for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enlightening-on-high-fidelity-window-images/"><u>Enlightening on High-Fidelity Window Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-now-glitch-xc0f1103f-in-win-1011-oses/"><u>Fixing GeForce Now Glitch XC0F1103F in Win 10/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-default-search-window-action-windows-11-guide/"><u>Halt Default Search Window Action, Windows 11 Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-vivo-s17-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/iphone-showdown-assessing-the-value-of-upgrading-from-iphone-14-pro-to-iphone-16-pro-expert-insights-digital-trends/"><u>IPhone Showdown: Assessing the Value of Upgrading From iPhone 14 Pro to iPhone 16 Pro – Expert Insights | Digital Trends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-scanning-condensed-viewing-for-file-finder/"><u>Simplified Scanning: Condensed Viewing for File Finder</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On OnePlus Nord CE 3 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-repairing-iomap64-syscall-issues-on-windows-devices/"><u>Tips for Repairing IOMap64 SysCall Issues on Windows Devices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-efficiency-with-claude-3-why-it-beats-chatgpt-on-all-fronts-revealed/"><u>Unlocking Efficiency with Claude 3 - Why It Beats ChatGPT on All Fronts (Revealed)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10-fix-overcoming-null-audio-device-problems/"><u>Win 10 Fix: Overcoming Null Audio Device Problems</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    