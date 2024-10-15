---
title: Renewal of Pre-Installed Software with Microsoft Store
date: 2024-10-11T12:43:25.845Z
updated: 2024-10-14T21:49:46.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Renewal of Pre-Installed Software with Microsoft Store
excerpt: This Article Describes Renewal of Pre-Installed Software with Microsoft Store
keywords: Windows Store Update,MS Store Redeem,Software Reinstallation,Patch New Apps,Digital Rights Management,Licensing Renewal,Microsoft OS Upgrade
thumbnail: https://thmb.techidaily.com/e0fa0d67e26442f6514904daf3cc23134382c2cc52f88c01d78e6b3f6c28c68c.jpg
---

## Renewal of Pre-Installed Software with Microsoft Store

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
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1584040/17916" target="_top" id="1584040">
  <img src="//a.impactradius-go.com/display-ad/17916-1584040" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1584040/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-building-a-diverse-content-portfolio-on-youtube-shorts/"><u>[Updated] 2024 Approved Building a Diverse Content Portfolio on YouTube Shorts</u></a></li>
<li><a href="https://win-news.techidaily.com/1-success-story-recovering-lost-partitions-on-western-digital-my-passport/"><u>1. Success Story: Recovering Lost Partitions on Western Digital My Passport</u></a></li>
<li><a href="https://review-topics.techidaily.com/does-find-my-friends-work-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/everything-you-need-to-know-about-unlocked-iphone-xr-by-drfone-ios/"><u>Everything You Need To Know About Unlocked iPhone XR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-developers-playground-windows-11s-enhanced-dev-drive/"><u>Exploring Developer's Playground: Windows 11'S Enhanced Dev Drive</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-realme-narzo-60x-5g-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Realme Narzo 60x 5G without App | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-make-a-splash-10-leading-music-video-makers-of-for-2024/"><u>New Make a Splash 10 Leading Music Video Makers Of for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-premiere-pro-system-essentials-what-you-need-to-know-before-you-start-for-2024/"><u>New Premiere Pro System Essentials What You Need to Know Before You Start for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcome-launch-difficulties-in-hogwarts-legacy-expert-tips-and-hacks/"><u>Overcome Launch Difficulties in Hogwarts Legacy - Expert Tips & Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powering-up-streamlined-settings-adjustments-in-window-11/"><u>Powering Up: Streamlined Settings Adjustments in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-failed-directx-setup-on-windows-pc/"><u>Remedying Failed DirectX Setup on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-previous-windows-backup-standards/"><u>Restoring Previous Windows Backup Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-the-absent-gpeditmsc-in-windows/"><u>Strategies for Tackling the Absent Gpedit.msc in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tray-upgrade-guide-custom-resource-monitoring-options/"><u>Tray Upgrade Guide: Custom Resource Monitoring Options</u></a></li>
</ul></div>

