---
title: Step-by-Step Methods to Use Both Network Types on a Single Windows Device
date: 2025-02-11T17:03:43.599Z
updated: 2025-02-15T18:33:58.956Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-share.techidaily.com/new-constructing-an-inviting-subscribe-link-for-youtube-enthusiasts-for-2024/"><u>[New] Constructing an Inviting Subscribe Link for YouTube Enthusiasts for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-obs-vs-shadowplay-the-ultimate-showdown-for-gamers/"><u>[New] In 2024, OBS vs ShadowPlay The Ultimate Showdown for Gamers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/1715860661707-new-learn-to-record-mac-display-like-a-pro/"><u>[New] Learn to Record MAC Display Like a Pro!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2021digiarty-macx-dvd-ripper-proplusamazon3000/"><u>「2021春節Digiarty MacX DVD Ripper Pro永久驅動器+Amazonギフト款券3,000元大獎：幸福新年抽選！」</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-the-best-5-book-video-promotions-ever-made/"><u>2024 Approved The Best 5 Book Video Promotions Ever Made</u></a></li>
<li><a href="https://driver-install.techidaily.com/boost-amd-rx-5500xt-driver-upgrades/"><u>Boost AMD RX 5500XT Driver Upgrades</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-vivo-y100-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-microsofts-web-browser-in-win11/"><u>How to Remove Microsoft's Web Browser in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-skip-the-onedrive-icon-on-windows-11-file-explorer/"><u>How To Skip the OneDrive Icon on Windows 11 File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-file-damage-error-code-0x80070570-in-windows-11/"><u>Remedy for File Damage Error (Code 0X80070570) in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-winservicesexe-in-windows-systems/"><u>The Role of Winservices.exe in Windows Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-significance-of-video-in-client-promotional-power/"><u>The Significance of Video in Client Promotional Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-netgear-nighthawk-x6-wi-fi-expansion-unit-a-full-feature-breakdown/"><u>Ultimate Guide to Netgear Nighthawk X6 Wi-Fi Expansion Unit - A Full Feature Breakdown</u></a></li>
</ul></div>

