---
title: Leveraging PS to Find IP and MAC on Windows Devices
date: 2024-10-27T18:07:01.544Z
updated: 2024-11-01T19:38:51.366Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Leveraging PS to Find IP and MAC on Windows Devices
excerpt: This Article Describes Leveraging PS to Find IP and MAC on Windows Devices
keywords: Windows Device MAC/IP Finder,PS Command for IP Addressing,Leveraging PowerShell for IP Locating,Mac Address Extraction Windows,PowerShell Network Tools,Identifying Device Details PS,Windows Devices IP Retrieval
thumbnail: https://thmb.techidaily.com/128a52db05a06f83263e58b5a6a26485493e4674a4560940aaffe08f0a59ec40.jpg
---

## Leveraging PS to Find IP and MAC on Windows Devices

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532">
  <img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-who-are-tiktoks-gaming-visionaries/"><u>[New] 2024 Approved Who Are TikTok’s Gaming Visionaries?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-mastering-identity-change-on-google-meet-via-pc-and-phone/"><u>[New] In 2024, Mastering Identity Change on Google Meet via PC & Phone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-capture-the-moment-idevice-screenshots-and-playback-for-2024/"><u>[Updated] Capture the Moment IDevice Screenshots & Playback for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-elevate-your-song-listening-with-these-top-6-android-apps/"><u>[Updated] In 2024, Elevate Your Song Listening With These Top 6 Android Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-how-windows-approves-deleted-items/"><u>Customizing How Windows Approves Deleted Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-windows-experience-through-keys-and-discounts/"><u>Elevating Your Windows Experience Through Keys and Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-time-management-on-pc-choose-from-these-5-best-tools-to-create-customized-clock-screen-savers/"><u>Enhance Time Management on PC: Choose From These 5 Best Tools to Create Customized Clock Screen Savers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/essential-titles-your-gateway-to-open-worlds/"><u>Essential Titles Your Gateway to Open Worlds</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/how-to-shift-conversations-effortlessly-migrating-whatsapp-data-from-samsung-galaxy-to-apples-latest-iphone-models/"><u>How to Shift Conversations Effortlessly: Migrating WhatsApp Data From Samsung Galaxy to Apple's Latest iPhone Models</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/perfecting-visual-fidelity-of-fc6-ui/"><u>Perfecting Visual Fidelity of FC6 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-notes-visually-a-guide-to-obsidian-canvas/"><u>Transform Your Notes Visually: A Guide to Obsidian Canvas</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-poco-x5-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Poco X5 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-startup-configurations-simplified-guidebook/"><u>Windows Startup Configurations Simplified Guidebook</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    