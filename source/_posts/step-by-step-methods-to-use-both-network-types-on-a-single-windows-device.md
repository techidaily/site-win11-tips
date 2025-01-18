---
title: Step-by-Step Methods to Use Both Network Types on a Single Windows Device
date: 2025-01-17T16:12:15.867Z
updated: 2025-01-18T16:33:04.848Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-posts.techidaily.com/new-in-2024-secrets-of-windows-10-effortless-media-importation-methods/"><u>[New] In 2024, Secrets of Windows 10 Effortless Media Importation Methods</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-step-by-step-guide-to-record-google-meet-on-smartphones/"><u>[New] Step-by-Step Guide to Record Google Meet on Smartphones</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-how-to-edit-the-length-of-a-video-on-youtube/"><u>[Updated] 2024 Approved How to Edit the Length of a Video on YouTube</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-nokia-c12-pro-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/deciphering-the-auto-cut-functionality-in-imovie-for-2024/"><u>Deciphering the Auto-Cut Functionality in iMovie for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-integrity-stick-to-proven-methods-for-win-11-keys/"><u>Ensuring Integrity: Stick to Proven Methods for Win 11 Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-no-start-windows-vms-and-vmware-error/"><u>Essential Fixes: No-Start Windows VMs & VMware Error</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-captured-words-top-10-mobile-writing-tools-for-images/"><u>In 2024, Captured Words Top 10 Mobile Writing Tools for Images</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-cutting-edge-creatives-on-your-feed/"><u>In 2024, The Cutting-Edge Creatives on Your Feed</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-windows-to-its-fundamental-backup-state/"><u>Resetting Windows to Its Fundamental Backup State</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-a-non-responsive-xbox-on-your-pc/"><u>Reviving a Non-Responsive Xbox on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionizing-ui-8-bubble-ui-personalization-tricks-for-win1011/"><u>Revolutionizing UI: 8 Bubble UI Personalization Tricks for Win10/11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/tips-for-enhancing-online-presence-with-imovie-on-vimeo-for-2024/"><u>Tips for Enhancing Online Presence with iMovie on Vimeo for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-impact-of-eradicating-windows-11s-taskbar-chatting-functionality/"><u>Unveiling the Impact of Eradicating Windows 11'S Taskbar Chatting Functionality.</u></a></li>
</ul></div>

