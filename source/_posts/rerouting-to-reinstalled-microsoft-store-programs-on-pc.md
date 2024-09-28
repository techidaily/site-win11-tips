---
title: Rerouting to Reinstalled Microsoft Store Programs on PC
date: 2024-09-27T17:54:06.493Z
updated: 2024-09-28T17:33:43.868Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rerouting to Reinstalled Microsoft Store Programs on PC
excerpt: This Article Describes Rerouting to Reinstalled Microsoft Store Programs on PC
keywords: Store Redirection,MS Store Update,Reinstall Microsoft Apps,Pc Software Relaunch,System Restore for MS Store,Retry Microsoft Installation,PC Store Refresh
thumbnail: https://thmb.techidaily.com/db39cf974b891a971b269fa1b5c545ac5598c4412d012bd826ff7f5dff9de440.png
---

## Rerouting to Reinstalled Microsoft Store Programs on PC

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
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148645/16836" target="_top" id="2148645">
  <img src="//a.impactradius-go.com/display-ad/16836-2148645" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148645/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037355/7443" target="_top" id="2037355">
  <img src="//a.impactradius-go.com/display-ad/7443-2037355" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037355/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-illuminating-photography-with-dynamic-mosaic-creations/"><u>[Updated] In 2024, Illuminating Photography with Dynamic Mosaic Creations</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-understanding-youtube-shorts-earning-potential/"><u>[Updated] Understanding YouTube Shorts Earning Potential</u></a></li>
<li><a href="https://fox-that.techidaily.com/7-effective-tips-to-correctly-focus-and-sharpen-images-on-your-iphones-camera/"><u>7 Effective Tips to Correctly Focus & Sharpen Images on Your iPhone's Camera</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-persistent-problem-how-to-overcome-windows-update-error-code-0x8007001f/"><u>Fixing the Persistent Problem: How to Overcome Windows Update Error Code 0X8007001f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-the-forgotten-windows-start-menu/"><u>How to Reactivate the Forgotten Windows Start Menu</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-xiaomi-redmi-note-13-pro-5g-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Xiaomi Redmi Note 13 Pro 5G Phone FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-the-pulse-of-internet-stability-at-work/"><u>Keeping the Pulse of Internet Stability at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-the-way-in-qr-decoding-with-your-windows-machine/"><u>Leading the Way in QR Decoding with Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-the-power-of-combined-android-and-windows-11-displays/"><u>Leveraging the Power of Combined Android & Windows 11 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-transparent-taskbars-on-win11/"><u>Mastering the Art of Transparent Taskbars on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-for-microsoft-store-crash-code-error-0x80072efd/"><u>Swift Fixes for Microsoft Store Crash Code Error 0X80072EFD</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-instagram-editors-companion-for-effective-video-cropping-for-2024/"><u>The Instagram Editor's Companion for Effective Video Cropping for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-guide-repairing-your-non-responsive-audio-receiver/"><u>Troubleshooting Guide: Repairing Your Non-Responsive Audio Receiver</u></a></li>
</ul></div>

