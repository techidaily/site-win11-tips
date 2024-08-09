---
title: Security First in Upgrade to Windows 11
date: 2024-08-08T11:12:15.342Z
updated: 2024-08-09T11:12:15.342Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Security First in Upgrade to Windows 11
excerpt: This Article Describes Security First in Upgrade to Windows 11
keywords: Windows 11 Security Update,Prioritize Security with Win11,Secure Win11 Installation,Upgrading Safe,Secure OS Transition,Enhance Security in Win11,Secure Windows 11 Upgrade
thumbnail: https://thmb.techidaily.com/6de10ca092ea22440e0ee57b0e4d9c17ed8937d0ae7586606e65eab4d9ad7104.jpg
---

## Security First in Upgrade to Windows 11

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

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Are Secure Boot and TPM?

 The [Trusted Module Platform (TPM) is a hardware-level security solution](http://www.makeuseof.com/what-is-a-trusted-platform-module-tpm/) that protects your data from hacking and other data breaches. The TPM holds unique encryption keys stored in such a way that it is nearly impossible for a hacker to access. If someone breaches your computer and your data is encrypted, it will remain secure.

 Microsoft's recommended requirements for Windows 11 list TMP 2.0\. However, you can still upgrade using a previous version, TPM 1.2, which is the minimum requirement.

 Along with TPM 2.0, Microsoft also requires you to activate Secure Boot, a UEFI-level security setting that stops any unauthorized operating system from booting up. Secure Boot is effectively a gatekeeper, stopping malicious code from booting up before your system, and its primary goal is to protect against rootkits, bootkits, and other malicious code.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
![windows bios secure boot warning](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/windows-bios-secure-boot-warning.jpg)

 But it also has some side effects. For example, Secure Boot will stop you from dual-booting Linux distributions, which has led many [users to disable Secure Boot.](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/)

 On top of those two vital features, [Windows 11 has specific hardware requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/), with Microsoft opting to block the automatic upgrade path for millions of users. If you're using Windows 10 on an AMD Ryzen 3000 series or later or an Intel 7th Gen CPU or later, you can upgrade to Windows 11 directly.

 However, if not, you'll have to opt for a [Windows 11 clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) or to [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/). A clean installation of Windows 11 will work on most hardware, but it does come with caveats. Notably, Microsoft has repeatedly stated that it will not provide updates to Windows 11 installations on "unsupported" hardware, so you install at your own risk.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## How to Enable TPM and Secure Boot

 Trusted Module Platform and Secure Boot are found in your UEFI settings. You'll have to enter system UEFI to enable them before attempting to upgrade to Windows 11\. Both settings are found in similar areas, but we'll break the steps down into three parts for ease of reading.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Enter Your BIOS/UEFI

 There are a couple of ways to enter your system BIOS/UEFI. The old tried and tested method of [tapping a keyboard key during bootup](https://www.makeuseof.com/tag/enter-bios-computer/) still works, but you might not get the chance if you have fast boot enabled. If the boot screens whizz past and you end up in Windows 10, there is another way you can access the BIOS:

1. Head to **Settings > Update & Security > Recovery > Restart now**.
2. When your computer restarts, you'll see a big blue screen with several options. Select **Troubleshoot > Advanced Options > UEFI Firmware Settings > Restart**.

 You should be in your BIOS/UEFI settings menu when the computer restarts again.

### How to Enable TPM in Your BIOS/UEFI

 The location of the TPM settings in your BIOS will differ depending on your motherboard manufacturer. The following images are taken from an X570 MSI motherboard, though where you find the TPM option won't necessarily be similar.

![msi motherboard enable tpm settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-tpm-settings.jpg)

 Be aware that the TPM might be listed under a different name on some motherboards, depending on your CPU manufacturer:

* Intel Platform Trust Technology (PTT)
* AMD fTMP

 On my motherboard, TPM options are found at **Settings > Security > Trusted Computing > TPM Device Selection**, where I'll switch on AMD fTMP.

 Once switched on, you can save the settings and return to Windows 10\. Once Windows boots, you can check your TPM status within the OS to ensure it's running properly.

 Press **Windows key + R** to open the Run dialog, then input **tpm.msc** and press Enter. The TPM management console will load, indicating if TPM is enabled—and if so, which version you're using.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
### How to Enable Secure Boot

 While you're deep in your system settings, take a moment to check if Secure Boot is enabled.

 Like the TPM options, where you find the Secure Boot option will differ depending on hardware, but it is generally located in the **Boot** tab. Find your **Boot** tab, scroll down to find the **Secure Boot** option, and ensure it's enabled.

![msi motherboard enable secure boot settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-secure-boot-settings.jpg)

 Note that Secure Boot requires your drives to use GUID Partition Table (GPT) rather than the older master boot record (MBR). As the newer partition table, GPT comes with several enhancements over MBR. If Secure Boot doesn't enable, you may need to [convert your MBR drive to GPT](http://www.makeuseof.com/tag/convert-mbr-gpt-windows/).

 Alternatively, your computer or hardware may be too old to enable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## Use Microsoft's PC Health Check App to Check If Your Hardware Is Compatible

 Microsoft recommends using its [PC Health Check App](https://www.microsoft.com/en-us/windows/windows-11?r=1), which you'll find at the bottom of the linked page, to check for hardware compatibility. Download and fire it up to check your system's compatibility with Windows 11\.

 Alternatively, you could check out [WhyNotWin11](https://github.com/rcmaehl/WhyNotWin11/releases/), an open-source alternative that may provide more detailed insight into your Windows 11 compatibility.

 So there you have it. You've enabled two of the most important settings that will block your Windows 11 upgrade path. Once enabled, and presuming you're running compatible hardware, Microsoft will offer you the Windows 11 upgrade. To check if your Windows 11 upgrade is ready, head to **Settings > Update & Security > Windows Update**, where you'll find the big update button.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-seamless-tweet-to-facebook-video-transfers-users/"><u>[New] 2024 Approved  Seamless Tweet-to-Facebook Video Transfers Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-perfecting-sims-4-live-action-for-videographers/"><u>[New] Perfecting Sims 4 Live Action for Videographers</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-securing-top-quality-pixel-ringtones-where-to-go/"><u>[New] Securing Top Quality Pixel Ringtones  Where to Go?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-transforming-challenges-into-triumphs-with-these-30-tips/"><u>[New] Transforming Challenges Into Triumphs with These 30 Tips</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-gopro-hero-series-clash-with-polaroid-cube-which-wins-for-2024/"><u>[Updated] GoPro Hero Series Clash with Polaroid Cube  Which Wins for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-steps-for-efficient-access-to-windows-connections-tool/"><u>10 Key Steps for Efficient Access to Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-methods-to-resuscitate-windows-system-backup/"><u>13 Methods to Resuscitate Windows System Backup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-steps-for-dealing-with-windows-http-error-0x80860010/"><u>7 Essential Steps for Dealing with Windows' HTTP Error 0X80860010</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-open-the-print-management-tool-in-windows-11/"><u>9 Ways to Open the Print Management Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-beginners-path-to-implementing-hyper-v-on-win-11-homes/"><u>A Beginner's Path to Implementing Hyper-V on Win 11 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-method-for-clean-booting-on-windows-11-systems/"><u>A Step-by-Step Method for Clean Booting on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-excessive-tiworkerexe-cpu-usage-issue/"><u>Addressing Excessive TiWorker.exe CPU Usage Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx9-point-on-windows-11/"><u>Addressing Missing D3DX9 Point on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-cloud-errors-on-windows/"><u>Addressing Steam Cloud Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-hang-issue-dxgierrordevicehunk-on-windows/"><u>Addressing the Hang Issue: DXGI_ERROR_DEVICE_HUNK on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-mouse-accessibility-in-windows-11-with-ease/"><u>Adjusting Mouse Accessibility in Windows 11 with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-dynamic-background-anytime/"><u>Adjusting Your Windows Dynamic Background Anytime</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-and-astrology-showdown-how-does-chatgpt-stack-up-against-magazine-horoscopes-for-predictions/"><u>AI and Astrology Showdown: How Does ChatGPT Stack Up Against Magazine Horoscopes for Predictions?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-overview-of-user-dissatisfaction-with-windows-11-upgrade/"><u>An Overview of User Dissatisfaction with Windows 11 Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-strengths-of-win11-in-compare-with-macos/"><u>Analyzing the Strengths of Win11 in Compare with MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approach-to-reveal-hidden-drives-on-windows/"><u>Approach to Reveal Hidden Drives on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-desktop-interactivity-the-widget-approach-in-win-11/"><u>Augmenting Desktop Interactivity: The Widget Approach in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-task-manager-functionality-in-windows-11-with-cli/"><u>Augmenting Task Manager Functionality in Windows 11 with CLI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-editing-setup-office-products-word-for-text-only-opened-attachments/"><u>Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-mistakes-fixing-office-error-0x80041015/"><u>Avoiding Common Mistakes Fixing Office Error 0X80041015</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-visual-clutter-inside-windows-search/"><u>Avoiding Visual Clutter Inside Windows Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-spacious-and-slow-a-bittersweet-blend/"><u>Blackview: Spacious and Slow - A Bittersweet Blend</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-health-through-interactive-device-tracking/"><u>Boost System Health Through Interactive Device Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284325307-chrome-opening-woes-resolved-fast-fixed-for-windows-11-users/"><u>Chrome Opening Woes Resolved: Fast Fixed for Windows 11 Users.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719331271081-dual-virus-scanners-think-twice-windows/"><u>Dual Virus Scanners? Think Twice, Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-oppo-find-x7-ultra-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-your-oneplus-11-5g-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your OnePlus 11 5G Lock Screen Password</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/infuse-harmonies-into-motion-picture-sequences-using-media-encrypter-for-2024/"><u>Infuse Harmonies Into Motion Picture Sequences Using Media Encrypter for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/online-accessory-fb-stories-capture-app/"><u>Online Accessory  Fb Stories Capture App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266840560-prevent-unwanted-updates-on-your-pc-today/"><u>Prevent Unwanted Updates on Your PC Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719310221725-tame-frozen-windows-handbraked-beast/"><u>Tame Frozen Windows-Handbraked Beast!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>