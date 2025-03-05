---
title: Correcting the Erratic Power Estimate Display in Windows 11 OS
date: 2025-02-26T23:51:25.869Z
updated: 2025-03-04T18:43:07.204Z
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

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-unleash-the-power-of-obs-for-superior-skype-screen-capture/"><u>[New] In 2024, Unleash the Power of OBS for Superior Skype Screen Capture</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-the-ultimate-guide-to-vr-and-ar-game-apps-for-phones/"><u>[Updated] 2024 Approved The Ultimate Guide to VR and AR Game Apps for Phones</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-step-by-step-techniques-for-convincing-reddit-readers/"><u>[Updated] Step-By-Step Techniques for Convincing Reddit Readers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-watch-over-instagrams-friendship-shifts-for-2024/"><u>[Updated] Watch Over Instagram's Friendship Shifts for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-honor-play-8t-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Honor Play 8T to iPhone | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/boosting-operability-win11w8w7-via-mf4770n-update/"><u>Boosting Operability: Win11/W8/W7 via MF4770n Update</u></a></li>
<li><a href="https://blog-min.techidaily.com/die-top-3-wege-um-dvds-effizient-als-avi-dateien-zu-konvertieren-im-jahr-2023/"><u>Die Top-3 Wege, Um DVDs Effizient Als AVI-Dateien Zu Konvertieren Im Jahr 2023</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-realme-gt-5-pro-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Realme GT 5 Pro Phones? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intuitive-windows-management-auto-update-and-gpu-switch-routine/"><u>Intuitive Windows Management: Auto Update & GPU Switch Routine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-installer-failures-on-modern-windows/"><u>Navigating Through Installer Failures on Modern Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-unlock-your-creativity-best-video-editing-apps-with-music-for-mobile/"><u>New 2024 Approved Unlock Your Creativity Best Video Editing Apps with Music for Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-setup-validate-microphone-and-camera-on-windows-pcs/"><u>Streamlined Setup: Validate Microphone & Camera on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tech-bargain-collectors-get-free-lifetime-access-to-top-priced-black-friday-windows-11/"><u>The Ultimate Tech Bargain - Collectors Get Free Lifetime Access to Top-Priced Black Friday Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-4-solutions-for-troubleshooting-full-screen-capture-issues-in-windows-snipping-tool/"><u>Top 4 Solutions for Troubleshooting Full-Screen Capture Issues in Windows Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-for-purging-ms-defender-logs-in-win-1111/"><u>Top Strategies for Purging MS Defender Logs in Win 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-power-top-5-windows-pc-enhancements/"><u>Unleashing Power: Top 5 Windows PC Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgraded-run-options-in-windows-adding-powerful-script-execution-capability/"><u>Upgraded Run Options in Windows: Adding Powerful Script Execution Capability</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/weaving-a-captivating-tiktok-closure-narrative-for-2024/"><u>Weaving a Captivating TikTok Closure Narrative for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-made-simple-implementing-microsoft-works/"><u>Windows 10/11 Made Simple: Implementing Microsoft Works</u></a></li>
</ul></div>

