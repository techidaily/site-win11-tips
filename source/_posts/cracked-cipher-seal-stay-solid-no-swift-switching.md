---
title: "Cracked Cipher Seal: Stay Solid; No Swift Switching"
date: 2024-11-12T16:00:42.865Z
updated: 2024-11-17T18:58:01.199Z
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

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036472/19272" target="_top" id="2036472">
  <img src="//a.impactradius-go.com/display-ad/19272-2036472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036472/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-dive-into-the-world-of-superior-no-cost-webm-viewers/"><u>[New] 2024 Approved Dive Into the World of Superior No-Cost WebM Viewers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unleash-your-potential-with-snapchats-commerce-tools/"><u>[New] In 2024, Unleash Your Potential with Snapchat's Commerce Tools</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-scaling-up-on-igtv-through-powerful-hash-tagging/"><u>[Updated] In 2024, Scaling Up on IGTV Through Powerful Hash Tagging</u></a></li>
<li><a href="https://win-able.techidaily.com/1726027066427-2024dvd/"><u>【2024】おススメ！安全に解除するDVDコピー保護ソフト：試してみるだけ無料</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-changes-in-sony-bdp-s670/"><u>2024 Approved Unveiling Changes in Sony BDP-S670</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversione-gratuita-online-da-3gp-a-mjpeg-con-movavi/"><u>Conversione Gratuita Online: Da 3GP a MJPEG Con Movavi</u></a></li>
<li><a href="https://win-answers.techidaily.com/diablo-2-revisited-fixes-and-solutions-for-the-notorious-game-crash-issue/"><u>Diablo 2: Revisited - Fixes and Solutions for the Notorious Game Crash Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-mp4-upgrader-effortlessly-convert-videos-from-vcddvd-format/"><u>Free Online MP4 Upgrader: Effortlessly Convert Videos From VCD/DVD Format</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-and-successfully-boot-battlefield-4-on-your-computer/"><u>How to Fix and Successfully Boot Battlefield 4 on Your Computer</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-vivo-x100-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Vivo X100 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-online-transforma-tus-archivos-flac-a-ogg-sin-costo-alguno/"><u>Movavi Online: Transforma Tus Archivos FLAC a Ogg Sin Costo Alguno</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-cost-free-tool-transforming-dpx-photos-into-png-format-online/"><u>Movavi's Cost-Free Tool: Transforming DPX Photos Into PNG Format Online</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-on-iphone-6-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue On iPhone 6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-13-aplicativos-de-captura-de-webcam-mais-usados-para-windows-10-guia-do-movavi/"><u>Top 13 Aplicativos De Captura De Webcam Mais Usados Para Windows 10 - Guia Do Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-file-swf-in-formato-mp4-libero-e-gratuito-tramite-il-servizio-online-di-movavi/"><u>Trasforma I Tuoi File SWF in Formato MP4 Libero E Gratuito Tramite Il Servizio Online Di Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    