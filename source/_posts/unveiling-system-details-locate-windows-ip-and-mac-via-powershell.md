---
title: "Unveiling System Details: Locate Windows' IP and MAC via Powershell"
date: 2024-08-16T01:58:34.947Z
updated: 2024-08-17T01:58:34.947Z
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

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-grab-free-video-profile-backgrounds/"><u>[New] In 2024, Grab Free Video Profile Backgrounds</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-quick-guide-sharing-videos-on-instagram-for-2024/"><u>[New] Quick Guide  Sharing Videos on Instagram for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-the-art-of-economy-streamlining-youtube-videos/"><u>[Updated] 2024 Approved  The Art of Economy  Streamlining YouTube Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-ride-the-viral-wave-mixing-tiktok-flair-into-instagram-reels-for-2024/"><u>[Updated] Ride the Viral Wave  Mixing TikTok Flair Into Instagram Reels for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-11-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 11 Blue Screen Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/20-tactics-for-disabling-windows-11/"><u>20 Tactics for Disabling Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-how-to-live-stream-facebook-from-pc-mac-or-laptop-with-obs/"><u>2024 Approved  How to Live Stream Facebook From PC, Mac or Laptop with OBS</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-seamless-sync-solutions-top-cloud-apps-for-android/"><u>2024 Approved  Seamless Sync Solutions  Top Cloud Apps for Android</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-top-8-tactics-for-striking-youtube-thumbnails-that-perform-well/"><u>2024 Approved  Top 8 Tactics for Striking YouTube Thumbnails That Perform Well</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transformative-techniques-mastering-lut-application-in-post-production/"><u>2024 Approved  Transformative Techniques  Mastering LUT Application in Post-Production</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-remove-a-saved-wi-fi-network-from-windows-11/"><u>4 Ways to Remove a Saved Wi-Fi Network From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tips-to-tell-if-your-pc-needs-restarting/"><u>5 Tips to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-way-to-fix-the-virus-and-threat-protection-engine-unavailable-issue-in-windows-defender/"><u>5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-restore-missing-windows-time-service/"><u>6 Ways to Restore Missing Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-key-steps-to-reinstall-missing-optional-windows-features/"><u>7 Key Steps to Reinstall Missing Optional Windows Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-notepad-not-opening-on-windows/"><u>7 Ways to Fix Notepad Not Opening on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-obs-studios-failed-to-connect-to-server-error-in-windows/"><u>7 Ways to Fix OBS Studio's Failed to Connect to Server Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-settings-to-tweak-on-a-new-windows-11-install/"><u>8 Settings to Tweak on a New Windows 11 Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-open-the-windows-internet-information-services-iis-manager/"><u>8 Ways to Open the Windows Internet Information Services (IIS) Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-walkthrough-windows-11-sandbox-setup/"><u>A Comprehensive Walkthrough: Windows 11 Sandbox Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-choose-winning-apps-of-2023/"><u>Accelerate Your PC: Choose Winning Apps of 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessible-beginnings-on-windows-for-first-timers/"><u>Accessible Beginnings on Windows for First-Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-smooth-transitions-between-android-and-windows-11-screens/"><u>Achieving Smooth Transitions Between Android & Windows 11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-stalled-keys-for-active-windows-11/"><u>Addressing Stalled Keys for Active Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-capture-for-underpowered-computers/"><u>Adjusting Windows Capture for Underpowered Computers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-infinix-hot-30i-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Infinix Hot 30i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-keystrokes-typingaid-techniques/"><u>Amplify Your Keystrokes - TypingAid Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-winning-factors-9-pc-features-that-trump-macs/"><u>Analyzing the Winning Factors: 9 PC Features That Trump Macs</u></a></li>
<li><a href="https://techtrends.techidaily.com/apples-upcoming-auto-project-unveiling-the-latest-news-expected-pricing-launch-timeline-and-speculated-features/"><u>Apple's Upcoming Auto Project: Unveiling the Latest News, Expected Pricing, Launch Timeline & Speculated Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unintended-read-only-file-states-in-windows-11/"><u>Avoiding Unintended Read-Only File States in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-folders-and-files-win-10s-technique/"><u>Blending Folders and Files: Win 10'S Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-insights-with-resource-tracking-tiles/"><u>Boost System Insights with Resource Tracking Tiles</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/combining-multiple-spotify-playlists-the-ultimate-walkthrough/"><u>Combining Multiple Spotify Playlists: The Ultimate Walkthrough</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/critical-technology-trajectories-three-game-changing-developments-to-watch-now/"><u>Critical Technology Trajectories: Three Game-Changing Developments to Watch Now</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/disabling-iphone-6-plus-parental-restrictions-withwithout-password-by-drfone-ios/"><u>Disabling iPhone 6 Plus Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719362383486-enhance-full-screen-screenshot-success-in-windows-snip-and-sketch-tool/"><u>Enhance Full-Screen Screenshot Success in Windows' Snip & Sketch Tool.</u></a></li>
<li><a href="https://extra-hints.techidaily.com/evaluating-dji-phantom-3s-advanced-capabilities/"><u>Evaluating DJI Phantom 3'S Advanced Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719231278472-how-to-correctly-use-win-plus-p-printer-command-in-windows/"><u>How to Correctly Use Win + P Printer Command in Windows.</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-y78t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-lenovo-thinkphone-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Lenovo ThinkPhone to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabled-iphone-xs-how-to-unlock-a-disabled-iphone-xs-by-drfone-ios/"><u>In 2024, Disabled iPhone XS How to Unlock a Disabled iPhone XS?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-itel-p40plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share Location in Messenger On Itel P40+? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-lenovo-thinkphone-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Lenovo ThinkPhone to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-professional-photo-tweaking-picarts-tactical-background-stripping/"><u>In 2024, Professional Photo Tweaking  PicArt's Tactical Background Stripping</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-sonic-pixels-turning-sound-into-visual-storytelling/"><u>In 2024, Sonic Pixels  Turning Sound Into Visual Storytelling</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-social-network-savants-secret-for-downloading-chats/"><u>In 2024, The Social Network Savant’s Secret for Downloading Chats</u></a></li>
<li><a href="https://win-amazing.techidaily.com/logitech-g502-gaming-mouse-troubleshooting-and-updating-drivers-made-simple/"><u>Logitech G502 Gaming Mouse: Troubleshooting & Updating Drivers Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-bypassing-defender-firewall-in-win11/"><u>Mastering the Art of Bypassing Defender Firewall in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364066200-microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes</u></a></li>
<li><a href="https://review-topics.techidaily.com/nubia-messages-recovery-recover-deleted-messages-from-nubia-by-fonelab-android-recover-messages/"><u>Nubia Messages Recovery - Recover Deleted Messages from Nubia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360119482-revolutionize-windows-experience-overcome-incompatibilities-now/"><u>Revolutionize Windows Experience: Overcome Incompatibilities Now</u></a></li>
</ul></div>
