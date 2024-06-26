---
title: Brightening Dull Cursors in UEFI
date: 2024-06-25T17:10:30.375Z
updated: 2024-06-26T17:10:30.375Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Brightening Dull Cursors in UEFI
excerpt: This Article Describes Brightening Dull Cursors in UEFI
keywords: Bright UEFI Cursors,Revive Cursor UI,Enhanced UEFI Cursors,Clear UEFI Icons,Dynamic Cursor UI,Improved UI Cursors,Clean UEFI Display
thumbnail: https://thmb.techidaily.com/e1e53d68e6a8bd97bb49ce774576b58cc661b7caf15fc6fdb1157408db40b882.jpg
---

## Brightening Dull Cursors in UEFI

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
<li><a href="https://win11-tips.techidaily.com/tackling-windows-authorization-snags-head-on/"><u>Tackling Windows Authorization Snags Head-On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-resolving-windows-store-issue-code-0x00000000/"><u>Unraveling and Resolving Windows Store Issue Code 0X00000000</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-o365-sync-issues-a-quick-guide-to-fixing-errors/"><u>Win 11 and O365 Sync Issues: A Quick Guide to Fixing Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/momentum-builds-with-windows-11s-upcoming-feature-unveil/"><u>Momentum Builds with Windows 11’S Upcoming Feature Unveil</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-rectify-bluetooth-check-pin-error-in-windows-oses/"><u>Strategies to Rectify Bluetooth Check Pin Error in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-this-pc-cant-run-post-windows-11-setup/"><u>Rectifying 'This PC Can't Run' Post-Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-bluetooth-issue-here-are-9-quick-cures-to-restore-your-link/"><u>Win 11'S Bluetooth Issue? Here Are 9 Quick Cures to Restore Your Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pivotal-techniques-for-reworking-windows-via-shortcuts/"><u>Pivotal Techniques for Reworking Windows via Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-works-into-windows-os-step-by-step-guide/"><u>Integrating Works Into Windows OS: Step by Step Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-samsung-galaxy-a14-5g-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Samsung Galaxy A14 5G for Free? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-master-looped-videos-for-maximum-instagram-impact/"><u>[New] In 2024, Master Looped Videos for Maximum Instagram Impact</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-screen-recording-techniques-for-enhanced-creativity/"><u>[Updated] 2024 Approved  Screen Recording Techniques for Enhanced Creativity</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-do-you-know-about-some-efficient-slow-motion-video-editors-read-this-article-to-find-out-the-best-slow-motion-video-editing-tools-that-you-c/"><u>Updated In 2024, Do You Know About some Efficient Slow-Motion Video Editors? Read This Article to Find Out the Best Slow-Motion Video Editing Tools that You Can Try</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-password-cracking-tools-for-infinix-zero-30-5g-by-drfone-android/"><u>Top 10 Password Cracking Tools For Infinix Zero 30 5G</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-best-of-both-worlds-8-lightweight-yet-powerful-video-editors/"><u>2024 Approved The Best of Both Worlds 8 Lightweight Yet Powerful Video Editors</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-cash-creation-in-content-a-deep-dive-into-vids-and-videos/"><u>[Updated] Cash Creation in Content  A Deep Dive Into Vids and Videos</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-c67-4g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Realme C67 4G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-guide-to-efficiently-convert-vimeo-videos-to-audible-files-for-2024/"><u>[Updated] Guide to Efficiently Convert Vimeo Videos to Audible Files for 2024</u></a></li>
</ul></div>
