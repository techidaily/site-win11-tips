---
title: Enhancing the User Experience with Drive Views
date: 2024-08-16T02:47:41.201Z
updated: 2024-08-17T02:47:41.201Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing the User Experience with Drive Views
excerpt: This Article Describes Enhancing the User Experience with Drive Views
keywords: Drive Enhancement,User Experience UI,Interactive Drives,Improved Viewing,Navigation Insights,Accessible Drives,Visualize Vehicles
thumbnail: https://thmb.techidaily.com/a6cda5d3da29aa302f42489d12b2f7ee98a977d6c686fb1e190a7cb786bdcbab.jpg
---

## Enhancing the User Experience with Drive Views

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/updated-chuckles-in-a-minute-how-to-whip-up-memes/"><u>[Updated] Chuckles in a Minute  How to Whip Up Memes</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-imagemagick-studio-walkthrough/"><u>[Updated] ImageMagick Studio Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/12-superfluous-windows-tools-you-can-live-without/"><u>12 Superfluous Windows Tools You Can Live Without</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-change-boot-menu-timeout-in-windows-11/"><u>4 Ways to Change Boot Menu Timeout in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-crucial-modifications-to-revolutionize-the-windows-11-taskbar/"><u>6 Crucial Modifications to Revolutionize the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-resetting-your-windows-screen-backlight/"><u>7 Strategies for Resetting Your Windows Screen Backlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-century-of-change-the-windows-taskbar/"><u>A Century of Change: The Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-walkthrough-upgrading-surface-hardware/"><u>A Comprehensive Walkthrough: Upgrading Surface Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-restoring-essential-features-of-photo-viewer-on-win11/"><u>A Quick Guide to Restoring Essential Features of Photo Viewer on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-seamless-shift-from-windows-11s-default-pin-logon-to-traditional-password-method/"><u>A Seamless Shift From Windows 11'S Default PIN Logon to Traditional Password Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-cease-chromes-unintended-tabs/"><u>A Step-By-Step Guide to Cease Chrome's Unintended Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-to-customize-your-laptops-touchpads/"><u>A Step-by-Step to Customize Your Laptop's Touchpads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-and-annotate-comics-easily-on-win11/"><u>Access and Annotate Comics Easily on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-an-innovative-auto-refresh-check-option-to-the-windows-ui/"><u>Adding an Innovative Auto-Refresh Check Option to the Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-efficiency-program-troubleshooting-tool-inclusion/"><u>Adding Efficiency: Program Troubleshooting Tool Inclusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrive-errors-in-windows-1011-system/"><u>Addressing OneDrive Errors in Windows 10/11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-screen-projection-not-working-window-glitch/"><u>Addressing Screen Projection Not Working Window Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-missing-rockalldlldll-problem/"><u>Addressing the 'Missing Rockalldll.dll' Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-system-blocked-issue-on-your-windows-machine/"><u>Addressing the System Blocked Issue on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-windows-11s-next-chapter/"><u>AI Integration: Windows 11'S Next Chapter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-fn-key-behavior-for-efficiency/"><u>Altering Windows Fn Key Behavior for Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-wallpaper-a-fresh-look-every-day/"><u>Altering Windows Wallpaper: A Fresh Look Every Day</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-efficiency-embrace-adaptive-tiling/"><u>Amplify Windows Efficiency: Embrace Adaptive Tiling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-and-ranking-video-codecs-for-windows-pcs/"><u>Analyzing and Ranking Video Codecs for Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-webcam-integration-on-windows-11-pcs/"><u>Android Webcam Integration on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-security-incorporating-advanced-firewalls-in-the-context-menu/"><u>Augment Windows Security: Incorporating Advanced Firewalls in the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-data-loss-make-windows-data-a-daily-ritual/"><u>Avoid Data Loss: Make Windows Data a Daily Ritual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-crashes-on-windows-11-10/"><u>Avoiding Teamsters Crashes on Windows 11, 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bar-of-time-the-windows-taskbars-journey/"><u>Bar of Time: The Windows Taskbar's Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-default-shrinking-in-winos/"><u>Beating the Default Shrinking in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-tools-for-win-soft-installation-chocolatey-or-wm/"><u>Best Tools for Win Soft Installation: Chocolatey or WM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitguard-compromised-continue-now-not-tomorrow/"><u>BitGuard Compromised: Continue Now, Not Tomorrow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-counter-strike-performance-a-frame-rate-guide/"><u>Boosting Counter-Strike Performance: A Frame Rate Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-functionality-with-windows-11s-taskbar/"><u>Boosting Functionality with Windows 11'S Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-of-windows-for-swift-steam-uploads/"><u>Boosting Performance of Windows for Swift Steam Uploads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-the-effectiveness-of-your-pointer-on-win11s-system/"><u>Boosting the Effectiveness of Your Pointer on Win11's System</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-guide-to-the-budget-friendly-tp-link-archer-c50-performance-reviewed/"><u>Comprehensive Guide to the Budget-Friendly TP-Link Archer C50: Performance Reviewed</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/dont-miss-out-4-official-ways-to-get-discounted-filmora-plans-for-2024/"><u>Dont Miss Out! 4 Official Ways to Get Discounted Filmora Plans for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/elevate-your-valorant-experience-by-eliminating-lag-and-increasing-frames-per-second-fps/"><u>Elevate Your Valorant Experience by Eliminating Lag & Increasing Frames Per Second (FPS)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268063873-ensuring-complete-screen-images-with-snip-and-sketch-tips/"><u>Ensuring Complete Screen Images with Snip & Sketch Tips</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-xs-max-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone XS Max Data From iTunes? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-sync-contacts-from-apple-iphone-8-plus-to-ipad-easily-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Sync Contacts from Apple iPhone 8 Plus to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/innovating-education-with-virtual-immersion/"><u>Innovating Education with Virtual Immersion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719377868664-is-prtscr-a-gateway-to-windows-11s-snipping-tool-no/"><u>Is PrtScr a Gateway to Windows 11'S Snipping Tool? No!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719353749292-navigate-compatibility-hurdles-with-easy-to-follow-steps/"><u>Navigate Compatibility Hurdles with Easy-to-Follow Steps.</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/snagting-smiles-on-iphones-and-androids-from-twitters-timeline/"><u>Snagting Smiles on iPhones & Androids From Twitter's Timeline</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719239834039-start-menu-no-more-unwanted-advertisements/"><u>Start Menu, No More Unwanted Advertisements</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-sports-cameras-for-high-pace-activities/"><u>Top Sports Cameras for High Pace Activities</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>