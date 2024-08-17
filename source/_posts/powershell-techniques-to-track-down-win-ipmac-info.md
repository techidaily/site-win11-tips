---
title: PowerShell Techniques to Track Down Win IP/MAC Info
date: 2024-08-16T02:42:40.262Z
updated: 2024-08-17T02:42:40.262Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes PowerShell Techniques to Track Down Win IP/MAC Info
excerpt: This Article Describes PowerShell Techniques to Track Down Win IP/MAC Info
keywords: PowerShell Network Forensics,Windows IP Address Finder,MAC Address Discovery PowerShell,PowerShell Windows Hacking,Track IP Win Systems,Mac Address Extraction Script,Powershell Win Network Analysis
thumbnail: https://thmb.techidaily.com/77006c539bf1ddb2e2b5e84e1f174870218883325d71d7edbcfdaf185bcde8ae.jpg
---

## PowerShell Techniques to Track Down Win IP/MAC Info

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
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-apples-m1-performance-enhancing-video-editing/"><u>[New] Apple’s M1 Performance  Enhancing Video Editing?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-catchy-opening-tunes-podcasts-best-audio-gems/"><u>[Updated] Catchy Opening Tunes  Podcast's Best Audio Gems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-microphone-feedback-audio-recorder/"><u>[Updated] In 2024, Microphone Feedback  Audio Recorder</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-playlist-passport-traveling-tunes-throughout-platforms/"><u>[Updated] Playlist Passport  Traveling Tunes Throughout Platforms</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-social-media-strategy-decoding-igtv-versus-youtubes-features/"><u>[Updated] Social Media Strategy  Decoding IGTV Versus YouTube's Features</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-entering-metaverse-ranked-best-virtual-reality-gear/"><u>2024 Approved  Entering Metaverse  Ranked Best Virtual Reality Gear</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gopro-cinema-boosted-list-of-the-best-15-luts/"><u>2024 Approved  GoPro Cinema Boosted  List of the Best 15 LUTs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-cmd-guru-understand-these-20-crucial-commands/"><u>Become a CMD Guru: Understand These 20 Crucial Commands</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/cutting-edge-green-tools-shaping-film/"><u>Cutting Edge Green Tools Shaping Film</u></a></li>
<li><a href="https://driver-install.techidaily.com/download-latest-drivers-netgear-a6200-usb-adapter/"><u>Download Latest Drivers: Netgear A6200 USB-Adapter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-pc-performance-insider-tips-on-wintools/"><u>Elevate PC Performance: Insider Tips on WinTools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-share-cant-be-opened-issues-in-geforce/"><u>Eliminating Share Can't Be Opened Issues in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-remedy-guide-eight-tactics/"><u>Essential Windows Remedy Guide - Eight Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-removal-of-win11s-official-store/"><u>Exclusive Removal of Win11's Official Store</u></a></li>
<li><a href="https://fox-access.techidaily.com/financial-forecast-shooting-a-music-video-for-2024/"><u>Financial Forecast  Shooting a Music Video for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-11-endless-reboot-cycle-expert-solutions/"><u>Fixing Windows 11 Endless Reboot Cycle: Expert Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/group-free-enhance-windows-11-taskbar-ease/"><u>Group-Free: Enhance Windows 11 Taskbar Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-an-exception-breakpoint-has-been-reached-error-on-windows/"><u>How to Fix the “An Exception Breakpoint Has Been Reached” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-iphone-image-import-something-went-wrong-error-in-windows-10-and-11/"><u>How to Fix the iPhone Image Import “Something Went Wrong” Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-steam-disk-write-error-on-windows/"><u>How to Fix the Steam Disk Write Error on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-tecno-camon-20-pro-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Tecno Camon 20 Pro 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-infinix-hot-40-pro-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Infinix Hot 40 Pro to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-cracking-the-cartoon-code-a-quick-guide-to-lenses-in-snapchat/"><u>In 2024, Cracking the Cartoon Code  A Quick Guide to Lenses in Snapchat</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-from-good-to-great-videos-the-20-essential-shortcuts-for-success/"><u>In 2024, From Good to Great Videos  The 20 Essential Shortcuts for Success</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-revitalize-your-tiktok-videos-masterful-techniques-to-alter-backdrops/"><u>In 2024, Revitalize Your TikTok Videos  Masterful Techniques to Alter Backdrops</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-realme-12plus-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Realme 12+ 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-fingerprint-recognition-in-windows-11/"><u>Integrating Fingerprint Recognition in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-older-systems-healthy-with-win10-improvements/"><u>Keep Older Systems Healthy with Win10 Improvements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-collectors-delight-exclusive-black-friday-price-drop-on-essential-windows-11/"><u>Key Collectors' Delight – Exclusive Black Friday Price Drop on Essential Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/non-edge-processes-lurking-in-task-manager/"><u>Non-Edge Processes Lurking in Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-network-issues-on-windows-11-a-comprehensible-approach/"><u>Overcoming Network Issues on Windows 11 - A Comprehensible Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-difficulty-of-error-0x000-in-xbox-game-pass-windows-edition/"><u>Overcoming the Difficulty of Error 0X000_ in Xbox Game Pass Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-jump-to-notes-starting-windows-with-immediate-access/"><u>Quick Jump to Notes: Starting Windows with Immediate Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-office-activation-error/"><u>Resolving Microsoft Office Activation Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-ps4-remote-link-eliminating-random-drops-in-connection/"><u>Secure Your PS4 Remote Link: Eliminating Random Drops in Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-search-with-image-cleanse/"><u>Simplifying Windows Search with Image Cleanse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-performance-essential-strategies-with-windows-11/"><u>Skyrocket Your Performance: Essential Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-gpu-load-for-smarter-windows-11-wm-efficiency/"><u>Slash GPU Load for Smarter Windows 11 WM Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-activatedeactivate-safeguard-in-windows-10/"><u>Steps to Activate/Deactivate SafeGuard in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-rectify-bluetooth-check-pin-error-in-windows-oses/"><u>Strategies to Rectify Bluetooth Check Pin Error in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-store-mishaps-cure-0x80072f30-glitches/"><u>Tackling Windows Store Mishaps: Cure 0X80072F30 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-keybinds-for-snippet-copy-and-paste/"><u>Tailored Keybinds for Snippet Copy & Paste</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/techniques-for-alluring-fb-video-marketing/"><u>Techniques for Alluring FB Video Marketing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-practical-side-of-bluescreenview-usage/"><u>The Practical Side of BlueScreenView Usage</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-solution-to-correct-mfc42dll-not-detected-errors/"><u>The Ultimate Solution to Correct Mfc42.dll Not Detected Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-control-over-your-pc-in-winos/"><u>Unlock Full Control Over Your PC in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-9-irritating-windows-11-layouts/"><u>Unraveling 9 Irritating Windows 11 Layouts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/urban-pursuit-without-the-need-for-gta/"><u>Urban Pursuit Without the Need for GTA</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722998642840-why-is-the-microsoft-teams-chatbot-keeps-freezing-and-crashing-heres-the-solution/"><u>Why Is the Microsoft Teams Chatbot Keeps Freezing and Crashing? Here's the Solution!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>