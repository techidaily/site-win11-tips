---
title: Revealing Your Internet IP Through Terminal Commands
date: 2024-09-01T05:17:58.845Z
updated: 2024-09-02T05:17:58.845Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revealing Your Internet IP Through Terminal Commands
excerpt: This Article Describes Revealing Your Internet IP Through Terminal Commands
keywords: Find My IP Address,Terminal IP Locate,Uncover IP Terminal,Terminal IP Reveal,Get IP Command-Line,Obtain IP Terminal,Discover Internet IP
thumbnail: https://thmb.techidaily.com/4c2f1c5599abfece009f925c2828de86667e5982a128d746578608e8851ede9e.jpg
---

## Revealing Your Internet IP Through Terminal Commands

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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/ffordable-acoustic-amps-and-mics-for-video-voyagers-for-2024/"><u>[New] Affordable Acoustic Amps and Mics for Video Voyagers for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-your-ultimate-guide-to-capturing-underwater-wonders/"><u>[New] In 2024, Your Ultimate Guide to Capturing Underwater Wonders</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-from-novice-to-viewer-keeper-top-10-basic-yet-captivating-video-ideas-for-2024/"><u>[Updated] From Novice to Viewer-Keeper  Top 10 Basic Yet Captivating Video Ideas for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-comprehensive-guide-to-storing-itunes-video-files/"><u>[Updated] In 2024, Comprehensive Guide to Storing iTunes Video Files</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-key-techniques-for-storing-lol-matches/"><u>[Updated] In 2024, Key Techniques for Storing LOL Matches</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-vivo-y100t-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Vivo Y100t to Roku | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-refresh-a-modern-take-on-windows-98-vibe/"><u>Classic Refresh: A Modern Take on Windows 98 Vibe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-forbidden-save-messages-on-windows-pcs/"><u>Clearing Up 'Forbidden Save' Messages on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-mute-issues-in-screencasts-with-powerpoint/"><u>Correcting Mute Issues in Screencasts with PowerPoint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-powerhouse-exes-from-windows-bat-files/"><u>Crafting Powerhouse EXEs From Windows .bat Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-steps-to-access-and-manage-printers-efficiently/"><u>Decoding Windows: Steps to Access and Manage Printers Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-windows-mechanism-for-allocated-ram/"><u>Delving Into Windows' Mechanism for Allocated RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-update-requests/"><u>Eliminating Windows Update Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-code-2e-strategies-for-windows-update-fix/"><u>Error Code 2E: Strategies for Windows Update Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-proactive-measures-to-counter-network-security-keys-misalignment-in-win11/"><u>Five Proactive Measures to Counter Network Security Keys Misalignment in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-fortify-dotnet-windows-style-max-156/"><u>Fix & Fortify DotNet, Windows Style (Max 156)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/guide-to-embedding-on-screen-text-on-youtube-clips/"><u>Guide to Embedding On-Screen Text on YouTube Clips</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/how-to-convert-facebook-video-to-mp4-720p1080phd-online-and-free/"><u>How to Convert Facebook Video to MP4 720P/1080p/HD Online and Free?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-disabled-firewall-in-windows-os/"><u>How to Reactivate Disabled Firewall in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-pasting-functionality-in-top-browsers/"><u>How to Recover Pasting Functionality in Top Browsers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-oppo-find-n3-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Oppo Find N3 Data? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-infinix-zero-30-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Infinix Zero 30 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-maximize-windows-11s-beginning/"><u>Innovative Approaches to Maximize Windows 11'S Beginning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-11-arm-detailed-iso-based-guide/"><u>Installing Windows 11 ARM: Detailed ISO-Based Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-premium-sound-experience-windows-11-and-dolby-atmos/"><u>Integrating Premium Sound Experience: Windows 11 & Dolby Atmos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-savings-techniques-for-thrifty-windows-10-enthusiasts/"><u>Key Savings Techniques for Thrifty Windows 10 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-wasteful-resource-usage-by-ntoskrnlexe/"><u>Lowering Wasteful Resource Usage by Ntoskrnl.exe</u></a></li>
<li><a href="https://extra-tips.techidaily.com/masterclass-in-media-magic-with-magix-video-pro-x/"><u>Masterclass in Media Magic with Magix Video Pro X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-system-fixes-reviving-troubleshooters-in-windows-11/"><u>Mastering System Fixes: Reviving Troubleshooters in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915361726-navigating-the-giants-of-social-platforms-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Social Platforms - Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-opening-woes-on-pc-find-solutions-here/"><u>OneDrive Opening Woes on PC? Find Solutions Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-copy-pasting-errors-in-popular-web-browsers/"><u>Overcoming Copy-Pasting Errors in Popular Web Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-wi-fi-setup-obstacles-bridging-actions-on-windows-os/"><u>Overcoming Wi-Fi Setup Obstacles: Bridging Actions on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protect-your-child-online-windows-11-safety-guide/"><u>Protect Your Child Online: Windows 11 Safety Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-missing-enter-action-from-keyboard/"><u>Recovering Missing 'Enter' Action From Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-update-failure-code-0x8019/"><u>Rectifying Update Failure: Code 0X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-system-recovery-activation-in-the-latest-windows-os/"><u>Simplifying System Recovery Activation in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skytop-techniques-for-elevated-fps-in-roblox/"><u>Skytop Techniques for Elevated FPS in Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-enhanced-win1011-system-graphics-memory/"><u>Step-by-Step to Enhanced Win10/11 System Graphics Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-windowss-uncommon-pink-issues/"><u>Strategies for Fixing WINDOWS's Uncommon Pink Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taskbar-transition-in-microsoft-ui-over-38-years/"><u>Taskbar Transition in Microsoft UI Over 38 Years</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tricks-bridging-airpods-and-windows-devices/"><u>Tech Tricks: Bridging AirPods & Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-win11-mouse-settings-and-controls/"><u>The Ultimate Guide to Win11 Mouse Settings & Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-and-restore-bluetooth-devices-on-win/"><u>Troubleshoot and Restore Bluetooth Devices on WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-and-bypassing-sound-access-issues-in-audacity-win/"><u>Troubleshooting and Bypassing Sound Access Issues in Audacity (Win)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11-themes-undiscovered-so-far/"><u>Unraveling Windows 11 Themes Undiscovered So Far</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-secrets-how-to-fix-the-no-server-error-in-pc-apex-legends-(156-chars/"><u>Unveiling Secrets: How to Fix the No-Server Error in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-effortless-soloist-extraction-devices-catering-to-every-skill-tier/"><u>Updated Effortless Soloist Extraction Devices Catering to Every Skill Tier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-gamers-should-prioritize-dxvk-in-their-win-based-setup/"><u>Why Gamers Should Prioritize DXVK in Their Win-Based Setup?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-exploring-6-unusual-visual-aspects/"><u>Windows 11: Exploring 6 Unusual Visual Aspects</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>