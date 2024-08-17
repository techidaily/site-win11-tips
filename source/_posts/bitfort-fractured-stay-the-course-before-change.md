---
title: "BitFort Fractured: Stay the Course Before Change"
date: 2024-08-16T02:12:56.762Z
updated: 2024-08-17T02:12:56.762Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-2023-techniques-posting-tiktoks-on-twitter/"><u>[New] 2023 Techniques  Posting TikToks on Twitter</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-ever-fading-memories-revived-youtubes-lost-content-hunt/"><u>[New] In 2024, Ever-Fading Memories Revived  YouTube's Lost Content Hunt</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-perfecting-your-video-game-broadcast-the-obs-way/"><u>[New] Perfecting Your Video Game Broadcast  The OBS Way</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-from-viewers-to-valuables-mastering-video-monetization-on-vimeo/"><u>[Updated] 2024 Approved  From Viewers to Valuables  Mastering Video Monetization on Vimeo</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-enabling-successful-video-sharing-in-messenger-for-ios-and-android-users-for-2024/"><u>[Updated] Enabling Successful Video Sharing in Messenger for iOS and Android Users for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-perfecting-aerial-images-key-factors-in-picking-a-gimbal-for-2024/"><u>[Updated] Perfecting Aerial Images  Key Factors in Picking a Gimbal for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-surf-in-focus-cutting-edge-action-cameras/"><u>[Updated] Surf in Focus  Cutting-Edge Action Cameras</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-ultimate-selection-of-free-youtube-introduction-makers/"><u>[Updated] Ultimate Selection of Free YouTube Introduction Makers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-top-tips-for-quick-and-reliable-recording-of-presentations/"><u>2024 Approved  Top Tips for Quick and Reliable Recording of Presentations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-upcoming-license-expiration-error-in-w10w11/"><u>Addressing Upcoming License Expiration Error in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwelcome-closure-messages-from-your-roblox-games/"><u>Avoiding Unwelcome Closure Messages From Your Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-failed-operations-code-0x0000011b-fixes/"><u>Eliminating 'Failed' Operations: Code 0X0000011B Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-soon-expiring-license-messages-from-your-pc/"><u>Eliminating “Soon Expiring License” Messages From Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-visibility-of-results-with-windows-11-search-fixes/"><u>Enhancing Visibility of Results with Windows 11 Search Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-error-30005-struggles-with-new-file-creation/"><u>Fixing Windows Error 30005 - Struggles with New File Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-files-fix-incessant-file-explorer-opens/"><u>Halt Files: Fix Incessant File Explorer Opens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-erase-files-for-good-on-your-windows-11-and-11-desktop-bin/"><u>How to Erase Files for Good on Your Windows 11 & 11 Desktop Bin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-store-error-0x80072f17-on-windows/"><u>How to Fix Microsoft Store Error 0X80072F17 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-fixes-for-unstartable-windows-services/"><u>Implementing Fixes for Unstartable Windows Services</u></a></li>
<li><a href="https://driver-download.techidaily.com/improve-performance-download-updated-drivers-for-intel-hd-graphics-ebx-53006300-series/"><u>Improve Performance: Download Updated Drivers for Intel HD Graphics Ebx 5300/6300 Series</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-expert-strategies-for-effective-online-image-trimming/"><u>In 2024, Expert Strategies for Effective Online Image Trimming</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-poco-c65-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Poco C65 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-copilot-key-what-does-it-mean-for-your-windows-11-pc/"><u>Microsoft's Copilot Key: What Does It Mean For Your Windows 11 PC?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-windows-horizon-surpassing-11s-achievements/"><u>Next Windows Horizon: Surpassing 11'S Achievements</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimize-your-pcs-visuals-with-a-fresh-intel-3000-driver-on-w10/"><u>Optimize Your PC's Visuals with a Fresh Intel 3000 Driver on W10.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-missing-component-alert-in-windows-1011/"><u>Overcoming the Missing Component Alert in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/playnite-extension-virtual-games-collection/"><u>Playnite Extension: Virtual Games Collection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-to-windows-updates-on-windows-108/"><u>Regaining Access to Windows Updates on Windows 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-photo-import-discrepancies-between-ios-and-windows-11/"><u>Remedying Photo Import Discrepancies Between iOS and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-hyper-v-feature-from-windows-11-builds/"><u>Removing Hyper-V Feature From Windows 11 Builds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-your-windows-display-hurdles-easily/"><u>Resolve Your Window's Display Hurdles Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-your-pcs-dns-with-ease-in-windows-11/"><u>Revitalizing Your PC's DNS with Ease in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-win11-wi-fi-accessibility-with-9-steps/"><u>Securing Win11 Wi-Fi Accessibility with 9 Steps</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-incompatible-hdmi-between-devices/"><u>Solved Incompatible HDMI Between Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-9-techniques-for-flawless-powerpoint-prints-in-windows/"><u>Solving the Puzzle: 9 Techniques for Flawless PowerPoint Prints in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/space-saving-savvy-master-windows-11s-minimalist-method/"><u>Space-Saving Savvy: Master Windows 11'S Minimalist Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-non-displaying-searches-in-win-1011-os/"><u>Strategies for Fixing Non-Displaying Searches in Win 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unreachable-mb-status-on-windows-11-systems/"><u>Tackling Unreachable MB Status on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-cmd-interface-a-step-by-step-process/"><u>Tailoring CMD Interface: A Step-by-Step Process</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-decreasing-audio-intensity-in-logic-pro-for-2024/"><u>The Art of Decreasing Audio Intensity in Logic Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-and-streamlining-the-microsoft-store-in-win11/"><u>Unblocking and Streamlining the Microsoft Store in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-efficiency-crafted-keybinds-for-snippet-pasting-in-windows-11/"><u>Unleashing Efficiency: Crafted Keybinds for Snippet Pasting in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Infinix Hot 40 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unlock-prime-deal-revealed/"><u>Windows 11 Unlock: Prime Deal Revealed</u></a></li>
</ul></div>
