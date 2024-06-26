---
title: Fractured Fort Knox? Continue Current Cybersecurity
date: 2024-06-25T16:16:43.103Z
updated: 2024-06-26T16:16:43.103Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fractured Fort Knox? Continue Current Cybersecurity
excerpt: This Article Describes Fractured Fort Knox? Continue Current Cybersecurity
keywords: Fort Knox Security,Cyber Defense Strategies,Data Protection Systems,Online Safety Measures,Network Vulnerabilities,Digital Threat Prevention,Cybersecurity Updates
thumbnail: https://thmb.techidaily.com/b750413312d41df96b3e21641f92f421092aa15408d61475c9e34aa15be286e0.jpg
---

## Fractured Fort Knox? Continue Current Cybersecurity

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
<li><a href="https://win11-tips.techidaily.com/essential-keyboard-commands-to-sharpen-your-3d-skills/"><u>Essential Keyboard Commands to Sharpen Your 3D Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-remedying-full-screen-troubles-in-sonic-games/"><u>Understanding and Remedying Full-Screen Troubles in Sonic Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-speedy-pointers-curtailing-acceleration-on-windows-11/"><u>Say Goodbye to Speedy Pointers: Curtailing Acceleration on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-closure-opening-folderfile-secrets-quickly/"><u>Inside Closure: Opening Folder/File Secrets Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-error-code-0x80-point-to-point-link-failure-on-windows/"><u>How to Handle Error Code: 0X80 Point-to-Point Link Failure on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-2023-laptop-reveals-ifa-edition/"><u>Top 2023 Laptop Reveals - IFA Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-laptop-onoff-trick-for-energy-conservation/"><u>Boost Your Laptop: On/Off Trick for Energy Conservation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-full-system-access-through-cmd-elevation/"><u>Gain Full System Access Through CMD Elevation</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamlining-the-process-for-free-pictured-frame-files-for-2024/"><u>Streamlining the Process for Free Pictured Frame Files for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-redefine-your-sonic-world-with-sony-ps4ps5/"><u>[Updated] Redefine Your Sonic World with Sony PS4/PS5</u></a></li>
<li><a href="https://screen-recording.techidaily.com/webcam-wizardry-for-creative-minds/"><u>Webcam Wizardry for Creative Minds</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-xiaomi-14-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Xiaomi 14</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-key-principles-of-metaverse-commercial-strategy/"><u>In 2024, Key Principles of Metaverse Commercial Strategy</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fb-video-downloader-extraordinaire-mp4-transformation-for-2024/"><u>[Updated] FB Video Downloader Extraordinaire - MP4 Transformation for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-nokia-c22-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Nokia C22 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-on-iphone-15-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock on iPhone 15</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-compreenhensive-guide-for-youtube-short-video-creators-for-2024/"><u>[New] Compreenhensive Guide for YouTube Short Video Creators for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>