---
title: Fixing Incorrect Estimated Time Remaining Indicator in Win 11
date: 2024-10-23T22:42:32.061Z
updated: 2024-10-26T22:09:06.000Z
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
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/1716069693154-updated-in-2024-engaging-recorders-within-huawei-mate-and-p-series-for-video-capture/"><u>[Updated] In 2024, Engaging Recorders Within Huawei Mate and P-Series for Video Capture.</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-unlock-the-potential-of-your-facebook-lives/"><u>[Updated] In 2024, Unlock the Potential of Your Facebook Lives</u></a></li>
<li><a href="https://driver-error.techidaily.com/2-in-the-nextteacherbmwits/"><u>2 in the nextTeacher_BMWits</u></a></li>
<li><a href="https://vp-tips.techidaily.com/breaking-down-why-syma-x5c-is-top-notch-for-new-dronists-for-2024/"><u>Breaking Down Why Syma X5C Is Top-Notch for New Dronists for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-non-responsive-scrolls-in-microsoft-excel-2019/"><u>End Non-Responsive Scrolls in Microsoft Excel 2019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-subsys-to-strategy-preparing-for-modern-android-use/"><u>From Subsys to Strategy: Preparing For Modern Android Use</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-nokia-xr21-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Nokia XR21</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-perfect-pathway-insta-to-tiktok-junction/"><u>In 2024, The Perfect Pathway Insta to TikTok Junction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-linux-within-the-windows-domain/"><u>Leveraging Linux Within the Windows Domain</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-space-windows-storage-optimization-guide/"><u>Maximizing Space: Windows Storage Optimization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-permission-denied-saving-issue-on-pc/"><u>Resolving 'Permission Denied' Saving Issue on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-windows-enforced-verification-for-unverified-drivers/"><u>Sidestep Windows Enforced Verification for Unverified Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-five-ways-your-info-is-snatched-by-win11/"><u>The Five Ways Your Info Is Snatched by Win11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/troubleshooting-tactics-for-when-your-zoom-screenshare-fails/"><u>Troubleshooting Tactics for When Your Zoom Screenshare Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-control-fixing-steam-disk-write-errors/"><u>Winning Back Control: Fixing Steam Disk Write Errors</u></a></li>
</ul></div>

