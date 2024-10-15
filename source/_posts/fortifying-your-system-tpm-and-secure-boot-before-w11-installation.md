---
title: "Fortifying Your System: TPM and Secure Boot Before W11 Installation"
date: 2024-10-09T19:43:14.765Z
updated: 2024-10-14T20:05:28.504Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fortifying Your System: TPM and Secure Boot Before W11 Installation"
excerpt: "This Article Describes Fortifying Your System: TPM and Secure Boot Before W11 Installation"
keywords: W11 Security Setup,TPM Use In Windows 11,Secure Boot Essentials,Defending System Integrity,Pre-Install W11 Boosts,Enhancing PC Safety,Windows 11 Protective Steps
thumbnail: https://thmb.techidaily.com/18b7f2a3affa298abd49de738912f69fd84b1ae730be3c4356f4b4963bc95eed.jpg
---

## Fortifying Your System: TPM and Secure Boot Before W11 Installation

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [What Are Secure Boot and TPM?](#what-are-secure-boot-and-tpm)
* [How to Enable TPM and Secure Boot](#how-to-enable-tpm-and-secure-boot)
* [Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible](#use-microsoft-39-s-pc-health-check-app-to-check-if-your-hardware-is-compatible)

### Key Takeaways

* Windows 11 requires specific hardware, including AMD Ryzen 3000 series or Intel 7th Gen CPU or better, TPM, and Secure Boot.
* TPM is a hardware-level security solution that protects data from hacking, while Secure Boot prevents unauthorized operating systems from booting up.
* You can enable TPM and Secure Boot in your BIOS/UEFI settings, but be aware that Secure Boot may prevent dual-booting and updates on unsupported hardware.

 Considering upgrading to Windows 11? There are a couple of requirements that might stop you in your tracks. We'll explain how to know if your hardware will pass Windows 11's checks.

 First up is your physical hardware. If you're not using an AMD Ryzen 3000 series or Intel 7th Gen CPU or better, neither a clean Windows 11 installation nor the Windows 10 upgrade path will work. Second, if your computer doesn't support Secure Boot and TPM, you'll also fall at the initial hurdle. However, all is not lost because you can switch on Secure Boot and TPM from your BIOS/UEFI menu.

## What Are Secure Boot and TPM?

 The [Trusted Module Platform (TPM) is a hardware-level security solution](http://www.makeuseof.com/what-is-a-trusted-platform-module-tpm/) that protects your data from hacking and other data breaches. The TPM holds unique encryption keys stored in such a way that it is nearly impossible for a hacker to access. If someone breaches your computer and your data is encrypted, it will remain secure.

 Microsoft's recommended requirements for Windows 11 list TMP 2.0\. However, you can still upgrade using a previous version, TPM 1.2, which is the minimum requirement.

 Along with TPM 2.0, Microsoft also requires you to activate Secure Boot, a UEFI-level security setting that stops any unauthorized operating system from booting up. Secure Boot is effectively a gatekeeper, stopping malicious code from booting up before your system, and its primary goal is to protect against rootkits, bootkits, and other malicious code.

![windows bios secure boot warning](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/windows-bios-secure-boot-warning.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 But it also has some side effects. For example, Secure Boot will stop you from dual-booting Linux distributions, which has led many [users to disable Secure Boot.](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/)

 On top of those two vital features, [Windows 11 has specific hardware requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/), with Microsoft opting to block the automatic upgrade path for millions of users. If you're using Windows 10 on an AMD Ryzen 3000 series or later or an Intel 7th Gen CPU or later, you can upgrade to Windows 11 directly.

 However, if not, you'll have to opt for a [Windows 11 clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) or to [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/). A clean installation of Windows 11 will work on most hardware, but it does come with caveats. Notably, Microsoft has repeatedly stated that it will not provide updates to Windows 11 installations on "unsupported" hardware, so you install at your own risk.

## How to Enable TPM and Secure Boot

 Trusted Module Platform and Secure Boot are found in your UEFI settings. You'll have to enter system UEFI to enable them before attempting to upgrade to Windows 11\. Both settings are found in similar areas, but we'll break the steps down into three parts for ease of reading.

### How to Enter Your BIOS/UEFI

 There are a couple of ways to enter your system BIOS/UEFI. The old tried and tested method of [tapping a keyboard key during bootup](https://www.makeuseof.com/tag/enter-bios-computer/) still works, but you might not get the chance if you have fast boot enabled. If the boot screens whizz past and you end up in Windows 10, there is another way you can access the BIOS:

1. Head to **Settings > Update & Security > Recovery > Restart now**.
2. When your computer restarts, you'll see a big blue screen with several options. Select **Troubleshoot > Advanced Options > UEFI Firmware Settings > Restart**.

 You should be in your BIOS/UEFI settings menu when the computer restarts again.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Enable TPM in Your BIOS/UEFI

 The location of the TPM settings in your BIOS will differ depending on your motherboard manufacturer. The following images are taken from an X570 MSI motherboard, though where you find the TPM option won't necessarily be similar.

![msi motherboard enable tpm settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-tpm-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Be aware that the TPM might be listed under a different name on some motherboards, depending on your CPU manufacturer:

* Intel Platform Trust Technology (PTT)
* AMD fTMP

 On my motherboard, TPM options are found at **Settings > Security > Trusted Computing > TPM Device Selection**, where I'll switch on AMD fTMP.

 Once switched on, you can save the settings and return to Windows 10\. Once Windows boots, you can check your TPM status within the OS to ensure it's running properly.

 Press **Windows key + R** to open the Run dialog, then input **tpm.msc** and press Enter. The TPM management console will load, indicating if TPM is enabled—and if so, which version you're using.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Enable Secure Boot

 While you're deep in your system settings, take a moment to check if Secure Boot is enabled.

 Like the TPM options, where you find the Secure Boot option will differ depending on hardware, but it is generally located in the **Boot** tab. Find your **Boot** tab, scroll down to find the **Secure Boot** option, and ensure it's enabled.

![msi motherboard enable secure boot settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-secure-boot-settings.jpg)

 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

## Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible

 Microsoft recommends using its [PC Health Check App](https://www.microsoft.com/en-us/windows/windows-11?r=1), which you'll find at the bottom of the linked page, to check for hardware compatibility. Download and fire it up to check your system's compatibility with Windows 11\.

 Alternatively, you could check out [WhyNotWin11](https://github.com/rcmaehl/WhyNotWin11/releases/), an open-source alternative that may provide more detailed insight into your Windows 11 compatibility.

 So there you have it. You've enabled two of the most important settings that will block your Windows 11 upgrade path. Once enabled, and presuming you're running compatible hardware, Microsoft will offer you the Windows 11 upgrade. To check if your Windows 11 upgrade is ready, head to **Settings > Update & Security > Windows Update**, where you'll find the big update button.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-compreehing-and-engaging-with-your-twitter-archive/"><u>[New] In 2024, Compreehing & Engaging with Your Twitter Archive</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-fast-fixes-effortless-screenshots-and-captures-with-dell-for-2024/"><u>[Updated] Fast Fixes Effortless Screenshots & Captures with Dell for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/boost-performance-and-features-from-win11-home-to-pro/"><u>Boost Performance & Features: From Win11 Home to Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-shift-your-video-format-from-mkv-to-mp4-windows/"><u>Efficiently Shift Your Video Format: From MKV to MP4 (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-visuals-and-speed-on-roblox-windows-app/"><u>Enhancing Visuals and Speed on Roblox Windows App</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-demystifying-best-hdr-cameras-for-professionals/"><u>In 2024, Demystifying Best HDR Cameras for Professionals</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Oppo A78 5G? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-lock-your-honor-magic5-ultimate-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Honor Magic5 Ultimate Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-code-0xa00f425d-in-microsofts-windows-camera-app/"><u>Overcoming Error Code: 0XA00F425D in Microsoft's Windows Camera App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-upgrade-error-0xc004f050/"><u>Overcoming Windows Upgrade Error: 0XC004F050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-error-e8024002e-in-updates-process/"><u>Prevent Error E:8024002E in Updates Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-elusive-error-0x80073d26-on-windows/"><u>Resolving the Elusive Error 0X80073D26 on Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/top-strategies-for-capturing-lol-matches/"><u>Top Strategies for Capturing LOL Matches</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-on-iphone-14-pro-max-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server On iPhone 14 Pro Max</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-red-magic-8s-proplus-by-fonelab-android-recover-music/"><u>Undelete lost music from Red Magic 8S Pro+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-ai-computers-distinctions-explored/"><u>Unveiling AI Computers: Distinctions Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-where-your-wallpaper-saves-in-pc/"><u>Unveiling Where Your Wallpaper Saves in PC</u></a></li>
</ul></div>

