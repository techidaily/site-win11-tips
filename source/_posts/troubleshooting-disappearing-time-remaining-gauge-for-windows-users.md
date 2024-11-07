---
title: Troubleshooting Disappearing Time Remaining Gauge for Windows Users
date: 2024-11-03T08:55:51.249Z
updated: 2024-11-07T04:09:11.952Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1948954/19272" target="_top" id="1948954">
  <img src="//a.impactradius-go.com/display-ad/19272-1948954" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948954/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-essential-techniques-for-color-correction-in-gopro/"><u>[New] 2024 Approved Essential Techniques for Color Correction in GoPro</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-screen-capture-mastery-a-closer-look-at-recmeister-tech/"><u>2024 Approved Screen Capture Mastery A Closer Look at Recmeister Tech</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-x-studio-voice-synthesizer-windows-compatible/"><u>2024 Approved X-Studio Voice Synthesizer, Windows Compatible</u></a></li>
<li><a href="https://fox-links.techidaily.com/full-assessment-of-slomo-application-trends-for-2024/"><u>Full Assessment of SloMo Application - Trends for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/harnessing-luts-for-precision-controlled-image-editing-for-2024/"><u>Harnessing LUTs for Precision-Controlled Image Editing for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-telepathy-through-tech-healthcare-reimagined/"><u>In 2024, Telepathy Through Tech Healthcare Reimagined</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-xiaomi-redmi-note-13-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Xiaomi Redmi Note 13 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-d-drive-into-explorer-toolbar/"><u>Integrating D: Drive Into Explorer Toolbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-easing-endless-prompts-after-login-attempts/"><u>Methods for Easing Endless Prompts After Login Attempts</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-nokia-c12-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Nokia C12.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-taskbar-in-windows-11/"><u>Streamlining Your Taskbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-system-errors-in-dwarf-fortress/"><u>Understanding and Correcting System Errors in Dwarf Fortress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-performance-potential-windows-11-hdd-defrag/"><u>Unlock Performance Potential: Windows 11 HDD Defrag</u></a></li>
</ul></div>

