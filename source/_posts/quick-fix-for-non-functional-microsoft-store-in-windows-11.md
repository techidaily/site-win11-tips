---
title: Quick Fix for Non-Functional Microsoft Store in Windows 11
date: 2024-10-31T17:41:18.266Z
updated: 2024-11-01T18:55:11.698Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fix for Non-Functional Microsoft Store in Windows 11
excerpt: This Article Describes Quick Fix for Non-Functional Microsoft Store in Windows 11
keywords: Windows 11 Store Issue,Microsoft Store Repair,Fixing Microsoft Store,Functioning MS Store,Quick Microsoft Fix,Restore MS Store,Stop Non-Functional Store
thumbnail: https://thmb.techidaily.com/600ab240c6c8b1ad864f3c8d1c4daad9b77c19a5afa889dc63fba4f50be8c27e.jpg
---

## Quick Fix for Non-Functional Microsoft Store in Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

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
<a href="https://aligracehair.sjv.io/c/5597632/2027195/19272" target="_top" id="2027195">
  <img src="//a.impactradius-go.com/display-ad/19272-2027195" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027195/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/updated-elevate-video-rankings-proven-youtube-seo-solutions-for-2024/"><u>[Updated] Elevate Video Rankings Proven YouTube SEO Solutions for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-full-screen-mastery-achieved-in-obs/"><u>[Updated] Full Screen Mastery Achieved in Obs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-breathe-life-into-your-reel-tips-for-perfect-slow-motion/"><u>[Updated] In 2024, Breathe Life Into Your Reel Tips for Perfect Slow Motion</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-master-facebooks-hd-livestreaming-techniques/"><u>[Updated] In 2024, Master Facebook’s HD Livestreaming Techniques</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-best-full-screen-recorders-windows-and-macos-version/"><u>2024 Approved Best Full-Screen Recorders - Windows & macOS Version</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-try-this-groundbreaking-free-valorant-audio-swap-tech/"><u>2024 Approved Try This Groundbreaking, Free Valorant Audio Swap Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compreptive-guide-virtualizing-win11-on-vmware-player-17/"><u>Compreptive Guide: Virtualizing Win11 on VMware Player 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-windows-snapping-with-powertoys-expertise/"><u>Designing Windows Snapping with PowerToys Expertise</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/direct-from-twitter-posting-engaging-video-content-on-snapchat/"><u>Direct From Twitter Posting Engaging Video Content on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-cpu-stewardship-managing-the-power-of-vanguards-sleep-service/"><u>Efficient CPU Stewardship: Managing the Power of Vanguard's Sleep Service</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/enhance-your-storytelling-mastering-the-green-screen-on-instagram/"><u>Enhance Your Storytelling Mastering the Green Screen on Instagram</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-illuminating-the-role-of-color-in-editing-mastery/"><u>In 2024, Illuminating the Role of Color in Editing Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-to-do-not-sync-here-are-easy-solutions/"><u>Microsoft To-Do Not Sync? Here Are Easy Solutions!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-access-to-blacklisted-windows-program/"><u>Reinstating Access to Blacklisted Windows Program</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/richer-imagery-enhancing-video-with-device-based-filters-for-2024/"><u>Richer Imagery Enhancing Video with Device-Based Filters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silencing-win-11s-mobility-hub/"><u>Silencing Win 11'S Mobility Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-marooned-xbox-app-issue-step-by-step/"><u>Tackling the Marooned Xbox App Issue, Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-comprerant-guide-to-picture-scaling-in-windows-11/"><u>The Compreran't Guide to Picture Scaling in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-your-gaming-experience-from-windows-error/"><u>Unblocking Your Gaming Experience From Windows Error</u></a></li>
</ul></div>

