---
title: Reinvigorating Old BIOS Color Schemes
date: 2024-10-04T21:25:18.050Z
updated: 2024-10-09T07:09:42.567Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinvigorating Old BIOS Color Schemes
excerpt: This Article Describes Reinvigorating Old BIOS Color Schemes
keywords: BIOS Revive Colors,Updated BIOS Palette,Refresh BIOS Hue,New BIOS Theme,Enhanced BIOS Shade,BIOS Color Renewal,Retro BIOS Update
thumbnail: https://thmb.techidaily.com/c7c73b7c4a7efc6c835802b5aee6775aac1b5aafcbc08ea28ac48bf90c458f91.jpg
---

## Reinvigorating Old BIOS Color Schemes

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
<a href="https://aligracehair.sjv.io/c/5597632/1975802/19272" target="_top" id="1975802">
  <img src="//a.impactradius-go.com/display-ad/19272-1975802" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975802/19272" style="position:absolute;visibility:hidden;" border="0" />
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
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.

<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148640/16836" target="_top" id="2148640">
  <img src="//a.impactradius-go.com/display-ad/16836-2148640" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148640/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-guidance.techidaily.com/new-understanding-crossfade-audio-transitions/"><u>[New] Understanding Crossfade Audio Transitions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-gallery-archive-websites/"><u>[Updated] Best Gallery Archive Websites</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-decoding-the-art-of-asmr-filmmaking-techniques/"><u>[Updated] Decoding the Art of ASMR Filmmaking Techniques</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-in-depth-look-at-facetune-a-photographers-best-friend/"><u>2024 Approved In-Depth Look at Facetune A Photographer’s Best Friend</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-no-display-available-on-windows-11/"><u>Counteracting 'No Display Available' On Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/effortless-conversion-guide-turning-your-m4b-tracks-into-mp3-players/"><u>Effortless Conversion Guide: Turning Your M4B Tracks Into MP3 Players</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-mkv-to-mp4-transformation-on-windows/"><u>Navigating Through MKV-to-MP4 Transformation on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/steps-for-gradual-audio-dimming-with-lumafusion/"><u>Steps for Gradual Audio Dimming with Lumafusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-system-efficiency-incorporating-law-filters-into-your-workflow/"><u>Streamlining System Efficiency: Incorporating LAW Filters Into Your Workflow</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-updated-method-to-bypass-oppo-a38-frp-by-drfone-android/"><u>The Updated Method to Bypass Oppo A38 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-4-innovations-microsoft-paint-revamped/"><u>Top 4 Innovations: Microsoft Paint Revamped</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-precision-audio-technicians-handbook-comprehensive-approaches-to-reverb-removal-for-2024/"><u>Updated The Precision Audio Technicians Handbook Comprehensive Approaches to Reverb Removal for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-timeline-6-ways-to-get-your-systems-timer-running/"><u>Windows Timeline: 6 Ways to Get Your System's Timer Running</u></a></li>
</ul></div>

