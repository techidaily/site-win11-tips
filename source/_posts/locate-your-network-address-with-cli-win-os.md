---
title: Locate Your Network Address with CLI, Win OS
date: 2024-09-21T18:04:51.375Z
updated: 2024-09-28T18:17:45.814Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Locate Your Network Address with CLI, Win OS
excerpt: This Article Describes Locate Your Network Address with CLI, Win OS
keywords: CLI Network Locator,Win OS IP Address,Command Line Interface Search,Find Windows Local IP,CLI Online Address Finder,OS Network Identification,CLI Windows IP Detection
thumbnail: https://thmb.techidaily.com/3dc1e13d990f9f4ed1b30979889fa15d157b3da05c97d832955a545581c7804d.jpg
---

## Locate Your Network Address with CLI, Win OS

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/new-effortless-transition-from-spotify-to-youtube-find-the-best-apps/"><u>[New] Effortless Transition From Spotify to YouTube Find the Best Apps</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-full-spectrum-analysis-unpacking-xstudio-video-workshop-essentials/"><u>[New] Full Spectrum Analysis Unpacking XStudio Video Workshop Essentials</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ncover-beats-shortcut-musical-roles-for-2024/"><u>[New] Uncover Beats Shortcut Musical Roles for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-best-vistas-backgrounds-boosting-live-quality/"><u>[Updated] 2024 Approved Best Vistas Backgrounds Boosting Live Quality</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-discover-free-and-paid-luts-for-profound-canon-camera-effects/"><u>[Updated] 2024 Approved Discover Free & Paid LUTs for Profound Canon Camera Effects</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-20-best-anime-opening-songs-of-all-time/"><u>2024 Approved 20 Best Anime Opening Songs of All Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-dilemran-of-winscripterrors/"><u>Deciphering the Dilemran of WinScriptErrors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-full-use-of-the-control-key-in-windows-11/"><u>Enabling Full Use of the Control Key in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-oppo-reno-11-5g-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Oppo Reno 11 5G without App | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Lava Blaze 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-editing-mastery-in-fcp-5-advanced-techniques-to-transform-your-videos/"><u>New 2024 Approved Editing Mastery in FCP 5 Advanced Techniques to Transform Your Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ftdibussys-its-impact-on-windows-memory-protocols/"><u>Unraveling ftdibus.sys: Its Impact on Windows Memory Protocols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-typical-windows-rainmeter-setbacks-and-how-to-overcome-them/"><u>Unraveling Typical Windows Rainmeter Setbacks and How to Overcome Them</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    