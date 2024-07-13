---
title: Addressing Incompatibility with Windows 11 at Home
date: 2024-07-12T17:47:03.319Z
updated: 2024-07-13T17:47:03.319Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Incompatibility with Windows 11 at Home
excerpt: This Article Describes Addressing Incompatibility with Windows 11 at Home
keywords: Win11 Compatibility Issues,Windows 11 Home Problems,Resolving Win11 Errors,Fixing Windows 11 Incompatibilities,Optimizing Win11 Performance,Overcoming Win11 Limitations,Enhancing Windows 11 Stability
thumbnail: https://thmb.techidaily.com/8cff42ae0b07628cf47b2fefd624aed56ec467c25aa15518d2e331ff9c28e273.jpg
---

## Addressing Incompatibility with Windows 11 at Home

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
<li><a href="https://win11-tips.techidaily.com/understanding-risks-in-windows-11-service-deactivation/"><u>Understanding Risks in Windows 11 Service Deactivation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-steps-to-resolve-onedrive-server-crashes/"><u>Swift Steps to Resolve OneDrive Server Crashes</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-pick-for-pen-notes-7-ultimate-windows-apps/"><u>Prime Pick for Pen Notes: 7 Ultimate Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/money-making-tactics-from-the-w11-windowware/"><u>Money-Making Tactics From the W11 Windowware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-security-top-5-fixes-for-access-denied-errors/"><u>Mastering Windows 11 Security: Top 5 Fixes for Access Denied Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-store-faults-rectify-error-0x80072f17/"><u>Mending Windows Store Faults: Rectify Error 0X80072f17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fix-geforce-experience-on-windows-pcs/"><u>Quick Guide to Fix GeForce Experience on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-solutions-at-fingertips-customizing-shortcuts-for-win-11-repairs/"><u>Speedy Solutions at Fingertips: Customizing Shortcuts for Win 11 Repairs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-realme-c67-5g-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Realme C67 5G Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-issues-a-comprehensible-guide-for-windows-11-users/"><u>Navigating Network Issues: A Comprehensible Guide for Windows 11 Users</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-oppo-reno-9a-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Oppo Reno 9A to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumph-over-windows-11-theme-lockdown-a-registry-approach/"><u>Triumph Over Windows 11 Theme Lockdown: A Registry Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-against-unexpected-scroll-behavior-in-os/"><u>Safeguard Against Unexpected Scroll Behavior in OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-top-10-cost-free-video-chat-apps-on-ios-and-android/"><u>2024 Approved  Top 10 Cost-Free Video Chat Apps on iOS & Android</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-androidandios-the-best-free-overlay-imaging-tools-top-10/"><u>In 2024, Android&iOS  The Best FREE Overlay Imaging Tools (Top 10)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-top-6-audio-transformation-tools-for-enhanced-phone-conversations-on-smartphones/"><u>Updated Top 6 Audio Transformation Tools for Enhanced Phone Conversations on Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/map-screenshot-archives-in-windows/"><u>Map Screenshot Archives in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/monetization-approaches-for-microsoft-and-windows-11/"><u>Monetization Approaches for Microsoft & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organizing-files-optimizing-drives-defrag-for-win11-users/"><u>Organizing Files, Optimizing Drives: Defrag for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-0xc0000001-on-windows-os/"><u>Steps to Solve 0XC0000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-outlook-and-gmail-synergy-on-your-pc/"><u>Mastering Outlook & Gmail Synergy on Your PC</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-movement-eradicate-slowness-on-sw-battlefront-windows/"><u>Master Movement: Eradicate Slowness on SW Battlefront Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regenerating-system-icons-in-windows-os/"><u>Regenerating System Icons in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-usb-drive-problems-for-efficient-data-handling/"><u>Solving USB Drive Problems for Efficient Data Handling</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-essential-tips-to-eliminate-instagram-video-issues-for-2024/"><u>[New] Essential Tips to Eliminate Instagram Video Issues for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-tips-for-photoshopping-on-windows-11/"><u>Troubleshooting Tips for Photoshopping on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-modify-mouses-double-click-speed/"><u>Ultimate Guide to Modify Mouse's Double-Click Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-surface-laptop-go-3-gains-processor-yet-fails-to-shine/"><u>Microsoft's Surface Laptop Go 3 Gains Processor, Yet Fails to Shine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-activate-folder-restrictions-in-windows/"><u>Step-by-Step Guide to Activate Folder Restrictions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scrutinizing-the-utility-of-windows-11-interface-components/"><u>Scrutinizing the Utility of Windows 11 Interface Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-instructions-downloading-and-installing-msixbundle-packages/"><u>Step-by-Step Instructions: Downloading & Installing MSixbundle Packages</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expanding-horizons-with-vr-filmmaking/"><u>Expanding Horizons with VR Filmmaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-pc-essential-free-tools-for-win11-users/"><u>Mastering Your PC: Essential Free Tools for Win11 Users</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-comprehensible-approach-to-personal-branding-in-the-youtube-sphere-for-2024/"><u>[New] A Comprehensible Approach to Personal Branding in the YouTube Sphere for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-the-user-experience-in-win11-settings/"><u>Redesigning the User Experience in Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-a-stuck-recycle-bin-on-microsofts-latest-os/"><u>Reviving a Stuck Recycle Bin on Microsoft's Latest OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-high-dpi-screen-resolution-problems-on-pcs/"><u>Tackling High DPI Screen Resolution Problems on PCs</u></a></li>
</ul></div>
