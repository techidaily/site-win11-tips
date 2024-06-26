---
title: "BitFort Fractured: Stay the Course Before Change"
date: 2024-06-25T16:26:26.759Z
updated: 2024-06-26T16:26:26.759Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes BitFort Fractured: Stay the Course Before Change"
excerpt: "This Article Describes BitFort Fractured: Stay the Course Before Change"
keywords: BitFort Transformation,Maintain BitFort,BitFort Security,Stay Secure BitFort,Navigate BitFort Change,Preserve BitFort Integrity,Keep BitFort Unified,Fortify BitFort Stay,Secure BitFort Course,Maintain BitFort Strong,Uphold BitFort Core,Steer Through Change BitFort,Safeguard BitFort Stand,Keep BitFort Together
thumbnail: https://thmb.techidaily.com/e937c769751b4b8235d825da190a8de514c18ce6c728b4bc630fa21c8db2efdc.jpg
---

## BitFort Fractured: Stay the Course Before Change

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/quick-suppress-mechanism-for-windows-11-dings/"><u>Quick Suppress Mechanism for Windows 11 Dings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-review-pcmac-comparison/"><u>ASUS Zenbook 14 OLED Review: PC/Mac Comparison?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-revive-slowq-bittorrent-progress-on-pc/"><u>Strategies to Revive Slowq Bittorrent Progress on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-video-lag-in-vlc-media-player-on-windows/"><u>How to Fix Video Lag in VLC Media Player on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-incorrect-windows-duo-software-setup/"><u>Steps to Rectify Incorrect Windows Duo Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/practical-guide-to-disregarding-false-security-alarms-in-chrome/"><u>Practical Guide to Disregarding False Security Alarms in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-and-dxgidll-fix-for-a-missing-crucial-file/"><u>Win11 & Dxgi.dll: Fix for a Missing Crucial File</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-the-unchanged-status-of-windows-screensaver/"><u>Ensuring the Unchanged Status of Windows Screensaver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-app-usage-a-comprehensive-review/"><u>Window's App Usage: A Comprehensive Review</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-primes-premier-pieces-the-watched-and-tweeted-superstars/"><u>[New] In 2024, Prime’s Premier Pieces  The #Watched & Tweeted Superstars</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-s21-fe-5g-2023-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy S21 FE 5G (2023) If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-variations-panoramic-and-virtual-reality-films-for-2024/"><u>Exploring Variations  Panoramic & Virtual Reality Films for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-make-your-own-lyric-video-top-online-makers-to-try-for-2024/"><u>New Make Your Own Lyric Video Top Online Makers to Try for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024s-rapid-rise-videos-achieving-100m-views-quickly/"><u>2024'S Rapid Rise Videos Achieving 100M Views Quickly</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-exploring-facetune-features-your-ultimate-guide-to-better-images/"><u>[Updated] In 2024, Exploring Facetune Features  Your Ultimate Guide to Better Images</u></a></li>
<li><a href="https://extra-tips.techidaily.com/flickvista-app-performance-index/"><u>FlickVista App Performance Index</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-ancient-warriors-new-battlegrounds-top-games-like-the-japanese-epic/"><u>2024 Approved  Ancient Warriors, New Battlegrounds  Top Games Like the Japanese Epic</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-become-a-viral-sensation-best-tiktok-sayings-compilation/"><u>[Updated] Become a Viral Sensation  Best TikTok Sayings Compilation</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-from-social-media-savant-to-money-maker-on-instagram/"><u>[Updated] From Social Media Savant to Money Maker on Instagram</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>