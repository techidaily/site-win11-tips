---
title: Restoring Faded Screen Settings in UEFI
date: 2024-07-12T17:02:51.420Z
updated: 2024-07-13T17:02:51.420Z
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
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-building-a-visual-story-on-facebook-with-slideshows/"><u>2024 Approved  Building a Visual Story on Facebook with Slideshows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenasolutiontowindowss-lsass-problem-step-by-step-guide/"><u>A CompreenasolutiontoWindows's Lsass Problem: Step by Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-honor-90-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Honor 90? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-new-windows-pin/"><u>A Step-by-Step Approach to New Windows PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363317332-troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows.</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-motorola-g24-power-drfone-by-drfone-android/"><u>How to Screen Mirroring Motorola G24 Power? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-itel-p40plus-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Itel P40+ to PC? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-mp4-video-download-companion-booklet/"><u>[New] 2024 Approved  MP4 Video Download Companion Booklet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-permanently-disable-microsoft-defender-in-windows-11/"><u>5 Ways to Permanently Disable Microsoft Defender in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-signs-its-probably-time-to-factory-reset-your-windows-pc/"><u>4 Signs It's Probably Time to Factory Reset Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-breakdown-of-mouse-customization-features-on-win11/"><u>A Complete Breakdown of Mouse Customization Features on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719377868664-is-prtscr-a-gateway-to-windows-11s-snipping-tool-no/"><u>Is PrtScr a Gateway to Windows 11'S Snipping Tool? No!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338441167-navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows.</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-the-ultimate-slack-filmora-duo-for-meeting-management-excellence/"><u>[New] The Ultimate Slack-Filmora Duo for Meeting Management Excellence</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-essential-guide-software-free-techniques-for-vimeo-downloads-for-2024/"><u>[New] Essential Guide  Software-Free Techniques for Vimeo Downloads for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-in-use-files-errors-in-windows-152-chars/"><u>Addressing 'In-Use' Files Errors in Windows (152 Chars)</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581335688-hasten-time-learn-1-10-in-japanese-numbers/"><u>Hasten Time, Learn 1-10 in Japanese Numbers</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-aspect-ratio-revolution-how-it-impacts-your-videos-visual-identity-for-2024/"><u>Updated Aspect Ratio Revolution How It Impacts Your Videos Visual Identity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-portaudio-fault-in-audacity-windows-11-os/"><u>Addressing PortAudio Fault in Audacity, Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-utorrent-installers-on-pc-with-os-x/"><u>Addressing Non-Functional uTorrent Installers on PC with OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-one-way-outlook-issue-in-secure-environments/"><u>Addressing the One-Way Outlook Issue in Secure Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-an-innovative-auto-refresh-check-option-to-the-windows-ui/"><u>Adding an Innovative Auto-Refresh Check Option to the Windows UI</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy M14 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-way-to-view-your-files-noteworthy-updates-in-windows-11/"><u>A New Way to View Your Files: Noteworthy Updates in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-package-registration-hurdles-in-win11-image-files/"><u>Addressing Package Registration Hurdles in Win11 Image Files</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-convert-avchd-mts-files-for-defy-2-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to convert AVCHD .mts files for Defy 2?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-power-management-hiding-dim-display/"><u>Accessing Power Management: Hiding 'Dim Display'</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-collages-a-look-at-the-best-of-12/"><u>2024 Approved  Mastering Collages  A Look at the Best of 12</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-expert-tips-extracting-audio-from-youtube-video-playback/"><u>[New] 2024 Approved  Expert Tips  Extracting Audio From YouTube Video Playback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-android-powered-webcams-in-windows-11-environments/"><u>A Guide to Android-Powered Webcams in Windows 11 Environments</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-secret-to-understanding-your-youtube-fans/"><u>[New] The Secret to Understanding Your YouTube Fans</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-economic-approaches-to-online-educational-broadcasting/"><u>[Updated] 2024 Approved  Economic Approaches to Online Educational Broadcasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-routes-to-reviving-the-elusive-windows-terminal/"><u>5 Routes to Reviving the Elusive Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-personalizing-windows-using-winbubble/"><u>A Step-by-Step Guide to Personalizing Windows Using WinBubble</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719317772933-reconcile-your-win-plus-print-discrepinasions-with-effective-solutions/"><u>Reconcile Your Win + Print Discrepinasions with Effective Solutions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-audience-captivation-at-its-peak-top-20-tiktok-caption-ideas/"><u>2024 Approved  Audience Captivation at Its Peak  Top 20 TikTok Caption Ideas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719348868755-is-your-pc-compatible-with-windows-11-see-here/"><u>Is Your PC Compatible with Windows 11? See Here</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/exploring-the-essence-of-vimeo-a-leader-in-video-platforms/"><u>Exploring the Essence of Vimeo  A Leader in Video Platforms</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/mastering-the-art-of-creating-alluring-fb-video-ads-for-2024/"><u>Mastering the Art of Creating Alluring FB Video Ads for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-ultimate-macos-manual-for-mixer-live-streaming-for-2024/"><u>The Ultimate MacOS Manual for Mixer Live Streaming for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-the-no-servers-found-error-in-apex-legends-for-windows/"><u>9 Ways to Fix the No Servers Found Error in Apex Legends for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrive-errors-in-windows-1011-system/"><u>Addressing OneDrive Errors in Windows 10/11 System</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-cam-clash-sj6-legend-versus-yi-4k-visionary/"><u>2024 Approved  Cam Clash  SJ6 Legend Versus Yi 4K Visionary</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-perfecting-pics-and-vids-the-art-of-snapchat-zooming/"><u>[New] Perfecting Pics & Vids  The Art of Snapchat Zooming</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-vivo-v30-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Vivo V30 Fingerprint Not Working Solutions</u></a></li>
</ul></div>
