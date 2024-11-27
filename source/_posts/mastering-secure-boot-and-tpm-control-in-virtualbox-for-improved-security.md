---
title: Mastering Secure Boot and TPM Control in VirtualBox for Improved Security
date: 2024-11-21T16:27:46.257Z
updated: 2024-11-27T17:02:26.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Secure Boot and TPM Control in VirtualBox for Improved Security
excerpt: This Article Describes Mastering Secure Boot and TPM Control in VirtualBox for Improved Security
keywords: Secure Boot VirtualBox,TPM Management VirtualBox,Boost VM Security,Enhance VM Protection,VirtualSecure Boot Control,TPM Virtualization,Improve VM Safety Measures
thumbnail: https://thmb.techidaily.com/3331b68243bf9259740fc95d1a73b2453b86dd532a7a2ec26036834e7833dd28.jpg
---

## Mastering Secure Boot and TPM Control in VirtualBox for Improved Security

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-decoding-youtubes-top-mp3-conversion-apps/"><u>[Updated] 2024 Approved Decoding YouTube's Top MP3 Conversion Apps</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-dissecting-hero5-camera-footage/"><u>[Updated] 2024 Approved Dissecting Hero5 Camera Footage</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-nailing-the-perfect-gameplay-with-fbx-for-2024/"><u>[Updated] Nailing the Perfect Gameplay with FBX for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/break-through-windows-barriers-be-an-admin-now/"><u>Break Through Windows Barriers - Be an Admin Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-faulty-tackling-corrupt-win1011-recycle-bin/"><u>Fixing the Faulty: Tackling Corrupt WIN10/11 Recycle Bin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-rid-of-silence-in-google-meet-chat/"><u>How to Get Rid of Silence in Google Meet Chat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-speech-recognition-on-microsofts-latest-os/"><u>How to Reactivate Speech Recognition on Microsoft's Latest OS</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-itel-p40-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Itel P40 Phone Pattern Lock</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-budget-friendly-high-definition-action-cams/"><u>In 2024, Ultimate Budget-Friendly High Definition Action Cams</u></a></li>
<li><a href="https://driver-download.techidaily.com/latest-canon-mx490-printing-software-for-windows-operating-systems/"><u>Latest Canon MX490 Printing Software for Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-errors-related-to-incorrect-system-tokens/"><u>Mitigating Errors Related to Incorrect System Tokens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-failed-windows-discord-update-seamlessly/"><u>Navigating a Failed Windows Discord Update Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-update-hiccup-x712/"><u>Overcoming Windows Update Hiccup X712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-fixing-a-stalled-resource-monitor-on-windows-11/"><u>Regaining Control: Fixing a Stalled Resource Monitor on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-incorrect-file-history-configurations/"><u>Resolving Windows Error: Incorrect File History Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-connectivity-how-to-fix-network-errors-in-windows-11/"><u>Seamless Connectivity: How to Fix Network Errors in Windows 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ess-screen-stretch-cycle-youtube-on-television-display-for-2024/"><u>Seamless Screen Stretch Cycle YouTube on Television Display for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-guide-to-correcting-image-persistence-on-screens-of-all-types/"><u>The Ultimate Guide to Correcting Image Persistence on Screens of All Types</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unlocking-potential-an-in-depth-look-at-the-open-source-capabilities-of-the-linksys-wrt1900ac-wi-fi-router/"><u>Unlocking Potential: An In-Depth Look at the Open Source Capabilities of the Linksys WRT1900AC Wi-Fi Router</u></a></li>
</ul></div>

