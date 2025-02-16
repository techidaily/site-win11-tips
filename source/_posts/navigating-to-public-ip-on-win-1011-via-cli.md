---
title: Navigating to Public IP on Win 10/11 via CLI
date: 2025-02-11T23:33:30.524Z
updated: 2025-02-16T03:16:32.086Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating to Public IP on Win 10/11 via CLI
excerpt: This Article Describes Navigating to Public IP on Win 10/11 via CLI
keywords: Win_PublicIPCLI,Windows_IPAddress,Win10IPFind,Win11PublicIP,CLI_WindowsIP,IPConfigWinXP,CMD_GetIPInfo
thumbnail: https://thmb.techidaily.com/43693d1bcddc3757eef24651324be62efb3dc8d54599f3df8a30593f96e0aa27.jpg
---

## Navigating to Public IP on Win 10/11 via CLI

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-unveil-your-world-in-wide-angle-iosandroid-photo-integration-on-social-media/"><u>[New] In 2024, Unveil Your World in Wide Angle IOS/Android Photo Integration on Social Media</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-ingenious-stop-motion-cinema-ranking-the-best-15/"><u>[New] Ingenious Stop-Motion Cinema - Ranking the Best 15</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-craft-a-vibrant-youtube-experience-with-tracks-for-2024/"><u>[Updated] Craft a Vibrant Youtube Experience with Tracks for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-finding-top-8-free-reliable-srt-translator-picks-online/"><u>[Updated] Finding Top 8 Free, Reliable SRT Translator Picks Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-hidden-addresses-of-installed-pc-apps/"><u>Demystifying the Hidden Addresses of Installed PC Apps</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722976618334-download-and-update-your-pc-with-realtek-asio-windows-10-drivers-now/"><u>Download and Update Your PC with RealTek Asio Windows 10 Drivers Now</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-shaky-to-stellar-the-best-free-online-video-stabilization-tools-reviewed-for-2024/"><u>From Shaky to Stellar The Best Free Online Video Stabilization Tools Reviewed for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-brand-storytelling-through-the-eyes-of-customer-voices/"><u>In 2024, Brand Storytelling Through the Eyes of Customer Voices</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-cure-to-steams-online-connectivity-problems/"><u>Quick Cure to Steam's Online Connectivity Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safety-switch-stopping-windows-11-tasks/"><u>Safety Switch: Stopping Windows 11 Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-data-how-to-use-controlling-access-settings-in-windows/"><u>Securing Data: How to Use Controlling Access Settings in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-pathway-for-windows-11-emulation-on-workstation-17/"><u>The Ultimate Pathway for Windows 11 Emulation on Workstation 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-workflows-utilize-flow-launcher-for-maximum-output/"><u>Turbocharge Workflows: Utilize Flow Launcher for Maximum Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-canary-an-easy-to-follow-guide/"><u>Understanding Windows Canary: An Easy-to-Follow Guide</u></a></li>
</ul></div>

