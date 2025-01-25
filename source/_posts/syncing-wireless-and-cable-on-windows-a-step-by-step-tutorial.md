---
title: "Syncing Wireless and Cable on Windows: A Step-by-Step Tutorial"
date: 2025-01-18T17:40:07.620Z
updated: 2025-01-24T23:54:32.353Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.

6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-choosing-the-right-format-boosting-your-youtube-videos-performance-for-2024/"><u>[New] Choosing the Right Format – Boosting Your YouTube Videos’ Performance for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-live-and-record-flawlessly-find-the-best-conference-tech-today/"><u>[New] In 2024, Live and Record Flawlessly - Find the Best Conference Tech Today</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/accidental-tiktok-overview-can-i-see-previous-videos-in-2024/"><u>Accidental TikTok Overview – Can I See Previous Videos, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-addressing-file-creation-fails-in-windows-error-30005/"><u>Comprehensively Addressing File Creation Fails in Windows Error 30005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-solving-the-application-couldnt-start-error/"><u>Deciphering and Solving The Application Couldn't Start Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-techniques-for-launching-windows-calculator/"><u>Efficient Techniques for Launching Windows' Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-error-0x80073d26-in-microsoft-store/"><u>Fixing Windows 10/11 Error 0X80073D26 in Microsoft Store</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-to-producing-impactful-lifestyle-motivational-content-for-2024/"><u>Guide to Producing Impactful Lifestyle Motivational Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-pc-screen-intensity-on-windows-11/"><u>How to Control PC Screen Intensity on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-realme-11x-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Realme 11X 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-seconds-life-on-fb-for-2024/"><u>In Seconds, Life On FB for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/quick-fixes-how-to-effectively-eliminate-on-screen-text-in-your-videos/"><u>Quick Fixes: How to Effectively Eliminate On-Screen Text in Your Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-increase-space-on-win11-drives-without-trashing-data-max-156-chars/"><u>Strategies to Increase Space on Win11 Drives Without Trashing Data (Max 156 Chars)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-path-to-ingenious-visuals-mastery-over-microsofts-copilot/"><u>The Path to Ingenious Visuals: Mastery Over Microsoft's Copilot</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-xiaomi-redmi-note-12-5g-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Xiaomi Redmi Note 12 5G Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-quick-access-to-file-explorer-via-onedrive/"><u>Transitioning From Quick Access to File Explorer via OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-resolving-package-registration-errors-in-images/"><u>Troubleshooting Windows 11: Resolving Package Registration Errors in Images</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unleashing-power-and-play-the-definitive-rankings-of-2024s-elite-gaming-laptops-by-leading-brands-like-razer-acer-msi-analysis/"><u>Unleashing Power and Play: The Definitive Rankings of 2024'S Elite Gaming Laptops by Leading Brands Like Razer, Acer, MSI Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-battle-against-the-d3d11-gpu-hurdle-in-w11w10/"><u>Winning Battle Against the D3D11 GPU Hurdle in W11/W10</u></a></li>
</ul></div>

