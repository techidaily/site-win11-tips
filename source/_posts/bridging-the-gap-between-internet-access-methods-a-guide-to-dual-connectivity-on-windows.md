---
title: "Bridging the Gap Between Internet Access Methods: A Guide to Dual Connectivity on Windows"
date: 2025-01-23T22:55:53.604Z
updated: 2025-01-24T18:24:27.181Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bridging the Gap Between Internet Access Methods: A Guide to Dual Connectivity on Windows"
excerpt: "This Article Describes Bridging the Gap Between Internet Access Methods: A Guide to Dual Connectivity on Windows"
keywords: Windows Dual Conn. Guide,Dual-Connect PC Tips,Enhancing Web Speed (Windows),Access Methods,Windows Connectivity Explained,Bridge Internet Gaps (Win),Optimize Win Browser Conn.
thumbnail: https://thmb.techidaily.com/769d83492280fd0660acd0112190d1d990d0e4305860168c39e79719f29b2ea7.jpg
---

## Bridging the Gap Between Internet Access Methods: A Guide to Dual Connectivity on Windows

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://some-knowledge.techidaily.com/updated-high-seas-of-hertz-best-websites-for-thrones-audio-files/"><u>[Updated] High Seas of Hertz Best Websites for Thrones Audio Files</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unravel-the-best-web-resources-for-perfecting-your-video-subtitles/"><u>[Updated] Unravel the Best Web Resources for Perfecting Your Video Subtitles</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-unveiling-the-key-to-thriving-in-online-communities-like-reddit-for-2024/"><u>[Updated] Unveiling the Key to Thriving in Online Communities Like Reddit for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-oppo-a58-4g-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Oppo A58 4G?</u></a></li>
<li><a href="https://article-tips.techidaily.com/elevate-your-edit-skills-with-these-pro-tiktok-tricks-for-2024/"><u>Elevate Your Edit Skills with These Pro TikTok Tricks for 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210399517-9781946088390-feminine-callings/"><u>Feminine Callings | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unwanted-hotkeys-during-typing-sessions/"><u>Fixing Unwanted Hotkeys During Typing Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-the-unseen-masterful-recovery-of-off-screen-applications-in-win-1011-6-tips/"><u>Recovering the Unseen: Masterful Recovery of Off-Screen Applications in Win 10/11 (6 Tips)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-authentication-failures/"><u>Remedying Windows Authentication Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-data-access-onedrive-sync-w-windows-microsoft-account/"><u>Simplifying Data Access: OneDrive Sync W/ Windows Microsoft Account</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/soluzioni-facile-ssd-m2-non-dettato-da-windows-11-utilizzare-i-11-stessi-metodi-di-resoluzione/"><u>SOLUZIONI FACILE: SSD M.2 NON DETTATO DA WINDOWS 11 - UTILIZZARE I 11 STESSI METODI DI RESOLUZIONE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncomplicating-docx-to-pdf-challenges-with-easy-steps-on-win-11-os/"><u>Uncomplicating Docx to PDF Challenges with Easy Steps on Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-utilizing-windows-11s-volume-mixer-feature/"><u>Understanding and Utilizing Windows 11'S Volume Mixer Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-errors-navigating-and-resolving-o365-glitches/"><u>Win 11 Errors: Navigating and Resolving O365 Glitches</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/z2-masterclass-smartphone-smarter-than-ever/"><u>Z2 Masterclass Smartphone Smarter Than Ever?</u></a></li>
</ul></div>

