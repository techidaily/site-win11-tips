---
title: Restoring Vintage BOOT Settings on Windows
date: 2024-09-11T16:57:26.188Z
updated: 2024-09-17T08:54:42.161Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Vintage BOOT Settings on Windows
excerpt: This Article Describes Restoring Vintage BOOT Settings on Windows
keywords: Vintage Boots Restore,WinXtunes Configuring,Historical Boot Repair,Retro Windows Setting,Antique OS Tuning,Classic PC Adjustment,Heritage BIOS Fix
thumbnail: https://thmb.techidaily.com/128a52db05a06f83263e58b5a6a26485493e4674a4560940aaffe08f0a59ec40.jpg
---

## Restoring Vintage BOOT Settings on Windows

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

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/updated-experience-unparalleled-text-design-with-top-5-downloadable-platforms-for-2024/"><u>[Updated] Experience Unparalleled Text Design with Top 5 Downloadable Platforms for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/discover-the-most-exciting-no-cost-comic-designs/"><u>Discover the Most Exciting, No-Cost Comic Designs</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-my-spouse-from-spying-on-my-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop My Spouse from Spying on My Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/installing-the-newest-hp-network-drivers-on-your-pc-windows-11-7-and-8-guide/"><u>Installing the Newest HP Network Drivers on Your PC: Windows 11, 7 & 8 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/linux-alone-ditching-wsl/"><u>Linux Alone: Ditching WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-challenges-adapting-linux-subsystem-to-windows-11-upgrades/"><u>Overcoming Challenges: Adapting Linux Subsystem to Windows 11 Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-the-source-win-friendly-free-software-picks/"><u>Secure the Source: Win-Friendly Free Software Picks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/snap-edit-and-assemble-a-rapid-google-collage-how-to-for-2024/"><u>Snap, Edit & Assemble A Rapid Google Collage How-To for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-unterminate-program-issue-in-windows/"><u>Solutions to Unterminate Program Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-solutions-for-inactive-batch-scripts-on-windows/"><u>Tactical Solutions for Inactive Batch Scripts on Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/the-undetected-strategies-for-dodging-shadowbanned-content/"><u>The Undetected Strategies for Dodging Shadowbanned Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-character-maps-unresponsiveness-in-windows-os/"><u>Troubleshooting Character Maps Unresponsiveness in Windows OS</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-best-9-french-video-translators-online-and-download-options-for-2024/"><u>Updated Best 9 French Video Translators Online and Download Options for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/windows-11-compatibility-guide-addressing-and-repairing-corsair-icue-issues/"><u>Windows 11 Compatibility Guide: Addressing and Repairing Corsair iCUE Issues</u></a></li>
</ul></div>

