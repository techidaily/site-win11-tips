---
title: Compromised Crypto-Wall? Hesitate to Swap Securely
date: 2024-11-25T16:27:40.398Z
updated: 2024-11-27T16:03:18.096Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-ideal-steps-for-silent-screen-imaging/"><u>[Updated] In 2024, Ideal Steps for Silent Screen Imaging</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-leveraging-videos-to-skyrocket-your-fb-audience/"><u>[Updated] Leveraging Videos to Skyrocket Your FB Audience</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-navigating-instagrams-posting-video-count/"><u>[Updated] Navigating Instagram's Posting Video Count</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-the-upside-down-world-of-instagram-videos/"><u>2024 Approved Exploring the Upside-Down World of Instagram Videos</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comment-faites-vous-des-gif-a-partir-de-vos-films-les-solutions-premium-movavi/"><u>Comment Faites-Vous Des GIF À Partir De Vos Films : Les Solutions Premium - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tweaks-for-enhanced-use-of-windows-11-hardware/"><u>Essential Tweaks for Enhanced Use of Windows 11 Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-expertly-control-your-sounds-with-windows-11/"><u>How to Expertly Control Your Sounds with Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-chucklecraft-pixel-perfect-humor/"><u>In 2024, ChuckleCraft Pixel-Perfect Humor</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-exciting-possibilities-the-best-12-clickers-for-pc-gamers/"><u>In 2024, Exciting Possibilities The Best 12 Clickers for PC Gamers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instagram-anon-mastery-pcandroidios-edition/"><u>In 2024, Instagram Anon Mastery PC/Android/iOS Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-reasons-why-a-pc-beats-a-mac-9-point-to-note/"><u>Mastering Reasons Why a PC Beats a Mac, #9 Point to Note</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/prime-8-film-grabs-from-fb-2023-edition-for-2024/"><u>Prime 8 Film Grabs From FB 2023 Edition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-for-wwe-2k23-glitches-on-windows-11-pcs/"><u>Swift Fixes for WWE 2K23 Glitches on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-prolonged-shutdown-during-running-apps-in-windows-10/"><u>Techniques for Prolonged Shutdown During Running Apps in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-convenient-way-to-load-apk-files-on-windows-11/"><u>The Convenient Way to Load APK Files on Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    