---
title: Enhancing Resource Management for Connected Services on PCs
date: 2024-11-13T19:34:32.842Z
updated: 2024-11-17T19:06:16.418Z
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

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-enhanced-mac-technology-video-plus-sound-record/"><u>[New] In 2024, Enhanced Mac Technology Video + Sound Record</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-navigating-bandicams-new-features-the-2023-breakdown/"><u>[New] Navigating Bandicam's New Features – The 2023 Breakdown</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-zap-extra-details-sharpen-logitech-webcam-recordings-for-2024/"><u>[Updated] Zap Extra Details - Sharpen Logitech Webcam Recordings for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/15-innovative-cost-free-photo-manipulation-software/"><u>15 Innovative, Cost-Free Photo Manipulation Software</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-guide-compatible-drivers-and-software-for-brother-hl-l2380dw-on-windows/"><u>Download Guide: Compatible Drivers & Software for Brother HL-L2380DW on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/google-play-setup-a-comprehensible-path/"><u>Google Play Setup: A Comprehensible Path</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-poco-x5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Xiaomi Redmi A2? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-gt-neo-5-se-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Realme GT Neo 5 SE Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-the-upgrade-from-samsung-galaxy-s22-ultra-to-s23-ultra-significant-enough-worth-switching-this-year-cnet-analysis/"><u>Is the Upgrade From Samsung Galaxy S22 Ultra to S23 Ultra Significant Enough Worth Switching This Year? | CNET Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-device-awareness-in-power-mode-slumber/"><u>Leveraging Device Awareness in Power Mode Slumber</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-anomaly-zero-error-correction-guide/"><u>Microsoft Store Anomaly: Zero-Error Correction Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-peeky-tabs-strategies-for-edge-on-w11/"><u>No Peeky Tabs: Strategies for Edge on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-file-images-in-windows-11-the-how-to-guide/"><u>Reinstating File Images in Windows 11 – The How-To Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-grayed-out-secure-boot-on-windows-bios-settings/"><u>Restoring Grayed-Out Secure Boot on Windows BIOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-recover-non-identified-wireless-networks-in-win11/"><u>Strategies to Recover Non-Identified Wireless Networks in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switch-off-windows-record-of-launches/"><u>Switch Off Windows Record of Launches</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-in-this-article-we-will-review-gopro-quik-for-desktop-and-recommend-alternatives-to-gopro-quik-pc/"><u>Updated In 2024, In This Article, We Will Review Gopro Quik for Desktop and Recommend Alternatives to Gopro Quik Pc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wake-up-rituals-for-keyboard-and-mouse-in-1011-environments/"><u>Wake-Up Rituals for Keyboard & Mouse in 10/11 Environments</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    