---
title: Correcting the Erratic Power Estimate Display in Windows 11 OS
date: 2025-01-17T17:58:16.642Z
updated: 2025-01-18T17:06:31.601Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

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
<li><a href="https://fox-friendly.techidaily.com/updated-unlock-new-dimensions-of-your-missing-iphone-x/"><u>[Updated] Unlock New Dimensions of Your Missing iPhone X</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-a-primer-on-using-azures-voice-to-text-service/"><u>2024 Approved A Primer on Using Azure's Voice-to-Text Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-avi-files-to-wmv-format-for-free-a-comprehensive-guide-using-the-online-movavi-video-converter/"><u>Convert AVI Files to WMV Format for Free: A Comprehensive Guide Using the Online Movavi Video Converter</u></a></li>
<li><a href="https://win-blog.techidaily.com/defeating-starfield-pc-issues-a-guide-to-stability-and-performance-optimization/"><u>Defeating Starfield PC Issues: A Guide to Stability & Performance Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-raw-to-jpeg-image-converter-simple-and-fast/"><u>Efficient RAW to JPEG Image Converter - Simple and Fast</u></a></li>
<li><a href="https://screen-recording.techidaily.com/how-to-quality-recording-of-your-roblox-journeys-on-mac-for-2024/"><u>How-To Quality Recording of Your Roblox Journeys on Mac for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-charting-a-path-to-monthly-earnings-from-youtube/"><u>In 2024, Charting a Path to Monthly Earnings From YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-22-video-editing-tutorial-applications-discover-the-ultimate-tools/"><u>Top 22 Video Editing Tutorial Applications - Discover the Ultimate Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformar-video-3gpp-a-mov-directamente-desde-la-web-por-nada-tecnica-facil-con-movavi/"><u>Transformar Video 3GPP a MOV Directamente Desde La Web Por Nada, Técnica Fácil Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformation-libre-de-raw-a-ligne-claire-avec-movavi/"><u>Transformation Libre De RAW À Ligne Claire Avec Movavi</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlocking-faster-mobile-data-speed-discover-easy-fixes-in-just-10-steps/"><u>Unlocking Faster Mobile Data Speed - Discover Easy Fixes in Just 10 Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-1011-and-acer-keyboard-reconnectivity-restored/"><u>Windows 10/11 & Acer: Keyboard Reconnectivity Restored</u></a></li>
</ul></div>

