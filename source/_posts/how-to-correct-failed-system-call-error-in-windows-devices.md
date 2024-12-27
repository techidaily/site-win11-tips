---
title: How to Correct Failed System Call Error in Windows Devices
date: 2024-12-24T19:09:02.412Z
updated: 2024-12-27T20:48:37.155Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct Failed System Call Error in Windows Devices
excerpt: This Article Describes How to Correct Failed System Call Error in Windows Devices
keywords: Fixing System Calls on Windows,Resolving Device Errors,Troubleshooting WinError,Handling OS System Fails,Correcting Call Failures,Debugging Devices in Windows,Fix Failed System Calls
thumbnail: https://thmb.techidaily.com/907f940c68ac3ee45f8b59683cc047cc04665184817513adef7255fa53df8a70.jpg
---

## How to Correct Failed System Call Error in Windows Devices

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check For Disk Errors With CHKDSK

 A failing hard drive is another potential cause of the “system call failed” error. You can check for and repair disk errors with the Check Disk (CHKDSK) tool on Windows.

 Our [how to run CHKDSK](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) guide explains how you can utilize the Check Disk tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-exclusive-roundup-top-tier-no-cost-luts-available/"><u>[New] In 2024, Exclusive Roundup Top-Tier, No-Cost LUTs Available</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-grasp-free-to-use-vimeo-editing-techniques/"><u>[Updated] Grasp Free-to-Use Vimeo Editing Techniques</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-gtx-gems-the-best-for-high-res-gaming/"><u>[Updated] In 2024, GTX Gems The Best for High-Res Gaming</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-transforming-scripted-words-into-powerful-video-soundtracks-for-2024/"><u>[Updated] Transforming Scripted Words Into Powerful Video Soundtracks for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-old-school-giggles-unpacking-goofy-movie/"><u>2024 Approved Old School Giggles Unpacking 'Goofy Movie'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-fix-a-flapping-control-key-on-win11/"><u>Effective Strategies to Fix a Flapping Control Key on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-your-gaming-experience-with-faster-yuzu/"><u>Ignite Your Gaming Experience with Faster Yuzu</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-internet-idolaters-top-ten-youtube-sensations/"><u>In 2024, Internet Idolaters Top Ten YouTube Sensations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-dark-mode-guide-for-calculator-application/"><u>Instant Dark Mode: Guide for Calculator Application</u></a></li>
<li><a href="https://win-answers.techidaily.com/league-of-legends-errors-fast-fixes-for-rapid-restart/"><u>League of Legends Errors: Fast Fixes for Rapid Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prolific-powerhouses-in-win-11-best-productivity-widgets-list/"><u>Prolific Powerhouses in Win 11: Best Productivity Widgets List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-a-dead-grammarly-feature-with-simple-steps/"><u>Reviving a Dead Grammarly Feature with Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-chrome-sounds-and-banners-in-windows/"><u>Stop Chrome Sounds & Banners in Windows</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-5-trusted-ipad-video-player-apps-of-2024-install-now/"><u>Top 5 Trusted iPad Video Player Apps of 2024 - Install Now</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-solving-issues-with-utorrents-download-and-connection-problems/"><u>Troubleshooting: Solving Issues with uTorrent's Download and Connection Problems</u></a></li>
</ul></div>

