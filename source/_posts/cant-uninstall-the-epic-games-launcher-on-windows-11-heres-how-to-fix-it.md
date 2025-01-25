---
title: Can’t Uninstall the Epic Games Launcher on Windows 11? Here’s How to Fix It
date: 2025-01-19T22:30:03.524Z
updated: 2025-01-25T01:18:45.010Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Can’t Uninstall the Epic Games Launcher on Windows 11? Here’s How to Fix It
excerpt: This Article Describes Can’t Uninstall the Epic Games Launcher on Windows 11? Here’s How to Fix It
keywords: Launcher Removal Guide,Epic Uninstall Issue,Fix Launcher Error,Uninstalling Epic Games,Windows 11 Launcher Fix,Troubleshoot Launcher,How to Remove Game App
thumbnail: https://thmb.techidaily.com/8467c9e20d909c3a99e5604c440b3f79e42d4e9a9f150048899a6b75835712f0.jpg
---

## Can’t Uninstall the Epic Games Launcher on Windows 11? Here’s How to Fix It

 Are you struggling to uninstall Epic Games Launcher on Windows 11? Most of the time, there’s a background process still running so the fix should be quick and easy. However, this isn’t always the case so the classical way of uninstalling software isn’t enough to fix the problem.

 If you're facing the same issue, you don't have to worry. We’ll take a look at five methods that are worth a try when you can’t uninstall the Epic Games Launcher app.

## 1\. Close Epic Games Background Processes

 If you try to uninstall Epic Games Launcher, but Windows shows you the “Epic Games Launcher is currently running” message, there’s a background process stopping you. Even if you haven’t launched the app, its process might already run if it’s set to launch at system startup.

 However, you can easily stop the app from running in the background.

1. Right-click the **Start** button and select **Task Manager**.
2. Open the **Processes** tab.
3. Right-click **EpicGamesLauncher** and select **End Task**.  
![End Epic Game background processes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/epic-game-process-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you still can’t uninstall Epic Games Launcher, move on to the next solution.

## 2\. Run the Install and Uninstall Troubleshooter

 Windows it’s trying its best to give you the necessary troubleshooting tools for every problem you might encounter. While there’s no built-in troubleshooter to help you uninstall stubborn software, you can use [Microsoft’s Install and Uninstall Troubleshooter](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d). Here’s how you can use it after you’ve downloaded it:

1. Launch the Install and Uninstall Troubleshooter and click **Yes** in the UAC window.
2. Click **Next** **\> Uninstalling**.  
![Run the install and Uninstall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/troubleshooter-1.jpg)
3. Choose **Epic Games Launcher** from the list of programs and click **Next**.
4. Select **Yes, try uninstall**.  
![Uninstall Epic Games using a troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/troubleshooter-2.jpg)

## 3\. Uninstall Epic Games Using Command Prompt

 There are [different ways to uninstall software in Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/), and most people use Control Panel to remove software. However, it might not be the best choice especially when it comes to problematic apps. So, if the classical method didn’t work, it’s time to give Command Prompt a try.

1. [Launch Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the **wmic** and press **Enter**.
3. Copy and run the **product where name="Epic Games Launcher" call uninstall** command line.
4. Confirm the action by typing **Y** and pressing **Enter**.  
![Uninstall Epic Games Launcher with Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-command-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for Command Prompt to uninstall the app. If it displays the **Method executions successful** message, Epic Games Launcher is now uninstalled.

## 4\. Delete Epic Games From Registry

 If the Command Prompt method didn’t work, you should delete the Epic Games Launcher entries in the Registry Editor.

1. Launching Registry Editor with administrative rights.
2. In the Registry window, navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Uninstall**. Windows shows installed programs using a combination of letters and numbers, so it might be difficult to identify which one corresponds to Epic Games Launcher.
3. Click each key one at a time and check the value displayed next to **Display Name**.
4. Once you find the right key, double-click **UninstallString** from the right pane and copy the **Value data** information.
5. To uninstall Epic Games Launcher, press **Windows key + R** to bring up a Run dialog. There, paste the Registry value and click **OK**.  
![Use the Registry Editor to uninstall Epic Games Launcher](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-registry-1.jpg)

 Before editing the Registry, you should [manually create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) in case something goes wrong.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Uninstall Epic Games in Safe Mode

 If Epic Games Launcher is still doing its best to stop you from uninstalling it, there’s a chance a background process is still interfering. In this case, you should [start Windows in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). By doing so, your system will start without any additional drivers and apps that might lead to conflict.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Use a Third-Party App

 Instead of editing the Registry or running command lines, you can have a third-party app do the job for you. If you haven’t used a similar app before, check out our guide on [the best uninstallers to remove stubborn apps in Windows](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Easily Uninstall Epic Games Launcher on Windows

 Hopefully, the above tips helped you uninstall Epic Games Launcher on your computer. When Windows built-in tools are not enough to fix the problem, you could use the Install and Uninstall Troubleshooter or switch to a third-party app.

 But if you haven’t had any luck and Epic Games Launcher isn’t the only program that you can’t uninstall, it might be time to reset Windows 11\.

 If you're facing the same issue, you don't have to worry. We’ll take a look at five methods that are worth a try when you can’t uninstall the Epic Games Launcher app.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-cinemas-best-bites-for-video-editors/"><u>[New] Cinema's Best Bites for Video Editors</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-evaluating-youtubes-monthly-creator-payments/"><u>[New] In 2024, Evaluating YouTube's Monthly Creator Payments</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-key-approaches-to-mute-motion-capture/"><u>[New] In 2024, Key Approaches to Mute Motion Capture</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-prime-steadicam-devices-for-drones-in-filmmaking/"><u>[Updated] Prime Steadicam Devices for Drones in Filmmaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-and-contrasting-win11-homes-vs-advanced-professional-editions/"><u>Comparing and Contrasting Win11: Homes Vs. Advanced Professional Editions</u></a></li>
<li><a href="https://blog-min.techidaily.com/experience-portable-melodies-anytime-the-tinypod-makes-your-apple-watch-an-on-the-go-ipod/"><u>Experience Portable Melodies Anytime: The TinyPod Makes Your Apple Watch an On-the-Go iPod!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-distorted-to-dazzling-a-guide-to-win11-display-correction/"><u>From Distorted to Dazzling: A Guide to Win11 Display Correction</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-factory-reset-ipad-or-apple-iphone-12-pro-without-icloud-password-or-apple-id-by-drfone-ios/"><u>How to Factory Reset iPad or Apple iPhone 12 Pro without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-translate-foreign-languages-with-hotkeys-in-windows-11-and-11/"><u>How to Translate Foreign Languages With Hotkeys in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-notetakers-choose-7-out-of-many-for-pcs/"><u>Ideal Notetakers: Choose 7 Out of Many For PCs</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-7-essential-tips-for-flawless-underwater-filming/"><u>In 2024, 7 Essential Tips for Flawless Underwater Filming</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-cutting-edge-display-selections-10-mac-list/"><u>In 2024, Cutting-Edge Display Selections #10 Mac List</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-apple-id-from-apple-iphone-se-2022-without-password-by-drfone-ios/"><u>In 2024, How to Remove Apple ID from Apple iPhone SE (2022) without Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-inactive-thumbnails-in-windows-ui/"><u>Repairing Inactive Thumbnails in Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-maintain-an-operational-windows-notepad/"><u>Techniques to Maintain an Operational Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-compatibility-list-for-24-laptops/"><u>The Ultimate Windows Compatibility List for '24 Laptops</u></a></li>
</ul></div>

