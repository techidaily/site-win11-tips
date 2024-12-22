---
title: Enabling/Disabling TPM Support in VirtualBox 7.0
date: 2024-12-16T22:59:38.450Z
updated: 2024-12-21T18:05:49.487Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-http.techidaily.com/new-exploring-best-stream-software-is-xsplit-outshining-obs-for-2024/"><u>[New] Exploring Best Stream Software - Is XSplit Outshining OBS for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-wirecast-critique-and-comparisons/"><u>[New] WireCast Critique & Comparisons</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-meme-design-excellence-guide/"><u>[Updated] In 2024, Meme Design Excellence Guide</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-the-future-of-presentations-text-conversion-powered-by-speech/"><u>[Updated] The Future of Presentations Text Conversion Powered by Speech</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-thorough-breakdown-the-dji-inspire-1-features/"><u>2024 Approved Thorough Breakdown The DJI Inspire 1 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-common-issues-with-steam-installation-windows-11/"><u>Combatting Common Issues with Steam Installation, Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-fixes-for-pdhdll-errors-and-disappearances/"><u>Comprehensive Fixes for Pdh.dll Errors and Disappearances</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-sid-sequences-in-windows-11-environments/"><u>Deciphering SID Sequences in Windows 11 Environments</u></a></li>
<li><a href="https://win-superb.techidaily.com/effizient-upload-von-iphono-fotos-zu-google-photos-professionelle-tipps/"><u>Effizient Upload Von iPhono-Fotos Zu Google Photos - Professionelle Tipps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-system-image-error-x80780119-in-windows/"><u>Eradicating System Image Error X80780119 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reclaiming-achievement-status-on-steam-games/"><u>Guide to Reclaiming Achievement Status on Steam Games</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-a-lost-apple-iphone-15-pro-max-for-free-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track a Lost Apple iPhone 15 Pro Max for Free? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-spark-20-pro-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Spark 20 Pro Phone FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-bloatware-12-unneeded-windows-apps-you-should-uninstall/"><u>Slash Bloatware: 12 Unneeded Windows Apps You Should Uninstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-conversational-features-in-win11/"><u>Stop Conversational Features in Win11</u></a></li>
<li><a href="https://win-hacks.techidaily.com/troubleshooting-scanner-error-messages-insights-from-yl-computings-experts/"><u>Troubleshooting Scanner Error Messages: Insights From YL Computing's Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-organization-best-windows-to-dos-compared/"><u>Unleashing Organization: Best Windows To-Dos Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/when-and-why-to-ditch-your-onboard-gpu/"><u>When and Why to Ditch Your Onboard GPU</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-easy-route-to-screen-grabber-tool/"><u>Windows 11'S Easy Route to Screen Grabber Tool</u></a></li>
</ul></div>

