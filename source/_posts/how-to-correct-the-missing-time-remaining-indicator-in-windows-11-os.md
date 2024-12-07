---
title: How to Correct the Missing Time Remaining Indicator in Windows 11 OS
date: 2024-12-04T22:03:25.888Z
updated: 2024-12-06T16:44:33.804Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct the Missing Time Remaining Indicator in Windows 11 OS
excerpt: This Article Describes How to Correct the Missing Time Remaining Indicator in Windows 11 OS
keywords: Fix Missing Time Reminder,Windows 11 Time Alert Fix,Correct Time Display Issue,Time Indicator Reset in Win11,Update Time Feature Win11,Remaining Time Monitor Setup,Fix Time Reminder Indicator
thumbnail: https://thmb.techidaily.com/fd844f53885e2c32c9ef30bfaf7233832cc28d58125ca084d49daf8878117921.png
---

## How to Correct the Missing Time Remaining Indicator in Windows 11 OS

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-essential-virtual-worlds-worth-playing/"><u>[Updated] In 2024, Essential Virtual Worlds Worth Playing</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-picks-for-the-modern-buyer-advanced-360cams/"><u>2024 Approved Top Picks for the Modern Buyer Advanced 360Cams</u></a></li>
<li><a href="https://win-able.techidaily.com/battlefield-4-not-initializing-step-by-step-pc-optimization-techniques/"><u>Battlefield 4 Not Initializing: Step-by-Step PC Optimization Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-solving-windows-11s-app-startup-error-code-0xc000003e/"><u>Deciphering and Solving Windows 11'S App Startup Error: Code 0XC000003E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-win11s-shop-error-code-x800704cf/"><u>Eliminating Win11's Shop Error Code X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essentials-of-windows-system-updates/"><u>Essentials of Windows' System Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-the-not-supported-error-in-miracast-with-a-simple-graphics-driver-update/"><u>Fix the Not Supported Error in Miracast with a Simple Graphics Driver Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-hard-drive-classification-on-windows/"><u>Guide to Hard Drive Classification on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guided-steps-altering-administrative-profile-in-windows-11/"><u>Guided Steps: Altering Administrative Profile in Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-nvidia-geforce-210-driver-enhancements-for-windows-10/"><u>Latest NVIDIA GeForce 210 Driver Enhancements for Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-download-pace-in-utorrent-for-windows-users/"><u>Mastering File Download Pace in uTorrent, for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-your-pcs-primary-command-line-editor/"><u>Perfect Your PC's Primary Command Line Editor</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/secure-the-new-ipad-9th-generation-at-a-bargain-price-of-250-following-apples-most-recent-launch-tech-news/"><u>Secure the New iPad (9Th Generation) at a Bargain Price of $250 Following Apple’s Most Recent Launch | Tech News</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitters-top-10-giggle-generators/"><u>Twitter's Top 10 Giggle Generators</u></a></li>
<li><a href="https://article-posts.techidaily.com/understanding-theta-s-complete-technical-review-for-2024/"><u>Understanding Theta S Complete Technical Review for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/which-is-superior-for-screen-recording-obs-studio-or-fraps-in-2024/"><u>Which Is Superior for Screen Recording – OBS Studio or Fraps, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-pcs-proclaim-their-superiority-to-mac-users-9/"><u>Why PCs Proclaim Their Superiority to Mac Users (#9)</u></a></li>
</ul></div>

