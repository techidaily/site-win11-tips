---
title: PowerShell Command for Extracting IP & MAC Addresses
date: 2024-07-12T17:32:00.147Z
updated: 2024-07-13T17:32:00.147Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes PowerShell Command for Extracting IP & MAC Addresses
excerpt: This Article Describes PowerShell Command for Extracting IP & MAC Addresses
keywords: PowerShell IP Extraction,PowerShell MAC Retrieval,PowerShell Network Tools,PowerShell Address Gathering,Advanced PowerShell Scripts,PowerShell Data Collection,IP & MAC via PowerShell
thumbnail: https://thmb.techidaily.com/88bfebb08e4cbb8d0a68e78c0297b8f1e363343f342702915251fd121c5a13e0.jpg
---

## PowerShell Command for Extracting IP & MAC Addresses

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
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Google Pixel Fold | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-reactivating-windows-11s-diagnostic-features/"><u>Quick Fixes: Reactivating Windows 11'S Diagnostic Features</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-solved-how-to-transfer-from-apple-iphone-14-pro-max-to-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Solved How To Transfer From Apple iPhone 14 Pro Max to iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-mastering-audio-post-production-in-final-cut-pro/"><u>Updated Mastering Audio Post-Production in Final Cut Pro</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-achieving-pristine-audio-quality-tips-to-eradicate-distorted-sounds-in-visual-media/"><u>Updated In 2024, Achieving Pristine Audio Quality Tips to Eradicate Distorted Sounds in Visual Media</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-pinnacle-avi-player-mobile-and-desktop-excellence/"><u>[New] Pinnacle Avi Player  Mobile & Desktop Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-ram-essential-tweaks-for-enhanced-windows-performance/"><u>Maximizing RAM: Essential Tweaks for Enhanced Windows Performance</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-2-ways-to-loop-a-youtube-video-on-tv/"><u>[New] 2024 Approved  2 Ways to Loop a YouTube Video On TV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/self-guided-inspector-writes-secure-your-computer-from-spyware/"><u>Self-Guided Inspector' Writes: Secure Your Computer From Spyware</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-overcoming-obs-fullscreen-issues/"><u>[Updated] In 2024, Overcoming OBS Fullscreen Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-stuck-scrollbar-and-freezing-pages-in-microsoft-excel-on-windows/"><u>Stop Stuck Scrollbar & Freezing Pages in Microsoft Excel on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-virtualboxs-0x80004005-failure-message/"><u>Resolving Virtualbox's 0X80004005 Failure Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/single-point-protection-the-benefits-of-a-solo-antivirus-on-windows/"><u>Single-Point Protection: The Benefits of a Solo Antivirus on Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-elevating-your-video-brand-tips-for-great-youtube-banners/"><u>[New] 2024 Approved  Elevating Your Video Brand  Tips for Great YouTube Banners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-1011s-camera-error-0xa00f425d/"><u>Quick-Fix for Windows 10/11'S Camera Error: 0XA00F425D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-clearing-steams-dns-cache/"><u>Mastering the Art of Clearing Steam's DNS Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-upgrades-safely-with-tpm-and-secure-boot-enablement/"><u>Navigating Upgrades Safely with TPM and Secure Boot Enablement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-pc-reset-virtual-memory/"><u>Optimize Your PC: Reset Virtual Memory</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-15-activation-lock-primer-by-drfone-ios-unlock-ios-unlock/"><u>iPhone 15 activation lock primer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-temporary-file-error-1152-on-windows/"><u>Remedying Temporary File Error 1152 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-profile-correction-for-w11-oses/"><u>Mastering User Profile Correction for W11 OSes</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-motorola-moto-g34-5g-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Motorola Moto G34 5G Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrives-blob-tag-issue-a-windows-based-solution-guide/"><u>OneDrive's Blob Tag Issue: A Windows-Based Solution Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlocking-the-past-best-educational-historical-content-on-yt/"><u>2024 Approved  Unlocking the Past  Best Educational Historical Content on YT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-normal-display-on-microsoft-store/"><u>Restoring Normal Display on Microsoft Store</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-how-to-make-instagram-slow-motion-video/"><u>[New] 2024 Approved  How to Make Instagram Slow Motion Video</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-explore-10-youtube-creators-accelerating-their-popularity/"><u>In 2024, Explore 10 YouTube Creators Accelerating Their Popularity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-lost-control-panel-features-on-windows-11/"><u>Reclaim Lost Control Panel Features on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-typical-directory-display-order-in-win11/"><u>Reviving Typical Directory Display Order in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-disabled-troubleshooters-in-modern-windows/"><u>Resolving Disabled Troubleshooters in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-utorrent-installer-errors-in-windows-environment/"><u>Overcoming uTorrent Installer Errors in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-windows-error-exception-breakpoint-encountered/"><u>Steps to Solve Windows Error: Exception Breakpoint Encountered</u></a></li>
<li><a href="https://some-techniques.techidaily.com/free-tools-to-master-voice-manipulation-and-sound-design-for-2024/"><u>Free Tools to Master Voice Manipulation and Sound Design for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screen-phenomenon-in-webcams/"><u>Overcoming Black Screen Phenomenon in Webcams</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-guide-to-free-green-screen-apps-for-android-and-ios/"><u>Updated The Ultimate Guide to Free Green Screen Apps for Android and iOS</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/final-cut-pro-tutorial-adding-emotional-depth-with-the-ken-burns-effect-updated-2023-for-2024/"><u>Final Cut Pro Tutorial Adding Emotional Depth with the Ken Burns Effect (Updated 2023) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-of-superior-gaming-with-amd-radeon-tweaks/"><u>Secrets of Superior Gaming with AMD Radeon Tweaks</u></a></li>
</ul></div>
