---
title: "Breached BitLocker: Hold Firm on Current Security"
date: 2024-07-29T08:13:35.509Z
updated: 2024-07-30T08:13:35.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breached BitLocker: Hold Firm on Current Security"
excerpt: "This Article Describes Breached BitLocker: Hold Firm on Current Security"
keywords: Breach BitLocker Secure,BitLocker Vulnerability,Encrypt Data Safely,Hardened BitLocker Defense,Strong BitLocker Security,Resist Crypto Attacks,Fortify Key Protection
thumbnail: https://thmb.techidaily.com/ce2c767b4ea66790422350863194f4cca1e1e1f1b31e78a51ee237f509439d21.jpg
---

## Breached BitLocker: Hold Firm on Current Security

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/023s-standout-youtube-music-playback-gems/"><u>[New] 2023'S Standout YouTube Music Playback Gems</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-how-to-craft-contagious-instagram-visuals/"><u>[New] 2024 Approved  How to Craft Contagious Instagram Visuals</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-comprehensive-guide-to-10-best-meme-patterns/"><u>[New] 2024 Approved  The Comprehensive Guide to #10 Best Meme Patterns</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-a-step-by-step-approach-to-generating-income-with-trailers/"><u>[New] A Step-by-Step Approach to Generating Income with Trailers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-high-speed-recording-tool-with-guided-soundtracks/"><u>[New] High-Speed Recording Tool with Guided Soundtracks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-proven-techniques-to-enhance-engagement-and-interaction/"><u>[New] In 2024, Proven Techniques to Enhance Engagement and Interaction</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-the-ultimate-starters-guide-to-understanding-and-using-green-screens/"><u>[New] The Ultimate Starter’s Guide to Understanding and Using Green Screens</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-top-11-pro-level-screen-recorders-for-mac-users/"><u>[Updated] 2024 Approved  Top 11 Pro-Level Screen Recorders for Mac Users</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-exploring-and-harnessing-twitter-archive-insights/"><u>[Updated] Exploring and Harnessing Twitter Archive Insights</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-beginners-guide-to-simple-yet-effective-filming-gear/"><u>2024 Approved  Beginner's Guide to Simple, Yet Effective Filming Gear</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-quick-guide-initiating-and-managing-android-zoom-calls/"><u>2024 Approved  Quick Guide  Initiating & Managing Android Zoom Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-lock-screen-timeout-windows/"><u>Addressing Disabled Lock Screen Timeout Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-code-0x0000004e-on-windows-os/"><u>Eliminating Code 0X0000004E on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-non-crashy-windows-user-experience/"><u>Ensure Non-Crashy Windows User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-in-minutes-command-line-steps/"><u>Exploring Windows in Minutes: Command Line Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-youtube-playback-speed-delays-in-chrome/"><u>Fixing YouTube Playback Speed Delays in Chrome</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-android-experience-with-rich-3d-content/"><u>In 2024, Best Android Experience with Rich 3D Content</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Tecno Spark Go (2024) | Dr.fone</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/in-2024-google-translate-video-a-complete-guide-to-translate-video-with-google/"><u>In 2024, Google Translate Video A Complete Guide To Translate Video With Google</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-honor-magic-vs-2-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Honor Magic Vs 2 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-pursuit-of-purposeful-downloads-from-windows-store/"><u>In Pursuit of Purposeful Downloads From Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-luminance-adjustments-on-your-win11-device/"><u>Leveraging Luminance Adjustments on Your Win11 Device</u></a></li>
<li><a href="https://data-wizards.techidaily.com/maintain-vids-clear-not-corrupted/"><u>Maintain Vids Clear, Not Corrupted</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-netconfig-a-guide-to-connectivity/"><u>Mastering Window's NetConfig: A Guide to Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11s-default-search-settings/"><u>Optimizing Windows 11'S Default Search Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-windows-resolution-glitches/"><u>Overcoming Common Windows Resolution Glitches</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-itel-s23plus-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Itel S23+ Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-honor-magic-6-pro-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Honor Magic 6 Pro Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-voice-typing-problems-error-code-0x80049dd3-in-windows-11/"><u>Remedying Voice Typing Problems (Error Code: 0X80049DD3) in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-onedrive-login-failure-x8004dec5-windows-issue/"><u>Resolving ONEDRIVE Login Failure: X.8004DEC5 Windows Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-muted-windows-start-button-icon/"><u>Resurrecting Your Muted Windows Start Button Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-current-windows-pass-error-in-win11win11/"><u>Solving Current Windows Pass Error in Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-creating-self-extracting-fx-in-win11/"><u>Step-by-Step: Creating Self-Extracting FX in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-halt-moving-of-apps-within-the-windows-ui/"><u>Techniques to Halt Moving of Apps Within the Windows UI</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy A23 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-pathway-to-preserving-instagram-content-via-desktop-platforms-for-2024/"><u>The Pathway to Preserving Instagram Content via Desktop Platforms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-banishing-the-persistent-pink-error-on-windows/"><u>The Ultimate Guide to Banishing the Persistent Pink Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-stopping-unwanted-disk-filling/"><u>The Ultimate Guide to Stopping Unwanted Disk Filling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-soundcard-irq-errors-on-pc/"><u>Troubleshooting Soundcard IRQ Errors on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-headset-microphone-blockage/"><u>Unblocking Windows Headset Microphone Blockage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-the-difference-between-the-c-drive-and-the-d-drive/"><u>What's the Difference Between the C: Drive and the D: Drive?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-password-safety-tools-for-windows-11-users/"><u>Winning Password Safety Tools for Windows 11 Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>