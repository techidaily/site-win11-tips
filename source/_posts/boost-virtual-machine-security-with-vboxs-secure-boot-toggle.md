---
title: Boost Virtual Machine Security with VBox's Secure Boot Toggle
date: 2024-08-16T01:59:44.216Z
updated: 2024-08-17T01:59:44.216Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost Virtual Machine Security with VBox's Secure Boot Toggle
excerpt: This Article Describes Boost Virtual Machine Security with VBox's Secure Boot Toggle
keywords: Boost VM Safety,Secure VM Box,VBox Security Enhance,VM Protection Switch,Safe Virtual Machine,Turn On Secure Boot,Toggle VM Security
thumbnail: https://thmb.techidaily.com/6669b51a644a6e6a471c5e95129c578aa098ea11ffbe838822c268118ff95e70.jpg
---

## Boost Virtual Machine Security with VBox's Secure Boot Toggle

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on [what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-how-to-make-killer-youtube-channel-art/"><u>[New] 2024 Approved  How to Make Killer YouTube Channel Art</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/uy-youtube-subscribers-hundreds-of-subscribers-for-5/"><u>[New] Buy YouTube Subscribers - Hundreds of Subscribers for $5?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-optimal-low-price-nintendo-simulations/"><u>[New] In 2024, Optimal Low-Price Nintendo Simulations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-kick-starting-a-captivating-instagram-live/"><u>[New] Kick-Starting a Captivating Instagram Live</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfecting-your-interview-role-a-comprehensive-guide/"><u>[New] Perfecting Your Interview Role  A Comprehensive Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-streamlining-movie-file-processing-in-windows-11/"><u>[New] Streamlining Movie File Processing in Windows 11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-demystifying-gopro-video-capture-with-burst-mode/"><u>[Updated] 2024 Approved  Demystifying GoPro Video Capture with Burst Mode</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-financially-flourishing-online-media-personality/"><u>[Updated] Financially Flourishing Online Media Personality</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-50-free-youtube-banners-come-see-them-all/"><u>[Updated] In 2024, 50 FREE YouTube Banners - Come See Them All!</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-ultimate-guide-to-the-finest-3d-blu-ray-equipment-for-2024/"><u>[Updated] Ultimate Guide to the Finest 3D Blu-Ray Equipment for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-bridging-the-gap-audio-to-text-in-powerpoint-slides/"><u>2024 Approved  Bridging the Gap  Audio to Text in PowerPoint Slides</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-transform-personal-experiences-through-direct-webcam-capture-using-vlc/"><u>2024 Approved  Transform Personal Experiences Through Direct Webcam Capture Using VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-troubleshooting-tactics-for-non-functional-firefox-in-windows/"><u>7 Troubleshooting Tactics for Non-Functional Firefox in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-task-managers-welcome-screenscape-in-win11/"><u>Adjusting Task Manager's Welcome Screenscape in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-character-map-hurdles-a-step-by-step-solution/"><u>Breaking Down Windows Character Map Hurdles: A Step-by-Step Solution</u></a></li>
<li><a href="https://fox-helps.techidaily.com/chrono-capture-excellence-slomo-apps-complete-critique-2024/"><u>Chrono-Capture Excellence  SloMo App's Complete Critique, 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-way-for-smooth-steam-disk-operations/"><u>Clearing the Way for Smooth Steam Disk Operations</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/detailed-ice-cream-snapshot-analysis-report/"><u>Detailed Ice Cream Snapshot Analysis Report</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-transformation-for-windows-old-to-new-drivers/"><u>Digital Transformation for Windows: Old to New Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-browsing-experience-in-win-11-by-enabling-ms-defender-application-guard/"><u>Elevate Your Browsing Experience in Win 11 by Enabling MS Defender Application Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-validity-of-windows-11-temp-files/"><u>Ensuring Validity of Windows 11 Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-unintended-mouse-scrolling-with-these-7-tricks/"><u>Eradicate Unintended Mouse Scrolling with These 7 Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-eliminating-windows-temp-files/"><u>Expert Advice for Eliminating Windows' Temp Files</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-advice-on-computing-equipment-from-toms-hardware-hub/"><u>Expert Advice on Computing Equipment From Tom's Hardware Hub</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-the-world-of-wireless-music-streaming-with-dts-play-fi/"><u>Exploring the World of Wireless Music Streaming with DTS Play-Fi</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-motorola-razr-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-samsung-galaxy-a05-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Samsung Galaxy A05 Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-instantaneously-generating-multiple-subfolders-in-windows/"><u>Innovative Approaches to Instantaneously Generating Multiple Subfolders in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-unison-explained-easy-mobile-dialing-on-the-latest-windows-11/"><u>Intel Unison Explained: Easy Mobile Dialing on the Latest Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-xiaomi-redmi-k70-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Xiaomi Redmi K70 Phone FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-non-uniform-colour-realms-in-windows/"><u>Navigating Non-Uniform Colour Realms in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-d3d11-gpu-error-landscape-for-windows-1110/"><u>Navigating the D3D11 GPU Error Landscape for Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-sound-settings-efficiently-using-these-9-strategies-in-windows-11/"><u>Open Sound Settings Efficiently Using These 9 Strategies in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-problems-with-saving-windows-volume-configurations/"><u>Overcoming Problems with Saving Window's Volume Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-exception-breakpoint-obstacle/"><u>Overcoming Windows Exception Breakpoint Obstacle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-data-theft-controlling-removable-storage-on-pcs/"><u>Preventing Data Theft: Controlling Removable Storage on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quash-windows-data-on-launches-tracking/"><u>Quash Windows Data on Launches Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivation-guide-for-your-frozen-windows-11-search-box/"><u>Reactivation Guide for Your Frozen Windows 11 Search Box</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-motorola-moto-g84-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Motorola Moto G84 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-steam-data-flow-escaping-slowdown-traps/"><u>Revitalizing Steam Data Flow: Escaping Slowdown Traps</u></a></li>
<li><a href="https://win-amazing.techidaily.com/revolutionary-fix-how-to-get-your-samsung-blu-ray-player-up-and-running-again/"><u>Revolutionary Fix: How to Get Your Samsung Blu-Ray Player Up and Running Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-ping-in-routine-windows-tasks/"><u>Seamless Integration of Ping in Routine Windows Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-telnet-activation-on-latest-windows-systems/"><u>Secure Telnet Activation on Latest Windows Systems</u></a></li>
<li><a href="https://video-capture.techidaily.com/secure-stylish-and-smart-choose-from-these-5-recorders/"><u>Secure, Stylish and Smart - Choose From These 5 Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-management-with-windows-autodelete-feature/"><u>Simplifying File Management with Windows' AutoDelete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-a-halted-download-the-windows-method/"><u>Speeding up a Halted Download: The Windows Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-package-unopenable-issue-effectively/"><u>Steps to Tackle Windows Package Unopenable Issue Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-share-failures-on-geforce-experience-for-w10w11/"><u>Tackling Share Failures on GeForce Experience for W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-to-fix-error-0x800700e1-in-windows-11/"><u>Tips & Tricks to Fix Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-device-diversity-into-a-single-note-world/"><u>Transforming Device Diversity Into a Single Note World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wasd-isolation-necessity-or-concern/"><u>Understanding WASD Isolation: Necessity or Concern?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-capability-of-windows-11-with-multi-display-setup/"><u>Unlock the Full Capability of Windows 11 With Multi-Display Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-adopting-sudo-can-transform-your-windows-experience/"><u>Why Adopting Sudo Can Transform Your Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-clean-boot-a-beginners-approach/"><u>Windows 11 Clean Boot: A Beginner's Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wizardry-learn-hotkeys-to-manage-your-pc/"><u>Windows Wizardry: Learn Hotkeys to Manage Your PC</u></a></li>
</ul></div>
