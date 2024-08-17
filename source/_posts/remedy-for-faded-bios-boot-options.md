---
title: Remedy for Faded BIOS Boot Options
date: 2024-08-16T01:35:45.397Z
updated: 2024-08-17T01:35:45.397Z
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

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
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

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-audio-amplified-todays-hits-backdropping-yt-shorts/"><u>[New] 2024 Approved  Audio Amplified  Today's Hits Backdropping YT Shorts</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-essential-tips-for-perfecting-photos-via-snapchat-edit-features/"><u>[New] 2024 Approved  Essential Tips for Perfecting Photos via Snapchat Edit Features</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-prime-5-image-background-altering-mobile-apps-iphone/"><u>[New] 2024 Approved  Prime 5 Image Background Altering Mobile Apps (iPhone)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-srt-file-open-srt-file-on-windows-or-mac/"><u>[New] SRT File  Open SRT File on Windows or Mac</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-streamlining-your-gaming-experience-windows-11-edition-for-2024/"><u>[New] Streamlining Your Gaming Experience  Windows 11 Edition for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-speak-with-synthetic-voices-chromebooks-leading-online-text-to-speech-apps/"><u>[Updated] 2024 Approved  Speak with Synthetic Voices  Chromebook's Leading Online Text-to-Speech Apps</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-elevate-your-team-with-expert-talent-selections/"><u>2024 Approved  Elevate Your Team with Expert Talent Selections</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-which-live-stream-software-wins-exploring-obs-vs-streamlabs/"><u>2024 Approved  Which Live Stream Software Wins? Exploring OBS Vs. Streamlabs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/5-most-effective-methods-to-unlock-apple-iphone-se-in-lost-mode-by-drfone-ios/"><u>5 Most Effective Methods to Unlock Apple iPhone SE in Lost Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-get-the-most-out-of-the-windows-11-taskbar/"><u>7 Ways to Get the Most Out Of the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lsassexe-component-not-found-error-in-windows/"><u>Addressing lsass.exe Component Not Found Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-barriers-the-role-of-copilot-key-in-windows-11/"><u>Breaking Down Barriers: The Role of Copilot Key in Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-evaluation-of-the-razer-blade-stealth-nix-redefining-ultp-innovation/"><u>Comprehensive Evaluation of the Razer Blade Stealth Nix: Redefining ULTP Innovation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-windows-11-unrecognized-devices/"><u>Curing Windows 11 Unrecognized Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-mechanics-behind-failed-usb-attachment-in-virtualbox/"><u>Decoding the Mechanics Behind Failed USB Attachment in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-upcoming-changes-with-windows-11-version-22h2/"><u>Delving Into Upcoming Changes with Windows 11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-the-ui-for-windows-11s-self-update-checker/"><u>Designing the UI for Windows 11'S Self-Update Checker</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Realme GT 3? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-routes-to-access-windows-11-display-settings-in-10-steps/"><u>Essential Routes to Access Windows 11 Display Settings in 10 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resynchronize-google-drive-on-desktop-os/"><u>Essential Steps to Resynchronize Google Drive on Desktop OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-oppo-a38-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Oppo A38.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-and-change-the-subnet-mask-in-windows-11/"><u>How to Find and Change the Subnet Mask in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-v29-pro-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Vivo V29 Pro</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-samsung-galaxy-m14-5g-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Samsung Galaxy M14 5G Phone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-mastering-iphone-xs-identity-verification-face-id-repair/"><u>In 2024, Mastering iPhone X's Identity Verification  Face ID Repair</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-oppo-reno-10-pro-5g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Oppo Reno 10 Pro 5G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-11-os-the-installation-of-outlook-preview-app/"><u>Leveraging Windows 11 OS: The Installation of Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cc-errors-on-windows-10-a-step-by-step-guide/"><u>Mastering CC Errors on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-multi-screen-setup-on-windows-11/"><u>Mastering Multi-Screen Setup on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-desktop-potential-with-new-features-in-win-11-widgets/"><u>Maximize Your Desktop Potential with New Features in Win 11 Widgets</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-itel-a70-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Itel A70 Phone? Unlock It Now</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-with-windows-11-rebuild/"><u>New Horizons with Windows 11 Rebuild</u></a></li>
<li><a href="https://review-topics.techidaily.com/oppo-data-retrieval-tool-restore-lost-data-from-oppo-f23-5g-by-fonelab-android-recover-data/"><u>Oppo Data Retrieval tool – restore lost data from Oppo F23 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-printer-connection-failsafes-in-windows/"><u>Overcoming Printer Connection Failsafes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-of-your-windows-headset-mic/"><u>Regain Control of Your Windows Headset Mic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-default-energy-management-in-windows-11/"><u>Regaining Default Energy Management in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-valorants-speech-issues-on-pc/"><u>Resolving Valorant's Speech Issues on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-image-import-error-with-apple-devices-step-by-step/"><u>Resolving Windows 11'S Image Import Error with Apple Devices Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-decades-old-windows-authentication-error/"><u>Reversing Decades-Old Windows Authentication Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routine-to-reach-wordpad-functionality-in-windows/"><u>Routine to Reach WordPad Functionality in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-security-faults-effectively/"><u>Steps to Tackle Windows Security Faults Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-connectivity-issues-with-geforce-experience-software/"><u>Tackling Connectivity Issues with GeForce Experience Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-not-signed-update-problem-in-win11win10/"><u>Troubleshooting 'Not Signed' Update Problem in Win11/Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-disabled-roblox-game-due-to-user-settings-in-windows/"><u>Troubleshooting Disabled Roblox Game Due to User Settings in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unexpectedly-installed-rav-trace-back-and-efface-it/"><u>Unexpectedly Installed Rav? Trace Back & Efface It</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleashing-creative-potential-with-pixiz-for-photo-videos/"><u>Unleashing Creative Potential with Pixiz for Photo Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-and-solving-the-mystery-of-error-0x8007251d/"><u>Unpacking and Solving the Mystery of Error 0X8007251d</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-resolving-windows-store-issue-code-0x00000000/"><u>Unraveling and Resolving Windows Store Issue Code 0X00000000</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-to-professional-recording-on-windows-11/"><u>Unveiling the Secrets to Professional Recording on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-application-space-consumption-guide/"><u>Windows Application Space Consumption Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-key-control-a-step-by-step-approach/"><u>Windows Key Control - A Step-by-Step Approach</u></a></li>
</ul></div>
