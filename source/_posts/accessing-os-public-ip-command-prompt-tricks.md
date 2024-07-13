---
title: "Accessing OS Public IP: Command Prompt Tricks"
date: 2024-07-12T17:55:51.503Z
updated: 2024-07-13T17:55:51.503Z
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
<li><a href="https://win11-tips.techidaily.com/activating-driver-verifier-on-windows-11/"><u>Activating Driver Verifier on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719317580799-brighten-up-windows-11-screens-with-easy-adjustments/"><u>Brighten Up Windows 11 Screens with Easy Adjustments</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-unlock-zooms-full-power-with-share-screen-expertise/"><u>[New] Unlock Zoom’s Full Power with Share Screen Expertise</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-comedy-canvas-painting-laughter-with-top-10-video-concepts/"><u>[Updated] Comedy Canvas  Painting Laughter with Top 10 Video Concepts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276426207-saving-the-day-with-win1011s-recycle-bin-corruption-fixed/"><u>Saving the Day with Win10/11's Recycle Bin Corruption Fixed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-cool-folder-tips-youll-love-using-on-windows/"><u>5 Cool Folder Tips You'll Love Using on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-to-spot-signs-for-windows-reset/"><u>4 Easy-to-Spot Signs for Windows Reset?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-your-account-has-been-disabled-in-the-app-store-and-itunes-from-iphone-13-pro-by-drfone-ios/"><u>In 2024, Your Account Has Been Disabled in the App Store and iTunes From iPhone 13 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-fix-hibernate-mode-not-working-on-windows/"><u>4 Ways to Fix Hibernate Mode Not Working on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-d-drive-folder-in-windows-explorer/"><u>Accessing D: Drive Folder in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-configuration-windows-11-and-pc-manager/"><u>Achieving Optimal Configuration: Windows 11 & PC Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-dive-into-modern-standby-and-its-problematic-aspects/"><u>A Dive Into Modern Standby and Its Problematic Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-app-opening-top-5-windows-11-tips/"><u>Accelerate App Opening: Top 5 Windows 11 Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-lock-apps-on-realme-v30t-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Realme V30T to Protect Your Individual Information</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-workflow-with-auto-moves-the-w11-way/"><u>Accelerate Workflow with Auto-Moves: The W11 Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-lightweight-windows-browsers-tested-for-ram-usage-which-is-the-best/"><u>7 Lightweight Windows Browsers Tested for RAM Usage: Which Is the Best?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-network-disconnect-in-windows-11-a-step-by-step-guide/"><u>Addressing Network Disconnect in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-gionee-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Gionee IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-for-windows-vr-compatibility/"><u>Adapting Oculus Quest 2 for Windows VR Compatibility</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-oppo-f25-pro-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Oppo F25 Pro 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268444157-eliminate-non-responsive-printer-a-guide-for-wwin-issues-on-pcs/"><u>Eliminate Non-Responsive Printer: A Guide for WWin Issues on PCs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-can-i-unlock-my-apple-iphone-6s-after-forgetting-my-pin-code-by-drfone-ios/"><u>How Can I Unlock My Apple iPhone 6s After Forgetting my PIN Code?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-30015-26-in-microsoft-365-for-users/"><u>Addressing Error Code 30015-26 in Microsoft 365 for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328256303-bargain-alert-key-enthusiasts-snag-612lifetime-windows-11-deal-today-only/"><u>Bargain Alert: Key Enthusiasts Snag $6.12/Lifetime Windows 11 Deal Today Only!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-keys-to-windows-program-harmony/"><u>4 Keys to Windows Program Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-blank-screens-on-system-ignition/"><u>Addressing Blank Screens on System Ignition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334255604-win11-chrome-issues-jumpstart-solution-suggestions/"><u>Win11 Chrome Issues? Jumpstart Solution Suggestions</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-trim-your-videos-for-free-10-best-online-editors/"><u>2024 Approved Trim Your Videos for Free 10 Best Online Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-connected-systems-error-windows/"><u>Addressing No Connected Systems Error Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-digital-dimensions-online/"><u>2024 Approved  Mastering Digital Dimensions Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-performance-with-powertoys-win11/"><u>Achieving Optimal Performance with PowerToys (Win11)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-exploring-best-fit-basic-to-pro-in-vimeo-services/"><u>[New] 2024 Approved  Exploring Best Fit  Basic to Pro in Vimeo Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-excel-operations-in-windows-os/"><u>Accelerate Your Excel Operations in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-inaccessibility-of-roblox-due-to-user-settings-in-windows/"><u>Addressing the Inaccessibility of Roblox Due to User Settings in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-tale-of-time-the-windows-taskbar-saga-19852023/"><u>A Tale of Time: The Windows Taskbar Saga (1985–2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-stalled-keys-for-active-windows-11/"><u>Addressing Stalled Keys for Active Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-service-did-not-respond-issue-in-windows/"><u>Addressing Service Did Not Respond Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719309481571-streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-honor-x9a-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Honor X9a to iPhone | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-honor-play-8t-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Honor Play 8T FRP</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-do-i-sim-unlock-my-apple-iphone-14-by-drfone-ios/"><u>How Do I SIM Unlock My Apple iPhone 14?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-digital-dreamland-with-windows-pcs/"><u>Achieving Digital Dreamland with Windows PCs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-honor-x50-devices-by-drfone-android/"><u>How to Reset Gmail Password on Honor X50 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328507288-uncomplicated-start-menus-say-no-to-ads/"><u>Uncomplicated Start Menus - Say No to Ads!</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/directly-sharing-twitter-videos-onto-your-instagram-account/"><u>Directly Sharing Twitter Videos Onto Your Instagram Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-poco-m6-pro-5g-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-domain-services-printer-errors-win11-tips-and-tricks/"><u>Addressing Domain Services Printer Errors: Win11 Tips & Tricks</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-split-your-videos-with-ease-top-5-free-software-for-2024/"><u>New Split Your Videos with Ease Top 5 Free Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx9-point-on-windows-11/"><u>Addressing Missing D3DX9 Point on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-windows-narrators-legacy-keyboard-shortcuts/"><u>A Complete Guide to Windows Narrator's Legacy Keyboard Shortcuts</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-windows-1011-grab-your-desk-view/"><u>[New] Windows 10/11  Grab Your Desk View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-clipchamp-integration-windows-11-setup-solved/"><u>Achieve ClipChamp Integration: Windows 11 Setup Solved</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-prime-7-video-software-for-apple-machines/"><u>[Updated] Prime 7 Video Software for Apple Machines</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-expertly-slice-your-videos-macs-finest-mp4-applications/"><u>In 2024, Expertly Slice Your Videos  Mac's Finest MP4 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-glitches-in-windows-google-nearby-share-app/"><u>Addressing Glitches in Windows Google Nearby Share App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-assistance-top-tips-for-fixed-gameplay-on-pcs/"><u>Accelerated Assistance: Top Tips for Fixed Gameplay on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-10-step-guide-to-windows-health-reports/"><u>A 10-Step Guide to Windows Health Reports</u></a></li>
</ul></div>
