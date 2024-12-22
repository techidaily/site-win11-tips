---
title: "Step-by-Step Guide: Extracting IP/MAC Using PS on PCs"
date: 2024-12-15T05:11:30.085Z
updated: 2024-12-22T07:09:53.026Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step Guide: Extracting IP/MAC Using PS on PCs"
excerpt: "This Article Describes Step-by-Step Guide: Extracting IP/MAC Using PS on PCs"
keywords: IP Extraction PS Guide,MAC Address PS,PS Extraction Steps,PC IP Retrieval,Networking PS Tutorial,MAC PS Extract,PS IP/MAC Guide
thumbnail: https://thmb.techidaily.com/0e8ec29ee6248aac03a17afe8cf5cfd2ec9d4e36dfc8648cae868f4622fb576a.jpg
---

## Step-by-Step Guide: Extracting IP/MAC Using PS on PCs

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-syncing-tiktok-content-with-twitter/"><u>[New] In 2024, Syncing TikTok Content with Twitter</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/nranked-movies-the-real-top-picks/"><u>[New] Unranked Movies The Real Top Picks</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-visualediting-deep-dive-comprehensive-article-on-androvid/"><u>[Updated] In 2024, VisualEditing Deep Dive – Comprehensive Article on AndroVid</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-metaverse-persona-design-a-beginners-compreraniary-guide/"><u>[Updated] Metaverse Persona Design A Beginner's Compreraniary Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-the-newest-titans-apple-iphone-15-pro-versus-pro-max/"><u>Comparing the Newest Titans: Apple iPhone 15 Pro versus Pro Max</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-probing-the-capabilities-of-ffmpeg-in-maintaining-audible-formats/"><u>In 2024, Probing the Capabilities of FFmpeg in Maintaining Audible Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-windows-portable-computing/"><u>Innovative Windows Portable Computing</u></a></li>
<li><a href="https://win-hot.techidaily.com/mastering-time-lapse-photography-simple-strategies-for-seamlessly-documenting-your-projects/"><u>Mastering Time-Lapse Photography: Simple Strategies for Seamlessly Documenting Your Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-uac-screenshots-on-pc/"><u>Mastering UAC Screenshots on PC</u></a></li>
<li><a href="https://extra-information.techidaily.com/set-the-mood-music-for-whatsapp-status/"><u>Set the Mood Music for WhatsApp Status</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/step-by-step-guide-recovering-accidentally-deleted-items-from-your-microsoft-onedrive/"><u>Step-by-Step Guide: Recovering Accidentally Deleted Items From Your Microsoft OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-how-to-for-efficiently-updating-your-windows-11-amd-drivers/"><u>The Ultimate How-To for Efficiently Updating Your Windows 11 AMD Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/which-win-pkg-tool-triumphs-choco-vs-wslm-analysis/"><u>Which Win Pkg Tool Triumphs? Choco VS. WSLM Analysis</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Vivo X100 | Dr.fone</u></a></li>
</ul></div>

