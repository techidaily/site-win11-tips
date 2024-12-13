---
title: "Syncing Two Networks: A Guide to Using Wi-Fi & Ethernet Together on Windows"
date: 2024-12-06T20:38:39.294Z
updated: 2024-12-12T17:11:49.318Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Syncing Two Networks: A Guide to Using Wi-Fi & Ethernet Together on Windows"
excerpt: "This Article Describes Syncing Two Networks: A Guide to Using Wi-Fi & Ethernet Together on Windows"
keywords: Wi-Fi + Ethernet Windows,Sync Wi-Fi Ethernet Windows,Network Integration Windows,Combine Wi-Fi Ethernet Guide,Windows Wi-Fi Ethernet Use,Ethernet & Wi-Fi Windows Tips,Windows Sync Wi-Fi/Ethernet
thumbnail: https://thmb.techidaily.com/1127690728774d68859773ac2967a71d9b05c7378c0abebd2da2f4a67474809a.jpg
---

## Syncing Two Networks: A Guide to Using Wi-Fi & Ethernet Together on Windows

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-essential-recording-tips-capturing-video-from-macbook-pro/"><u>[New] In 2024, Essential Recording Tips Capturing Video From MacBook Pro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-streamlining-post-processing-with-effective-use-of-luts-in-pscc/"><u>[New] Streamlining Post-Processing with Effective Use of LUTs in PSCC</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-superior-capture-software-for-mac-excluding-bandicam-for-2024/"><u>[New] Superior Capture Software for Mac, Excluding Bandicam for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-six-easy-steps-to-acquire-fb-links-for-free/"><u>[Updated] In 2024, Six Easy Steps to Acquire FB Links for FREE</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-echoes-of-entertainment-vr-cinematic-worlds/"><u>2024 Approved Echoes of Entertainment VR Cinematic Worlds</u></a></li>
<li><a href="https://blog-min.techidaily.com/6-ways-to-transfer-contacts-from-xiaomi-redmi-note-12-pro-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>6 Ways To Transfer Contacts From Xiaomi Redmi Note 12 Pro 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp2mp3-movavi/"><u>優化MP2為MP3的無限制線上移動 - 運用Movavi 解決方案</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comment-transformer-facilement-un-video-mkv-en-format-avi/"><u>Comment Transformer Facilement Un Vidéo MKV en Format AVI?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-gifs-from-3gp-files-without-cost-quick-and-easy-video-editing-by-movavi/"><u>Create GIFs From 3GP Files Without Cost - Quick & Easy Video Editing by Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/flvmpeg-movavi/"><u>FLVからMPEGへの無料で簡単なオンライン変換 - Movavi</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/from-play-to-record-the-fraps-verdict-for-2024/"><u>From Play to Record The Fraps Verdict for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/interview-success-with-chatgpt-top-tips-and-techniques/"><u>Interview Success with ChatGPT: Top Tips and Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-nastinovy-skoleni-podrobna-postupy-a-vikna-pro-starsich-hracici/"><u>Movavi Nástinový Školení: Podrobná Postupy a Víkna Pro Starších Hracíči</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-bmp-to-png-conversion-by-movavi-get-it-free/"><u>Online BMP to PNG Conversion by Movavi: Get It FREE!</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/seamless-transition-from-windows-to-linux-with-ubuntu-and-cinnamon-a-beginners-guide/"><u>Seamless Transition From Windows to Linux with Ubuntu & Cinnamon - A Beginner's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-12-caddy-per-display-per-computer-portatili-suggerimenti-e-consigli-di-ottimizzazione-seo/"><u>Top 12 Caddy Per Display Per Computer Portatili: Suggerimenti E Consigli Di Ottimizzazione SEO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transcodificador-de-video-sin-coste-online-como-cambiar-m4v-a-mpeg-con-movavi-gratis/"><u>Transcodificador De Video Sin Coste Online: Cómo Cambiar M4V a MPEG Con Movavi Gratis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-wma-in-ogg-gratuitamente-online-utilizzando-movavi/"><u>Trasforma I Tuoi WMA in Ogg Gratuitamente Online Utilizzando Movavi!</u></a></li>
</ul></div>

