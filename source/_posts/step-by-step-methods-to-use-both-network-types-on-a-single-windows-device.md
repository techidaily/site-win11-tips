---
title: Step-by-Step Methods to Use Both Network Types on a Single Windows Device
date: 2025-02-26T18:14:20.320Z
updated: 2025-03-04T18:55:47.959Z
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

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-become-a-youtube-gif-wizard-your-complete-online-transformation-tutorial/"><u>[New] 2024 Approved Become a Youtube Gif Wizard Your Complete Online Transformation Tutorial</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-fb-cover-videos-strategies-for-maximum-impact-for-2024/"><u>[New] FB Cover Videos Strategies for Maximum Impact for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-the-art-of-producing-attention-grabbing-podcast-openers/"><u>[Updated] In 2024, The Art of Producing Attention-Grabbing Podcast Openers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-to-show-or-not-to-display-off-facebook-activities/"><u>[Updated] To Show or Not to Display Off-Facebook Activities</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-honor-x50i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Honor X50i | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-activation-lock-from-apple-iphone-14-pro-max-4-easy-ways-by-drfone-ios/"><u>Bypass Activation Lock From Apple iPhone 14 Pro Max - 4 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-decades-old-password-in-windows-error/"><u>Deciphering Decades-Old Password in Windows Error</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-system-up-to-date-for-windows-11-installation/"><u>Is Your System up to Date for Windows 11 Installation?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-steam-disconnect-issues/"><u>Overcoming Windows Steam Disconnect Issues</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/seamless-video-conferencing-zoom-and-xbox-playground-for-2024/"><u>Seamless Video Conferencing Zoom & Xbox Playground for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/srt-production-via-xml-ssa-and-ttml-conversions-for-2024/"><u>SRT Production via XML, SSA & TTML Conversions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-five-data-usage-practices-in-win11/"><u>Understanding Five Data Usage Practices in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-win-friendly-secure-software-archives/"><u>Unveiling Win-Friendly, Secure Software Archives</u></a></li>
</ul></div>

