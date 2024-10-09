---
title: Navigating Windows Subsystem for Linux with Win 11
date: 2024-10-07T16:22:43.351Z
updated: 2024-10-09T00:54:30.331Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016129/19272" target="_top" id="2016129">
  <img src="//a.impactradius-go.com/display-ad/19272-2016129" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016129/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100526/7443" target="_top" id="2100526">
  <img src="//a.impactradius-go.com/display-ad/7443-2100526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2151890/7443" target="_top" id="2151890">
  <img src="//a.impactradius-go.com/display-ad/7443-2151890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151890/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-maintain-peaceful-posting-dismiss-ig-recommendations/"><u>[New] 2024 Approved Maintain Peaceful Posting Dismiss IG Recommendations</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-boost-communication-merging-skype-and-zoom-functionality/"><u>[Updated] In 2024, Boost Communication Merging Skype and Zoom Functionality</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-spark-ar-maximizing-realism-with-downloadable-lut-files/"><u>[Updated] Spark AR Maximizing Realism with Downloadable LUT Files</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-no-video-display-on-sony-a6400-screen/"><u>2024 Approved No Video Display on Sony A6400 Screen</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>3 Ways to Fake GPS Without Root On Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-the-iphone-14-pro-max-icloud-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing the iPhone 14 Pro Max iCloud Lock</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elite-cameras-perfect-for-professional-podcasting/"><u>Elite Cameras Perfect for Professional Podcasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-code-to-compassion-ai-in-windows-tomorrow/"><u>From Code to Compassion: AI in Windows Tomorrow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reveal-taskbar-behind-maximized-window-titles/"><u>How to Reveal Taskbar Behind Maximized Window Titles</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-youtube-mastery-elevating-your-channel-with-strategic-spotlight-techniques/"><u>In 2024, YouTube Mastery Elevating Your Channel with Strategic Spotlight Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-pc-query-speed-using-everythingapp/"><u>Optimize PC Query Speed Using EverythingApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-efficient-powertoys-setup-in-win11/"><u>Quick Guide: Efficient PowerToys Setup in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-greyed-out-recycling-tool-in-windows-11/"><u>Reactivating Greyed-Out Recycling Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-photo-capture-failures-in-windows-os/"><u>Resolve Photo Capture Failures in Windows OS</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-creative-pebble-speaker-malfunction-problems-troubleshooting-tips/"><u>Solving Creative Pebble Speaker Malfunction Problems - Troubleshooting Tips</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/subscribing-to-hulu-heres-why-now-is-prime-time/"><u>Subscribing to Hulu? Here's Why Now Is Prime Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-taskbar-utility-adding-directories-to-windows-11-menu/"><u>Transform Taskbar Utility: Adding Directories to Windows 11 Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-s-mode-is-it-right-for-your-pc/"><u>Windows 11 S Mode: Is It Right for Your PC?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-chatgpt-integration-steps/"><u>Windows ChatGPT Integration Steps</u></a></li>
</ul></div>

