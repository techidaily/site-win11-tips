---
title: Overcoming Obstacles in Package Registration on Windows 10/11
date: 2024-12-30T16:07:54.929Z
updated: 2025-01-06T07:24:21.429Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Obstacles in Package Registration on Windows 10/11
excerpt: This Article Describes Overcoming Obstacles in Package Registration on Windows 10/11
keywords: W10/11 Registration Challenges,Package Sign-Up Issues,Overcome W10 Registration,Resolve W11 Package Errors,Efficient PC Package Setup,Streamline Windows Package Verify,Tackle Obstacles in W10/11 Packaging
thumbnail: https://thmb.techidaily.com/b271e3424a506666cfc32d0840f08d97d7b8b324df271cfd9aff178b05822fa5.jpg
---

## Overcoming Obstacles in Package Registration on Windows 10/11

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

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

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to[opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/new-pivotal-principles-in-digital-story-making/"><u>[New] Pivotal Principles in Digital Story Making</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-snapshotstop-screen-shot-on-demand-guide-for-2024/"><u>[New] SnapshotStop Screen Shot on Demand Guide for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-sony-bdp-s3700-review-latest-update-summary/"><u>2024 Approved Sony BDP-S3700 Review Latest Update Summary</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-zte-axon-40-lite-frp-by-drfone-android/"><u>5 Quick Methods to Bypass ZTE Axon 40 Lite FRP</u></a></li>
<li><a href="https://fox-sys.techidaily.com/die-top-2-methoden-zum-einrichten-von-windows-11-auf-einer-neuen-ssd-schritt-fur-schritt-anleitung/"><u>Die Top-2 Methoden Zum Einrichten Von Windows 11 Auf Einer Neuen SSD: Schritt-Für-Schritt Anleitung</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/explore-kid-safe-world-mondlys-awarded-feature-set/"><u>Explore Kid-Safe World - Mondly’s Awarded Feature Set</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-15-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 15 Pro Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-level-tips-run-any-application-as-admin-permanently-on-windows-n-11/"><u>Master Level Tips: Run Any Application as Admin Permanently on Windows N 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-past-the-barrier-fixing-windows-updates-0x800736cc/"><u>Navigate Past the Barrier: Fixing Windows Update's 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-unrequested-console-emergence-on-pcs/"><u>Preventing Unrequested Console Emergence on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/staying-ahead-adding-passwords-to-your-win-texts-proactively/"><u>Staying Ahead: Adding Passwords to Your Win Texts Proactively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-up-your-file-organization-game-windows-11-and-11-style/"><u>Step Up Your File Organization Game - Windows 11 & 11 Style</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-guide-securely-moving-images-from-pc-to-iphone-using-windows-11-or-10/"><u>Step-by-Step Guide: Securely Moving Images From PC to iPhone Using Windows 11 or 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reviving-the-inactive-wsreset-service/"><u>Strategies for Reviving the Inactive WSReset Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-mystery-of-missing-drive-letters-in-windows-systems-a-compreayers-guide-to-fixing-it/"><u>The Mystery of Missing Drive Letters in Windows Systems - A Compreayer's Guide to Fixing It</u></a></li>
</ul></div>

