---
title: Swiftly Reactivate Lost Store Apps on Windows 11
date: 2024-09-11T04:12:05.246Z
updated: 2024-09-17T02:47:30.527Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swiftly Reactivate Lost Store Apps on Windows 11
excerpt: This Article Describes Swiftly Reactivate Lost Store Apps on Windows 11
keywords: Swift App Reactivation Windows,Reinstate Lost Windows Store,Quick Windows App Fixing,Windows 11 App Restore,Reactivating Lost Apps W11,Fast Restart Store Software,Windows 11 App Revival
thumbnail: https://thmb.techidaily.com/6ed52b8d826a5b6701c9229d81239cb21a1a6ea95480871656b8b252c90f9890.jpeg
---

## Swiftly Reactivate Lost Store Apps on Windows 11

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

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-protect-your-privacy-top-webcam-shields-ranked/"><u>[New] In 2024, Protect Your Privacy - Top Webcam Shields Ranked</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-steps-to-restore-obs-fullscreen-for-2024/"><u>[Updated] Steps to Restore OBS Fullscreen for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-tactics-to-minimize-edge-processes/"><u>Effective Tactics to Minimize Edge Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-windows-11-tpm-removal-techniques-explored/"><u>Effortless Windows 11 TPM Removal Techniques Explored</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723009221237-fixing-valheim-performance-problems-no-more-frame-drops-or-freezes/"><u>Fixing Valheim Performance Problems - No More Frame Drops or Freezes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-tips-for-setting-windows-time-locally/"><u>Instant Tips for Setting Windows Time Locally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-windows-11-temporary-files-reliable-and-valid/"><u>Keeping Your Windows 11 Temporary Files Reliable & Valid</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-the-art-of-fixing-pc-instability-during-starfield-gameplay-an-expert-guide/"><u>Master the Art of Fixing PC Instability During Starfield Gameplay: An Expert Guide</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-elevate-your-brand-20-professional-adobe-premiere-title-templates-free-to-download-for-2024/"><u>New Elevate Your Brand 20 Professional Adobe Premiere Title Templates Free to Download for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quell-windows-audio-intensity-protocols/"><u>Quell Windows' Audio Intensity Protocols</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-photos-during-transfer-from-iphone-11-pro-max-to-pc-or-mac-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Recover Lost Photos during Transfer from iPhone 11 Pro Max to PC or Mac | Stellar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-the-chrome-plugin-failed-to-load-issue-in-windows-10/"><u>Resolved: Fixing the 'Chrome Plugin Failed to Load' Issue in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-google-chrome-from-a-black-screen-nightmare-with-these-simple-fixes/"><u>Revive Your Google Chrome From a Black Screen Nightmare with These Simple Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-vscode-on-windows-11-systems/"><u>Stabilizing VSCode on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-windows-11-themes-you-may-have-overlooked/"><u>The Best Windows 11 Themes You May Have Overlooked</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unraveling-why-imovie-alters-video-borders-for-2024/"><u>Unraveling Why iMovie Alters Video Borders for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115950/19272" target="_top" id="2115950">
  <img src="//a.impactradius-go.com/display-ad/19272-2115950" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115950/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

