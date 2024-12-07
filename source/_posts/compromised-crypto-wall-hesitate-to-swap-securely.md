---
title: Compromised Crypto-Wall? Hesitate to Swap Securely
date: 2024-12-05T17:37:47.935Z
updated: 2024-12-06T17:38:15.498Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Compromised Crypto-Wall? Hesitate to Swap Securely
excerpt: This Article Describes Compromised Crypto-Wall? Hesitate to Swap Securely
keywords: Crypto Wall Concerns,Secure Exchange Risks,Crypto Security Breach,Safe Cryptocurrency Trade,Hesitate to Swap,Crypto Safety Check,Trading with Caution
thumbnail: https://thmb.techidaily.com/6644f0a2d74892fa3a39d2d46d9f44395a7ca3377bb37001448c4704afb2e518.jpg
---

## Compromised Crypto-Wall? Hesitate to Swap Securely

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/new-fostering-fast-visual-storytelling-with-google-imagery-for-2024/"><u>[New] Fostering Fast Visual Storytelling with Google Imagery for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-best-practices-snatching-supreme-photos-for-free/"><u>[New] In 2024, Best Practices Snatching Supreme Photos for Free</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-efficacy-of-social-media-authenticity-validation-for-2024/"><u>[New] The Efficacy of Social Media Authenticity Validation for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-premium-video-capture-devices-for-windows-os-for-2024/"><u>[Updated] Premium Video Capture Devices for Windows OS for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-tecno-spark-20-proplus-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Tecno Spark 20 Pro+ System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-poco-x6-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-modify-registry-editor-access-in-win11/"><u>Easily Modify Registry Editor Access in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-edges-security-features-graphics-boost/"><u>Elevating Edges Security Features: Graphics Boost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essentials-on-using-microsofts-phone-link-a-guide/"><u>Essentials on Using Microsoft's 'Phone Link': A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-concept-to-creation-painting-ai-masterpieces-on-windows-11-paint-cocreator-edition/"><u>From Concept to Creation: Painting AI Masterpieces on Windows 11, Paint Cocreator Edition</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-samsung-galaxy-m34-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Samsung Galaxy M34 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-data-management-on-windows-11/"><u>Mastering Data Management on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolve-windows-stores-error-0x80073d26/"><u>Quick Guide to Resolve Windows Store's Error 0X80073D26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-dealing-with-non-terminatable-processes-on-pc/"><u>Tips for Dealing with Non-Terminatable Processes on PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/unlocking-screen-capture-mastery-in-windows-os-for-2024/"><u>Unlocking Screen Capture Mastery in Windows OS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-lite-version-exploring-s-mode-benefits/"><u>Windows 11'S Lite Version: Exploring S Mode Benefits?</u></a></li>
</ul></div>

