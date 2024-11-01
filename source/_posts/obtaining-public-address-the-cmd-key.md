---
title: "Obtaining Public Address: The CMD Key"
date: 2024-10-31T16:41:06.622Z
updated: 2024-11-01T18:03:31.071Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Obtaining Public Address: The CMD Key"
excerpt: "This Article Describes Obtaining Public Address: The CMD Key"
keywords: CMD Access Info,Public Addr Finder,Command Line Guide,Obtain Address CMD,DOS Address Search,Execute LocateAddr,Command for Address
thumbnail: https://thmb.techidaily.com/b74744220589b6a906ebb663c728844a6da00413ed53ac60e0a2a79854afed11.jpg
---

## Obtaining Public Address: The CMD Key

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
<a href="https://aligracehair.sjv.io/c/5597632/1880931/19272" target="_top" id="1880931">
  <img src="//a.impactradius-go.com/display-ad/19272-1880931" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880931/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047366/19272" target="_top" id="2047366">
  <img src="//a.impactradius-go.com/display-ad/19272-2047366" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047366/19272" style="position:absolute;visibility:hidden;" border="0" />
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

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-instagrams-secret-fine-tuning-fcpx-for-high-aspect-videos/"><u>[New] 2024 Approved Instagram's Secret Fine-Tuning FCPX for High Aspect Videos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-powerdirector-unveiled-in-depth-review-and-users-handbook/"><u>[Updated] 2024 Approved PowerDirector Unveiled In-Depth Review & User's Handbook</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-budget-conscious-filmmakers-guide-to-360-cameras/"><u>[Updated] Budget-Conscious Filmmakers' Guide to 360° Cameras</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-crafting-video-narratives-with-chiseled-chapters-on-vimeo/"><u>[Updated] Crafting Video Narratives with Chiseled Chapters on Vimeo</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-essential-photo-and-film-capture-apps-iphone-and-android-edition/"><u>[Updated] In 2024, Essential Photo & Film Capture Apps IPhone & Android Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2023windows-movie-maker11/"><u>2023年最好的免费Windows Movie Maker替代品：探索11种功能丰富的视频编辑工具</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/avoidance-and-remedy-of-live-video-interruption-issues-fb/"><u>Avoidance & Remedy of Live Video Interruption Issues (FB)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-wsl-complete-uninstall-guide-for-windows-11/"><u>Eliminating WSL: Complete Uninstall Guide for Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mov-mxf-movavi-0/"><u>MOV 파일을 MXF로 이식: MOVavi에서 비용 0%의 온라인 제공</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-ferramenta-online-gratuita-para-transformar-mp4-em-formato-3gp-com-facilidade/"><u>Móvavi: Ferramenta Online Gratuita Para Transformar MP4 Em Formato 3GP Com Facilidade!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mpg-conversion-of-ram-a-complimentary-online-service-with-moveai-tech-solutions/"><u>MPG Conversion of RAM: A Complimentary Online Service with MoveAI Tech Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/veelvoulend-ongemakkooptje-qt-naar-mp4-omzetten-met-movavi-gratis-en-direct-op-internet/"><u>Veelvoulend Ongemakkooptje: QT Naar MP4 Omzetten Met Movavi, Gratis en Direct Op Internet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aiff-m4amp3/"><u>무료 AIFF 매니페스트를 M4A/MP3로 바꾸기 - 이식센터에서 원통</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    