---
title: Strategies to Reduce Memory Consumption by Connected Devices Software
date: 2024-10-16T01:27:04.482Z
updated: 2024-10-21T01:38:05.573Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Reduce Memory Consumption by Connected Devices Software
excerpt: This Article Describes Strategies to Reduce Memory Consumption by Connected Devices Software
keywords: LowMemoryDevicesTips,DeviceSoftwareOptimization,EfficientDeviceUsage,OptimalConnectedDevices,MemorySavingStrategies,SoftwareLowFootprint,ResourceSmartDevices
thumbnail: https://thmb.techidaily.com/13322664753ec1bcb9b951122efdf005d8bc61a3a13c44fac0ae0c8584b8720e.jpg
---

## Strategies to Reduce Memory Consumption by Connected Devices Software

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

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880940/19272" target="_top" id="1880940">
  <img src="//a.impactradius-go.com/display-ad/19272-1880940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880940/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-support.techidaily.com/new-premium-energy-packs-for-gopro-hero5-black-certified-and-counterfeit-options/"><u>[New] Premium Energy Packs for GoPro Hero5 Black – Certified & Counterfeit Options</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-10-essential-tips-for-achieving-wealth-through-youtube-video-views/"><u>[Updated] 10 Essential Tips for Achieving Wealth Through YouTube Video Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-wma-en-aac-facile-et-gratuite-sur-internet-audioconverterpro/"><u>Conversion WMA en AAC Facile Et Gratuite Sur Internet - AudioConverterPro</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/default-text-configuration-options/"><u>Default Text Configuration Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargue-su-clave-de-activacion-gratuita-para-el-convertidor-de-videos-de-movavi/"><u>Descargue Su Clave De Activación Gratuita Para El Convertidor De Videos De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-convert-your-asf-media-formats-into-anything-you-need-using-the-movavi-video-converter/"><u>Easily Convert Your ASF Media Formats Into Anything You Need - Using the Movavi Video Converter</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-k11x-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from K11x</u></a></li>
<li><a href="https://win11-tips.techidaily.com/en-lukkelse-til-at-snite-din-forhor-med-fjerntrimmning-af-de-uonskede-avlejningsdeler-i-filmen/"><u>En Lukkelse Til At Snite Din Forhør Med Fjerntrimmning Af De Uønskede Avlejningsdeler I Filmen</u></a></li>
<li><a href="https://techtrends.techidaily.com/fixing-connection-not-private-errors-tips-and-solutions/"><u>Fixing 'Connection Not Private' Errors: Tips and Solutions</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-life360-shows-wrong-location-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Life360 Shows Wrong Location On Nokia C110? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instagram-to-soundtrack-the-complete-conversion-manual/"><u>In 2024, Instagram to Soundtrack The Complete Conversion Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-image-dimensions-the-ultimate-movavi-resize-tutorial/"><u>Mastering Image Dimensions: The Ultimate Movavi Resize Tutorial</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/by-step-guide-to-collab-videos-and-channel-growth-for-2024/"><u>Step-by-Step Guide to Collab Videos & Channel Growth for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-simples-pour-envoi-de-films-via-courriel/"><u>Techniques Simples Pour Envoi De Films via Courriel</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-future-is-here-explore-potential-specs-launch-timeframe-and-cost-estimations-for-the-new-apple-watch-ultra-2/"><u>The Future Is Here – Explore Potential Specs, Launch Timeframe & Cost Estimations for the New Apple Watch Ultra 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-images-into-webp-format-instantly-and-free-with-movavis-online-tool/"><u>Transform Images Into WebP Format Instantly and Free with Movavi's Online Tool</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-resolving-discords-dark-mode-while-screen-capturing/"><u>Troubleshooting: Resolving Discord's Dark Mode While Screen Capturing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asf-mp4/"><u>자이로나스터: 무료 ASF 영상 데이터를 MP4로 구성하기</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726227055668-wavmkv-movavi/"><u>シェア機能付きWAVからMKVへのオンライン無償変換 - Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    