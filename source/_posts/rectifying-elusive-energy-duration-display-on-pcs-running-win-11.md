---
title: Rectifying Elusive Energy Duration Display on PCs Running Win 11
date: 2024-10-28T19:26:26.699Z
updated: 2024-11-01T17:10:19.416Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying Elusive Energy Duration Display on PCs Running Win 11
excerpt: This Article Describes Rectifying Elusive Energy Duration Display on PCs Running Win 11
keywords: WIN11 Energy Display Fix,Elusive Energy Monitor,Power Status Correction,Windows 11 Uptime Alert,Duration Time Error Win11,Power Bottleneck Resolve,Efficiency Screen Update PCs
thumbnail: https://thmb.techidaily.com/f5d1594082aca6452dbc25a49388a37fc7e84721f123ecd76572cb92530c4365.jpg
---

## Rectifying Elusive Energy Duration Display on PCs Running Win 11

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
<a href="https://appsumo.8odi.net/c/5597632/2094429/7443" target="_top" id="2094429">
  <img src="//a.impactradius-go.com/display-ad/7443-2094429" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094429/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151872/7443" target="_top" id="2151872">
  <img src="//a.impactradius-go.com/display-ad/7443-2151872" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151872/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-blue.techidaily.com/new-ultimate-guide-to-online-portals-for-text-artistry/"><u>[New] Ultimate Guide to Online Portals for Text Artistry</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-affordable-setups-tailored-obs-for-budget-computers/"><u>[Updated] In 2024, Affordable Setups Tailored OBS for Budget Computers</u></a></li>
<li><a href="https://extra-information.techidaily.com/1-tablespoon-baking-powder/"><u>1 Tablespoon Baking Powder</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-future-on-your-screen-best-performing-8k-tvs-ranked/"><u>2024 Approved The Future On Your Screen Best Performing 8K TVs Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descubra-e-instale-o-capcut-para-windows-uso-facil-do-editor-de-videos-mais-popular/"><u>Descubra E Instale O CapCut Para Windows: Uso Fácil Do Editor De Vídeos Mais Popular</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-you-when-your-poco-x6-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your Poco X6 is off? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-poco-c50-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Poco C50? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professional-content-development-services-by-movavi-team/"><u>Professional Content Development Services by Movavi Team</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-samsung-galaxy-a25-5g-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Samsung Galaxy A25 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-3-methods-for-altering-video-backdrops-effortlessly/"><u>Top 3 Methods for Altering Video Backdrops Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transfert-de-fichiers-gratuits-guides-pour-convertir-vos-chansons-mp3-en-aiff-avec-movavi-online/"><u>Transfert De Fichiers Gratuits : Guides Pour Convertir Vos Chansons MP3 en AIFF Avec Movavi Online</u></a></li>
<li><a href="https://tech-haven.techidaily.com/what-are-the-response-boundaries-for-chatgpt-interactions/"><u>What Are the Response Boundaries for ChatGPT Interactions?</u></a></li>
</ul></div>

