---
title: "Unveiling System Details: Locate Windows' IP and MAC via Powershell"
date: 2024-06-25T16:40:44.766Z
updated: 2024-06-26T16:40:44.766Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling System Details: Locate Windows' IP and MAC via Powershell"
excerpt: "This Article Describes Unveiling System Details: Locate Windows' IP and MAC via Powershell"
keywords: Find Windows IP Powershell,Windows MAC Address Command,Win IP Location Scripting,PoweShell IP Detailing,Locate Mac Windows PS,PowerShell Windows Details,Extract Windows Ip Info
thumbnail: https://thmb.techidaily.com/16367f6c60ce9653f1392a643e2b82dc02b50b35ff890c97d3a0607584104c84.jpg
---

## Unveiling System Details: Locate Windows' IP and MAC via Powershell

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

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

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/enhance-file-management-engage-filters-with-checkbox-on-win11/"><u>Enhance File Management: Engage Filters with Checkbox on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purple-pandemonium-restore-your-pcs-color-calibration/"><u>Purple Pandemonium? Restore Your PC's Color Calibration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhome-explained-mastering-windows-11-upgrades/"><u>DevHome Explained: Mastering Windows 11 Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx939-dll-in-win11/"><u>Addressing Missing D3DX9_39 DLL in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/traverse-backward-commanding-windows-11-history/"><u>Traverse Backward: Commanding Windows 11 History</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-error-unsigned-update-files-fix-guide/"><u>Windows Error: Unsigned Update Files; Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-safety-invest-heavily-in-research-to-develop-advanced-safety-features-that-reduce-potential-risks-associated-with-drone-operations-such-as-collis31/"><u>Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-manual-for-chrome-and-windows-11/"><u>The Ultimate Manual for Chrome and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-widespread-connectivity-problem-in-steam-windows-11/"><u>Resolving Widespread Connectivity Problem in Steam Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-maximizing-view-quality-on-team-meetings-in-ms-teams/"><u>[New] In 2024, Maximizing View Quality on Team Meetings in MS Teams</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-confused-about-deciding-the-next-destination-for-your-trip-this-article-features-some-of-the-best-vloggers-you-can-find-for-gaining-inspiration-for-/"><u>In 2024, Confused About Deciding the Next Destination for Your Trip? This Article Features some of the Best Vloggers You Can Find for Gaining Inspiration for Traveling</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-snapping-with-style-a-guide-to-cartoon-faces-in-snapchat/"><u>2024 Approved  Snapping with Style  A Guide to Cartoon Faces in Snapchat</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-fashioning-a-footprint-fonts-for-visual-stories-in-ae/"><u>In 2024, Fashioning a Footprint  Fonts for Visual Stories in AE</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-compactscreengrab-critique-report/"><u>[Updated] CompactScreenGrab Critique Report</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-becoming-a-master-at-creating-flattering-discord-pfps/"><u>2024 Approved  Becoming a Master at Creating Flattering Discord PFPs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-bringing-your-instagram-aesthetic-to-life-with-square-videos-in-imovie-for-2024/"><u>[Updated] Bringing Your Instagram Aesthetic to Life with Square Videos in iMovie for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-professional-desktop-image-merging-tips/"><u>[Updated] Professional Desktop Image Merging Tips</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-becoming-an-exclusive-guest-on-tiktok-live/"><u>In 2024, Becoming an Exclusive Guest on TikTok Live</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>