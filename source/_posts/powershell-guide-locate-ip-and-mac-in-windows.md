---
title: "PowerShell Guide: Locate IP and MAC in Windows"
date: 2024-11-11T17:42:31.296Z
updated: 2024-11-17T19:51:30.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes PowerShell Guide: Locate IP and MAC in Windows"
excerpt: "This Article Describes PowerShell Guide: Locate IP and MAC in Windows"
keywords: PowerShell Networking Tips,Mac Address Extraction PS,IP Search via PowerShell,Windows Device Info Query,Essential PowerShell Commands,Locate MAC Address Scripts,Find Windows IP Details Guide
thumbnail: https://thmb.techidaily.com/a3a2d9a996d9eb1a5a7f44f59aadc7d2130837ea4123069d71208845b762ea4c.jpg
---

## PowerShell Guide: Locate IP and MAC in Windows

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
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037334/7443" target="_top" id="2037334">
  <img src="//a.impactradius-go.com/display-ad/7443-2037334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037334/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/new-leveraging-video-conferencing-a-guide-to-zipping-up-zoom-and-gmail-integration/"><u>[New] Leveraging Video Conferencing A Guide to Zipping Up Zoom and Gmail Integration</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/winx-mediatrans-iphoneipadipod-and-pcwindows10/"><u>『公式』WinX MediaTrans - 高性能デバイス間iPhone/iPad/iPodデータ管理 & セキュアバックアップ！PCとの転送簡単化、Windows(10)互換</u></a></li>
<li><a href="https://app-tips.techidaily.com/before-microsoft-drops-support-for-windows-explore-five-essential-alternatives-to-keep-your-pc-running-smoothly/"><u>Before Microsoft Drops Support for Windows # : Explore Five Essential Alternatives to Keep Your PC Running Smoothly.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-wacatacbml-symptoms-and-solutions-for-windows-malware-woes/"><u>Decode Wacatac.B!ml: Symptoms & Solutions for Windows Malware Woes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-solving-high-msmpeng-cpu-usage-on-windows-11-step-by-step/"><u>Diagnosing and Solving High MsMpEng CPU Usage on Windows 11 – Step by Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-life-with-premium-windows-software/"><u>Enhance Life with Premium Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-or-block-other-wi-fi-networks-on-windows/"><u>How to Hide or Block Other Wi-Fi Networks on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-oppo-a1-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Oppo A1 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-graphics-fixes-for-gta-v-solving-the-errgfxd3dinit-error/"><u>Mastering Graphics Fixes for GTA V: Solving the ERR_GFX_D3D_INIT Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-zerox-error-at-keyboard-input/"><u>Overcoming Windows 11'S Zerox Error at Keyboard Input</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-operation-requirements-and-error-740-on-windows-11/"><u>Quick Fixes for Operation Requirements and Error 740 on Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/record-games-with-no-hassle-nvidia-way-for-2024/"><u>Record Games with No Hassle - NVIDIA Way for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/seeking-authentic-ps2-play-check-out-the-5-best-android-simulators-for-2024/"><u>Seeking Authentic PS2 Play? Check Out the 5 Best Android Simulators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-and-fixing-windows-discord-query-mechanism/"><u>Streamlining and Fixing Windows' Discord Query Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-clean-slate-three-methods/"><u>The Ultimate Windows Clean Slate: Three Methods</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-rated-ultrabook-and-luxury-laptop-picks-of-2024/"><u>Top-Rated Ultrabook & Luxury Laptop Picks of 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-covert-software-on-your-pc/"><u>Uncovering Covert Software on Your PC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unleashing-your-funny-bone-a-stepwise-guide-to-making-memes-on-9gag/"><u>Unleashing Your Funny Bone A Stepwise Guide to Making Memes on 9GAG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-win11-potential-installing-powertoys/"><u>Unlock Win11 Potential - Installing PowerToys</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    