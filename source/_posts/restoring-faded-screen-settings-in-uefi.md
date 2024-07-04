---
title: Restoring Faded Screen Settings in UEFI
date: 2024-06-25T16:34:59.599Z
updated: 2024-06-26T16:34:59.599Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Faded Screen Settings in UEFI
excerpt: This Article Describes Restoring Faded Screen Settings in UEFI
keywords: Restore UEFI Screens,Fix Faded Display UEFI,Brighten UEFI Displays,Enhance UEFI Panel Brightness,Correcting Faded Screen UEFI,Improve UEFI Image Clarity,Adjust UEFI Visual Settings
thumbnail: https://thmb.techidaily.com/9abfa493c09f599241cf74fbf150ee16ae0981c6610495144fe17eca852c8fbd.jpg
---

## Restoring Faded Screen Settings in UEFI

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
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-causes-behind-usb-attachment-failure-in-virtualbox/"><u>Unraveling the Causes Behind 'USB Attachment Failure' In VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-editing-text-via-snipping-tool/"><u>Expert Guide: Editing Text via Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-integrate-sudo-with-windows-systems/"><u>Why Integrate Sudo with Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-local-user-policies-a-guide-to-windows-11-and-11-systems/"><u>Adjusting Local User Policies: A Guide to Windows 11 & 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-slacks-missing-notifications-issue-in-win-11/"><u>Solving Slack's Missing Notifications Issue in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-regain-onedrive-entry-points-in-windows/"><u>Effortlessly Regain OneDrive Entry Points in Windows</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevate-video-content-with-proven-strategies-for-youtube-shorts-growth-for-2024/"><u>Elevate Video Content with Proven Strategies for YouTube Shorts Growth for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/earning-as-a-video-game-geek/"><u>Earning as a Video Game Geek</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-looking-beyond-vegas-pro-explore-these-10-exceptional-mac-video-editors-in-20/"><u>Updated Looking Beyond Vegas Pro? Explore These 10 Exceptional Mac Video Editors in 20</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-ideal-approaches-to-correct-iphone-hdr-overexposure-in-adobe-premiere/"><u>In 2024, [Expert] Ideal Approaches to Correct iPhone HDR Overexposure in Adobe Premiere</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/top-10-picks-for-flawless-slow-motion-video-generation-for-2024/"><u>Top 10 Picks for Flawless Slow Motion Video Generation for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-14-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 14 Pro Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-choosing-between-vlc-and-mx-for-video-enjoyment/"><u>[Updated] Choosing Between VLC and MX for Video Enjoyment</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-your-brand-discover-the-riches-in-our-gallery-of-50-free-youtube-banners/"><u>[New] 2024 Approved  Elevate Your Brand - Discover the Riches in Our Gallery of 50 Free YouTube Banners</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-key-conduct-criteria-in-the-youtube-sphere/"><u>In 2024, Key Conduct Criteria in the YouTube Sphere</u></a></li>
</ul></div>
