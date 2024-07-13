---
title: Rectifying 'This PC Can't Run' Post-Windows 11 Setup
date: 2024-07-12T16:44:15.991Z
updated: 2024-07-13T16:44:15.991Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying 'This PC Can't Run' Post-Windows 11 Setup
excerpt: This Article Describes Rectifying 'This PC Can't Run' Post-Windows 11 Setup
keywords: Windows 11 Troubleshooting,Fixing PC Errors Post-Update,Overcoming Not Installable Issue,Resolving System Error in Win11,Win11 Setup Restart Failure,Addressing Uninstall Issues Win11,Windows 11 Optimization Guide
thumbnail: https://thmb.techidaily.com/6b564cfcc68d7fa9fa2ebcc8ac34b00c6e2d610d2ee82b6185002beb469144e3.jpg
---

## Rectifying 'This PC Can't Run' Post-Windows 11 Setup

 Microsoft Windows 11 is here, and you can use the company's PC Health Check app to check if your PC meets the minimum system requirements to install Windows 11\. Unfortunately, for many users, running the PC Health Check app returns the This PC can't Run Windows 11 error.

 You will most likely encounter this error if the app detects your system hardware incompatible with Windows 11\. Fortunately, there are workarounds to get around this annoying error that may prevent you from upgrading to Windows 11 successfully.

## What Is the Windows 11 Upgrade Error Message?

The full error message reads:

 "This PC can't run Windows 11—While this PC doesn't meet the system requirements to run Windows 11, you'll keep getting Windows 10 updates"

Additionally, you may also see the following error:

* This PC must support TMP 1.2/2.0.
* This PC must support Secure Boot.

 If you are experiencing similar errors, it is possible that your PC doesn't have the minimum system requirements to run Windows 11\. That said, the error can be a false flag as well as it will not detect a Secure Boot and TMP 2.0-supported systems if the features are disabled in BIOS.

## What Are the System Requirements to Install Windows 11?

 Interestingly, the official [Windows 11 system requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/) aren't the most intensive, and most modern systems should support it out of the box. However, there are some upgrades from Windows 10.

 The following are the system requirements to install and run Windows 11:

* 1GHz 64-bit processor
* 4GB of RAM
* 64 GB of storage space
* System firmware that supports UEFI, Secure Boot capable
* Trusted Platform Module (TPM) 1.2/2.0.

 Now, if you meet the hardware specifications and still encounter this PC can't run Windows 11 error when using the [PC Health Checkup](https://www.microsoft.com/en-us/windows/windows-11) app, you can fix it by tweaking a few settings in your BIOS/UEFI setup.

![pc health check upgrade windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/pc-health-check-upgrade-windows-11.png)

 You may also encounter said error when installing Windows 11 through a bootable drive or setup file from the mounted ISO.

### What Is UEFI Boot Mode?

 UEFI (Unified Extensible Firmware Interface) is a booting method designed to replace BIOS (Basic Input Output System). In the legacy boot, the system uses BIOS firmware for booting.

 In general, installing Windows using the newer UEFI mode is recommended as it comes with more security features such as Secure Boot than the legacy BIOS mode. You can [learn more about BIOS](https://www.makeuseof.com/tag/the-bios-explained-boot-order-video-memory-saving-resets-and-optimum-defaults-si/) here.

## What Causes the "PC Can't Run Windows 11 Error?"

 This error occurs when you run the PC Health Check app to check if your PC supports Windows 11\. It may also occur when you try to install Windows 11 from the bootable flash drive or using the setup file from the mounted ISO.

 For Windows 11 to be compatible with your computer, it must support UEFI with Secure Boot, and TPM 1.2 or 2.0 must be enabled. Since Windows 11 requires a UEFI Secure Boot compatible system, the setup will fail to detect required features if you have installed Windows 10 via the legacy boot mode.

 This will trigger the This PC can't install Windows 11 error as the system requirements are unmet. Even if your PC support both Secure Boot and TMP 2.0, you may still have to enable them to resolve the error manually.

 If you use legacy boot mode, you need to set the Boot Mode to UEFI in your BIOS setup to enable the Secure Boot feature (and potentially switch TMP 1.2/2.0 on, too).

## How to Fix the "This PC Can't Run Windows 11 Error?"

 To fix this error, you should set the Boot Mode to UEFI and enable Secure Boot, and then make sure TPM 1.2/2.0 is enabled on your computer. Please note that the tab names may vary between manufacturers, but the instructions should translate roughly across hardware.

## 1\. Enable Secure Boot in Windows 10
![Enable Secure Boot UEFI Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/Secure-Boot-enabled.png)

Follow these steps to enable Secure Boot compatibility in Windows 10.

1. Close all the open Windows and save your work. Then shut down your PC.
2. Restart your system and start pressing**F2** to enter BIOS setup. Different laptop and PC manufacturers may use other function keys such as F12, F10, F8, or Esc key to enter BIOS. If you need help, refer to our guide on [how to enter BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) for more tips.
3. In the BIOS setup utility, use the arrow keys to open the**Boot** tab. Highlight**Boot Mode** and check if it is set to**Legacy** .
4. To change the Boot Mode, press Enter while the**Boot Mode** is highlighted.
5. Choose**UEFI** from the options. Use the Up and Down arrow keys to select UEFI, and hit Enter to select the option.
6. Next, open the**Security** tab.
7. Highlight the**Secure Boot** option using the arrow keys and hit Enter.
8. Choose**Enabled** to enable Secure Boot on your PC.

 Once you have enabled Secure Boot and UEFI in Boot Mode, make sure TPM 1.2/2.0 is also enabled for your PC. So, don't close the BIOS setup menu yet.

## 2\. Enable TMP 1.2/2.0 to fix the "This PC Can't Install Windows 11 Error"

![Enable Trusted Platform Module](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/Enable-TPM-2-0-BIOS.png)

 TMP 1.2/2.0 feature is accessible from the BIOS setup as well. Here's how to do it.

1. In BIOS/UEFI, open the**Security** tab.
2. Scroll down and highlight the**Trusted Platform Technology** option, and hit Enter. On Intel laptops, you may see the**Intel Platform Trust Technology** option instead.
3. Choose**Enabled** and press Enter to apply your selection.
4. Save the changes and exit.

 That's it. You have successfully enabled Secure Boot compatibility and TMP 2.0 on Windows 10\. Restart your PC, run the PC Health Checkup tool, or install Windows 11 to see if the error is resolved.

## 3\. Bypass TPM 2.0 and Secure Boot Requirement Using Registry Editor

 If your PC doesn't support Secure Boot and TPM 2.0, you can bypass the restriction using a workaround. To do this, we will modify the registry entry, allowing you to upgrade without Secure Boot and TPM 2.0 requirements.

 Note that your system must support at least TPM 1.2 for this workaround to work.

 Note that editing your Windows Registry involves risk. Make sure to [create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and then proceed with the step below.

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor.**
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\Setup\MoSetup`
4. Right-click on the**MoSetup** key and selec**t New > DWORD** (32-bit) value.  
![registry editor mosetup new value bypass windows 11 restriction](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-mosetup-new-value-bypass-windows-11-restriction.jpg)
5. Rename the value as**AllowUpgradeWithUnsupportedTPMorCPU.**
6. Right-click on the newly created value and select**Modify** .  
![registry editor mosetup new value 1 bypass windows 11 restriction](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-mosetup-new-value-1-bypass-windows-11-restriction.jpg)
7. In the Value data field, type**1** and click**OK** to save the changes.
8. Close the Registry Editor and try to install Windows 11 using the media creation tool or ISO. The upgrade should complete without the error.

 If the issue persists, read our guide to [bypass Windows 11 minimum installation requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) to learn more ways to bypass the restrictions and upgrade your PC.

## No Boot Device Found Error After Changing Boot Mode from Legacy to UEFI

 You may encounter the**No Boot Device Found** error if you change the Boot Mode for an existing Windows 10 installation from Legacy to UEFI. However, there's nothing to worry about.

 You can easily boot into your existing Windows 10 installation by changing the Boot Mode to Legacy from UEFI again in the BIOS setup. Next, use the MBR2GTP tool to convert your installation drive/disk from Master Boot Record (MBR) to the GUID Partition Table (GPT) without modifying or deleting data on the disk. You can learn more about using MBR2GRP here .

 Once you have converted the drive, you can change the Boot Mode from Legacy to UEFI without the No Boot Device Found error. Alternatively, if you are going to clean install Windows 11, make sure to install Windows 11 (or Windows 10) in the UEFI mode to prevent any issues in the future.

 If the bootable drive does not show up in the Boot Manager after enabling Secure Boot, ensure it is formatted with the UEFI system in Rufus. If not, create a bootable drive again with the target system set to UEFI (CMS).

## Fixing the This PC Can't Run Windows 11 Error

 Windows computers with the BIOS legacy firmware enabled won't be able to install Windows 11\. Fortunately, you can easily fix the error by tweaking your BIOS setup utility to enable UEFI firmware mode to enable Secure Boot and TPM 2.0.


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
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-nokia-c12-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-essence-of-timelessness-instagrams-slow-motion-guide-for-2024/"><u>[New] The Essence of Timelessness  Instagram's Slow-Motion Guide for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-streaming-success-recorded-google-chats/"><u>In 2024, Streaming Success  Recorded Google Chats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-windows-in-minutes-with-handy-shorthand/"><u>Ace Windows in Minutes with Handy Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-handy-windows-10-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 10 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-reverse-rewind-repeat-a-beginners-guide-to-tiktok-video-editing-for-2024/"><u>Updated Reverse, Rewind, Repeat A Beginners Guide to TikTok Video Editing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-github-desktop-in-windows-1011/"><u>A Comprehensive Guide to GitHub Desktop in Windows 10/11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-a-comprehensive-review-of-the-latest-picsart-updates/"><u>[New] A Comprehensive Review of the Latest PicsArt Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-harmony-with-googles-cross-platform-tool/"><u>Achieving Harmony with Google's Cross-Platform Tool</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-boosting-visibility-on-tiktok-with-smart-hashtags/"><u>[New] In 2024, Boosting Visibility on TikTok with Smart Hashtags</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-alter-program-dimensions-using-pc-keys/"><u>A Step-by-Step Guide to Alter Program Dimensions Using PC Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-strategies-to-extend-your-hard-drives-lifespan/"><u>6 Strategies to Extend Your Hard Drive's Lifespan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719315730924-avoid-frustration-fixing-the-missing-print-feature-on-windows/"><u>Avoid Frustration: Fixing the Missing Print Feature on Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-mastering-the-art-of-sourcing-quiet-melodic-tunes-for-2024/"><u>New Mastering the Art of Sourcing Quiet, Melodic Tunes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-pc-interaction-with-comprehensible-win11-navkeys/"><u>Accelerate PC Interaction with Comprehensible Win11 NavKeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-zero-x-in-the-mail-application-of-windows/"><u>Addressing Error Code Zero X in the Mail Application of Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Realme 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/action-plan-conquering-error-0x800700e1-in-windows-11-systems/"><u>Action Plan: Conquering Error 0X800700E1 in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-fix-a-grayed-out-screen-saver-settings-on-windows/"><u>4 Ways to Fix a Grayed Out Screen Saver Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-straightforward-steps-to-find-windows-ram-details/"><u>5 Straightforward Steps to Find Windows RAM Details</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-the-essential-guide-to-4-premium-fullscreen-software/"><u>[Updated] The Essential Guide to 4 Premium Fullscreen Software</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-realme-c67-4g-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Realme C67 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-windows-printer-speedy-solutions/"><u>Accelerating Windows Printer: Speedy Solutions</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-how-to-create-snapchat-lenses-easily-2-methods/"><u>In 2024, How to Create Snapchat Lenses Easily  2 Methods</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-blue-band-promise-made-easy-snapping-strategies/"><u>The Blue Band Promise Made Easy  Snapping Strategies</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/legends-awakened-a-library-of-mythical-creatures-sounds-for-2024/"><u>Legends Awakened A Library of Mythical Creatures Sounds for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fantasy-in-full-view-vr-cinemascape/"><u>[Updated] Fantasy in Full View  VR Cinemascape</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-top-charting-tracks-on-spotify/"><u>In 2024, Top Charting Tracks on Spotify</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-flawless-frame-capturer-kit/"><u>[New] In 2024, Flawless Frame Capturer Kit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-winget-not-working-on-windows-11/"><u>8 Ways to Fix Winget Not Working on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367958537-adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings.</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/best-aggregate-video-chat-and-multi-user-platforms/"><u>Best Aggregate Video Chat & Multi-User Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-issues-with-googles-nearby-sharing-on-desktop-pc/"><u>Addressing Issues with Google's Nearby Sharing on Desktop PC</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-compare-and-contrast-leading-online-and-desktop-gif-tools/"><u>In 2024, Compare & Contrast  Leading Online & Desktop GIF Tools</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-top-12-vlogger-friendly-cameras-unveiled/"><u>[Updated] Top 12 Vlogger-Friendly Cameras Unveiled</u></a></li>
<li><a href="https://extra-resources.techidaily.com/blueprint-for-a-thriving-portfolio-in-graphics/"><u>Blueprint for a Thriving Portfolio in Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-administrative-control-settings-in-windows-11-devices/"><u>Addressing Administrative Control Settings in Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-obs-studios-failed-to-connect-to-server-error-in-windows/"><u>7 Ways to Fix OBS Studio's Failed to Connect to Server Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-razers-in-the-synapse-interface-of-win-11/"><u>Addressing Absence of Razers in the Synapse Interface of Win 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-realme-c51-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Realme C51 | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-motion-monitoring-made-easy-best-apps-for-android-and-ios/"><u>2024 Approved Motion Monitoring Made Easy Best Apps for Android and iOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364066200-microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-creative-edge-filmmakers-blueprint-for-captivating-anime-subscribers-filmora/"><u>In 2024, The Creative Edge  Filmmaker's Blueprint for Captivating Anime Subscribers (Filmora)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operational-utorrent-installer-on-pcs/"><u>Addressing Non-Operational uTorrent Installer on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266023156-zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266840560-prevent-unwanted-updates-on-your-pc-today/"><u>Prevent Unwanted Updates on Your PC Today!</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-essential-guide-to-compositing-using-blending-modes/"><u>[Updated] Essential Guide to Compositing Using Blending Modes</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-nokia-c12-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Nokia C12</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-queries-with-everythingapp/"><u>Accelerate Your PC Queries with EverythingApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-open-the-print-management-tool-in-windows-11/"><u>9 Ways to Open the Print Management Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-amending-system-call-failures-in-modern-windows/"><u>Addressing and Amending System Call Failures in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-customize-win11-mouse-controls/"><u>A Guide to Customize Win11 Mouse Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-10-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-checksum-error-in-winrar/"><u>6 Ways to Fix the Checksum Error in WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abort-windows-over-the-top-contrast-mode/"><u>Abort Windows' Over-the-Top Contrast Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-renovated-widget-display-tool-for-windows-11/"><u>Accessing Renovated Widget Display Tool for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failed-shadow-copy-procedures/"><u>Addressing Failed Shadow Copy Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-windows-11-home-hub-guide/"><u>Activate Windows 11 Home Hub: Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Itel S23+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-choose-winning-apps-of-2023/"><u>Accelerate Your PC: Choose Winning Apps of 2023</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-charting-your-path-to-success-in-youtubes-earnings-system/"><u>2024 Approved  Charting Your Path to Success in YouTube's Earnings System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-locate-elusive-gpeditmsc-on-pc/"><u>7 Ways to Locate Elusive 'Gpedit.msc' On PC</u></a></li>
</ul></div>
