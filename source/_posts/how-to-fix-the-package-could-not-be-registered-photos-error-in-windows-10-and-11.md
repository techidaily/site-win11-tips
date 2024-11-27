---
title: How to Fix the “Package Could Not Be Registered” Photos Error in Windows 10 & 11
date: 2024-11-26T16:16:15.036Z
updated: 2024-11-27T16:23:51.219Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “Package Could Not Be Registered” Photos Error in Windows 10 & 11
excerpt: This Article Describes How to Fix the “Package Could Not Be Registered” Photos Error in Windows 10 & 11
keywords: Windows Package Registration FIX,Photo Error Solution,Win10 11 Fix Issue,Registering Photo Problem,Solve Photography Errors,Windows Update Error,Package Registration Troubleshoot,Fix Win Photo Error,Package Registration Guide,10 & 11 Update Troubleshoot,Register Windows Photos,Photo Error Remediation,Solve Windows Updates,Photography Package Fix
thumbnail: https://thmb.techidaily.com/b1dd0483f32a09412f335f94508f9f7301d5aa196fe907bac96fdd29e9d8162d.png
---

## How to Fix the “Package Could Not Be Registered” Photos Error in Windows 10 & 11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-tweeting-visuals-integrating-youtube-and-snapchat/"><u>[New] In 2024, Tweeting Visuals Integrating YouTube and Snapchat</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-pivot-and-post-mastering-video-orientation/"><u>[Updated] Pivot and Post Mastering Video Orientation</u></a></li>
<li><a href="https://driver-download.techidaily.com/ensure-your-canon-pixma-mg2522-runs-smoothly-with-updated-drivers/"><u>Ensure Your Canon PIXMA MG2522 Runs Smoothly with Updated Drivers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/filmeditingsuite-assessment-detailed-insights-for-2024/"><u>FilmEditingSuite Assessment – Detailed Insights for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/fixing-intel-hd-graphics-630-driver-problems-on-windows-a-comprehensive-solution/"><u>Fixing Intel HD Graphics 630 Driver Problems on Windows: A Comprehensive Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-pc-folders-exposed-in-windows-11/"><u>Hidden Pc Folders Exposed in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-connect-your-airpods-to-windows/"><u>How to Effortlessly Connect Your AirPods to Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-5-from-vivo-y100t-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 5 from Vivo Y100t to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-comic-reading-a-guide-to-win11-mastery/"><u>Optimizing Comic Reading: A Guide to Win11 Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personal-touches-changing-windows-screenshot-settings/"><u>Personal Touches: Changing Windows Screenshot Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-old-bios-color-schemes/"><u>Reinvigorating Old BIOS Color Schemes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-windows-operatic-install-with-easy-fixes/"><u>Revive Your Windows Operatic Install with Easy Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-run-cmd-with-administrator-rights/"><u>Strategies to Run CMD with Administrator Rights</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-journey-through-a-decade-with-mondly/"><u>The Journey Through a Decade with Mondly</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/unlock-the-secrets-of-stellar-snaps-and-snapchat-boomers-for-2024/"><u>Unlock the Secrets of Stellar Snaps and Snapchat Boomers for 2024</u></a></li>
</ul></div>

