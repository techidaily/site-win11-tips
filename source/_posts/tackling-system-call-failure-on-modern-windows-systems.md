---
title: Tackling System Call Failure on Modern Windows Systems
date: 2024-10-22T17:18:51.082Z
updated: 2024-10-26T22:55:21.707Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling System Call Failure on Modern Windows Systems
excerpt: This Article Describes Tackling System Call Failure on Modern Windows Systems
keywords: Windows Call Failures,System Errors Windows,WinError Diagnosis,CallFailure Windows Solutions,Resolve OS Failures,Addressing WinSystem Fails,Managing Windows System Calls
thumbnail: https://thmb.techidaily.com/a26060fad92020f54b317e5747fec75ccfe05e7c2700d5cb66b41afce88bdb6e.jpg
---

## Tackling System Call Failure on Modern Windows Systems

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100529/7443" target="_top" id="2100529">
  <img src="//a.impactradius-go.com/display-ad/7443-2100529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 3\. Check For Disk Errors With CHKDSK

 A failing hard drive is another potential cause of the “system call failed” error. You can check for and repair disk errors with the Check Disk (CHKDSK) tool on Windows.

 Our [how to run CHKDSK](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) guide explains how you can utilize the Check Disk tool.

## 4\. Initiate a Malwarebytes Scan

 Malware can cause many kinds of crashes to occur on Windows. The “system call failed” error could be occurring because of malware on your PC.

 You can scan for malware with many antivirus apps, including Windows Security. However, Malwarebytes is one of the [best free antivirus software for Windows](https://www.makeuseof.com/tag/ten-best-antivirus-programs/). So, try running a Malwarebytes scan like this:

1. Go to the [Malwarebytes download page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2028435/https://www.malwarebytes.com/mwb-download) and download the tool from there.
2. Open the **MBSetup** file from your Downloads folder and click **Install**.
3. Next, click **Skip** if you don’t want to install the additional software offered.
4. Select **Open Malwarebytes** to run the software.
5. Click **Scan** to initiate a malware scan.  
![The Scan option in Malwarebytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-scan-option.jpg)
6. Select **Quarantine** and **Yes** if Malwarebytes detects malware.

## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137220/26400" target="_top" id="2137220">
  <img src="//a.impactradius-go.com/display-ad/26400-2137220" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137220/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-navigating-instagrams-question-marker-magic/"><u>[New] 2024 Approved Navigating Instagram’s Question Marker Magic</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unleashing-potential-the-rising-stars-of-women-in-video-content-for-2024/"><u>[Updated] Unleashing Potential The Rising Stars of Women in Video Content for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-realme-narzo-60x-5g-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Realme Narzo 60x 5G Without Power Button | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-customized-cmd-shortcuts-and-windows/"><u>Boost Efficiency with Customized Cmd Shortcuts and Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-battlenet-speed-fasten-your-windows-pace/"><u>Boosting Battle.net Speed: Fasten Your Windows Pace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-the-heat-cutting-down-vanguard-writes-on-your-computer/"><u>Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-xiaomi-redmi-note-12-pro-5g-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Xiaomi Redmi Note 12 Pro 5G Unlock Without Password</u></a></li>
<li><a href="https://win-answers.techidaily.com/league-of-legends-launch-issues-top-tips-and-fixes-for-players/"><u>League of Legends Launch Issues: Top Tips and Fixes for Players</u></a></li>
<li><a href="https://extra-support.techidaily.com/macos-slideshow-creator-unite-images-and-videos-for-2024/"><u>MacOS SlideShow Creator Unite Images & Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pitfalls-of-the-promotional-assessing-risks-with-low-price-auth-codes/"><u>Pitfalls of the Promotional: Assessing Risks with Low-Price Auth Codes</u></a></li>
<li><a href="https://fox-tips.techidaily.com/secure-your-classroom-content-seamless-schooltube-downloads-in-mp4-or-avi-format-for-enhanced-learning-experiences/"><u>Secure Your Classroom Content: Seamless SchoolTube Downloads in MP4 or AVI Format for Enhanced Learning Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-manual-for-chrome-and-windows-11/"><u>The Ultimate Manual for Chrome and Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/visual-voyage-from-vimeo-footage-to-animated-artistry-for-2024/"><u>Visual Voyage From Vimeo Footage to Animated Artistry for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/vr-2/"><u>VRコンテンツ鑑賞に最適: 簡単かつ効果的な2つの技術</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    