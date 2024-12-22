---
title: "Quick Guide: Fetching IP & MAC Addresses, Windows-Wise"
date: 2024-12-16T22:27:33.390Z
updated: 2024-12-21T19:34:06.952Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Guide: Fetching IP & MAC Addresses, Windows-Wise"
excerpt: "This Article Describes Quick Guide: Fetching IP & MAC Addresses, Windows-Wise"
keywords: Win_IPAddressGuide,MacAddrWindowsTip,IPMACWinFind,AccessWindowsMAC,FindIPMACWindows,MACIDWiseSearch,WindowsIPMACQuick
thumbnail: https://thmb.techidaily.com/1d9ebf5bb7f01c1686988d2dbf12477c216dfe196b34a2ea4b98d961a480d427.jpg
---

## Quick Guide: Fetching IP & MAC Addresses, Windows-Wise

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-info.techidaily.com/new-frame-loss-enigma-why-are-videos-cropped-by-imovie/"><u>[New] Frame Loss Enigma Why Are Videos Cropped by iMovie?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-dissonant-designs-mastering-on-a-mac/"><u>[New] In 2024, Dissonant Designs Mastering on a Mac</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-beginners-blueprint-for-initiating-instagram-discussions/"><u>2024 Approved Beginner's Blueprint for Initiating Instagram Discussions</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-the-complete-obs-guide-to-skype-call-recording/"><u>2024 Approved The Complete OBS Guide to Skype Call Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-access-controls-for-standard-windows-users/"><u>Customizing Access Controls for Standard Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-digital-deceit-unmasking-fakes-in-windows-store-apps/"><u>Deciphering Digital Deceit: Unmasking Fakes in Windows Store Apps</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-videos-and-music-files-from-iphone-12-mini-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Photos, Videos & Music Files from iPhone 12 mini | Stellar</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-accelerated-learning-quick-start-to-becoming-a-lut-expert/"><u>In 2024, Accelerated Learning Quick Start to Becoming a LUT Expert</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-analysis-the-best-features-of-anthropicss-smart-photo-editing-suite/"><u>In-Depth Analysis: The Best Features of Anthropics's Smart Photo Editing Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-microsoft-store-fault-code-0x80073cf3-on-win11/"><u>Mending Microsoft Store Fault Code 0X80073cf3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/patch-up-the-net-framework-on-windows-efficiently-max-156/"><u>Patch Up the .NET Framework on Windows Efficiently (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pivotal-points-a-roadmap-for-system-refreshment/"><u>Pivotal Points: A Roadmap for System Refreshment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-approach-to-rectify-device-not-found-in-virtualbox/"><u>Stepwise Approach to Rectify 'Device Not Found' In VirtualBox</u></a></li>
<li><a href="https://discover-great.techidaily.com/taming-high-server-load-yl-softwares-guide-to-optimizing-your-processor-usage/"><u>Taming High Server Load: YL Software's Guide to Optimizing Your Processor Usage</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-smartest-way-to-engage-with-chatgpt-a-must-have-chrome-enhancement/"><u>The Smartest Way to Engage with ChatGPT - A Must-Have Chrome Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-customizing-windows-11-notepad/"><u>The Ultimate Guide to Customizing Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-update-fiasco-defeat-0x800736cc/"><u>Troubleshooting Windows Update Fiasco: Defeat 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-terminal-reboot-return-to-standard/"><u>Win11 Terminal Reboot: Return To Standard</u></a></li>
</ul></div>

