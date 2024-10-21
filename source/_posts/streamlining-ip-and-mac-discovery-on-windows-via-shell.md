---
title: Streamlining IP & MAC Discovery on Windows via Shell
date: 2024-10-20T03:32:49.737Z
updated: 2024-10-20T22:13:28.530Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining IP & MAC Discovery on Windows via Shell
excerpt: This Article Describes Streamlining IP & MAC Discovery on Windows via Shell
keywords: IP-MAC Discovery,Window Shell Tools,Streamlined Detection,Shell Scripting Help,Network ID Finder,Windows Discover System,MAC Address Locator
thumbnail: https://thmb.techidaily.com/c7a57ea0c6d875a784d917881bf9f1dac3c811b03454856c62819bb5612b0808.jpg
---

## Streamlining IP & MAC Discovery on Windows via Shell

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
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043618/7443" target="_top" id="2043618">
  <img src="//a.impactradius-go.com/display-ad/7443-2043618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043618/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<span id="1983471">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983471%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983471/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-how-to-get-vids-to-autoplay-effortlessly-on-fb-for-2024/"><u>[New] How to Get Vids to Autoplay Effortlessly on FB for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-tecno-phantom-v-fold-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Tecno Phantom V Fold without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/easy-steps-to-fix-error-4013-your-ultimate-solution-for-iphone-updates-and-restores/"><u>Easy Steps to Fix Error 4013 - Your Ultimate Solution for iPhone Updates and Restores</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-window-file-tracking-on-windows/"><u>Effortless Window File Tracking on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-vision-to-reality-personal-animation-mastery-for-2024/"><u>From Vision to Reality Personal Animation Mastery for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-adapt-to-the-digital-age-mastering-computer-based-live-feeds-on-tiktok/"><u>In 2024, Adapt to the Digital Age Mastering Computer-Based Live Feeds on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/linux-alone-ditching-wsl/"><u>Linux Alone: Ditching WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-class-nullifying-stealthy-windows-apps/"><u>Master Class: Nullifying Stealthy Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-challenges-adapting-linux-subsystem-to-windows-11-upgrades/"><u>Overcoming Challenges: Adapting Linux Subsystem to Windows 11 Upgrades</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-stuttering-issues-solutions-to-prevent-warzone-20-from-crashing-on-windows-computers/"><u>Overcoming Stuttering Issues – Solutions to Prevent Warzone 2.0 From Crashing on Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-unterminate-program-issue-in-windows/"><u>Solutions to Unterminate Program Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-character-maps-unresponsiveness-in-windows-os/"><u>Troubleshooting Character Maps Unresponsiveness in Windows OS</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-infinix-hot-40-pro-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Infinix Hot 40 Pro? Here is How | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    