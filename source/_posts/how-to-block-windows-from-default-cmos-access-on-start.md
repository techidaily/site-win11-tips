---
title: How to Block Windows From Default CMOS Access on Start
date: 2024-07-12T16:52:14.309Z
updated: 2024-07-13T16:52:14.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Block Windows From Default CMOS Access on Start
excerpt: This Article Describes How to Block Windows From Default CMOS Access on Start
keywords: Blocking Windows CMOS,CMOS Access Restriction,Disable Windows Boot Menu,Prevent Windows Boot Options,Secure CMOS Settings,Protect Startup Interface,Halt Default CMOS Entry
thumbnail: https://thmb.techidaily.com/c4f624b3f2bccad5b6da118fee2e7df55a3a172015085fad0a0d2520bcd157aa.jpg
---

## How to Block Windows From Default CMOS Access on Start

 Does your Windows device keep booting to BIOS every time you restart it? Numerous factors could be responsible for this, such as having the boot key pressed on the keyboard, running outdated BIOS, improperly plugged-in operating system drive, misconfigured boot sequence, or a CMOS battery issue.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

## 1\. Disconnect Peripherals and Discharge Static Charge

 Disconnecting the peripherals and discharging the static charge has fixed the issue under discussion for some users. Therefore, before you proceed with any other fixes, unplug all peripherals from your device, and press the power button for half a minute to discharge static electricity. After that, reboot your device. If it boots back into BIOS, begin applying the remaining fixes.

## 2\. Perform a Quick Restart From the BIOS

 Although it sounds pretty simple, restarting the computer after saving BIOS settings usually boots a device into Windows, which may help bypass the issue. Therefore, once your device boots into BIOS, do not make any changes; save the changes and exit BIOS. Afterward, your device may restart once and boot directly into Windows this time.

 Even if this workaround works, it isn't a permanent fix, as you will need to restart Windows through BIOS every time you turn it on, which can be annoying. Continue applying the remaining fixes for a permanent solution.

## 3\. Ensure That the Boot Key Isn't Pressed Down

 Booting into BIOS requires users to press a specific key on the keyboard, which is different for nearly every Windows laptop manufacturer. If you're unfamiliar with it, our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) covers the correct key to enter BIOS on laptops from different manufacturers.

![HyperX Alloy Origins Core Function Keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/02/Alloy-Origins-Core-HyperX-Function-Keys.jpg)

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

 If it isn't selected, click on the **arrow button** and move the drive containing your operating system to the top.

![Putting the Drive Containing the OS at Top in Boot Sequence in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/putting-the-drive-containing-the-os-at-top-in-boot-sequence-in-bios.jpg)

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/resolving-the-not-responding-problem-for-spotify-software/"><u>Resolving the Not Responding Problem for Spotify Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-0x80072f8f-0x20000-error-on-pcs/"><u>Resolving 0X80072f8f-0x20000 Error on PCs</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-tecno-spark-20-proplus-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Tecno Spark 20 Pro+ Activity | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-failed-projection-links-on-windows-os/"><u>How to Tackle Failed Projection Links on Windows OS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-game-capture-software-analysis-obs-vs-shadowplay/"><u>[Updated] 2024 Approved  Game Capture Software Analysis  OBS vs ShadowPlay</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pioneering-3d-design-avoiding-common-pitfalls-in-illustrator/"><u>In 2024, Pioneering 3D Design  Avoiding Common Pitfalls in Illustrator</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-the-secrets-to-flawless-hdr-image-creation-and-merging-in-lightroom/"><u>[New] The Secrets to Flawless HDR Image Creation and Merging in Lightroom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-overlapping-app-symbols-on-pc-screen/"><u>Rectifying Overlapping App Symbols on PC Screen</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identity-infiltration-windows-fingerprints-in-the-crosshairs/"><u>Identity Infiltration: Windows Fingerprints in the Crosshairs</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-vivo-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Vivo Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-it-admin-access-restricted-on-windows/"><u>Resolving 'IT Admin Access Restricted' On Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-tecno-spark-10-4g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Tecno Spark 10 4G</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlocking-an-icloud-locked-ipad-and-iphone-x-by-drfone-ios/"><u>Unlocking an iCloud Locked iPad and iPhone X</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevating-your-contents-impact-an-in-depth-look-at-youtube-thumbnail-size-for-2024/"><u>[Updated] Elevating Your Content's Impact  An In-Depth Look at YouTube Thumbnail Size for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-extreme-sports-face-off-comparing-hero5-black-to-session/"><u>[Updated] Extreme Sports Face-Off  Comparing Hero5 Black to Session</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-5-best-snipping-tools-for-pc/"><u>In 2024, 5 Best Snipping Tools for Pc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovery-of-missing-widgets-and-icons-on-windows-11/"><u>Recovery of Missing Widgets and Icons on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-recovery-for-non-functional-windows-software/"><u>Immediate Recovery for Non-Functional Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-app-crash-common-issues-and-fixes/"><u>Resolving Windows App Crash: Common Issues & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-glitches-to-achieve-uninterrupted-gameplay-win-11/"><u>Overcoming Steam Glitches to Achieve Uninterrupted Gameplay Win 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-vivo-y36i-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Vivo Y36i Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-protocol-port-vulnerability-check-for-windows/"><u>Network Protocol Port Vulnerability Check for Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-image-editors-ultimate-toolkit-review/"><u>[Updated] The Image Editor's Ultimate Toolkit Review</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-step-into-the-spotlight-with-these-top-20-tiktok-dancers/"><u>[New] In 2024, Step Into the Spotlight with These Top 20 TikTok Dancers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now!</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-securing-your-ps4-adventures-with-advanced-recording/"><u>[Updated] 2024 Approved  Securing Your PS4 Adventures with Advanced Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-win-gameplay-with-dxvk-why-gamers-should-care/"><u>Maximize Win Gameplay with DXVK – Why Gamers Should Care</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-change-new-directions-for-winadmin-access-control/"><u>Initiating Change: New Directions for WinAdmin Access Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-windows-11-desktop-menu-layout/"><u>Personalizing Your Windows 11 Desktop Menu Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-intrusions-top-7-windows-safeguarding-methods/"><u>Preventing Intrusions: Top 7 Windows Safeguarding Methods</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-master-voice-customization-on-ps-playstation-devices/"><u>2024 Approved  Master Voice Customization on PS PlayStation Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-win-11-gaming-landscape-with-these-fps-counters/"><u>Mastering the Win 11 Gaming Landscape with These FPS Counters</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-xiaomi-redmi-note-12t-pro-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Xiaomi Redmi Note 12T Pro to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-facebook-photosvideos-the-role-of-watermarks/"><u>In 2024, Facebook Photos/Videos  The Role of Watermarks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-elusive-windows-search-responses/"><u>Recovering Elusive Windows Search Responses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-closure-opening-folderfile-secrets-quickly/"><u>Inside Closure: Opening Folder/File Secrets Quickly</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/mi-11-the-ultimate-mobile-camera-to-record-your-lifes-moments-for-2024/"><u>Mi 11  The Ultimate Mobile Camera to Record Your Life's Moments for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-school-explorer-revival-strategies/"><u>Old-School Explorer Revival Strategies</u></a></li>
</ul></div>
