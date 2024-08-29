---
title: Overcoming the Error 0Xc0f1103f in Windows 11 & NVIDIA
date: 2024-08-28T01:16:42.643Z
updated: 2024-08-29T01:16:42.643Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming the Error 0Xc0f1103f in Windows 11 & NVIDIA
excerpt: This Article Describes Overcoming the Error 0Xc0f1103f in Windows 11 & NVIDIA
keywords: WinErrorCodeC0F1103FSolution,FixNvidiaWindows11Error,Windows11NvidiaXc0f1103F,NVIDIAWin11Correction,0XC0F1103FWindowsRepair,OvercomingNVidiaErrorWin11,RemedyNvidiaErrorCodeXc0f1103f
thumbnail: https://thmb.techidaily.com/28b4424e01d4cc277a30d2dc85adec4230b241c9e861b58d7c8b2fd02e294cb8.jpg
---

## Overcoming the Error 0Xc0f1103f in Windows 11 & NVIDIA

 Some GeForce Now users have reported that their app no longer works because of error 0xc0f1103f. Those players see that error code when they start the GeForce Now app or games with it. Error 0xc0f1103f has a message that says, “Your system does not meet the minimum requirements for streaming.”

 That issue occurs on PCs that do meet the minimum streaming system requirements. Is the same error stopping you from playing GeForce Now titles? If so, this is how you can fix error 0xc0f1103f in Windows 10 and 11.

## Double-Check That Your PC Matches GeForce Now's System Requirements

 If you’re a first-time GeForce Now user, double-check your PC meets the streaming service’s system requirements before troubleshooting. Open the[GeForce Now system requirement page](https://www.nvidia.com/en-gb/geforce-now/system-reqs/) for Windows PCs to check hardware requirements.

![GeForce Now system requirements](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/geforce-now-system-requirements.jpg)

 You can check how your PC’s specs match up by[opening the System Information app](https://www.makeuseof.com/windows-open-system-information/) . The system summary shows most of the essential hardware specs for GeForce Now streaming. You can view GPU details by clicking**Components** \>**Display** in the System Information app.

 You’ll need to upgrade your PC if it doesn’t match a system requirement. Desktop users can add new graphics adapters or even processors to their PCs if required. If your PC does indeed match all the GeForce Now requirements, proceed with the troubleshooting below.

## 1\. Double-Check if GeForce Now’s Servers Are Operational

 This error can occur because the GeForce Now server is down. For example, the server could be down for maintenance. You can check the service status for various regions on the[GeForce Now service status](https://status.geforcenow.com/) page. If a server for your region is down, wait until the service is operational again before opening the GeForce Now app again.

![The NVIDIA server status page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/nvidia-server-status-page.jpg)

## 2\. Run GeForce Now With Administrator Rights

 Running GeForce Now with admin rights is a simple potential solution to try that’s worth a try. If you have a desktop shortcut for the software, right-click and select the**Run as administrator** option. Or you can enter**GeForce Now** in the Windows search box and right-click the app in the results to select**Run as administrator** .

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-as-adminstrator-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If that works, it’s best to set GeForce Now to always run with elevated rights. You can do that by opening the properties window for the GeForce Now EXE (Application) and selecting the**Run as administrator** checkbox. Check out our guide about[always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) for further details.

## 3\. Select a Power Saving GPU for the GeForce Now App

 This resolution applies to users with PCs that have two GPUs (graphics processing units). Selecting a power-saving integrated GPU for the GeForce Now app is a widely confirmed fix for error 0xc0f1103f. This is how you can select an integrated GPU for the GeForce Now app in Windows:

1. First, activate the search utility with the**Win+ S** key combination.
2. Type**graphics settings** in the search box.
3. Click**Graphics settings** to open the options in Settings.
4. Then click**Browse** to bring up an Open window.
5. Select the GeForceNow app at this path:  
`C:\Users\[user folder]\AppData\Local\NVIDIA Corporation\GeForceNOW\CEF\GeForceNow.exe`
6. Click the**Add** button.
7. Select the added**GeForce Now** app and click its**Options** button.
8. Then select the**Power saving** (integrated GPU) option.  
![Power saving option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/power-saving-option.jpg)
9. Click**Save** to apply the selected option.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Update Your Graphics Card’s Driver

 Other users have said updating graphics drivers resolved the issue for them. You can update your PC’s graphics driver with third-party driver update software or download it from the NVIDIA, AMD, or Intel manufacturer site. Check out our guide for[updating graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) for further details about applying this potential error 0xc0f1103f solution.

## 5\. Restart All NVIDIA-Related Services

 This GeForceNow error can occur because certain NVIDIA certain services are not running or need restarting. You can fix that by going through and restarting (or starting) all NVIDIA services as follows:

1. Bring up Windows Search (see[how to find Windows Search](https://www.makeuseof.com/windows-search-use-guide/) if you need help).
2. Input**Services** , then click the**Services** app the search tool finds.
3. Then scroll to NVIDIA-related services.  
![NVIDIA-related-services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/nvidia-services-window.jpg)
4. Right-click every NVIDIA-related service you can see and select**Restart** . If an NVIDIA service isn’t already running, select the**Start** option for it instead.  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Restart option for a NVIDIA service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart-option.jpg)

## 6\. Turn Off Any Active Proxy Servers

 Do you have a proxy server on your PC? If so, that could be causing the 0xc0f1103f error by generating a server issue. So, try disabling your proxy server on Windows via Settings or the Control Panel. Our article about[disabling your proxy server on Windows](https://www.makeuseof.com/windows-11-disable-proxy/) includes instructions for how to do so.

![The Edit proxy server option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-proxy-server-option.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Disable Any Active VPNs

 Weaker VPN (Virtual Private Network) connections can also cause this game streaming issue to arise. If you utilize a VPN connection, disable it via the Windows Settings app like this:

1. Launch Settings by clicking the Start menu button or pinned shortcut for opening that app.
2. Then select the**Network & Internet** tab or category.
3. Click the**VPN** navigation option or tab.  
![The VPN navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/vpn-navigation-option.jpg)
4. Select a listed VPN connection added.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![VPN settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/vpn-settings.jpg)
5. Then select the**Disconnect** option for the VPN.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
6. Open GeForce Now and try playing some games with the VPN disconnected.

## 8\. Reinstall GeForce Now

 The GeForce Now app might be corrupted if none of the alternative troubleshooting methods specified here work for you. In this case, you’ll probably need to reinstall the GeForce Now software to resolve such an issue. These are the steps for reinstalling GeForce Experience:

1. Open Programs and Features (see[how to open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/) for methods) and select GeForce Now.
2. Click GeForce Now’s**Uninstall/Change** option.  
![The Uninstall/Change option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-option.jpg)
3. Select**Uninstall** on the window that opens.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
4. Restart Windows 11 or 10 after uninstalling GeForce Now.
5. Open the[GeForce Now](https://www.nvidia.com/en-us/geforce-now/download/) [download page](http://www.nvidia.com/en-us/geforce-now/download/) .
6. Click**Download** for the GeForce Now Windows software.  
![The GeForce Now download option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/geforce-now-download-option.jpg)  
 Double-click the**GeForce-Now-release.exe** file to open the software’s setup wizard.
7. Then go through the setup wizard steps to reinstall GeForce Now.

## Play GeForce Now Games on Windows Again

 Those are the most likely potential fixes for error 0xc0f1103f that have worked for users. So, there’s a pretty good chance one will resolve that issue on your PC if it meets the minimum GeForce Now system requirements. With error 0xc0f1103f fixed, you can enjoy all the best games the GeForce Now streaming service has to offer again.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-free-online-services-for-youtube-images-extraction/"><u>[New] 2024 Approved  FREE Online Services for YouTube Images Extraction</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-metaverse-inspiration-enhanced-by-ar-and-vr/"><u>[New] Metaverse Inspiration  Enhanced by AR & VR</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-unveiling-secrets-of-hulu-recording-across-windowsmacosios/"><u>[New] Unveiling Secrets of Hulu Recording Across Windows/MacOS/iOS</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-a-compreomed-approach-for-making-tiktok-songs-your-ringtone/"><u>[Updated] A Compreomed Approach for Making TikTok Songs Your Ringtone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tweeting-videos-to-tweenish-animations-for-no-fee/"><u>[Updated] In 2024, Tweeting Videos to Tweenish Animations for No Fee</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-top-10-collage-apps-for-android-top-picks/"><u>[Updated] Top 10 Collage Apps for Android (Top Picks)</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-free-scape-discovering-the-artistic-no-money-backdrops-of-tiktok/"><u>2024 Approved  FREE-Scape  Discovering the Artistic No-Money Backdrops of TikTok</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-kinemaster-app-for-android-a-comprehensive-insight-review/"><u>2024 Approved  KineMaster App for Android  A Comprehensive Insight Review</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-ae-title-design-standout-effects-guide/"><u>2024 Approved  Mastering AE Title Design  Standout Effects Guide</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-the-yuneec-typhoon-h-dive-professional-takeaways/"><u>2024 Approved  The Yuneec Typhoon H Dive  Professional Takeaways</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/5-essential-android-image-tweakers/"><u>5 Essential Android Image Tweakers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/augmenting-digital-conversations-with-ai-helpdesk/"><u>Augmenting Digital Conversations with AI Helpdesk</u></a></li>
<li><a href="https://extra-resources.techidaily.com/blur-the-boundaries-techniques-to-mask-faces-in-photos-for-2024/"><u>Blur the Boundaries  Techniques to Mask Faces in Photos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-windows-smartscreen-filters-and-alerts/"><u>Configuring Windows' SmartScreen Filters and Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-system-call-failure-in-win11/"><u>Eliminating System Call Failure in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-win11-stay-up-to-date-essential-uptime-checks/"><u>Ensure Win11 Stay Up-to-Date: Essential Uptime Checks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-and-solving-roblox-error-403-for-windows-devices/"><u>Exploring & Solving Roblox Error 403 for Windows Devices</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/eyecapture-facebook-content-saves/"><u>EyeCapture  Facebook Content Saves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-server-crashes-in-media-software/"><u>Fixing Server Crashes in Media Software</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-lsassexe-unable-to-locate-component-error-in-windows/"><u>How to Fix the lsass.exe Unable to Locate Component Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-keep-your-desktop-spotless-with-windows-self-clean-feature/"><u>How to Keep Your Desktop Spotless with Windows Self-Clean Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-absence-of-key-dll-mfc71u-in-os/"><u>How to Reinstate: Absence of Key DLL – Mfc71u in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-force-remove-a-print-spooler-from-pc/"><u>How to Swiftly Force Remove a Print Spooler From PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-causes-behind-missing-regedit-application/"><u>Identifying Causes Behind Missing Regedit Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/illuminate-interruption-5-solutions-to-bring-back-keyboard-glow/"><u>Illuminate Interruption: 5 Solutions to Bring Back Keyboard Glow</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-realme-v30-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Realme V30 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-thors-fury-legends-of-the-ragnarok/"><u>In 2024, Thor's Fury  Legends of the Ragnarök</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-xiaomi-redmi-13c-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Xiaomi Redmi 13C 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-over-jerks-top-techniques-to-address-win-11s-typing-latency/"><u>Jump Over Jerks: Top Techniques to Address Win 11'S Typing Latency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mkv-to-mp4-file-shift-in-windows-environment/"><u>Mastering MKV to MP4 File Shift in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-absent-items-from-file-explorer-list/"><u>Mending Absent Items From File Explorer List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-error-0x80070570s-maze-of-corruption/"><u>Navigating Through Windows Error 0X80070570's Maze of Corruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-widows-handbrake-freeze-woes/"><u>Overcome Widows' HandBrake Freeze Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-opengl-error-code-3-with-nvidia/"><u>Overcoming OpenGL Error Code 3 with NVIDIA</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pc-awakening-guide-navigating-windows-8-revival-strategies/"><u>PC Awakening Guide: Navigating Windows' 8 Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-find-functionality-a-step-by-step-guide-for-win11-users/"><u>Quick Find Functionality – A Step-by-Step Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-rearranged-keystrokes-in-operating-systems/"><u>Remedying Rearranged Keystrokes in Operating Systems</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-zte-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on ZTE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-digital-label-changing-username-in-windows-11/"><u>Revolutionize Your Digital Label: Changing UserName in Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/rising-trend-do-gpu-prices-increase-next/"><u>Rising Trend: Do GPU Prices Increase Next?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-windows-partition-union-explained/"><u>Seamless Windows Partition Union Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shutting-down-defender-firewall-in-windows-11-easily/"><u>Shutting Down Defender Firewall in Windows 11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-regaining-router-interface-on-pc/"><u>Strategies for Regaining Router Interface on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-distribution-the-ultimate-sefx-guide-for-win11/"><u>Streamlining File Distribution: The Ultimate SEFx Guide for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tutorial-review-and-purge-windows-activity-records/"><u>Tech Tutorial: Review & Purge Windows Activity Records</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-low-adoption-rate-of-windows-11-seven-points/"><u>The Low Adoption Rate of Windows 11: Seven Points</u></a></li>
<li><a href="https://games-able.techidaily.com/the-stealthiest-of-players-guide/"><u>The Stealthiest of Players Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On OnePlus Ace 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/tightening-control-over-who-you-engage-with-fb/"><u>Tightening Control Over Who You Engage With FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-controlling-content-filter-on-windows-11/"><u>Tips for Controlling Content Filter on Windows 11</u></a></li>
</ul></div>
