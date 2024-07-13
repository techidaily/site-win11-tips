---
title: "Boost Security with VBox: Turn On/Off Secure Boot & TPM"
date: 2024-07-12T18:02:39.698Z
updated: 2024-07-13T18:02:39.698Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Security with VBox: Turn On/Off Secure Boot & TPM"
excerpt: "This Article Describes Boost Security with VBox: Turn On/Off Secure Boot & TPM"
keywords: Secure Boot Control,Enhance VM Security,Activate VBox Secure Boot,Use TPM in Virtualization,Improve System Protection,Turn On/Off TPM Feature,Optimize VM Performance
thumbnail: https://thmb.techidaily.com/d03c6bda0db9e446c0d9464753859ee1c2f12f38d94da77b1f5b8b2204a1d875.jpg
---

## Boost Security with VBox: Turn On/Off Secure Boot & TPM

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
<li><a href="https://driver-install.techidaily.com/tp-link-wi-fi-usb-drivers-simple-windows-installation/"><u>TP-Link Wi-Fi USB Drivers - Simple Windows Installation</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-12-drfone-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-your-windows-11-activation-status/"><u>Assessing Your Windows 11 Activation Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resources-windows-task-management/"><u>Balancing Resources: Windows Task Management</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-latest-guide-on-ipad-23-and-iphone-12-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Latest Guide on iPad 2/3 and iPhone 12 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-basics-cloning-without-external-help/"><u>Backup Basics: Cloning Without External Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-upgrades-to-windows-11s-clipboard-history/"><u>Boosting Efficiency: Upgrades to Windows 11'S Clipboard History</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enjoyable-footage-recorder-test/"><u>Enjoyable Footage Recorder Test</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-tremors-fixing-pointer-instability-in-windows/"><u>Avoid the Tremors: Fixing Pointer Instability in Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-laugh-out-loud-select-funny-photo-enhancers-online/"><u>[New] Laugh Out Loud  Select Funny Photo Enhancers Online</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-advanced-techniques-for-high-quality-youtube-content-for-2024/"><u>[Updated] Advanced Techniques for High-Quality YouTube Content for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-get-fb-videos-down-as-mp4-swiftly-and-simply/"><u>In 2024, Get FB Videos Down as MP4 – Swiftly & Simply</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-prime-video-capturing-applications/"><u>2024 Approved  Prime Video Capturing Applications</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-lockout-interval-after-unsuccessful-windows-sign-in/"><u>Adjusting Lockout Interval After Unsuccessful Windows Sign In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bargain-alert-key-enthusiasts-snag-612lifetime-windows-11-deal-today-only/"><u>Bargain Alert: Key Enthusiasts Snag $6.12/Lifetime Windows 11 Deal Today Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apple-maps-integration-guide-for-windows-devices/"><u>Apple Maps Integration Guide for Windows Devices</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-best-android-options-10-gb-emulation-tools-for-2024/"><u>[New] Best Android Options  10 GB Emulation Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-to-component-services-on-windows-11/"><u>Beginner’s Guide to Component Services on Windows 11</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-sony-xperia-5-v-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Sony Xperia 5 V Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-boundaries-artificinas-intelligence-in-windows-11/"><u>Beyond Boundaries: Artificinas Intelligence in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-the-real-value-of-selfie-verifications/"><u>[Updated] 2024 Approved  The Real Value of Selfie Verifications?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-overview-of-user-dissatisfaction-with-windows-11-upgrade/"><u>An Overview of User Dissatisfaction with Windows 11 Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/atlasos-makeover-new-life-for-vintage-pcs/"><u>AtlasOS Makeover: New Life for Vintage PCs</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-mini-to-other-iphone-15-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 mini To Other iPhone 15 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-final-cut-pro-tutorial-adding-realistic-motion-blur-for-2024/"><u>New Final Cut Pro Tutorial Adding Realistic Motion Blur for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitguard-compromised-continue-now-not-tomorrow/"><u>BitGuard Compromised: Continue Now, Not Tomorrow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/antivirus-alert-7-significant-windows-functions-under-scrutiny/"><u>Antivirus Alert: 7 Significant Windows Functions Under Scrutiny</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-superior-sound-capture-insiders-list-of-the-best-9-microphones-online/"><u>[Updated] In 2024, Superior Sound Capture  Insider's List of the Best 9 Microphones Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edges-app-guard-with-enhanced-graphics/"><u>Boosting Edge's App Guard with Enhanced Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-power-visibility-customizing-full-charge-alerts-for-win11/"><u>Boost Power Visibility: Customizing Full Charge Alerts for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-high-temperatures-in-windows-11-pcs/"><u>Avoiding High Temperatures in Windows 11 PCs</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Vivo V29 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-ancient-tech-upgrade-with-atlasos/"><u>Boost Ancient Tech: Upgrade with AtlasOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-instant-folders-generation-hacks-for-windows-users/"><u>Boost Your Workflow: Instant Folders Generation Hacks for Windows Users</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unwrapping-utopia-creating-magical-unboxing-moments/"><u>[Updated] Unwrapping Utopia  Creating Magical Unboxing Moments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-editing-setup-office-products-word-for-text-only-opened-attachments/"><u>Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-2023-free-music-samples-for-dreaming-up-your-next-visual-project/"><u>New 2024 Approved 2023 Free Music Samples for Dreaming Up Your Next Visual Project</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-ssd-performance-with-windows-and-ssd-fresh/"><u>Boosting SSD Performance with Windows & SSD Fresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-by-mastering-task-management-on-a-windows-11-pc/"><u>Boost Productivity by Mastering Task Management on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-capacity-securely-without-erasing-files/"><u>Boost Windows Capacity Securely without Erasing Files</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/elevate-your-visual-storytelling-with-these-5-top-photo-movie-makers/"><u>Elevate Your Visual Storytelling with These 5 Top Photo Movie Makers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-sharpen-zoom-conversations-eliminate-distortion/"><u>2024 Approved  Sharpen Zoom Conversations  Eliminate Distortion</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-best-top-vlog-editor-apps-for-iphone-and-android-for-2024/"><u>New Best Top Vlog Editor Apps for iPhone and Android for 2024</u></a></li>
</ul></div>
