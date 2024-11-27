---
title: Optimizing Windows Memory Allocation for Connected User Services
date: 2024-11-21T16:18:53.019Z
updated: 2024-11-27T18:01:15.967Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing Windows Memory Allocation for Connected User Services
excerpt: This Article Describes Optimizing Windows Memory Allocation for Connected User Services
keywords: MemAllocWinUserServ,WinMemoryOptimize,ConnectUsServMem,WindowsMemoryAllok,AllokcNetServices,UserServiceMemOpt,ServConnWinSpace
thumbnail: https://thmb.techidaily.com/d44947af2d23263a61b2bb19233d3717a7fd178394378301c673d9cd094e466a.jpg
---

## Optimizing Windows Memory Allocation for Connected User Services

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/new-strategic-insights-into-making-emotional-connection-with-customer-success-videos/"><u>[New] Strategic Insights Into Making Emotional Connection with Customer Success Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-frosty-flourishes-at-the-winter-games/"><u>2024 Approved Frosty Flourishes at the Winter Games</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-online-with-leading-sites-facebook-twitter-instagram-and-youtube-journey/"><u>Connect Online with Leading Sites: Facebook, Twitter, Instagram and YouTube Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directory-discovery-3-approaches-on-windows-os/"><u>Directory Discovery: 3 Approaches on Windows OS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-dvd-tools-compatible-with-sierra/"><u>Essential DVD Tools Compatible with Sierra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-on-managing-users-in-the-cli/"><u>Expert Tips on Managing Users in the CLI</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-vivo-y200e-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Vivo Y200e 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-meizu-21-pro-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Meizu 21 Pro To Phone | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-understanding-asmrs-health-perks/"><u>In 2024, Understanding ASMR's Health Perks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-in-windows-11-avoid-these-slips/"><u>Navigating New Horizons in Windows 11: Avoid These Slips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-your-cortana-experiences-step-by-step-guide/"><u>Saving Your Cortana Experiences: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11-rdp-fails-internal-error-resolution/"><u>Tackling Windows 11 RDP Fails: Internal Error Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-customize-windows-1011-icons-with-spacing-tweaks/"><u>Title: Customize Windows 10/11 Icons with Spacing Tweaks</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-poco-x5-pro-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Poco X5 Pro Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-frozen-shift-on-windows-pcs/"><u>Unlock Frozen Shift on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-future-key-upgrades-from-microsofts-feb-win11-patch/"><u>Unveiling the Future: Key Upgrades From Microsoft's Feb Win11 Patch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-through-improvement-not-just-innovation/"><u>Winning Through Improvement, Not Just Innovation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    