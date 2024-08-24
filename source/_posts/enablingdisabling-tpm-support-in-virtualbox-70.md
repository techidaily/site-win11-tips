---
title: Enabling/Disabling TPM Support in VirtualBox 7.0
date: 2024-08-23T06:59:58.738Z
updated: 2024-08-24T06:59:58.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling/Disabling TPM Support in VirtualBox 7.0
excerpt: This Article Describes Enabling/Disabling TPM Support in VirtualBox 7.0
keywords: Enable TPM VirtualBox,Disable TPM VirtualBox,TPM Support VirtualBox,VirtualBox TPM Control,Manage TPM in VirtualBox,Turning TPM On/Off Vbox,VirtualBox TPM Settings
thumbnail: https://thmb.techidaily.com/e7b26cce85084898820694a03b988f46853880c83b86563e047e92a3e8096101.jpg
---

## Enabling/Disabling TPM Support in VirtualBox 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-hidden-features-top-30-unknown-window-11-tips/"><u>[New] In 2024, Hidden Features  Top 30 Unknown WINDOW 11 Tips</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-navigating-instagrams-search-function-a-pathway-to-complimentary-filters-for-2024/"><u>[New] Navigating Instagram's Search Function  A Pathway to Complimentary Filters for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-perfecti-the-ultimate-guide-to-iphone-slideshows-xs-max/"><u>[New] Perfecti  The Ultimate Guide to iPhone Slideshows (XS Max)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-top-picks-for-virtual-globe-tourists/"><u>[New] Top Picks for Virtual Globe Tourists</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unique-14-motion-graphics-showcasing-text/"><u>[New] Unique 14 Motion Graphics Showcasing Text</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-launchpad-for-twitter-beginners/"><u>[Updated] 2024 Approved  Launchpad for Twitter Beginners</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-building-a-broad-spectrum-audience-with-multichannel-strategy/"><u>[Updated] Building a Broad-Spectrum Audience with Multichannel Strategy</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-how-to-upload-horizontal-videos-to-igtv/"><u>[Updated] In 2024, How to Upload Horizontal Videos to IGTV</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-analyzing-the-financial-gains-of-podcasting/"><u>2024 Approved  Analyzing the Financial Gains of Podcasting</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-strategizing-against-the-phantom-follower-phenomenon/"><u>2024 Approved  Strategizing Against the Phantom Follower Phenomenon</u></a></li>
<li><a href="https://tech-revival.techidaily.com/clear-internet-data-for-faster-browsing-a-user-friendly-guide-for-windows-10-operating-system/"><u>Clear Internet Data for Faster Browsing: A User-Friendly Guide for Windows 10 Operating System</u></a></li>
<li><a href="https://extra-information.techidaily.com/clearing-up-disrupted-visual-playback-online/"><u>Clearing Up Disrupted Visual Playback Online</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-directdraw-fails-a-practical-approach-for-win11-users/"><u>Conquering DirectDraw Fails: A Practical Approach for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-overcoming-windows-error-code-0x80070570-for-you/"><u>Decoding and Overcoming Windows Error Code 0X80070570 for You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defeating-server-hiccups-a-microsoft-store-error-guide-for-win-1011/"><u>Defeating Server Hiccups: A Microsoft Store Error Guide for Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-disk-read-problems-in-windows/"><u>Eliminating Disk Read Problems in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-os-compatibility-for-adobes-creative-suite/"><u>Enhancing OS Compatibility for Adobe's Creative Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-windows-shop-crash-overcoming-error-x00000000/"><u>Eradicating Windows Shop Crash: Overcoming Error X00000000</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-unhandled-exception-a-step-by-step-process/"><u>Fixing Windows 'Unhandled Exception': A Step-by-Step Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-error-code-0xc00000f-instantly/"><u>Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/future-of-work-the-impact-of-generative-ai-on-job-landscape/"><u>Future of Work: The Impact of Generative AI on Job Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-rectify-windows-bluetooth-outputs-music-only/"><u>Guidelines to Rectify Windows Bluetooth Outputs - Music Only</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correctly-unstrand-your-gaming-experience-in-windows/"><u>How to Correctly Unstrand Your Gaming Experience in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-retrieve-lost-default-volume-levels-on-pc/"><u>How to Retrieve Lost Default Volume Levels on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reverse-the-activation-failure-code-0x803f700f/"><u>How to Reverse the Activation Failure: Code 0X803f700f</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-realme-12-pro-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Realme 12 Pro 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intelligent-battery-alerts-set-up-full-charges-in-windows-11/"><u>Intelligent Battery Alerts: Set Up Full Charges in Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/key-dialogues-unraveling-crypto-and-ai/"><u>Key Dialogues Unraveling Crypto & AI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-windows-programs-that-aid-the-transition-from-apple-devices/"><u>Key Windows Programs That Aid the Transition From Apple Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restoring-lost-ps4-input-connection/"><u>Mastering the Art of Restoring Lost PS4 Input Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-text-environment-a-windows-11-notepad-guide/"><u>Mastering Your Text Environment: A Windows 11 Notepad Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/maximizing-your-digital-gold-rush-the-ultimate-list-of-leading-cryptocurrency-mining-gpus-according-to-toms-hardware/"><u>Maximizing Your Digital Gold Rush: The Ultimate List of Leading Cryptocurrency Mining GPUs According to Tom's Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-11s-geforce-now-xc0f1103f-fix/"><u>Mending Windows 11’S GeForce Now: Xc0f1103f Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-driver-failed-to-initialize-error-in-windows-11/"><u>Mitigating Driver Failed to Initialize Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-controller-on-windows-calibration-techniques/"><u>Optimizing Your Controller on Windows: Calibration Techniques</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Lava Agni 2 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/professional-take-the-syma-x5c-ideal-first-timers-droning-companion-for-2024/"><u>Professional Take  The Syma X5C – Ideal First-Timer's Droning Companion for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-the-menu-strategies-against-freezing-windows/"><u>Reactivating the Menu: Strategies Against Freezing Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscover-classics-atlasos-refresh/"><u>Rediscover Classics: AtlasOS Refresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refresh-classics-atlasos-gaming-update/"><u>Refresh Classics: AtlasOS Gaming Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-code-0x80073cf3-in-windows/"><u>Resolving Microsoft Store Error Code 0X80073CF3 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sleep-mode-stuck-keyboard-mouse-fix-for-win1011/"><u>Sleep Mode Stuck: Keyboard, Mouse Fix for Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-a-nonresponsive-discord-overlay-window-on-windows/"><u>Solutions for a Nonresponsive Discord Overlay Window on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-find-windows-11s-authorize-center/"><u>Steps to Find Windows 11'S Authorize Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-android-studio-operations-a-win32-guide/"><u>Streamlining Android Studio Operations: A Win32 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-trigger-camera-notification-in-win11-os/"><u>Techniques to Trigger Camera Notification in Win11 OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-final-act-steps-for-permanent-instagram-account-removal-for-2024/"><u>The Final Act  Steps for Permanent Instagram Account Removal for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-quick-route-to-joy-embracing-the-ifunny-meme-app-for-2024/"><u>The Quick Route to Joy  Embracing the iFunny Meme App for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-ensure-camera-activity-notifications-in-ws11/"><u>Tips to Ensure Camera Activity Notifications in WS11</u></a></li>
<li><a href="https://some-skills.techidaily.com/tops-in-vocal-transformation-tech-featuring-magic-for-2024/"><u>Tops in Vocal Transformation Tech, Featuring Magic for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transitioning-to-excellence-4-crucial-factors-that-make-claude-3-a-superior-choice-over-chatgpt/"><u>Transitioning to Excellence: 4 Crucial Factors That Make Claude 3 a Superior Choice Over ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-sluggish-microsoft-edge-on-windows-1011/"><u>Troubleshooting Sluggish Microsoft Edge on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficiency-installing-windows-11-on-workstation-17/"><u>Unlocking Efficiency: Installing Windows 11 on Workstation 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-index-options-breakdown/"><u>Windows Index Options Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrar-sync-failures-6-methods-for-checksum-harmony/"><u>WinRAR Sync Failures: 6 Methods for Checksum Harmony</u></a></li>
</ul></div>
