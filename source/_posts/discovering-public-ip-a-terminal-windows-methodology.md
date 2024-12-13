---
title: "Discovering Public IP: A Terminal Windows Methodology"
date: 2024-12-06T23:18:12.997Z
updated: 2024-12-13T02:03:44.988Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Discovering Public IP: A Terminal Windows Methodology"
excerpt: "This Article Describes Discovering Public IP: A Terminal Windows Methodology"
keywords: Public IP Discover,IP Terminal Guide,Windows IP Finder,Network Address ID,Terminal IP Check,Locate Window IP,Public IP Protocol
thumbnail: https://thmb.techidaily.com/b4ed3f08ab6e820bb58ff66c5f5e67696c65d753e22482d093bffe3ae2ca67e1.png
---

## Discovering Public IP: A Terminal Windows Methodology

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Your Private IP Address on Windows

![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-web.techidaily.com/outube-broadcasts-made-simple-an-easy-to-follow-obs-guide-for-2024/"><u>[New] Youtube Broadcasts Made Simple An Easy-to-Follow OBS Guide for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-find-excellence-in-hd-on-android-our-top-10-player-guide-for-2024/"><u>[Updated] Find Excellence in HD on Android Our Top 10 Player Guide for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>A Working Guide For Pachirisu Pokemon Go Map On Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-apples-messaging-protocol-in-windows-10/"><u>Enabling Apple's Messaging Protocol in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-theme-options-a-comprehensive-guide-for-windows-users/"><u>Exploring Theme Options: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-your-capture-application-fast-in-windows-11/"><u>Getting to Your Capture Application Fast in Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-can-you-unlock-apple-iphone-15-plus-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>In 2024, Can You Unlock Apple iPhone 15 Plus After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-the-windows-n-enigma-which-version-to-purchase/"><u>Inside the Windows N Enigma: Which Version to Purchase?</u></a></li>
<li><a href="https://extra-support.techidaily.com/masterclass-from-yis-4k-to-thrilling-cinematography-for-2024/"><u>Masterclass From Yi's 4K to Thrilling Cinematography for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/quirky-quotables-tailoring-hilarious-content-for-brief-videography-for-2024/"><u>Quirky Quotables Tailoring Hilarious Content for Brief Videography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-the-point-of-interest-with-new-cursor-style/"><u>Redefine the Point of Interest with New Cursor Style</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/scanner-problem-solving-effective-fixes-and-tips-from-yl-computings-software/"><u>Scanner Problem Solving: Effective Fixes & Tips From YL Computing's Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-instruction-office-works-installation-on-w11/"><u>Stepwise Instruction: Office Works Installation on W11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ngle-alchemists-guide-to-transforming-your-videos-youtube-edition-for-2024/"><u>The Angle Alchemist's Guide to Transforming Your Videos (YouTube Edition) for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/the-final-solution-to-rectify-visual-distortion-in-rust-programming/"><u>The Final Solution to Rectify Visual Distortion in Rust Programming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-installing-and-using-outlook-preview/"><u>The Ultimate Guide to Installing and Using Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-window-11s-default-search-settings/"><u>Transforming Window 11'S Default Search Settings</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    