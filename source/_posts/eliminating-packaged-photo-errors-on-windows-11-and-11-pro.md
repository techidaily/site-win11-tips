---
title: Eliminating Packaged Photo Errors on Windows 11 & 11 Pro
date: 2024-08-08T11:05:42.276Z
updated: 2024-08-09T11:05:42.276Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Packaged Photo Errors on Windows 11 & 11 Pro
excerpt: This Article Describes Eliminating Packaged Photo Errors on Windows 11 & 11 Pro
keywords: Fix Win11 Pics,Clear Image Errors,Photoshop Corrections,Error-Free Win Photos,Windows Photo Repair,Eliminate Picture Flaws,Resolve Win11 Photo Issues
thumbnail: https://thmb.techidaily.com/573a01f636332d7e5c995b169e7da5e56cb9c949cb98537f68160223a0f7de27.jpg
---

## Eliminating Packaged Photo Errors on Windows 11 & 11 Pro

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to[opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://some-knowledge.techidaily.com/updated-first-time-periscope-income-strategies-for-success/"><u>[Updated] First-Time Periscope Income  Strategies for Success</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-essential-notebooks-excellent-in-media-post-production/"><u>[Updated] In 2024, Essential Notebooks Excellent in Media Post-Production</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-mememirror-app-mirror-the-worlds-laughter/"><u>[Updated] MemeMirror App - Mirror the World's Laughter</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-seamless-tv-integration-looping-videos-from-youtube-on-large-screens/"><u>[Updated] Seamless TV Integration  Looping Videos From YouTube on Large Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-proven-strategies-to-solve-windows-update-woes/"><u>10 Proven Strategies to Solve Windows Update Woes</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-unveiling-vr-inventory-and-imagination-deficit/"><u>2024 Approved  Unveiling VR  Inventory and Imagination Deficit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-common-complaints-users-have-about-windows-11/"><u>5 Common Complaints Users Have About Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-strategies-for-optimizing-windows-11s-bar/"><u>5 Key Strategies for Optimizing Windows 11'S Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secure-windows-strategies-when-bitlocker-fails/"><u>5 Secure Windows Strategies When Bitlocker Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/50plus-innovative-ideas-to-customize-your-windows-11-layout/"><u>50+ Innovative Ideas to Customize Your Windows 11 Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-altering-lockout-frequency-in-windows-11-successor/"><u>A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-windows-iscsi-initiator/"><u>A Step-by-Step Guide to Using Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-thoroughly-detailed-guide-to-windows-boot-options/"><u>A Thoroughly Detailed Guide to Windows Boot Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-reconnecting-to-windows-shared-items/"><u>Access Denied: Reconnecting to Windows Shared Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-success-winning-strategies-for-windows/"><u>Achieve Academic Success: Winning Strategies for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lunar-client-startup-failures-on-windows-systems/"><u>Addressing “Lunar Client Startup Failures” On Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-vscode-shutdown-problems-on-windows-11/"><u>Addressing VSCode Shutdown Problems on Windows 11</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/arctic-accolades-top-athletes-and-events/"><u>Arctic Accolades  Top Athletes & Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-ux3405-review-is-this-the-macbook-of-windows/"><u>ASUS Zenbook 14 OLED (UX3405) Review: Is This the MacBook of Windows?</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-webcams-for-podcast-for-2024/"><u>Best Webcams for Podcast for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlock-cracked-staying-secure-yet-unmoved/"><u>BitLock Cracked: Staying Secure Yet Unmoved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-call-productivity-on-windows-11-with-the-intel-unison-app/"><u>Boosting Call Productivity on Windows 11 with the Intel Unison App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719244514852-enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-realme-12-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Realme 12 5G? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>How to Stop Life360 from Tracking You On Apple iPhone 7 Plus? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-15-plus-passcode-without-computer-drfone-by-drfone-ios/"><u>How to Unlock iPhone 15 Plus Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719294305886-ignite-performance-gains-in-winoutlook-today/"><u>Ignite Performance Gains in WinOutlook, Today</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-master-video-creation-understanding-the-role-of-camera-lenses-in-vlogging/"><u>In 2024, Master Video Creation  Understanding the Role of Camera Lenses in Vlogging</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-soundscapes-from-social-media-videos/"><u>In 2024, Soundscapes From Social Media Videos</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-motorola-moto-g-5g-2023-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Motorola Moto G 5G (2023) for Parents | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/leading-hubs-for-virtual-typography/"><u>Leading Hubs for Virtual Typography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367478733-overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-vivo-y100i-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266622683-rejuvenate-your-locked-shift-key-in-windows/"><u>Rejuvenate Your Locked Shift Key in Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resetting-display-settings-failures-on-windows-7-and-10-fix-complete/"><u>Resetting Display Settings Failures on Windows 7 & 10 [Fix Complete]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276426207-saving-the-day-with-win1011s-recycle-bin-corruption-fixed/"><u>Saving the Day with Win10/11's Recycle Bin Corruption Fixed</u></a></li>
</ul></div>
