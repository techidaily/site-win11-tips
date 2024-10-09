---
title: Renewal of Pre-Installed Software with Microsoft Store
date: 2024-10-07T04:00:00.133Z
updated: 2024-10-08T23:15:46.314Z
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
<a href="https://appsumo.8odi.net/c/5597632/2144287/7443" target="_top" id="2144287">
  <img src="//a.impactradius-go.com/display-ad/7443-2144287" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144287/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-maximize-zoom-audio-clarity-methods-and-tips-shared-for-2024/"><u>[New] Maximize Zoom Audio Clarity Methods & Tips Shared for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-the-watchers-whispers-essential-websites-for-got-sound-files/"><u>[Updated] 2024 Approved The Watchers' Whispers Essential Websites for GoT Sound Files</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-peeling-away-at-sharex-comparative-views-and-substitutes/"><u>[Updated] Peeling Away at ShareX Comparative Views & Substitutes</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-git-proficiency-with-github-desktop-on-windows-11/"><u>Boost Your Git Proficiency with Github Desktop on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-spotlight-screenshot-preferences-efficiently-in-windows/"><u>Configure Spotlight Screenshot Preferences Efficiently in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-stealth-network-safeguarding-in-windows-settings/"><u>Crafting Stealth Network Safeguarding in Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pcs-appeal-animated-backgrounds-in-windows-11/"><u>Elevate Your PC's Appeal: Animated Backgrounds in Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-logitech-g35-headset-drivers-updated-version-supporting-windows-7810/"><u>Free Logitech G35 Headset Drivers - Updated Version Supporting Windows 7/8/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-save-location-errors-in-windows-pcs/"><u>How to Correct Save Location Errors in Windows PCs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-stabilizing-your-gopro-footage-a-step-by-step-guide/"><u>In 2024, Stabilizing Your GoPro Footage A Step-by-Step Guide</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-alienware-aurora-r7-exceptional-power-meets-its-price-tag/"><u>In-Depth Analysis of Alienware Aurora R7: Exceptional Power Meets Its Price Tag</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unable-to-link-error-guide-for-nvidia-experience-on-windows-11/"><u>Overcoming Unable to Link Error: Guide for Nvidia Experience on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-non-responsive-key-to-control-display-brightness-on-windows-11/"><u>Unblocking Non-Responsive Key to Control Display Brightness on Windows 11</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-samsung-galaxy-xcover-7-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on Samsung Galaxy XCover 7 ?</u></a></li>
</ul></div>

