---
title: Managing Secure Boot Settings for Enhanced Virtual Machine Security
date: 2024-10-07T02:20:20.847Z
updated: 2024-10-09T06:37:14.305Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing Secure Boot Settings for Enhanced Virtual Machine Security
excerpt: This Article Describes Managing Secure Boot Settings for Enhanced Virtual Machine Security
keywords: VM Security Boost,Secure Boot Control,VMM Safety,Boot Mode Lockdown,Encrypted VMs,VM Hardening,TrustZone Management
thumbnail: https://thmb.techidaily.com/c0fe8b6f81af5b05eb5adacea58a29fe6fd2f271b6a687457517f15534dc6b13.jpg
---

## Managing Secure Boot Settings for Enhanced Virtual Machine Security

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
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137972/21526" target="_top" id="2137972">
  <img src="//a.impactradius-go.com/display-ad/21526-2137972" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137972/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-godly-onslaught-ragnaroks-day/"><u>[Updated] In 2024, Godly Onslaught Ragnarok’s Day</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premium-action-recording-in-faceview-option/"><u>[Updated] Premium Action Recording In-Faceview Option</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/1-detallado-analisis-de-caracteristicas-y-capacidades-de-la-inteligencia-artificial-de-winxvideo/"><u>1. Detallado Análisis De Características Y Capacidades De La Inteligencia Artificial De Winxvideo</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-the-world-of-telegram-online-with-ease/"><u>2024 Approved Navigating the World of Telegram Online with Ease</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024s-best-bargains-in-the-world-of-cloud-storage/"><u>2024'S Best Bargains in the World of Cloud Storage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-reasons-why-windows-11-is-better-than-macos/"><u>6 Reasons Why Windows 11 Is Better Than macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-locate-elusive-gpeditmsc-on-pc/"><u>7 Ways to Locate Elusive 'Gpedit.msc' On PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-remedies-to-clear-windows-setup-stuck-on-validation-error/"><u>9 Remedies to Clear Windows Setup Stuck on Validation Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-step-by-step-plan-msoffice-install-on-win11/"><u>A Complete Step-by-Step Plan: MSOffice Install on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-walkthrough-to-unveil-ms-paint-windows-11/"><u>A Quick Walkthrough to Unveil MS Paint, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-screen-separation-issues/"><u>Addressing Windows Screen Separation Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automatic-file-disposal-in-windows-11/"><u>Boost Efficiency with Automatic File Disposal in Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-cod-warzone-glitch-expert-advice-on-overcoming-dev-error-6328/"><u>Fixing Cod Warzone Glitch: Expert Advice on Overcoming Dev Error #6328</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/perfecting-instagram-stories-adding-and-sharing-custom-emojis-for-2024/"><u>Perfecting Instagram Stories Adding & Sharing Custom Emojis for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284654722-software-environment-setup/"><u>Software Environment Setup:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719356387702-stuck-google-chrome-on-win11-try-these-immediate-actions/"><u>Stuck Google Chrome on Win11? Try These Immediate Actions</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unbeatable-deal-alert-grab-the-power-of-rtx-4080-in-lenovo-legion-gaming-laptops-for-750-less-plus-a-240hz-display/"><u>Unbeatable Deal Alert! Grab the Power of RTX 4080 in Lenovo Legion Gaming Laptops for $750 Less – Plus a 240Hz Display!</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-some-outdated-your-hardware-drivers-on-windows-1110-by-drivereasy-guide/"><u>Use Device Manager to identify some outdated your hardware drivers on Windows 11/10</u></a></li>
</ul></div>

