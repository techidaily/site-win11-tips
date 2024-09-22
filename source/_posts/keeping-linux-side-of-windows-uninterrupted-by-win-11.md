---
title: Keeping Linux Side of Windows Uninterrupted by Win 11
date: 2024-09-18T00:14:17.511Z
updated: 2024-09-22T00:07:43.488Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Keeping Linux Side of Windows Uninterrupted by Win 11
excerpt: This Article Describes Keeping Linux Side of Windows Uninterrupted by Win 11
keywords: Seamless OS Switching,Win11 + Linux Integration,No Interruption Windows,Continuous Linux Use,Dual-OS Operation Ease,Uninterrupted System Setup,Harmonious Windows+Linux Combo
thumbnail: https://thmb.techidaily.com/84b555054820124f11889e906637732ab71a15523e1f3cc982eace446c58606e.jpg
---

## Keeping Linux Side of Windows Uninterrupted by Win 11

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

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880956/19272" target="_top" id="1880956">
  <img src="//a.impactradius-go.com/display-ad/19272-1880956" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880956/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-epic-imagery-crafting-inspiring-instagram-posts-top20/"><u>[New] Epic Imagery Crafting Inspiring Instagram Posts #Top20</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-excellent-backdrops-setting-the-stage-for-streaming/"><u>2024 Approved Excellent Backdrops Setting the Stage for Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-dark-screen-customization-for-your-notepad-windowed-edition/"><u>Effortless Dark Screen Customization for Your Notepad, Windowed Edition</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/essential-haul-editing-skills-making-every-purchase-memorable/"><u>Essential Haul Editing Skills Making Every Purchase Memorable</u></a></li>
<li><a href="https://win11-tips.techidaily.com/establishing-print-capabilities-in-edge-shield-mode/"><u>Establishing Print Capabilities in Edge Shield Mode</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-s17-pro-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Vivo S17 Pro</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/installation-instructions-latest-driver-download-for-logitech-wireless-mice-on-windows/"><u>Installation Instructions: Latest Driver Download for Logitech Wireless Mice on Windows</u></a></li>
<li><a href="https://fox-glue.techidaily.com/journey-to-audio-excellence-mastering-ios-based-recording-techniques-for-2024/"><u>Journey to Audio Excellence Mastering iOS-Based Recording Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-notepad-aesthetics-choosing-windows-11s-themes-and-typefaces/"><u>Mastering Notepad Aesthetics: Choosing Windows 11'S Themes & Typefaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-speed-and-visuals-in-roblox-for-win-users/"><u>Maximize Speed and Visuals in Roblox for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionizing-workflow-with-7-pinnacle-windows-11-tools/"><u>Revolutionizing Workflow with 7 Pinnacle Windows 11 Tools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/seamless-gopro-broadcasts-tips-for-facebook-and-periscope-channeling-for-2024/"><u>Seamless GoPro Broadcasts Tips for Facebook & Periscope Channeling for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-calendar-viewing-experience-with-windows-outlook-tips/"><u>Transform Your Calendar Viewing Experience with Windows Outlook Tips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-our-choice-of-favorite-complimentary-international-call-services/"><u>Unveiling Our Choice of Favorite Complimentary International Call Services</u></a></li>
</ul></div>

