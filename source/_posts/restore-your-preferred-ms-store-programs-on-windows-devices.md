---
title: Restore Your Preferred MS Store Programs on Windows Devices
date: 2024-09-15T02:44:19.378Z
updated: 2024-09-22T02:28:55.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restore Your Preferred MS Store Programs on Windows Devices
excerpt: This Article Describes Restore Your Preferred MS Store Programs on Windows Devices
keywords: MS Store Restoration,Reset Windows Settings,Recover Applications,Fix Device OS,Remove Unwanted Programs,Regain Default Software,Streamline Windows Experience
thumbnail: https://thmb.techidaily.com/1925602951b4d52698ec670857ef818988d6fc983d6278e2dead21b251870b2b.jpg
---

## Restore Your Preferred MS Store Programs on Windows Devices

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
<li><a href="https://win11-tips.techidaily.com/2023windows-movie-maker11/"><u>2023年最好的免费Windows Movie Maker替代品：探索11种功能丰富的视频编辑工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp2mp3-movavi/"><u>優化MP2為MP3的無限制線上移動 - 運用Movavi 解決方案</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/crafting-authentic-asian-mini-homes-in-mc/"><u>Crafting Authentic Asian Mini-Homes in MC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effektivt-bearbetar-audiofilmer-ivan-med-movavi-din-gamla-ljudbittarrat-ratt-utanfor-tiden/"><u>Effektivt Bearbetar Audiofilmer - Ivån Med Movavi: Din Gamla Ljudbittarrat Rätt Utanför Tiden</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exploring-the-vivid-world-with-curved-images-for-2024/"><u>Exploring the Vivid World with Curved Images for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/gadgets-and-gear-insights-by-toms-hardware-review/"><u>Gadgets & Gear Insights by Tom's Hardware Review</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-zte-nubia-z60-ultra-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from ZTE Nubia Z60 Ultra Devices</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-perform-a-gentle-reboot-on-your-iphone-a-step-by-step-tutorial/"><u>How to Perform a Gentle Reboot on Your iPhone - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mov-mxf-movavi-0/"><u>MOV 파일을 MXF로 이식: MOVavi에서 비용 0%의 온라인 제공</u></a></li>
<li><a href="https://vp-tips.techidaily.com/one-month-apple-vision-pro-assessment-unveiling-the-answers-to-key-queries/"><u>One-Month Apple Vision Pro Assessment: Unveiling the Answers to Key Queries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-bmp-to-png-conversion-by-movavi-get-it-free/"><u>Online BMP to PNG Conversion by Movavi: Get It FREE!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043603/7443" target="_top" id="2043603">
  <img src="//a.impactradius-go.com/display-ad/7443-2043603" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043603/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

