---
title: Lowering High Resource Demand in Device-to-Device Interaction Windows
date: 2024-09-30T23:48:26.394Z
updated: 2024-10-03T23:41:55.935Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Lowering High Resource Demand in Device-to-Device Interaction Windows
excerpt: This Article Describes Lowering High Resource Demand in Device-to-Device Interaction Windows
keywords: D2D Low Cost,Efficient D2D Devices,Energy-Saving D2D,D2D Power Reduction,Resource-Efficient D2D,Eco-Friendly D2D Interaction,Sustainable D2D Communication
thumbnail: https://thmb.techidaily.com/d8e6435243e7bdae68e29ae66158699a00161b12482bc1fecd3d439c888dea97.png
---

## Lowering High Resource Demand in Device-to-Device Interaction Windows

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
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145079/17095" target="_top" id="2145079">
  <img src="//a.impactradius-go.com/display-ad/17095-2145079" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145079/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-step-by-step-guide-incorporating-tunes-into-instagram-reels/"><u>[New] 2024 Approved Step-by-Step Guide Incorporating Tunes Into Instagram Reels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-folder-size-evaluation-using-powershell-commands/"><u>Demystifying Folder Size Evaluation Using PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-alternatives-to-cortana-in-windows-10/"><u>Exploring Alternatives to Cortana in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-graphic-card-compatibility-with-fortnite-on-windows-platforms/"><u>Fixing Graphic Card Compatibility with Fortnite on Windows Platforms</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-decoding-youtube-analytics-insights-for-every-content-creator/"><u>In 2024, Decoding YouTube Analytics Insights for Every Content Creator</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-lava-blaze-2-pro-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Lava Blaze 2 Pro FRP Locks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/microsofts-gpt-influence-how-to-attribute-references-properly-in-scholarship/"><u>Microsoft's GPT Influence: How to Attribute References Properly in Scholarship</u></a></li>
<li><a href="https://fox-that.techidaily.com/optimizing-iphone-photography-tips-for-low-megapixel-cameras/"><u>Optimizing iPhone Photography: Tips for Low-Megapixel Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-5-must-have-pc-tools/"><u>Streamline Your System: 5 Must-Have PC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-concealreveal-windows-security-zones/"><u>Tactics to Conceal/Reveal Windows Security Zones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-top-7-methods-for-windows-11-excellence/"><u>Transform Your Workflow: Top 7 Methods for Windows 11 Excellence</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/unleash-the-power-of-memes-with-twitter-video-to-gif-transformation-for-2024/"><u>Unleash the Power of Memes with Twitter Video-to-GIF Transformation for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unveiling-the-performance-of-samsungs-cf591-in-modern-gaming-scenarios/"><u>Unveiling the Performance of Samsung's CF591 in Modern Gaming Scenarios</u></a></li>
</ul></div>

