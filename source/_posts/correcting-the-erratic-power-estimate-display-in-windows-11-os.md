---
title: Correcting the Erratic Power Estimate Display in Windows 11 OS
date: 2025-01-05T20:19:51.774Z
updated: 2025-01-13T00:43:59.337Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting the Erratic Power Estimate Display in Windows 11 OS
excerpt: This Article Describes Correcting the Erratic Power Estimate Display in Windows 11 OS
keywords: Power Consumption Windows 11,Windows 11 Energy Display,Erratic Power Readings Fix,Power Meter Accuracy Win11,Correcting Power Screen,Win11 Energy Estimates,Improve OS Power Graphs
thumbnail: https://thmb.techidaily.com/860b3898b4af7e1c1dc6c593b5d2eb5997c8c8e6aad583a53288672db7b6ce02.jpg
---

## Correcting the Erratic Power Estimate Display in Windows 11 OS

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.

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
<li><a href="https://vp-tips.techidaily.com/updated-10-superior-text-conversion-tools-for-mac-enthusiasts/"><u>[Updated] 10 Superior Text Conversion Tools for Mac Enthusiasts</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-guide-to-screen-record-on-mac-with-shortcuts/"><u>[Updated] In 2024, Guide to Screen Record on Mac with Shortcuts</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-precise-color-correction-mastery-in-gopro-studio/"><u>[Updated] Precise Color Correction Mastery in GoPro Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-1011-functionality-add-diskspace-analyzer-menu-feature/"><u>Boosting Windows 10/11 Functionality: Add DiskSpace Analyzer Menu Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-drive-space-without-deletion/"><u>Boosting Windows Drive Space Without Deletion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bouncing-back-from-excessive-life-enthusiasm-on-windows-systems/"><u>Bouncing Back From Excessive Life Enthusiasm on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-file-save-obstacles-quick-fixes-to-overcome-win11-issues/"><u>Bypass File Save Obstacles: Quick Fixes to Overcome WIN11 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-sound-with-snipping-tools-screen-recorder-feature-max-156/"><u>Capturing Sound with Snipping Tool's Screen Recorder Feature (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-the-intrusive-windows-update-alerts/"><u>Cease the Intrusive Windows Update Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-defaults-optimize-your-windows-11-device-use/"><u>Changing Defaults: Optimize Your Windows 11 Device Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-your-cutting-edge-for-windows-screenshots/"><u>Choosing Your Cutting Edge for Windows Screenshots</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-comfort-in-simplicity-can-apples-vision-pro-enhance-your-economy-travel-experience/"><u>Exploring Comfort in Simplicity: Can Apple's Vision Pro Enhance Your Economy Travel Experience?</u></a></li>
<li><a href="https://win-docs.techidaily.com/krasser-vs-samsung-ssd-die-optimale-wahl-fur-ihre-speicheranforderungen/"><u>Krasser Vs. Samsung SSD - Die Optimale Wahl Für Ihre Speicheranforderungen</u></a></li>
<li><a href="https://driver-install.techidaily.com/opengl-shading-language-user-manual/"><u>OpenGL Shading Language User Manual</u></a></li>
<li><a href="https://win-howtos.techidaily.com/securing-permission-from-trustedinstaller-to-alter-windows-system-files/"><u>Securing Permission From TrustedInstaller to Alter Windows System Files</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-mystery-of-jvmdll-missing-a-step-by-step-guide/"><u>Solving the Mystery of JVM_DLL Missing: A Step-by-Step Guide</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-enduring-power-of-the-lg-gram-156-laptop-an-in-depth-look-at-its-remarkable-battery-life-and-portability/"><u>Unveiling the Enduring Power of the LG Gram 15.6 Laptop: An In-Depth Look at Its Remarkable Battery Life & Portability</u></a></li>
</ul></div>

