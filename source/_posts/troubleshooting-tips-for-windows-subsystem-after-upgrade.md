---
title: Troubleshooting Tips for Windows Subsystem After Upgrade
date: 2024-12-17T02:53:57.060Z
updated: 2024-12-22T07:27:01.505Z
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

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-how-to-pick-a-unique-name-for-youtube-channel-filmora/"><u>[New] 2024 Approved How To Pick a Unique Name for YouTube Channel - Filmora</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-tricks-to-improve-instagram-video-load-speeds-mobile/"><u>[Updated] 2024 Approved Tricks to Improve Instagram Video Load Speeds (Mobile)</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-comprehensive-conversion-guide-for-avi-media-to-web-ready-gif-in-filmora/"><u>[Updated] Comprehensive Conversion Guide for AVI Media to Web-Ready GIF in Filmora</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-holistic-harmony-the-best-online-yoga-channels-for-2024/"><u>[Updated] Holistic Harmony - The Best Online Yoga Channels for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-voice-transformation-made-simple-with-no-fee-tools/"><u>[Updated] In 2024, Voice Transformation Made Simple with No-Fee Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-constructing-emotional-resonance-trailer-sound-selection-guide/"><u>2024 Approved Constructing Emotional Resonance Trailer Sound Selection Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-setting-up-powertoys-on-win11/"><u>Expert Guide to Setting Up PowerToys on Win11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-oppo-reno-8t-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Oppo Reno 8T 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-internal-audio-errors-in-audacity-for-windows-1111/"><u>Fixing Internal Audio Errors in Audacity for Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-circumvent-direct-folder-name-challenges-on-windows-11/"><u>How to Circumvent Direct Folder Name Challenges on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>How to Stop My Spouse from Spying on My Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-security-detecting-open-tcpip-ports-in-windows/"><u>Network Security: Detecting Open TCP/IP Ports in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/permanent-erase-strategies-implementing-trash-bin-for-windows-pcs-11/"><u>Permanent Erase Strategies: Implementing Trash Bin for Windows PCs (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-resolving-error-0x800700e1-on-windows-11-systems/"><u>Solutions for Resolving Error 0X800700E1 on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-installer-problems-on-microsoft-store/"><u>Solving Installer Problems on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-jumbled-symbols-in-os-taskbar-display/"><u>Solving Jumbled Symbols in OS Taskbar Display</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-non-functional-bluetooth-on-your-windows-11-pc-with-these-simple-steps/"><u>Troubleshoot Non-Functional Bluetooth on Your Windows 11 PC with These Simple Steps</u></a></li>
</ul></div>

