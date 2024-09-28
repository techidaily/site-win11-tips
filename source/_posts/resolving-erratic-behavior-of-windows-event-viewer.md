---
title: Resolving Erratic Behavior of Windows Event Viewer
date: 2024-09-23T17:47:34.877Z
updated: 2024-09-28T19:05:00.674Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Erratic Behavior of Windows Event Viewer
excerpt: This Article Describes Resolving Erratic Behavior of Windows Event Viewer
keywords: Win Event Log Issues,Event Viewer Anomalies,Fixing Event Errors,Troubleshoot Event Monitor,Erratic Windows Events,Stabilize Viewer Display,Diagnose EVW Problems
thumbnail: https://thmb.techidaily.com/33493674183189bab67b88de79a85b9996c293935f6ec3a823ac568973956aae.jpg
---

## Resolving Erratic Behavior of Windows Event Viewer

 Windows Event Viewer shows the system events and helps review app, security, and system logs useful to check errors on Windows 11\. However, this handy utility can stop working for various reasons, making it difficult to diagnose issues on your computer.

 Event Viewer can stop working due to issues with the Windows system files, system memory, glitchy Event Viewer services, and corrupt user accounts. Even some rudimentary issues with the recently installed updates can trigger the issue. Here are a few troubleshooting tips to help you fix the Event Viewer not working problem on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://aligracehair.sjv.io/c/5597632/1902309/19272" target="_top" id="1902309">
  <img src="//a.impactradius-go.com/display-ad/19272-1902309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902309/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Often the issues with Windows Event Viewer are associated with bad Windows updates. Check your Windows Updates section if a new update is available with a fix.

 To install Windows 11 updates:

1. Press **Win + I** to open **Settings**.
2. Open the **Windows Updates** tab.
3. Click **Check for Updates**. Windows will scan the server for newer updates and populate the screen with the same if available.
4. Click on **Download & install** to install any critical Windows updates available.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148633/16836" target="_top" id="2148633">
  <img src="//a.impactradius-go.com/display-ad/16836-2148633" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148633/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Try Some Generic Troubleshooting Steps to Get Event Viewer Working

 If the issue persists, this may be an issue with a recently installed Windows update, corrupt system files, and a problematic memory stick. Here are a few tips to try and resolve issues associated with the Windows Event Viewer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144274/7443" target="_top" id="2144274">
  <img src="//a.impactradius-go.com/display-ad/7443-2144274" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144274/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Perform a System Restore

 A restore point saves a copy of your system’s working image. Depending on your System Protection settings, you can use the [existing restore point to restore the system](https://www.makeuseof.com/use-system-restore-windows/) and undo system changes caused by an update or the user.

 Start with the most recent restore point available. If the problem persists, check if you can undo the most recently installed Windows update. You can also [manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) from the Settings app.

### Check for System File Corruption

 Damaged or missing Windows system files can be a reason why some of your system apps are not working. To fix the issue, [run the System File Checker utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to perform a scan and then run the DISM command to repair or replace the damaged files.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/updated-make-your-mark-personalized-brands-zero-price-tag/"><u>[Updated] Make Your Mark - Personalized Brands, Zero Price Tag</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1723807936957-do-you-need-a-vpn-yes-you-do-heres-why/"><u>Do You Need a VPN? Yes, You Do. Here's Why.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-image-perfection-with-windows-photos-app/"><u>Effortless Image Perfection with Windows Photos App</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/enhance-your-language-learning-via-mondly/"><u>Enhance Your Language Learning via Mondly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-for-microsoft-pc-manager-on-w11/"><u>Essential Guide for Microsoft PC Manager on W11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-lava-blaze-2-pro-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Lava Blaze 2 Pro to Protect Your Individual Information</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-resolve-oppo-reno-10-pro-5g-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Oppo Reno 10 Pro 5G Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-the-ultimate-list-of-image-to-video-makers-free-paid-and-everything-in-between/"><u>In 2024, The Ultimate List of Image to Video Makers Free, Paid, and Everything in Between</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-websites-windows-programs-a-tutorial/"><u>Making Websites Windows Programs: A Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-expiring-notifications-on-win11/"><u>Strategies to Prevent Expiring Notifications on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-deskanywhere-failures-in-windows-11/"><u>Troubleshooting DeskAnywhere Failures in WIndows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    