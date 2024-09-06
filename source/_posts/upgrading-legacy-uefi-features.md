---
title: Upgrading Legacy UEFI Features
date: 2024-09-05T19:32:02.985Z
updated: 2024-09-06T19:32:02.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Upgrading Legacy UEFI Features
excerpt: This Article Describes Upgrading Legacy UEFI Features
keywords: Legacy UEFI Improvements,UEFI Update Advances,Enhancing Old UEFI,Legacy Systems UEFI,UEFI Modernization,Elevating Legacy UEFI,Upgrading UEFI Features
thumbnail: https://thmb.techidaily.com/a1248d9b4e7ad7b3aedb40cb2befdc93715f7a75414c6458bd1e077bee973ffa.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Upgrading Legacy UEFI Features

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-seamless-search-for-your-youtube-comments-across-platforms/"><u>[New] 2024 Approved  Seamless Search for Your YouTube Comments Across Platforms</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-bend-reality-with-your-own-animated-craftsmanship-for-2024/"><u>[New] Bend Reality with Your Own Animated Craftsmanship for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-boost-your-snapshots-proper-use-of-zoom-in-snapchat/"><u>[New] Boost Your Snapshots  Proper Use of Zoom in Snapchat</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-best-freebies-winning-windowsmac-video-tools/"><u>[New] In 2024, Best Freebies  Winning Windows/Mac Video Tools</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-navigating-netizens-youtubes-footprint-in-facebook-for-2024/"><u>[New] Navigating Netizens  YouTube’s Footprint in Facebook for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-elevate-presentations-with-melodic-additions/"><u>[Updated] In 2024, Elevate Presentations with Melodic Additions</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-financial-foresight-select-youtube-stocks-hubs/"><u>[Updated] In 2024, Financial Foresight  Select YouTube Stocks Hubs</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-ultimate-guide-to-kids-drones/"><u>[Updated] The Ultimate Guide to Kids' Drones</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-be-open-minded-listen-with-an-open-mind-without-preconceived-notions-or-biases-that-may-affect-understanding/"><u>2024 Approved  Be Open-Minded  Listen with an Open Mind, without Preconceived Notions or Biases that May Affect Understanding</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-get-back-on-track-resetting-final-cut-pro-x-to-resolve-common-problems/"><u>2024 Approved Get Back on Track Resetting Final Cut Pro X to Resolve Common Problems</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-oppo-find-x6-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Oppo Find X6 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-windows-steam-clients-dll-error/"><u>Cure for Windows Steam Client's Dll Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disable-windows-and-office-updates-4-easy-ways/"><u>Disable Windows & Office Updates: 4 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-10-capabilities-of-windows-powertoys-tools/"><u>Discover the Top 10 Capabilities of Windows PowerToys Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-execution-slang-for-software-deployment/"><u>Discovering Execution Slang for Software Deployment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-reboot-windows-update-components/"><u>Guidelines to Reboot Windows Update Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-spotify-autoplay-on-your-windows-system/"><u>Halt Spotify Autoplay on Your Windows System</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-lava-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Lava ?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approach-to-file-merging-and-directory-unification-on-windows-11/"><u>Innovative Approach to File Merging & Directory Unification on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joyous-jingles-tickling-tech-with-windows-software/"><u>Joyous Jingles: Tickling Tech with Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-filters-for-safe-browsing/"><u>Mastering Windows Filters for Safe Browsing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11s-advanced-setup/"><u>Navigating Windows 11'S Advanced Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-error-0xc0f1103f-in-windows-11-and-nvidia/"><u>Overcoming the Error 0Xc0f1103f in Windows 11 & NVIDIA</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-time-settings-in-windows-manual-configuration-steps/"><u>Personalizing Time Settings in Windows: Manual Configuration Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-through-pc-problems-master-these-20-cmd-commands/"><u>Power Through PC Problems: Master These 20 CMD Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-windows-systems-into-high-efficiency-video-land-with-tdarr-tools/"><u>Propel Windows Systems Into High-Efficiency Video Land with Tdarr Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-unreliable-keys-on-the-windows-snipper/"><u>Quick Fixes for Unreliable Keys on the Window's Snipper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-address-windows-task-sequence-fails-0x8007000f/"><u>Quick Fixes to Address Windows Task Sequence Fails 0X8007000F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-solution-for-local-sam-service-error-signal/"><u>Quick Solution for 'Local SAM Service' Error Signal</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quickly-troubleshoot-and-correct-the-lack-of-sound-during-your-skype-conversations/"><u>Quickly Troubleshoot and Correct the Lack of Sound During Your Skype Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-driver-failure-error-on-pcs-running-windows-1011/"><u>Resolving Driver Failure Error on PCs Running Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-unresponsive-menus-of-the-windows-11-os/"><u>Reviving Unresponsive Menus of the Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-setup-achieving-batch-software-updates-with-winstall-in-windows-11/"><u>Revolutionize Your Setup: Achieving Batch Software Updates with Winstall in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-pc-control-hotkey-heroes-of-the-auto-world/"><u>Speedy PC Control: Hotkey Heroes of the Auto World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-unauthorized-nvidia-control-panel-errors/"><u>Steps to Fix Unauthorized Nvidia Control Panel Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-implement-spatial-sound-on-windows-11/"><u>Strategies to Implement Spatial Sound on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sustaining-calculator-leading-position-on-pcs/"><u>Sustaining Calculator Leading Position on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-failed-office-activation-on-windows-devices/"><u>Tackling Failed Office Activation on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-system-for-optimal-performance-with-new-windows-and-linux-blend/"><u>Tailoring Your System for Optimal Performance With New Windows and Linux Blend</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-art-of-balance-mastering-tripod-usage-in-video-blogging/"><u>The Art of Balance  Mastering Tripod Usage in Video Blogging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-users-guide-to-task-filtering-and-theme-tweaking-in-windows-11/"><u>The Complete User's Guide to Task Filtering & Theme Tweaking in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-nokia-c110-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Nokia C110 Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-manipulate-windows-11-search-highlights/"><u>Tricks to Manipulate Windows 11 Search Highlights</u></a></li>
<li><a href="https://app-tips.techidaily.com/ultimate-tutorial-on-clearing-out-your-visual-memories-photosimages-from-icloud-storage/"><u>Ultimate Tutorial on Clearing Out Your Visual Memories (Photos/Images) From iCloud Storage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-hidden-links-resuscitate-windows-networks/"><u>Unveiling Hidden Links: Resuscitate Windows Networks</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-top-5-udemy-subtitle-translation-tools-for-seamless-auto-translations/"><u>Updated 2024 Approved Top 5 Udemy Subtitle Translation Tools for Seamless Auto Translations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/will-generative-ai-like-chatgpt-take-over-my-job-understanding-the-impact-on-employment/"><u>Will Generative AI Like ChatGPT Take Over My Job? Understanding the Impact on Employment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-for-admin-restricted-windows-software/"><u>Workaround for Admin-Restricted Windows Software</u></a></li>
</ul></div>
