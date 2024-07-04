---
title: Navigate Your Computer's IP and MAC with Powershell
date: 2024-06-25T16:50:08.500Z
updated: 2024-06-26T16:50:08.500Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate Your Computer's IP and MAC with Powershell
excerpt: This Article Describes Navigate Your Computer's IP and MAC with Powershell
keywords: PC IP Addressing,MAC Addressing Windows,PC PowerShell Commands,Find PC IP Address,Locate MAC Address,System Network Info,PowerShell Netconfig
thumbnail: https://thmb.techidaily.com/2cb259c465a86a9d87c2ab8ed232a243225880491ec4b7484688140a5b3e77f5.jpg
---

## Navigate Your Computer's IP and MAC with Powershell

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
<li><a href="https://win11-tips.techidaily.com/four-steps-for-pausing-windows-update/"><u>Four Steps for Pausing Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-error-unending-teams-sign-in-requests/"><u>Overcoming Windows Error: Unending Teams Sign-In Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-file-lockdowns-access-restoration-on-pcs/"><u>Reversing File Lockdowns: Access Restoration on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-innovation-windows-personalization-through-lock-patterns/"><u>Stepwise Innovation: Windows Personalization Through Lock Patterns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x0000011b-operation-failure-on-windows-11/"><u>Correcting 0X0000011B Operation Failure on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-the-failed-to-launch-lunar-client-windows-message/"><u>Circumventing the Failed to Launch: Lunar Client Windows Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-solution-to-error-code-0x80070570-rescuing-damaged-files-on-windows-11/"><u>Unlocking Solution to Error Code 0X80070570: Rescuing Damaged Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-deletion-in-windows-11-115-chars/"><u>Mastering Software Deletion in Windows 11 (115 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-fixing-unexpected-system-call-failures-on-win1011/"><u>Guide: Fixing Unexpected System Call Failures on Win10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/asus-proart-excellence-in-4k-hdr-monitoring/"><u>ASUS ProArt  Excellence in 4K HDR Monitoring</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-how-to-upload-youtube-shorts-video-from-computer-and-mobile/"><u>2024 Approved  How to Upload YouTube Shorts Video From Computer and Mobile?</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-honor-magic-v2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-narratives-of-the-bravest-our-favorites-in-adventure-games/"><u>2024 Approved  Narratives of the Bravest  Our Favorites in Adventure Games</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/ultimate-guidelines-to-help-you-use-vlc-media-player-better-for-2024/"><u>Ultimate Guidelines to Help You Use VLC Media Player Better for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/our-picks-for-the-finest-car-dvd-units-for-2024/"><u>Our Picks for the Finest Car DVD Units for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-is-ipogo-not-working-on-realme-11-pro-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Realme 11 Pro? Fixed | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/audience-market-leaders-in-youtubes-short-clips-downloads/"><u>Audience’ Market Leaders in YouTube's Short Clips Downloads</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ideal-15-mounts-and-tripods-compatible-with-gopro/"><u>In 2024, Ideal 15 Mounts and Tripods Compatible with GoPro</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/no-delays-you-can-now-see-your-shorts/"><u>No Delays! You Can Now See Your Shorts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>