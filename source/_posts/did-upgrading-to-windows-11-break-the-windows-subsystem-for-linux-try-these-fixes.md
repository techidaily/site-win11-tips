---
title: Did Upgrading to Windows 11 Break the Windows Subsystem for Linux? Try These Fixes
date: 2024-12-30T05:51:15.635Z
updated: 2025-01-06T00:10:47.555Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Did Upgrading to Windows 11 Break the Windows Subsystem for Linux? Try These Fixes
excerpt: This Article Describes Did Upgrading to Windows 11 Break the Windows Subsystem for Linux? Try These Fixes
keywords: WSFL Upgrade Issues,Win11 WSL Compatibility,Resolve WSL Post-Upgrade,Windows Subsystem Troubleshoot,Fixing WSL After Win11,WSL Functionality in Win11,Solving WSL Upgrade Problems
thumbnail: https://thmb.techidaily.com/9b3d4059cce82d617824aff75bbe2c1cfb1dda056b7a7373daee332b511aa58b.jpg
---

## Did Upgrading to Windows 11 Break the Windows Subsystem for Linux? Try These Fixes

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

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
<li><a href="https://some-techniques.techidaily.com/new-harmonizing-sound-dynamics-in-ableton/"><u>[New] Harmonizing Sound Dynamics in Ableton</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-how-to-share-the-screen-with-zoom/"><u>[New] How to Share the Screen with Zoom</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-tiny-film-plot-proposal/"><u>[Updated] 2024 Approved Tiny Film Plot Proposal</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-the-commercial-viability-of-creative-video-content/"><u>[Updated] In 2024, The Commercial Viability of Creative Video Content</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-poco-m6-pro-4g-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Poco M6 Pro 4G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-modify-smartscan-settings-on-microsofts-win11/"><u>Easily Modify SmartScan Settings on Microsoft’s Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-samsung-galaxy-f04-easily-by-drfone-android/"><u>In 2024, How To Unlock a Samsung Galaxy F04 Easily?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-privileged-requirement-not-met-windows-error/"><u>Methods to Overcome Privileged Requirement Not Met Windows Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-booting-a-comprehensible-approach/"><u>Optimize Windows Booting: A Comprehensible Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-your-screen-nine-windows-11-fixes-for-pixelation/"><u>Sharpen Your Screen: Nine Windows 11 Fixes for Pixelation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-overcoming-world-of-warcrafts-critical-glitch-error-132/"><u>Strategies for Overcoming World of Warcraft's Critical Glitch (Error 132)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-restoring-missing-taskbar-during-maxed-viewing/"><u>Strategies for Restoring Missing Taskbar During Maxed Viewing</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/utility-mapping-and-relocation/"><u>Utility Mapping and Relocation</u></a></li>
</ul></div>

