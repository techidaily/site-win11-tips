---
title: How to Unblock and Redo App Registrations (Windows 11)
date: 2024-10-20T02:10:10.876Z
updated: 2024-10-20T16:50:07.500Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unblock and Redo App Registrations (Windows 11)
excerpt: This Article Describes How to Unblock and Redo App Registrations (Windows 11)
keywords: Windows Unblocking Guide,Windows 11 Login Fixes,Reset Registration Steps,Clear Browser Blocks,App Sign-Up Redo Tips,Unblock Windows Settings,Re-Register Apps Windows 11
thumbnail: https://thmb.techidaily.com/b1aabf9182a40f39eacfea832a56e2883c1058666aaa24cc7d5f400170f744e3.jpeg
---

## How to Unblock and Redo App Registrations (Windows 11)

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
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134496/18498" target="_top" id="2134496">
  <img src="//a.impactradius-go.com/display-ad/18498-2134496" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134496/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-cloud.techidaily.com/new-the-riders-eye-view-unveiling-23s-finest-action-camera-hats-for-bike-enthusiasts-for-2024/"><u>[New] The Rider's Eye View – Unveiling '23’S Finest Action Camera Hats for Bike Enthusiasts for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-radio-dramas-peak-of-creative-scripting/"><u>[Updated] Radio Dramas Peak of Creative Scripting</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-samsung-galaxy-z-fold-5-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Samsung Galaxy Z Fold 5 Pattern Lock Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-windows-update-error-0x800736cc/"><u>How to Fix Windows Update Error 0X800736cc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-different-wallpapers-for-each-monitor-in-windows-10-and-11/"><u>How to Use Different Wallpapers for Each Monitor in Windows 10 and 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mastering-youtube-tvs-features-a-beginners-guide-for-2024/"><u>Mastering YouTube TV's Features A Beginner's Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-task-monitor-update-velocity-on-windows-11/"><u>Maximize Task Monitor Update Velocity on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-dxgierrordevice-in-win-11-and-11/"><u>Overcoming DXGI_ERROR_DEVICE in Win 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-defenders-protection-to-use-other-avs/"><u>Overcoming Windows Defender's Protection to Use Other AVs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-repairing-ms-store-crash-error-0x0-on-win-1011/"><u>Quick Guide to Repairing MS Store Crash (Error 0X0) on Win 10/11</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-motorola-g54-5g-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Motorola G54 5G</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-reduce-video-size-online-10-best-free-compression-tools/"><u>Updated Reduce Video Size Online 10 Best Free Compression Tools</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/what-are-the-real-benefits-of-jailbreaking-gpt/"><u>What Are the Real Benefits of Jailbreaking GPT?</u></a></li>
</ul></div>

