---
title: Uncovering Windows IP & MAC with PowerShell
date: 2024-10-28T18:19:03.558Z
updated: 2024-11-01T18:20:58.339Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uncovering Windows IP & MAC with PowerShell
excerpt: This Article Describes Uncovering Windows IP & MAC with PowerShell
keywords: Find Windows IP Address,Locate Mac Address in WS,PowerShell Get Device Info,Extract Windows Network Details,Obtain MAC Address via PS,Retrieve PC IP with Powershell,Identify Computer IP & MAC
thumbnail: https://thmb.techidaily.com/d1308294694574ea6db8acba4a99168df2eb7c1da8079de3619058fd0f089920.jpg
---

## Uncovering Windows IP & MAC with PowerShell

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
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136626/26400" target="_top" id="2136626">
  <img src="//a.impactradius-go.com/display-ad/26400-2136626" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136626/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-sharing-videos-on-tweet-no-retweets-just-phones/"><u>[New] 2024 Approved Sharing Videos on Tweet No Retweets, Just Phones</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-drone-dynamics-a-thorough-gopro-karma-examination/"><u>[Updated] Drone Dynamics A Thorough GoPro Karma Examination</u></a></li>
<li><a href="https://discover-blog.techidaily.com/comparing-process-intelligence-and-business-intelligence-key-differences-explained/"><u>Comparing Process Intelligence and Business Intelligence: Key Differences Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-hiccups-fixing-slow-playback-in-vlc/"><u>Eliminating Hiccups: Fixing Slow Playback in VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-insight-on-locating-windows-1110-product-key/"><u>Exclusive Insight on Locating Windows 11/10 Product Key</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-xiaomi-13-ultra-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Xiaomi 13 Ultra Location on Viber | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-infinix-smart-8-hd-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Infinix Smart 8 HD Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-over-disabled-router-settings-on-windows/"><u>Regaining Control over Disabled Router Settings on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/simplifying-the-world-of-ifunnys-meme-application-for-2024/"><u>Simplifying the World of iFunny's Meme Application for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/taste-the-pandemonium-in-depth-analysis-and-review-of-overcooked-2/"><u>Taste the Pandemonium: In-Depth Analysis and Review of Overcooked! 2</u></a></li>
<li><a href="https://games-able.techidaily.com/the-evolution-of-smoother-gaming-introducing-nvidia-g-sync/"><u>The Evolution of Smoother Gaming: Introducing Nvidia G-Sync</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-inaccessible-file-permissions/"><u>Troubleshooting Windows' Inaccessible File Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-are-windows-update-and-update-orchestrator-services/"><u>What Are Windows Update and Update Orchestrator Services?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-innovative-color-design/"><u>Windows Terminal: Innovative Color Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winos-tricks-for-program-stability/"><u>WinOS Tricks for Program Stability</u></a></li>
</ul></div>

