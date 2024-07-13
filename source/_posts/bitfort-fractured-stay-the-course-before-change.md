---
title: "BitFort Fractured: Stay the Course Before Change"
date: 2024-07-12T16:52:58.301Z
updated: 2024-07-13T16:52:58.301Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-help.techidaily.com/2024-approved-guide-incorporating-youtube-videos-in-google-slides/"><u>2024 Approved  Guide  Incorporating YouTube Videos in Google Slides</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-honor-90-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Honor 90? Here is How | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-breaking-barriers-in-advertising-animating-for-maximum-roi-on-fb/"><u>[New] 2024 Approved  Breaking Barriers in Advertising  Animating for Maximum ROI on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-analysis-creating-and-interpreting-data/"><u>Navigating Windows Analysis: Creating & Interpreting Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-troubleshooting-tips-to-ease-team-communication-errors-on-w11/"><u>Transformative Troubleshooting Tips to Ease Team Communication Errors on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-laptop-or-desktop-windows-era/"><u>Unveiling Laptop or Desktop Windows Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-for-generating-flawless-ai-images-on-windows-11-through-paint-tool-sai/"><u>The Ultimate Guide for Generating Flawless AI Images on Windows 11 Through Paint Tool SAI</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-exit-recovery-mode-on-iphone-xr-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unraveling-free-filter-treasures-through-instagrams-advanced-searches-for-2024/"><u>[New] Unraveling Free Filter Treasures Through Instagram’s Advanced Searches for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-downloading-and-installing-windows-11-arm-from-iso/"><u>Step by Step: Downloading and Installing Windows 11 ARM From ISO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refining-windows-11-for-superior-usability/"><u>Refining Windows 11 for Superior Usability</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-do-you-want-to-add-subtitles-to-your-videos-efficiently-this-article-will-introduce-an-online-subtitle-editor-that-will-help-you-to-create-subtitles-for/"><u>New Do You Want to Add Subtitles to Your Videos Efficiently? This Article Will Introduce an Online Subtitle Editor that Will Help You to Create Subtitles for Your Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-navigation-tips-on-using-narrator-commands/"><u>Streamlining Windows Navigation: Tips on Using Narrator Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-0xc0000142-in-win7win8/"><u>Resolving Error 0XC0000142 in Win7/Win8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-overcoming-windows-onedrives-cant-add-now-error/"><u>Step-by-Step Guide: Overcoming Windows OneDrive's 'Can’t Add Now' Error</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/optimizing-screen-captures-expert-techniques-for-hp-laptops-for-2024/"><u>Optimizing Screen Captures  Expert Techniques for HP Laptops for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unleashing-potential-a-treasury-of-youtube-themes-for-channels/"><u>In 2024, Unleashing Potential  A Treasury of YouTube Themes for Channels</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/laughmaker-quick-meme-and-image-crafter/"><u>LaughMaker  Quick Meme & Image Crafter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-roblox-availability-tackling-windows-settings-issue/"><u>Unblocking Roblox Availability: Tackling Windows Settings Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-safe-mode-access/"><u>Step-by-Step Guide to Windows 11 Safe Mode Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-implement-without-obstacles-win11-version-22h2-update/"><u>Tactics to Implement Without Obstacles: Win11 Version 22H2 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-operational-amd-radeon-ssp-on-windows/"><u>Troubleshooting Non-Operational AMD Radeon SSP on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-unrivaled-public-domain-screenshots-and-video-tools-guide/"><u>[New] 2024 Approved  Unrivaled Public Domain Screenshots & Video Tools Guide</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/crafting-a-viral-narrative-on-social-media/"><u>Crafting a Viral Narrative on Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobes-secrets-ms-store-version-acquisition/"><u>Unlocking Adobe's Secrets: MS Store Version Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-pin-removal-functionality-in-windows-11-os/"><u>Restoring PIN Removal Functionality in Windows 11 OS</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-automate-playlist-retrieval-from-youtube-directly/"><u>In 2024, Automate Playlist Retrieval From YouTube Directly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-win1011-screen-glitches-with-ease/"><u>Quelling WIN10/11 Screen Glitches with Ease</u></a></li>
<li><a href="https://facebook.techidaily.com/paving-your-path-as-an-influential-voice/"><u>Paving Your Path as an Influential Voice</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unlock-video-insights-top-7-free-easy-to-use-tag-extraction-software-reviewed-for-2024/"><u>Unlock Video Insights  Top 7 Free, Easy-to-Use Tag Extraction Software Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-right-pace-for-your-cursor-how-to-turn-off-acceleration-win-11/"><u>The Right Pace for Your Cursor: How to Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-the-8-most-common-mistakes-for-beginners-to-skip/"><u>Navigating Windows 11: The 8 Most Common Mistakes for Beginners to Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swordsmans-secrets-tackle-windows-lag-in-star-wars-battlefront-2/"><u>Swift Swordsman's Secrets: Tackle Windows Lag in Star Wars Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategy-to-eradicate-error-0x80300024-on-pcs/"><u>Strategy to Eradicate Error 0X80300024 on PCs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-high-cash-content-creators/"><u>[Updated] 2024 Approved  High-Cash Content Creators</u></a></li>
<li><a href="https://extra-support.techidaily.com/sticky-visuals-at-a-glance-iphoneandroids-best-sticker-add-on-apps-for-2024/"><u>Sticky Visuals at a Glance – iPhone/Android's Best Sticker Add-On Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-for-outdated-pcs-on-their-way-to-windows-11/"><u>The Guide for Outdated PCs on Their Way to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-maximum-speed-for-your-digital-purchases-at-microsoft/"><u>Unlock Maximum Speed for Your Digital Purchases at Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-troubled-windows-11-calendars/"><u>Resetting Techniques for Troubled Windows 11 Calendars</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-bypassing-instagrams-video-roadblocks-effortlessly/"><u>[New] 2024 Approved  Bypassing Instagram's Video Roadblocks Effortlessly</u></a></li>
</ul></div>
