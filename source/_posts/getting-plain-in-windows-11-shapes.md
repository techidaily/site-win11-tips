---
title: Getting Plain in Windows 11 Shapes
date: 2025-01-16T16:18:59.948Z
updated: 2025-01-18T17:43:26.480Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Getting Plain in Windows 11 Shapes
excerpt: This Article Describes Getting Plain in Windows 11 Shapes
keywords: Win11_PlainInterface,SimplifiedWindowsUI,Windows11BasicLayout,UnclutteredWindows11,PlainWindowsInterface,SimpleWin11Style,CleanWindowsDesign11
thumbnail: https://thmb.techidaily.com/91b7cfb4d96e2456602f29985eb790b38dbd8c0fc22d4f4a877755c3058adea9.jpg
---

## Getting Plain in Windows 11 Shapes

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/updated-a-step-by-step-guide-to-crafting-immersive-fb-video-experienenas/"><u>[Updated] A Step-by-Step Guide to Crafting Immersive FB Video Experienenas</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-exclusive-review-best-free-videocall-platforms-w-screen-view/"><u>[Updated] Exclusive Review Best Free Videocall Platforms W/ Screen View</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ideal-tools-for-group-online-communication/"><u>[Updated] Ideal Tools for Group Online Communication</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-killer-routers-firmware-v1535-installed-free-drivers-available/"><u>Get Your Killer Router's Firmware v1535 Installed - Free Drivers Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-rockalldlldll-not-found-or-missing-error-on-windows-pc/"><u>How to Fix Rockalldll.dll Not Found or Missing Error on Windows PC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-unfading-flight-ambitions-top-10-longevity-drone-lists/"><u>In 2024, Unfading Flight Ambitions Top 10 Longevity Drone Lists</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-honor-x50-gt-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Honor X50 GT Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-windows-11-more-engaging-with-themes/"><u>Make Windows 11 More Engaging with Themes</u></a></li>
<li><a href="https://win-blog.techidaily.com/movaviflacogg/"><u>Movaviのサポート:オンラインで無料FLACからOGGへ効率的な変換</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-to-zero-clutter-windows-auto-delete-feature/"><u>Navigate to Zero Clutter: Windows' Auto-Delete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-system-call-error-in-windows-os/"><u>Overcoming System Call Error in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-windows-email-and-scheduling-with-top-pics/"><u>Personalize Window's Email & Scheduling with Top Pics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-disabled-windows-account-access/"><u>Restoring Disabled Windows Account Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverting-windows-viewer-to-original-arrangement/"><u>Reverting Windows Viewer to Original Arrangement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-a-step-by-step-windows-11-reboot-guide/"><u>Reviving Your PC: A Step-by-Step Windows 11 Reboot Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-mobile-setup-with-one-click-apks-in-windows-11/"><u>Supercharge Your Mobile Setup with One Click APKs in Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/zoom-into-your-workspace-learn-screen-casting-via-ezvide/"><u>Zoom Into Your Workspace Learn Screen Casting via EZvide</u></a></li>
</ul></div>

