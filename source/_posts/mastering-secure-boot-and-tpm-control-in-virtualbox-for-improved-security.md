---
title: Mastering Secure Boot and TPM Control in VirtualBox for Improved Security
date: 2024-11-15T17:32:23.584Z
updated: 2024-11-17T18:47:02.320Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087485/7443" target="_top" id="2087485">
  <img src="//a.impactradius-go.com/display-ad/7443-2087485" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087485/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-prime-software-for-professional-4k-screen-capture/"><u>[New] 2024 Approved Prime Software for Professional 4K Screen Capture</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-top-10-road-racers-playlist/"><u>[New] Top 10 Road Racers Playlist</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-top-social-shackles-hilarious-fb-incarceration-moments-for-cheer/"><u>[New] Top Social Shackles Hilarious FB Incarceration Moments for Cheer</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/avanddvd/"><u>AVコピーガード解析&解除法：アダルト動画DVDに役立つテクニック集</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-samsung-galaxy-s21-fe-5g-2023-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to Samsung Galaxy S21 FE 5G (2023) Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-oppo-a79-5g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Oppo A79 5G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-quick-capture-deep-insight-time-lapse-techniques-for-samsung-users/"><u>In 2024, Quick Capture, Deep Insight Time-Lapse Techniques for Samsung Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/key-picks-the-best-6-online-communities-for-enterprise-expansion-for-2024/"><u>Key Picks The Best 6 Online Communities for Enterprise Expansion for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-metric-tracking-on-windows-11-wifi/"><u>Managing Metric Tracking on Windows 11 Wifi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-system-leading-winners-winning/"><u>Optimize Your System: Leading Winners, Winning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/presents-for-the-holidays-windows-apps-from-ms-store/"><u>Presents for the Holidays: Windows Apps From MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establish-smooth-operations-in-windows-controls/"><u>Re-Establish Smooth Operations in Windows Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-non-existent-device-error-in-windows-11/"><u>Solving Non-Existent Device Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-improve-win-11s-virtual-memory/"><u>Tips to Improve Win 11'S Virtual Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-microsoft-windows-11-for-child-safety/"><u>Utilizing Microsoft Windows 11 for Child Safety</u></a></li>
</ul></div>

