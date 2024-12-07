---
title: How to Fix the Event Viewer Not Working in Windows 11
date: 2024-12-04T21:09:34.948Z
updated: 2024-12-06T20:58:50.465Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart the Windows Event Log Service

![restart windows event log service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/restart-windows-event-log-service.jpg)

 You can restart the Windows Event Viewer log service to fix temporary issues with the app. Use the Services snap-in to stop and restart the service and check for any improvements.

 To restart the Windows Event Log Service:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the **Services** snap-in.
3. In the right pane, locate and right-click on the **Windows Event Log** service.
4. Select **Restart** and wait for the service to restart.
5. Close the Services snap-in and try to relaunch Event Viewer to see if the issue is resolved.

## 2\. Install the Latest Windows Updates

![windows 11 update advanced options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update-advanced-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Often the issues with Windows Event Viewer are associated with bad Windows updates. Check your Windows Updates section if a new update is available with a fix.

 To install Windows 11 updates:

1. Press **Win + I** to open **Settings**.
2. Open the **Windows Updates** tab.
3. Click **Check for Updates**. Windows will scan the server for newer updates and populate the screen with the same if available.
4. Click on **Download & install** to install any critical Windows updates available.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Some Generic Troubleshooting Steps to Get Event Viewer Working

 If the issue persists, this may be an issue with a recently installed Windows update, corrupt system files, and a problematic memory stick. Here are a few tips to try and resolve issues associated with the Windows Event Viewer.

### Perform a System Restore

 A restore point saves a copy of your system’s working image. Depending on your System Protection settings, you can use the [existing restore point to restore the system](https://www.makeuseof.com/use-system-restore-windows/) and undo system changes caused by an update or the user.

 Start with the most recent restore point available. If the problem persists, check if you can undo the most recently installed Windows update. You can also [manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) from the Settings app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Check for System File Corruption

 Damaged or missing Windows system files can be a reason why some of your system apps are not working. To fix the issue, [run the System File Checker utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to perform a scan and then run the DISM command to repair or replace the damaged files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Check for Issues With the Storage Drive

 Some apps can stop working if the storage drive is corrupt and need repair. You can [use the built-in check disk utility on Windows to scan and repair your drive](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for data corruption.

### Disable Windows Defender

 If your Event Viewer cannot load the log files, check if the action is blocked by Windows Defender. To determine the problem, [temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) on Windows 11 and then try to open the log files in Event Viewer.

### Check for Memory Leak Issues

 Issues with your system memory are another reason why the Event Viewer app is not working. Fortunately, Windows has a built-in [Memory Diagnostic tool to scan and detect issues with your system memory](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/).

 Often issues with the system memory may be due to faulty hardware. However, it is recommended to run more tests using the Memory Diagnostic tool report to get more insights into the issue.

### Perform a Windows Installation Repair

 If all else fails, you may need to repair your Windows installation. This will fix critical issues with your Windows image and reinstall the operating system without deleting apps and other data.

 You can [reinstall Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) using a Windows 11 ISO image. If you download the latest version of the ISO, the repair installation process will upgrade your Windows to the latest version available.

## The Windows Event Viewer, Back to Normal

 Event Viewer is a handy utility to troubleshoot your system for issues and keep a tab on all the system and application activities. When it stops working, start by restarting the Windows Event Viewer service. Additionally, check for newer Windows updates, corrupt storage drives, and missing Windows system files.

 If you still have no luck, consider using an Event Viewer alternative. Third-party event log analyzers offer better visualization and advanced features.

 Event Viewer can stop working due to issues with the Windows system files, system memory, glitchy Event Viewer services, and corrupt user accounts. Even some rudimentary issues with the recently installed updates can trigger the issue. Here are a few troubleshooting tips to help you fix the Event Viewer not working problem on Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-the-complete-minecraft-recording-blueprint-for-mac-users/"><u>[New] In 2024, The Complete Minecraft Recording Blueprint for Mac Users</u></a></li>
<li><a href="https://article-files.techidaily.com/new-iphone-photography-flip-and-tilt-your-images-anywhere/"><u>[New] IPhone Photography Flip & Tilt Your Images Anywhere</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-flash-fiction-directorial-map/"><u>[Updated] Flash Fiction Directorial Map</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-honor-90-gt-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Honor 90 GT with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/live-gaming-hubs-the-9-you-cant-miss-for-2024/"><u>Live Gaming Hubs The 9 You Can't Miss for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-inverted-keystroke-correction-on-pcs/"><u>Mastering Inverted Keystroke Correction on PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/maximize-your-vr-journey-oculus-rift-readiness-for-2024/"><u>Maximize Your VR Journey Oculus Rift Readiness for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-win-friendly-video-coders-reasoned/"><u>Selecting Win-Friendly Video Coders Reasoned</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-screenshare-troubleshooting-microphone-on-google-meet-windows/"><u>Silent Screenshare: Troubleshooting Microphone on Google Meet (Windows)</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/cket-engagement-with-youtubes-powerful-featured-channels-strategy/"><u>Skyrocket Engagement with Youtube’s Powerful Featured Channels Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-error-30005-failed-file-creation-code-32/"><u>Steps to Correct Error 30005: Failed File Creation, Code 32</u></a></li>
</ul></div>

