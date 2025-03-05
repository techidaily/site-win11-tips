---
title: "Syncing Wireless and Cable on Windows: A Step-by-Step Tutorial"
date: 2025-02-27T01:28:32.757Z
updated: 2025-03-04T23:22:36.417Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Syncing Wireless and Cable on Windows: A Step-by-Step Tutorial"
excerpt: "This Article Describes Syncing Wireless and Cable on Windows: A Step-by-Step Tutorial"
keywords: Windows Sync Tech,Cable Wi-Fi Guide,Bluetooth Setup Windows,Link Cable Wireless,Cable Network Integration,Wi-Fi Connectivity Windows,Hybrid Wireless Config
thumbnail: https://thmb.techidaily.com/f7564240f8faa92ac0e388d789a175a79bd1b95533429025b3702f8272211ea0.jpg
---

## Syncing Wireless and Cable on Windows: A Step-by-Step Tutorial

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-capture-and-save-everything-on-your-screen/"><u>[New] 2024 Approved Capture & Save Everything on Your Screen</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-why-my-instagram-videos-turned-upside-down-whats-going-on/"><u>[New] 2024 Approved Why My Instagram Videos Turned Upside Down – What's Going On?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-elevate-your-social-media-reach-fb-ad-mastery-techniques/"><u>[Updated] 2024 Approved Elevate Your Social Media Reach FB Ad Mastery Techniques</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-av1-versus-vp9-the-ultimate-codec-showdown/"><u>[Updated] AV1 Versus VP9 The Ultimate Codec Showdown</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-interconnecting-your-music-collection-across-services/"><u>[Updated] Interconnecting Your Music Collection Across Services</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-how-to-share-youtube-link-on-instagram-story/"><u>2024 Approved How to Share YouTube Link on Instagram Story</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-on-managing-users-in-the-cli/"><u>Expert Tips on Managing Users in the CLI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-in-windows-11-avoid-these-slips/"><u>Navigating New Horizons in Windows 11: Avoid These Slips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-your-cortana-experiences-step-by-step-guide/"><u>Saving Your Cortana Experiences: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-solving-windows-errors-top-8-methods/"><u>Swiftly Solving Windows Errors: Top 8 Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-customize-windows-1011-icons-with-spacing-tweaks/"><u>Title: Customize Windows 10/11 Icons with Spacing Tweaks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/unleashing-creativity-advanced-obs-techniques-explained-for-2024/"><u>Unleashing Creativity Advanced OBS Techniques Explained for 2024</u></a></li>
</ul></div>

