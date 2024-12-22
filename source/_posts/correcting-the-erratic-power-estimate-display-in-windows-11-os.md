---
title: Correcting the Erratic Power Estimate Display in Windows 11 OS
date: 2024-12-19T01:38:55.605Z
updated: 2024-12-22T04:18:07.044Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-tips.techidaily.com/converting-sdr-video-to-hdr-a-comprehensive-tutorial/"><u>Converting SDR Video to HDR - A Comprehensive Tutorial</u></a></li>
<li><a href="https://win-forum.techidaily.com/defy-the-restrictions-a-step-by-step-to-run-windows-11-on-prohibited-cpus/"><u>Defy the Restrictions: A Step-by-Step to Run Windows 11 on Prohibited CPUs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-solutions-overcoming-windows-install-steps-freeze/"><u>Essential Solutions: Overcoming Windows Install Steps Freeze</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-sony-xperia-1-v-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Sony Xperia 1 V Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/asts-financial-portrait-for-2024/"><u>Mr. Beast’s Financial Portrait for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-world-of-microsoft-code-assistant/"><u>Navigating the World of Microsoft Code Assistant</u></a></li>
<li><a href="https://data-wizards.techidaily.com/nebula-data-revival-techniques-for-sql/"><u>Nebula Data Revival Techniques for SQL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-save-failed-issue-for-windows-users/"><u>Overcoming Save Failed Issue for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-lost-remote-links-on-your-home-pc/"><u>Restoring Lost Remote Links on Your Home PC</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/storytelling-revolution-free-cross-platform-social-sensations/"><u>Storytelling Revolution FREE, Cross-Platform Social Sensations</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/strategic-use-of-jump-cuts-for-non-linear-storytelling/"><u>Strategic Use of Jump Cuts for Non-Linear Storytelling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-remediate-error-code-0x80300024/"><u>Strategies to Remediate Error Code: 0X80300024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-cpu-and-memory-for-seamless-browsing-experience/"><u>Streamlining CPU & Memory for Seamless Browsing Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-blocking-random-shortcuts-on-pc/"><u>Techniques for Blocking Random Shortcuts on PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-power-of-multitasking-mastering-ffpm-for-2024/"><u>The Power of Multitasking Mastering FFPM for 2024</u></a></li>
<li><a href="https://techidaily.com/ultimate-guide-selecting-the-perfect-mobile-case-for-your-device/"><u>Ultimate Guide: Selecting the Perfect Mobile Case for Your Device</u></a></li>
</ul></div>

