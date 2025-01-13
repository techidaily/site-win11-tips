---
title: Step-by-Step Methods to Use Both Network Types on a Single Windows Device
date: 2025-01-10T02:09:08.353Z
updated: 2025-01-12T21:21:30.144Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Methods to Use Both Network Types on a Single Windows Device
excerpt: This Article Describes Step-by-Step Methods to Use Both Network Types on a Single Windows Device
keywords: WinNetworkSetupGuide,HybridOSUseWindows,MultiNetworkDeviceTips,DualNetWinSystem,SeamlessNetIntegration,WindowsDualNetworking,SingleDeviceMultiNet
thumbnail: https://thmb.techidaily.com/c23fd39a2d5eab7804c8c0b256c287da5a7d97c2d7588b0ef8db354da07eb1bf.jpg
---

## Step-by-Step Methods to Use Both Network Types on a Single Windows Device

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**

5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-how-to-blur-and-hide-private-information-in-recorded-video/"><u>[New] In 2024, How to Blur and Hide Private Information in Recorded Video</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-surviving-splashes-top-7-action-cam-selection/"><u>[New] Surviving Splashes Top 7 Action Cam Selection</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-angled-artistry-elevating-youtube-video-editing-skills/"><u>2024 Approved Angled Artistry Elevating YouTube Video Editing Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-ways-to-check-your-ram-type-on-windows/"><u>4 Easy Ways to Check Your RAM Type on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-turn-filter-keys-on-or-off-on-windows/"><u>4 Ways to Turn Filter Keys On or Off on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-resolving-steam-setup-problems-win11-edition/"><u>A Practical Guide to Resolving Steam Setup Problems, Win11 Edition</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-step-by-step-approach-for-effective-spotify-marketing/"><u>A Step-by-Step Approach for Effective Spotify Marketing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-automation-rules-on-desktop/"><u>Addressing Non-Functional Automation Rules on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sudden-screen-blackouts-in-winsteam/"><u>Addressing Sudden Screen Blackouts in WinSteam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-copilot-arrives-on-windows-11-transforming-user-interaction/"><u>AI Copilot Arrives on Windows 11, Transforming User Interaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-display-drivers-that-dont-launch-in-windows-10/"><u>Avoiding Display Drivers That Don’t Launch in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-full-screen-screenshot-expert-4-essential-tricks-for-windows/"><u>Become a Full-Screen Screenshot Expert: 4 Essential Tricks for Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-performance-by-enabling-automatic-file-deletion-in-winos/"><u>Boost System Performance by Enabling Automatic File Deletion in WINOS</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-digital-landscape-with-facebook-twitter-instagram-and-youtube/"><u>Exploring the Digital Landscape with Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-10t-5g-phone-without-pin-by-drfone-android/"><u>How to Unlock Realme 10T 5G Phone without PIN</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pixelated-projections-immersive-filmscape-for-2024/"><u>Pixelated Projections Immersive Filmscape for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/quick-guide-to-infusing-new-flair-in-old-content-using-instagram-features-for-2024/"><u>Quick Guide to Infusing New Flair in Old Content Using Instagram Features for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/repaired-fnaf-mobile-game-crashes-no-more-play-stable-version/"><u>Repaired FNAF Mobile Game Crashes No More – Play Stable Version</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1726029244126-xmedia-recode/"><u>XMedia Recodeを使用したビデオ解像度調整手順とそれに代わる戦略</u></a></li>
</ul></div>

