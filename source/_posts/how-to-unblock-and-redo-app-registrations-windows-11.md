---
title: How to Unblock and Redo App Registrations (Windows 11)
date: 2024-10-24T18:21:21.048Z
updated: 2024-10-26T23:15:00.690Z
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
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471">
  <img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024s-a-list-top-rated-business-simulators-reviewed/"><u>[Updated] 2024’S A-List Top Rated Business Simulators Reviewed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-transform-your-note-habits-with-mematics-tools/"><u>[Updated] Transform Your Note Habits with Mematic's Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-android-sky-docs-ranking/"><u>2024 Approved Ultimate Android Sky Docs Ranking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-7-red-flags-in-system-windows-operations/"><u>Identifying 7 Red Flags in System Windows Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-for-nonresponsive-itunes-on-windows-desktop/"><u>Immediate Fixes for Nonresponsive iTunes on Windows Desktop</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-21plus-novel-collage-formulas-amplify-your-mood/"><u>In 2024, 21+ Novel Collage Formulas Amplify Your Mood</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-stepwise-manual-harnessing-googles-automatic-conversion-service/"><u>In 2024, Stepwise Manual Harnessing Google's Automatic Conversion Service</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-lighten-the-load-best-free-video-compression-software-for-windows-10/"><u>New In 2024, Lighten the Load Best Free Video Compression Software for Windows 10</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/portable-powerhouse-or-overpriced-gadget-meet-the-steam-deck/"><u>Portable Powerhouse or Overpriced Gadget? Meet the Steam Deck</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-dxgierrordevicehunk-in-win1011-devices/"><u>Resolving DXGI_ERROR_DEVICE_HUNK in Win10/11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-potential-append-folders-to-taskbar-menu/"><u>Unlock Windows Potential: Append Folders to Taskbar Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-keystrokes-fix-windows-keys-glitch/"><u>Unlocking Keystrokes: Fix Windows Keys Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-error-codes-and-solutions-for-failed-installs-in-microsoft-store/"><u>Unveiling Error Codes and Solutions for Failed Installs in Microsoft Store</u></a></li>
</ul></div>

