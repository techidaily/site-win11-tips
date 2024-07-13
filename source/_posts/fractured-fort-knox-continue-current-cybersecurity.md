---
title: Fractured Fort Knox? Continue Current Cybersecurity
date: 2024-07-12T16:41:46.026Z
updated: 2024-07-13T16:41:46.026Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fractured Fort Knox? Continue Current Cybersecurity
excerpt: This Article Describes Fractured Fort Knox? Continue Current Cybersecurity
keywords: Fort Knox Security,Cyber Defense Strategies,Data Protection Systems,Online Safety Measures,Network Vulnerabilities,Digital Threat Prevention,Cybersecurity Updates
thumbnail: https://thmb.techidaily.com/b750413312d41df96b3e21641f92f421092aa15408d61475c9e34aa15be286e0.jpg
---

## Fractured Fort Knox? Continue Current Cybersecurity

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/notepads-dark-shift-windows-11-guide/"><u>Notepad's Dark Shift: Windows 11 Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-ultimate-list-of-10-free-online-subtitle-creators-for-videos-for-2024/"><u>New The Ultimate List of 10 Free Online Subtitle Creators for Videos for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-cut-to-perfection-advanced-guide-to-cropping-videos-for-instagram/"><u>[New] Cut to Perfection  Advanced Guide to Cropping Videos for Instagram</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-bright-ideas-in-film-setup-secrets-to-perfect-lighting/"><u>[New] Bright Ideas in Film Setup  Secrets to Perfect Lighting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-steam-for-seamless-gameplay-on-windows-11-devices/"><u>Realigning Steam for Seamless Gameplay on Windows 11 Devices</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/dslrs-place-among-mirrorless-cameras-for-videos-for-2024/"><u>DSLR's Place Among Mirrorless Cameras for Videos for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-shaping-public-perception-5-essentials-for-instagram-marketing-mavericks/"><u>[New] 2024 Approved  Shaping Public Perception  5 Essentials for Instagram Marketing Mavericks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-win-microphone-functionality/"><u>Troubleshoot Win Microphone Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-adjustments-for-enhanced-windows-bar/"><u>Step-by-Step Adjustments for Enhanced Windows Bar</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-securing-your-snapshots-premium-and-budget-friendly-cloud-options/"><u>2024 Approved  Securing Your Snapshots  Premium and Budget-Friendly Cloud Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-to-spotify-fixing-windows-11-errors/"><u>Reconnecting to Spotify: Fixing Windows 11 Errors</u></a></li>
<li><a href="https://extra-hints.techidaily.com/affordable-yet-high-quality-cameras-list-for-2024/"><u>Affordable Yet High-Quality Cameras List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-disrupted-windows-thx-spatial-sound/"><u>Mending Disrupted Windows THX Spatial Sound</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/techniques-for-high-quality-rl-footage/"><u>Techniques for High-Quality RL Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-updating-window-11s-context-menu/"><u>Streamlining Tasks: Updating Window 11'S Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-for-windows-1011-search-that-fails-to-display-output/"><u>Troubleshooting for Windows 10/11 Search that Fails to Display Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-failed-updates-error-0x800f0845/"><u>Steps to Fix Failed Updates - Error 0X800f0845</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/lively-latins-interactive-and-exciting-education/"><u>Lively Latins: Interactive and Exciting Education</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-dish-to-screen-your-recipe-video-blueprint/"><u>[New] 2024 Approved  Dish to Screen  Your Recipe Video Blueprint</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-avoid-breaches-the-pre-upload-guide-to-copyright-on-tiktok/"><u>[Updated] In 2024, Avoid Breaches  The Pre-Upload Guide to Copyright on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-aggregatorhostexe-windows-functionality-and-safety-concerns/"><u>Understanding AggregatorHost.exe: Windows' Functionality & Safety Concerns</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-the-mobile-way-to-youtube-fame-streamlined-channel-creation-process/"><u>2024 Approved  The Mobile Way to YouTube Fame  Streamlined Channel Creation Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-user-support-4-new-windows-features/"><u>Transforming User Support: 4 New Windows Features</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pro-photo-framegers-to-polish-pictures-online/"><u>[New] Pro Photo Framegers to Polish Pictures Online</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-the-digital-landscape-mastery-of-video-filter-techniques/"><u>Navigating the Digital Landscape  Mastery of Video Filter Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/universal-font-collection-windows-installation-steps/"><u>Universal Font Collection: Windows Installation Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-pathway-for-changing-login-method-from-pin-to-passwords-on-windows-11/"><u>Unveiling the Pathway for Changing Login Method From PIN to Passwords on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-ideas-for-creating-sequences-of-iphone-burst-images/"><u>[Updated] Ideas for Creating Sequences of iPhone Burst Images</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-highpoint-artist-toolkit-review/"><u>2024 Approved  Highpoint Artist Toolkit Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-outlook-problems-on-pcs/"><u>Understanding and Fixing Outlook Problems on PCs</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-pianofilm-harmonies-a-premium-assembly-of-royalty-free-cinematic-scores-perfect-for-visual-media-production/"><u>New 2024 Approved Pianofilm Harmonies A Premium Assembly of Royalty-Free Cinematic Scores Perfect for Visual Media Production</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-explore-10-premium-youtube-to-webm-converter-tools/"><u>[New] Explore 10 Premium YouTube-to-WebM Converter Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-inactive-windows-file-alignment-service/"><u>Solutions for Inactive Windows File Alignment Service</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-best-practices-for-mobile-snapchat-recording-techniques-for-2024/"><u>[Updated] Best Practices for Mobile Snapchat Recording Techniques for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-motorola-razr-40-ultra-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve  deleted photos on Motorola Razr 40 Ultra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-7-steps-to-mend-obs-server-link-error-in-windows/"><u>Navigating 7 Steps to Mend OBS Server Link Error in Windows</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-shegames-legends-youtubes-number-one-ten/"><u>[Updated] SheGames Legends  YouTube's Number One Ten</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-exception-handling-breaking-point-solution/"><u>Mastering Windows Exception Handling: Breaking Point Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-pc-boost-unearthing-windows-best-eight-restart-strategies/"><u>Quick PC Boost: Unearthing Windows' Best Eight Restart Strategies</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-top-builds-for-maximum-mc-safety/"><u>2024 Approved  Top Builds for Maximum MC Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipgear-gone-wrong-nine-effective-tips-to-get-it-running-again/"><u>SnipGear Gone Wrong? Nine Effective Tips to Get It Running Again</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-best-14-youtube-gaming-video-ideas-to-boost-gaming-channels/"><u>In 2024, Best 14 YouTube Gaming Video Ideas to Boost Gaming Channels</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ate-picks-for-costless-subtitle-extraction-tools/"><u>Ultimate Picks for Costless Subtitle Extraction Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-roots-user-permissions-back-to-basics-in-win11/"><u>Restoring Roots: User Permissions Back to Basics in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-microsofts-copilot-key-for-windows-11-users/"><u>Unveiling the Secrets of Microsoft's Copilot Key for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-unregistered-package-error-in-win11-images/"><u>Steps to Resolve Unregistered Package Error in Win11 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-restarting-windows-11-apps/"><u>Reviving Your PC: Restarting Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-service-management-for-optimized-windows-11/"><u>Strategic Service Management for Optimized Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-rhythmcapture-toolkit-a-critical-walkthrough/"><u>2024 Approved  RhythmCapture Toolkit  A Critical Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-hardware-new-horizinas-guiding-windows-11-22h2-installation/"><u>Old Hardware, New Horizinas: Guiding Windows 11 22H2 Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-on-or-off-windows-digital-protection-filter/"><u>Switching on or Off Windows' Digital Protection Filter</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-huawei-p60-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Huawei P60 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-removing-virtualization-support-on-win11/"><u>Tips for Removing Virtualization Support on Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-instagram-power-play-top-10-apps-to-increase-followers-and-posts/"><u>[New] 2024 Approved  Instagram Power Play  Top 10 Apps to Increase Followers & Posts</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-oppo-reno-11-pro-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Oppo Reno 11 Pro 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-undoing-movement-how-to-reverse-video-on-snapchat/"><u>[New] Undoing Movement  How to Reverse Video on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-aural-anomaly-fixing-audacity-writes-on-wos/"><u>Tackling the Aural Anomaly: Fixing Audacity' Writes on WOS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/action-like-never-before-review-the-t5-eye-action-camera/"><u>Action Like Never Before  Review the T5 Eye Action Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-terminal-the-unshackled-experience/"><u>Restoring Windows Terminal: The Unshackled Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-why-drives-vanish-on-windows-fix-guide-required/"><u>Unveiling Why Drives Vanish on Windows - Fix Guide Required</u></a></li>
</ul></div>
