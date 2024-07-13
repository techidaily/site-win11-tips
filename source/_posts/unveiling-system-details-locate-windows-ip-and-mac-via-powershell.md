---
title: "Unveiling System Details: Locate Windows' IP and MAC via Powershell"
date: 2024-07-12T17:09:33.845Z
updated: 2024-07-13T17:09:33.845Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling System Details: Locate Windows' IP and MAC via Powershell"
excerpt: "This Article Describes Unveiling System Details: Locate Windows' IP and MAC via Powershell"
keywords: Find Windows IP Powershell,Windows MAC Address Command,Win IP Location Scripting,PoweShell IP Detailing,Locate Mac Windows PS,PowerShell Windows Details,Extract Windows Ip Info
thumbnail: https://thmb.techidaily.com/16367f6c60ce9653f1392a643e2b82dc02b50b35ff890c97d3a0607584104c84.jpg
---

## Unveiling System Details: Locate Windows' IP and MAC via Powershell

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-asus-rog-phone-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-non-verified-error-during-windows-file-installation/"><u>Solving the Non-Verified Error During Windows File Installation</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-xr21-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from XR21?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storeroom-in-mp60-speed-still-scarce/"><u>Storeroom in MP60, Speed Still Scarce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resolving-user-not-found-issue-windows-1011/"><u>Steps for Resolving 'User Not Found' Issue: Windows 10/11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-muting-mastery-keeping-your-meeting-focus-on-google-go-for-2024/"><u>[Updated] Muting Mastery  Keeping Your Meeting Focus on Google Go for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-itel-s23plus-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Itel S23+ Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-mastering-the-art-of-screensaver-recording-with-mobizen-technology/"><u>[New] 2024 Approved  Mastering the Art of Screensaver Recording with Mobizen Technology</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-make-movies-that-wow-a-comprehensive-guide-to-professional-video-production/"><u>2024 Approved Make Movies That Wow A Comprehensive Guide to Professional Video Production</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-d3dx939dll-loss-in-windows-11/"><u>Resolving D3DX9_39.dll Loss in Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-12-impressive-ai-video-ideas-for-making-engaging-video-content-for-2024/"><u>New 12 Impressive AI Video Ideas for Making Engaging Video Content for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-vivo-by-fonelab-android-recover-contacts/"><u>How to Rescue Lost Contacts from Vivo ?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-mastering-media-analysis-evaluating-your-vs-opponents-youtube-content/"><u>[Updated] Mastering Media Analysis  Evaluating Your Vs. Opponents' YouTube Content</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-composers-handbook-to-instagram-and-music-rights/"><u>[New] The Composer's Handbook to Instagram and Music Rights</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-navigate-to-the-5-preferred-android-ps2-emulator-apps/"><u>[New] Navigate to the 5 Preferred Android PS2 Emulator Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-isarcextract-error-in-windows-11-updates/"><u>Overcoming ISArcExtract Error in Windows 11 Updates</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-complete-guide-to-producing-high-quality-gopro-time-lapse/"><u>The Complete Guide to Producing High-Quality GoPro Time-Lapse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-error-unending-teams-sign-in-requests/"><u>Overcoming Windows Error: Unending Teams Sign-In Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restoring-functionality-fix-media-on-win11/"><u>Mastering the Art of Restoring Functionality: Fix Media on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-driver-initialization-failure-in-windows-11/"><u>Solutions for Driver Initialization Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-demanded-assets-error-in-windows-1011-environments/"><u>Overcoming Demanded Assets Error in Windows 10/11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejoining-fall-guys-fixing-connectivity-issues-on-pc/"><u>Rejoining Fall Guys: Fixing Connectivity Issues on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-mic-malfunctions-in-windows-os/"><u>Overcoming Xbox Mic Malfunctions in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-options-picking-right-nvidia-driver-type-for-you/"><u>Navigating Options, Picking Right Nvidia Driver Type For You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unsuited-file-vlc-problem/"><u>Overcoming Windows' 'Unsuited File' VLC Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-expanded-pinned-area-on-windows-11-ui/"><u>Techniques for Expanded Pinned Area on Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-troubleshooting-failed-capture-on-win11/"><u>Methods for Troubleshooting Failed Capture on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-stuck-windows-enter-function/"><u>Mending the Stuck Windows 'Enter' Function</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-command-gain-admin-status/"><u>Regain Command - Gain Admin Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-windows-1011-interrupt-crashes/"><u>Strategies for Tackling Windows 10/11 INTERRUPT Crashes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-disabled-iphone-12-miniipad-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Disabled iPhone 12 mini/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-methods-to-identify-system-gadgets/"><u>Proven Windows Methods to Identify System Gadgets</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-maximize-your-engagement-with-full-screen-facebook-videos-for-2024/"><u>[Updated] Maximize Your Engagement with Full-Screen Facebook Videos for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-ultimate-group-communication-applications/"><u>[New] Ultimate Group Communication Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-virtualbox-usb-connection-issue-on-windows-devices/"><u>Overcoming VirtualBox USB Connection Issue on Windows Devices</u></a></li>
</ul></div>
