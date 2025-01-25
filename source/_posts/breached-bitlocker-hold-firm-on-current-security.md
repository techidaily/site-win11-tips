---
title: "Breached BitLocker: Hold Firm on Current Security"
date: 2025-01-21T19:22:47.811Z
updated: 2025-01-24T16:37:48.964Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-hints.techidaily.com/21-vegas-pros-impact-on-sports-betting-analysis-for-2024/"><u>'21 Vegas Pro's Impact on Sports Betting Analysis for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ow-to-create-a-live-stream-on-youtube-with-the-best-webcams/"><u>[New] How to Create a Live Stream on YouTube With the Best Webcams</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-igniting-interest-how-to-elevate-your-instagram-contents-impact/"><u>[New] In 2024, Igniting Interest How to Elevate Your Instagram Content's Impact</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-master-the-art-of-fast-instagram-videos-for-2024/"><u>[New] Master the Art of Fast Instagram Videos for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-the-essentials-of-audio-feature-insertion-for-ppts-for-2024/"><u>[New] The Essentials of Audio Feature Insertion for PPTs for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-precision-videoplayers-for-high-definition-on-android/"><u>[Updated] 2024 Approved Precision Videoplayers for High Definition on Android</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-crafting-engaging-youtube-videos-using-finalcut-pro-expertise/"><u>[Updated] In 2024, Crafting Engaging YouTube Videos Using FinalCut Pro Expertise</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-understanding-auto-hdr-and-smart-exposure-techniques-in-photos/"><u>[Updated] Understanding Auto HDR and Smart Exposure Techniques in Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-the-clutter-updating-and-refreshing-outdated-windows-tech/"><u>Clear the Clutter: Updating and Refreshing Outdated Windows Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-internal-audio-problems-with-audacity-windows-11/"><u>Fixing Internal Audio Problems with Audacity (Windows 11)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-short-form-content-breakdown-now/"><u>In 2024, Short Form Content Breakdown Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-troubles-heres-a-list-of-solutions-to-rescue-ineffectual-shortcuts-in-windows/"><u>Keyboard Troubles? Here's a List of Solutions to Rescue Ineffectual Shortcuts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-free-0x80072af9-corrections/"><u>Mastering Error-Free: 0X80072AF9 Corrections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-chromium-noise-on-your-windows-pc/"><u>Reducing Chromium Noise on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-procedure-elevating-to-virtualbox-version-70-on-windows-11/"><u>Stepwise Procedure: Elevating to VirtualBox Version 7.0 on Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/top-10-enterprise-cloud-options-for-2024/"><u>Top 10 Enterprise Cloud Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-pixel-density-on-win11/"><u>Tweaking Pixel Density on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-decoding-the-red-x-in-windows-explorer/"><u>Unpacking: Decoding the Red X in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wi-fi-adapter-no-more-windows-80211n-resolved-by-broadcom/"><u>Wi-Fi Adapter No More: Windows 802.11N Resolved by Broadcom</u></a></li>
</ul></div>

