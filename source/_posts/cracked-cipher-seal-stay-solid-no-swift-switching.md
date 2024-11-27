---
title: "Cracked Cipher Seal: Stay Solid; No Swift Switching"
date: 2024-11-24T16:28:22.036Z
updated: 2024-11-27T17:19:42.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cracked Cipher Seal: Stay Solid; No Swift Switching"
excerpt: "This Article Describes Cracked Cipher Seal: Stay Solid; No Swift Switching"
keywords: Cracked Cipher Secure,Cipher Solidity,Unbroken Encryption,Steady Cipher,Resistant Cryptography,Sturdy Seal Cipher,No Switching Ciphers
thumbnail: https://thmb.techidaily.com/72f5184d5296c1cbee8c85039f08d18862c38c7bcca88e3aaa3f5eb78673eb91.png
---

## Cracked Cipher Seal: Stay Solid; No Swift Switching

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-streamlining-video-craft-youtube-studio-edition/"><u>[Updated] Streamlining Video Craft YouTube Studio Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-solving-windows-11s-app-startup-error-code-0xc000003e/"><u>Deciphering and Solving Windows 11'S App Startup Error: Code 0XC000003E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-continuous-edge-key-presses/"><u>Eradicating Continuous Edge Key Presses</u></a></li>
<li><a href="https://win-blog.techidaily.com/error-free-gaming-awaits-guide-to-correcting-nba-2k24-issue-72e66ac-for-the-2024-season/"><u>Error-Free Gaming Awaits! Guide to Correcting NBA 2K24 Issue 72^E66AC for the 2024 Season</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guided-steps-altering-administrative-profile-in-windows-11/"><u>Guided Steps: Altering Administrative Profile in Windows 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-mobile-mastery-youtube-video-thumbnails-made-easy/"><u>In 2024, Mobile Mastery YouTube Video Thumbnails Made Easy</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-amplify-animated-photo-with-acoustic-elements-via-win-1011/"><u>New Amplify Animated Photo with Acoustic Elements via Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-your-pcs-primary-command-line-editor/"><u>Perfect Your PC's Primary Command Line Editor</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-the-potential-of-adobe-and-exploring-others-for-2024/"><u>Unlocking the Potential of Adobe & Exploring Others for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unraveling-the-mystery-why-do-cybercriminals-focus-on-chatgpt-usernames/"><u>Unraveling the Mystery: Why Do Cybercriminals Focus on ChatGPT Usernames?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-pcs-proclaim-their-superiority-to-mac-users-9/"><u>Why PCs Proclaim Their Superiority to Mac Users (#9)</u></a></li>
</ul></div>

