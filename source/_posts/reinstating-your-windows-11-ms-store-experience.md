---
title: Reinstating Your Windows 11 MS Store Experience
date: 2024-06-25T16:45:45.386Z
updated: 2024-06-26T16:45:45.386Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Your Windows 11 MS Store Experience
excerpt: This Article Describes Reinstating Your Windows 11 MS Store Experience
keywords: Win11StoreRestore,MSStoreRedo,ReinstallMSStore,ReviveWinStore,FixWinMSStore,ResetWindowsStore,StoreWin11Fix
thumbnail: https://thmb.techidaily.com/05a2bebe19d9c7fab4bc3ec91fa821946b0580297afafdcde864123fe0ad252d.jpg
---

## Reinstating Your Windows 11 MS Store Experience

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users ![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users ![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

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
<li><a href="https://win11-tips.techidaily.com/upgrade-playnite-with-emulated-game-support/"><u>Upgrade Playnite with Emulated Game Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719311785872-fix-crashing-file-explorer-on-windows-11-now/"><u>Fix Crashing File Explorer on Windows 11 Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-file-operations-in-powershell-and-command-prompt/"><u>Optimizing File Operations in PowerShell & Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-discord-install-problems-on-windows-11/"><u>Bypassing Discord Install Problems on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-game-capture-denial-due-to-low-specs/"><u>Fixing Windows Game Capture Denial Due to Low Specs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-portable-executable-an-overview/"><u>Windows' Portable Executable: An Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-privacy-activating-controlled-folder-access-in-windows-11/"><u>Mastering Privacy: Activating Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-check-your-windows-computers-model-name/"><u>6 Ways to Check Your Windows Computer's Model Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-chromes-system-time-a-fix-guide-windows/"><u>Realigning Chrome's System Time: A Fix Guide (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-deep-into-identity-unveiling-sids-in-windows-11/"><u>Diving Deep Into Identity: Unveiling SIDs in Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/most-acclaimed-ipad-recording-software-3p-for-2024/"><u>Most Acclaimed iPad Recording Software 3P for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-achieving-excellence-in-work-and-online-content/"><u>In 2024, Achieving Excellence in Work and Online Content</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-free-dvd-player-roundup-top-picks-for-windows-10/"><u>New Free DVD Player Roundup Top Picks for Windows 10</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-beat-design-mastery-tailoring-soundtracks-to-captivate-your-music-videos/"><u>In 2024, Beat Design Mastery Tailoring Soundtracks to Captivate Your Music Videos</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-decoding-video-thread-embellishments-for-2024/"><u>[Updated] Decoding Video Thread Embellishments for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-capturing-live-streams-on-fb-top-techniques-revealed/"><u>[New] In 2024, Capturing Live Streams on FB  Top Techniques Revealed</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-huawei-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Huawei</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-samsung-galaxy-a24-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Samsung Galaxy A24 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-optimized-obs-options-for-low-end-systems-for-2024/"><u>[Updated] Optimized OBS Options for Low-End Systems for 2024</u></a></li>
</ul></div>
