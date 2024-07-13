---
title: Unraveling IP and MAC Info with Windows Powershell
date: 2024-07-12T17:35:25.047Z
updated: 2024-07-13T17:35:25.047Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling IP and MAC Info with Windows Powershell
excerpt: This Article Describes Unraveling IP and MAC Info with Windows Powershell
keywords: Windows PowerShell Scripts,PSH Network Analysis,IP Address Details,MAC Address Extraction,Powershell Infrastructure Insight,Systems Configuration Tools,Data Interpretation in WinPSH
thumbnail: https://thmb.techidaily.com/f68ad44dfce4596bff961c8c73128e503881dbfbd95e5f1787a78426eec3f375.jpg
---

## Unraveling IP and MAC Info with Windows Powershell

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-samsung-galaxy-s23-fe-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Samsung Galaxy S23 FE Without PUK Codes</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-apple-iphone-12-pro-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From Apple iPhone 12 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-value-with-smart-acquisition-of-windows-10-product-keys/"><u>Maximizing Value with Smart Acquisition of Windows 10 Product Keys</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-preeminent-5-cloud-video-capture-systems/"><u>2024 Approved  Preeminent 5 Cloud Video Capture Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/find-out-if-your-pc-is-a-win11-ready-machine/"><u>Find Out if Your PC Is a Win11-Ready Machine</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-extract-and-save-still-images-from-movies-in-windows-photos/"><u>In 2024, Extract and Save Still Images From Movies in Windows Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantaneous-transcription-experience-with-whisper-desktop/"><u>Instantaneous Transcription Experience with Whisper Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-notepad-blockade-uncover-the-7-pathways-to-access-it-again/"><u>Windows Notepad Blockade: Uncover the 7 Pathways to Access It Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-server-slips-for-smooth-ms-store-in-windows-os/"><u>Conquering Server Slips for Smooth MS Store in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-solving-obs-errors-windows-edition/"><u>Understanding and Solving OBS Errors: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-update-anomaly-error-0xca00a009/"><u>Eliminating Windows Update Anomaly: Error 0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-experience-mastering-windows-11s-search-tool/"><u>Jumpstart Your PC Experience: Mastering Windows 11’S Search Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-systems-analyzers-for-windows/"><u>Essential Systems Analyzers for Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-techniques-for-gh-video-logging/"><u>In 2024, Techniques for GH Video Logging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-onedrive-invalid-tag-error-in-windows-file-system/"><u>Eliminating the OneDrive Invalid Tag Error in Windows File System</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-how-to-see-every-participant-in-google-meet-in-2024/"><u>[Updated] How to See Every Participant in Google Meet, In 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-uncover-5-windows-11-tools-for-professional-audio-recording/"><u>In 2024, Uncover 5 Windows 11 Tools for Professional Audio Recording</u></a></li>
<li><a href="https://vp-tips.techidaily.com/navigating-photoplusvideo-integration-with-iphone-for-2024/"><u>Navigating Photo+Video Integration with iPhone for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-boost-video-quality-best-brightness-adjustment-tools-online-and-offline/"><u>Updated In 2024, Boost Video Quality Best Brightness Adjustment Tools Online and Offline</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-much-do-podcasters-earn-on-average-in-2024/"><u>How Much Do Podcasters Earn on Average, In 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-honor-90-gt-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-expert-guide-extracting-silence-from-video-files-on-windows-10-without-spending-a-penny/"><u>In 2024, Expert Guide Extracting Silence From Video Files on Windows 10 Without Spending a Penny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-package-blockage-a-window-solution-for-error-fixes/"><u>Disabling Package Blockage: A Window Solution for Error Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-snip-and-sketch-shortcut/"><u>Launching Windows 11'S Snip & Sketch Shortcut</u></a></li>
<li><a href="https://win11-tips.techidaily.com/checking-audio-device-integrity-on-windows/"><u>Checking Audio Device Integrity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-sound-glitch-error-0xc00d36b4-on-win11/"><u>Bypassing Sound Glitch: Error 0XC00D36B4 on Win11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-magnificent-mavericks-amongst-millions-on-tiktoks-stage-for-2024/"><u>[Updated] Magnificent Mavericks Amongst Millions on TikTok's Stage for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-out-onedrive-from-your-pcs-file-explorer-screenshot/"><u>How to Cut Out OneDrive From Your PC's File Explorer Screenshot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-upgrading-isnt-feeling-right-for-many-to-windows-11/"><u>Why Upgrading Isn't Feeling Right for Many to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-to-the-upcoming-sudo-integration/"><u>Adapting to the Upcoming Sudo Integration</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-avoid-ordinary-bordered-instagram-photos-for-impact/"><u>[New] 2024 Approved  Avoid Ordinary  Bordered Instagram Photos for Impact</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-srt-file-uploads-on-social-platforms-step-by-step-guide/"><u>In 2024, Mastering SRT File Uploads on Social Platforms  Step-by-Step Guide</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/navigating-the-increasedecrease-functionality-in-audacity-for-clearer-sounds/"><u>Navigating the Increase/Decrease Functionality in Audacity for Clearer Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-home-page-from-the-settings-app-in-windows-11/"><u>How to Remove the Home Page From the Settings App in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-how-to-speed-up-videos-on-quicktime-player-windowsmac/"><u>2024 Approved How to Speed Up Videos on QuickTime Player Windows/Mac</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-activation-lock-on-apple-watch-or-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, How To Bypass Activation Lock On Apple Watch Or iPhone 11 Pro Max?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-xbox-apps-voice-issues-in-windows/"><u>Understanding Xbox App's Voice Issues in Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-screen-recorder-software-guide-12-picks/"><u>[New] Screen Recorder Software Guide  12 Picks</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1715860313707-new-xbox-game-memories-save-them-with-screenshots/"><u>[New] Xbox Game Memories, Save Them with Screenshots!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-winservicesexe-operations/"><u>Demystifying WinServices.exe Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/forge-ahead-with-stronger-windows-security-top-four-password-keepers/"><u>Forge Ahead with Stronger Windows Security: Top Four Password Keepers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-power-management-features-for-maximum-efficiency/"><u>Unlocking Power Management Features for Maximum Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-editorial-techniques-select-from-the-top-8-video-trimming-titles/"><u>Winning Editorial Techniques: Select From The Top 8 Video Trimming Titles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-path-to-larger-video-presentation-in-youtube/"><u>2024 Approved  The Path to Larger Video Presentation in YouTube</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-voice-memo-mastery-for-ios-users-step-by-step/"><u>[New] In 2024, Voice Memo Mastery for iOS Users Step-by-Step</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-tecno-spark-20-lock-screen-password-by-drfone-android/"><u>How to Reset your Tecno Spark 20 Lock Screen Password</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-your-viewers-your-wealth-building-an-earning-strategy/"><u>[New] In 2024, Your Viewers, Your Wealth  Building an Earning Strategy</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-game-changers-discovering-top-tier-gaming-webcam-technology/"><u>2024 Approved  Game Changers  Discovering Top-Tier Gaming Webcam Technology</u></a></li>
<li><a href="https://games-able.techidaily.com/2-year-tale-why-i-prefer-an-oled-monitor/"><u>2-Year Tale: Why I Prefer an OLED Monitor</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-itel-p40-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Itel P40 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-core-data-an-analysis-of-the-registry/"><u>Unlocking Windows 11'S Core Data: An Analysis of the Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-pathways-to-launching-windows-fix/"><u>Essential Pathways to Launching Windows FIX</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-capturing-the-cloudline-in-your-backyard-the-revolutionary-dji-spark-unveiled-for-2024/"><u>[New] Capturing the Cloudline in Your Backyard  The Revolutionary DJI Spark Unveiled for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-5-panoramic-capture-models/"><u>Top 5 Panoramic Capture Models</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-efficient-wsl-2-on-windows/"><u>Winning Strategies for Efficient WSL 2 on Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-assessing-instagrams-limits-on-posted-videos/"><u>2024 Approved  Assessing Instagram's Limits on Posted Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-printing-at-your-fingertips-slow-printer-remedies-in-windows/"><u>Fast Printing at Your Fingertips: Slow Printer Remedies in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-flawless-display-with-win11-settings/"><u>Achieve Flawless Display with Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-slow-computer-wake-up-the-complete-window-11-startup-guide/"><u>Conquering Slow Computer Wake-Up: The Complete Window 11 Startup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-hard-drives-performance-defrag-guide-for-win11/"><u>Enhance Hard Drives Performance: Defrag Guide for Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-vivo-v27e-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Vivo V27e to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-yourphoneexe-phone-link-in-windows-1110-should-you-disable-it/"><u>What Is YourPhone.exe (Phone Link) in Windows 11/10? Should You Disable It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-visual-elements-from-search-bar/"><u>How to Clear Visual Elements From Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-flickering-win1011-screens/"><u>Efficient Fixes for Flickering WIN10/11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-game-bar-errors-on-underpowered-systems/"><u>Addressing Game Bar Errors on Underpowered Systems</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-elevate-your-content-strategies-for-youtube-success/"><u>[New] Elevate Your Content  Strategies for YouTube Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-disabled-windows-application/"><u>How to Enable Disabled Windows Application</u></a></li>
</ul></div>
