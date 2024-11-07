---
title: Resolving Absence of Power Elapsed Display in Windows 11
date: 2024-11-03T22:17:24.498Z
updated: 2024-11-07T10:31:43.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Absence of Power Elapsed Display in Windows 11
excerpt: This Article Describes Resolving Absence of Power Elapsed Display in Windows 11
keywords: Win11 Power Error Fix,Elapsed Time Displacement Issue,W11 Power Status Glitch,Correcting Windows Power Failure,Resolve Win11 Elapsed Display,Power Event Recovery in Windows 11,Address Power Loss Warning Windows
thumbnail: https://thmb.techidaily.com/733caf2abbd8fb995bf457552e00ba90aafeaec9c6d7712345148ce88c83b02a.jpg
---

## Resolving Absence of Power Elapsed Display in Windows 11

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
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-cloud.techidaily.com/new-augmenting-creativity-with-the-best-ai-for-podcast-names-for-2024/"><u>[New] Augmenting Creativity with the Best AI for Podcast Names for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-seamless-screen-capture-software-w10-edition/"><u>[New] Seamless Screen Capture Software, W10 Edition</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/he-aspiring-asmr-producers-guide-to-video-excellence/"><u>[New] The Aspiring ASMR Producer's Guide to Video Excellence</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-5-efficient-ways-to-store-movies-and-videos-mov-in-windows/"><u>[Updated] 2024 Approved 5 Efficient Ways to Store Movies & Videos (.mov) in Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-capture-life-in-motion-using-ipad-filming-techniques/"><u>2024 Approved Capture Life in Motion Using iPad Filming Techniques</u></a></li>
<li><a href="https://fox-blue.techidaily.com/bend-and-shape-your-text-with-3d-effects-in-illustrator/"><u>Bend and Shape Your Text with 3D Effects in Illustrator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-problems-to-perfect-integration-steps-for-optimal-add-ons-in-windows-os/"><u>From Problems to Perfect Integration: Steps for Optimal Add-Ons in Windows OS</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-ensure-your-graphics-card-supports-call-of-duty-warzone-on-windows-11/"><u>How To Ensure Your Graphics Card Supports Call of Duty: Warzone on Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-apps-from-xiaomi-redmi-13c-5g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Apps from Xiaomi Redmi 13C 5G to Another | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-interventions-nine-fixes-to-stop-wwe-crashes/"><u>Immediate Interventions: Nine Fixes to Stop WWE Crashes</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-hardware-detection-alerts/"><u>Navigating Through Hardware Detection Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reduce-windows-surrounders-for-better-control/"><u>Reduce Windows Surrounders for Better Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-your-windows-11-deskconnect-experience/"><u>Revitalizing Your WIndows 11 DeskConnect Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-share-failures-on-geforce/"><u>Strategies for Resolving Share Failures on GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-win11s-update-failure-0x30017/"><u>Strategies for Win11's Update Failure #0X30017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-efficient-backup-of-notebook-apps/"><u>Techniques for Efficient Backup of Notebook Apps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722896459701-the-future-of-android-awaits-download-android-16-for-free-insights-into-release-timing-estimated-costs-and-advanced-features/"><u>The Future of Android Awaits: Download Android 16 for Free - Insights Into Release Timing, Estimated Costs & Advanced Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unravel-word-mysteries-quickly-with-windows-11/"><u>Unravel Word Mysteries Quickly with Windows 11</u></a></li>
</ul></div>

