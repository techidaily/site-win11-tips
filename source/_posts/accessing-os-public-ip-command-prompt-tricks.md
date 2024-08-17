---
title: "Accessing OS Public IP: Command Prompt Tricks"
date: 2024-08-16T01:12:14.976Z
updated: 2024-08-17T01:12:14.976Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accessing OS Public IP: Command Prompt Tricks"
excerpt: "This Article Describes Accessing OS Public IP: Command Prompt Tricks"
keywords: OpenSSH Remote Access,Windows Public IP Guide,Command Line Network Tools,Bypass Firewall Commands,Custom Host Ports Setting,Advanced Command Prompt Skills,Troubleshoot OS Connectivity
thumbnail: https://thmb.techidaily.com/0d1e6d469f4667c3d31e2ee564e25a93a1f4e0a1835558608501c466657ed85d.png
---

## Accessing OS Public IP: Command Prompt Tricks

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

## How to Check Your Private IP Address on Windows

![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

 Windows offers multiple ways to view your network information, including the IP address. For instance, you can easily [check your IP address from the Settings app](https://www.makeuseof.com/tag/find-ip-address-windows-10/). You can also use the Network and Sharing Center in Control Panel or dig a little bit in the Task Manager’s Performance tab to access your system’s network details.

 But if you would rather skip multiple clicks and are comfortable with Command Prompt, the ipconfig (Internet Protocol configuration) command is all you need. It is easy to remember and shows more information quickly than the Settings app.

 Follow these steps to get your Private IP address using Command Prompt:

1. Press the **Win** key, and type **cmd**. From the search result, click on **Command Prompt**.
2. Next, type the following command in the Command Prompt window and press Enter:  
`ipconfig`
3. The output will display a host of network information. Look for the IPv4 address for your Ethernet or Wireless LAN adapter to identify your private IP address.
4. If you need complete information, including NetBIOS over TCPIP, DHCP status, and Physical IP address, use the following command instead:  
`Ipconfig /all`
5. You’ll likely see multiple network adapter entries with unique IP addresses. This is usually due to your computer having multiple network adapters, including Ethernet, Wireless LAN, and vEthernet switches.

 If you need to share the output for troubleshooting purposes, you can export the output to a text file. In Command Prompt, run **ipconfig > NetworkInfo.txt** to save the output to a **NetworkInfo.text** file. By default, it is saved to the **C:\\Users\\Username** directory.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Unlike the private IP address, the **ipconfig** command cannot retrieve the public IP address of your ISP. Instead, you’ll need to [use the curl command-line utility to make HTTP requests](https://www.makeuseof.com/curl-how-make-http-requests/) using a third-party service, like ifconfig.me, to obtain IP address mapping information.

 The newer versions of the OS, Windows 10 and 11, come with the curl utility built-in. If you are using an older version, you may need to install curl for Windows to run the utility.

 Follow these steps to get the public IP address using Command Prompt:

1. Press **Win + R**, type **cmd** and click **OK** to [open Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/)
2. Type the following command in the Command Prompt window and press Enter:  
`curl ifconfig.me`
3. The above command sends an HTTP request to the **ifconfig.me** server, which returns your public IP address information. Similarly, you can visit the **ifconfig.me** URL using your web browser to view your public IP address.
4. That said, if the **ifconfig.me** command doesn’t return a public IPv6 address, use the following command instead:  
`nslookup myip.opendns.com resolver1.opendns.com`
5. The above command uses the **nslookup** command-line utility to retrieve your public IP address using the OpenDNS service. Your public IPv6 address will look something like this 2401:\*\*00:1c08:55f0:594b:cdbe:\*\*\*\*.\*\*\*\*.

 If you check your public IPv6 address again after a few hours or days—depending on the router's configuration—you may notice a different IPv6 address. Due to privacy concerns, your router dynamically assigns and changes the IPv6 address for all connected devices.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-best-practices-in-yt-thumbnail-sizing/"><u>[New] 2024 Approved  Best Practices in YT Thumbnail Sizing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-enriching-the-instagram-experience-with-background-sounds-for-2024/"><u>[New] Enriching the Instagram Experience with Background Sounds for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-elevate-traffic-ethical-practices-for-amplifying-content-views/"><u>[Updated] 2024 Approved  Elevate Traffic  Ethical Practices for Amplifying Content Views</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-seamlessly-capture-and-store-your-favorite-episodes-on-iphone/"><u>2024 Approved  Seamlessly Capture and Store Your Favorite Episodes on iPhone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-poco-x5-pro-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Poco X5 Pro Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/6-cautionary-tales-of-reliance-on-artificial-brains/"><u>6 Cautionary Tales of Reliance on Artificial Brains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/best-choices-for-switchs-hd-gaming-for-2024/"><u>Best Choices for Switch's HD Gaming for 2024</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-infinix-hot-30i-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Infinix Hot 30i Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-writing-game-wins-finest-tools/"><u>Elevate Your Writing Game – Win's Finest Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-lightweight-browsers-for-chromeoswindowsmacos-ram-and-cpu-wise/"><u>Finding Lightweight Browsers for ChromeOS/Windows/macOS: RAM & CPU-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-system-ready-for-windows-11-with-our-top-3-usb-tips/"><u>Get Your System Ready for Windows 11 with Our Top 3 USB Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-terminal-and-quake-mode/"><u>Getting Started: Terminal & Quake Mode</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-honor-x8b-drfone-by-drfone-android/"><u>How to Screen Mirroring Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-streamline-note-taking-with-win-11-display-rules/"><u>How to Streamline Note-Taking with Win 11 Display Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unleash-your-typographic-vision-in-after-effects-mastery/"><u>In 2024, Unleash Your Typographic Vision in After Effects Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-comparison-dissecting-key-differences-between-local-and-microsoft-logins-in-os/"><u>In-Depth Comparison: Dissecting Key Differences Between Local & Microsoft Logins in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-immediate-folder-upload-tackling-onedrive-errors/"><u>Mastering Immediate Folder Upload: Tackling OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mobile-file-access-via-windows-server/"><u>Mobile File Access via Windows Server</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-future-microsofts-copilot-key-and-windows-11-revolution/"><u>Navigating the Future: Microsoft's Copilot Key and Windows 11 Revolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-disconnection-dxgi-error-guide/"><u>Overcoming Device Disconnection: DXGI Error Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vmware-crashes-a-guide-for-win11-users/"><u>Overcoming VMware Crashes: A Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinventing-win11s-configuration-interface/"><u>Reinventing Win11's Configuration Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-the-start-page-to-a-new-preference-in-win11/"><u>Revising the Start Page to a New Preference in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-strategies-windows-voice-logging/"><u>Step-by-Step Strategies: Windows Voice Logging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-multitasking-enhancing-windows-11-widget-capabilities/"><u>Streamlining Multitasking: Enhancing Windows 11 Widget Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-app-experience-win11-color-automation/"><u>Tailoring Your App Experience: Win11 Color Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-prolong-pin-length-for-enhanced-safety/"><u>Tips to Prolong PIN Length for Enhanced Safety</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricking-eyes-vanish-taskbar-search-in-windows-11/"><u>Tricking Eyes: Vanish Taskbar Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-of-sandbox-with-win-11/"><u>Unleashing the Power of Sandbox with Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ip-and-mac-info-with-windows-powershell/"><u>Unraveling IP and MAC Info with Windows Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-stronger-side-why-you-should-opt-for-win11/"><u>Unveiling the Stronger Side: Why You Should Opt for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/w11-addressing-undetected-additional-monitor/"><u>W11: Addressing Undetected Additional Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-compatibility-tips-synapse-reinstatement-guide/"><u>Win Compatibility Tips: Synapse Reinstatement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-roblox-needs-to-close-windows-errors/"><u>Winning Against Roblox Needs to Close Windows Errors</u></a></li>
</ul></div>
