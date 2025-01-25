---
title: Can't Use the Program Compatibility Troubleshooter on Windows? Try These Fixes
date: 2025-01-19T18:28:03.839Z
updated: 2025-01-24T23:15:46.573Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Can't Use the Program Compatibility Troubleshooter on Windows? Try These Fixes
excerpt: This Article Describes Can't Use the Program Compatibility Troubleshooter on Windows? Try These Fixes
keywords: Win XP/Vista Compatibility,Program Troubleshooting Guide,Windows Compatibility Fix,Compatibility Tool Errors,Resolve Compat Issues,Windows Troubleshooter Usage,Compatibility Settings Adjust
thumbnail: https://thmb.techidaily.com/11e98257d7e7257e5883dcc5757d573b33d04f0ecfefae2f5882a90863822c25.png
---

## Can't Use the Program Compatibility Troubleshooter on Windows? Try These Fixes

 The Program Compatibility Troubleshooter is a tool from Microsoft that checks for and resolves compatibility issues when running older applications on newer versions of Windows. However, sometimes the troubleshooter fails to work as expected.

 If you're facing this issue, there are several possible causes and ways to fix it. Let's look into them below.

## 1\. Check For Corrupted System Files

 Corrupted system files can cause the Program Compatibility Troubleshooter not to work correctly. To ensure all your system files are functioning properly, run the built-in System File Checker utility on Windows. Here's how to do it:

1. Right-click on**Start** and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC appears on the screen, click**Yes** to grant privileges.  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In Command Prompt type the below command and hit Enter:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`sfc /scannow`

 Wait for the scan to finish. This may take several minutes and your PC may restart once or twice during the process. Once the scan is completed, check if the Program Compatibility Troubleshooter works now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair Corrupted System Image

 If the System File Checker was unable to repair corrupt system files, you can use the DISM tool from Command Prompt to fix them. Here's how to do it:

1. Use one of the many[ways to run Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) to get an elevated prompt running.  
![Run DISM Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-dism-command.jpg)
2. In Command Prompt, type the below command and hit**Enter** :  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`DISM /Online /Cleanup-Image /RestoreHealth`

 The DISM tool will start scanning the system for corruption. It can take up to 20 minutes, but it is worth waiting because it can repair a lot of system issues. Once the scan is completed, restart your computer and check if the issue is fixed.

## 3\. Uninstall Third-Party Security Software

 Sometimes, certain third-party security software can interfere with the Program Compatibility Troubleshooter and cause it to not work. Uninstalling these programs should help.

1. Right-click on Start and select**Installed apps** .
2. Search for your security software in the list of installed programs.
3. Then click the three dots and select**Uninstall** .

 Follow the on-screen instructions to remove the program from your PC. Once done, restart your PC and try running the Program Compatibility Troubleshooter again.

## 4\. Restart the Diagnostic Policy Service

 The Diagnostic Policy Service is responsible for allowing the Program Compatibility Troubleshooter to work properly. If it's not running, restarting it should help the troubleshooter function normally.

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**services.msc** in the text box and click**OK** .
3. Look for the**Diagnostic Policy Service** and double-click it.  
![Restart Diagnostic Policy Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-diagnostic-policy-service.jpg)
4. In the Diagnostic Policy Service Properties window, set the Startup type to**Automatic** and click**Start** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Next, click**Apply** and**OK** to save the changes.

 Now restart your PC and try running the Program Compatibility Troubleshooter again to see if it works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Run the Troubleshooter in Safe Mode

 If you are still experiencing this issue, try running the Program Compatibility Troubleshooter in safe mode. This will help you troubleshoot any compatibility issues more effectively.

To do this, follow the below steps:

1. Start your PC in safe mode (see[how to start Windows in safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) for instructions).
2. Once in safe mode,[run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) and check if it works. If so, it means that one of your installed programs is causing the issue. Try uninstalling them and see if the issue is fixed.

## 6\. Reset Windows

 If all else fails, you can try[resetting Windows to its default settings](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will reinstall Windows and get rid of any potential issues that may be causing the troubleshooter to not work.

## Fixing Program Compatibility Troubleshooter Problems on Windows

 If the Program Compatibility Troubleshooter is not working on your computer, read this guide. The steps here will help you fix this issue and have the tool working and running again.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tech-savvy.techidaily.com/apple-unveils-vision-pro-now-compatible-with-microsofts-key-tools-word-and-excel-from-day-one-gizmo-insights/"><u>Apple Unveils Vision Pro - Now Compatible With Microsoft's Key Tools: Word and Excel From Day One | Gizmo Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-desktop-space-adding-personalized-weather-symbols-on-taskbar-in-windows-11/"><u>Customize Desktop Space: Adding Personalized Weather Symbols on Taskbar in Windows 11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/cutting-edge-capture-selecting-top-smartphone-cameras-in-high-res-video-for-2024/"><u>Cutting Edge Capture Selecting Top Smartphone Cameras in High-Res Video for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effective-solutions-dealing-with-missing-or-unavailable-wininetdll-files/"><u>Effective Solutions: Dealing with Missing or Unavailable wininet.dll Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-network-error-0x800704b3-in-windows-10-and-11/"><u>How to Fix the Network Error 0X800704b3 in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-your-sticky-notes-not-syncing-on-windows-11/"><u>How to Fix Your Sticky Notes Not Syncing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-apps-supporting-mac-users-in-their-windows-journey/"><u>Ideal Apps Supporting Mac Users in Their Windows Journey</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-google-pixel-8-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Google Pixel 8</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-best-free-video-communication-apps-for-iphone-and-android-users/"><u>In 2024, Best Free Video Communication Apps for iPhone & Android Users</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/maximizing-zoom-meeting-insight-through-grid-view-settings-for-2024/"><u>Maximizing Zoom Meeting Insight Through Grid View Settings for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/pursuit-of-pleasure-10-games-echoing-gta-v/"><u>Pursuit of Pleasure 10 Games Echoing GTA V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-skills-faster-with-these-top-8-study-tips-on-a-windowed-pc/"><u>Sharpen Skills Faster with These Top 8 Study Tips on a Windowed PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-to-overcome-windows-11-unresponsive-typing-error-x80049dd3/"><u>Swift Fixes to Overcome Windows 11 Unresponsive Typing Error - X80049DD3</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-tutorial-for-effective-free-timer-management/"><u>The Ultimate Tutorial for Effective FREE Timer Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/total-uninstallation-tactics-for-win-1011-wsl/"><u>Total Uninstallation Tactics for Win 10/11 WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-timed-lock-screen-issue-in-windows/"><u>Troubleshooting Non-Timed Lock Screen Issue in Windows</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/troubleshooting-tips-overcoming-challenges-with-inaccessible-backup-data/"><u>Troubleshooting Tips: Overcoming Challenges with Inaccessible Backup Data</u></a></li>
</ul></div>

