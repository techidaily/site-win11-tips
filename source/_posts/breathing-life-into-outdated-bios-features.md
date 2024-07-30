---
title: Breathing Life Into Outdated BIOS Features
date: 2024-07-29T08:12:17.010Z
updated: 2024-07-30T08:12:17.010Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breathing Life Into Outdated BIOS Features
excerpt: This Article Describes Breathing Life Into Outdated BIOS Features
keywords: Revitalize BIOS,Upgrade BIOS,Update BIOS Feature,BIOS Modernization,Enhance Old BIOS,Refresh BIOS Capabilities,Improve Outdated BIOS
thumbnail: https://thmb.techidaily.com/e90a41374ab8bcea029035e600ef5fff009cee16ec9e8eead9f3969598aefde0.jpg
---

## Breathing Life Into Outdated BIOS Features

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)

1. Click**Restart** to boot into the**Startup Menu.**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
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

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-essential-ios-gif-apps-compendium-for-latest-iphones/"><u>[New] 2024 Approved  Essential iOS GIF Apps Compendium for Latest iPhones</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-tricks-for-instantly-boosting-youtube-subscribers-for-2024/"><u>[New] 5 Tricks for Instantly Boosting YouTube Subscribers for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-camstudio-live-streaming-and-screen-capturing-review/"><u>[New] CamStudio Live Streaming & Screen Capturing Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-premier-mic-choices-for-4k-cameras-and-clear-audio-capture/"><u>[New] Premier Mic Choices for 4K Cameras & Clear Audio Capture</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-creators-ultimate-playlist-the-best-free-sound-sources/"><u>[New] YouTube Creators' Ultimate Playlist  The Best Free Sound Sources</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-how-to-achieve-inverted-movie-time-in-a-snap/"><u>[Updated] How to Achieve Inverted Movie Time in a Snap</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-influential-impact-celebrating-instagrams-most-dynamic-stars-for-2024/"><u>[Updated] Influential Impact  Celebrating Instagram's Most Dynamic Stars for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-optimal-no-audio-recording-practices/"><u>[Updated] Optimal No-Audio Recording Practices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-techniques-for-temporarily-haltin-windows-11-safety/"><u>5 Alternative Techniques for Temporarily Haltin Windows 11 Safety</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-samsung-galaxy-a05-unlock-without-password-by-drfone-android/"><u>5 Solutions For Samsung Galaxy A05 Unlock Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tactics-to-prevent-c-drive-from-running-dry-in-windows/"><u>5 Tactics to Prevent C: Drive From Running Dry in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-noteworthy-changes-in-the-windows-11-file-explorer/"><u>7 Noteworthy Changes in the Windows 11 File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-windows-firewall-configuration/"><u>7 Strategies for Windows Firewall Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-glimpse-into-gloom-crafting-art-in-paints-dim-modes/"><u>A Glimpse Into Gloom: Crafting Art in Paint's Dim Modes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-mastering-windows-11s-search-functionality/"><u>A Quick Guide to Mastering Windows 11'S Search Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-with-efficient-cmd-commands-top-20/"><u>Accelerate Tasks with Efficient CMD Commands (Top 20)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-system-best-practices-for-dns-setup-in-windows-11/"><u>Accelerate Your System: Best Practices for DNS Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/action-plan-conquering-error-0x800700e1-in-windows-11-systems/"><u>Action Plan: Conquering Error 0X800700E1 in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-quick-fix-support-windows-11-procedure/"><u>Activate Quick Fix Support: Windows 11 Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disappearing-badge-icons/"><u>Addressing Disappearing Badge Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incompatibility-with-windows-11-at-home/"><u>Addressing Incompatibility with Windows 11 at Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-utorrent-installers-on-pc-with-os-x/"><u>Addressing Non-Functional uTorrent Installers on PC with OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-restart-and-shutdown-disruptions-from-windows-faulty-apps/"><u>Addressing Restart and Shutdown Disruptions From Windows Faulty Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-how-to-open-excel-files-in-notepad-correctly/"><u>Addressing: How to Open Excel Files in Notepad Correctly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-window-placement-for-windows-users/"><u>Adjust Window Placement for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-real-time-performance-of-win-11-task-manager/"><u>Adjusting Real-Time Performance of Win 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-strategies-in-group-policy-with-gpresult/"><u>Advanced Strategies in Group Policy with GPResult</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-avenue-windows-11-disabling-tactics/"><u>Avoidance Avenue: Windows 11 Disabling Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-note-visibility-in-windows-desktop/"><u>Boost Note Visibility in Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-essential-wsl-2-approaches-for-win-users/"><u>Boost Performance: Essential WSL 2 Approaches for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296840588-end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12!</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-efficient-setup-adding-snapchat-to-your-mac/"><u>In 2024, Efficient Setup  Adding Snapchat to Your Mac</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-locked-apple-id-on-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, How to Fix Locked Apple ID on iPhone 12 Pro Max</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-unveiling-the-best-storytelling-schools-1-8-guide/"><u>In 2024, Unveiling the Best Storytelling Schools - #1-#8 Guide</u></a></li>
<li><a href="https://howto.techidaily.com/quick-fixes-for-why-is-my-samsung-galaxy-s23-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Samsung Galaxy S23 Black and White | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-for-streamlining-iphone-video-content-for-2024/"><u>The Ultimate Guide for Streamlining iPhone Video Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719323547365-unlock-the-future-affordable-windows-11-for-keys-fan-enthusiasts-on-black-friday/"><u>Unlock the Future: Affordable Windows 11 for Keys Fan Enthusiasts on Black Friday</u></a></li>
</ul></div>
