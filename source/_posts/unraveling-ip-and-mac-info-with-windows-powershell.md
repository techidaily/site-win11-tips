---
title: Unraveling IP and MAC Info with Windows Powershell
date: 2024-06-25T17:03:05.830Z
updated: 2024-06-26T17:03:05.830Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/purging-steams-domain-name-system-on-windows-systems/"><u>Purging Steam's Domain Name System on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disparities-in-cloud-and-offline-windows-updates/"><u>Exploring Disparities in Cloud and Offline Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-methods-to-identify-system-gadgets/"><u>Proven Windows Methods to Identify System Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-systemsettings-issue-on-win11/"><u>Strategies to Solve SystemSettings Issue on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-keyspace-perfection-on-windows-11/"><u>Configuring Keyspace Perfection on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resolve-steam-video-hiccups/"><u>Essential Steps to Resolve Steam Video Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-online-journey-the-guide-to-win-net-health/"><u>Uninterrupted Online Journey: The Guide to Win Net Health</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-jujutsu-kaisen-characters-in-the-world-of-tiktok-creatives/"><u>[Updated] Jujutsu Kaisen Characters in the World of TikTok Creatives</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-behind-top-discord-emotes-crafting-conversation-artifacts/"><u>In 2024, Behind Top Discord Emotes  Crafting Conversation Artifacts</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-photo-distortion-techniques-in-ps/"><u>[New] Mastering Photo Distortion Techniques in PS</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-the-ultimate-cheat-sheet-to-creating-captivating-slow-motion-on-tiktok-for-2024/"><u>[New] The Ultimate Cheat Sheet to Creating Captivating Slow Motion on TikTok for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-achieving-instagrammable-proportion-the-self-clone-method-on-tiktok/"><u>2024 Approved  Achieving Instagrammable Proportion  The Self-Clone Method on TikTok</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/premium-5-web-based-video-recorders-for-2024/"><u>Premium 5 Web-Based Video Recorders for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-10-ultimate-webcam-reviews-for-informed-buyers/"><u>[New] In 2024, 10 Ultimate Webcam Reviews for Informed Buyers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/laughter-and-tears-connected-10-memes-that-resonate-on-ig/"><u>Laughter and Tears Connected  10 Memes That Resonate On IG</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>