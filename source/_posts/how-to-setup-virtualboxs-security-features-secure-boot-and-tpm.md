---
title: "How to Setup VirtualBox's Security Features: Secure Boot & TPM"
date: 2024-07-12T16:36:33.264Z
updated: 2024-07-13T16:36:33.264Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Setup VirtualBox's Security Features: Secure Boot & TPM"
excerpt: "This Article Describes How to Setup VirtualBox's Security Features: Secure Boot & TPM"
keywords: VirtualBox Security Basics,Enable Secure Boot VBox,Manage TPM in VirtualBox,VirtualBox TPM Configuration,Virtualization Security Features,Setup Secure Boot in VMs,Optimize VirtualBox TPM Use
thumbnail: https://thmb.techidaily.com/d765545ba359efe066eea79e8d50579ac2c2c25cde956ba79513b5dc7e88e8de.jpg
---

## How to Setup VirtualBox's Security Features: Secure Boot & TPM

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on [what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://win11-tips.techidaily.com/efficient-remedies-to-immediate-addition-problems-for-your-onedrive-drive/"><u>Efficient Remedies to Immediate Addition Problems for Your OneDrive Drive</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-twitter-visual-content-proportions/"><u>2024 Approved  Twitter Visual Content Proportions</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/mastering-call-recording-on-google-voice-a-comprehensive-guide-for-2024/"><u>Mastering Call Recording on Google Voice A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-shifting-your-powertoys-profile-to-another-pc/"><u>Efficiently Shifting Your PowerToys Profile to Another PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-soon-expiring-license-messages-from-your-pc/"><u>Eliminating “Soon Expiring License” Messages From Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-insufficient-access-error-on-win-11-pcs/"><u>How to Bypass Insufficient Access Error on Win 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-the-classics-with-clear-cut-winning-strategies-for-high-definition-hd/"><u>Ace the Classics with Clear-Cut Winning Strategies for High-Definition HD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-erase-files-for-good-on-your-windows-11-and-11-desktop-bin/"><u>How to Erase Files for Good on Your Windows 11 & 11 Desktop Bin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-seamless-multilingual-input-adjusting-keyboard-layout-in-windows-11/"><u>Achieve Seamless Multilingual Input: Adjusting Keyboard Layout in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hack-your-hardware-close-multiple-windows-at-once/"><u>Hack Your Hardware: Close Multiple Windows at Once</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-local-groups-policy-a-focused-approach-for-users-in-windows-11-and-11/"><u>Directing Local Groups Policy: A Focused Approach for Users in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-pc-tune-ups-wins-prime-performance-hacks/"><u>Essential PC Tune-Ups: Win's Prime Performance Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-art-microsoft-paints-latest-enhancements/"><u>Mastering Art: Microsoft Paint's Latest Enhancements</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-10-blockbuster-films-edited-with-final-cut-pro/"><u>Updated 2024 Approved 10 Blockbuster Films Edited with Final Cut Pro</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-charismatic-oratory-study-part-8/"><u>[Updated] In 2024, Charismatic Oratory Study Part 8</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-tecno-pova-5-pro-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Tecno Pova 5 Pro FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-restore-connection-with-vanished-ubisoft-launcher/"><u>Guide to Restore Connection with Vanished Ubisoft Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-resolving-rdp-errors-in-windows-11/"><u>Essential Tips for Resolving RDP Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-are-windows-cab-files-and-how-do-you-install-them/"><u>What Are Windows CAB Files and How Do You Install Them?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dism-strategies-reviving-windows-11-images/"><u>DISM Strategies: Reviving Windows 11 Images</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-basics-of-capturing-switch-gaming-moments/"><u>The Basics of Capturing Switch Gaming Moments</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-realme-11x-5g-frp-by-drfone-android/"><u>The Updated Method to Bypass Realme 11X 5G FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assess-power-demands-in-windows-based-personal-computers/"><u>Assess Power Demands in Windows-Based Personal Computers</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-top-15-screen-snappers-for-win10/"><u>2024 Approved  Top 15 Screen Snappers for Win10</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-vivo-y17s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-common-youtube-shorts-when-thumbnails-disappear-without-notice/"><u>[New] Common YouTube Shorts  When Thumbnails Disappear Without Notice</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-get-free-followers-on-tiktok-in-10-ways/"><u>[Updated] In 2024, Get Free Followers on TikTok in 10 Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-woes-cure-non-responsive-f-keys-now/"><u>Windows 10 Woes? Cure Non-Responsive F-Keys Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guideline-for-granting-google-chrome-permissions-through-firewalls/"><u>Guideline for Granting Google Chrome Permissions Through Firewalls</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-12-pro-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 12 Pro To Other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-security-account-manager-glitches/"><u>Correcting Windows Security Account Manager Glitches</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-decoding-the-art-of-engaging-in-youtube-short-forms/"><u>[New] 2024 Approved  Decoding the Art of Engaging in YouTube Short Forms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwelcome-closure-messages-from-your-roblox-games/"><u>Avoiding Unwelcome Closure Messages From Your Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificial-insight-windows-software-reinvented/"><u>Artificial Insight: Windows Software Reinvented</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-endure-and-correct-win11s-fatal-bug/"><u>How to Endure and Correct Win11's Fatal Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-fixes-for-unstartable-windows-services/"><u>Implementing Fixes for Unstartable Windows Services</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-realtime-recording-titans/"><u>[New] In 2024, RealTime Recording Titans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-visibility-of-results-with-windows-11-search-fixes/"><u>Enhancing Visibility of Results with Windows 11 Search Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-to-stop-windows-10-blue-screens/"><u>Essential Fixes to Stop Windows 10 Blue Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-error-30005-struggles-with-new-file-creation/"><u>Fixing Windows Error 30005 - Struggles with New File Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-obscure-to-owned-taking-control-of-your-username-in-windows-11/"><u>From Obscure to Owned: Taking Control of Your UserName in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-to-reinstate-normal-access-in-microsofts-safe-mode-outlook/"><u>Guidance to Reinstate Normal Access in Microsoft's Safe Mode Outlook</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-roadmap-to-an-influential-instagram-profile-six-simple-steps-for-following-and-verified-recognition-for-2024/"><u>The Roadmap to an Influential Instagram Profile  Six Simple Steps for Following and Verified Recognition for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tech-picks-leading-drone-gimbals-for-2024/"><u>Tech Picks  Leading Drone Gimbals for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/fast-flexible-and-fantastic-best-light-video-editing-options/"><u>Fast, Flexible, and Fantastic Best Light Video Editing Options</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/what-is-lumetri-color-and-how-do-you-use-it-in-adobe-after-effects-find-out-the-numerous-functions-of-lumetri-panel-and-ways-to-apply-them-to-your-video-for/"><u>What Is Lumetri Color and How Do You Use It in Adobe After Effects? Find Out the Numerous Functions of Lumetri Panel and Ways to Apply Them to Your Video for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-motorola-razr-40-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Motorola Razr 40 Location Settings | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-from-filming-to-sharing-a-youtube-video-edition/"><u>[Updated] From Filming to Sharing  A YouTube Video Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sticky-notes-display-on-win-11/"><u>Mastering the Art of Sticky Notes Display on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstalling-microsoft-store-apps-on-windows-10-and-11/"><u>Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/discovering-your-favorite-makeup-vloggers-on-youtube/"><u>Discovering Your Favorite Makeup Vloggers on YouTube</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/adsense-on-youtube-determining-your-income-from-1k-viewer-engagement/"><u>AdSense on YouTube  Determining Your Income From 1K Viewer Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-the-ultimate-start-menu-guide/"><u>Mastering Windows 11: The Ultimate Start Menu Guide</u></a></li>
</ul></div>
