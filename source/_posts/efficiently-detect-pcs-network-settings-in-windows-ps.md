---
title: Efficiently Detect PC's Network Settings in Windows PS
date: 2024-11-05T19:36:02.259Z
updated: 2024-11-06T23:15:06.379Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficiently Detect PC's Network Settings in Windows PS
excerpt: This Article Describes Efficiently Detect PC's Network Settings in Windows PS
keywords: WinPSNetworkCheck,PsWindowsConfig,NetInfoWinPC,SetupDetectorPS,WINPSNetSettings,ConfigDetectionWin,PSNetworkDiagnose
thumbnail: https://thmb.techidaily.com/26dcef27c207b8605e3fcf4585ee0822110eeb8a794c85ff8e27071c7786d452.jpg
---

## Efficiently Detect PC's Network Settings in Windows PS

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047411/19272" target="_top" id="2047411">
  <img src="//a.impactradius-go.com/display-ad/19272-2047411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-unlocking-viral-potential-creating-captivating-instagram-puzzles/"><u>[New] 2024 Approved Unlocking Viral Potential Creating Captivating Instagram Puzzles</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-cloud-choice-best-value-in-data-safekeeping/"><u>[New] Cloud Choice Best Value in Data Safekeeping</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-renowned-crafters-exquisite-instagram-hlv-designers-online/"><u>[New] In 2024, Renowned Crafters Exquisite Instagram HLV Designers Online</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-comprehensive-guide-to-acquiring-instagram-ringtones-and-creating-noteworthy-chimes/"><u>[New] The Comprehensive Guide to Acquiring Instagram Ringtones & Creating Noteworthy Chimes</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-perfecting-package-adventure-for-all-for-2024/"><u>[Updated] Perfecting Package Adventure for All for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-quick-steps-to-capture-ios-audio-files/"><u>In 2024, Quick Steps to Capture iOS Audio Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-activity-log-inspection-in-windows-10/"><u>Mastering Activity Log Inspection in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-post-update-issues-a-guide-for-windows-discord-users/"><u>Overcoming Post-Update Issues: A Guide for Windows Discord Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unwinding-catastrophic-javascript-hiccup-in-discord-w10w11/"><u>Quick Guide: Unwinding Catastrophic Javascript Hiccup in Discord W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-pc-not-valid-warning-on-windows-11/"><u>Remedy for PC Not Valid Warning on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rustic-tech-resurgence-atlasos-update/"><u>Rustic Tech Resurgence: AtlasOS Update</u></a></li>
<li><a href="https://vp-tips.techidaily.com/seamlessly-bring-back-windows-photo-viewer-in-win-11-systems-for-2024/"><u>Seamlessly Bring Back Windows Photo Viewer in Win 11 Systems for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/signs-youre-not-in-someones-contact-list/"><u>Signs You're Not in Someone's Contact List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-network-adapter-error-31-on-windows/"><u>Steps to Rectify Network Adapter Error 31 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-adjusting-icons-distance-on-windows-1110/"><u>Title: Adjusting Icons' Distance on Windows 11/10</u></a></li>
</ul></div>

