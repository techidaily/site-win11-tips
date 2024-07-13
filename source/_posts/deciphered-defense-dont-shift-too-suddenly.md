---
title: Deciphered Defense? Don't Shift Too Suddenly
date: 2024-07-12T17:12:49.512Z
updated: 2024-07-13T17:12:49.512Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphered Defense? Don't Shift Too Suddenly
excerpt: This Article Describes Deciphered Defense? Don't Shift Too Suddenly
keywords: Defense Decoded,No Rapid Change,Security Insight,Strategic Pause,Tactics Reveal,Shift Caution,Sudden Transition
thumbnail: https://thmb.techidaily.com/04715cc01635128f130003aeefa217d9440724157165604a4668d27f41792057.jpeg
---

## Deciphered Defense? Don't Shift Too Suddenly

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
<li><a href="https://win11-tips.techidaily.com/new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-treasures-found-the-guide-to-recover-lost-features-in-windows-11/"><u>Hidden Treasures Found: The Guide to Recover Lost Features in Window’s 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-performance-skyrocketing-vram-in-win1011-systems/"><u>Enhance Performance: Skyrocketing VRAM in Win10/11 Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-mobile-video-assembly-software-for-smartphones/"><u>[Updated] Top Mobile Video Assembly Software for Smartphones</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-download-youtube-videos-directly/"><u>[New] 2024 Approved  Download YouTube Videos Directly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-grayed-out-secure-boot-in-the-bios-on-windows/"><u>How to Fix a Grayed-Out Secure Boot in the BIOS on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-adopting-sudo-can-transform-your-windows-experience/"><u>Why Adopting Sudo Can Transform Your Windows Experience</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-prime-7-apps-for-smooth-youtube-live-broadcast-from-iphone-and-android-devices/"><u>[New] Prime 7 Apps for Smooth YouTube Live Broadcast From iPhone & Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-web-access-via-win-os/"><u>Ensuring Seamless Web Access via Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-elevating-your-listening-experience-online-techniques-for-speed-and-pitch-alteration-for-2024/"><u>New Elevating Your Listening Experience Online Techniques for Speed and Pitch Alteration for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-capturing-uac-alerts-on-your-pc/"><u>Expert Guide: Capturing UAC Alerts on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-manual-for-individualized-keybindings-in-win11/"><u>A Detailed Manual for Individualized Keybindings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-phone-media-saving-problems/"><u>Eliminating Windows Phone Media Saving Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-windows-printer-revival/"><u>Immediate Windows Printer Revival</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-get-adobe-premiere-pro-cs6-for-mac-at-no-cost-2023-update/"><u>Updated 2024 Approved Get Adobe Premiere Pro CS6 for Mac at No Cost 2023 Update</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-elite-mkv-media-viewer-pc-and-smartphone/"><u>2024 Approved  Elite MKV Media Viewer (PC & Smartphone)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-tour-to-windows-booting-point/"><u>A Quick Tour to Windows' Booting Point</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-frame-your-photos-right-a-guide-to-top-notch-edges-in-instagram/"><u>2024 Approved  Frame Your Photos Right  A Guide to Top-Notch Edges in Instagram</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-into-the-humor-hub-of-the-world-wide-web-metaverse-memes-101/"><u>2024 Approved  Into the Humor Hub of the World Wide Web - Metaverse Memes 101</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wizardry-learn-hotkeys-to-manage-your-pc/"><u>Windows Wizardry: Learn Hotkeys to Manage Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-mouseclicklock-usability-on-windows-systems/"><u>Boosting MouseClickLock Usability on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-hdd-invisibility-glitches/"><u>Correcting HDD Invisibility Glitches</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-wild-wonders-the-ultimate-list-of-strange-and-exciting-tiktok-games/"><u>[New] Wild Wonders  The Ultimate List of Strange and Exciting TikTok Games</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-15-top-montage-music-for-different-video-types/"><u>New 2024 Approved 15 Top Montage Music for Different Video Types</u></a></li>
<li><a href="https://extra-resources.techidaily.com/video-vibrance-10-tips-for-dynamic-color-manipulation/"><u>Video Vibrance  10 Tips for Dynamic Color Manipulation</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-make-your-videos-accessible-10-free-subtitle-makers-online/"><u>New Make Your Videos Accessible 10 Free Subtitle Makers Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-malware-scanners-hang-up-compute-resources/"><u>Can Malware Scanners Hang Up Compute Resources?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-comprehensive-list-of-premier-webinars/"><u>2024 Approved  Comprehensive List of Premier Webinars</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-unlock-new-horizons-best-6-instagram-reel-apps/"><u>[Updated] Unlock New Horizons  Best 6 Instagram Reel Apps</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-crafting-content-that-wins-on-ig-unboxing-edition/"><u>[New] Crafting Content That Wins on IG  Unboxing Edition</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-chirping-cha-cha-charade/"><u>[New] Chirping Cha-Cha Charade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updater-setback-error-0x800f080a-on-windows-systems/"><u>Bypassing Updater Setback Error 0X800F080A on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-the-minutes-windows-system-synchronized/"><u>Mend the Minutes: Windows System Synchronized</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erratic-read-only-file-behavior-on-win11/"><u>Fixing Erratic Read-Only File Behavior on Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/perfecting-your-content-time-stamping-in-online-vids/"><u>Perfecting Your Content  Time Stamping in Online Vids</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-from-your-apple-iphone-x-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID From your Apple iPhone X?</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-digital-diving-into-youtubes-veiled-video-vaults/"><u>[Updated] 2024 Approved  Digital Diving Into YouTube’s Veiled Video Vaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-clean-boot-a-beginners-approach/"><u>Windows 11 Clean Boot: A Beginner's Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-transfer-windows-11-auto-move-techniques/"><u>Mastering File Transfer: Windows 11 Auto-Move Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-real-time-hardware-for-vr/"><u>[New] Real-Time Hardware for VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-scroll-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can't Scroll in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-customize-your-loading-text-effect-in-2024/"><u>New How to Customize Your Loading Text Effect, In 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-nocturnal-nexus-versus-daylight-dominion/"><u>[New] Nocturnal Nexus Versus Daylight Dominion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convergence-of-ios-and-windows-using-apple-maps-effectively/"><u>Convergence of iOS and Windows: Using Apple Maps Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confusion-in-xbox-app-gaming-placement/"><u>Confusion in Xbox App Gaming Placement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-operation-fixing-windows-notepad-crashes/"><u>Ensuring Smooth Operation: Fixing Windows Notepad Crashes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/standing-and-proficiently-implementing-cc-copyrights-for-2024/"><u>Understanding and Proficiently Implementing CC Copyrights for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/discovering-the-power-behind-youtube-statistics-interpretation/"><u>Discovering the Power Behind YouTube Statistics Interpretation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-customized-policies-to-a-singular-account-in-win-1011/"><u>Executing Customized Policies to a Singular Account in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-center-personalizing-folders-through-comments-in-11/"><u>Command Center: Personalizing Folders Through Comments in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-product-activation-failed-error-on-microsoft-office-apps-for-windows/"><u>How to Fix the Product Activation Failed Error on Microsoft Office Apps for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-desktop-experience-with-windows-11-widgets/"><u>Elevate Your Desktop Experience with Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-personalized-windows-11-interface-with-enlarged-icons/"><u>Crafting a Personalized Windows 11 Interface with Enlarged Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-value-not-available-issue-in-windows/"><u>Eradicating Value Not Available Issue in Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-excellence-in-detail-a-curated-list-of-8k-cameras/"><u>In 2024, Excellence in Detail  A Curated List of 8K Cameras</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-captivate-and-conquer-with-customized-content-shorts/"><u>[New] Captivate and Conquer with Customized Content Shorts</u></a></li>
</ul></div>
