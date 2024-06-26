---
title: Boost Virtual Machine Security with VBox's Secure Boot Toggle
date: 2024-06-25T16:38:08.504Z
updated: 2024-06-26T16:38:08.504Z
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
<li><a href="https://win11-tips.techidaily.com/enhancing-file-sharing-capabilities-in-geforce/"><u>Enhancing File-Sharing Capabilities in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-updating-windows-in-isolation/"><u>The Art of Updating Windows in Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-keyscalyping-restore-your-arrows-now/"><u>Keyboard Keyscalyping? Restore Your Arrows Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synchronizing-sound-pathways-resolving-paudio-in-winaudacity/"><u>Synchronizing Sound Pathways: Resolving PAudio in WINAudacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-to-follow-plan-starting-over-with-windows-updates/"><u>Easy-to-Follow Plan: Starting Over with Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-suppress-mechanism-for-windows-11-dings/"><u>Quick Suppress Mechanism for Windows 11 Dings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-network-issues-on-windows-11-a-comprehensible-approach/"><u>Overcoming Network Issues on Windows 11 - A Comprehensible Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increase-output-decrease-time-harness-power-of-flow-launcher/"><u>Increase Output, Decrease Time: Harness Power of Flow Launcher</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/a-comprehensive-examination-of-obs-recording-tech-for-2024/"><u>A Comprehensive Examination of OBS Recording Tech for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-efficiently-uploading-youtube-vids-to-insta-profile/"><u>[Updated] In 2024, Efficiently Uploading YouTube Vids to Insta Profile</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-secret-source-to-make-a-great-stop-motion-puppet-for-2024/"><u>New Secret Source to Make a Great Stop Motion Puppet for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/essential-six-hubs-where-companies-thrive-socially-and-professionally/"><u>Essential Six Hubs Where Companies Thrive Socially & Professionally</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-unveiling-secrets-of-effortless-screen-sharing-in-meet-for-2024/"><u>[Updated] Unveiling Secrets of Effortless Screen Sharing in Meet for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-slideshow-makers-are-on-demand-as-they-come-with-multiple-possibilities-for-both-professional-and-personal-uses-gradually-the-best-software-to-make-/"><u>In 2024, Slideshow Makers Are On-Demand as They Come with Multiple Possibilities for Both Professional and Personal Uses. Gradually, the Best Software to Make Slideshows Is Always Welcomed to Save Time and Effort without Compromising the Quality</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-dual-display-video-editing-top-apps-for-iphone-and-android/"><u>Updated Dual-Display Video Editing Top Apps for iPhone and Android</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/loom-lens-illuminating-your-recording-journey-for-2024/"><u>Loom Lens  Illuminating Your Recording Journey for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Infinix Smart 7 HD | Dr.fone</u></a></li>
</ul></div>
