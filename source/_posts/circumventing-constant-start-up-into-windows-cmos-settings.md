---
title: Circumventing Constant Start-Up Into Windows CMOS Settings
date: 2024-12-06T16:41:15.542Z
updated: 2024-12-12T21:14:55.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Circumventing Constant Start-Up Into Windows CMOS Settings
excerpt: This Article Describes Circumventing Constant Start-Up Into Windows CMOS Settings
keywords: Bypassing Boot Sequence,CMOS Reset Access,Windows Startup Adjustments,Boot Settings Override,PC Configuration Changes,Startup Code Modification,Windows System Reinitialization
thumbnail: https://thmb.techidaily.com/3fd32f657ca906fd6ed8ec321bcb0a471e050e9fdbe1e0332d4aba568afc6cd5.jpg
---

## Circumventing Constant Start-Up Into Windows CMOS Settings

 Does your Windows device keep booting to BIOS every time you restart it? Numerous factors could be responsible for this, such as having the boot key pressed on the keyboard, running outdated BIOS, improperly plugged-in operating system drive, misconfigured boot sequence, or a CMOS battery issue.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disconnect Peripherals and Discharge Static Charge

 Disconnecting the peripherals and discharging the static charge has fixed the issue under discussion for some users. Therefore, before you proceed with any other fixes, unplug all peripherals from your device, and press the power button for half a minute to discharge static electricity. After that, reboot your device. If it boots back into BIOS, begin applying the remaining fixes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Perform a Quick Restart From the BIOS

 Although it sounds pretty simple, restarting the computer after saving BIOS settings usually boots a device into Windows, which may help bypass the issue. Therefore, once your device boots into BIOS, do not make any changes; save the changes and exit BIOS. Afterward, your device may restart once and boot directly into Windows this time.

 Even if this workaround works, it isn't a permanent fix, as you will need to restart Windows through BIOS every time you turn it on, which can be annoying. Continue applying the remaining fixes for a permanent solution.

## 3\. Ensure That the Boot Key Isn't Pressed Down

 Booting into BIOS requires users to press a specific key on the keyboard, which is different for nearly every Windows laptop manufacturer. If you're unfamiliar with it, our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) covers the correct key to enter BIOS on laptops from different manufacturers.

![HyperX Alloy Origins Core Function Keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/02/Alloy-Origins-Core-HyperX-Function-Keys.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When this button is pressed, Windows will boot into BIOS instead of the operating system following a turn-on. So, if your device is automatically booting into BIOS, it is possible that this key got stuck while pressed down on the keyboard, telling your PC to boot into BIOS.

 Therefore, make sure the boot key on your keyboard isn't pressed. If there are any dust particles on it, wipe them off and press the key several times to ensure nothing is stuck.

## 4\. Ensure the Drive Containing the Operating System Is Plugged In

 Your device can also boot into BIOS if it does not find a bootable drive containing your operating system. Typically, it happens when your PC's hard drive disconnects or is no longer detected by your device due to a hardware issue.

 Thus, you must ensure that your drive is connected and detectable by your system and that it isn't causing your device to boot into BIOS. Since the BIOS interfaces of most laptops differ between manufacturers, the process to check that varies.

 Users facing this issue on a Dell device should navigate to the **System Information** tab in BIOS and look under **Device Information**.

![Checking the Device Information in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-the-device-information-in-bios-1.jpg)

 If you don't see the drive with your OS installed, ensure it's connected properly. If your drive is connected but not detectable by your device, you should have it inspected to see if there is a hardware problem. However, if the drive containing your operating system is listed there, move on to the next step.

## 5\. Check Your Boot Sequence

 Boot sequence refers to the order in which your device searches for bootable data. It's recommended to keep the device containing your OS at the top of the sequence, especially if you have multiple storage devices connected. With this, your device can quickly find the bootable data and boot your operating system.

 If the drive containing your OS appears connected in the previous step, ensure it comes first in the boot sequence. To check that on a Dell device, select **Boot Sequence** from the left sidebar. After that, choose **Legacy** under **Boot List Option** and make sure your desired drive appears first in the **Boot Sequence**.

![Changing the Boot Mode in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/changing-the-boot-mode-in-bios.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If it isn't selected, click on the **arrow button** and move the drive containing your operating system to the top.

![Putting the Drive Containing the OS at Top in Boot Sequence in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/putting-the-drive-containing-the-os-at-top-in-boot-sequence-in-bios.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Disable Fast Startup

 The Fast Startup feature in Windows hibernates the system and loads the files quicker. In a nutshell, it helps Windows boot faster. Even though it saves users a lot of time and helps them get back to work quickly, it is known to cause annoying issues during bootup. Often, disabling this feature fixes most of these problems.

 If you can boot into Windows from BIOS, our guide on [turning Fast Startup on and off](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) can help you disable this feature. However, if you are stuck at the BIOS screen and cannot boot into Windows, you can also disable Fast Startup from there. For that, go to your laptop manufacturer's website for instructions on turning off Fast Startup from BIOS.

## 7\. Update the BIOS

 An outdated BIOS can also prevent Windows from booting correctly. It's the most neglected cause of most booting problems. Therefore, to ensure that the issue under discussion is not caused due to an outdated BIOS, you should upgrade it to the latest version.

 So, if you are able to boot to Windows from BIOS but again encounter the issue when restarting, refer to our guide on [how to update your UEFI BIOS in Windows](https://www.makeuseof.com/tag/update-uefi-bios-windows/). If you cannot boot to Windows, you will have to resort to other methods of updating BIOS.

## 8\. Replace or Reinsert the CMOS Battery

![Person tampering with a motherboard.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/cmos-battery-explained-featured.jpg)

 The CMOS battery powers the BIOS firmware on the laptop. If you are unable to boot to Windows, a dead CMOS battery could also be to blame. Often, just removing and reinserting the battery fixes the issue; however, it resets a few settings, including the date and time. In case of a dead battery, you may need to replace it.

 If you want to know more about the CMOS battery and how to remove it, refer to our guide on [what a CMOS battery is](https://www.makeuseof.com/what-is-a-cmos-battery-and-how-do-you-remove-one/).

## Don’t Let Your Windows PC Boot to BIOS

 Seeing your device boot directly into BIOS rather than Windows can be extremely frustrating. We hope the above fixes will help you successfully resolve the issue and boot to Windows. If the above fixes don't work, repair or reinstall Windows. If that doesn't work either, the laptop could have a hardware problem, so take it to a technician for inspection.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-in-2024-ultimate-vr-showdown-scoring-the-best-oculus-models/"><u>[New] In 2024, Ultimate VR Showdown Scoring the Best Oculus Models</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-analyzing-the-dji-phantom-4-vision-tech/"><u>2024 Approved Analyzing the DJI Phantom 4 Vision Tech</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/elevate-video-output-quality-mastering-aiseesoft-screencast-tech-for-2024/"><u>Elevate Video Output Quality Mastering Aiseesoft Screencast Tech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-gaming-and-productivity-top-6-gpu-load-checkers-in-windows/"><u>Essential Gaming & Productivity: Top 6 GPU Load Checkers in Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/experts-companion-navigating-the-nuances-of-mobizen-screen-recording-for-2024/"><u>Expert's Companion Navigating the Nuances of Mobizen Screen Recording for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016408463-fortnite-sounds-down-heres-how-to-turn-up-the-volume-and-win/"><u>Fortnite Sounds Down? Here’s How to Turn Up the Volume and Win!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-location-of-your-onedrive-folder-in-windows-11/"><u>How to Change the Location of Your OneDrive Folder in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-novice-cinematographers-initial-work-analysis-and-replacements/"><u>In 2024, Novice Cinematographer's Initial Work Analysis & Replacements</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-the-load-strategies-to-reduce-ums-impact-on-your-system/"><u>Lowering the Load: Strategies to Reduce UMS Impact on Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-visuals-adjust-win11-scaling/"><u>Maximize Visuals: Adjust Win11 Scaling</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/new-update-all-graphics-hardware-compatible-with-overwatch/"><u>New Update: All Graphics Hardware Compatible with Overwatch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-vintage-boot-settings-on-windows/"><u>Restoring Vintage BOOT Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-directx-setup-for-your-gaming-experience/"><u>Streamlining DirectX Setup for Your Gaming Experience</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tame-asus-laptop-display-stop-the-squirm-not-quiver/"><u>Tame ASUS Laptop Display: Stop the Squirm, Not Quiver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-error-0x80041015-in-ms-office-for-windows-users/"><u>Unlocking Error 0X80041015 in MS Office for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-fullscreen-fiasco-fixing-glitches-in-sonic-adventure-w11/"><u>Unraveling the Fullscreen Fiasco: Fixing Glitches in Sonic Adventure (W11)</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-honor-90-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Honor 90 Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-hello-vulnerability-should-we-trust-our-fingerprints/"><u>Windows Hello Vulnerability: Should We Trust Our Fingerprints?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    