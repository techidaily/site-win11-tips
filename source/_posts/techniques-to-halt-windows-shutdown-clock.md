---
title: Techniques to Halt Windows Shutdown Clock
date: 2024-12-06T00:11:47.291Z
updated: 2024-12-12T16:40:35.173Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Halt Windows Shutdown Clock
excerpt: This Article Describes Techniques to Halt Windows Shutdown Clock
keywords: Stop Windows Downtime Timer,Cease PC Sleep Time,Halting Win Sleep Countdown,Prevent Windows Standby,Disable Taskbar Tick,Freeze Clock Shutdown,Block PC Sleep Timer
thumbnail: https://thmb.techidaily.com/8a64098fc8c00724b390ed4672a78681ea9b2ccc0c75a67c21e60baebffadabf.jpg
---

## Techniques to Halt Windows Shutdown Clock

 If your Windows PC is protected by a password, the computer will auto-lock whenever you restart it or put it into Sleep mode. While this auto-locking behavior is a security measure, it can be annoying on occasion.

 Fortunately, you can keep Windows from automatically locking itself. Here’s how.

## Why Is Windows 10 Automatically Locking Itself?

 Windows automatically locks itself for one simple reason: to protect your privacy.

 Imagine a scenario where you have to leave your computer unattended for an extended period. If there is no auto-lock on Windows, anyone can use your PC for any reason without any repercussions.

 By locking itself automatically once your PC goes into sleep mode, Windows ensures that your data stays private and nobody except you has access to your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Stop Windows From Automatically Locking Itself

You can stop Windows from automatically locking itself by:

* Disabling Windows sign-in.
* Disabling sleep mode and screen saver.
* Editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to disable auto-locking.

Now that we know how to do it, let's dive into the steps.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disabling Windows Sign-In

 Outright disabling Windows’ sign-in requirement is the most serious step that you can take to disable auto-locking on Windows. To disable the sign-in requirement:

* Hit the Windows keys, type “sign in”, and choose**Sign-in options** .
* In the**Require sign-in** section, select**Never** from the dropdown menu.
* While you are in Sign-in options, make sure to disable Dynamic lock by unchecking the option in the**Dynamic lock** section.

![Disable Windows sign-in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sign-in-2.JPG)

 Dynamic lock automatically locks your PC if a Bluetooth-connected device, for instance, your smartphone, goes out of range. So, disabling this option will ensure that your PC doesn’t lock up when you walk away from it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disabling Sleep Mode and Screen Saver

 Next, because Windows automatically locks itself when in sleep mode, you can effectively disable auto-locking by keeping your computer from entering sleep mode. To do this:

* Hit the Windows key, type “power and sleep”, and choose**Power & sleep settings** .
* In the Power & sleep section, set disable mode by choosing**Never** from both dropdowns under**Sleep** .  
![Disable sleep mode on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sleep-mode.JPG)

 If you’ve set a screen saver active on your PC, we also recommend turning it off, as it can, sometimes, cause Windows to automatically lock itself. To disable the screen saver:

* Hit the Windows key again, type “screen saver”, and click**Turn screen saver on or off** to open**Screen Saver Settings** .
* In the Screen Saver Settings, set**Screen saver** to**None** and uncheck**On resume, display the logon screen** .

![Disable screen saver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-screen-saver.JPG)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-social-synergy-blueprint-for-ig-and-tiktok-pairing/"><u>[New] 2024 Approved Social Synergy Blueprint for IG & TikTok Pairing</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-comprehensive-drone-racing-guide-and-5-top-fpv-uavs/"><u>[Updated] Comprehensive Drone Racing Guide & 5 Top FPV UAVs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-achieve-professional-level-recordings-with-these-top-4-methods-on-hp-devices/"><u>[Updated] In 2024, Achieve Professional-Level Recordings with These Top 4 Methods on HP Devices</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-pairing-video-cameras-with-desktop-captures/"><u>[Updated] In 2024, Pairing Video Cameras with Desktop Captures</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/capturing-and-crafting-your-essential-guide-to-gopro-4k-edits-for-2024/"><u>Capturing and Crafting Your Essential Guide to GoPro 4K Edits for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-windows-11s-volume-mixer-for-improved-audio/"><u>Configure Windows 11'S Volume Mixer for Improved Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-operation-errors-windows-1011-edition/"><u>Conquering Operation Errors: Windows 10/11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/control-program-size-display-tips-for-win11/"><u>Control Program Size Display: Tips for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-file-clarity-committing-comments-in-windows-11/"><u>Elevating File Clarity: Committing Comments in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-poco-f5-pro-5g-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on Poco F5 Pro 5G</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-intro-to-cinema-top-8-user-friendly-cameras-35mm/"><u>In 2024, Intro to Cinema Top 8 User-Friendly Cameras (35Mm)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ranked-creative-suites-equivalent-to-procreate-on-windows/"><u>Ranked Creative Suites Equivalent to Procreate on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-lost-steam-friends-list-in-win11-systems/"><u>Reinstating Lost Steam Friends List in Win11 Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/todays-vr-experience-insight-for-2024/"><u>Today’s VR Experience Insight for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-resetting-video-error-in-windows-1011/"><u>Troubleshooting Resetting Video Error in Windows 10/11</u></a></li>
<li><a href="https://program-issues.techidaily.com/unlock-the-mystery-behind-pc-launch-failures-of-resident-evil-5-and-get-playing-asap/"><u>Unlock the Mystery Behind PC Launch Failures of Resident Evil #5 and Get Playing ASAP!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-guidance-for-resolving-missing-time-remaining-issues/"><u>Win 11: Guidance for Resolving Missing Time Remaining Issues</u></a></li>
</ul></div>

