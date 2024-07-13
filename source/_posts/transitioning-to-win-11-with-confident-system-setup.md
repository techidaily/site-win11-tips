---
title: Transitioning to Win 11 with Confident System Setup
date: 2024-07-12T16:30:58.653Z
updated: 2024-07-13T16:30:58.653Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transitioning to Win 11 with Confident System Setup
excerpt: This Article Describes Transitioning to Win 11 with Confident System Setup
keywords: Win 11 Transition,System Upgrade Plan,Secure Win 11 Install,Win 11 Configuration,Advanced OS Shift,Win 11 Setup Guide,Stable Win 11 Launch
thumbnail: https://thmb.techidaily.com/a6232b975632e43de71e5ab6217eebf552fc531569d56d79c1b10e2acedb4321.png
---

## Transitioning to Win 11 with Confident System Setup

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
<li><a href="https://win11-tips.techidaily.com/winning-valorant-on-pc-overcoming-frames-drops/"><u>Winning Valorant on PC: Overcoming Frames Drops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-ensure-complete-ram-usage-by-windows-os/"><u>Strategies to Ensure Complete RAM Usage by Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-wild-high-on-your-windows-desktop/"><u>Taming the Wild High on Your Windows Desktop</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-exploring-vlogging-selecting-the-best-cameras-and-lenses-for-2024/"><u>[New] Exploring Vlogging  Selecting the Best Cameras & Lenses for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-instagram-experience-adding-vimeo-videos-for-2024/"><u>[Updated] The Instagram Experience  Adding Vimeo Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-reversing-frozen-dark-theme-on-computers/"><u>A Guide to Reversing Frozen Dark Theme on Computers</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-how-to-master-real-time-video-sharing-on-facebook/"><u>[New] In 2024, How to Master Real-Time Video Sharing on Facebook</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/revolutionizing-channel-presence-the-secret-of-higher-subscriber-numbers/"><u>Revolutionizing Channel Presence  The Secret of Higher Subscriber Numbers</u></a></li>
<li><a href="https://extra-information.techidaily.com/brighten-your-surroundings-with-21plus-collage-wonders/"><u>Brighten Your Surroundings with 21+ Collage Wonders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-windows-safe-mode-limitation-on-office-suite/"><u>Resolving the Windows-Safe Mode Limitation on Office Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-pace-in-windows-11-overcome-keyboard-latency/"><u>Boost Your Typing Pace in Windows 11: Overcome Keyboard Latency</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-streamline-your-content-posting-twitter-videos-on-snapchat/"><u>In 2024, Streamline Your Content  Posting Twitter Videos on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vac-denied-access-in-steam-windows/"><u>Troubleshooting VAC Denied Access in Steam Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-motorola-moto-g04-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Motorola Moto G04 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-reactivate-an-inactive-hotspot-in-windows-11/"><u>Guidelines to Reactivate an Inactive Hotspot in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/common-windows-11-22h2-issues-and-their-fixes/"><u>Common Windows 11 22H2 Issues and Their Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secure-boot-a-comprehensive-guide-using-rufus-on-win11/"><u>Unlocking Secure Boot: A Comprehensive Guide Using Rufus on Win11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-mastering-mobile-screen-recording-in-snapchat-for-2024/"><u>[New] Mastering Mobile  Screen Recording in Snapchat for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-freezing-your-window-windows-screenshoting-guide/"><u>[Updated] 2024 Approved  Freezing Your Window  Windows Screenshoting Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-3-ways-to-unlock-your-apple-iphone-13-for-free-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock Your Apple iPhone 13 for Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-persistent-issues-windows-obs-not-opening-troubleshooting/"><u>Tackling Persistent Issues: Windows OBS Not Opening Troubleshooting</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-easily-obtain-unique-epilogue-audio-files-online/"><u>2024 Approved  Easily Obtain Unique Epilogue Audio Files Online</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-androids-ultimate-sky-archive-sentries-2-written-by-a-user-not-an-ai-model/"><u>In 2024, Android's Ultimate Sky Archive Sentries (2 Written by a User, Not an AI Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-inactive-printer-on-pcs/"><u>Winning Back Your Inactive Printer on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-intel-unison-for-convenient-windows-11-calls/"><u>Making the Most of Intel Unison for Convenient Windows 11 Calls</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/keyframes-interval-everything-you-need-to-know-for-2024/"><u>Keyframes Interval Everything You Need To Know for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-gaming-voice-alteration-techniques-selecting-the-optimal-solution/"><u>New In 2024, Gaming Voice Alteration Techniques Selecting the Optimal Solution</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-reaper-experience-features-applications-and-step-by-step-tutorial-guides/"><u>New The Reaper Experience Features, Applications, and Step-by-Step Tutorial Guides</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-security-with-new-passwords-in-win-11/"><u>Streamline Security with New Passwords in Win 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-create-stunning-intros-top-10-websites-with-free-and-paid-options/"><u>2024 Approved Create Stunning Intros Top 10 Websites with Free and Paid Options</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Oppo K11 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-snip-tool-text-edits-on-win-11/"><u>Perfecting Snip Tool Text Edits on Win 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ow-to-seamlessly-incorporate-video-game-banners-for-2024/"><u>[New] How to Seamlessly Incorporate Video Game Banners for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-device-opens-issue-on-audacity-in-windows/"><u>Steps to Correct Device Opens Issue on Audacity in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-muted-slack-notifications-on-windows-11/"><u>Addressing Muted Slack Notifications on Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-15-top-video-to-gif-app-on-iphone-and-android/"><u>In 2024, 15 Top Video to GIF App on iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-techniques-transform-mkv-videos-into-windows-mp4-files/"><u>Simple Techniques: Transform MKV Videos Into Windows MP4 Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-keyboard-confusion-30-ways-to-fix/"><u>No More Keyboard Confusion: 30 Ways to Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-lock-pattern-creation-guide-for-windows-11-pcs/"><u>Personalized Lock Pattern Creation Guide for Windows 11 PCs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/converting-your-clips-into-perfect-instagram-stories/"><u>Converting Your Clips Into Perfect Instagram Stories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-control-of-security-answers-in-windows-11-local-account/"><u>Taking Control of Security Answers in Windows 11 Local Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-chrome-induced-system-time-missteps-windows/"><u>Rectifying Chrome-Induced System Time Missteps (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modern-standby-anomalies-in-the-windows-ecosystem/"><u>Modern Standby Anomalies in the Windows Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-teamsters-downtime-on-windows-11-10/"><u>Troubleshooting Teamsters Downtime on Windows 11, 10</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-say-goodbye-to-physical-media-converting-dvds-to-digital-files-for-2024/"><u>New Say Goodbye to Physical Media Converting DVDs to Digital Files for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-top-video-to-audio-converters-for-mobile-devices-for-2024/"><u>Updated Top Video to Audio Converters for Mobile Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-your-spoken-words-into-written-sense-using-whisper/"><u>Turn Your Spoken Words Into Written Sense Using Whisper</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-capturing-attention-from-content-creation-to-commerce-for-2024/"><u>[Updated] Capturing Attention  From Content Creation to Commerce for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-disabling-discords-auto-checkup-at-startup/"><u>Strategies for Disabling Discord's Auto-Checkup at Startup</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-pathway-to-profit-via-youtubes-cp2024-program/"><u>[Updated] Pathway to Profit via Youtube's CP2024 Program</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-deciphering-customization-the-art-of-iphone-rings/"><u>[New] Deciphering Customization  The Art of iPhone Rings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-define-your-own-idle-time/"><u>Windows: Define Your Own Idle Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-repair-code-0xc00ce556-on-windows/"><u>Mastering Error Repair: Code 0xC00CE556 on WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-autoshrink-mechanism/"><u>Taming Window's Autoshrink Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-student-essentials-asus-vivobook-s-15-reviewed/"><u>The Ultimate Student Essentials - ASUS Vivobook S 15 Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-custom-keybinds-quick-paste-in-win-1011/"><u>Master Custom Keybinds: Quick Paste in Win 10/11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-gamers-guide-to-twisting-videos-on-youtube-2e/"><u>A Gamer's Guide to Twisting Videos on YouTube (2E)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/four-steps-for-pausing-windows-update/"><u>Four Steps for Pausing Windows Update</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-unveiling-vimeo-the-preferred-platform-by-directors/"><u>[Updated] Unveiling Vimeo  The Preferred Platform by Directors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-screen-failure-during-boot-up-in-windows-11/"><u>Addressing Screen Failure During Boot-Up in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-computer-management-not-opening-on-windows-11/"><u>5 Ways to Fix Computer Management Not Opening on Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-rapid-transition-from-srt-to-subc-with-simple-steps/"><u>2024 Approved  Rapid Transition From SRT to SUBC with Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-playback-lags-a-guide-for-chromium-users/"><u>Overcoming Playback Lags: A Guide for Chromium Users</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-social-media-trends-visualized/"><u>[New] Social Media Trends Visualized</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-escape-the-slow-gpsvc-cycle/"><u>Expert Tips to Escape the Slow GPSVC Cycle</u></a></li>
</ul></div>
