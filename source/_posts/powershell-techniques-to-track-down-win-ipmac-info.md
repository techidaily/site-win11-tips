---
title: PowerShell Techniques to Track Down Win IP/MAC Info
date: 2024-12-23T22:03:24.601Z
updated: 2024-12-27T17:22:36.461Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-approaches.techidaily.com/updated-intro-magic-unmatched-editors-across-all-tech/"><u>[Updated] Intro Magic Unmatched Editors Across All Tech</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-the-quick-route-to-joy-embracing-the-ifunny-meme-app/"><u>[Updated] The Quick Route to Joy Embracing the iFunny Meme App</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-achieving-excellence-in-your-android-video-brightness/"><u>2024 Approved Achieving Excellence in Your Android Video Brightness</u></a></li>
<li><a href="https://win-solutions.techidaily.com/enhancements-in-windows-11-update-installation-process/"><u>Enhancements in Windows 11 Update Installation Process</u></a></li>
<li><a href="https://games-able.techidaily.com/google-play-pass-a-steal-yet-not-perfect/"><u>Google Play Pass - A Steal, Yet Not Perfect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-at-snipeits-stalling-fast-fixes-to-jumpstart-it/"><u>Halt at SnipeIt's Stalling? Fast Fixes to Jumpstart It</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-visions-of-the-future-the-historical-vr-journey/"><u>In 2024, Visions of the Future The Historical VR Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-disconnection-quick-fix-for-xbox-win11-app/"><u>Navigating Through Disconnection: Quick Fix for Xbox Win11 App</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-y78plus-t1-edition-by-fonelab-android-recover-data/"><u>Recover lost data from Y78+ (T1) Edition</u></a></li>
<li><a href="https://fox-pages.techidaily.com/step-by-step-tutorial-safeguard-phone-numbers-and-emails-by-transferring-contacts-to-google-drive-latest-version/"><u>Step-by-Step Tutorial: Safeguard Phone Numbers and Emails by Transferring Contacts to Google Drive (Latest Version)</u></a></li>
<li><a href="https://extra-information.techidaily.com/tale-bearers-school-distinguished-dothee/"><u>Tale Bearers School - Distinguished Dothee</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-pathway-through-frozen-windows-update-woes/"><u>The Pathway Through Frozen Windows Update Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-bluetooth-troubleshooting-music-only-lacking-volumecontrols/"><u>Windows Bluetooth Troubleshooting: Music Only Lacking Volume/Controls</u></a></li>
</ul></div>

