---
title: How to Fix the Event Viewer Not Working in Windows 11
date: 2024-11-23T17:10:04.522Z
updated: 2024-11-27T17:57:56.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Event Viewer Not Working in Windows 11
excerpt: This Article Describes How to Fix the Event Viewer Not Working in Windows 11
keywords: Windows Event Log Issue,Fixing Event Viewer Errors,Troubleshoot Windows 11 EVT,Resolve EVT in Win11,Stop EVT Crashes Win11,Correcting EVT in Windows,Fixing Event Viewer Windows
thumbnail: https://thmb.techidaily.com/e4a8d7447e854c2de99b048e14a9c3d2b9315b35b4cc07b6ffa3d376da485f27.jpg
---

## How to Fix the Event Viewer Not Working in Windows 11

 Windows Event Viewer shows the system events and helps review app, security, and system logs useful to check errors on Windows 11\. However, this handy utility can stop working for various reasons, making it difficult to diagnose issues on your computer.

 Event Viewer can stop working due to issues with the Windows system files, system memory, glitchy Event Viewer services, and corrupt user accounts. Even some rudimentary issues with the recently installed updates can trigger the issue. Here are a few troubleshooting tips to help you fix the Event Viewer not working problem on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart the Windows Event Log Service

![restart windows event log service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/restart-windows-event-log-service.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can restart the Windows Event Viewer log service to fix temporary issues with the app. Use the Services snap-in to stop and restart the service and check for any improvements.

 To restart the Windows Event Log Service:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the **Services** snap-in.
3. In the right pane, locate and right-click on the **Windows Event Log** service.
4. Select **Restart** and wait for the service to restart.
5. Close the Services snap-in and try to relaunch Event Viewer to see if the issue is resolved.

## 2\. Install the Latest Windows Updates

![windows 11 update advanced options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update-advanced-options.jpg)

 Often the issues with Windows Event Viewer are associated with bad Windows updates. Check your Windows Updates section if a new update is available with a fix.

 To install Windows 11 updates:

1. Press **Win + I** to open **Settings**.
2. Open the **Windows Updates** tab.
3. Click **Check for Updates**. Windows will scan the server for newer updates and populate the screen with the same if available.
4. Click on **Download & install** to install any critical Windows updates available.

## 3\. Try Some Generic Troubleshooting Steps to Get Event Viewer Working

 If the issue persists, this may be an issue with a recently installed Windows update, corrupt system files, and a problematic memory stick. Here are a few tips to try and resolve issues associated with the Windows Event Viewer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Perform a System Restore

 A restore point saves a copy of your system’s working image. Depending on your System Protection settings, you can use the [existing restore point to restore the system](https://www.makeuseof.com/use-system-restore-windows/) and undo system changes caused by an update or the user.

 Start with the most recent restore point available. If the problem persists, check if you can undo the most recently installed Windows update. You can also [manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) from the Settings app.

### Check for System File Corruption

 Damaged or missing Windows system files can be a reason why some of your system apps are not working. To fix the issue, [run the System File Checker utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to perform a scan and then run the DISM command to repair or replace the damaged files.

### Check for Issues With the Storage Drive

 Some apps can stop working if the storage drive is corrupt and need repair. You can [use the built-in check disk utility on Windows to scan and repair your drive](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for data corruption.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disable Windows Defender

 If your Event Viewer cannot load the log files, check if the action is blocked by Windows Defender. To determine the problem, [temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) on Windows 11 and then try to open the log files in Event Viewer.

### Check for Memory Leak Issues

 Issues with your system memory are another reason why the Event Viewer app is not working. Fortunately, Windows has a built-in [Memory Diagnostic tool to scan and detect issues with your system memory](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/).

 Often issues with the system memory may be due to faulty hardware. However, it is recommended to run more tests using the Memory Diagnostic tool report to get more insights into the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Perform a Windows Installation Repair

 If all else fails, you may need to repair your Windows installation. This will fix critical issues with your Windows image and reinstall the operating system without deleting apps and other data.

 You can [reinstall Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) using a Windows 11 ISO image. If you download the latest version of the ISO, the repair installation process will upgrade your Windows to the latest version available.

## The Windows Event Viewer, Back to Normal

 Event Viewer is a handy utility to troubleshoot your system for issues and keep a tab on all the system and application activities. When it stops working, start by restarting the Windows Event Viewer service. Additionally, check for newer Windows updates, corrupt storage drives, and missing Windows system files.

 If you still have no luck, consider using an Event Viewer alternative. Third-party event log analyzers offer better visualization and advanced features.

 Event Viewer can stop working due to issues with the Windows system files, system memory, glitchy Event Viewer services, and corrupt user accounts. Even some rudimentary issues with the recently installed updates can trigger the issue. Here are a few troubleshooting tips to help you fix the Event Viewer not working problem on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-unveiling-the-magic-of-seamless-sound-integration-in-videos/"><u>[New] 2024 Approved Unveiling the Magic of Seamless Sound Integration in Videos</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-sculpting-soundscapes-the-fading-trick/"><u>[Updated] In 2024, Sculpting Soundscapes The Fading Trick</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-the-spectacular-lg-ud88w-4k-widescreen-monitor-review/"><u>[Updated] In 2024, The Spectacular LG UD88W 4K Widescreen Monitor Review</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-puzzling-perfection-hunt-for-the-ultimate-rooms/"><u>2024 Approved Puzzling Perfection Hunt for the Ultimate Rooms</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/dawn-of-dialectics-the-greek-linguistic-saga/"><u>Dawn of Dialectics: The Greek Linguistic Saga</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elite-economical-countdown-companions/"><u>Elite Economical Countdown Companions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-gaming-palette-with-android-windows-11-and-google-play/"><u>Enhance Your Gaming Palette with Android, Windows 11 & Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriching-user-interface-the-roadmap-for-future-widgets-in-windows-11/"><u>Enriching User Interface: The Roadmap for Future Widgets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-fixes-for-admin-managed-browsing-on-chromiumedge/"><u>Guiding Users Through Fixes for Admin-Managed Browsing on Chromium/Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-your-pc-top-10-uses-for-windows-powertoy-tools/"><u>Reimagine Your PC: Top 10 Uses for Windows PowerToy Tools</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-xiaomi-redmi-note-12t-pro-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-problem-of-windows-not-detecting-proxies/"><u>Solving the Problem of Windows Not Detecting Proxies</u></a></li>
<li><a href="https://driver-download.techidaily.com/troubleshooting-and-downloading-the-latest-broadcom-ethernet-drivers-compatible-with-windows-11/"><u>Troubleshooting and Downloading the Latest Broadcom Ethernet Drivers Compatible with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-isolated-audio-pathways-on-windows/"><u>Unraveling Isolated Audio Pathways on Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unveiling-the-eight-best-free-video-editing-software-for-social-media/"><u>Unveiling the Eight Best FREE Video Editing Software for Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-wasd-do-and-its-effects/"><u>What Does WASD Do and Its Effects?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    