---
title: Crafty Tricks for Extracting Network Info in Windows PS
date: 2024-09-10T21:57:24.499Z
updated: 2024-09-16T21:41:30.909Z
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

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-art-of-lenovos-video-screen-capture/"><u>[New] 2024 Approved The Art of Lenovo's Video Screen Capture</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-exploring-differences-between-igtv-and-youtube-for-effective-posts/"><u>[New] In 2024, Exploring Differences Between IGTV and YouTube for Effective Posts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-zero-price-screen-recording-easy-on-pc-and-mac-for-2024/"><u>[New] Zero Price Screen Recording - Easy on PC & Mac for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-functionality-to-flair-windows-10s-transition-to-11/"><u>From Functionality to Flair: Windows 10'S Transition to 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-an-end-task-option-on-the-windows-11-taskbar/"><u>How to Enable an End Task Option on the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shortcuts-for-skipping-windows-sign-in-requirements/"><u>Shortcuts for Skipping Windows Sign-In Requirements</u></a></li>
<li><a href="https://extra-support.techidaily.com/sky-high-savings-the-least-expensive-drones-on-market-for-2024/"><u>Sky-High Savings The Least Expensive Drones on Market for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    