---
title: "Discovering System Details: IP & MAC with PS on Windows"
date: 2024-06-25T16:47:11.810Z
updated: 2024-06-26T16:47:11.810Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/brightening-dull-cursors-in-uefi/"><u>Brightening Dull Cursors in UEFI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodge-the-null-error-resolving-win11-problems/"><u>Dodge the Null Error: Resolving Win11 Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-0x00000709-operation-could-not-be-completed-on-windows/"><u>How to Fix Error 0X00000709: Operation Could Not Be Completed on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realign-subtitles-in-prime-video-elevate-your-windows-11-experience/"><u>Realign Subtitles in Prime Video, Elevate Your Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-playing-old-championship-manager-on-pc/"><u>Top Tips for Playing Old Championship Manager on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-cross-platform-tools-windows-meets-android/"><u>Crucial Cross-Platform Tools: Windows Meets Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excellent-windows-apps-transforming-videos/"><u>Excellent Windows Apps Transforming Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disconnections-windows-and-printers/"><u>Overcoming Disconnections: Windows & Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unzipping-challenge-managing-multiple-compressed-files-in-a-snap/"><u>Unzipping Challenge: Managing Multiple Compressed Files in a Snap</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-the-essential-technique-screen-recording-on-the-go/"><u>[Updated] The Essential Technique  Screen Recording on the Go</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-realme-11x-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Realme 11X 5G Phone that is Locked?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-itel-a60-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Itel A60 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://article-files.techidaily.com/new-2024-approved-the-development-and-application-of-vr-shopping/"><u>[New] 2024 Approved  The Development and Application of VR Shopping</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-video-ranking-rise-must-have-youtube-seo-aids/"><u>[Updated] Video Ranking Rise – Must-Have YouTube SEO Aids</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-through-the-10-leading-countdown-clock-apps-for-your-big-day-androidios/"><u>2024 Approved  Navigating Through the 10 Leading Countdown Clock Apps for Your Big Day (Android/iOS)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-sj7-redefines-capturing-life-comprehensively-reviewing-its-4k-star-cam/"><u>[New] SJ7 Redefines Capturing Life  Comprehensively Reviewing Its 4K Star Cam</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-8t-video-recovery-recover-deleted-videos-from-play-8t-by-fonelab-android-recover-video/"><u>Play 8T Video Recovery - Recover Deleted Videos from Play 8T</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-ultimate-checklist-for-superior-sound-on-personal-video-recording/"><u>Updated The Ultimate Checklist for Superior Sound on Personal Video Recording</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-from-iphone-14-pro-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock From iPhone 14 Pro? How to Fix it?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>