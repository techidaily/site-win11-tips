---
title: Fixing Incorrect Estimated Time Remaining Indicator in Win 11
date: 2024-10-15T19:58:48.139Z
updated: 2024-10-20T18:38:58.398Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Incorrect Estimated Time Remaining Indicator in Win 11
excerpt: This Article Describes Fixing Incorrect Estimated Time Remaining Indicator in Win 11
keywords: Fix Win 11 Time Display,Win 11 Time Reminder Update,Win 11 Estimate Timer Correction,Correct Windows Time Indicator,Resolve PC Time Error W11,Adjust Win 11 ETRI Fix,Timing Issue in Win 11 Help
thumbnail: https://thmb.techidaily.com/64cbdaa1aef5615ff39347b9db4c0280ec8c3ce520d27154774aa65c3ef13831.jpg
---

## Fixing Incorrect Estimated Time Remaining Indicator in Win 11

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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/1995803/22899" target="_top" id="1995803">
  <img src="//a.impactradius-go.com/display-ad/22899-1995803" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/1995803/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918714/19272" target="_top" id="1918714">
  <img src="//a.impactradius-go.com/display-ad/19272-1918714" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918714/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016165/19272" target="_top" id="2016165">
  <img src="//a.impactradius-go.com/display-ad/19272-2016165" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016165/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://games-able.techidaily.com/enhancing-steam-online-status-on-win11/"><u>Enhancing Steam Online Status on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-discord-overlay-not-working-on-windows/"><u>How to Fix the Discord Overlay Not Working on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-show-the-minimum-or-maximum-processor-state-in-the-power-options-menu-on-windows/"><u>How to Show the Minimum or Maximum Processor State in the Power Options Menu on Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/iphone-and-android-compared-top-youtube-app-analysis/"><u>IPhone & Android Compared Top YouTube App Analysis</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-of-corrupted-or-lost-d3dcompiler47dll-on-your-pc/"><u>Resolving the Issue of Corrupted or Lost D3DCOMPILER_47.dll on Your PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-vivo-y27s-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Vivo Y27s Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-data-sharing-on-pc-a-curated-list-of-leading-tools/"><u>Simplified Data Sharing on PC: A Curated List of Leading Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-integrating-invisible-drop-downs-in-win-oses/"><u>Stealth Mode: Integrating Invisible Drop-Downs in Win OSes</u></a></li>
<li><a href="https://facebook.techidaily.com/tips-for-allowing-unnamed-comments-on-your-fb-group/"><u>Tips for Allowing Unnamed Comments on Your FB Group</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-11-dialer-interface-effortlessly/"><u>Unlock Windows 11 Dialer Interface Effortlessly</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-the-secrets-of-crafting-perfect-audio-for-videos/"><u>Unveiling the Secrets of Crafting Perfect Audio for Videos</u></a></li>
</ul></div>

