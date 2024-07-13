---
title: Unmasking Your Worldwide Address Through CMD, Windows
date: 2024-07-12T17:24:07.927Z
updated: 2024-07-13T17:24:07.927Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unmasking Your Worldwide Address Through CMD, Windows
excerpt: This Article Describes Unmasking Your Worldwide Address Through CMD, Windows
keywords: Global IP Finder,Uncover Domain Location,Windows Command ID,CMD Locate IP,Geo-IP Windows Tool,Address Discovery CLI,CMD Worldwide Decoder
thumbnail: https://thmb.techidaily.com/830a114fa27984f8d212144f3dee11f785f5b8b667c623d0ec997b65a2b06877.jpg
---

## Unmasking Your Worldwide Address Through CMD, Windows

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

## How to Get Your Public IP Address on Windows
![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

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
<li><a href="https://win11-tips.techidaily.com/fingerprint-fraud-unraveling-the-latest-hack-on-windows-hello/"><u>Fingerprint Fraud? Unraveling the Latest Hack on Windows Hello</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/obs-studio-for-gamers-ps4-screenshots-and-recordings-guide-for-2024/"><u>OBS Studio for Gamers  PS4 Screenshots & Recordings Guide for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-transformative-thumbnails-with-immersive-scenes/"><u>In 2024, Transformative Thumbnails with Immersive Scenes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-clearer-journey-the-art-of-annotating-folders-on-windows-11/"><u>A Clearer Journey: The Art of Annotating Folders on Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-honor-magic-5-pro-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-windows-11-shutdown-procedure-for-active-operations/"><u>Tweak Windows 11 Shutdown Procedure for Active Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fasten-up-your-pc-launches-mastering-windows-11-quick-start-mode/"><u>Fasten Up Your PC Launches: Mastering Windows 11 Quick Start Mode</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-vivo-x-flip-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Vivo X Flip Phone? Unlock It Now</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-crafting-clarity-a-detailed-exploration-of-audio-editing-in-audacity/"><u>New 2024 Approved Crafting Clarity A Detailed Exploration of Audio Editing in Audacity</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/viral-cuisine-discover-the-top-15-most-popular-tiktok-food-videos-yet-for-2024/"><u>Viral Cuisine  Discover the Top 15 Most Popular TikTok Food Videos Yet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-addressing-critical-app-issues/"><u>Approaches to Addressing Critical App Issues</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-finding-your-next-big-idea-in-iconography-at-these-6-places/"><u>[Updated] Finding Your Next Big Idea in Iconography at These 6 Places</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-insights-into-utilizing-dism-for-win11-fixes/"><u>Expert Insights Into Utilizing Dism for Win11 Fixes</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/by-step-for-quick-chromakey-application-for-2024/"><u>Step-by-Step for Quick Chromakey Application for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-vivetool-innovations/"><u>Elevate Your Windows Experience with ViVeTool Innovations</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-xs-to-other-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone XS to Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11-bluescreen-mastery-through-11-fixes/"><u>Unraveling Windows 11 Bluescreen: Mastery Through 11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-for-quake-via-windows-terminal/"><u>Command Line for Quake via Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-crashing-file-explorer-on-windows-11-now/"><u>Fix Crashing File Explorer on Windows 11 Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-win-11-gameplay-unveiling-the-ultimate-seven-steps/"><u>Boosting Win 11 Gameplay: Unveiling the Ultimate Seven Steps</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Oppo Reno 9A? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-touch-input-in-windows-enabledisable-steps/"><u>Configure Touch Input in Windows: Enable/Disable Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-artificial-intelligence-generating-vibrant-ai-graphics-paint-cocreator/"><u>Windows 11 & Artificial Intelligence: Generating Vibrant AI Graphics (Paint Cocreator)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-ultra-clear-gaming-best-21-hdmi-compatible-monitors-ps5/"><u>[New] Ultra Clear Gaming  Best 2.1 HDMI Compatible Monitors [PS5]</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-evaluating-igtv-video-impact-effectively/"><u>In 2024, Evaluating IGTV Video Impact Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-folder-multiplication-on-windows-devices/"><u>Unlocking the Potential of Folder Multiplication on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-for-repairing-nonfunctional-itunes-on-windows/"><u>Efficient Methods for Repairing Nonfunctional iTunes on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10win11-troubleshooting-hardware-recognition-issues/"><u>Win10/Win11: Troubleshooting Hardware Recognition Issues</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-screensavers-supreme-mastering-the-art-of-twitvid-archiving/"><u>[New] 2024 Approved  ScreenSavers Supreme  Mastering the Art of TwitVid Archiving</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-spotlight-series-the-best-gamers-on-tiktok-for-2024/"><u>[Updated] Spotlight Series  The Best Gamers on TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-index-performance-on-your-pc/"><u>Enhancing Index Performance on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-code-0x887a0006-for-graphics/"><u>Correcting Error Code 0X887A0006 for Graphics</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-tiktok-unleashed-mastering-its-core-components/"><u>2024 Approved  TikTok Unleashed  Mastering Its Core Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-0x800704cf-from-windows-marketplace/"><u>Eliminating 0X800704CF From Windows Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-infamous-blue-screen-issues/"><u>Demystifying Windows' Infamous Blue Screen Issues</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-easy-video-editing-how-to-freeze-frames-like-a-pro-in-minutes/"><u>Updated In 2024, Easy Video Editing How to Freeze Frames Like a Pro in Minutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-edge-techniques-for-effective-wsl-2-use/"><u>Leading Edge Techniques for Effective WSL 2 Use</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-modern-guide-to-implementing-decay-in-sound-tracks-for-2024/"><u>Updated The Modern Guide to Implementing Decay in Sound Tracks for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-precision-in-motion-learning-to-record-perfect-screens-on-macos/"><u>2024 Approved  Precision in Motion  Learning to Record Perfect Screens on macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-cease-discord-startup-and-update-checks-in-windows/"><u>Workaround: Cease Discord Startup and Update Checks in Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/experts-take-on-magix-video-pro-x-for-2024/"><u>Expert's Take on Magix Video Pro X for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-easy-online-video-editors-with-music-and-audio-features/"><u>2024 Approved Easy Online Video Editors with Music and Audio Features</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-xiaomi-13t-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Xiaomi 13T to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-oppo-a38-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Oppo A38 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-no-fee-guide-converting-skype-to-mp3-for-2024/"><u>[New] No-Fee Guide  Converting Skype to Mp3 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-solutions-to-unacceptable-connections-in-windows-os/"><u>Finding Solutions to Unacceptable Connections in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-defenders-0x80004004-issue/"><u>Breaking Down Windows Defender's 0X80004004 Issue</u></a></li>
</ul></div>
