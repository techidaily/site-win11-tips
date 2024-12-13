---
title: Secure Boot and TPM Setup Guide for VirtualBox
date: 2024-12-10T17:57:39.145Z
updated: 2024-12-12T18:39:38.691Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secure Boot and TPM Setup Guide for VirtualBox
excerpt: This Article Describes Secure Boot and TPM Setup Guide for VirtualBox
keywords: VirtualBox Secure Boot,VirtualBox TPM Guide,TPM Installation VMware,Enable Secure Boot Vbox,Virtual Machine TPM Setup,Booting Security VMware,TPM Config in VirtualBox
thumbnail: https://thmb.techidaily.com/7d954d5ef5beb31b578dcda4509d16e23f0ef0d1b79a76b01e4834ddb01328ea.jpg
---

## Secure Boot and TPM Setup Guide for VirtualBox

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
8. Now, click on the**OK** button. The settings window will close automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-unravel-media-complexity-transforming-xmlttml-into-srt-gold/"><u>[New] 2024 Approved Unravel Media Complexity Transforming XML/TTML Into SRT Gold</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-expertise-in-speech-conversion-mastering-googles-method/"><u>[New] In 2024, Expertise in Speech Conversion Mastering Google’s Method</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-unveiling-the-10-best-free-os-agnostic-video-solutions-for-2024/"><u>[New] Unveiling the 10 Best Free OS-Agnostic Video Solutions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-hyper-v-installation-in-windows-11-home-systems/"><u>Conquering Hyper-V Installation in Windows 11 Home Systems</u></a></li>
<li><a href="https://screen-capture.techidaily.com/getting-ahead-with-professional-itunes-capture-methods/"><u>Getting Ahead with Professional iTunes Capture Methods</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-honor-90-lite-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Honor 90 Lite to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovation-meets-efficiency-top-6-to-do-list-apps-for-win-11/"><u>Innovation Meets Efficiency - Top 6 To-Do List Apps for Win 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-elevated-cpu-consumption-in-god-of-war-a-comprehensive-guide/"><u>Resolving Elevated CPU Consumption in God of War: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrect-dead-headset-on-your-machine-instantly/"><u>Resurrect Dead Headset on Your Machine, Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-trigger-success-in-windows-service-starts/"><u>Strategies to Trigger Success in Windows Service Starts</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-motorola-moto-g-stylus-2023-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-synergy-of-ai-and-windows-software-development/"><u>The Synergy of AI and Windows Software Development</u></a></li>
</ul></div>

