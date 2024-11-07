---
title: Win OS 10/11 – How to Correct Non-Registered Photo Packages
date: 2024-11-05T00:59:39.187Z
updated: 2024-11-07T02:14:16.824Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Win OS 10/11 – How to Correct Non-Registered Photo Packages
excerpt: This Article Describes Win OS 10/11 – How to Correct Non-Registered Photo Packages
keywords: Win OS Fix Photos,Unregister Windows Photo,Windows Photo Registration,Register Windows Pics,OS X Photo Compatibility,Mac OS Picture Upload,Correcting OS Photo Issues
thumbnail: https://thmb.techidaily.com/e7c07b94a0d6b31286cb181ffa8593e2e10d0215534d64f40b8e2e1bab83a4ee.jpg
---

## Win OS 10/11 – How to Correct Non-Registered Photo Packages

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

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
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

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
<li><a href="https://desktop-recording.techidaily.com/new-the-ultimate-zoom-communication-guide-unlocking-the-power-of-remote-conversations-for-2024/"><u>[New] The Ultimate Zoom Communication Guide Unlocking the Power of Remote Conversations for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ling-challenge-brainstroming-7-humorous-youtube-videos/"><u>Chuckling Challenge Brainstroming 7 Humorous YouTube Videos</u></a></li>
<li><a href="https://techtrends.techidaily.com/1725288959075-dvd/"><u>DVDデクリプターにおける日本語パッチでの文字化け原因・修正手順</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-pathway-to-boot-your-pc-with-intel-network-hardware/"><u>Easy Pathway to Boot Your PC with Intel Network Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-pc-info-retrieval-with-everythingapp/"><u>Fast PC Info Retrieval with EverythingApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-broken-internet-links-an-in-depth-examination-of-solutions-for-win-pc-network-issues/"><u>Fix Broken Internet Links: An In-Depth Examination of Solutions for Win PC Network Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-to-tackle-windows-loading-library-error-87paramerr/"><u>Guidance to Tackle Windows Loading Library Error 87:ParamErr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-maintaining-a-fixed-win-printer/"><u>Guidelines for Maintaining a Fixed Win Printer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-loaderror-87-on-windows-libraries-misalignment/"><u>Handling LoadError 87 on Windows Libraries Misalignment</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-chic-crests-curating-the-best-websites-for-aesthetic-laptop-backgrounds/"><u>In 2024, Chic Crests Curating the Best Websites for Aesthetic Laptop Backgrounds</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-ideal-cutting-edge-apps-top-10-for-editing-youtube-shorts/"><u>In 2024, Ideal Cutting Edge Apps Top 10 for Editing Youtube Shorts</u></a></li>
<li><a href="https://win-cloud.techidaily.com/introduccion-al-software-black-mith-optimiza-el-mantenimiento-de-tu-informacion-con-funciones-de-archivado-proteccion-y-respaldo/"><u>Introducción Al Software Black Mith: Optimiza El Mantenimiento De Tu Información Con Funciones De Archivado, Protección Y Respaldo</u></a></li>
<li><a href="https://tech-revival.techidaily.com/no-number-necessary-signing-up-for-chatgpt-telegram-whatsapp-with-alternative-methods/"><u>No-Number Necessary: Signing Up for ChatGPT, Telegram, WhatsApp with Alternative Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-your-steam-game-victories/"><u>Refreshing Your Steam Game Victories</u></a></li>
<li><a href="https://program-issues.techidaily.com/the-ultimate-solution-why-is-call-of-duty-warzone-still-crashing-tips-and-tricks-to-fix-it-now/"><u>The Ultimate Solution: Why Is Call of Duty Warzone Still Crashing ? Tips & Tricks to Fix It Now!</u></a></li>
<li><a href="https://facebook.techidaily.com/top-4-metrics-and-tools-for-thriving-businesses/"><u>Top 4 Metrics & Tools for Thriving Businesses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-synchronizing-sticky-notes-on-w11/"><u>Troubleshooting Non-Synchronizing Sticky Notes on W11</u></a></li>
</ul></div>

