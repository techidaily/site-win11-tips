---
title: Tactics for Lessening RAM Load in User-Connected Platforms
date: 2024-10-12T01:43:19.270Z
updated: 2024-10-15T08:32:53.814Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tactics for Lessening RAM Load in User-Connected Platforms
excerpt: This Article Describes Tactics for Lessening RAM Load in User-Connected Platforms
keywords: Reduce RAM Usage,Minimize Memory Load,Decrease System Burden,Optimize RAM Efficiency,Lower Resource Consumption,Cut Down Platform Demand,Enhance User-System Synergy
thumbnail: https://thmb.techidaily.com/606be4e6c5a29affde6b0062eb01d7884930a95dd58e84baf4df0ccd1b6b1a9d.jpg
---

## Tactics for Lessening RAM Load in User-Connected Platforms

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043618/7443" target="_top" id="2043618">
  <img src="//a.impactradius-go.com/display-ad/7443-2043618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043618/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151889/7443" target="_top" id="2151889">
  <img src="//a.impactradius-go.com/display-ad/7443-2151889" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<span id="1304648">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304648%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304648/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-all-encompassing-iptv-access-strategies/"><u>[New] All-Encompassing IPTV Access Strategies</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-fb-video-to-mp3-digital-audio-extraction-guide/"><u>[Updated] 2024 Approved FB Video to MP3 Digital Audio Extraction Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-mastering-the-art-of-sniping-on-mac-with-these-tools/"><u>[Updated] In 2024, Mastering the Art of Sniping on Mac with These Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-the-most-ignored-yet-crucial-windows-11-features/"><u>A Guide to the Most Ignored Yet Crucial Windows 11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-strongest-passwords-effortlessly-with-these-7-free-generators/"><u>Access Strongest Passwords Effortlessly With These 7 Free Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-affected-windows-shield-functions-on-win-11/"><u>Addressing Affected Windows Shield Functions on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-unified-sticky-note-syncing-on-win11/"><u>Addressing Non-Unified Sticky Note Syncing on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-stealth-tactics-eliminate-11s-search-icon/"><u>Advanced Stealth Tactics: Eliminate 11'S Search Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-efficient-voice-access-on-windows/"><u>Advanced Tips for Efficient Voice Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-interruptions-resolving-steams-error-code-e84/"><u>Avoid Interruptions: Resolving Steam’s Error Code E84</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-inquiries-stealthy-strategies-for-secure-credentials-in-win-11/"><u>Avoiding Inquiries: Stealthy Strategies for Secure Credentials in Win 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/echoes-of-harmony-in-a-social-sphere-for-2024/"><u>Echoes of Harmony in a Social Sphere for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719202889022-efficient-tips-for-resolving-common-windows-problems/"><u>Efficient Tips for Resolving Common Windows Problems</u></a></li>
<li><a href="https://blog-min.techidaily.com/future-proof-video-coding-av1-or-hevc-analyzing-superiority-for-next-gen-media/"><u>Future-Proof Video Coding: AV1 or HEVC – Analyzing Superiority for Next-Gen Media</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/gain-german-proficiency-from-binge-watched-show/"><u>Gain German Proficiency From Binge-Watched Show</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-realme-11-proplus-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Realme 11 Pro+ Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/leading-picture-holding-portals-for-2024/"><u>Leading Picture Holding Portals for 2024</u></a></li>
<li><a href="https://win-news.techidaily.com/mbr-gpt-ssd/"><u>MBR プラッターをGPT SSDにコピーする方法 - インストールなしで</u></a></li>
<li><a href="https://win-manuals.techidaily.com/windows-1011programdata/"><u>Windows 10/11でProgramDataフォルダにアクセスする方法</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    