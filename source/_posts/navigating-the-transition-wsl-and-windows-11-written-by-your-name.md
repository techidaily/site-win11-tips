---
title: "Navigating the Transition: WSL and Windows 11' Written by [Your Name]"
date: 2024-11-12T18:04:32.701Z
updated: 2024-11-17T16:21:17.408Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating the Transition: WSL and Windows 11' Written by [Your Name]"
excerpt: "This Article Describes Navigating the Transition: WSL and Windows 11' Written by [Your Name]"
keywords: WSL Basics,Windows 11 Updates,WinShell Environment,Linux on PC,MSYS2 Tools,Cygwin Interface,Windows Subsystem
thumbnail: https://thmb.techidaily.com/62017b9a75f2be738008dfd82e88e32736119212be885f48835d0be5b0d3459a.jpg
---

## Navigating the Transition: WSL and Windows 11' Written by [Your Name]

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896510/19272" target="_top" id="1896510">
  <img src="//a.impactradius-go.com/display-ad/19272-1896510" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896510/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-harmonic-havens-expert-picks-of-ringtone-download-sites/"><u>[New] Harmonic Havens Expert Picks of Ringtone Download Sites</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-vivo-y27-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-windows-restore-error-0x80042306/"><u>Decoding and Correcting Windows Restore Error 0X80042306</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-0x80004005-efail-virtualbox-glitch-on-pcs/"><u>Fixing 0X80004005 E_FAIL VirtualBox Glitch on PCs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-motorola-razr-40-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Motorola Razr 40 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-maximizing-efficiency-with-azures-audio-transcription/"><u>In 2024, Maximizing Efficiency with Azure's Audio Transcription</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiate-a-transition-new-cursor-style-on-windows/"><u>Initiate a Transition: New Cursor Style on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gpu-task-management-on-windows/"><u>Mastering GPU Task Management on Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/mastering-the-repair-of-non-working-rust-microphones-the-definitive-guide-to-audio-troubleshooting/"><u>Mastering the Repair of Non-Working Rust Microphones: The Definitive Guide to Audio Troubleshooting</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-converting-regular-videos-with-best-vr-video-converters/"><u>New 2024 Approved Converting Regular Videos with Best VR Video Converters</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/review-the-ultimate-guide-to-sennheiser-momentum-sport-gym-ready-headphones/"><u>Review: The Ultimate Guide to Sennheiser Momentum Sport - Gym-Ready Headphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-restoration-reinstalling-windows-photo-viewer-on-win11/"><u>Seamless Restoration: Reinstalling Windows Photo Viewer on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplicity-in-files-optimize-windows-11-explorer-display/"><u>Simplicity in Files: Optimize Windows 11 Explorer Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sound-quality-assessment-for-your-windows-pc/"><u>Sound Quality Assessment for Your Windows PC</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ey-to-professional-filming-without-spending-free-lessons-from-the-best-in-green-screen-artistry/"><u>The Key to Professional Filming Without Spending Free Lessons From the Best in Green Screen Artistry</u></a></li>
<li><a href="https://fox-helps.techidaily.com/the-key-to-unlocking-the-best-video-production-talents-for-2024/"><u>The Key to Unlocking the Best Video Production Talents for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-health-alerts-time-to-consider-restarting/"><u>Windows Health Alerts: Time to Consider Restarting</u></a></li>
</ul></div>

