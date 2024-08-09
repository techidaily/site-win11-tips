---
title: Balancing Wireless & Cable Networks on Windows Systems
date: 2024-08-08T10:55:50.290Z
updated: 2024-08-09T10:55:50.290Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Balancing Wireless & Cable Networks on Windows Systems
excerpt: This Article Describes Balancing Wireless & Cable Networks on Windows Systems
keywords: Balance Wireless/Cable,Network Integration Win,Mixing Protocols,Hybrid Net Setup,Cross-Platform Connectivity,Windows Network Harmony,Seamless Wired/Wireless
thumbnail: https://thmb.techidaily.com/a26306e3d205a36c4a6b9d44bd1cf9f948f504e389465c9417b498ad1381c72e.jpg
---

## Balancing Wireless & Cable Networks on Windows Systems

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can [merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons [why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**
5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**
6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## Make Your Computer Use Your Wi-Fi and Ethernet at the Same Time

 You can configure the network adapter on your computer to use both Wi-Fi and Ethernet connection simultaneously. While it has many advantages, it won't increase your Internet speed. Instead, you’ll need multiple Internet connections powering your Wi-Fi and Ethernet networks to see increased speed.

 Alternatively, if you have multiple Wi-Fi connections at home or office, you can configure your Windows computer to automatically switch to the strongest Wi-Fi network available when you move around.


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
<li><a href="https://fox-access.techidaily.com/new-in-2024-automated-methods-for-adding-photo-dates/"><u>[New] In 2024, Automated Methods for Adding Photo Dates</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-proven-tactics-for-saving-lol-events/"><u>[New] In 2024, Proven Tactics for Saving LOL Events</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-superior-streams-with-av1-activate-on-youtube/"><u>[New] Superior Streams with AV1  Activate on YouTube</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-economic-guide-to-capturing-virtual-learning-spaces/"><u>[Updated] 2024 Approved  Economic Guide to Capturing Virtual Learning Spaces</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-optimize-your-films-a-mac-approach-to-instagram-shortening/"><u>[Updated] In 2024, Optimize Your Films  A Mac Approach to Instagram Shortening</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-unlocking-screen-capture-shortcut-driven-mac-techniques/"><u>[Updated] In 2024, Unlocking Screen Capture  Shortcut-Driven Mac Techniques</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-unveiling-the-mystery-of-facebooks-status-video-downloads/"><u>[Updated] In 2024, Unveiling the Mystery of Facebook's Status Video Downloads</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-safeguarding-snapshots-techniques-for-instagram-watermarks/"><u>[Updated] Safeguarding Snapshots  Techniques for Instagram Watermarks</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-android-tips-creating-stunning-slow-motion-videos/"><u>2024 Approved  Android Tips  Creating Stunning Slow Motion Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-boundless-treasure-tales-of-instagram-flair/"><u>2024 Approved  Boundless Treasure Tales of Instagram Flair</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-nba-live-your-ultimate-guide-to-15-streaming-methods/"><u>2024 Approved  NBA Live  Your Ultimate Guide to 15 Streaming Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-easy-steps-to-resolve-windows-interface-errors-quickly/"><u>5 Easy Steps to Resolve Windows' Interface Errors Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-insights-on-staying-with-older-windows-editions/"><u>7 Insights on Staying with Older Windows Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-lightweight-windows-browsers-tested-for-ram-usage-which-is-the-best/"><u>7 Lightweight Windows Browsers Tested for RAM Usage: Which Is the Best?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-honor-x50iplus-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Honor X50i+ PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-temporarily-bypassing-windows-11s-safety-measures/"><u>A Quick Guide: Temporarily Bypassing Windows 11'S Safety Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-microsofts-bluetooth-app/"><u>A Step-by-Step Guide to Using Microsoft's Bluetooth App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-app-opening-top-5-windows-11-tips/"><u>Accelerate App Opening: Top 5 Windows 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-awareness-custom-notification-for-win11-users/"><u>Accelerating Battery Awareness: Custom Notification for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-performance-add-custom-alerts-to-windows-11/"><u>Accelerating Battery Performance: Add Custom Alerts to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-workflow-efficient-redo-keys-on-windows/"><u>Ace Your Workflow: Efficient Redo Keys on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-windows-11-firewall-settings-to-the-context-menu/"><u>Adding Windows 11 Firewall Settings to the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-administrative-control-settings-in-windows-11-devices/"><u>Addressing Administrative Control Settings in Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-common-failures-when-importing-iphones-to-windows/"><u>Addressing Common Failures When Importing iPhones to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-install-net-now-demands-from-apps/"><u>Addressing Install .NET Now Demands From Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-hang-error-dxgierrordevicehunk-on-windows/"><u>Addressing the HANG Error: DXGI_ERROR_DEVICE_HUNK on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-cameras-failed-recordings/"><u>Addressing Windows Camera's Failed Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-control-display-settings-for-windows-11-users/"><u>Advanced Control: Display Settings for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-strategies-for-pinpointing-hardware-identification-in-windows/"><u>Advanced Strategies for Pinpointing Hardware Identification in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/arrow-anomalies-unveiled-and-resolved-for-windows-users/"><u>Arrow Anomalies Unveiled and Resolved for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-the-role-and-safety-profile-of-aggregatorhostexe-in-windows/"><u>Assessing the Role and Safety Profile of AggregatorHost.exe in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automated-password-inclusion-in-windows-file-management/"><u>Automated Password Inclusion in Windows File Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-and-recovery-for-windows-note-apps/"><u>Backup & Recovery for Windows Note Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bargain-alert-key-enthusiasts-snag-612lifetime-windows-11-deal-today-only/"><u>Bargain Alert: Key Enthusiasts Snag $6.12/Lifetime Windows 11 Deal Today Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-fps-measurement-software-for-windows-11-users/"><u>Best FPS Measurement Software for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-in-a-chip-size-world/"><u>Best Windows in a Chip Size World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-windows-innovations-into-linux/"><u>Blending Windows Innovations Into Linux</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blocking-windows-update-messages/"><u>Blocking Windows Update Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bolstering-bygone-directx-games-with-cutting-edge-dxvk-features/"><u>Bolstering Bygone DirectX Games with Cutting-Edge DXVK Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-browser-performance-fix-youtube-delays/"><u>Boosting Browser Performance: Fix YouTube Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-productivity-with-wordpad-embedding-commands-into-context-menus/"><u>Boosting Productivity with WordPad: Embedding Commands Into Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-real-time-task-tracker-on-windows-11-os/"><u>Boosting Real-Time Task Tracker on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-ssd-performance-with-windows-and-ssd-fresh/"><u>Boosting SSD Performance with Windows & SSD Fresh</u></a></li>
<li><a href="https://article-helps.techidaily.com/exploring-popularity-stock-images-meme-journey-for-2024/"><u>Exploring Popularity  Stock Images' Meme Journey for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-oppo-reno-10-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Oppo Reno 10 5G | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-realme-note-50-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719314760975-home-run-your-gptclone-on-windows-free-and-easy-with-gpt4all/"><u>Home-Run Your GPTClone on Windows – Free & Easy with GPT4All</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-oppo-k11x-by-drfone-android/"><u>How to Bypass FRP on Oppo K11x?</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-poco-m6-5g-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-honor-x50iplus-devices-by-drfone-android/"><u>How to Reset Gmail Password on Honor X50i+ Devices</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-nokia-g310-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Nokia G310 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-tecno-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Tecno Phone and Remove Locked Screen</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-comprehensive-srt-education-and-resources/"><u>In 2024, Comprehensive SRT Education and Resources</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-elevating-viewers-prime-video-ideas-for-channels/"><u>In 2024, Elevating Viewers  Prime Video Ideas for Channels</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-lava-yuva-3-pro-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Lava Yuva 3 Pro to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-a-found-iphone-13-pro-by-drfone-ios/"><u>In 2024, How To Unlock A Found iPhone 13 Pro?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-professional-insights-crafting-and-sharing-360-videos-on-fb/"><u>In 2024, Professional Insights  Crafting & Sharing 360 Videos on FB</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-unlock-apple-id-without-phone-number-on-apple-iphone-14-by-drfone-ios/"><u>In 2024, Unlock Apple ID without Phone Number On Apple iPhone 14</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/pro-tools-2021-elevating-your-tiktok-footage-on-mac-for-2024/"><u>Pro Tools 2021  Elevating Your TikTok Footage on Mac for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/simple-android-recording-without-rooting-steps/"><u>Simple Android Recording Without Rooting Steps</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-steps-to-restart-your-desktop-without-power-indicators/"><u>Troubleshooting Steps to Restart Your Desktop Without Power Indicators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381461685-unlock-hidden-features-in-windows-snipping-tool-for-flawless-screen-shots/"><u>Unlock Hidden Features in Windows Snipping Tool for Flawless Screen Shots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370971554-xbox-not-responding-unfreeze-and-get-back-in/"><u>Xbox Not Responding? Unfreeze and Get Back In!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719262774069-your-on-premise-window-to-a-costless-chatgpt-clone-via-gpt4all/"><u>Your On-Premise Window to a Costless ChatGPT Clone via GPT4All.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/zero-price-green-screen-visuals/"><u>Zero Price, Green Screen Visuals</u></a></li>
</ul></div>
