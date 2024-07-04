---
title: Remedy for Faded BIOS Boot Options
date: 2024-06-25T17:00:08.877Z
updated: 2024-06-26T17:00:08.877Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for Faded BIOS Boot Options
excerpt: This Article Describes Remedy for Faded BIOS Boot Options
keywords: Fix Faded BIOS,Rejuvenate BIOS,Recover BIOS Settings,Restore BIOS Options,Refresh BIOS Boot,Update BIOS Display,Enhance BIOS Visuals
thumbnail: https://thmb.techidaily.com/57ebcefbd038d5518117756c100dd6989f85e0e6cff4615a7e12084a4473983a.jpg
---

## Remedy for Faded BIOS Boot Options

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to [disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

 The below steps to disable Secure Boot are for an HP Pavilion computer. For other systems, refer to your system manual.

To disable secure boot:

1. Click on**Start** and then click on**Power** .
2. Press and hold the**Shift key** and click on**Restart** . Confirm the action if necessary.
3. Release the**Shift** key as the PC shuts down and boot into the**Recovery Menu.**
4. Go to**Troubleshoot** and click on**Advanced options** .
5. Next, click on**UEFI Firmware Settings.**  
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

## Restore a Grayed Out Legacy Boot Option in Your BIOS

 You can fix the grayed-out Legacy boot option in BIOS by disabling Secure Boot and Trusted Platform Technology. In addition, disable Standard Standby (S0) to fix the problem.

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
<li><a href="https://win11-tips.techidaily.com/tailor-made-dns-strategies-for-windows-11-enthusiasts/"><u>Tailor-Made DNS Strategies for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-internal-error-in-windows-11-remote/"><u>Mastering the Art of Fixing Internal Error in Windows 11 Remote</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amend-non-working-shortcuts-solve-f-keys-issue-on-windows-11/"><u>Amend: Non-Working Shortcuts - Solve F Keys Issue on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-fury-not-frustration-fixing-lag-in-sw-battlefront-2/"><u>Unleash Fury, Not Frustration: Fixing Lag in SW Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-fixing-excel-notation-on-notepad/"><u>Guide: Fixing Excel Notation on Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminals-in-win11-undo-changes-and-start-new/"><u>Terminals in Win11: Undo Changes & Start New</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-system-image-creation-on-windows/"><u>Simplified System Image Creation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-activate-folder-restrictions-in-windows/"><u>Step-by-Step Guide to Activate Folder Restrictions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-full-use-of-the-control-key-in-windows-11/"><u>Enabling Full Use of the Control Key in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-infinix-smart-7-hd-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Infinix Smart 7 HD to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/navigating-the-best-no-cost-podcast-software-a-comprehensive-list-for-mobile-users/"><u>Navigating the Best No-Cost Podcast Software A Comprehensive List for Mobile Users</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-unshaken-learn-to-stabilize-your-videos-like-a-pr/"><u>New 2024 Approved Unshaken Learn to Stabilize Your Videos Like a Pr</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-android-and-iphone-video-creators-best-music-integrated-options/"><u>In 2024, Android and iPhone Video Creators Best Music-Integrated Options</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-secrets-to-unforgettable-borders-in-your-instagram-shots/"><u>In 2024, The Secrets to Unforgettable Borders in Your Instagram Shots</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-master-list-of-vimeo-video-capturers/"><u>In 2024, Master List of Vimeo Video Capturers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-upgrade-your-sky-faring-with-these-11-essentials-for-2024/"><u>[New] Upgrade Your Sky-Faring with These 11 Essentials for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-strategies-for-correcting-quietened-video-sounds-on-fb-for-2024/"><u>[New] Strategies for Correcting Quietened Video Sounds on Fb for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-do-you-want-to-know-how-to-add-luts-to-premiere-pro-in-this-guide-you-will-find-details-and-easy-steps-to-proceed-with-using-luts-in-p/"><u>Updated 2024 Approved Do You Want to Know How to Add LUTs to Premiere Pro? In This Guide, You Will Find Details and Easy Steps to Proceed with Using LUTs in Premiere Pro</u></a></li>
</ul></div>
