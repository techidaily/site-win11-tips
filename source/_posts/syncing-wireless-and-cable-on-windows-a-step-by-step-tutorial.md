---
title: "Syncing Wireless and Cable on Windows: A Step-by-Step Tutorial"
date: 2024-12-16T16:50:45.280Z
updated: 2024-12-22T01:49:32.696Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-how-luts-revolutionize-your-photo-editing-experience/"><u>[New] 2024 Approved How LUTs Revolutionize Your Photo Editing Experience</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-uncover-the-best-12-flipscreen-vlogging-cameras-on-a-budget/"><u>[New] 2024 Approved Uncover the Best 12 Flipscreen Vlogging Cameras on a Budget</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-essentials-of-drafting-engaging-vlogger-speeches-for-2024/"><u>[Updated] Essentials of Drafting Engaging Vlogger Speeches for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-advanced-tips-for-mastering-color-grading-via-3d-luts-in-photoshop/"><u>2024 Approved Advanced Tips for Mastering Color Grading via 3D LUTs in Photoshop</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-newest-msi-bluetooth-software-for-enhanced-wireless-communication-on-windows-pcs/"><u>Download the Newest MSI Bluetooth Software for Enhanced Wireless Communication on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-non-functional-resource-monitor-apps-on-win11/"><u>How to Tackle Non-Functional Resource Monitor Apps on Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-vivo-y78t-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Vivo Y78t Devices</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-hashtags-enhance-your-gaming-youtube-content/"><u>In 2024, Mastering Hashtags Enhance Your Gaming YouTube Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-directory-restarts-for-distro-and-catroot2-in-ws11/"><u>Navigating Directory Restarts for Distro & Catroot2 in WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-typing-delay-7-tricks-for-windows-1011/"><u>Overcoming Typing Delay: 7 Tricks for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-fn-button-actions-in-windows-11/"><u>Personalizing FN Button Actions in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/premiere-add-ons-for-firefox-recording/"><u>Premiere Add-Ons for Firefox Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-remote-links-fixing-disconnected-devices-on-pc/"><u>Restoring Remote Links: Fixing Disconnected Devices on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-adjustments-for-enhanced-devices-with-windows-11/"><u>Streamlined Adjustments for Enhanced Devices with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stylish-practicality-asus-vivobook-s-15s-perfect-fusion/"><u>Stylish Practicality - ASUS Vivobook S 15'S Perfect Fusion</u></a></li>
</ul></div>

