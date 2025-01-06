---
title: Unfreezing Frozen Windows Run Logs
date: 2025-01-05T07:59:41.931Z
updated: 2025-01-05T20:02:32.155Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unfreezing Frozen Windows Run Logs
excerpt: This Article Describes Unfreezing Frozen Windows Run Logs
keywords: Unfreeze Windows Logs,Fix Windows Freeze,Windows Log Diagnosis,Stop Windows Crash Logs,Resolve Windows Errors,Clear Frozen System Logs,Enable Running Windows Logs
thumbnail: https://thmb.techidaily.com/795b74ea54cc5678eb54323c8f0f4911a2d522641c62a676cf0d7c5aa1dfbffa.jpg
---

## Unfreezing Frozen Windows Run Logs

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-quick-stitching-together-synchronizing-obs-and-zoom/"><u>[New] Quick Stitching Together Synchronizing OBS and Zoom</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-apple-m1-pro-versus-m1-max-unveiling-variations-for-2024/"><u>[Updated] Apple M1 Pro Versus M1 Max Unveiling Variations for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-delving-into-the-chronology-of-windows-movie-maker-editions/"><u>[Updated] Delving Into the Chronology of Windows Movie Maker Editions</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-bringing-your-vision-alive-transferring-vids-from-premiere/"><u>[Updated] In 2024, Bringing Your Vision Alive Transferring Vids From Premiere</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-upside-of-asmr-a-closer-look-at-its-advantages/"><u>2024 Approved The Upside of ASMR A Closer Look At Its Advantages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/covert-menu-configurations-for-modern-windows/"><u>Covert Menu Configurations for Modern Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/digital-zen-spaces-the-leading-10-sites-for-soothing-the-soul-for-2024/"><u>Digital Zen Spaces The Leading 10 Sites for Soothing the Soul for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expanding-accessibility-to-external-devices-in-explorer/"><u>Expanding Accessibility to External Devices in Explorer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-delete-photos-from-facebook/"><u>How to Delete Photos From Facebook</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-vivo-v30-pro-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Vivo V30 Pro</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-vivo-t2-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Vivo T2 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-usage-profile-deciphering-your-windows-pcs-energy-needs/"><u>Power Usage Profile: Deciphering Your Windows PC's Energy Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-self-update-windows-148-chars/"><u>Step-by-Step Guide to Self-Update Windows (148 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-quick-access-to-visual-keyboard/"><u>Windows 11'S Quick Access to Visual Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winstore-breakdown-overcoming-error-0x80072f17/"><u>WinStore Breakdown: Overcoming Error 0X80072F17</u></a></li>
</ul></div>

