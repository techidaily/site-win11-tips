---
title: Fixing Obsolete Boot Configurations
date: 2024-12-10T21:49:52.057Z
updated: 2024-12-13T00:36:35.520Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Obsolete Boot Configurations
excerpt: This Article Describes Fixing Obsolete Boot Configurations
keywords: Boot Config Fix-Up,Outdated Boot Setup,Reconfigure Old Boot,Revise Elden Boot Configs,Overhaul Obsolete Boot,Update Boot Settings,Eliminate Ancient Boot Modes
thumbnail: https://thmb.techidaily.com/474c5054a0eaa723712bc3725331bacf73663ebfef0031bd8bc1879804e39c8f.jpg
---

## Fixing Obsolete Boot Configurations

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to[disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

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
<li><a href="https://extra-guidance.techidaily.com/new-navigating-the-world-of-9gag-memes-made-easy/"><u>[New] Navigating the World of 9GAG Memes Made Easy</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-essential-methods-for-documenting-overwatch-games/"><u>[Updated] 2024 Approved Essential Methods for Documenting Overwatch Games</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ai-assistance-in-students-essays-progress-or-setback/"><u>AI Assistance in Students' Essays: Progress or Setback?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-choice-avi-player-with-multiplatform-support/"><u>Best Choice Avi Player with Multiplatform Support</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-music-players-software-for-windows-for-2024/"><u>Best Music Players Software for Windows for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Realme Narzo 60x 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-steps-to-unlock-control-panel-settings/"><u>Efficient Steps to Unlock Control Panel Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-computer-efficiency-with-w11-vm-reset/"><u>Improve Computer Efficiency with W11 VM Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-disk-space-at-its-peak-learn-to-automate-file-disposal-in-win11/"><u>Keeping Disk Space at Its Peak: Learn to Automate File Disposal in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-voice-logging-features/"><u>Navigating Windows' Voice Logging Features</u></a></li>
<li><a href="https://hardware-help.techidaily.com/realtek-pcie-fe-family-controller-drivers-for-windows-11-free-download/"><u>Realtek PCIe FE Family Controller Drivers for Windows 11 Free Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-steam-symbols-a-quick-fix/"><u>Resetting Steam Symbols: A Quick Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-issue-in-w11-the-9-fixes-approach/"><u>Tackling OneDrive Issue in W11 - The 9 Fixes Approach</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/user-insights-and-thoughts-on-the-latest-map-my-ride-version/"><u>User Insights and Thoughts on the Latest Map My Ride Version</u></a></li>
</ul></div>

