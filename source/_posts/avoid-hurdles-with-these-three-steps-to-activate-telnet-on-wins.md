---
title: Avoid Hurdles with These Three Steps to Activate Telnet on Wins
date: 2024-07-12T18:07:01.560Z
updated: 2024-07-13T18:07:01.560Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoid Hurdles with These Three Steps to Activate Telnet on Wins
excerpt: This Article Describes Avoid Hurdles with These Three Steps to Activate Telnet on Wins
keywords: Telnet Activation Guide,WinXtel Setup Steps,Telnet on Windows,Easy Telnet Initiation,Enable Telnet on PC,Wins Telnet Setup,Activate WinTel Telnet
thumbnail: https://thmb.techidaily.com/72ca63d6325a67d4b7a844299776fc3c0b1aca6440d5ca1111f8174af4b16af4.jpg
---

## Avoid Hurdles with These Three Steps to Activate Telnet on Wins

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-budding-buyers-guide-monetization-platforms-for-novice-channels/"><u>2024 Approved  Budding Buyers Guide  Monetization Platforms for Novice Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edge-safety-implement-windows-11-defender-application-guard/"><u>Boosting Edge Safety: Implement Windows 11 Defender Application Guard</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-sailing-through-tiktoks-anime-oceans-choreographies-beats-and-visual-trends/"><u>[New] 2024 Approved  Sailing Through TikTok’s Anime Oceans  Choreographies, Beats and Visual Trends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-manager-admin-mode-on-windows-11/"><u>Boosting Task Manager: Admin Mode on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-premium-windows-11-webcam-recorder-lineup/"><u>[New] 2024 Approved  Premium Windows 11 Webcam Recorder Lineup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-eluding-windows-11-explorer-errors/"><u>Best Practices for Eluding Windows 11 Explorer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-discord-updates-and-autostart-on-windows-10/"><u>Avoid Discord Updates & Autostart on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-unveil-the-potential-of-zoom-filters-for-excellence/"><u>[New] In 2024, Unveil the Potential of Zoom Filters for Excellence</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-iphone-tips-for-perfecting-motion-shot-photography/"><u>2024 Approved  IPhone Tips for Perfecting Motion Shot Photography</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-ultimate-guide-to-finding-the-most-impactful-keywords-for-your-videos/"><u>The Ultimate Guide to Finding the Most Impactful Keywords for Your Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-do-not-have-access-issue-for-app-removals/"><u>Avoiding Do Not Have Access Issue for App Removals</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-a-lost-apple-iphone-xs-max-for-free-drfone-by-drfone-virtual-ios/"><u>How to Track a Lost Apple iPhone XS Max for Free? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-old-directx-gaming-via-dxvk-powered-upgrades/"><u>Amplifying Old DirectX Gaming via DXVK-Powered Upgrades</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-apple-iphone-14-pro-without-him-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Two Ways to Track My Boyfriends Apple iPhone 14 Pro without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-not-stopping-generic-audio-issue/"><u>Addressing 'Windows Not Stopping Generic Audio' Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-winservicesexe-and-its-errors/"><u>An In-Depth Look at Winservices.exe and Its Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-display-drivers-that-dont-launch-in-windows-10/"><u>Avoiding Display Drivers That Don’t Launch in Windows 10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-spectral-film-reset-guide/"><u>2024 Approved  Spectral Film Reset Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automated-folder-pairings-in-new-windows-os/"><u>Boost Efficiency with Automated Folder Pairings in New Windows OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/lighten-your-load-with-laughs-fb-detainment-chuckle-highlighters/"><u>Lighten Your Load with Laughs  FB Detainment Chuckle Highlighters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-folders-and-files-win-10s-technique/"><u>Blending Folders and Files: Win 10'S Technique</u></a></li>
<li><a href="https://facebook.techidaily.com/why-your-life-is-better-with-these-9-social-media-uses/"><u>Why Your Life Is Better with These 9 Social Media Uses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-and-reset-windows-11s-touch-keyboard-layout/"><u>Adjust and Reset Windows 11'S Touch Keyboard Layout</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-stream-like-a-pro-top-5-devices-for-live-recording-success/"><u>In 2024, Stream Like a Pro  Top 5 Devices for Live Recording Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-code-development-top-wls-2-methods-on-latest-oses/"><u>Boost Your Code Development: Top WLS 2 Methods on Latest OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adopt-a-streamlined-approach-to-input-customization/"><u>Adopt a Streamlined Approach to Input Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-update-disruption-x712-fiasco/"><u>Addressing Windows Update Disruption: X712 Fiasco</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-not-working-on-realme-narzo-n53-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Realme Narzo N53? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-leveraging-viewership-the-mechanics-of-product-sponsored-youtube-videos/"><u>In 2024, Leveraging Viewership  The Mechanics of Product-Sponsored YouTube Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-unlock-the-power-of-online-interaction-essential-tips-for-successful-zoom-chats/"><u>2024 Approved  Unlock the Power of Online Interaction  Essential Tips for Successful Zoom Chats</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-win11s-top-5-cost-free-applications-for-recording-screens/"><u>[New] In 2024, Win11's Top 5 Cost-Free Applications for Recording Screens</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-ultimate-screen-grabbing-software-for-windows/"><u>[Updated] Ultimate Screen Grabbing Software for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-control-display-settings-for-windows-11-users/"><u>Advanced Control: Display Settings for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-a-guide-to-setting-up-hyper-v-on-win-11-home/"><u>Boost Your PC: A Guide to Setting Up Hyper-V on Win 11 Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11-lock-screen-effortlessly/"><u>Avoiding Windows 11 Lock Screen Effortlessly</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-leading-online-repositories-for-text-effect-graphics/"><u>In 2024, Leading Online Repositories for Text Effect Graphics</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/learning-some-perfect-ways-to-convert-a-slow-motion-video-to-normal/"><u>Learning Some Perfect Ways to Convert a Slow-Motion Video to Normal</u></a></li>
<li><a href="https://driver-install.techidaily.com/supercharge-your-driver-updating-speed-in-win-10-81-and-7/"><u>Supercharge Your Driver Updating Speed in Win 10, 8.1 & 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-customized-windows-cmd-tricks-and-tips/"><u>Boost Productivity: Customized Windows Cmd Tricks and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-experts-strategy-for-managing-component-services-in-w11/"><u>An Expert's Strategy for Managing Component Services in W11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-investigating-youtube-dialogues/"><u>[New] Investigating YouTube Dialogues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11-shutdown-interval-for-executing-jobstasks/"><u>Adjusting Windows 11 Shutdown Interval for Executing Jobs/Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-mobile-with-instant-windows-apks/"><u>Boost Your Mobile with Instant Windows APKs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/creating-captivating-podcast-summaries-for-2024/"><u>Creating Captivating Podcast Summaries for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-on-time-adjusting-startup-services-for-windows-11/"><u>Beginning on Time: Adjusting Startup Services for Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-rotate-your-videos-with-ease-a-comprehensive-tutorial-for-2024/"><u>New Rotate Your Videos with Ease A Comprehensive Tutorial for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-unlocked-iphone-8-plus-by-drfone-ios/"><u>In 2024, Everything You Need To Know About Unlocked iPhone 8 Plus</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-top-5-free-online-tone-generator-tools-for-easy-use/"><u>2024 Approved Top 5 Free Online Tone Generator Tools for Easy Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-errors-essential-tips-for-first-time-windows-11-users/"><u>Avoiding Common Errors: Essential Tips for First-Time Windows 11 Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/game-recording-mastery-utilizing-gameye-and-more/"><u>Game Recording Mastery  Utilizing GamEye and More</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-whats-the-optimal-frame-rate-comparing-30-vs-60hz-recording/"><u>[Updated] In 2024, What's the Optimal Frame Rate? Comparing 30 Vs. 60Hz Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-on-windows-11-top-seven-tweaks-for-game-enthusiasts/"><u>Boosting Performance on Windows 11: Top Seven Tweaks for Game Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-write-access-denial-errors-in-windows-11-system/"><u>Addressing Write Access Denial Errors in Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-with-smooth-directx-downloads-and-upgrades/"><u>Boost Your PC with Smooth DirectX Downloads & Upgrades</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-breaking-down-itunes-video-recording-basics/"><u>In 2024, Breaking Down iTunes Video Recording Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aesthetic-arcade-adventures-old-classics-in-dosbox-x/"><u>Aesthetic Arcade Adventures: Old Classics in DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-blank-spaces-on-your-screen-icons-revival-guide/"><u>Avoid Blank Spaces on Your Screen: Icons Revival Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bidding-farewell-to-ads-in-the-win-11-startup/"><u>Bidding Farewell to Ads in the Win 11 Startup</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-fixing-11s-windows-pin-hiccups/"><u>Avoid Frustration: Fixing 11'S Windows PIN Hiccups</u></a></li>
</ul></div>
