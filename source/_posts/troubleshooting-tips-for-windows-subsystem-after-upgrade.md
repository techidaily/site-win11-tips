---
title: Troubleshooting Tips for Windows Subsystem After Upgrade
date: 2025-02-10T23:27:52.334Z
updated: 2025-02-16T00:53:07.305Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Tips for Windows Subsystem After Upgrade
excerpt: This Article Describes Troubleshooting Tips for Windows Subsystem After Upgrade
keywords: WinSys Upgrade Fixes,Windows Sys Troubleshoot,System Update Solutions,Resolve WinSub Upgrade,PC Boot Subsystem Fix,Restart WinSub Errors,Upgrading Windows Sys Tips
thumbnail: https://thmb.techidaily.com/9cc1ab34a2708ce6599562965ce7d038d6461c86c7f5043e45b0cca41d824dbd.jpg
---

## Troubleshooting Tips for Windows Subsystem After Upgrade

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  

![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.

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
<li><a href="https://fox-boxes.techidaily.com/new-essential-iphone-watermark-software-guide-for-2024/"><u>[New] Essential iPhone Watermark Software Guide for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-navigate-the-social-sphere-10-techniques-for-triumphant-fb-growth-for-2024/"><u>[Updated] Navigate the Social Sphere 10 Techniques for Triumphant FB Growth for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-tecno-spark-20-pro-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Tecno Spark 20 Pro Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/breaking-down-the-latest-from-apples-let-loose-features-of-the-m4-ipad-pro-13-inch-ipad-air-and-apple-pencil-pro-insights-by-zdnet/"><u>Breaking Down the Latest From Apple's 'Let Loose': Features of the M4 iPad Pro, 13-Inch iPad Air & Apple Pencil Pro | Insights by ZDNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantle-the-defenses-taking-out-secure-qandas-from-win-11/"><u>Dismantle the Defenses: Taking Out Secure Q&As From Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-silent-slack-alerts-a-win-11-strategy-guide/"><u>Enhance Silent Slack Alerts: A Win 11 Strategy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-group-policies-for-single-accounts-in-latest-windows-versions/"><u>Fine-Tuning Group Policies for Single Accounts in Latest Windows Versions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/free-downloads-latest-dell-device-drivers-compatible-with-windows-7/"><u>Free Downloads: Latest Dell Device Drivers Compatible with Windows 7</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-vivo-y56-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Vivo Y56 5G phone? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-lenovos-screen-recording-an-in-depth-user-manual/"><u>In 2024, Lenovo’s Screen Recording – An In-Depth User Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-manual-time-adjustment-in-windows-systems/"><u>Master Manual Time Adjustment in Windows Systems</u></a></li>
<li><a href="https://fox-that.techidaily.com/mastering-iphone-repairs-navigating-apples-online-support-and-testing-services/"><u>Mastering iPhone Repairs: Navigating Apple's Online Support and Testing Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-guide-access-to-computer-controls/"><u>Quick Start Guide: Access to Computer Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-power-options-in-ws-11-interface/"><u>Reviving Lost Power Options in WS 11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-step-by-step-guide-to-recovering-windows-1110-keys/"><u>The Step-by-Step Guide to Recovering Windows 11/10 Keys</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-samsung-galaxy-f54-5g-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Samsung Galaxy F54 5G Phones</u></a></li>
</ul></div>

