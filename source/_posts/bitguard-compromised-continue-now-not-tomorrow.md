---
title: "BitGuard Compromised: Continue Now, Not Tomorrow"
date: 2025-01-24T16:33:34.712Z
updated: 2025-02-01T04:36:11.029Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes BitGuard Compromised: Continue Now, Not Tomorrow"
excerpt: "This Article Describes BitGuard Compromised: Continue Now, Not Tomorrow"
keywords: BitGuard Breach Alert,Data Security Risk,Immediate Cyber Threat,Urgent Privacy Warning,Compromised Device Tips,Stop Tomorrow, Act Now,Protect Your Info Swiftly
thumbnail: https://thmb.techidaily.com/151496d9a19ba95beb3641cc868ae237a3532fbd921c881e6672274d100dff06.jpg
---

## BitGuard Compromised: Continue Now, Not Tomorrow

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-lessons.techidaily.com/updated-creating-a-visual-statement-with-stellar-podcast-artwork/"><u>[Updated] Creating a Visual Statement with Stellar Podcast Artwork</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202561962-combat-the-disappearing-cursor-problem-on-your-windows-11-touchpad-today/"><u>Combat the Disappearing Cursor Problem on Your Windows 11 Touchpad Today!</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cutting-edge-photo-restoration-pro/"><u>Cutting-Edge Photo Restoration Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-seamless-connectivity-9-tips-to-unlock-usb-wi-fi-on-pcs/"><u>Ensure Seamless Connectivity: 9 Tips to Unlock USB Wi-Fi on PCs</u></a></li>
<li><a href="https://win-able.techidaily.com/fortnite-boot-up-blues-heres-how-to-fix-a-frozen-loading-screen/"><u>Fortnite Boot-Up Blues? Here’s How to Fix a Frozen Loading Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-windows-11-control-appetizer/"><u>Mastering the Windows 11 Control Appetizer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-pin-lockouts-effective-methods/"><u>Overcoming Windows PIN Lockouts: Effective Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-restoring-erratic-windows-software/"><u>Quick Guide to Restoring Erratic Windows Software</u></a></li>
<li><a href="https://app-tips.techidaily.com/step-by-step-guide-transitioning-from-windows-home-to-professional-key-benefits-unveiled/"><u>Step-by-Step Guide: Transitioning From Windows Home to Professional - Key Benefits Unveiled</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/streamlining-home-entertainment-a-step-by-step-guide-to-converting-your-dvds-into-digital-format-on-synology-or-qnap-network-attached-storage-devices/"><u>Streamlining Home Entertainment: A Step-by-Step Guide to Converting Your DVDs Into Digital Format on Synology or QNAP Network Attached Storage Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sweetening-windows-soundscape-with-irq-fixes/"><u>Sweetening Windows Soundscape with IRQ Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-biggest-gains-in-windows-11s-february-2023-patch/"><u>The Biggest Gains in Windows 11'S February 2023 Patch</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-why-your-razor-keyboard-lights-are-dimmedunlit/"><u>Troubleshooting Guide: Fixing Why Your Razor Keyboard Lights Are Dimmed/Unlit</u></a></li>
</ul></div>

