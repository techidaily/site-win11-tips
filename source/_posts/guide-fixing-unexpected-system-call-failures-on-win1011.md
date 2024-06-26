---
title: "Guide: Fixing Unexpected System Call Failures on Win10/11"
date: 2024-06-25T17:00:53.716Z
updated: 2024-06-26T17:00:53.716Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Fixing Unexpected System Call Failures on Win10/11"
excerpt: "This Article Describes Guide: Fixing Unexpected System Call Failures on Win10/11"
keywords: Windows System Call Troubleshoot,Win10 OS Call Errors Solve,Handling Win10 SysCalls Fails,Fixing Windows 10/11 SysCall Issues,Remedy for Win10/11 Call Failures,Resolving System Calls on Win10/11,Addressing Unexpected SysCalls in Win10/11
thumbnail: https://thmb.techidaily.com/94f7e6bb0d500f60edc6e34b363527bd47bbfffa481cdc60b824492075830e06.jpg
---

## Guide: Fixing Unexpected System Call Failures on Win10/11

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer ![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt ![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

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

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/fixing-csgo-start-problems-on-w11/"><u>Fixing CS:GO Start Problems on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-icon-alignment-in-windows-10/"><u>Simplify Icon Alignment in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-0x800704cf-from-windows-marketplace/"><u>Eliminating 0X800704CF From Windows Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-net-speeds-unlock-efficient-adapter-checking/"><u>Navigate Net Speeds: Unlock Efficient Adapter Checking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-memory-limitation-indicators-on-windowsvmware-systems/"><u>Correcting Memory Limitation Indicators on Windows/VMware Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-printer-access-for-windows-users/"><u>Unblocking Printer Access for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-using-ical-with-windows-operating-systems/"><u>Bridging the Gap: Using iCal with Windows Operating Systems</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-record-perfectly-with-apples-webcam-on-macbook/"><u>[Updated] In 2024, Record Perfectly with Apple's Webcam on MacBook</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-update-hardware-drivers-on-windows-10-by-drivereasy-guide/"><u>How to use Device Manager to update hardware drivers on Windows 10</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/discovering-great-videostreams-youtubes-best-27-alternatives/"><u>Discovering Great Videostreams  YouTube's Best 27 Alternatives</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-oneplus-nord-n30-se-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on OnePlus Nord N30 SE</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-crash-free-editing-tips-and-tricks-for-a-stable-final-cut-pro-x-experience-for-2024/"><u>Updated Crash-Free Editing Tips and Tricks for a Stable Final Cut Pro X Experience for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-speaking-into-the-future-iphone-recordings/"><u>In 2024, Speaking Into the Future - iPhone Recordings</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-step-by-step-crafting-a-masterpiece-with-collages/"><u>2024 Approved  Step-by-Step  Crafting a Masterpiece with Collages</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-unleash-your-creativity-6-innovative-adobe-premiere-pro-techniques/"><u>In 2024, Unleash Your Creativity 6 Innovative Adobe Premiere Pro Techniques</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>