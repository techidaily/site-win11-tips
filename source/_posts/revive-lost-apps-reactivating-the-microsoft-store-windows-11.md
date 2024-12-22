---
title: "Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)"
date: 2024-12-17T19:22:37.233Z
updated: 2024-12-22T06:25:27.673Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)"
excerpt: "This Article Describes Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)"
keywords: WinStore Revive Guide,Windows Reinstalls,Activate Windows Store,MS Store Restore,Reactivate Apps Windows,Microsoft Store Reset,Lost Apps Fix Windows 11
thumbnail: https://thmb.techidaily.com/b926e430c3910450366f0c5eac6f2faf425580bfe11541a9628c11209d7640f5.jpg
---

## Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-web.techidaily.com/ddressing-missing-image-display-in-youtubes-shorts-for-2024/"><u>[New] Addressing Missing Image Display in YouTubes Shorts for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-mastering-cross-service-playlist-migration-step-by-step-guide/"><u>[Updated] In 2024, Mastering Cross-Service Playlist Migration Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-revolutionary-tactics-for-enhanced-roi-in-animated-facebook-advertising/"><u>[Updated] In 2024, Revolutionary Tactics for Enhanced ROI in Animated Facebook Advertising</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-pioneering-time-lapse-mastery-full-slomo-app-evaluation-2024/"><u>[Updated] Pioneering Time-Lapse Mastery Full SloMo App Evaluation, 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-elevate-instagram-presence-with-professional-video-editing-skills/"><u>In 2024, Elevate Instagram Presence with Professional Video Editing Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-steam-dns-cache-cleansing-on-windows-machines/"><u>Mastering Steam DNS Cache Cleansing on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-on-mac-running-windows-11-through-parallels/"><u>Maximizing Productivity on Mac: Running Windows 11 Through Parallels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-performance-perfecting-your-win11-startups/"><u>Proactive Performance: Perfecting Your Win11 Startups</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-guide-to-downloading-and-updating-synaptics-drivers-on-your-pc/"><u>Quick Guide to Downloading and Updating Synaptics Drivers on Your PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-guide-to-increasing-fps-while-playing-tainted-grail-conquest/"><u>Step-by-Step Guide to Increasing FPS While Playing Tainted Grail: Conquest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-system-updates-via-explorers-context-menus/"><u>Streamlining System Updates via Explorer's Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-entering-safe-mode-in-windows-11-devices/"><u>The Essentials of Entering Safe Mode in Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-syncing-two-windows-systems-with-aoemi/"><u>The Ultimate Guide to Syncing Two Windows Systems with AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workspace-combining-android-tabs-with-w11-pcs/"><u>Transform Your Workspace: Combining Android Tabs with W11 PCs</u></a></li>
</ul></div>

