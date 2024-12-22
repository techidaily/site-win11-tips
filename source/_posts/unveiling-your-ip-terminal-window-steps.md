---
title: "Unveiling Your IP: Terminal Window Steps"
date: 2024-12-19T16:12:30.942Z
updated: 2024-12-22T05:05:59.973Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling Your IP: Terminal Window Steps"
excerpt: "This Article Describes Unveiling Your IP: Terminal Window Steps"
keywords: Terminal Window Guide,Accessing IP Info,Network Terminal Tips,IP Display Windows,Steps for Terminal IP,Window IP Reveal,Terminal IP Exploration
thumbnail: https://thmb.techidaily.com/017337439b4f792b0246468061b8e1aa8f8f36d01cdf2619fb3c06685fc0972f.jpg
---

## Unveiling Your IP: Terminal Window Steps

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Your Private IP Address on Windows

![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

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
<li><a href="https://youtube-web.techidaily.com/esizing-youtube-images-step-by-step-guide-for-2024/"><u>[New] Resizing YouTube Images Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-time-saving-tips-for-documenting-virtual-meeting-events-for-2024/"><u>[Updated] Time-Saving Tips for Documenting Virtual Meeting Events for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-unlocking-the-secrets-of-instagrams-saved-content-for-2024/"><u>[Updated] Unlocking the Secrets of Instagram's Saved Content for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtube-videography-essentials-7-free-audio-choices/"><u>[Updated] YouTube Videography Essentials - 7 Free Audio Choices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-xiaomi-redmi-a2-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Xiaomi Redmi A2 Activity | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/conversion-gratuita-de-archivos-wav-a-formato-mkv-online-con-movavi/"><u>Conversión Gratuita De Archivos .wav a Formato .mkv Online Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-non-installed-disk-errors-and-how-to-tackle-them-in-windows-11/"><u>Deciphering 'Non-Installed Disk' Errors and How To Tackle Them in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-in-file-history-settings-on-windows-pcs/"><u>Fixing Error in File History Settings on Windows PCs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/gratis-online-konverter-mov-nach-wma-mit-movavi-kostenlos/"><u>Gratis Online Konverter: MOV Nach WMA Mit Movavi - Kostenlos</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-itel-p55plus-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Itel P55+ Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-directx-installation-problems/"><u>Overcoming DirectX Installation Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-gameplay-win-troubleshooting-epic-login/"><u>Reviving Your Gameplay: Win Troubleshooting Epic Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-0x80246007-windows-update-problems/"><u>Swift Solutions to 0X80246007 Windows Update Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-views-configuring-windows-11-dual-monitors/"><u>Tailor Your Views: Configuring Windows 11 Dual Monitors</u></a></li>
</ul></div>

