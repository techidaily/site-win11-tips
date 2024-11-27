---
title: Enhancing Resource Management for Connected Services on PCs
date: 2024-11-25T16:06:51.783Z
updated: 2024-11-27T16:14:21.489Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing Resource Management for Connected Services on PCs
excerpt: This Article Describes Enhancing Resource Management for Connected Services on PCs
keywords: PC Service Optimization,PC Connectivity Boost,Resource Mgmt Efficiency,Service Networking PC,Smart PC Resources,Connected Services Improve,Effective PC Service Management
thumbnail: https://thmb.techidaily.com/5d3200ea7acc8a267e33f7e3f6be29344352dcba610c7cb281d20c740b294fae.jpg
---

## Enhancing Resource Management for Connected Services on PCs

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-essential-budget-gaming-hardware-the-ultimate-keyboard-list/"><u>[New] Essential Budget Gaming Hardware The Ultimate Keyboard List</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-methods-for-a-no-ads-experience-on-social-platforms/"><u>[New] Methods for a No-Ads Experience on Social Platforms</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-affordable-acoustic-amps-and-mics-for-video-voyagers-for-2024/"><u>[Updated] Affordable Acoustic Amps and Mics for Video Voyagers for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-exploring-gospel-music-how-to-download-and-modify-your-ringtone-for-2024/"><u>[Updated] Exploring Gospel Music How to Download & Modify Your Ringtone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726221539564-aviswf-movavi/"><u>網頁版AVI到SWF自由下載 - MOVAVI影片轉化工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swf-mpeg/"><u>線上無限制 SWF 改編成 MPEG - 動視高效能格式化器</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-look-at-the-future-leading-photo-framing-apps-for-2024/"><u>A Look at the Future Leading Photo Framing Apps for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/a-list-cameras-for-dreamy-4k-videos-18-selection/"><u>A-List Cameras for Dreamy 4K Videos (#18 Selection)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-itel-a05s-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Itel A05s | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-gratuita-de-archivos-wmv-a-m4v-en-linea-con-movavi/"><u>Conversión Gratuita De Archivos WMV a M4V en Línea Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-conversion-of-ppm-images-to-tiff-format-movavis-online-tool/"><u>Free Conversion of PPM Images to TIFF Format - Movavi's Online Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuit-veillez-transformer-des-fichiers-videos-en-mov-en-wma-enligne-movavi-solutions/"><u>Gratuit Veillez Transformer Des FICHIERS VIDEOS en MOV en WMA Enligne - Movavi Solutions</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-data-from-apple-iphone-13-to-zte-phones-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Data from Apple iPhone 13 to ZTE Phones | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/nvidia-driver-updates-for-gtx-1660-a-quick-and-straightforward-approach/"><u>NVIDIA Driver Updates for GTX 1660: A Quick & Straightforward Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/topos-player-and-videosnack-los-mejores-clientes-de-torrents-y-visualizadores/"><u>Topos Player & VideoSnack: Los Mejores Clientes De Torrents Y Visualizadores</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-aiff-in-mp3-gratuitamente-con-movavi-il-metodo-piu-semplice/"><u>Trasforma I Tuoi AIFF in MP3 Gratuitamente Con Movavi - Il Metodo Più Semplice!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wav-vs-mp3-a-comprehensive-guide-for-high-quality-audio-movavi/"><u>Understanding WAV Vs. MP3: A Comprehensive Guide for High-Quality Audio - Movavi</u></a></li>
</ul></div>

