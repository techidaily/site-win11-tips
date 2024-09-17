---
title: How to Re-Register Microsoft Store Apps on Windows 11 & 11
date: 2024-09-15T05:02:17.636Z
updated: 2024-09-16T22:47:37.552Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Re-Register Microsoft Store Apps on Windows 11 & 11
excerpt: This Article Describes How to Re-Register Microsoft Store Apps on Windows 11 & 11
keywords: Regain MS Store Access,Resetting App Permissions,Reactivate Microsoft Apps,Renewing OS Licenses,Reinstalling Windows Store,Restore Store Functionality,Update Windows 11 Apps
thumbnail: https://thmb.techidaily.com/6038b4e1d0b30613cb41c0ccc8733d5ac9ac78f0122128d3845aaea9056bae9f.jpg
---

## How to Re-Register Microsoft Store Apps on Windows 11 & 11

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

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

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
<li><a href="https://facebook-video-recording.techidaily.com/new-in-seconds-life-on-fb/"><u>[New] In Seconds, Life On FB</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-vr-buying-guide-mobile-liberty-or-tethered-unity/"><u>[New] The Ultimate VR Buying Guide Mobile Liberty or Tethered Unity?</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-achieving-muted-audibility-with-effortless-fading-in-lumafusion/"><u>[Updated] 2024 Approved Achieving Muted Audibility with Effortless Fading in Lumafusion</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-enhancing-video-longeayer-androidmac-app-utilization/"><u>[Updated] Enhancing Video Longeayer Android/Mac App Utilization</u></a></li>
<li><a href="https://apple-account.techidaily.com/3-ways-of-how-to-get-someones-apple-id-off-iphone-6-without-password-by-drfone-ios/"><u>3 Ways of How to Get Someones Apple ID Off iPhone 6 without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-fixed-windows-character-mapping-glitches/"><u>Guiding You Through Fixed Windows Character Mapping Glitches</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-much-do-you-earn-when-a-million-watch-youtube-in-2024/"><u>How Much Do You Earn When a Million Watch Youtube, In 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-oppo-find-x7-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Oppo Find X7 to PC? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-best-practices-for-exporting-audacity-sessions-as-mp3-files/"><u>New Best Practices for Exporting Audacity Sessions as MP3 Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-stubborn-windows-previous-credentials-error/"><u>Overcoming Stubborn Windows Previous Credentials Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-trick-to-elevate-your-account-type/"><u>Quick Trick to Elevate Your Account Type</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-3d-art-process-with-indispensable-keyboard-shortcuts/"><u>Streamline Your 3D Art Process with Indispensable Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-cmd-connoisseurs-guide-to-five-fun-hacks/"><u>The Cmd Connoisseur's Guide to Five Fun Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-screen-separation-problems/"><u>Unblocking Screen Separation Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-visual-display-ideal-5-apps-for-personalized-time-themed-windows-screensavers/"><u>Upgrade Your Visual Display: Ideal 5 Apps for Personalized Time-Themed Windows Screensavers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/your-pathway-to-mastery-in-youtube-vids-on-twitter/"><u>Your Pathway to Mastery in YouTube Vids on Twitter</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

