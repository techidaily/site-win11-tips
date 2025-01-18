---
title: Resolving Exception Breakpoint Reached on Windows System
date: 2025-01-16T18:13:31.235Z
updated: 2025-01-18T16:45:41.759Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Exception Breakpoint Reached on Windows System
excerpt: This Article Describes Resolving Exception Breakpoint Reached on Windows System
keywords: WinExceptionBreakpointSolved,DebugWinErrorHandling,HandleWindowsDebugFailures,FixWindowsBreakpointError,ResolveWinSystemErrors,WindowsExceptionDebugging,BreakpointTroubleshootWin
thumbnail: https://thmb.techidaily.com/2151304b15358b5e0486365b1b4e0f5fc2185a4452deb2b08eaf2b9d1e47c0a1.jpg
---

## Resolving Exception Breakpoint Reached on Windows System

 When you try to shut down or restart your PC, you may encounter an error that reads "the exception breakpoint has been reached." This error can also occur when you try to open specific apps on your PC.

 Issues with your system files, glitchy apps, memory leaks, and bad disk sectors are common contributing factors to this error. If you experience this error, here is a quick troubleshooting guide to help you fix the "the exception breakpoint has been reached" error on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Any Automatic Startup Apps

 Apart from the essential Windows services, third-party apps enabled to run during startup can cause conflicts and cause problems. To determine the cause, disable all the automatic startup apps and restart your PC.

To disable startup apps on Windows:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Task Manager** to open the app.
3. In Task Manager, open the**Startup apps** tab.
4. Click the**Status** column to sort the table with the enabled apps at the top.
5. Select all the apps one by one and click**Disabled** .  
![disable startup apps windows 11 new](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/disable-startup-apps-windows-11-new.jpg)

 Once done, restart your PC and check if the error persists. If not, enable the apps again one by one until you find the problematic application. Depending on the use, you can update, uninstall or find an alternative for the app.

## 2\. Run the System File Checker and the DISM Tools

 The Deployment Image Service Management (DISM) tool is a command-line utility that can find and fix issues with your Windows image. If your error is triggered by a corrupt system image, the DISM command can help you fix the error.

 In addition, we'll also run the System File Checker utility. Like DISM, the System File Checker is a built-in command-line utility to detect and fix corrupted or missing system files on Windows computers.

Follow these steps to run the DISM and System File Checker tools:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you need help).
2. In the Command Prompt window, type the following command to check your system health:  
`Dism /Online /Cleanup-Image /CheckHealth`
3. ![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dism-scan-health-restore-health-command-prompt-1.jpg)  
 Next, type the following command and press**Enter** to scan your PC's health:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`Dism /Online /Cleanup-Image /ScanHealth`
4. Once done, type the following command to repair the system image:  
`Dism /Online /Cleanup-Image /RestoreHealth`
5. This process may take several minutes, so wait till the verification reaches 100%.
6. Once done, type the following command to execute the System File Checker utility:  
`sfc /scannow`
7. This process can take some time to complete. Once the verification reaches 100%, it will display the result and any actions taken.
8. Type**exit** and press**Enter** to close Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check Your Hard Drive for Errors With CHKDSK

 Check Disk (CHKDSK) is a Windows command-line utility to find and fix issues on your hard drive due to bad sectors. You can run the tool on your traditional mechanical hard drive and Solid State Drives (SSDs).

 You can use the CHKDSK utility with multiple parameters. Here we'll use the /r parameter to locate bad sections and recover readable information.

To run the CHKDSK tool:

1. Open Command Prompt as administrator, as you did in method two.
2. In the Command Prompt window, type the following command and press**Enter** to run the CHKDSK utility:  
`chkdsk C: /r`

![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-chkdsk-command.jpg)

 When executed, it will scan and check your system drive (C:/) for bad sectors. Wait for the scan to finish and close the Command Prompt window.

## 4\. Turn Off Any GPU Overclocking

 If the error is triggered while performing a graphic-intensive task (such as playing a game or rendering 3D models), it can be due to an overclocked GPU.

 While an overclocked GPU offers performance benefits, it can cause your system to crash and trigger multiple errors if not done correctly. Whether you have used a third-party GPU overclocking tool or a proprietary app from your GPU manufacturer, undo all the recent instances of GPU overclocking to see if that helps fix this error.

 If you need help with overclocking, check out[the best GPU overclocking tools](https://www.makeuseof.com/best-gpu-overclocking-tools/) to get the best results.

## 5\. Check for Memory Leaks

 The "the exception breakpoint has been reached" 0x80000003 can occur if your system fails to efficiently utilize the available memory resulting in a memory leak. Fortunately, Window comes with a built-in Memory Diagnostic Tool to check your computer for memory problems. Here's how to do it.

1. Make sure to save all the work and close all the running apps.
2. Press**Win + R** to open**Run** .
3. Type**mdsched.exe** and click**OK** .
4. In the**Windows Memory Diagnostic** dialog, click**Restart now and check for problems (recommended)** .  
![Windows memory diagnostic tool restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-memory-diagnostic-tool-restart.jpg)
5. Your computer will restart and boot into the Windows Memory Diagnostic Tool menu, and the system will start a test automatically.  

![Windows memory diagnostic tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-memory-diagnostic-tooljpg.jpg)
6. You can also perform**Basic, Standard, or Extended** test manually. To do this, press**F1** to access the**Options** menu and select from the**Basic, Standard, and Extended** option under the**Test Mix** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. If a problem is detected, you can view it under the Status section. Even if the test appears inactive or stuck, do not shut down your computer until testing is complete.
8. Once done, the PC will start, and the Windows Memory Diagnostic Tool will display the test result after you log on.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Create a New Windows Local Account

 A corrupted user profile may cause the "the exception breakpoint has been reached" error. To fix the error, you can[create a new user local user profile on Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) and give it administrator privilege. Sign into your new user profile and launch the app to see if the error is resolved.

## 7\. Update or Uninstall the Problematic App

 If specific apps trigger the error, such as the Origin launcher or the Steam client, consider reinstalling the app to solve the issue.

 Before you uninstall it, check if your app has any pending updates. Install any update available and check for any improvements. If the issue persists, reinstalling the app may be necessary.

To uninstall an application on Windows:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Install** **apps** .  
![windows 11 settings installed apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-installed-apps.jpg)
4. Type the name of your app in the search bar.  

![uninstall apps windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-apps-windows-11.jpg)
5. Next, click**the three-dots menu** next to the app name and**Uninstall** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click on**Uninstall** again to confirm the action.
7. Once uninstalled, download the app installer and install the app. Restart your PC and check for any improvements.

 Note that, at times, the issue can be with a specific version of the app. To fix this, try to install an older version of the app to see if that works.

## Fixing the "The Exception Breakpoint Has Been Reached" Error on Windows

 This error is often related to your system's inability to utilize the memory resources available due to system file corruption or issues with your hard disk. Use the built-in Windows image repair and System File Checker too to resolve system issues. Also, install pending updates for the app or reinstall the problematic app to fix the problem.

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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-meta-vs-omni-navigating-digital-realms/"><u>[New] In 2024, Meta Vs. Omni Navigating Digital Realms</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-silent-blades-and-righteous-honor-your-next-game-adventure-awaits/"><u>[New] Silent Blades & Righteous Honor Your Next Game Adventure Awaits</u></a></li>
<li><a href="https://win-solutions.techidaily.com/6-effective-strategies-to-resolve-terraria-disconnection-issues/"><u>6 Effective Strategies to Resolve Terraria Disconnection Issues</u></a></li>
<li><a href="https://win-solutions.techidaily.com/effective-tips-on-resolving-in-game-lag-and-connection-errors-in-new-world/"><u>Effective Tips on Resolving In-Game Lag and Connection Errors in New World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-memory-safety-seven-tips-to-overcome-win11-grayouts/"><u>Elevating Memory Safety: Seven Tips to Overcome Win11 Grayouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fixing-brightness-controls-via-keyboard-shortcuts-on-windows-11/"><u>Guide to Fixing Brightness Controls via Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-continuous-crashing-issues-in-the-discord-platform/"><u>How to Fix Continuous Crashing Issues in the Discord Platform</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-itel-a70-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Itel A70 Phone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-top-ranked-graphics-cards-for-optimal-online-streaming-quality/"><u>In 2024, Top-Ranked Graphics Cards for Optimal Online Streaming Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cortana-data-backup-on-pc/"><u>Mastering Cortana Data Backup on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-closed-down-calendar-and-mail-on-w11/"><u>Navigating Closed-Down Calendar and Mail on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-troubleshooting-stop-youtube-lagging-on-chrome/"><u>Quick Troubleshooting: Stop YouTube Lagging on Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-why-you-shouldnt-turn-off-windows-11s-alerts/"><u>Revealing Why You Shouldn’t Turn Off Windows 11'S Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-steam-cloud-sync-setbacks/"><u>Reversing Steam Cloud Sync Setbacks</u></a></li>
<li><a href="https://facebook.techidaily.com/safeguard-your-facebook-experience-avoid-these-14-schemes/"><u>Safeguard Your Facebook Experience: Avoid These 14 Schemes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/social-simulacrum-sketches-designing-distorted-digital-selves/"><u>Social Simulacrum Sketches Designing Distorted Digital Selves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-ascending-taskmanager-above-all/"><u>The Guide to Ascending TaskManager Above All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-to-defeat-the-closed-terminal-conundrum/"><u>Top Strategies to Defeat the Closed Terminal Conundrum</u></a></li>
<li><a href="https://some-skills.techidaily.com/unite-video-files-into-playlist-assembly-for-2024/"><u>Unite Video Files Into Playlist Assembly for 2024</u></a></li>
</ul></div>

