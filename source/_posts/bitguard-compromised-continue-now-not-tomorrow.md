---
title: "BitGuard Compromised: Continue Now, Not Tomorrow"
date: 2024-07-12T18:02:31.801Z
updated: 2024-07-13T18:02:31.801Z
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
<li><a href="https://win11-tips.techidaily.com/banish-errors-restore-mspm-on-vista/"><u>Banish Errors: Restore MSPM on Vista</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-elevate-your-audio-experience-top-5-voice-recorder-software-for-phones-and-tablets/"><u>New In 2024, Elevate Your Audio Experience Top 5 Voice Recorder Software for Phones and Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-capacity-securely-without-erasing-files/"><u>Boost Windows Capacity Securely without Erasing Files</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/stock-success-the-ultimate-list-of-channels/"><u>Stock Success  The Ultimate List of Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/atlasos-makeover-new-life-for-vintage-pcs/"><u>AtlasOS Makeover: New Life for Vintage PCs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-spotting-the-top-10-discreet-instagram-story-followers/"><u>[New] Spotting the Top 10 Discreet Instagram Story Followers</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-sony-xperia-10-v-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Sony Xperia 10 V is off? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-instant-folders-generation-hacks-for-windows-users/"><u>Boost Your Workflow: Instant Folders Generation Hacks for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-boundaries-artificinas-intelligence-in-windows-11/"><u>Beyond Boundaries: Artificinas Intelligence in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-your-windows-11-activation-status/"><u>Assessing Your Windows 11 Activation Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/arrow-key-calm-a-guide-for-win-users/"><u>Arrow Key Calm: A Guide for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-tremors-fixing-pointer-instability-in-windows/"><u>Avoid the Tremors: Fixing Pointer Instability in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjustments-for-a-seamless-integration-of-wsl-in-win-11/"><u>Adjustments for a Seamless Integration of WSL in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-upgrades-to-windows-11s-clipboard-history/"><u>Boosting Efficiency: Upgrades to Windows 11'S Clipboard History</u></a></li>
<li><a href="https://youtube-help.techidaily.com/from-blank-canvas-to-biggest-hit-mastering-youtube-thumbnail-sizes-for-2024/"><u>From Blank Canvas to Biggest Hit  Mastering YouTube Thumbnail Sizes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-overview-of-user-dissatisfaction-with-windows-11-upgrade/"><u>An Overview of User Dissatisfaction with Windows 11 Upgrade</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-ultimate-guide-testing-mycam-recording-capabilities/"><u>[New] 2024 Approved  Ultimate Guide  Testing MyCam Recording Capabilities</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-xiaomi-redmi-note-12r-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Xiaomi Redmi Note 12R Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-to-component-services-on-windows-11/"><u>Beginner’s Guide to Component Services on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apple-maps-integration-guide-for-windows-devices/"><u>Apple Maps Integration Guide for Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resources-windows-task-management/"><u>Balancing Resources: Windows Task Management</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unraveling-the-mechanics-auto-play-yourtube-videos-on-fb-platform/"><u>Unraveling the Mechanics  Auto-Play YourTube Videos on FB Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edges-app-guard-with-enhanced-graphics/"><u>Boosting Edge's App Guard with Enhanced Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-high-temperatures-in-windows-11-pcs/"><u>Avoiding High Temperatures in Windows 11 PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-infinix-by-fonelab-android-recover-music/"><u>How to retrieve erased music from Infinix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/antivirus-alert-7-significant-windows-functions-under-scrutiny/"><u>Antivirus Alert: 7 Significant Windows Functions Under Scrutiny</u></a></li>
<li><a href="https://extra-tips.techidaily.com/conceal-visages-with-confidence-using-these-select-apps/"><u>Conceal Visages with Confidence Using These Select Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-academic-achievement-winning-study-methods-on-a-windows-pc/"><u>Boost Academic Achievement: Winning Study Methods on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-power-visibility-customizing-full-charge-alerts-for-win11/"><u>Boost Power Visibility: Customizing Full Charge Alerts for Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-avoid-spending-discover-the-finest-free-mac-screen-recorders/"><u>In 2024, Avoid Spending  Discover the Finest Free Mac Screen Recorders</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-5-best-backwards-music-videos/"><u>New In 2024, 5 Best Backwards Music Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-srt-conversion-simplified-subtitles-transformation/"><u>[Updated] SRT Conversion Simplified  Subtitles Transformation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-lockout-interval-after-unsuccessful-windows-sign-in/"><u>Adjusting Lockout Interval After Unsuccessful Windows Sign In</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-shoot-video-with-virtual-green-screen-for-2024/"><u>Updated Shoot Video with Virtual Green Screen for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-introduction/"><u>2024 Approved  Introduction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tactics-for-superior-windows-navigation-eliminating-ls/"><u>Advanced Tactics for Superior Windows Navigation: Eliminating LS</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-sound-to-words-a-free-guide-to-youtube-transcribing-mastery-for-2024/"><u>[New] From Sound to Words  A FREE Guide to YouTube Transcribing Mastery for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>