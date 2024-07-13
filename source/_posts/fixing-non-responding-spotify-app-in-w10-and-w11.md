---
title: Fixing Non-Responding Spotify App in W10 & W11
date: 2024-07-12T16:53:14.761Z
updated: 2024-07-13T16:53:14.761Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Non-Responding Spotify App in W10 & W11
excerpt: This Article Describes Fixing Non-Responding Spotify App in W10 & W11
keywords: Spotify Resume Fix,Windows 10/11 App Repair,Spotify Not Responding,Spotify Troubleshooting,Win10 W11 App Issue,Stop Spotify Freeze,Unfreeze Spotify Music
thumbnail: https://thmb.techidaily.com/dd7a824e4ab8b6d6473fb0116a606a013dd12f046dfa0556ebd9b84053509fd9.png
---

## Fixing Non-Responding Spotify App in W10 & W11

 Spotify is among the foremost music-streaming apps for Windows. However, some users can’t utilize that software because of a “Spotify application is not responding” error. That error message pops up for some users when they try opening the Spotify app on Windows 10 and 11\.

 Spotify doesn’t open when the “application is not responding” error occurs. Although users can’t still utilize Spotify within a browser, that’s not quite the same as the Windows app. This is how you can fix the “Spotify application is not responding” error message on a Windows PC.

## 1\. Terminate Background Spotify Processes in Task Manager

 Ending Spotify background processes is one of the most straightforward and widely confirmed resolutions for the “application is not responding” error. This error often occurs because a Spotify process is still running in the background. So, the first thing you should do is to terminate all Spotify processes you can find in Task Manager like this:

1. Click anywhere on an empty taskbar space with your mouse’s right button to select **Task Manager**.
2. Select **Processes** if Task Manager opens with a different tab.
3. If you can see Spotify in the Apps section, right-click that process and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/end-task-option.jpg)
4. Go through the background section and disable any Spotify processes you see there by selecting **End task**.
5. Exit the Task Manager tool.
6. Then right-click a Spotify desktop or Start menu shortcut and select **Run as administrator**.

## 2\. Run the Taskkill Command

 Some Spotify users have said they were able to resolve the “application is not responding” error by running a taskkill command. This is a variation of the above resolution for terminating Spotify processes via the Command Prompt. You can run the taskkill command for Spotify as follows:

1. Open the Command Prompt as an administrator (see [how to open the Command Prompt app with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) for help).  
![The Run as administrator Command Prompt option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option-for-command-prompt.jpg)
2. Input this taskkill command:  
`TASKKILL /F /IM spotify.exe`  
![The taskkill command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/taskkill-command.jpg)
3. Press **Enter** to execute the taskill command.

## 3\. Delete the Spotify User Data Folder

 Deleting a -user subfolder within the Spotify data folder is another user-confirmed method for fixing the “Spotify application is not responding” error. Erasing that subfolder will delete the Spotify desktop app’s cached data for songs and login details. This is how you can delete the -user data folder in Windows:

1. Open Run by pressing that app’s **Win + R** key combo.
2. Type **%appdata%** in Run’s **Open** box and press **Enter** to view a Roaming folder.
3. Click the Spotify folder.
4. Open the users subfolder within the Spotify directory.  
![The -user folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-folder.jpg)
5. Right-click on the -user folder with random characters within its directory title and select **Delete**.
6. Try opening Spotify again.

 A variation of this potential resolution is to erase a specific Spotify cache file. To do so, you’ll need to open the -user folder. Then right-click the **local-files.bnk** file and select **Delete**.

 If you’re utilizing the UWP app, select the **Reset** option to clear Spotify’s cached data. You can click that **Reset** option within the Apps & Features section of the Windows Settings app. Our guide tells you [how to reset Windows apps](https://www.makeuseof.com/windows-reset-app/).

## 4\. Repair the Spotify App

 Users with the UWP Spotify app can also try selecting a **Repair** option. The **Repair** option is available for fixing Microsoft Store apps that aren’t working right. You can select that troubleshooting option for Spotify just below that app’s **Reset** button from its advanced options within the Apps & Features tool.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/apps-and-features.jpg)

## 5\. Check That Spotify Is Allowed Through the Windows Firewall

 A firewall block is another potential cause for the “Spotify application is not responding” error. To address this possible cause, open Windows Defender Firewall’s allowed app settings and select the **Public** and **Private** checkboxes for the Spotify app. Our guide for [allowing apps through Windows Defender Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes full instructions for applying this resolution.

![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-defender-firewall.jpg)

 Many third-party security apps also have firewall components that can feasibly cause the “Spotify application is not responding” error much the same as WDF. If your PC has third-party security software installed, try allowing Spotify through that app’s firewall. Look for firewall exception options in the software’s settings tabs and select to permit Spotify through it.

## 6\. Disable Third-Party Security Software Installed

 Third-party security software packages also have antivirus shields that can cause app startup issues. So, try disabling the antivirus component of any third-party security app installed before running Spotify. This can usually be done by right-clicking the system tray icon of an antivirus tool and selecting a disable or turn-off setting for temporarily deactivating the shield.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If that works, don’t leave the antivirus shield disabled. Instead, add Spotify to the antivirus software’s scanning exclusion list. Go through the app’s setting tabs to find its antivirus exclusion options.

## 7\. Reinstall the Spotify App

 Finally, reinstall your Spotify software if the “application is not responding” error persists after applying all the alternative resolutions above. That’s probably the best way to fix other Spotify bugs or corrupted files causing the error. You can uninstall Spotify with the Apps & Features Settings tool, which is one of the methods in our guide to [removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/apps-and-features.jpg)

 We also recommend that you eradicate leftover Spotify data before reinstalling. To do so, delete the Spotify data folder at this directory path:

`C:\Users\<user name>\AppData\Roaming\Spotify`

 Or you could utilize a third-party uninstaller to remove Spotify. Software packages like IObit Uninstaller and Advanced Uninstaller Pro are freely available and will eradicate Spotify’s leftover data and registry entries. Check out our article about the [best Windows third-party uninstaller software](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/) for further details.

![The IObit Uninstaller software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/iobit-uninstaller-1.jpg)

 Then you can reinstall either the UWP or the desktop Spotify app. Click **Download** on the [Spotify Windows download page](https://www.spotify.com/us/download/windows/) to get the setup wizard for the desktop software. Then you’ll need to double-click the **SpotifySet.exe** file to install the desktop software.

 If you prefer the UWP Spotify app version, open this [Microsoft Store page](https://apps.microsoft.com/store/detail/spotify-music-and-podcasts/9NCBCSZSJRSB). Press the **Get in Store** app button on the Spotify page. Next, select **Open Microsoft Store** on the dialog box that prompts you to install the app from there. Click on Spotify’s **Get** button to both download and install that app.

![The Get option for the Spotify UWP app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/get-option-for-spotify.jpg)

## Get Back in the Groove With Your Spotify Windows App

 Those potential solutions will probably kick-start Spotify when the “Spotify application is not responding” stops it from starting. They’re worth a try since they’ve worked for many other Spotify users. Then you can listen to all your favorite albums with the Spotify Windows app again.

 Spotify doesn’t open when the “application is not responding” error occurs. Although users can’t still utilize Spotify within a browser, that’s not quite the same as the Windows app. This is how you can fix the “Spotify application is not responding” error message on a Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/master-hardware-controls-quick-keys-for-windows-disk-editor-entrance/"><u>Master Hardware Controls: Quick Keys for Windows Disk Editor Entrance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-extracting-device-ids-in-windows/"><u>Unleashing the Power: Extracting Device IDs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-starting-windows-media-player/"><u>Mastering the Art of Starting Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trouble-locating-astra-pilot-help-for-windows-11-pcs/"><u>Trouble Locating Astra Pilot? Help For Windows 11 PCs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlock-the-full-potential-of-zoom-in-your-xbox-setup/"><u>[Updated] Unlock the Full Potential of Zoom in Your Xbox Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-crashing-file-explorer-on-windows-11-now/"><u>Fix Crashing File Explorer on Windows 11 Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-windows-barriers-to-download-icloud-immediately/"><u>Overcome Windows' Barriers to Download iCloud Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-discrepancies-in-computers-processor-utilization/"><u>Resolving Discrepancies in Computers' Processor Utilization</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-on-iphone-11-pro-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password On iPhone 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-device-synergy-samsung-dex-for-galaxy-users/"><u>Streamlining Device Synergy: Samsung DeX for Galaxy Users</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-widespread-connectivity-problem-in-steam-windows-11/"><u>Resolving Widespread Connectivity Problem in Steam Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-building-your-own-youtube-auto-subscribe-url/"><u>[Updated] 2024 Approved  Building Your Own YouTube Auto-Subscribe URL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-driver-load-failure-in-win11/"><u>Overcoming Device Driver Load Failure in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-variability-in-windows-protocols-for-cloud-and-local-reinstallation/"><u>Understanding Variability in Windows Protocols for Cloud and Local Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-windows-11-in-software-installation-harmony/"><u>The Role of Windows 11 in Software Installation Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-system-space-essential-windows-extras-for-elimination/"><u>Revamp Your System Space: Essential Windows Extras for Elimination</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-make-a-hyperlapse-video/"><u>[Updated] How to Make A Hyperlapse Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-to-new-life-for-your-outdated-computer/"><u>Transition to New Life for Your Outdated Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-prioritize-disk-format-in-windows-errors/"><u>Resolving Prioritize Disk Format in Windows Errors</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-capturing-high-fidelity-games/"><u>[New] In 2024, Capturing High Fidelity Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-tools-focused-uninstall-strategies-for-windows-1011/"><u>Tailored Tools: Focused Uninstall Strategies for Windows 10/11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-elevate-your-footage-expert-advice-for-stunning-home-videos/"><u>In 2024, Elevate Your Footage Expert Advice for Stunning Home Videos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-crafting-engaging-youtube-thumbnails-a-step-by-step-guide/"><u>[New] 2024 Approved  Crafting Engaging YouTube Thumbnails  A Step-by-Step Guide</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713961252239-new-an-intro-video-describing-you-and-your-content-is-the-first-and-the-foremost-thing-which-a-viewer-sees-thinking-of-how-to-make-an-interesting-intro-vide/"><u>New An Intro Video Describing You and Your Content Is the First and the Foremost Thing Which a Viewer Sees. Thinking of How to Make an Interesting Intro Video, This Blog Is Surely a Supportive Guide for You. Learn More Here for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-missing-5ghz-network-on-windows-11-top-7-solutions/"><u>Troubleshoot Missing 5GHz Network on Windows 11: Top 7 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-workspaces-into-a-unified-digital-ecosystem-via-aoemi/"><u>Transforming Windows Workspaces Into a Unified Digital Ecosystem via AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-edge-techniques-for-effective-wsl-2-use/"><u>Leading Edge Techniques for Effective WSL 2 Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-browsing-efficiency-on-windows/"><u>Streamlining Browsing Efficiency on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-of-restarting-windows-sound-on-booting/"><u>Overcoming the Challenge of Restarting Windows Sound on Booting</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-unlocking-tiktok-perfecting-siri-voice-interaction/"><u>[New] 2024 Approved  Unlocking TikTok  Perfecting Siri Voice Interaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-alter-desktop-icons-separation-in-win-oss/"><u>Title: Alter Desktop Icons' Separation in WIN OSs</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-essential-tips-enhancing-focus-in-your-youtube-video/"><u>[Updated] Essential Tips  Enhancing Focus in Your YouTube Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-google-drives-synced-files-with-7-key-steps/"><u>Reviving Google Drive's Synced Files with 7 Key Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-windows-11-search-quick-fixes-to-follow/"><u>Mastery of Windows 11 Search: Quick Fixes to Follow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-removing-window-search-artifacts/"><u>Mastery Over Removing Window Search Artifacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-leaks-auto-shutdown-at-low-activity-windows-11-style/"><u>Preventing Leaks: Auto-Shutdown at Low Activity, Windows 11 Style</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-commanders-conclave-celebrating-the-best-of-7-total-wars-for-2024/"><u>[Updated] Commanders' Conclave  Celebrating the Best of 7 Total Wars for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/portable-apps-integration-guide-for-w11/"><u>Portable Apps Integration Guide for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-frozen-opera-downloads-in-windows-sphere/"><u>Unlock Frozen Opera Downloads in Windows Sphere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fingerprint-fraud-unraveling-the-latest-hack-on-windows-hello/"><u>Fingerprint Fraud? Unraveling the Latest Hack on Windows Hello</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-tips-for-disabling-usb-power-save-mode/"><u>Stay Connected - Tips for Disabling USB Power Save Mode</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On OnePlus 11 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-reinstating-default-windows-backups/"><u>The Path to Reinstating Default Windows Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-30015-26-in-m365-for-windows-computers/"><u>Resolving Error Code 30015-26 in M365 for Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-combat-gaming-induced-laptop-overheating/"><u>Steps to Combat Gaming-Induced Laptop Overheating</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-install-package-troubleshooting-in-newest-windows-release/"><u>Mastering Install Package Troubleshooting in Newest Windows Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-future-windows-laptops-top-picks/"><u>The Ultimate Guide to Future Windows Laptops: Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-troubleshooting-windows-1011-file-issues/"><u>Strategies for Troubleshooting Windows 10/11 File Issues</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-complete-guide-the-basics-of-google-podcasts-app/"><u>2024 Approved  Complete Guide  The Basics of Google Podcasts App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-high-definition-adventures-winning-with-windows-and-scummvm/"><u>The Ultimate Guide to High Definition Adventures: Winning with Windows & ScummVM</u></a></li>
</ul></div>
