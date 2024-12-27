---
title: Correcting the Erratic Power Estimate Display in Windows 11 OS
date: 2024-12-24T18:56:59.907Z
updated: 2024-12-27T17:59:17.137Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-optimizing-team-calls-prepost-meeting-screen-customization/"><u>[Updated] 2024 Approved Optimizing Team Calls Pre/Post-Meeting Screen Customization</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-unlocking-twitters-potential-with-live-videos/"><u>[Updated] In 2024, Unlocking Twitter's Potential with Live Videos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-multimedia-designers-space/"><u>[Updated] Multimedia Designer's Space</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/8-mirrorless-cameras-to-elevate-your-vlogging-game/"><u>Best 8 Mirrorless Cameras to Elevate Your Vlogging Game</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-11-pro-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Realme 11 Pro Phone without Any Data Loss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-win-gurus-6-premier-gpu-stress-testers/"><u>Identifying Win Gurus: 6 Premier GPU Stress Testers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sound-symphony-music-within-whatsapp-statuses/"><u>In 2024, Sound Symphony Music Within WhatsApp Statuses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-vanished-5ghz-link-on-windows-11-with-these-simple-steps/"><u>Resolve Vanished 5GHz Link on Windows 11 With These Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-audacitys-error-9999-on-windows-oses/"><u>Resolving Audacity's Error 9999 on Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-clearing-darkened-remote-screen-on-windows/"><u>Techniques for Clearing Darkened Remote Screen on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-truth-about-esc-key-malfunctions-and-how-to-fix-them/"><u>The Truth About Esc Key Malfunctions and How to Fix Them</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/ultimate-guide-mastering-vimeo-video-editing-craft-your-flawless-visuals-with-top-tutorial/"><u>Ultimate Guide: Mastering Vimeo Video Editing - Craft Your Flawless Visuals with Top Tutorial</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unlimited-fake-faces-top-free-online-generators-reviewed/"><u>Unlimited Fake Faces Top Free Online Generators Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-new-ways-to-run-your-favorite-windows-software/"><u>Unlock New Ways to Run Your Favorite Windows Software</u></a></li>
</ul></div>

