---
title: "Troubleshooting Windows 11: Resolving Package Registration Errors in Images"
date: 2024-10-24T21:13:11.307Z
updated: 2024-10-26T23:15:15.630Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Windows 11: Resolving Package Registration Errors in Images"
excerpt: "This Article Describes Troubleshooting Windows 11: Resolving Package Registration Errors in Images"
keywords: Win11 Fix PackReg Err,Win11 ImageError Solve,RegError WindowsImage Fix,PackErrWin11 Resolution,ImagePackage Registration,WindowsImg Fix Guide,Package Error in Win11 Img
thumbnail: https://thmb.techidaily.com/c774dca3ab72d0dd337e416f6694c83a3258e570406ced6f2d33110479fdae4a.jpg
---

## Troubleshooting Windows 11: Resolving Package Registration Errors in Images

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047361/19272" target="_top" id="2047361">
  <img src="//a.impactradius-go.com/display-ad/19272-2047361" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to[opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885999/19272" target="_top" id="1885999">
  <img src="//a.impactradius-go.com/display-ad/19272-1885999" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885999/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148643/16836" target="_top" id="2148643">
  <img src="//a.impactradius-go.com/display-ad/16836-2148643" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148643/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://youtube-tips.techidaily.com/phoneandroid-autoplay-continuous-youtube-access/"><u>[New] IPhone/Android AutoPlay Continuous YouTube Access</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-exploring-object-oriented-programming-for-complex-applications/"><u>[Updated] 2024 Approved Exploring Object-Oriented Programming for Complex Applications</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-apex-craftsman-studio-evaluation/"><u>[Updated] Apex Craftsman Studio Evaluation</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/s-youtube-tracks-without-spending-a-dime-25plus-no-cost-audio-extractors/"><u>Access YouTube Tracks Without Spending a Dime 25+ No-Cost Audio Extractors</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/asus-releases-intel-baseline-update-resolves-stability-issues-for-gamers-on-raptor-lakerefresh-processors/"><u>Asus Releases Intel Baseline Update: Resolves Stability Issues for Gamers on Raptor Lake/Refresh Processors</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-of-both-worlds-exclusive-11-bridge-camera-guide/"><u>Best of Both Worlds Exclusive 11 Bridge Camera Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-broken-exe-file-execution-on-pcs/"><u>Fix Broken Exe File Execution on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-mechanism-for-windows-error-x80780119-images/"><u>Fix Mechanism for Windows Error X80780119 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-printer-error-0x8000ffff-in-windows/"><u>How to Fix the Printer Error 0X8000ffff in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-realme-c53-drfone-by-drfone-virtual-android/"><u>In 2024, Apply These Techniques to Improve How to Detect Fake GPS Location On Realme C53 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-audiophiles-ultimate-narrative-guides/"><u>In 2024, Audiophile's Ultimate Narrative Guides</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-vivo-v29-pro-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Vivo V29 Pro to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-disconnection-in-windows-11/"><u>Mastering User Disconnection in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-powershell-for-windows-account-management/"><u>Navigating PowerShell for Windows Account Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shush-windows-11-explore-tabs-step-by-step/"><u>Shush Windows 11 Explore Tabs: Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-dex-power-bridge-galaxy-and-windows-effortlessly/"><u>Unleashing DeX Power: Bridge Galaxy & Windows Effortlessly</u></a></li>
</ul></div>

