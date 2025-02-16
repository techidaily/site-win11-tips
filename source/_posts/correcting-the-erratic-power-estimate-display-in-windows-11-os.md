---
title: Correcting the Erratic Power Estimate Display in Windows 11 OS
date: 2025-01-30T01:23:36.193Z
updated: 2025-02-02T20:13:44.203Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/new-visual-enhancement-expertly-applying-borders-on-social-media-images/"><u>[New] Visual Enhancement Expertly Applying Borders on Social Media Images</u></a></li>
<li><a href="https://extra-resources.techidaily.com/arcade-affordability-index/"><u>ARCADE AFFORDABILITY INDEX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-computer-storage-the-c-and-d-scene/"><u>Comparing Computer Storage: The 'C:' And 'D:' Scene</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comparing-performance-the-ultimate-guide-to-ipad-mini-and-ipad-air-contrast/"><u>Comparing Performance: The Ultimate Guide to iPad Mini and iPad Air Contrast</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-strategies-for-effective-online-image-trimming-for-2024/"><u>Expert Strategies for Effective Online Image Trimming for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-messages-failed-to-load-error-on-discord-for-windows/"><u>How to Fix the Messages Failed to Load Error on Discord for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-roblox-needs-quitting-on-windows-without-hesitation/"><u>How to Stop Roblox Needs Quitting on Windows Without Hesitation</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-oneplus-ace-2-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on OnePlus Ace 2 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/prioritizing-features-for-an-ideal-smart-tv/"><u>Prioritizing Features for an Ideal Smart TV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-solutions-for-windows-missing-lsass-components/"><u>Quick Solutions for Windows' Missing Lsass Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-virtual-disk-service-not-started-in-windows/"><u>Remedy for Virtual Disk Service Not Started in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-building-win11-self-extractables/"><u>Securely Building Win11 Self-Extractables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-audio-service-restart-process-before-boot-up/"><u>Simplifying Audio Service Restart Process Before Boot Up</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-lava-yuva-2-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Lava Yuva 2 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-watermark-your-videos-for-free-top-5-software-options/"><u>Updated In 2024, Watermark Your Videos for Free Top 5 Software Options</u></a></li>
</ul></div>

