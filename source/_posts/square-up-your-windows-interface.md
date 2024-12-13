---
title: Square Up Your Windows Interface
date: 2024-12-06T18:59:23.598Z
updated: 2024-12-12T20:16:02.875Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Square Up Your Windows Interface
excerpt: This Article Describes Square Up Your Windows Interface
keywords: Windows UI Enhancement,User Interface Update,Modernizing Windows Look,Improve Window Design,Square Interface Boost,Elevate Windows Aesthetics,Windows Theme Upgrade
thumbnail: https://thmb.techidaily.com/290fdfbe7988bc73a9658535e5e89697be7bda898900fabab3b9425630194609.jpg
---

## Square Up Your Windows Interface

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-efficient-photographic-snipping-techniques-windows-11/"><u>[Updated] 2024 Approved Efficient Photographic Snipping Techniques, Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-overcoming-inconsistency-stop-obs-frame-loss/"><u>[Updated] 2024 Approved Overcoming Inconsistency Stop OBS Frame Loss</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-cyclings-apex-titles-for-gamers-for-2024/"><u>[Updated] Cycling's Apex Titles for Gamers for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-infusing-interactive-elements-incorrante-youtube-music-into-videography-for-2024/"><u>[Updated] Infusing Interactive Elements Incorrante YouTube Music Into Videography for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1725288319530-winxdvd/"><u>如何便捷地利用WinXDVD：功能介紹及使用方法指南</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/create-magic-download-premium-soundscapes-now-in-2024/"><u>Create Magic Download Premium Soundscapes Now, In 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/discover-the-creme-de-la-creme-of-mac-snipers-for-2024/"><u>Discover the Crème De La Crème of Mac Snipers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-print-device-instability-in-win-os/"><u>How to Prevent Print Device Instability in Win OS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mighty-machines-meet-thieyes-t5-vs-jcb-sjcam-s6/"><u>In 2024, Mighty Machines Meet Thieye's T5 Vs JCB SJCAM S6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-high-contrast-brightness-in-windows/"><u>Lowering High Contrast Brightness in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-windows-calculator-darker/"><u>Making Windows Calculator Darker</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/maximizing-efficiency-with-azures-audio-transcription/"><u>Maximizing Efficiency with Azure's Audio Transcription</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-desktop-with-window-notifications/"><u>Streamlining Your Desktop With Window Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-overcoming-server-notifications-on-apex-legends-(156-chars/"><u>Top Strategies: Overcoming Server Notifications on Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-windows-process-aggregatorhostexe-usage-and-risks-explored/"><u>What Is Windows Process AggregatorHost.exe? Usage and Risks Explored</u></a></li>
</ul></div>

