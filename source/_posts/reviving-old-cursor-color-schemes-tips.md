---
title: "Reviving Old Cursor Color Schemes: Tips"
date: 2024-08-28T01:20:54.495Z
updated: 2024-08-29T01:20:54.495Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reviving Old Cursor Color Schemes: Tips"
excerpt: "This Article Describes Reviving Old Cursor Color Schemes: Tips"
keywords: Cursor Color Revival,ReColoring Cursors,Scheme Change Guide,Update Cursor Design,Modern Cursor Palette,Alter Cursor Style,Cursors Color Transformation
thumbnail: https://thmb.techidaily.com/f567dab373423469fdd9df8f70e7990588879bfed38e1184b365dd128527e555.jpg
---

## Reviving Old Cursor Color Schemes: Tips

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

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

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
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
<li><a href="https://some-techniques.techidaily.com/new-examination-the-top-tier-ar-parrot-drone-20/"><u>[New] Examination  The Top-Tier AR Parrot Drone 2.0</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-exiting-facebook-livestreams-device-specific-methods/"><u>[New] Exiting Facebook Livestreams  Device-Specific Methods</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-clearer-chrome-tips-to-improve-facebook-playback/"><u>[Updated] In 2024, Clearer Chrome  Tips to Improve Facebook Playback</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pioneering-post-production-excellence-with-these-11-top-tutorials/"><u>[Updated] Pioneering Post-Production Excellence with These 11 Top Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-invisible-button-on-taskview-bar/"><u>Crafting an Invisible Button on TaskView Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decreasing-processor-load-while-engaged-in-virtual-battles/"><u>Decreasing Processor Load While Engaged in Virtual Battles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-microsofts-conversational-ai/"><u>Disabling Microsoft's Conversational AI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-ultimate-tools-for-international-peak-level-mouse-usage/"><u>Discover the Ultimate Tools for International, Peak-Level Mouse Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-windows-ready-website-apps/"><u>Easy Steps to Windows-Ready Website Apps</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-lava-blaze-2-5g-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Lava Blaze 2 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-top-displayed-calculator-on-pcs/"><u>Ensuring Top-Displayed Calculator on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-resolving-windows-camera-issues/"><u>Essential Steps for Resolving Windows Camera Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-working-taskbar-elements-in-windows/"><u>Fixing Non-Working Taskbar Elements in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-activating-terminals-quake-modes/"><u>Guide to Activating Terminal's Quake Modes</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-from-your-iphone-14-pro-max-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card from Your iPhone 14 Pro Max Apple ID and Apple Pay</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-nokia-c32-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Nokia C32 Lock Screen Password?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-transforming-your-archive-adding-instagram-filters-to-old-media/"><u>In 2024, Transforming Your Archive  Adding Instagram Filters to Old Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-smart-color-automation-for-win11-software-suite/"><u>Introducing Smart Color Automation for Win11 Software Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/loudness-levelers-essential-apps-for-taking-windows-audio-above-100/"><u>Loudness Levelers: Essential Apps for Taking Windows' Audio Above 100%%</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-repairing-windows-service-not-responding-errors/"><u>Mastering the Art: Repairing Windows Service Not Responding Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-display-in-windows-11/"><u>Overcoming Missing Display in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-fetching-ip-and-mac-addresses-windows-wise/"><u>Quick Guide: Fetching IP & MAC Addresses, Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicken-keystrokes-with-windows-powertoys/"><u>Quicken Keystrokes with Windows PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resize-windows-11-ui-elements-for-better-visibility/"><u>Resize Windows 11 UI Elements for Better Visibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieve-your-wingman-copilot-in-ws11s-struggle/"><u>Retrieve Your Wingman (Copilot) In WS11's Struggle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-audio-glitch-win11s-error-0xc00d36b4/"><u>Solving Audio Glitch: Win11's Error 0XC00D36B4</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/speaking-to-the-future-identifying-the-top-10-advanced-ios-voice-recorders-for-2024/"><u>Speaking to the Future Identifying the Top 10 Advanced iOS Voice Recorders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-unlocking-telnet-on-wins-os-x/"><u>Step-by-Step Guide: Unlocking Telnet on Wins OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-overcoming-network-errors-in-the-latest-windows-os/"><u>Steps for Overcoming Network Errors in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-autonomous-restarts-win11-strategy/"><u>Stop Autonomous Restarts: Win11 Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-screech-start-scroll-mouse-adjustment-guide/"><u>Stop Screech, Start Scroll: Mouse Adjustment Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-tweaks-lessening-apps-resource-consumption/"><u>System Tweaks: Lessening Apps' Resource Consumption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-empty-directory-error-code-x80070091/"><u>Troubleshooting Windows' Empty Directory Error Code X80070091</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-xiaomi-14-ultra-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Xiaomi 14 Ultra FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-executing-windows-restore-operations/"><u>Understanding and Executing Windows Restore Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-creativity-with-top-video-editors-on-windows-11/"><u>Unleash Creativity with Top Video Editors on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-lan-world-play-windows-mc-solutions/"><u>Unleashing LAN World Play: Windows MC Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-back-your-elusive-5ghz-connection-with-these-solutions/"><u>Win Back Your Elusive 5GHz Connection with These Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-drawing-delights-the-ultimate-7-app-guide/"><u>Win10 Drawing Delights: The Ultimate 7 App Guide</u></a></li>
</ul></div>
