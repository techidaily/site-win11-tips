---
title: How to Reinstate Accurate Battery Life Meter on PCs Running Win 11
date: 2024-09-10T20:47:11.335Z
updated: 2024-09-16T22:04:59.097Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reinstate Accurate Battery Life Meter on PCs Running Win 11
excerpt: This Article Describes How to Reinstate Accurate Battery Life Meter on PCs Running Win 11
keywords: Win 11 Battery Monitor,Win 11 Power Management,Win 11 Energy Efficiency,Win 11 Accurate Metering,Win 11 Battery Calibration,PCs Win 11 Life Meter,Win 11 Energy Saving Tips
thumbnail: https://thmb.techidaily.com/eaa498618a30b7449a5127779e22901025842c318bde80345b630595fb88d747.jpg
---

## How to Reinstate Accurate Battery Life Meter on PCs Running Win 11

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
<li><a href="https://youtube-data.techidaily.com/hat-lies-behind-the-unlisted-tag-on-youtube-for-2024/"><u>[New] What Lies Behind the 'Unlisted' Tag on YouTube for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-game-on-log-it-galaxy-phone-playthroughs-for-2024/"><u>[Updated] Game on, Log It! Galaxy Phone Playthroughs for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-peak-workshop-masterpiece-insight/"><u>2024 Approved Peak Workshop Masterpiece Insight</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-nokia-c300-frp-by-drfone-android/"><u>Full Guide to Bypass Nokia C300 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-conversational-ai-on-win11/"><u>How to Disable Conversational AI on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-run-task-sequence-error-0x8007000f-in-windows/"><u>How to Fix the Failed to Run Task Sequence Error 0X8007000f in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-capturing-the-perfect-snap-on-pexels/"><u>In 2024, Capturing the Perfect Snap on Pexels</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-realme-gt-neo-5-se-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Realme GT Neo 5 SE</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-success-the-essentials-of-crafting-great-reddit-threads/"><u>In 2024, Unlocking Success The Essentials of Crafting Great Reddit Threads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-windows-hiccups-with-top-4-pct-solutions/"><u>Navigate Windows' Hiccups with Top 4 PCT Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-server-woes-no-more-12-solutions-for-pc-apex-users-(156-chars/"><u>No-Server Woes, No More! 12 Solutions for PC Apex Users (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sly-startup-settings-concealing-the-shutdown-option/"><u>Sly Startup Settings: Concealing the Shutdown Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-stopping-fix-error-2e/"><u>Stop Windows From Stopping, Fix Error 2E</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123469/16836" target="_top" id="2123469">
  <img src="//a.impactradius-go.com/display-ad/16836-2123469" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123469/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

