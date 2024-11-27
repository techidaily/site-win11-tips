---
title: Steps to Resolve Call Failed Error on Windows Systems
date: 2024-11-26T18:03:26.389Z
updated: 2024-11-27T16:11:22.134Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Resolve Call Failed Error on Windows Systems
excerpt: This Article Describes Steps to Resolve Call Failed Error on Windows Systems
keywords: Fixing Call Fail in Windows,Resolving Call Errors PC,Windows Call Error Guide,Tackle Windows Phone Issue,Overcome Windows Call Fail,Troubleshoot Call Fail Windows,Fix Failed Calls on Windows
thumbnail: https://thmb.techidaily.com/744014ffd50adb1d07a7a2940727b9c6e249d35c9b35474b3c5a660491ebe0a3.png
---

## Steps to Resolve Call Failed Error on Windows Systems

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-expert-analysis-of-samsung-photo-editor-prospects-and-constraints/"><u>[New] 2024 Approved Expert Analysis of Samsung Photo Editor Prospects & Constraints</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-short-track-olympics-highlights-from-22/"><u>[New] Short Track Olympics - Highlights From '22</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/he-art-of-building-powerful-youtube-backlinks-for-2024/"><u>[New] The Art of Building Powerful YouTube Backlinks for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-greatest-7-web-based-recording-tools-2023/"><u>[Updated] In 2024, Greatest 7 Web-Based Recording Tools 2023</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-to-install-realtek-audio-solution-for-windows-11-download-today/"><u>Easy-to-Install Realtek Audio Solution for Windows 11 – Download Today</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effortless-transition-how-to-convert-network-settings-from-public-to-private-in-windows-11/"><u>Effortless Transition: How to Convert Network Settings From Public to Private in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-office-365-problem-code-30015-26-on-pcs/"><u>Eliminating Office 365 Problem Code: 30015-26 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-graphics-memory-capability-for-hogwarts-virtual-learning-experience/"><u>Enhancing Graphics Memory Capability for Hogwarts Virtual Learning Experience</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-the-problem-why-arent-the-2024-game-finals-launching-expert-advice-inside/"><u>Fixing the Problem: Why Aren't The 2024 Game Finals Launching? Expert Advice Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/function-failures-on-win10-quick-remedies-available/"><u>Function Failures on Win10? Quick Remedies Available!</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-on-lava-yuva-3-by-drfone-android/"><u>In 2024, How to Bypass FRP on Lava Yuva 3?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increasing-video-ram-availability-on-windows-11-pcs/"><u>Increasing Video RAM Availability on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-consistent-printer-selection-under-windows/"><u>Keeping Consistent Printer Selection Under Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-windows-11s-error-0x800704b3/"><u>Steps to Solve Windows 11'S Error 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-windows-setup-epic-games-edition/"><u>Supercharge Your Windows Setup: Epic Games Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-for-windows-11-anomalies/"><u>Troubleshooting Guide for WINDOWS 11 Anomalies</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-360-view-camera-analysis-for-2024/"><u>Ultimate 360-View Camera Analysis for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-admin-powershell-potential-in-windows-11-environment/"><u>Unleashing the Admin PowerShell Potential in Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-full-potential-of-your-mouse-with-cross-border-powers/"><u>Unleashing the Full Potential of Your Mouse with Cross-Border Powers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    