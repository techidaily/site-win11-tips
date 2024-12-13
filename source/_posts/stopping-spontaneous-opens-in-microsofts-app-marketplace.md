---
title: Stopping Spontaneous Opens in Microsoft's App Marketplace
date: 2024-12-09T23:24:19.070Z
updated: 2024-12-12T21:40:45.943Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stopping Spontaneous Opens in Microsoft's App Marketplace
excerpt: This Article Describes Stopping Spontaneous Opens in Microsoft's App Marketplace
keywords: Opens Prevention,Marketplace Security,Microsoft App Safety,Stop Unauthorized Access,Protect App Store,Secure MS Apps,Avoid Spontaneous Opens
thumbnail: https://thmb.techidaily.com/33f7a6674447c8f7173ff1c687707de6ab2b192d47bf8afae9f7fe02b3355e59.jpg
---

## Stopping Spontaneous Opens in Microsoft's App Marketplace

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Restart the Microsoft Store Services

 There’s a chance that the Microsoft Store keeps acting up because of a service malfunction. The Microsoft Store Install Service is the one that works in the background to keep the store working.

 This is why restarting the service might be enough to fix Microsoft Store.

1. In the Start menu search bar, search for**services** and select**Run as administrator** .
2. In the Services window, locate and open**Microsoft Store Install Service** .
3. Click**Stop > Start** to restart it.
4. Restart your computer and monitor if Microsoft Store keeps opening.

![Restart Microsoft Store service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-service-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Apply Generic Fixes for Microsoft Store Issues

 You may encounter this problem if the cache has become corrupted. As such, check out[how to fix a damaged Microsoft Store cache](https://www.makeuseof.com/ways-to-fix-damaged-microsoft-store-cache/) for more ways to fix this annoying problem.

 Similarly, a virus may be causing the Microsoft Store to open. Check out[how to remove malware using a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) and give your PC a deep clean.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix the Microsoft Store App Opening Itself

 Having the Microsoft Store app open by itself can be very disruptive, especially if it opens on top of all windows. Hopefully, one of these solutions worked and Microsoft Store has stopped launching by itself.

 If you’ve had enough and uninstalled it, you can still get Microsoft apps without the Microsoft Store.

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
<li><a href="https://fox-cloud.techidaily.com/new-20plus-laughs-no-boundaries-crafting-memes-across-metaverse-realms/"><u>[New] 20+ Laughs, No Boundaries Crafting Memes Across Metaverse Realms</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-airpods-alone-restoring-connection/"><u>[Updated] Airpods Alone Restoring Connection</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-under-100-budget-friendly-action-cams-top-choices-guide/"><u>[Updated] In 2024, Under-$100 Budget-Friendly Action Cams – Top Choices Guide</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-steps-to-acquire-free-picture-frame-videos/"><u>2024 Approved Steps to Acquire Free Picture Frame Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/bring-your-images-alive-on-android-with-these-5-powerful-editors-for-2024/"><u>Bring Your Images Alive on Android with These 5 Powerful Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disarming-webcam-error-code-a00f4289-in-windows-11-panorama/"><u>Disarming Webcam Error Code A00F4289 in Windows 11 Panorama</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-the-ultimate-gaming-experience-logitech-driving-force-gt-for-pc-with-windows-compatibility-win71011/"><u>Download the Ultimate Gaming Experience: Logitech Driving Force GT for PC with Windows Compatibility (Win7/10/11)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-empower-your-digital-tales-with-complimentary-upgrades/"><u>In 2024, Empower Your Digital Tales with Complimentary Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-office-error-0x80041015-on-windows/"><u>Mastering the Art of Fixing Office Error: 0X80041015 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-sticky-menu-issues-in-windows-11/"><u>Overcoming Sticky Menu Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rekindle-festive-spirit-with-enchanting-pane-decor/"><u>Rekindle Festive Spirit with Enchanting Pane Decor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-installation-with-microsofts-windows-cab-format/"><u>Streamlining File Installation with Microsoft's Windows CAB Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-rdp-connectivity-woes/"><u>Understanding and Resolving RDP Connectivity Woes</u></a></li>
</ul></div>

