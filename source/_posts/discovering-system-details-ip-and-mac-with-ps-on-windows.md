---
title: "Discovering System Details: IP & MAC with PS on Windows"
date: 2024-08-16T01:49:38.160Z
updated: 2024-08-17T01:49:38.160Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-clips.techidaily.com/new-end-screen-essentials-for-social-media-success-on-youtube/"><u>[New] End-Screen Essentials for Social Media Success on YouTube</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-quick-and-easy-incorrante-audio-into-fb-profiles-ios-android-for-2024/"><u>[New] Quick & Easy  Incorrante Audio Into FB Profiles (iOS, Android) for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-quick-windows-10-tutorial-for-simple-video-trimming/"><u>[Updated] Quick Windows 10 Tutorial for Simple Video Trimming</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-soundscapes-in-stories-instagram-video-techniques/"><u>[Updated] Soundscapes in Stories  Instagram Video Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-20-ae-templates-for-aspiring-designers/"><u>[Updated] Top 20 AE Templates for Aspiring Designers</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-innovative-ideas-for-customized-gif-art/"><u>2024 Approved  Innovative Ideas for Customized GIF Art</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-master-pip-feature-while-consuming-youtube-videos-on-iphones/"><u>2024 Approved  Master PIP Feature While Consuming YouTube Videos on iPhones</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pro-gopro-filming-techniques-unveiled/"><u>2024 Approved  Pro-Gopro Filming Techniques Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-precise-methods-to-resolve-onedrive-errors/"><u>6 Precise Methods to Resolve OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-gaining-entry-into-windows-11s-application-repository/"><u>A Guide to Gaining Entry Into Windows 11'S Application Repository</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-steam-contact-issues-on-win11/"><u>A Step-by-Step Guide to Fixing Steam Contact Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-gameplay-9-tricks-to-end-wwe-2k23-freezes-in-windows/"><u>Accelerate Gameplay: 9 Tricks to End WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimum-ssd-speed-on-windows-via-ssdfresh/"><u>Achieve Optimum SSD Speed on Windows via SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-gmail-to-windows-outlook-seamless-integration-method/"><u>Adding Gmail to Windows Outlook: Seamless Integration Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-id-inaccuracy-in-windows-11/"><u>Addressing System ID Inaccuracy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-reset-account-lockouts-after-failed-logins-in-windows-11/"><u>Adjusting Reset Account Lockouts After Failed Logins in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alteration-of-login-failure-counter-windows-11-user-guide/"><u>Alteration of Login Failure Counter: Windows 11 User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-computer-speakers-not-working-how-to-fix-having-no-sound/"><u>Are Your Computer Speakers Not Working? How to Fix Having No Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-mobility-center-activation-in-w11-systems/"><u>Avoid Mobility Center Activation in W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-crashes-in-the-epic-launcher-for-win-users/"><u>Avoidance of Crashes in the Epic Launcher for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-nvidia-writes-of-error-3-in-win1011/"><u>Avoiding NVIDIA' Writes of Error 3 in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-screen-glitches-in-modern-operating-systems/"><u>Banishing Screen Glitches in Modern Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-delay-in-sw-top-tips-to-speed-up-your-bf2-gameplay/"><u>Beat Delay in SW: Top Tips to Speed Up Your BF2 Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-tools-for-mp4-and-mov-clips/"><u>Best Windows Tools for MP4 and MOV Clips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-extended-storage-mediocre-execution/"><u>Blackview MiniPC: Extended Storage, Mediocre Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automated-folder-pairings-in-new-windows-os/"><u>Boost Efficiency with Automated Folder Pairings in New Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-hotkeys-for-instantaneous-windows-redos/"><u>Boost Efficiency: Hotkeys for Instantaneous Windows Redos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-terminal-as-favorite-app/"><u>Boost Productivity with Terminal as Favorite App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359374237-combat-window-settings-malfunctions-now/"><u>Combat Window Settings Malfunctions Now!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dispel-darkness-of-dazzling-displays/"><u>Dispel Darkness of Dazzling Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-craft-visionary-videos-from-start-to-finish-using-youtube-studio-editor/"><u>In 2024, Craft Visionary Videos From Start to Finish Using YouTube Studio Editor</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-mechanics-of-instagrams-featured-stories/"><u>In 2024, The Mechanics of Instagram's Featured Stories</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-samsung-galaxy-a25-5g-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Samsung Galaxy A25 5G Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338441167-navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298161302-overcoming-grayed-out-screensaver-in-win-os-top-fixes/"><u>Overcoming Grayed-Out Screensaver in Win OS: Top Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-dilemma-obs-not-opening-on-windows/"><u>Resolving the Dilemma: OBS Not Opening on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steer-clear-of-stuck-arrows-in-windows/"><u>Steer Clear of Stuck Arrows in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-samsung-galaxy-s24plus-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Samsung Galaxy S24+ Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-s-mode-imply-in-windows-11-upgrade/"><u>What Does 'S Mode' Imply in Windows 11 Upgrade?</u></a></li>
</ul></div>
