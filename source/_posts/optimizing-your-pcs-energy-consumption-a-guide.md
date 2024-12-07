---
title: Optimizing Your PC's Energy Consumption - A Guide
date: 2024-12-04T19:39:20.048Z
updated: 2024-12-06T23:13:02.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing Your PC's Energy Consumption - A Guide
excerpt: This Article Describes Optimizing Your PC's Energy Consumption - A Guide
keywords: Power-Saving PC Tips,PC Energy Efficiency,Optimal PC Use,Low-Energy PC,Green PC Strategies,Save PC Power,Energy PC Guide
thumbnail: https://thmb.techidaily.com/d2b7e4746fe693895b4178e4d3a3d7272df65f201ddb10f4f23b159b9a8a8a69.jpg
---

## Optimizing Your PC's Energy Consumption - A Guide

 Your Windows laptop features a handy battery saver mode that allows you to stretch your device's battery life. Windows archives this by lowering the screen brightness, limiting background processes, and disabling certain visual effects and animations.

 Here we show you how to enable or disable battery saver mode on your Windows 10 or 11 laptop.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Enable or Disable Battery Saver Mode Using Quick Settings

 The[Quick Settings panel in Windows](https://www.makeuseof.com/use-quick-settings-on-windows-11/) provides access to frequently used features such as Wi-Fi, Bluetooth, Airplane Mode, and others. You can also access this panel to turn the battery saver mode on or off quickly.

 Simply press**Win + A** to open the Quick Settings panel, and then click the**Battery saver** icon to enable or disable it.

![Enable or Disable Battery Saver in via Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-quick-settings-panel.jpg)

 In case the Battery saver icon is missing, you can add it manually. Click the**pencil** icon at the bottom, and then select**Add > Battery saver** .

![Add Battery Saver Button to Quick Settings Panel in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/add-battery-saver-button-to-quick-settings-panel-in-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Enable or Disable Battery Saver Mode Using the Settings App

 Another way to turn the battery saver mode on or off in Windows is via the Settings app. To do so, use these steps:

1. Right-click on the**Start icon** and select**Settings** from the list.
2. In the**System** tab, click on**Power & battery** .
3. Under**Battery** , click on**Battery saver** to expand it.
4. Click the**Turn on now** button to enable battery saver mode.  
![Enable or Disable Battery Saver in via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the battery saver mode is on, you will see the**Turn off now** button instead. Further, plugging your laptop into a power outlet will also disable the battery saver mode.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Configure the Battery Saver Mode to Turn On Automatically on Windows

 Don’t want to enable the battery saver mode manually all the time? No problem. You can configure Windows to activate battery saver mode automatically whenever the battery level drops below a specific percentage. To do so, you can use the Windows Settings app. Here are the steps you can follow.

1. Press**Win + I** to open the Settings app.
2. Navigate to**System > Power & battery** .
3. Click on**Battery saver** to expand it.
4. Click the drop-down menu next to**Turn battery saver on automatically at** and select your preferred battery level.  
![Configure the Battery Saver Mode to Turn On Automatically in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-in-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can also prevent Windows from enabling battery saver mode on its own by selecting**Never** . Alternatively, if you want the battery saver mode to be enabled at all times, choose**Always** instead.

 Although the Settings app is the most commonly used method for configuring the battery saver mode in Windows, it's not the only option available. You can also use a command-line tool like Command Prompt or Windows PowerShell to configure the battery saver mode to turn on automatically. Here are the steps for the same.

1. Use one of the[many ways to open Command Prompt or PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command in the console and press**Enter** .  
`powercfg /setdcvalueindex scheme_current sub_energysaver esbattthreshold <BatteryPercentage>`

 Replace**<BatteryPercentage>** in the above command with the percentage below which you want the battery saver mode to kick in automatically. Unlike the Settings app, you can specify a custom battery level percentage between 0 and 100 using the command line method.

![Configure the Battery Saver Mode to Turn On Automatically Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-using-command-prompt.jpg)

 While PowerShell and Windows Terminal may look similar, they act very differently. Check our detailed guide to learn[the differences between PowerShell and Windows Terminal](https://www.makeuseof.com/windows-terminal-vs-powershell/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Easily Enable or Disable Battery Saver Mode on Windows

 Battery saver mode in Windows can come in handy when you're away from a power source. However, it's important to note that leaving battery saver mode on all the time can impact certain features, such as notifications and background app sync. Hence, it's best to enable battery saver mode only when necessary.

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-premium-dj-visuals-library-seamless-download-experience/"><u>[New] 2024 Approved Premium DJ Visuals Library - Seamless Download Experience</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-bridging-the-gap-youtube-editing-mastered-in-imovie-workflows/"><u>[Updated] Bridging the Gap YouTube Editing Mastered in iMovie Workflows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sticky-context-menus-in-windows-11-edition/"><u>Addressing Sticky Context Menus in Windows 11 Edition</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/best-tablets-of-2023-amaze-with-amazon-fire-or-go-with-samsung-options-compared/"><u>Best Tablets of 2023: Amaze with Amazon Fire or Go with Samsung Options Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitfort-fractured-stay-the-course-before-change/"><u>BitFort Fractured: Stay the Course Before Change</u></a></li>
<li><a href="https://driver-install.techidaily.com/boost-graphics-performance-via-win11-fixes/"><u>Boost Graphics Performance via Win11 Fixes</u></a></li>
<li><a href="https://win-cheats.techidaily.com/dr-folder-icon-personalization-tutorial-setting-country-flag-icons-for-file-management-version-2663-expertise-from-yl-software/"><u>Dr. Folder Icon Personalization Tutorial: Setting Country Flag Icons for File Management (Version 2.6.6.3) – Expertise From YL Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-end-task-feature-for-efficient-task-execution-windows-11/"><u>How to Configure End Task Feature for Efficient Task Execution (Windows 11)</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-realme-v30-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Realme V30 FRP In 3 Different Ways</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-honor-magic-v2-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Honor Magic V2 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/masterful-text-effects-in-adobe-after-effects/"><u>Masterful Text Effects in Adobe After Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-active-directory-related-printer-crashes-on-w11/"><u>Strategies for Resolving Active Directory-Related Printer Crashes on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-definitive-window-by-window-walkthrough-of-hdr-in-windows-11/"><u>The Definitive Window-by-Window Walkthrough of HDR in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unplugging-problems-addressing-frequent-ps4-disconnection-in-pc/"><u>Unplugging Problems: Addressing Frequent PS4 Disconnection in PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mysteries-of-microsofts-copilot-key-in-windows-11/"><u>Unveiling the Mysteries of Microsoft's Copilot Key in Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/virtual-event-space-12-channel-livestream-experience/"><u>Virtual Event Space 12-Channel Livestream Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-gaming-experience-boosted-by-solving-directdraw-errors/"><u>Windows 11 & 11 Gaming Experience Boosted by Solving DirectDraw Errors</u></a></li>
</ul></div>

