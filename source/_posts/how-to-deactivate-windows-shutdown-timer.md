---
title: How to Deactivate Window's Shutdown Timer
date: 2024-09-27T19:02:37.339Z
updated: 2024-10-03T23:09:13.522Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Deactivate Window's Shutdown Timer
excerpt: This Article Describes How to Deactivate Window's Shutdown Timer
keywords: Turn Off Windows Sleep Timer,Disable PC Shutdown Timeout,End Windows Standby Delay,Stop Power Save Timer,Cancel Sleep Mode Schedule,Deactivate System Slumber,Override Sleep Timer Setting
thumbnail: https://thmb.techidaily.com/10c291d26c69b79184acc714bd905fecf227774d1628ff4b17b2024d943bf02d.jpg
---

## How to Deactivate Window's Shutdown Timer

 If your Windows PC is protected by a password, the computer will auto-lock whenever you restart it or put it into Sleep mode. While this auto-locking behavior is a security measure, it can be annoying on occasion.

 Fortunately, you can keep Windows from automatically locking itself. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Is Windows 10 Automatically Locking Itself?

 Windows automatically locks itself for one simple reason: to protect your privacy.

 Imagine a scenario where you have to leave your computer unattended for an extended period. If there is no auto-lock on Windows, anyone can use your PC for any reason without any repercussions.

 By locking itself automatically once your PC goes into sleep mode, Windows ensures that your data stays private and nobody except you has access to your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151858/7443" target="_top" id="2151858">
  <img src="//a.impactradius-go.com/display-ad/7443-2151858" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151858/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Stop Windows From Automatically Locking Itself

You can stop Windows from automatically locking itself by:

* Disabling Windows sign-in.
* Disabling sleep mode and screen saver.
* Editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to disable auto-locking.

Now that we know how to do it, let's dive into the steps.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934183/19272" target="_top" id="1934183">
  <img src="//a.impactradius-go.com/display-ad/19272-1934183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934183/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Disabling Windows Sign-In

 Outright disabling Windows’ sign-in requirement is the most serious step that you can take to disable auto-locking on Windows. To disable the sign-in requirement:

* Hit the Windows keys, type “sign in”, and choose**Sign-in options** .
* In the**Require sign-in** section, select**Never** from the dropdown menu.
* While you are in Sign-in options, make sure to disable Dynamic lock by unchecking the option in the**Dynamic lock** section.

![Disable Windows sign-in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sign-in-2.JPG)

 Dynamic lock automatically locks your PC if a Bluetooth-connected device, for instance, your smartphone, goes out of range. So, disabling this option will ensure that your PC doesn’t lock up when you walk away from it.

### Disabling Sleep Mode and Screen Saver

 Next, because Windows automatically locks itself when in sleep mode, you can effectively disable auto-locking by keeping your computer from entering sleep mode. To do this:

* Hit the Windows key, type “power and sleep”, and choose**Power & sleep settings** .
* In the Power & sleep section, set disable mode by choosing**Never** from both dropdowns under**Sleep** .  
![Disable sleep mode on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sleep-mode.JPG)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you’ve set a screen saver active on your PC, we also recommend turning it off, as it can, sometimes, cause Windows to automatically lock itself. To disable the screen saver:

* Hit the Windows key again, type “screen saver”, and click**Turn screen saver on or off** to open**Screen Saver Settings** .
* In the Screen Saver Settings, set**Screen saver** to**None** and uncheck**On resume, display the logon screen** .

![Disable screen saver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-screen-saver.JPG)

### Editing Windows Registry to Disable Auto-Locking

 Finally, you can also edit Windows Registry to stop Windows from automatically locking itself. Before we show you how to do this, make sure you understand that editing Windows Registry can make your system unstable requiring you to restart or even[perform a fresh Windows install](https://www.makeuseof.com/windows-11-set-up-without-internet-connection/) for your PC to work properly again.

So, edit Windows Registry only when nothing else works.

* Hit the Windows keys, type “registry”, right-click on**Registry Editor** , and select**Run as administrator** .
* In Registry Editor, navigate to**HKEY\_LOCAL\_MACHINE** \>**Software** \>**Policies** \>**Microsoft** .
* Next, right-click on**Windows** , select**New** , and choose**Key** to define a new key/create a new folder in Windows Registry. Name the new folder something like “Disable autoLock”.
* Now, right-click on the folder you just created, place the mouse cursor over**New** , and select**DWORD (32-bit) Value** . Change the name of this new element to “NoLockScreen”.
* Open**NoLockScreen** and set the Value data to 1\. Press ok to finish the process.

![Disable auto-lock from Windows Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-auto-lock-registry.JPG)

Finally, restart your computer to see if a lock screen appears.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Use Windows Hello to Make Windows’ Auto-Locking Bearable

 If your PC or notebook has facial recognition or a fingerprint reader, you can set up Windows Hello to make sign-ins a breeze.

 On supported computers, Windows Hello can instantly recognize your face/fingerprint to log you in, taking the hassle out of typing a password in case of Windows auto-locking itself.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-initiating-conversations-with-google-meet/"><u>[New] 2024 Approved Initiating Conversations with Google Meet</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-asus-proart-review-a-visual-spectacle-unveiled-for-2024/"><u>[New] ASUS ProArt Review A Visual Spectacle Unveiled for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-ultimate-windows-audio-suite/"><u>[Updated] Ultimate Windows Audio Suite</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-steps-for-keeping-your-samsung-smart-tvs-system-current-and-secure/"><u>Easy Steps for Keeping Your Samsung Smart TV's System Current and Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-back-to-normal-overcoming-safe-mode-outlook/"><u>Getting Back to Normal: Overcoming Safe Mode Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/grasping-how-windows-handles-preemptive-memory/"><u>Grasping How Windows Handles Preemptive Memory</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-some-outdated-your-hardware-drivers-with-windows-device-manager-in-windows-11107-by-drivereasy-guide/"><u>Identify some outdated your hardware drivers with Windows Device Manager in Windows 11/10/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepaddarkmodesettingguidewin/"><u>NotepadDarkModeSettingGuideWin</u></a></li>
<li><a href="https://driver-download.techidaily.com/nvidias-latest-geforce-driver-release-fast-and-smooth-gaming-on-your-windows-computer/"><u>NVIDIA's Latest GeForce Driver Release: Fast and Smooth Gaming on Your Windows Computer</u></a></li>
<li><a href="https://extra-skills.techidaily.com/prime-retro-elements-reviving-classic-vhs-tricks-for-2024/"><u>Prime Retro Elements Reviving Classic VHS Tricks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pursuing-mac-os-aesthetics-for-windows-5-must-try-methods/"><u>Pursuing Mac OS Aesthetics for Windows: 5 Must-Try Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-intermittent-wireless-mouse-issues-in-windows-10-and-11-expert-solutions-unveiled/"><u>Resolving Intermittent Wireless Mouse Issues in Windows 10 and 11: Expert Solutions Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-no-hypervisor-issue-on-windows-sandbox/"><u>Resolving No Hypervisor Issue on Windows Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sifting-through-nvidia-drivers-to-find-best-suit-for-you/"><u>Sifting Through Nvidia Drivers to Find Best Suit For You</u></a></li>
<li><a href="https://win-studio.techidaily.com/step-by-step-guide-to-acquiring-free-recovery-media-for-your-pc-dell-hp-lenovo-or-surface-using-windowslinux-insights-by-zdnet/"><u>Step-by-Step Guide to Acquiring Free Recovery Media for Your PC (Dell, HP, Lenovo or Surface) Using Windows/Linux | Insights by ZDNet</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-0x80860010-error-streamlining-windows-app-functionality/"><u>Taming the 0X80860010 Error: Streamlining Windows App Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-context-menu-customization-in-windows-11/"><u>The Art of Context Menu Customization in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricking-tpm-and-secure-boot-a-guide-to-rufus-usage/"><u>Tricking TPM and Secure Boot: A Guide to Rufus Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-cheap-windows-key-savings-may-not-pay-off/"><u>Why Cheap Windows Key Savings May Not Pay Off</u></a></li>
</ul></div>

