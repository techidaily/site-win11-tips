---
title: "Handling Error: No Qt Platform Engine Available for Startup"
date: 2024-11-26T17:54:54.211Z
updated: 2024-11-27T16:07:46.156Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Handling Error: No Qt Platform Engine Available for Startup"
excerpt: "This Article Describes Handling Error: No Qt Platform Engine Available for Startup"
keywords: Qt Engine Not Found,QT Platform Engine Error,Engine Initialization Failure,Qt Startup Issue,Missing Qt Plugin,No Qt Platform Available,Qt Engine Unavailable at Launch
thumbnail: https://thmb.techidaily.com/f244a4b607ff1304250df827a08b69767edd00f8e4433a759d16a32700c891a6.jpg
---

## Handling Error: No Qt Platform Engine Available for Startup

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the System File Checker didn’t fix the problem, there are[more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

## 6\. Uninstall Any Recent Windows Updates

 Sometimes, Windows display the “Application failed because no QT platform plugin could be initialized” error after a system update. In this case, you can load a restore point to undo the change and get rid of the error.

 But if there’s no restore point available, you can manually uninstall Windows updates.

1. Launch Windows Settings by pressing**Win + I** .
2. From the left pane, click**Windows Update > Update History** .
3. Head to**Related Settings** and click**Uninstall updates** .
4. Right-click the latest update and select**Uninstall** .

![Uninstall recent Windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-updates-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of the QT Error on Windows

 Hopefully, one or more of the above solutions helped you fix the “Application failed to start because no Qt platform plugin could be initialized” error.

 Sometimes, it’s difficult to figure out the exact cause of a Windows error, and reinstalling the app every time might not be the most efficient solution. To speed up the troubleshooting process, you should use one of the many Windows repair tools.

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
<li><a href="https://win11.techidaily.com/addressing-screen-driver-crash-in-windows-11/"><u>Addressing Screen Driver Crash in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprerante-windows-11-printer-issues-and-fixes-heres-how/"><u>Comprerante Windows 11 Printer Issues & Fixes, Here's How</u></a></li>
<li><a href="https://extra-resources.techidaily.com/content-crafting-top-smartphone-picks-in-ranking/"><u>Content Crafting Top Smartphone Picks in Ranking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-in-use-errors-fixing-resource-locks-on-windows-11/"><u>Disabling 'In Use' Errors: Fixing Resource Locks on Windows 11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/discover-the-premier-home-cinema-pc-picks-for-an-unmatched-viewing-pleasure/"><u>Discover the Premier Home Cinema PC Picks for an Unmatched Viewing Pleasure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escalate-your-network-speed-tackling-windows-100mbps-threshold/"><u>Escalate Your Network Speed: Tackling Windows' 100Mbps Threshold</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-official-msi-z370-a-pro-drivers-for-free-immediate-download/"><u>Get the Official MSI Z370-A Pro Drivers for Free - Immediate Download!</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-oppo-a56s-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Oppo A56s 5G Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-slideshow-crafting-without-software-installation-7-steps/"><u>Masterful Slideshow Crafting Without Software Installation (7 Steps)</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/solving-the-1-quick-303-error-on-your-hard-drive-a-step-by-step-guide/"><u>Solving the 1 Quick (303) Error on Your Hard Drive: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-tech-seven-tactics-to-resolve-obs-server-issue/"><u>Streamlining Your Tech: Seven Tactics to Resolve OBS Server Issue</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-computer-components-the-ultimate-tech-guide/"><u>Tom's Computer Components: The Ultimate Tech Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-wi-fi-issues-in-windows-11-a-pocket-guide-with-8-solutions/"><u>Troubleshoot Wi-Fi Issues in Windows 11: A Pocket Guide with 8 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understand-and-optimize-tech-health-with-windows-live-panels/"><u>Understand and Optimize Tech Health with Window's Live Panels</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Oppo Find X7 Ultra? | Dr.fone</u></a></li>
</ul></div>

