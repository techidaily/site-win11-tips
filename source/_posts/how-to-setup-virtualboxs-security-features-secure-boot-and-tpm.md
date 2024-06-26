---
title: "How to Setup VirtualBox's Security Features: Secure Boot & TPM"
date: 2024-06-25T16:12:13.524Z
updated: 2024-06-26T16:12:13.524Z
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
<li><a href="https://win11-tips.techidaily.com/streamline-your-vids-with-these-8-windows-titles/"><u>Streamline Your Vids with These 8 Windows Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-stuck-warcraft-patches/"><u>Steering Clear of Stuck Warcraft Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-capsules-unlocked-exploring-7-features-from-bygone-windows/"><u>Time Capsules Unlocked: Exploring 7 Features From Bygone Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-windows-defender-shield-unresponsiveness/"><u>Essential Fixes for Windows Defender Shield Unresponsiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-printer-settings-the-easy-way-in-win11-max-50-chars/"><u>Guide to Printer Settings: The Easy Way in Win11 (Max 50 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/space-saving-savvy-master-windows-11s-minimalist-method/"><u>Space-Saving Savvy: Master Windows 11'S Minimalist Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-your-digital-experience-with-active-windows-11-notifications/"><u>Maximizing Your Digital Experience with Active Windows 11 Notifications</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/dynamic-diversity-30plus-fresh-biographical-strategies-to-triple-your-views-following-on-tiktok-filmora-platform-for-2024/"><u>Dynamic Diversity  30+ Fresh Biographical Strategies to Triple Your Views, Following on TikTok-Filmora Platform for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-s24-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy S24 Lock Screen Password?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-xiaomi-13-ultra-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Xiaomi 13 Ultra FRP?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/starting-out-right-budget-friendly-game-editing-software-for-beginners/"><u>Starting Out Right  Budget-Friendly Game Editing Software for Beginners</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-best-gopro-for-action-compare-max-and-hero-11-for-2024/"><u>The Best GoPro for Action  Compare Max and Hero 11 for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevate-your-video-guide-with-annotations-on-youtube-for-2024/"><u>[Updated] Elevate Your Video Guide with Annotations on YouTube for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-ultimate-toolkit-for-top-notch-tiktok-cuts/"><u>[Updated] 2024 Approved  Ultimate Toolkit for Top-Notch TikTok Cuts</u></a></li>
</ul></div>
