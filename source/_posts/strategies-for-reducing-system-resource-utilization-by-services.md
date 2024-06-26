---
title: Strategies for Reducing System Resource Utilization by Services
date: 2024-06-25T16:22:30.224Z
updated: 2024-06-26T16:22:30.224Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Reducing System Resource Utilization by Services
excerpt: This Article Describes Strategies for Reducing System Resource Utilization by Services
keywords: Reduce Resource Usage,Service Efficiency Boost,Optimize System Resources,Minimize Service Footprint,Energy-Saving Strategies,Performance Enhancement Tactics,Service Resource Management
thumbnail: https://thmb.techidaily.com/756e6cbc4b4a2e3ac30671657870528bb336d9b2f0f8b2cf5d7bebdde4893059.jpg
---

## Strategies for Reducing System Resource Utilization by Services

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

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

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

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
<li><a href="https://win11-tips.techidaily.com/step-into-the-world-of-windows-11-home/"><u>Step Into the World of Windows 11 Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-unopened-sharing-error-on-w10w11/"><u>How to Rectify Unopened Sharing Error on W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-audio-service-restart-process-before-boot-up/"><u>Simplifying Audio Service Restart Process Before Boot Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-change-windows-startpage-configuration/"><u>Steps to Change Windows Startpage Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-workflow-why-the-latest-windows-outlook-matters/"><u>Revolutionize Your Workflow: Why the Latest Windows' Outlook Matters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successfully-overcome-windows-error-0x80070003-a-step-by-step-guide/"><u>Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-windows-1011-climate-choices/"><u>Exclusive Windows 10/11 Climate Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-vlc-input-compatibility-faults/"><u>Correcting Windows VLC Input Compatibility Faults</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-minecraft-filming-101-from-start-to-finish-for-2024/"><u>[New] Minecraft Filming 101  From Start to Finish for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/auditory-aesthetics-choosing-the-right-soundtracks-for-boxings-for-2024/"><u>Auditory Aesthetics  Choosing the Right Soundtracks for Boxings for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-exposing-sham-numbers-the-danger-of-fabricated-youtube-views-for-2024/"><u>[Updated] Exposing Sham Numbers  The Danger of Fabricated YouTube Views for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-the-ultimate-guide-to-slow-motion-video-playback-on-vlc/"><u>2024 Approved The Ultimate Guide to Slow Motion Video Playback on VLC</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-samsung-galaxy-f14-5g-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-visual-tweets-the-panorama-of-threaded-video/"><u>2024 Approved  Visual Tweets  The Panorama of Threaded Video</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-anonymize-your-media-top-10-free-face-blurring-apps-for-pc-and-mobile-for-2024/"><u>New Anonymize Your Media Top 10 Free Face Blurring Apps for PC and Mobile for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-samsung-galaxy-a15-4g-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Samsung Galaxy A15 4G to PC? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-escaping-tiktoks-silent-screens-methods-to-unshadowban-for-2024/"><u>[Updated] Escaping TikTok's Silent Screens  Methods to Unshadowban for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-launch-free-youtube-events-a-step-by-step-guide/"><u>2024 Approved  Launch Free Youtube Events  A Step-by-Step Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>