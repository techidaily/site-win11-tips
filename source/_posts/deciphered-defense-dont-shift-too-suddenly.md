---
title: Deciphered Defense? Don't Shift Too Suddenly
date: 2024-06-25T16:43:32.416Z
updated: 2024-06-26T16:43:32.416Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/clearing-steam-goals-a-complete-walkthrough/"><u>Clearing Steam Goals: A Complete Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-the-stopped-netflix-app-in-windows/"><u>Reviving the Stopped Netflix App in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-to-your-needs-active-hours-and-updates/"><u>Tailoring Windows 11 to Your Needs: Active Hours & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-unfreeze-steam-and-resume-gaming-on-windows-11/"><u>How To Swiftly Unfreeze Steam and Resume Gaming on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-file-explorer-top-troubleshooting-for-win11/"><u>Revive Your File Explorer: Top Troubleshooting for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/returning-the-windows-11-search-bar-to-an-icon-style/"><u>Returning the Windows 11 Search Bar to an Icon Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-windows-11-home-settings/"><u>Navigating to Windows 11 Home Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-artificial-intelligence-generating-vibrant-ai-graphics-paint-cocreator/"><u>Windows 11 & Artificial Intelligence: Generating Vibrant AI Graphics (Paint Cocreator)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-undetected-consumer-of-life-streams-fb/"><u>In 2024, Undetected Consumer of Life Streams (FB)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-access-recovery-mastering-post-hack-facebook-fixes/"><u>[Updated] In 2024, Access Recovery  Mastering Post-Hack Facebook Fixes</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-crafting-a-continuous-youtube-video-stream-from-separate-files/"><u>[New] 2024 Approved  Crafting a Continuous Youtube Video Stream From Separate Files</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-5-essential-strategies-for-capturing-high-quality-chromebook-sound/"><u>New In 2024, 5 Essential Strategies for Capturing High-Quality Chromebook Sound</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-creative-ways-to-create-iphone-text-gif/"><u>Updated In 2024, Creative Ways to Create iPhone Text GIF</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-understanding-ip-instagram-melody-rights/"><u>[New] Understanding IP  Instagram Melody Rights</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-vivo-v30-lite-5g-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Vivo V30 Lite 5G FRP Without Computer</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-bite-sized-broadcasting-maintaining-quality-in-quick-posts-for-2024/"><u>[New] Bite-Sized Broadcasting  Maintaining Quality in Quick Posts for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>