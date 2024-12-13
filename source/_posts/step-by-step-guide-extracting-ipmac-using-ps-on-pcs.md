---
title: "Step-by-Step Guide: Extracting IP/MAC Using PS on PCs"
date: 2024-12-11T23:01:32.277Z
updated: 2024-12-13T00:40:53.845Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-the-art-of-rebranding-online-expert-tips-for-transforming-your-tiktok-username/"><u>[New] In 2024, The Art of Rebranding Online Expert Tips for Transforming Your TikTok Username</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-staying-grounded-in-vr-worlds/"><u>[New] Staying Grounded in VR Worlds</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-live-stream-titans-duel-comparative-exploration-of-twitch-and-youtube/"><u>[Updated] 2024 Approved Live-Stream Titans Duel Comparative Exploration of Twitch & YouTube</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-first-home-frontier-top-6-beginner-friendly-mc-abodes/"><u>[Updated] First Home Frontier Top 6 Beginner-Friendly MC Abodes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-in-class-subtitle-converters-revealed-transform-sub-into-srtr-in-minutes-not-hours-for-2024/"><u>Best-in-Class Subtitle Converters Revealed Transform SUB Into SRTR in Minutes, Not Hours for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversione-gratuita-online-da-3gp-a-mjpeg-con-movavi/"><u>Conversione Gratuita Online: Da 3GP a MJPEG Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-classroom-assets-explore-the-ultimate-guide-of-30-top-rated-teacher-resources-on-movavi-channel/"><u>Essential Classroom Assets: Explore the Ultimate Guide of 30 Top-Rated Teacher Resources on Movavi Channel</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-incorporating-natural-language-processing-siri-into-your-tiktok-strategy/"><u>In 2024, Incorporating Natural Language Processing (Siri) Into Your TikTok Strategy</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-the-meme-craft-kinemasters-role/"><u>In 2024, Mastering the Meme Craft KineMaster's Role</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-online-transforma-tus-archivos-flac-a-ogg-sin-costo-alguno/"><u>Movavi Online: Transforma Tus Archivos FLAC a Ogg Sin Costo Alguno</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-cost-free-tool-transforming-dpx-photos-into-png-format-online/"><u>Movavi's Cost-Free Tool: Transforming DPX Photos Into PNG Format Online</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/navigating-the-features-of-anthropics-smart-photo-editor-a-detailed-assessment/"><u>Navigating the Features of Anthropics Smart Photo Editor - A Detailed Assessment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-high-quality-streaming-audio-devices-reviewed-by-movavi/"><u>Top 10 High-Quality Streaming Audio Devices - Reviewed by Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-13-aplicativos-de-captura-de-webcam-mais-usados-para-windows-10-guia-do-movavi/"><u>Top 13 Aplicativos De Captura De Webcam Mais Usados Para Windows 10 - Guia Do Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-file-swf-in-formato-mp4-libero-e-gratuito-tramite-il-servizio-online-di-movavi/"><u>Trasforma I Tuoi File SWF in Formato MP4 Libero E Gratuito Tramite Il Servizio Online Di Movavi</u></a></li>
<li><a href="https://driver-install.techidaily.com/uefi-me-driver-for-windows-oses/"><u>UEFI ME Driver for Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wmawmv-movavi/"><u>WMAおよびWMVファイルの自由なオンライン変換 - Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    