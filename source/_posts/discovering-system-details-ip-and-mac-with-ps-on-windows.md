---
title: "Discovering System Details: IP & MAC with PS on Windows"
date: 2024-07-12T17:17:05.144Z
updated: 2024-07-13T17:17:05.144Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Discovering System Details: IP & MAC with PS on Windows"
excerpt: "This Article Describes Discovering System Details: IP & MAC with PS on Windows"
keywords: PS Windows IP Info,PS Network MAC Address,Windows PS Device Details,PS System Information,PS Get IP Address,PS Display MAC,PS OS Configuration
thumbnail: https://thmb.techidaily.com/a9fb2f2e749603e5c7deed59a3dccc2eb82bb973e6c7211350802c91feadcdaf.jpg
---

## Discovering System Details: IP & MAC with PS on Windows

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
<li><a href="https://win11-tips.techidaily.com/take-full-advantage-of-windows-11-features/"><u>Take Full Advantage of Windows 11 Features</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-financial-forecasts-in-focus-select-stock-youtube-channels-for-2024/"><u>[Updated] Financial Forecasts in Focus  Select Stock YouTube Channels for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-management-adding-this-pc-to-windows-desktop/"><u>Window Management: Adding 'This PC' To Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-restore-colorful-screen-on-windows-pc-via-remote-access/"><u>Steps to Restore Colorful Screen on Window's PC via Remote Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-hypervisorerror-blue-screen-on-windows-10-and-11/"><u>5 Ways to Fix the HYPERVISOR_ERROR Blue Screen on Windows 10 & 11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/top-6-free-talking-stock-photo-sites/"><u>Top 6 Free Talking Stock Photo Sites</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-share-your-ps4-gaming-moments-with-the-world-a-simple-tutorial/"><u>Updated In 2024, Share Your PS4 Gaming Moments with the World A Simple Tutorial</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-virtual-producers-showdown/"><u>[Updated] In 2024, Virtual Producer's Showdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-full-use-of-the-control-key-in-windows-11/"><u>Enabling Full Use of the Control Key in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-efficiently-record-your-gotomeeting-conferences-for-2024/"><u>[New] Efficiently Record Your GoToMeeting Conferences for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-where-can-i-find-scream-sound-effect-in-2024/"><u>New Where Can I Find Scream Sound Effect, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-your-onedrive-to-a-desired-spot-on-win10/"><u>Transitioning Your OneDrive to a Desired Spot on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx939-dll-in-win11/"><u>Addressing Missing D3DX9_39 DLL in Win11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/5-ways-to-record-gameplay-and-webcam/"><u>5 Ways to Record Gameplay and Webcam</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-growth-through-video-content-a-guide-to-thriving-with-tiktok/"><u>[Updated] 2024 Approved  Growth Through Video Content  A Guide to Thriving with TikTok</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-from-iphone-12-pro-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account From iPhone 12 Pro</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-asus-mg28uq-monitor-unpacking-the-ultra-high-resolution-experience/"><u>[Updated] In 2024, ASUS MG28UQ Monitor  Unpacking the Ultra High-Resolution Experience</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/dramatic-footage-showdown-hero5-against-star/"><u>Dramatic Footage Showdown  Hero5 Against Star</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stuck-battlenet-login-screen/"><u>Solutions for Stuck Battle.net Login Screen</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-clearer-sound-with-these-ipad-tips/"><u>[New] In 2024, Clearer Sound with These iPad Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-captioning-hurdles-on-windows-10-devices/"><u>Solving Common Captioning Hurdles on Windows 10 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-system-image-creation-on-windows/"><u>Simplified System Image Creation on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-recording-basics-for-newcomers-on-win-11/"><u>Audio Recording Basics for Newcomers on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-to-access-mspaint-in-windows-11/"><u>Discovering How to Access MSPaint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-manual-timezone-setting-in-microsoft-os/"><u>Troubleshoot Manual Timezone Setting in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-switching-on-updated-widget-selection-interface-in-windows-11/"><u>Seamlessly Switching on Updated Widget Selection Interface in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-samsung-galaxy-s23-ultra-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Samsung Galaxy S23 Ultra to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/assessing-tseries-financial-outcomes-from-youtube-presence-for-2024/"><u>Assessing TSeries’ Financial Outcomes From YouTube Presence for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-users-should-anticipate-sudo/"><u>Why Windows Users Should Anticipate Sudo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-0x800713f-mail-glitch/"><u>Resolving Windows' 0X800713F Mail Glitch</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-expert-choice-top-12-non-time-restricted-recorders/"><u>In 2024, Expert Choice  Top 12 Non-Time Restricted Recorders</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-the-ultimate-pathway-to-saving-social-media-gifs-on-different-devices-for-2024/"><u>[New] The Ultimate Pathway to Saving Social Media GIFs on Different Devices for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-0x800f0922-error-quick-fixed-guide/"><u>Solving Windows 11'S 0X800F0922 Error - Quick Fixed Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-navigate-must-try-world-building-games/"><u>[New] Navigate  Must-Try World Building Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-operations-7-easy-tips-for-advanced-windows-11-users/"><u>Streamline Operations: 7 Easy Tips for Advanced Windows 11 Users</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-motorola-moto-g84-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Motorola Moto G84 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268439990-chrome-freeze-no-more-top-solutions-for-windows-11-users/"><u>Chrome Freeze No More: Top Solutions for Windows 11 Users!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-tecno-phantom-v-fold-frp-bypass-by-drfone-android/"><u>In 2024, About Tecno Phantom V Fold FRP Bypass</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-slow-and-steady-wins-the-race-vlc-slow-motion-guide-for-desktop-and-mobile/"><u>Updated Slow and Steady Wins the Race VLC Slow Motion Guide for Desktop and Mobile</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-what-is-anime-filter-on-snapchat-how-to-get-it-for-2024/"><u>[New] What Is Anime Filter On Snapchat? [How to Get It] for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-setup-guide-for-steam-deck-owners/"><u>Windows Setup Guide for Steam Deck Owners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-system-editor-access-control-on-windows-11/"><u>Techniques for System Editor Access Control on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-cant-access-mail-alert-on-windows-11s-mail-app/"><u>Unveiling Fixes for Can't Access Mail Alert on Windows 11'S Mail App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-caps-lock-and-numeric-status-on-taskbar-tray-of-win11/"><u>Displaying Caps Lock & Numeric Status on Taskbar Tray of Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-videos-not-playing-with-my-edge-40-by-stellar-video-repair-mobile-video-repair/"><u>How to fix videos not playing with my Edge 40?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-dilemran-of-winscripterrors/"><u>Deciphering the Dilemran of WinScriptErrors</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-elevating-sims-4-chronicles-advanced-techniques-for-precise-game-recording-for-2024/"><u>[Updated] Elevating Sims 4 Chronicles  Advanced Techniques for Precise Game Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-primes-textual-missteps-on-windows-11-desktops/"><u>Correct Prime's Textual Missteps on Windows 11 Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-data-flow-from-non-responsive-usb-devices-win-os/"><u>Restoring Data Flow From Non-Responsive USB Devices (Win OS)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-high-dpi-displays-a-windows-guide/"><u>Dealing with High DPI Displays: A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-time-intensive-gpsvc-hangs/"><u>Eliminating Time-Intensive GPSVC Hangs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-engaging-audiences-on-multiple-digital-landscapes/"><u>[Updated] Engaging Audiences on Multiple Digital Landscapes</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-package-unopenable-error-on-win11-10-oses/"><u>Eliminating the 'Package Unopenable' Error on Win11, 10 OSes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-ultimate-players-guide-best-of-terraria-mods/"><u>[Updated] In 2024, Ultimate Player's Guide  Best of Terraria Mods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphered-defense-dont-shift-too-suddenly/"><u>Deciphered Defense? Don't Shift Too Suddenly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-fatal-0xf0831-bug/"><u>Resolving Windows 11'S Fatal 0xF0831 Bug</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-syncing-tunes-with-video-posts-on-facebook/"><u>2024 Approved  Syncing Tunes with Video Posts on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-productivity-integrating-flow-launcher-into-daily-routine/"><u>Amplify Productivity: Integrating Flow Launcher Into Daily Routine</u></a></li>
</ul></div>
