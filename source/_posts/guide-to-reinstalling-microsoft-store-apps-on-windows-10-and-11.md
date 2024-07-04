---
title: Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11
date: 2024-07-03T12:38:48.144Z
updated: 2024-07-04T12:38:48.144Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11
excerpt: This Article Describes Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11
keywords: Install Microsoft Store,Store Reinstall Guide,Windows Store Apps,Reinstall Store Apps,Windows 10 Store Restore,Microsoft Store Reset,Restore Store on Windows
thumbnail: https://thmb.techidaily.com/a208b6b47f62fc53f6719bf37fb44710d3bca87f00271cab6e02272f4110e26d.jpg
---

## Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11

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
<li><a href="https://win11-tips.techidaily.com/cure-for-non-booting-windows-hiberflattening/"><u>Cure for Non-Booting Windows HiberFlattening</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-custom-keybinds-quick-paste-in-win-1011/"><u>Master Custom Keybinds: Quick Paste in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-missing-mcuicnt-file-execution-issue-on-windows/"><u>Tackling Missing McUICnt File Execution Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-11-theme-barriers-using-registry/"><u>Breaking Through Windows 11 Theme Barriers Using Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-tracking-your-apps/"><u>Stop Windows From Tracking Your Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-windows-steam-broadcaster-errors/"><u>Combatting Windows Steam Broadcaster Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cleanup-automating-deletion-of-files-in-windows/"><u>Quick Cleanup: Automating Deletion of Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-latency-strategies-to-fasten-windows-discord/"><u>Lowering Latency: Strategies to Fasten Windows Discord</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-mastering-yt-creator-hub-the-ultimate-playbook/"><u>[Updated] Mastering YT Creator Hub  The Ultimate Playbook</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-premium-best-ten-spotifys-superior-recording-tools/"><u>2024 Approved  Premium Best Ten  Spotify's Superior Recording Tools</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-best-free-video-rotation-apps-for-android-iphone-windows-and-mac/"><u>Updated 2024 Approved Best Free Video Rotation Apps for Android, iPhone, Windows, and Mac</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/principles-of-crafting-compelling-youtube-introduction-vids-for-2024/"><u>Principles of Crafting Compelling YouTube Introduction Vids for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/infographic-social-video-marketing-tips-for-small-business-for-2024/"><u>[Infographic] Social Video Marketing Tips for Small Business for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/leading-6-sites-transforming-how-companies-connect-socially/"><u>Leading 6 Sites Transforming How Companies Connect Socially</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-sony-camcorder-video-editing-tutorial-from-capture-to-completion/"><u>2024 Approved Sony Camcorder Video Editing Tutorial From Capture to Completion</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-step-by-step-capturing-powerful-presentations-in-adobe-presenter/"><u>[Updated] Step-by-Step  Capturing Powerful Presentations in Adobe Presenter</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/edu-stream-100-cutting-edge-learning-yt-for-2024/"><u>Edu-Stream 100  Cutting-Edge Learning YT for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-v-purse-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor V Purse to BlackBerry | Dr.fone</u></a></li>
</ul></div>
