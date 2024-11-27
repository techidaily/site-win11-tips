---
title: "PowerShell Guide: Locate IP and MAC in Windows"
date: 2024-11-20T16:06:06.682Z
updated: 2024-11-27T17:27:40.725Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://easy-unlock-android.techidaily.com/7-ways-to-unlock-a-locked-oneplus-nord-n30-se-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked OnePlus Nord N30 SE Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726225497208-gif-mp4-movavi/"><u>在線無限制地自由轉換 GIF成 MP4 - 使用Movavi技術</u></a></li>
<li><a href="https://win-tips.techidaily.com/connecting-an-ipad-to-your-pc-comprehensive-tutorial-on-extending-windows-screens-with-apple-tablets/"><u>Connecting an iPad to Your PC: Comprehensive Tutorial on Extending Windows Screens with Apple Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-gratuite-de-fichiers-mp3-vers-mkv-en-ligne-avec-movavi-guide-complet/"><u>Conversion Gratuite De Fichiers MP3 Vers MKV en Ligne Avec Movavi - Guide Complet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convertissez-vos-fichiers-mov-en-format-m4v-pour-le-web-gratuitement-avec-movavi/"><u>Convertissez Vos Fichiers MOV en Format M4V Pour Le Web Gratuitement Avec Movavi</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/effortless-memes-using-kinemaster-101/"><u>Effortless Memes Using KineMaster 101</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-resolving-windows-update-malfunctions-a-step-by-step-approach/"><u>Guide To Resolving Windows Update Malfunctions - A Step-By-Step Approach</u></a></li>
<li><a href="https://sound-issues.techidaily.com/hearthstone-troubleshooting-eliminating-the-games-noise-problem-once-and-for-all/"><u>Hearthstone Troubleshooting: Eliminating the Game's Noise Problem Once and For All</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-ancient-aesthetics-public-domain-pieces/"><u>In 2024, Ancient Aesthetics Public Domain Pieces</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-realme-11x-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Realme 11X 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726219698839-movavi/"><u>Movaviの返品ポリシー:お客様向けガイド</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-video-edit-suite-accelerate-your-edits-using-fastclip-master-edition/"><u>Rapid Video Edit Suite - Accelerate Your Edits Using FastClip Master Edition</u></a></li>
<li><a href="https://program-issues.techidaily.com/steam-friendship-dilemma-regaining-connection-with-a-comprehensive-fix/"><u>Steam Friendship Dilemma: Regaining Connection with a Comprehensive Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-11-software-solutions-for-editing-mp4-files-on-windows-and-mac-systems/"><u>The Best 11 Software Solutions for Editing MP4 Files on Windows & Mac Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-le-tue-immagini-in-gif-o-png-con-due-clic-usando-il-convertitore-multimediali-rapido-di-movavi/"><u>Trasforma Le Tue Immagini in GIF O PNG Con Due Clic Usando Il Convertitore Multimediali Rapido Di Movavi</u></a></li>
</ul></div>

