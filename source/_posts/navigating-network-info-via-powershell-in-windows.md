---
title: Navigating Network Info via PowerShell in Windows
date: 2024-09-21T17:43:07.363Z
updated: 2024-09-28T16:57:30.941Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Network Info via PowerShell in Windows
excerpt: This Article Describes Navigating Network Info via PowerShell in Windows
keywords: PowerShell for Nets,Win-Based NetInfo,PC Network Insight,PS Network Command,Windows Networks Pow,PowerNet Info Tools,Windows Data Navigation
thumbnail: https://thmb.techidaily.com/d2f76001c4f2646491c0fc840a81d8218602e492050e0d16896d960da5c49a16.png
---

## Navigating Network Info via PowerShell in Windows

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
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/new-mastering-video-thumbnail-creation-for-maximum-clicks/"><u>[New] Mastering Video Thumbnail Creation for Maximum Clicks</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-vigor-in-voice-assessment-version-8-for-2024/"><u>[Updated] Vigor in Voice Assessment Version 8 for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-sound-studio-everything-about-the-sound-recording-studio-mac/"><u>2024 Approved Sound Studio - Everything About the Sound Recording Studio Mac</u></a></li>
<li><a href="https://discover-help.techidaily.com/como-comprimir-un-video-de-gran-tamano-para-whatsapp-sin-perder-la-calidad-guia-completa/"><u>Cómo Comprimir Un Video De Gran Tamaño Para WhatsApp Sin Perder La Calidad: Guía Completa</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-7-steps-to-missing-windows-add-ons/"><u>Enhancing User Experience: 7 Steps to Missing Windows Add-Ons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-default-windows-backup-reset/"><u>Guiding Through Default Windows Backup Reset</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-iphone-6-plus-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On iPhone 6 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-to-peak-ssd-performance-win-and-fresh-methods/"><u>Leap to Peak SSD Performance: Win and Fresh Methods</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-oneplus-11-5g-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your OnePlus 11 5G Phone Now with These Tips</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-correction-clear-legends-crashes/"><u>Quick Correction: Clear Legends Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-to-customizing-the-desktop-menu/"><u>The Insider's Guide to Customizing the Desktop Menu</u></a></li>
<li><a href="https://buynow-help.techidaily.com/ultimate-guide-choosing-durable-and-stylish-cases-for-your-google-pixel-8-device/"><u>Ultimate Guide: Choosing Durable and Stylish Cases for Your Google Pixel 8 Device</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-shorts-demystified-in-30-minutes/"><u>YouTube Shorts Demystified in 30 Minutes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    