---
title: PowerShell Command for Extracting IP & MAC Addresses
date: 2024-08-16T01:35:42.783Z
updated: 2024-08-17T01:35:42.783Z
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

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://win-solutions.techidaily.com/the-ascent-overcoming-frequent-pc-crash-glitches-with-easy-fixes-and-troubleshooting-guide/"><u>'The Ascent': Overcoming Frequent PC Crash Glitches with Easy Fixes and Troubleshooting Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-3-ways-to-record-discord-live-stream-for-2024/"><u>[New] 3 Ways to Record Discord Live Stream for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-dominate-youtube-with-effective-content-strategies-for-2024/"><u>[New] Dominate YouTube with Effective Content Strategies for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-the-beat-is-in-your-hands-for-free/"><u>[New] The Beat Is in Your Hands for Free</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-instagram-stories-harmonizing-photos-for-maximum-impact/"><u>[Updated] 2024 Approved  Instagram Stories  Harmonizing Photos for Maximum Impact</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-all-about-lightroom-a-comprehensive-android-study/"><u>[Updated] In 2024, All About Lightroom  A Comprehensive Android Study</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-ultimate-trifecta-for-instagram-video-borders/"><u>[Updated] In 2024, The Ultimate Trifecta for Instagram Video Borders</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-a-new-dimension-understanding-the-innovations-in-hp-envy-27-monitor/"><u>2024 Approved  A New Dimension  Understanding the Innovations in HP Envy 27 Monitor</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-ultimate-guide-screen-capture-and-recording-with-showmore/"><u>2024 Approved  Ultimate Guide  Screen Capture & Recording with ShowMore</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/advanced-movie-file-management-six-tips-for-the-modern-user-in-windows-11-for-2024/"><u>Advanced Movie File Management - Six Tips for the Modern User in Windows 11 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-explorer-tooltips-with-auto-update-notifications/"><u>Amplifying Explorer Tooltips with Auto-Update Notifications</u></a></li>
<li><a href="https://extra-information.techidaily.com/craft-the-perfect-blurred-photo-with-these-essentials-for-2024/"><u>Craft the Perfect Blurred Photo with These Essentials for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-mistakes-to-sidestep-on-your-first-day-with-windows-11/"><u>Crucial Mistakes to Sidestep on Your First Day with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-run-windows-media-player/"><u>Easy Steps to Run Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-onedrive-operations-in-windows-10-and-11/"><u>Fixing Unsuccessful OneDrive Operations in Windows 10 & 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-tecno-spark-go-2023-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Tecno Spark Go (2023) to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-apply-local-group-policies-to-a-specific-user-account-in-windows-11-and-11/"><u>How to Apply Local Group Policies to a Specific User Account in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-robloxs-access-denied-error-403/"><u>How to Eradicate Roblox's Access Denied (Error 403)</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oppo-a18-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Oppo A18 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-switch-cards-between-apple-iphone-13-mini-and-other-iphones-will-move-all-phone-services-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Switch Cards Between Apple iPhone 13 mini and other iPhones Will Move All Phone Services? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fix-for-winerror-xc004f050/"><u>Mastering Fix for WinError Xc004f050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-presentations-physical-form-essential-strategies-for-prints-in-windows/"><u>Mastering Your Presentations' Physical Form: Essential Strategies for Prints in Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/most-asked-questions-about-pokemon-go-battle-league-rewards-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>Most Asked Questions about Pokemon Go Battle League Rewards On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-android-to-windows-shared-drives/"><u>Navigating Android to Windows Shared Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-complexities-of-docker-with-wsl-2/"><u>Navigating the Complexities of Docker with WSL 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-with-ease-access-calculator/"><u>Navigating Windows 11 with Ease: Access Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-updater-problem-code-0x8019/"><u>Overcoming Updater Problem: Code 0X8019</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/photo-perfection-how-to-erase-background-noise-with-ease/"><u>Photo Perfection  How to Erase Background Noise with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precise-methods-to-address-windows-activation-failure-code-0x803f700f/"><u>Precise Methods to Address Windows Activation Failure Code 0X803F700f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-invisible-displays-when-gaming-on-win-os/"><u>Preventing Invisible Displays When Gaming on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-slow-or-non-responsive-windows-download-area/"><u>Repairing Slow or Non-Responsive Windows Download Area</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-instant-addition-problems-with-windows-onedrive-a-compreenhensive-guide/"><u>Resolving Instant Addition Problems with Windows OneDrive - A Compreenhensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-non-working-windows-lock-screen-delay/"><u>Reviving Non-Working Windows Lock Screen Delay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-successful-installation-in-the-windows-store/"><u>Securing Successful Installation in the Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-failed-cloud-operations-on-windows-devices/"><u>Solutions for Failed Cloud Operations on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-microsoft-store-fault-error-0x0-in-windows/"><u>Strategies to Resolve Microsoft Store Fault: Error 0X0 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-printer-linkup/"><u>Streamlining Windows Printer Linkup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-windows-os-not-found-error/"><u>Swift Solution to Windows OS 'Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-0x887a0006-for-gpu-hangs/"><u>Tackling Windows Error 0X887A0006 for GPU Hangs</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-realme-narzo-60x-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Realme Narzo 60x 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-into-macos-style-ui-these-5-tips-to-try/"><u>Transforming Windows Into MacOS Style UI: These 5 Tips to Try</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-and-resolving-the-dreaded-error-28-on-your-pc-a-step-by-step-guide/"><u>Troubleshooting and Resolving the Dreaded Error 28 on Your PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-issue-insufficient-it-admin-rights/"><u>Troubleshooting Windows Issue: Insufficient IT Admin Rights</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlock-the-power-of-sony-vegas-to-enhance-your-youtube-channel-for-2024/"><u>Unlock the Power of Sony Vegas to Enhance Your YouTube Channel for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-zero-error-mystery-in-windows-11-updates/"><u>Unraveling Zero-Error Mystery in Windows 11 Updates</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-black-screen-after-fall-creators-update-solved/"><u>Windows 10 Black Screen After Fall Creators Update [Solved]</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/your-device-uninterrupted-revealing-the-top-7-android-adblockers/"><u>Your Device, Uninterrupted  Revealing the Top 7 Android AdBlockers</u></a></li>
</ul></div>
