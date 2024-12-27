---
title: "Revival Tactics: Restoring Microsoft Store on Win 11 & 11"
date: 2024-12-23T17:45:41.770Z
updated: 2024-12-27T19:16:11.951Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revival Tactics: Restoring Microsoft Store on Win 11 & 11"
excerpt: "This Article Describes Revival Tactics: Restoring Microsoft Store on Win 11 & 11"
keywords: Win 11 MSStore,Revive MSStore,Win 11 Store Restore,Windows Store Redo,Win 11 Microsoft Store Update,Win 11 Reinstate MSStore,Win 11 Restore Store
thumbnail: https://thmb.techidaily.com/36b23ef4c54f4e12997c9a2584ed2c68d00394366c249b53e078e95dee6e414c.jpg
---

## Revival Tactics: Restoring Microsoft Store on Win 11 & 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.

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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-top-5-ios-tools-to-download-facebook-movies-and-clips/"><u>[New] In 2024, Top 5 iOS Tools to Download Facebook Movies & Clips</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-value-airborne-innovations-top-5-budget-drone-selections/"><u>[Updated] Value Airborne Innovations Top 5 Budget Drone Selections</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-connectivity-at-its-peak-usb-c-and-the-hp-envy-27-monitor/"><u>2024 Approved Connectivity at Its Peak USB-C & the HP Envy 27 Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extended-support-for-windows-11-version-22h2-announced/"><u>Extended Support for Windows 11 Version 22H2 Announced</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-newcomer-to-pro-classic-diablo-techniques/"><u>From Newcomer to Pro: Classic Diablo Techniques</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-nokia-c12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-guide-to-unlock-your-samsung-galaxy-f04-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Samsung Galaxy F04</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-full-spectrum-analysis-unpacking-xstudio-video-workshop-essentials/"><u>In 2024, Full Spectrum Analysis Unpacking XStudio Video Workshop Essentials</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-htc-u23-pro-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from HTC U23 Pro Phones with/without a PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-money-multiplier-how-to-maximize-youtube-profits-with-mobile-viewers/"><u>In 2024, Money Multiplier How to Maximize YouTube Profits with Mobile Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insider-take-unveiling-key-upgrades-in-feb-update/"><u>Insider Take: Unveiling Key Upgrades in FEB Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-windows-shortcuts-for-uwp-apps/"><u>Mastering the Art of Windows Shortcuts for UWP Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-csgo-playthrough-speed-with-these-tips/"><u>Maximize CSGO Playthrough Speed with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win-11-recycle-bin-crashes-and-issues/"><u>Overcoming Win 11 Recycle Bin Crashes & Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-missing-peripheral-driver-issues-for-optimal-performance/"><u>Troubleshooting Missing Peripheral Driver Issues for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-window-11-themes-with-advanced-registry-techniques/"><u>Unlocking Window 11 Themes with Advanced Registry Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-alternative-approaches-to-open-your-apps/"><u>Windows 10: Alternative Approaches to Open Your Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution</u></a></li>
</ul></div>

