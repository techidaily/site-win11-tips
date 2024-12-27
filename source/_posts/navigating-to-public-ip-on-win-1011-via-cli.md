---
title: Navigating to Public IP on Win 10/11 via CLI
date: 2024-12-23T20:38:04.260Z
updated: 2024-12-27T21:36:40.024Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Your Private IP Address on Windows

![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/new-fraudulent-fronts-navigating-the-minefield-of-fake-youtube-viewers-for-2024/"><u>[New] Fraudulent Fronts Navigating the Minefield of Fake YouTube Viewers for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-unleashing-the-power-of-obs-macos-install-and-usage-tips/"><u>[New] In 2024, Unleashing the Power of OBS MacOS Install & Usage Tips</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-innovation-hub-for-youtube-gurus/"><u>[Updated] 2024 Approved Innovation Hub for YouTube Gurus</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-brighten-up-your-gameplay-tips-to-fix-a-black-screen-on-obs-for-2024/"><u>[Updated] Brighten Up Your Gameplay Tips to Fix a Black Screen on OBS for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-must-have-essentials-for-a-starry-drive-with-your-sj4000-for-2024/"><u>[Updated] Must-Have Essentials for a Starry Drive with Your SJ4000 for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-windows-11-updates-examined/"><u>[Updated] Windows 11 Updates Examined</u></a></li>
<li><a href="https://win-unique.techidaily.com/discover-the-features-of-windows-11s-new-ai-integrated-update-launching-today-an-expert-breakdown-zdnet/"><u>Discover the Features of Windows 11'S New AI-Integrated Update Launching Today - An Expert Breakdown | ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-new-interfaces-in-windows-11-post-update-edition/"><u>Discovering New Interfaces in Windows 11 Post-Update Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-structure-and-significance-of-windows-batch-files/"><u>Dissecting the Structure & Significance of Windows Batch Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-into-server-management-using-iis-manager/"><u>Dive Deep Into Server Management Using IIS Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-accessing-and-using-winnettoolbox/"><u>Essential Tips: Accessing and Using WinNetToolbox</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/et-guides-leading-food-vloggers-online-for-2024/"><u>Gourmet Guides Leading Food Vloggers Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-syncing-wsl-with-windows-11/"><u>Mastering the Art of Syncing WSL With Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/pioneering-seven-water-resilient-camera-brands/"><u>Pioneering Seven Water-Resilient Camera Brands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-win-password-update/"><u>Step-by-Step Guide to Win Password Update</u></a></li>
</ul></div>

