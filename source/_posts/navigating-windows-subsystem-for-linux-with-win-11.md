---
title: Navigating Windows Subsystem for Linux with Win 11
date: 2024-10-08T05:30:36.123Z
updated: 2024-10-14T20:22:03.195Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Windows Subsystem for Linux with Win 11
excerpt: This Article Describes Navigating Windows Subsystem for Linux with Win 11
keywords: WSL Navigator (Win 11),Win 11 Linux Shell,SubSystem WSLC Tricks,Windows for Linux Setup,Ctrl+Alt+WSL Key Combo,WSL Configuration Guide,Integrating WSL in Win 11
thumbnail: https://thmb.techidaily.com/280632bcded78a124b04e053c7d047b36940366fb100b93a3444f92f9f5d3614.jpg
---

## Navigating Windows Subsystem for Linux with Win 11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535">
  <img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938745/19272" target="_top" id="1938745">
  <img src="//a.impactradius-go.com/display-ad/19272-1938745" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938745/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-essential-steps-to-record-and-archive-google-voice-calls/"><u>[New] In 2024, Essential Steps to Record and Archive Google Voice Calls</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-reaping-rewards-a-comprehensive-guide-to-7-14-stardew-mods/"><u>[Updated] Reaping Rewards A Comprehensive Guide to #7-14 Stardew Mods</u></a></li>
<li><a href="https://fox-that.techidaily.com/ensure-connectivity-with-your-loved-ones-fixing-iphones-dnd-mode-for-messages-and-calls/"><u>Ensure Connectivity with Your Loved Ones: Fixing iPhone's DND Mode for Messages & Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hotkeys-fastest-car-drivers-for-windows/"><u>Explore Hotkeys: Fastest Car Drivers for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-cab-structures-in-microsofts-windows-environment/"><u>Exploring CAB Structures in Microsoft's Windows Environment</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-do-i-sim-unlock-my-iphone-12-pro-by-drfone-ios/"><u>In 2024, How Do I SIM Unlock My iPhone 12 Pro?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/itops-expert-selection-best-windows-screencasters-for-2024/"><u>ITop's Expert Selection Best Windows Screencasters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-for-heic-image-conversion/"><u>Optimizing Windows for Heic Image Conversion</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/save-storage-space-swiftly-top-free-methods-for-clearing-your-iphone/"><u>Save Storage Space Swiftly: Top Free Methods For Clearing Your iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reset-blank-login-windows-1011/"><u>Strategies to Reset Blank Login Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-browsing-safety-with-aguard-feature-on-windows-11/"><u>Streamline Your Browsing Safety with Aguard Feature on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-common-onedrive-crashes-on-pc/"><u>Swift Solutions to Common OneDrive Crashes on PC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-choices-for-next-gen-vr-accessories-unveiled/"><u>Top Choices for Next-Gen VR Accessories Unveiled</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transforming-diy-with-innovative-tech-anticipate-gpt-4s-revolutionary-impact/"><u>Transforming DIY with Innovative Tech: Anticipate GPT-4's Revolutionary Impact</u></a></li>
</ul></div>

