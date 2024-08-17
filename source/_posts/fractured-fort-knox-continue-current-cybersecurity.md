---
title: Fractured Fort Knox? Continue Current Cybersecurity
date: 2024-08-16T02:24:28.815Z
updated: 2024-08-17T02:24:28.815Z
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

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://extra-approaches.techidaily.com/new-mastering-phantoms-time-reversal-feature/"><u>[New] Mastering Phantom's Time-Reversal Feature</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-streamline-projects-with-free-video-intros/"><u>[New] Streamline Projects with Free Video Intros</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-the-ultimate-tutorial-for-musical-harmony-in-your-facebook-feed/"><u>[Updated] 2024 Approved  The Ultimate Tutorial for Musical Harmony in Your Facebook Feed</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-achieving-professional-audio-in-home-recording-studios/"><u>[Updated] In 2024, Achieving Professional Audio in Home Recording Studios</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-economic-expressiveness-in-video-theming-tools/"><u>[Updated] In 2024, Economic Expressiveness in Video Theming Tools</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-efficiently-add-your-own-look-to-youtube-shorts-via-simple-steps/"><u>[Updated] In 2024, Efficiently Add Your Own Look to YouTube Shorts via Simple Steps</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-mac-users-adding-the-social-app-snapchat/"><u>[Updated] Mac Users  Adding the Social App Snapchat</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-ultimate-software-guide-to-gamers-broadcast/"><u>[Updated] Ultimate Software Guide to Gamers' Broadcast</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-advanced-techniques-for-capturing-vr-content-on-iphone/"><u>2024 Approved  Advanced Techniques for Capturing VR Content on iPhone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-maximize-video-visibility-on-facebook-via-youtube/"><u>2024 Approved  Maximize Video Visibility on Facebook via YouTube</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/4-ways-to-transfer-messages-from-apple-iphone-6s-to-iphone-including-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>4 Ways to Transfer Messages from Apple iPhone 6s to iPhone Including iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-task-managers-welcome-screenscape-in-win11/"><u>Adjusting Task Manager's Welcome Screenscape in Win11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/amd-gpio-device-drivers-secure-your-free-download-now/"><u>AMD GPIO Device Drivers - Secure Your Free Download Now!</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/breaking-barriers-chatgpts-remarkable-new-capabilities/"><u>Breaking Barriers: ChatGPT's Remarkable New Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-way-for-smooth-steam-disk-operations/"><u>Clearing the Way for Smooth Steam Disk Operations</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/comprender-y-tener-conocimiento-del-tiempo-en-espanol/"><u>Comprender Y Tener Conocimiento Del Tiempo en Espaňol</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-n-series-pros-and-cons/"><u>Deciphering Windows N Series: Pros & Cons</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-tips-for-installing-the-latest-drivers-on-your-logitech-m31-mouse/"><u>Easy Tips for Installing the Latest Drivers on Your Logitech M31 Mouse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-connect-airpods-to-windows-machines/"><u>Effortlessly Connect AirPods to Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-validity-of-windows-11-temp-files/"><u>Ensuring Validity of Windows 11 Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-eliminating-windows-temp-files/"><u>Expert Advice for Eliminating Windows' Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-changing-windows-11-search-icons-backwards/"><u>Guidelines for Changing Windows 11 Search Icons Backwards</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-vivo-by-drfone-android/"><u>How to Bypass FRP from Vivo?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreadable-source-issue-on-your-windows-pc/"><u>How to Fix ‘Unreadable Source’ Issue on Your Windows PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo Find N3? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-voice-to-text-in-real-time-with-whisper-desktop/"><u>How to Turn Your Voice to Text in Real Time With Whisper Desktop</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-enrich-engagement-tailored-questions-for-ig-story-boosting/"><u>In 2024, Enrich Engagement  Tailored Questions for IG Story Boosting</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-selecting-the-ideal-mac-screenshot-software/"><u>In 2024, Selecting the Ideal Mac Screenshot Software</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-tailoring-tutorials-for-square-shaped-video-sharing/"><u>In 2024, Tailoring Tutorials for Square-Shaped Video Sharing</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-thriving-in-the-digital-space-crafting-high-impact-fb-videos/"><u>In 2024, Thriving in the Digital Space  Crafting High-Impact FB Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-process-hostaggregate-use-and-security-implications/"><u>Investigating Windows' Process HostAggregate: Use & Security Implications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-free-leap-essential-tips-for-clean-video-windows-streams/"><u>Latency-Free Leap: Essential Tips for Clean Video Windows Streams</u></a></li>
<li><a href="https://some-guidance.techidaily.com/master-techniques-to-dodge-edgenuity-videos-swiftly-for-2024/"><u>Master Techniques to Dodge Edgenuity Videos Swiftly for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-halted-warcraft-update-sequence/"><u>Navigating a Halted Warcraft Update Sequence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-d3d11-gpu-error-landscape-for-windows-1110/"><u>Navigating the D3D11 GPU Error Landscape for Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-problems-with-saving-windows-volume-configurations/"><u>Overcoming Problems with Saving Window's Volume Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-exception-breakpoint-obstacle/"><u>Overcoming Windows Exception Breakpoint Obstacle</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-vivo-x-flip-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Vivo X Flip.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-data-theft-controlling-removable-storage-on-pcs/"><u>Preventing Data Theft: Controlling Removable Storage on PCs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/recording-real-time-action-in-overwatch-for-2024/"><u>Recording Real-Time Action in Overwatch for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reset-and-reactivate-a-windows-users-guide-for-ms-store/"><u>Reset and Reactivate: A Windows User's Guide for MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-steam-data-flow-escaping-slowdown-traps/"><u>Revitalizing Steam Data Flow: Escaping Slowdown Traps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-telnet-activation-on-latest-windows-systems/"><u>Secure Telnet Activation on Latest Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-hidden-time-display-on-windows-bar/"><u>Setting Up Hidden Time Display on Window's Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-management-with-windows-autodelete-feature/"><u>Simplifying File Management with Windows' AutoDelete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-a-halted-download-the-windows-method/"><u>Speeding up a Halted Download: The Windows Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-incorrect-windows-duo-software-setup/"><u>Steps to Rectify Incorrect Windows Duo Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-package-unopenable-issue-effectively/"><u>Steps to Tackle Windows Package Unopenable Issue Effectively</u></a></li>
<li><a href="https://games-able.techidaily.com/stop-automatic-steam-launch-on-system-restart/"><u>Stop Automatic Steam Launch on System Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-display-embrace-tiled-workspace/"><u>Streamline Your Display: Embrace Tiled Workspace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-dims-handbook-for-windows-11-repair/"><u>The Complete DIMS Handbook for Windows 11 Repair</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/top-5-cost-effective-pc-recording-applications/"><u>Top 5 Cost-Effective PC Recording Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-tactics-reactivating-windows-defender-protection-mechanism/"><u>Top 5 Tactics: Reactivating Windows Defender Protection Mechanism</u></a></li>
<li><a href="https://program-issues.techidaily.com/trouble-with-avatars-new-area-a-comprehensive-fix-for-pandoras-edge-not-loading/"><u>Trouble with Avatar's New Area? A Comprehensive Fix for Pandora's Edge Not Loading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-start-issue-qt-plugin-not-available/"><u>Troubleshooting App Start Issue: Qt Plugin Not Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wasd-isolation-necessity-or-concern/"><u>Understanding WASD Isolation: Necessity or Concern?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-capability-of-windows-11-with-multi-display-setup/"><u>Unlock the Full Capability of Windows 11 With Multi-Display Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-adopting-sudo-can-transform-your-windows-experience/"><u>Why Adopting Sudo Can Transform Your Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-clean-boot-a-beginners-approach/"><u>Windows 11 Clean Boot: A Beginner's Approach</u></a></li>
</ul></div>
