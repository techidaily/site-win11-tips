---
title: Crafty Tricks for Extracting Network Info in Windows PS
date: 2024-10-01T00:05:58.008Z
updated: 2024-10-03T22:58:07.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Crafty Tricks for Extracting Network Info in Windows PS
excerpt: This Article Describes Crafty Tricks for Extracting Network Info in Windows PS
keywords: WinPSNetworkInfo,DataExtractionWin,PSSecurityLeak,OSHackPSTools,WindowsNetworkSnoop,PsExtractDataWin,SneakyWindowsTricks
thumbnail: https://thmb.techidaily.com/b419546ab6fdd218d829eb22a844376fcf0d2afcf21c79595fda949de5f6b103.jpg
---

## Crafty Tricks for Extracting Network Info in Windows PS

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087395/7443" target="_top" id="2087395">
  <img src="//a.impactradius-go.com/display-ad/7443-2087395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087395/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/2024-approved-the-insiders-guide-to-ultimate-audio-equipment/"><u>2024 Approved The Insider's Guide to Ultimate Audio Equipment</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-realme-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Realme Fingerprint Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-compromised-windows-defense-in-win-11/"><u>Correcting Compromised Windows Defense in Win 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/diy-repair-correcting-joystick-drift-in-playstation-5-controllers-with-easy-fixes/"><u>DIY Repair: Correcting Joystick Drift in PlayStation 5 Controllers with Easy Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-linux-setup-not-wsl/"><u>Efficient Linux Setup, Not WSL</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-dialer-feature-win-11/"><u>How to Engage Dialer Feature Win 11</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-tecno-pop-7-pro-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Tecno Pop 7 Pro Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-error-win11s-uptime-failure-code-0x80246007/"><u>How to Reset Error: Win11’s Uptime Failure, Code 0X80246007</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-vivo-y100-5g-drfone-by-drfone-android/"><u>How to Screen Mirroring Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6s-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6s To Other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-points-preparing-for-a-full-system-reinstallation/"><u>Key Points: Preparing for a Full System Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-hurdle-opening-windows-folders-via-double-click/"><u>Overcoming the Hurdle: Opening Windows' Folders via Double-Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-grades-essential-tips-for-efficient-windows-learning/"><u>Skyrocket Your Grades: Essential Tips for Efficient Windows Learning</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-clearing-your-browser-history-on-microsoft-edge/"><u>Step-by-Step Guide: Clearing Your Browser History on Microsoft Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-correction-winoss-parsing-error-0exc00ce556/"><u>Swift Correction: WinOSs Parsing Error 0eXC00CE556</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-choice-selecting-quality-bittorrent-clients/"><u>The Best Choice: Selecting Quality BitTorrent Clients</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-clearing-and-maintaining-your-3d-printers-nozzle/"><u>Ultimate Guide: Clearing & Maintaining Your 3D Printer's Nozzle</u></a></li>
<li><a href="https://article-tips.techidaily.com/unveiling-drone-excellence-the-q500-experience/"><u>Unveiling Drone Excellence The Q500 Experience</u></a></li>
</ul></div>

