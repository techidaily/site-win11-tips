---
title: Mastering IP & MAC Extraction in Windows with PowerShell
date: 2024-10-29T19:07:11.498Z
updated: 2024-11-01T18:06:40.915Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering IP & MAC Extraction in Windows with PowerShell
excerpt: This Article Describes Mastering IP & MAC Extraction in Windows with PowerShell
keywords: PowerShell Network Extraction,MAC Address Retrieval PS,IP Info Extract PS,OS IP/MAC Scripting,WinOS Extract IPs,PowerShell MAC Tools,Windows NETSH Command
thumbnail: https://thmb.techidaily.com/0553b37a2d0bfe56c6f7794ae22609d4c46a2b30d090cb5ced8396683e115022.jpg
---

## Mastering IP & MAC Extraction in Windows with PowerShell

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
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123726/7443" target="_top" id="2123726">
  <img src="//a.impactradius-go.com/display-ad/7443-2123726" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123726/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-iphone-videography-elevated-8-key-techniques-for-professional-recordings/"><u>[New] IPhone Videography Elevated 8 Key Techniques for Professional Recordings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-detailed-steps-to-using-azure-speech-recognition/"><u>[Updated] Detailed Steps to Using Azure Speech Recognition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wmamov-movavi/"><u>網站直接免費自動轉化WMA到MOV - Movavi無損格式轉換器</u></a></li>
<li><a href="https://article-posts.techidaily.com/chromatic-mastery-bridging-theory-and-art/"><u>Chromatic Mastery Bridging Theory and Art</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-google-pixel-fold-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from Google Pixel Fold?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-navigating-zoom-recordings-for-business-success/"><u>In 2024, Navigating Zoom Recordings for Business Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-online-mp3-to-m4r-service-convert-your-songs-free/"><u>Movavi's Online MP3-to-M4R Service - Convert Your Songs Free!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-audio-formats-effortlessly-convert-m4a-to-m4v-at-no-cost-via-web-services/"><u>Switching Audio Formats Effortlessly - Convert M4A to M4V at No Cost via Web Services</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/vsr-video-vaulter-reviews-comprehensive-guide/"><u>VSR Video Vaulter Reviews Comprehensive Guide</u></a></li>
<li><a href="https://buynow-help.techidaily.com/xbox-series-s-evaluation-astonishing-tech-in-compact-design/"><u>Xbox Series S Evaluation: Astonishing Tech in Compact Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gif-muvavi/"><u>オンラインで簡単にGIFファイルを無料変換 - Muvavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    