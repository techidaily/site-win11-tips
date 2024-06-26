---
title: PowerShell Command for Extracting IP & MAC Addresses
date: 2024-06-25T17:00:07.002Z
updated: 2024-06-26T17:00:07.002Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes PowerShell Command for Extracting IP & MAC Addresses
excerpt: This Article Describes PowerShell Command for Extracting IP & MAC Addresses
keywords: PowerShell IP Extraction,PowerShell MAC Retrieval,PowerShell Network Tools,PowerShell Address Gathering,Advanced PowerShell Scripts,PowerShell Data Collection,IP & MAC via PowerShell
thumbnail: https://thmb.techidaily.com/88bfebb08e4cbb8d0a68e78c0297b8f1e363343f342702915251fd121c5a13e0.jpg
---

## PowerShell Command for Extracting IP & MAC Addresses

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-device-access-after-encountering-error-22-in-windows-11/"><u>How to Unlock Device Access After Encountering Error 22 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-assault-fixing-lags-for-pc-warriors/"><u>Ace Your Assault: Fixing Lags for PC Warriors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correctly-installing-an-ms-store-app/"><u>Steps for Correctly Installing an MS Store App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-grades-with-these-top-8-windows-study-hacks/"><u>Skyrocket Grades with These Top 8 Windows Study Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-overcoming-server-notifications-on-pc-apex-(156-chars/"><u>Top Tips for Overcoming Server Notifications on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-11-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-walkthrough-switching-nat-type-on-wins-10-and-11/"><u>Step-By-Step Walkthrough: Switching NAT Type on Wins 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-zero-x-eight-oh-three-one-f-failures-in-mail-apps/"><u>Winning Against Zero X Eight Oh Three One F Failures in Mail Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pitfalls-of-the-promotional-assessing-risks-with-low-price-auth-codes/"><u>Pitfalls of the Promotional: Assessing Risks with Low-Price Auth Codes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/resurrecting-windows-photo-viewer-windows-10-techniques-1-and-2-for-2024/"><u>Resurrecting Windows Photo Viewer  Windows 10 Techniques #1 & #2 for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-high-res-gopro-hero5-against-sj7-star/"><u>[Updated] High Res GoPro Hero5 Against SJ7 Star</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-essential-mac-apps-screen-recording-made-simple/"><u>[Updated] In 2024, Essential Mac Apps  Screen Recording Made Simple</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-explore-our-list-of-10-superior-phone-based-video-chat-apps/"><u>2024 Approved  Explore Our List of 10 Superior Phone-Based Video Chat Apps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-streamlining-access-to-fb-live-via-roku/"><u>[Updated] In 2024, Streamlining Access to FB Live via Roku</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-videos-not-playing-with-my-edge-40-by-stellar-video-repair-mobile-video-repair/"><u>How to fix videos not playing with my Edge 40?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-next-gen-realities-navigating-vrs-future-trajectory/"><u>[Updated] Next-Gen Realities  Navigating VR's Future Trajectory</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-on-iphone-6-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock on iPhone 6</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-elevate-your-vimeo-watch-time/"><u>[Updated] 2024 Approved  Elevate Your Vimeo Watch Time</u></a></li>
<li><a href="https://change-location.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-vivo-v30-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Vivo V30? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>