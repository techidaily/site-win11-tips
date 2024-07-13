---
title: "Tech-Free Gaming Setup: DualShock for Windows Users"
date: 2024-07-12T17:07:17.504Z
updated: 2024-07-13T17:07:17.504Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tech-Free Gaming Setup: DualShock for Windows Users"
excerpt: "This Article Describes Tech-Free Gaming Setup: DualShock for Windows Users"
keywords: Tech-Free Gaming,DualShock Games,Play Sans Tech,Wireless Controller,Gamers' Choice,Console for PC,Eco-Gaming Setup
thumbnail: https://thmb.techidaily.com/b77f4a1b111b54e2805878ed9aa3d1afc9409a9f5cc36ff257194dcf6821d1ac.jpg
---

## Tech-Free Gaming Setup: DualShock for Windows Users

 Your PS3 is probably gathering dust by now, so why not put it to good use... or, at least, its controllers? Use them on your PC and give them a new life.

 Although it was possible to use PS3 joypads on PCs in the past, the process was finicky, and their wireless functionality was wonky. That was until DsHidMini entered the scene. Here's how you can use a PS3 DualShock controller on your PC, both through a USB connection and wirelessly through Bluetooth

## What Is DsHidMini?

 DsHidMini is an open-source solution for connecting and configuring many types of joypads to a PC. As such, if you have your old PS3 or PS4 DualShock controllers around, why not put them to use with this app?

 DsHidMini enables your PC to recognize them and provides XInput emulation. With Xinput being the modern standard for joypads under Windows, you'll be able to use your PlayStation controller with most modern games.

## Getting the Necessary Software for Using Your PS3 Controller on a PC

 By combining two pieces of software, DsHidMini, and BthPS3, you can have your PC detect your DualShock controller effortlessly both when connected with a USB cable and wirelessly through Bluetooth.

 Note, though, that for this guide, we take the existence of correctly working Bluetooth functionality for granted. If your PC lacks Bluetooth support, check our buyer's guide on [the best Bluetooth adapters you can grab today](https://www.makeuseof.com/best-bluetooth-adapters/) . Then, check our guide on [how to add Bluetooth to any computer](https://www.makeuseof.com/add-bluetooth-pc/) .

### Download and Install DsHidMini and BthPS3

 DsHidMini suggests installing BthPS3 to have your DualShock controllers correctly detected and connected to your PC. This guide will follow that suggestion, especially since we want them to work wirelessly.

1. Start by downloading the first piece of software from [DsHidMini's GitHub page](https://github.com/ViGEm/DsHidMini) .  
![DsHidMini GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-github-page.jpg)
2. Do the same with a visit at [BthPS3's GitHub page](https://github.com/ViGEm/BthPS3) .  
![BthPS3 GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-page.jpg)
3. In both cases, you'll find the downloadable files by clicking on the link under**Installation** , then checking out the links under**Assets** . Most people should go for the x64 versions. If you're still using an older 32-bit version of Windows, get the x86 files.  
![BthPS3 GitHub Assets Links](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-assets-links.jpg)
4. Click on**BthPS3's MSI file** that you've downloaded to install the Bluetooth driver. "MSI" stands for Microsoft Software Installer. Unlike executable installers, MSI relies on the "official" installation libraries bundled with Windows. If you meet any problems during that step, check our guide on [how to fix issues with the Windows Installer package](https://www.makeuseof.com/windows-installer-package-fix-issues/) .  
![BthPS3 Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installation.jpg)
5. After BthPS3's successful installation, you'll see it as a new device under the**Bluetooth** category in**Device Manager** . The easiest way to access the Device Manager is by using the**Windows Key** +**X** shortcut and selecting it from the menu that shows up.  
![BthPS3 Installed Bluetooth Driver in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installed-bluetooth-driver-in-device-manager.jpg)
6. DsHidMini's installation is a tad more complicated since it comes in a compressed archive. Open**Windows File Explorer** , and pay a visit to the folder where you saved DsHidMini's downloaded archive. All modern versions of Windows support the ZIP archive format, so you can right-click on the file and choose**Extract** . However, we used WinRAR instead simply because we had it installed, and it's somewhat faster. In both cases, the result is the same.  
![Extracting DsHidMini Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extracting-dshidmini-archive.jpg)
7. Look inside the extracted archive's folder, and you'll see two more folders:**x64** and**x86** . Enter the one matching your Windows architecture. As mentioned above, most people nowadays should go for**x64** .  
![DsHidMini Extracted Archive Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents.jpg)
8. Inside that folder, you'll find another subfolder named**dshidmini** . Enter that one, too.  
![DsHidMini Extracted Archive Contents x64](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents-x64.jpg)
9. Right-click on the**dshidmini.inf** file, and choose**Install** from the menu that shows up. When that step completes, install the**igfilter.inf** the same way.  
![DsHidMini Extracted Archive Contents x64 dshidmini inf install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents-x64-dshidmini-inf-install.jpg)

 Theoretically, that's everything you need for your DualShock to work with your PC. Practically, as is Windows' tradition, it wouldn't hurt to restart once to ensure the drivers are correctly installed, activated, and work as they should.

## How to Pair and Configure Your PS3 DualShock

 The next step is to "pair" your controller with your PC. However, that process is somewhat unconventional compared to how you usually connect Bluetooth devices to your PC.

1. Connect your DualShock joypad to your PC using a mini-USB cable. Your joypad should begin charging.
2. Pay a visit to the folder with DsHidMini's extracted files. Double-click on the**DSHMC.exe** to run it.  
![DSHMC.exe File In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-file-in-file-explorer.jpg)
3. You should see your "PlayStation controller" detected on the left side of the app's window. Now, if you run Steam with its outstanding controller support, it should detect and configure your joypad for use in modern games. As for wireless? Unplug the cable, and your joypad should keep working as if nothing happened.  
![DSHMC.exe Controller Detected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-controller-detected.jpg)
4. DsHidMini will have your controller recognized as an**XInput** device by default to maximize compatibility with modern software. But what if you want to use it on an older title that uses the older**DirectInput** standard or to have emulators like PPSSPP, PCSX2, and RPCS3 recognize it as an actual PlayStation controller? Close DSHMC.exe, then right-click on it and re-run it, but this time choose**Run as Administrator** . When its window shows up again, click on your controller on the left, and you'll see more details about it on the right and some options you can tweak.  
![DSHMC Configuration As Admin](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-configuration-as-admin.jpg)
5. You can change the HID device mode from**XInput** to another mode compatible with the software where you want to use your controller. You can also tweak its**Idle disconnect** period or define after how much time of inactivity the controller should disconnect and turn off.  
![DSHMC Change HID Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-change-hid-mode.jpg)

## How to Remove Remnants of Old Drivers

 If your joypad isn't correctly detected, did you use another solution in the past to have it work under Windows, like Sony's official driver or ScpToolkit? If yes, the problem might be a conflict between those and the DsHidMini and BthPS3 combo.

 Removing the older drivers and software is somewhat complicated. Plus, the process varies based on the driver and software used. So, we won't go over it in detail but offer a "generic guide" covering the basic steps for most cases.

 Run the**Command Prompt** or**PowerShell** with Administrative rights. Then, use the commands, in sequence, if you were using ScpToolkit:

`taskkill /F /IM ScpServer.exe  
taskkill /F /IM ScpMonitor.exe  
taskkill /F /IM ScpTrayApp.exe  
sc stop Ds3Service  
sc delete Ds3Service`

 These will stop and remove all active processes and services for PlayStation joypad-enabling software you might have used in the past.

 Now, press**Win** +**X** and choose**Device Manager** . Find and remove any mention of a "PlayStation controller" under**Human Interface Devices** if you were using the official Sony drivers.

 For ScpToolkit, look under**libusbK USB Devices** instead, and right-click and**Uninstall** any entry you see. Also, check for and, if found, uninstall the drivers for any "Bluetooth Dongle", "DualShock controller", or "PlayStation controller" under**Universal Serial Bus devices** .

 Then, download [DriverStore Explorer from its GitHub page](https://github.com/lostindark/DriverStoreExplorer/releases/tag/v0.11.79) . Extract its archive and run the app. Enable**Force Deletion** on the right. Seek any**libusbK USB Devices** , a standalone**scpvbus.inf** , or**bluetoothhost.inf** and**ds3controller.inf** if using ScpToolkit.

 Look for**sixaxis.inf** instead if using the official Sony driver. In both cases, place a checkmark next to any of those entries you'll find, and then click on**Delete Drivers** on the right.

 Afterward, exit the app, restart your PC, and let Windows re-detect any hardware and install the default drivers. Then, repeat the steps we covered above to install BthPS3 and DsHidMini from scratch.

## How to Use Your PS3 DualShock in Games

 Your controller should work now in most modern games that support Xbox joypads and for most joypad-enabled titles running under Steam.

 When that's not the case, run DSHMC.exe as an administrator and change the HID mode used by your joypad to the one supported by the game or app where you want to use it.

 An easy way to find the HID mode to choose for a particular title is to check if there's information about it at [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Main%5FPage) .

## Using Classic PS3 Joypads on Your Modern-Day Games for Windows

 Reusing your older joypads on your PC is the smartest choice. Apart from the fact you won't have to pay a dime to do it, they're great performers, tried and tested, and you're already familiar with them.

 Worst case scenario, you might have to buy a Bluetooth dongle for your PC, which would still come at a fraction of the cost of a brand-new controller.


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
<li><a href="https://vp-tips.techidaily.com/resonant-rhythms-where-to-download-classical-ringtones/"><u>Resonant Rhythms  Where to Download Classical Ringtones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-file-access-failures-in-microsoft-office-outlook/"><u>Correcting File Access Failures in Microsoft Office Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-becoming-a-skin-deep-sage-setting-up-your-beauty-channel/"><u>[New] 2024 Approved  Becoming a Skin-Deep Sage  Setting Up Your Beauty Channel</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-iphone-guide-to-breathtaking-shadow-images/"><u>2024 Approved  The Ultimate iPhone Guide to Breathtaking Shadow Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inactive-windows-system-voices/"><u>Addressing Inactive Windows System Voices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-implementing-bluescreenview-strategies/"><u>Detailed Guide to Implementing BlueScreenView Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-high-cpu-usage-by-windows-ums-for-vanguard-users/"><u>Unraveling High CPU Usage by Windows’ UMS for Vanguard Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-calc-app-for-night-time-viewing-dark-mode-tutorial/"><u>Adapt Calc App for Night-Time Viewing: Dark Mode Tutorial</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-modify-mac-snapshot-savings-spot/"><u>[Updated] Modify Mac Snapshot Savings Spot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-archival-steganography-in-photos-windows-11/"><u>The Art of Archival Steganography in Photos (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-decoding-password-demand/"><u>Winning Back Access: Decoding Password Demand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-remedying-directdraw-disruptions-in-win1011/"><u>Expert Guide: Remedying DirectDraw Disruptions in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-windows-11s-stealthy-taskbar-spotlight/"><u>Triggering Windows 11'S Stealthy Taskbar Spotlight</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/1717086809936-updated-photography-tutorial-how-to-shoot-and-create-impressive-hdr-portraits/"><u>[Updated] Photography Tutorial_ How to Shoot and Create Impressive HDR Portraits</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-discover-the-best-top-rated-audio-conversion-tools-revealed/"><u>New Discover the Best Top-Rated Audio Conversion Tools Revealed</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-crafting-attention-grabbing-facebook-giveaways/"><u>[New] Crafting Attention-Grabbing Facebook Giveaways</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-creating-compelling-thumbnails-that-stand-out/"><u>[Updated] In 2024, Creating Compelling Thumbnails that Stand Out</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oppo-find-x6-pro-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Oppo Find X6 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-potential-masterful-docx-to-pdf-migration/"><u>Unlocking Windows 11'S Potential: Masterful DOCX to PDF Migration</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/high-impact-tweets-of-the-year-viewer-rankings-for-2024/"><u>High-Impact Tweets of the Year  Viewer Rankings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-barriers-to-running-powershell-scripts-in-windows/"><u>Dismantling Barriers to Running PowerShell Scripts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-media-maker-tool-error-x90017-on-windows/"><u>Unraveling Media Maker Tool Error X.90017 On Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/siri-voice-changer-how-to-change-siri-voice-on-iphone-ipad-or-mac/"><u>Siri Voice Changer How to Change Siri Voice on iPhone, iPad or Mac?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/navigating-the-nuances-of-network-based-video-sharing-on-discord/"><u>Navigating the Nuances of Network-Based Video Sharing on Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-full-system-access-through-cmd-elevation/"><u>Gain Full System Access Through CMD Elevation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-speed-for-swift-steam-content-delivery/"><u>Enhance PC Speed for Swift Steam Content Delivery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-loop-of-0xf0831-error-in-win11-os/"><u>Breaking the Loop of 0XF0831 Error in Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-using-windows-11-calendar/"><u>A Practical Approach to Using Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-power-for-photo-renewal-with-windows/"><u>Transformative Power for Photo Renewal with Windows</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-design-memes-that-speak-to-your-audience/"><u>[New] In 2024, Design Memes That Speak to Your Audience</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-quick-answer-what-is-a-gif-file/"><u>Updated 2024 Approved Quick Answer What Is a GIF File?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-unraveling-the-mysteries-of-instagram-saved-stories/"><u>[New] In 2024, Unraveling the Mysteries of Instagram Saved Stories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-failures-on-older-windows-versions/"><u>Troubleshooting Installer Failures on Older Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-speed-minimizing-applications-via-keyboard-shortcuts/"><u>Unleash Speed: Minimizing Applications via Keyboard Shortcuts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transform-your-chromebooks-auditory-experience-with-top-5-web-tools-for-2024/"><u>Transform Your Chromebook's Auditory Experience with Top 5 Web Tools for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabled-apple-iphone-xr-how-to-unlock-a-disabled-apple-iphone-xr-by-drfone-ios/"><u>In 2024, Disabled Apple iPhone XR How to Unlock a Disabled Apple iPhone XR?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-yuzu-fps-on-pc-systems/"><u>Enhancing Yuzu FPS on PC Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
</ul></div>
