---
title: Improving Device Linking Performance with Reduced RAM Consumption
date: 2024-11-26T17:33:44.846Z
updated: 2024-11-27T16:31:38.322Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Improving Device Linking Performance with Reduced RAM Consumption
excerpt: This Article Describes Improving Device Linking Performance with Reduced RAM Consumption
keywords: Link Boost Efficiency,Low-RAM Optimization,Devices Link Speedup,Memory Usage Minimize,Performance Enhancement,RAM Reduction Techniques,Device Connectivity Improvement
thumbnail: https://thmb.techidaily.com/b1557e3d9700a9810b8b9bbec88362c53ba5a3f98f5f309c7652fc768db4746d.jpg
---

## Improving Device Linking Performance with Reduced RAM Consumption

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/updated-seamless-techniques-to-share-your-screen-on-google-meet-for-2024/"><u>[Updated] Seamless Techniques to Share Your Screen on Google Meet for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-retroactive-video-mastery-for-android-users/"><u>2024 Approved Retroactive Video Mastery for Android Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-seamless-srt-and-mp4-fusion-the-ultimate-guide/"><u>2024 Approved Seamless SRT & MP4 Fusion – The Ultimate Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-oppo-find-x6-pro-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Oppo Find X6 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-org-managed-configuration-issues-in-windows-11-os/"><u>Correcting Org-Managed Configuration Issues in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-the-default-path-failure-on-windows-devices/"><u>Cure the Default Path Failure on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-win10s-sound-flaw-error-xc00d36b4/"><u>Eliminating Win10's Sound Flaw: Error Xc00d36b4</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elite-echoes-outstanding-games-for-your-google-cardboard/"><u>Elite Echoes Outstanding Games for Your Google Cardboard</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-easy-steps-on-how-to-create-a-new-apple-id-account-on-apple-iphone-11-by-drfone-ios/"><u>In 2024, Easy Steps on How To Create a New Apple ID Account On Apple iPhone 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-apple-iphone-se-2020-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Your Apple iPhone SE (2020) Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reconnect-lost-razer-devices-via-windows-synapse/"><u>Methods to Reconnect Lost Razer Devices via WIndows' Synapse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-practices-for-audio-recordings/"><u>Proven Windows Practices for Audio Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-0x80070522-clients-access-rights-enhancement/"><u>Tackling Windows Error 0X80070522: Client's Access Rights Enhancement</u></a></li>
<li><a href="https://program-issues.techidaily.com/top-10-tips-to-eliminate-battlefield-5-latency-issues/"><u>Top 10 Tips to Eliminate Battlefield 5 Latency Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-power-in-windows-11-banishing-slowness/"><u>Unleash Power in Windows 11: Banishing Slowness</u></a></li>
<li><a href="https://technical-tips.techidaily.com/upgrading-to-the-newest-apple-phone-compare-iphone-16-with-15-essential-factors-revealed-gadgetsphere/"><u>Upgrading to the Newest Apple Phone? Compare iPhone 16 with 15 – Essential Factors Revealed | GadgetSphere</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    