---
title: Navigating Upgrades Safely with TPM and Secure Boot Enablement
date: 2024-07-12T16:54:24.989Z
updated: 2024-07-13T16:54:24.989Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Upgrades Safely with TPM and Secure Boot Enablement
excerpt: This Article Describes Navigating Upgrades Safely with TPM and Secure Boot Enablement
keywords: Safe TPM Use,TPM Security,Secure Boot Guide,TPM Compliance,Upgrade Securely,Booting Safely,TPM+SecureBoot
thumbnail: https://thmb.techidaily.com/86eaf732ac0282547acec52c64c3976ebfde5c25b2b266f861ae95d9b96270a9.jpg
---

## Navigating Upgrades Safely with TPM and Secure Boot Enablement

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

### How to Enable TPM in Your BIOS/UEFI

 The location of the TPM settings in your BIOS will differ depending on your motherboard manufacturer. The following images are taken from an X570 MSI motherboard, though where you find the TPM option won't necessarily be similar.

![msi motherboard enable tpm settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/msi-motherboard-enable-tpm-settings.jpg)

 Be aware that the TPM might be listed under a different name on some motherboards, depending on your CPU manufacturer:

* Intel Platform Trust Technology (PTT)
* AMD fTMP

 On my motherboard, TPM options are found at **Settings > Security > Trusted Computing > TPM Device Selection**, where I'll switch on AMD fTMP.

 Once switched on, you can save the settings and return to Windows 10\. Once Windows boots, you can check your TPM status within the OS to ensure it's running properly.

 Press **Windows key + R** to open the Run dialog, then input **tpm.msc** and press Enter. The TPM management console will load, indicating if TPM is enabled—and if so, which version you're using.

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
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-xiaomi-redmi-12-5g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Xiaomi Redmi 12 5G Without PUK Codes</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-windows-11s-update-0x800f0922-failure/"><u>Steps to Fix Windows 11'S Update 0X800F0922 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-sound-system-malfunctions/"><u>Tackling Windows Sound System Malfunctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-interface-quick-menu-install/"><u>Enhancing Windows Interface: Quick Menu Install</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-playbook-for-parallel-pursuit-of-youtube-videos/"><u>[New] The Playbook for Parallel Pursuit of Youtube Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-step-by-step-guide-adding-subs-to-igtv/"><u>[New] 2024 Approved  Step-by-Step Guide  Adding Subs to IGTV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-skills-quickly-winning-techniques-from-windows-experts/"><u>Sharpen Skills Quickly: Winning Techniques From Windows Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-print-management-service-absence-in-windows/"><u>Steps to Resolve 'Print Management' Service Absence in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-cure-the-msconfig-missing-gpeditmsc-bug/"><u>Solutions to Cure the Msconfig Missing Gpedit.msc Bug</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fusion-of-youtube-beats-and-imovie-editing-magic/"><u>[New] 2024 Approved  Fusion of YouTube Beats and iMovie Editing Magic</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-easysnap-win11-no-hassle-just-screenshots-for-2024/"><u>[New] EasySnap Win11  No Hassle, Just Screenshots for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-restoring-saved-settings-in-nvidia-gui-on-win11/"><u>Solutions for Restoring Saved Settings in Nvidia GUI on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-adding-emoji-15-to-win11-setup/"><u>Navigate with Style: Adding Emoji 15 to Win11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-address-translation-win1110-edition-explained/"><u>Navigating Network Address Translation: Win11/10 Edition Explained</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ring-outro-techniques-for-videos/"><u>Mastering Outro Techniques for Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-updating-windows-in-isolation/"><u>The Art of Updating Windows in Isolation</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-canon-video-editing-made-easy-a-beginners-guide-to-professional-results/"><u>New In 2024, Canon Video Editing Made Easy A Beginners Guide to Professional Results</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-messages-files-on-samsung-by-fonelab-android-recover-messages/"><u>Complete guide for recovering messages files on Samsung</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-files-essential-pitfalls-prevention-in-windows-11/"><u>Navigating Files: Essential Pitfalls Prevention in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-frostbite-finishes-olympic-ice-classics/"><u>[New] Frostbite Finishes  Olympic Ice Classics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-through-efficiency-top-7-strategies-with-windows-11-39/"><u>Skyrocketing Through Efficiency: Top 7 Strategies with Windows 11 (39)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-absence-of-critical-dll-mfc71u-on-pc/"><u>Resolving Absence of Critical DLL: Mfc71u on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-controller-reviving-it-from-steams-oblivion/"><u>Master the Controller: Reviving It From Steam's Oblivion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unchangeable-power-configurations-in-windows-11/"><u>Overcoming Unchangeable Power Configurations in Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-absolute-zero-to-audience-peaks-top-10-insights-on-boosting-video-viewership/"><u>[Updated] In 2024, From Absolute Zero to Audience Peaks  Top 10 Insights on Boosting Video Viewership</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/strategies-to-become-a-top-notch-interviewer/"><u>Strategies to Become a Top-Notch Interviewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productivity-hack-instant-open-of-windows-sticky-notes-on-login/"><u>Productivity Hack: Instant Open of Windows' Sticky Notes on Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-format-missing-error-on-pc-windows/"><u>Overcoming 'Format Missing' Error on PC Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-terminal-settings-on-windows-pc/"><u>Optimizing Terminal Settings on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revert-windows-settings-after-restart/"><u>Methods to Revert Windows Settings After Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-enable-and-customize-widgets-on-win11/"><u>Easy Steps: Enable and Customize Widgets on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-frozen-lock-screen-timing-windows/"><u>Overcoming Frozen Lock Screen Timing Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/demystifying-profile-naming-and-username-systems/"><u>Demystifying Profile Naming and Username Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-manage-your-windows-11-administrative-credentials/"><u>Efficiently Manage Your Windows 11 Administrative Credentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screenscape-symphony-composing-personalized-displays-in-windows-1011/"><u>Screenscape Symphony: Composing Personalized Displays in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-to-revive-windows-desktop-icons/"><u>Efficient Methods to Revive Windows Desktop Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unbootable-windows-vms-via-vmware-in-win11/"><u>Eliminating Unbootable Windows VMs via VMware in Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-news-narratives-concluding-flourishes/"><u>2024 Approved  News Narratives' Concluding Flourishes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/still-using-pattern-locks-with-vivo-y100t-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Vivo Y100t? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-standard-to-special-a-guide-to-the-best-custom-box-stores-on-the-internet/"><u>[Updated] From Standard to Special  A Guide to the Best Custom Box Stores on the Internet</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mastering-youtube-a-guide-for-gamers-live-broadcasts/"><u>2024 Approved  Mastering YouTube  A Guide for Gamers' Live Broadcasts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-code-0x0000004e-problem/"><u>Overcoming Windows 11'S Code 0X0000004E Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-shopping-experience-fixing-error-0x80072f30/"><u>Streamlining Your Shopping Experience: Fixing Error 0X80072F30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-overheat-in-laptops-with-intensive-play/"><u>Preventing Overheat in Laptops with Intensive Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-window-11-style-hacks-and-themes/"><u>Exclusive Window 11 Style Hacks & Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-editing-the-windows-registry-via-terminal/"><u>Essential Tips for Editing the Windows Registry via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-a-lasting-deletion-toolbar-on-windows-systems/"><u>Personalizing a Lasting Deletion Toolbar on Windows Systems</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oneplus-12-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your OnePlus 12</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-how-to-log-your-favorites-6-proven-methods-for-webcast-capture/"><u>[Updated] 2024 Approved  How to Log Your Favorites  6 Proven Methods for Webcast Capture</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-guide-to-enhancing-reels-with-harmonious-tunes/"><u>The Ultimate Guide to Enhancing Reels with Harmonious Tunes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-launch-chrome-in-your-newest-windows-11-pc/"><u>How to Launch Chrome in Your Newest Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-mail-alert-failures-with-9-practical-tips-for-windows-users/"><u>Fixing Mail Alert Failures with 9 Practical Tips for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-steam-file-sync-failures-in-windows/"><u>Methods to Prevent Steam File Sync Failures in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-roblox-system-crashes/"><u>Steps to Rectify Roblox System Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-into-the-world-of-windows-11-home/"><u>Step Into the World of Windows 11 Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-experience-fixes-for-elusive-optional-components/"><u>Revamp Your Windows Experience: Fixes for Elusive Optional Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-event-viewer-usability/"><u>Restoring Windows Event Viewer Usability</u></a></li>
</ul></div>
