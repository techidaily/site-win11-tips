---
title: Restoring Microsoft Store Functionality in Windows 11
date: 2024-07-12T16:57:50.371Z
updated: 2024-07-13T16:57:50.371Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Microsoft Store Functionality in Windows 11
excerpt: This Article Describes Restoring Microsoft Store Functionality in Windows 11
keywords: Win11 Store Fix,MS Windows Restore,Store OS Repair,Microsoft Store Enable,Win11 Store Recovery,MSCornerStore Function,Windows 11 Store Revive
thumbnail: https://thmb.techidaily.com/f68ad44dfce4596bff961c8c73128e503881dbfbd95e5f1787a78426eec3f375.jpg
---

## Restoring Microsoft Store Functionality in Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users
![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

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
<li><a href="https://ai-vdieo-software.techidaily.com/discover-the-top-audio-converters-for-your-music-library/"><u>Discover the Top Audio Converters for Your Music Library</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-xpatch-puzzle-error-0x80073712/"><u>Decoding Windows XPatch Puzzle: Error 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-distinctions-a-comparative-analysis-of-standard-login-vs-microsoft-account-on-pcs/"><u>Dissecting Distinctions: A Comparative Analysis of Standard Login vs Microsoft Account on PCs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/first-rate-biodegradable-filming-gear-tutorials-for-2024/"><u>First-Rate Biodegradable Filming Gear Tutorials for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-shop-failure-x800704cf/"><u>Deciphering Windows Shop Failure X800704CF</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-vivo-y100a-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Vivo Y100A Phones? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-access-to-your-visual-data-with-windows-11/"><u>Immediate Access to Your Visual Data with Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-beginners-handbook-to-igtv-mastery/"><u>[New] 2024 Approved  The Beginner's Handbook to IGTV Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-recycle-bin-corrupted-error-on-windows-11-and-11/"><u>How to Fix a Recycle Bin Corrupted Error on Windows 11 & 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-innovators-crafting-engaging-marvel-escapades/"><u>In 2024, Innovators Crafting Engaging Marvel Escapades</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pioneering-virtual-meetings-mastering-gmail-and-zoom-usage-together/"><u>2024 Approved  Pioneering Virtual Meetings  Mastering Gmail and Zoom Usage Together</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-local-group-policy-editor-in-windows-11/"><u>10 Ways to Open the Local Group Policy Editor in Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-snappytweet-get-your-digital-snapshots-on-iphone/"><u>2024 Approved  SnappyTweet  Get Your Digital Snapshots on iPhone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-elevate-landscape-imaging-with-your-iphone-device-for-2024/"><u>How to Elevate Landscape Imaging with Your iPhone Device for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-toggle-picture-in-picture-feature-for-youtube-app/"><u>2024 Approved  Toggle Picture-in-Picture Feature for Youtube App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-correcting-stuck-batch-files-on-windows/"><u>Comprehensively Correcting Stuck Batch Files on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-drive-space-without-spending-a-dime/"><u>Elevate Windows Drive Space Without Spending a Dime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-the-pinnacle-of-windows-interactivity/"><u>Experience the Pinnacle of Windows Interactivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-distinctions-between-windows-terminal-and-powershell/"><u>Analyzing The Distinctions Between Windows Terminal and PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ingenious-approach-to-hide-win-11s-taskbar-icon/"><u>Ingenious Approach to Hide Win 11'S Taskbar Icon</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-comprehensive-review-evolution-of-digital-entertainment/"><u>[New] Comprehensive Review  Evolution of Digital Entertainment</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-priority-tools-critical-6-fb-lite-downloads/"><u>[New] Priority Tools  Critical 6 FB Lite Downloads</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-the-ultimate-mac-video-editing-experience-avs/"><u>New 2024 Approved The Ultimate Mac Video Editing Experience AVS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-a-personalized-look-with-these-easy-to-follow-theme-steps-for-win11/"><u>Achieve a Personalized Look with These Easy-to-Follow Theme Steps for Win11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-mastering-video-placement-on-social-media-platforms/"><u>2024 Approved  Mastering Video Placement on Social Media Platforms</u></a></li>
<li><a href="https://extra-tips.techidaily.com/beyond-low-definition-the-ultimate-path-from-sdr-to-hdri-video-for-2024/"><u>Beyond Low Definition  The Ultimate Path From SDR to HDRI Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-web-speed-contrast-in-your-tech-world/"><u>Addressing the Web Speed Contrast in Your Tech World</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-from-voice-to-print-effective-speech-to-text-strategies/"><u>New 2024 Approved From Voice to Print Effective Speech-to-Text Strategies</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-realme-gt-5-pro-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Realme GT 5 Pro Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-solutions-for-dead-hubs-and-usb-connectors-win-pc/"><u>Immediate Solutions for Dead Hubs & USB Connectors Win PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-desktop-icon-spacing-in-windows-11-and-10/"><u>How to Change Desktop Icon Spacing in Windows 11 and 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-old-school-games-a-guide-to-adding-achievements-via-retroarch/"><u>Boosting Old-School Games: A Guide to Adding Achievements via Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reacquire-lost-copilot-in-ws11-journeys/"><u>How To Reacquire Lost Copilot In WS11 Journeys</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-techniques-for-stronger-video-content-with-b-clips/"><u>[Updated] Techniques for Stronger Video Content with B-Clips</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-comprehensive-logitech-4k-cam-review-for-ultimate-video-quality/"><u>[Updated] Comprehensive Logitech 4K Cam Review for Ultimate Video Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-customization-top-20-settings-for-enhanced-performance/"><u>Windows 11 Customization: Top 20 Settings for Enhanced Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-common-print-issues-related-to-domain-services-in-modern-windows-oses/"><u>How to Rectify Common Print Issues Related to Domain Services in Modern Windows OSes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-re-enable-sound-on-twitter-video-tweets/"><u>2024 Approved  Re-Enable Sound on Twitter Video Tweets</u></a></li>
</ul></div>
