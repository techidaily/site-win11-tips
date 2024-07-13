---
title: "BitLock Cracked: Staying Secure Yet Unmoved"
date: 2024-07-12T18:00:37.283Z
updated: 2024-07-13T18:00:37.283Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes BitLock Cracked: Staying Secure Yet Unmoved"
excerpt: "This Article Describes BitLock Cracked: Staying Secure Yet Unmoved"
keywords: BitLock Hack,Security Breach,Unmovable Encryption,Stay Secure,Cracked Encryption,Data Safety,Anti-Hack Tech
thumbnail: https://thmb.techidaily.com/95f65ec843e39dc81b80b6ffcbfef45d788958cee2b82fb5803fb90b93482a66.jpg
---

## BitLock Cracked: Staying Secure Yet Unmoved

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
<li><a href="https://win11-tips.techidaily.com/avoiding-could-not-create-window-mmc-snapshot-issues/"><u>Avoiding 'Could Not Create' Window MMC Snapshot Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-adding-uninstall-shortcuts-to-windows-menu/"><u>Boosting Efficiency: Adding Uninstall Shortcuts to Windows Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-windows-11-highlighted-icons-for-tidy-desktop/"><u>Banish Windows 11 Highlighted Icons for Tidy Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-plan-for-windows-users-when-bitlocker-isnt-an-option/"><u>Backup Plan for Windows Users When BitLocker Isn't an Option</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-silence-problem-twitter-videos-lacking-sounds-for-2024/"><u>[New] Silence Problem  Twitter Videos Lacking Sounds for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-synergy-with-windows-os-paving-a-futuristic-path/"><u>AI Synergy with Windows OS: Paving a Futuristic Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-functionality-and-visual-impact-of-win11-taskbar-icons/"><u>Boosting Functionality & Visual Impact of Win11 Taskbar Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-sync-and-conquer-to-dot-and-ifttt/"><u>Automate, Sync, and Conquer: To-Dot & IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-errors-secure-your-onedrive-login-on-windows/"><u>Avoiding Errors: Secure Your OneDrive Login on Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-gionee-f3-prowithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Gionee F3 Prowith/without a PC</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-ultimate-seal-on-immersive-odyssey/"><u>[Updated] In 2024, Ultimate Seal on Immersive Odyssey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-graphical-performance-in-windows-11s-safeguard-feature/"><u>Amplifying Graphical Performance in Windows 11'S Safeguard Feature</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enhancing-your-podcast-experience-the-art-of-editing-in-garageband/"><u>Enhancing Your Podcast Experience  The Art of Editing in GarageBand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-print-output-in-seconds-fix-windows-printer/"><u>Boost Print Output in Seconds, Fix Windows Printer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprints-for-crafting-safe-dialog-box-for-hardware-disconnect/"><u>Blueprints for Crafting Safe Dialog Box for Hardware Disconnect</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reverse-screen-alignment-in-windows-10-issue-fixed/"><u>Reverse Screen Alignment in Windows 10: Issue Fixed</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-twist-your-content-strategy-inverting-videos-for-instagram/"><u>[New] Twist Your Content Strategy  Inverting Videos for Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-the-ultimate-guide-to-wpm-in-windows-11/"><u>Boost Your Workflow: The Ultimate Guide to WPM in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-windows-11s-next-chapter/"><u>AI Integration: Windows 11'S Next Chapter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-mastering-windows-11-efficiency/"><u>Boost Your System: Mastering Windows 11 Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-overview-of-the-windows-canary-security-feature/"><u>An Overview of the Windows Canary Security Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-creating-efficient-troubleshooter-tools-shortcuts/"><u>Boost Productivity: Creating Efficient Troubleshooter Tools Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approach-to-reveal-hidden-drives-on-windows/"><u>Approach to Reveal Hidden Drives on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-pitfalls-with-microsoft-teams-how-to-conquer-error-80080300/"><u>Avoiding Pitfalls with Microsoft Teams: How to Conquer Error 80080300</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-rename-made-easy-the-powerof-tools-guide/"><u>Batch-Rename Made Easy: The PowerOf Tools Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-on-unlocking-apple-iphone-7-plus-with-a-broken-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide on Unlocking Apple iPhone 7 Plus with a Broken Screen? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-windows-cab-and-its-functionality/"><u>An In-Depth Look at Windows CAB and Its Functionality</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/unleashing-creativity-a-tiktok-video-guide-for-devices/"><u>Unleashing Creativity  A TikTok Video Guide for Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-wows-endless-loop-fix-error-132-in-win-editions/"><u>Avoid WoW's Endless Loop: Fix Error 132 in Win Editions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fiendish-film-pause-techniques/"><u>2024 Approved  Fiendish Film Pause Techniques</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-streamlined-process-to-download-parts-from-youtube-videos/"><u>[New] Streamlined Process to Download Parts From YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-game-breaking-disconnections-fall-guys-windows-fixes/"><u>Avoid Game-Breaking Disconnections: Fall Guys Windows Fixes</u></a></li>
<li><a href="https://extra-information.techidaily.com/sky-high-creations-professional-tips-for-drone-video-mastery/"><u>Sky High Creations  Professional Tips for Drone Video Mastery</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-financial-anatomy-of-youtube-shorts-money-splitting/"><u>[New] The Financial Anatomy of YouTube Shorts Money Splitting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-protection-with-new-firewall-add-ons-in-the-context-menu/"><u>Boost Windows 11 Protection with New Firewall Add-Ons in the Context Menu</u></a></li>
<li><a href="https://youtube-web.techidaily.com/tects-crafting-fantasy-realms-for-marvel-for-2024/"><u>Architects Crafting Fantasy Realms for Marvel for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-capture-for-underpowered-computers/"><u>Adjusting Windows Capture for Underpowered Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-setting-up-shortcuts-for-windows-troubleshooters/"><u>Boost Efficiency: Setting Up Shortcuts for Windows Troubleshooters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-call-productivity-on-windows-11-with-the-intel-unison-app/"><u>Boosting Call Productivity on Windows 11 with the Intel Unison App</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-turbo-techniques-for-faster-vimeo-views/"><u>[Updated] 2024 Approved  Turbo Techniques for Faster Vimeo Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-window-placement-for-windows-users/"><u>Adjust Window Placement for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-efficient-w11-microphone-use/"><u>Beginner's Guide: Efficient W11 Microphone Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-abrupt-termination-of-wow-error-132-on-win11/"><u>Banishing The Abrupt Termination of WoW (Error 132) on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-lighter-browsing-options-best-in-class-for-ram-consumption/"><u>Assessing Lighter Browsing Options: Best in Class for RAM Consumption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-auto-lock-on-windows-tips-and-tricks/"><u>Avoiding Auto-Lock on Windows: Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-assistants-impact-on-windows-11-experience/"><u>AI Assistant's Impact on Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-bonanza-get-your-deal-612-for-eternal-windows-10/"><u>Black Friday Bonanza: Get Your Deal - $6.12 for Eternal Windows 10</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-oppo-a1-5g-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Oppo A1 5G with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-outputs-with-savvy-techniques/"><u>Amplify Windows 11 Outputs with Savvy Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-fun-integrating-games-into-windows-11-through-google-play/"><u>Android Fun: Integrating Games Into Windows 11 Through Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bolstering-bygone-directx-games-with-cutting-edge-dxvk-features/"><u>Bolstering Bygone DirectX Games with Cutting-Edge DXVK Features</u></a></li>
<li><a href="https://fox-http.techidaily.com/globalscreen-top-ranked-local-and-live-tv-streams-for-2024/"><u>GlobalScreen  Top-Ranked Local & Live TV Streams for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-sfx-strategies-for-windows-11-users/"><u>Advanced SFX Strategies for Windows 11 Users</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-different-methods-to-unlock-your-iphone-x-by-drfone-ios/"><u>In 2024, Different Methods To Unlock Your iPhone X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminals-user-privilege-settings/"><u>Adjusting Windows Terminal's User Privilege Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unintended-read-only-file-states-in-windows-11/"><u>Avoiding Unintended Read-Only File States in Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>