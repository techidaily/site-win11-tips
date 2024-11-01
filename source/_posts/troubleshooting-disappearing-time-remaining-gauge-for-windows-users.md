---
title: Troubleshooting Disappearing Time Remaining Gauge for Windows Users
date: 2024-10-27T18:51:50.023Z
updated: 2024-11-01T18:22:22.660Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Disappearing Time Remaining Gauge for Windows Users
excerpt: This Article Describes Troubleshooting Disappearing Time Remaining Gauge for Windows Users
keywords: Time Remaining Issue,Fixing Win Time Gauge,Window's Timer Troubleshoot,Windows Clock Error,Resolve PC Time Display,Addressing Win Time Loss,Correcting Timer Shortage
thumbnail: https://thmb.techidaily.com/aca7466ead46101c525a65c4ba2c61065f452c93cdf56e9e8e63cd78fa3eee10.jpg
---

## Troubleshooting Disappearing Time Remaining Gauge for Windows Users

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
<a href="https://united.elfm.net/c/5597632/2139558/4704" target="_top" id="2139558">
  <img src="//a.impactradius-go.com/display-ad/4704-2139558" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139558/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1030129/11832" target="_top" id="1030129">
  <img src="//a.impactradius-go.com/display-ad/11832-1030129" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1030129/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/updated-in-2024-next-gen-sound-and-vision-leading-devices-of-24/"><u>[Updated] In 2024, Next-Gen Sound and Vision Leading Devices of '24</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-revel-in-the-rhythm-of-rising-text/"><u>[Updated] Revel in the Rhythm of Rising Text</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-best-of-the-best-hexacopter-drone-reviews/"><u>2024 Approved Best of the Best Hexacopter Drone Reviews</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/comprehensive-full-system-backup-tutorial-for-various-windows-versions/"><u>Comprehensive Full System Backup Tutorial for Various Windows Versions</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discovering-the-value-of-caixuns-4k-75-android-smart-tv-a-thorough-performance-review/"><u>Discovering the Value of Caixun's 4K 75 Android Smart TV - A Thorough Performance Review</u></a></li>
<li><a href="https://tech-hub.techidaily.com/diy-custom-chatbot-creation-with-gpt-powered-tools-a-comprehhemic-approach/"><u>DIY Custom Chatbot Creation with GPT-Powered Tools – A Comprehhemic Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-telnet-setup-in-windows-10-and-11-wrap-up/"><u>Easy Telnet Setup in Windows 10 and 11 (Wrap Up)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-operational-mishap-fixing-0x0000011b-error/"><u>Handling Operational Mishap: Fixing 0X0000011B Error</u></a></li>
<li><a href="https://discover-dash.techidaily.com/mp4youtube/"><u>MP4ビデオの高品質YouTubeアップロードガイド</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-ideal-soundtrack-choices-selecting-songs-to-elevate-your-montage-masterpiece/"><u>New Ideal Soundtrack Choices Selecting Songs to Elevate Your Montage Masterpiece</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reboot-strategies-restarting-windows-in-three-steps/"><u>Reboot Strategies: Restarting Windows in Three Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-ctrl-failure-issues-in-windows-11-systems/"><u>Solving Ctrl Failure Issues in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-file-navigation-in-windows-integrate-movecopy-commands/"><u>Streamline File Navigation in Windows: Integrate 'Move'/'Copy' Commands</u></a></li>
</ul></div>

