---
title: Identify Your Worldwide IP in Command Prompt, Windows PCs
date: 2024-12-10T16:48:06.607Z
updated: 2024-12-12T20:33:01.369Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Identify Your Worldwide IP in Command Prompt, Windows PCs
excerpt: This Article Describes Identify Your Worldwide IP in Command Prompt, Windows PCs
keywords: Global IP Address Finder,IP Location Service,Locate IP Internationally,Find Worldwide IP,IP Region Identifier,GeoIP Command Prompt,Windows IP Explorer
thumbnail: https://thmb.techidaily.com/a8380bddcca8cf55ebe9b6409c5102df744a27a7ccc7e054a06e6cf78ab12144.png
---

## Identify Your Worldwide IP in Command Prompt, Windows PCs

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Check Your Private IP Address on Windows

![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-digital-picture-perfect-with-audio-touches/"><u>[New] 2024 Approved Digital Picture Perfect with Audio Touches</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-unveiling-the-mysteries-of-io-video-capture/"><u>[New] 2024 Approved Unveiling the Mysteries of IO Video Capture</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-embrace-authenticity-your-style-journey-begins-here-for-2024/"><u>[Updated] Embrace Authenticity Your Style Journey Begins Here for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-how-to-see-what-you-just-watched-on-facebook/"><u>2024 Approved How to See What You Just Watched on Facebook</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/download-winxdvd-software-professional-dvd-to-iphone-movies-conversion-and-transfers/"><u>Download WinXDVD Software | Professional DVD to iPhone Movies Conversion & Transfers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-productivity-with-cloud-services-dropboxgoogle-on-c/"><u>Enhancing Productivity with Cloud Services: Dropbox/Google on C:</u></a></li>
<li><a href="https://tools.techidaily.com/flyingcfx/products/"><u>Flyingcfx's Products</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-the-enhancement-tab-missing-in-windows-11-try-these-5-fixes/"><u>Is the Enhancement Tab Missing in Windows 11? Try These 5 Fixes</u></a></li>
<li><a href="https://driver-download.techidaily.com/lenovo-thunderbolt-3-hub-latest-driver-update-available-now/"><u>Lenovo Thunderbolt 3 Hub: Latest Driver Update Available Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-non-starting-indexing-in-windows/"><u>Methods to Prevent Non-Starting Indexing in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-adopting-apple-maps-in-windows/"><u>Navigating with Ease: Adopting Apple Maps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-invalid-user-alerts-a-windows-11-guide/"><u>Resolving Invalid User Alerts: A Windows 11 Guide</u></a></li>
<li><a href="https://fox-links.techidaily.com/reveling-in-4k-an-in-depth-look-at-yis-hero-series-for-2024/"><u>Reveling in 4K An In-Depth Look at Yi’s HERO Series for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/riding-secure-the-creme-de-la-cam-selection-for-motorcyclists/"><u>Riding Secure - The Crème De La Cam Selection for Motorcyclists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-of-silence-stopping-background-windows-jobs/"><u>Secrets of Silence: Stopping Background Windows Jobs</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-resolving-non-functional-voice-chat-in-phasmophobia/"><u>Troubleshooting Guide: Resolving Non-Functional Voice Chat in Phasmophobia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-capability-of-windows-11-with-easy-widget-additions/"><u>Unlock the Full Capability of Windows 11 With Easy Widget Additions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-seamless-play-easy-drive-selection-in-xbox-app/"><u>Unlocking Seamless Play: Easy Drive Selection in Xbox App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-tactics-boosting-valorant-download-speed-quickly/"><u>Winning Tactics: Boosting Valorant Download Speed Quickly</u></a></li>
</ul></div>

