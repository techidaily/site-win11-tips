---
title: "Fractured Fortify: Forge On, Postpone Potential Upgrade"
date: 2024-08-28T01:15:41.572Z
updated: 2024-08-29T01:15:41.572Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fractured Fortify: Forge On, Postpone Potential Upgrade"
excerpt: "This Article Describes Fractured Fortify: Forge On, Postpone Potential Upgrade"
keywords: Forge on Upgrades,Delay Upgrade Risks,Strengthen Post-Upgrade,Enhance Fortification,Prioritize Software Updates,Fortify with Careful Planning,Upgrade Strategies Vital
thumbnail: https://thmb.techidaily.com/3dc1e13d990f9f4ed1b30979889fa15d157b3da05c97d832955a545581c7804d.jpg
---

## Fractured Fortify: Forge On, Postpone Potential Upgrade

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/1716069640306-new-capturing-screen-content-on-huawei-mate-10-20-and-p-series-phones-via-built-in-recorders-for-2024/"><u>[New] Capturing Screen Content on Huawei Mate 10, 20 & P-Series Phones via Built-In Recorders. For 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-discovering-windows-best-snipping-and-cropping-software/"><u>[New] In 2024, Discovering Windows' Best Snipping and Cropping Software</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-instagram-highlights-comprehensive-photography-tips/"><u>[New] Mastering Instagram Highlights  Comprehensive Photography Tips</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-affordable-online-education-hosting-on-youtube/"><u>[Updated] 2024 Approved  Affordable Online Education  Hosting on YouTube</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-streamlined-teaching-mastering-lecture-capture-on-mac-systems/"><u>[Updated] Streamlined Teaching  Mastering Lecture Capture on Mac Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-2023-guide-to-affordable-laptop-dvd-players/"><u>2024 Approved  2023 Guide to Affordable Laptop DVD Players</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-digging-into-the-data-top-10-twitvideos/"><u>2024 Approved  Digging Into the Data  Top 10 TwitVideos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-solutions-to-decipher-muted-facebook-videos/"><u>2024 Approved  Solutions to Decipher Muted Facebook Videos</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-realme-11-proplus-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-windows-smartscreen-filters-and-alerts/"><u>Configuring Windows' SmartScreen Filters and Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-tech-controlling-appbrowser/"><u>Decoding Windows Tech: Controlling App/Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-role-fixing-cmd-prompt-issues/"><u>Elevating Your Role: Fixing Cmd Prompt Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-elusive-gpeditmsc-on-your-pc/"><u>Essential Fixes for Elusive 'Gpedit.msc' On Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-fs-apps-crowd-picked-winners/"><u>Essential Windows FS Apps: Crowd-Picked Winners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-maximize-your-use-of-remote-connections-w11/"><u>Expert Tips: Maximize Your Use of Remote Connections W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixers-compendium-tackling-active-directory-printer-errors-on-win-1011/"><u>Fixer's Compendium: Tackling Active Directory Printer Errors on WIN 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-nonfunctional-windows-11-wireless-hotspot-issue/"><u>Fixing Nonfunctional Windows 11 Wireless Hotspot Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-spotify-autoplay-behavior-on-windows-pcs/"><u>Halt Spotify Autoplay Behavior on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-display-not-turning-on-when-booting-up-windows/"><u>How to Fix a Display Not Turning On When Booting Up Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-lsassexe-unable-to-locate-component-error-in-windows/"><u>How to Fix the lsass.exe Unable to Locate Component Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-apple-maps-on-a-windows-pc/"><u>How to Use Apple Maps on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-browsers-pasting-feature-across-pcs/"><u>Improving Browsers' Pasting Feature Across PCs</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-editors-playbook-for-social-media-stardom/"><u>In 2024, The Editor's Playbook for Social Media Stardom</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-role-of-non-verbal-communication-in-interviewing/"><u>In 2024, The Role of Non-Verbal Communication in Interviewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-omnipotent-options-in-windows-11/"><u>Incorporating Omnipotent Options in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-network-key-harmony-5-steps-for-windows-error-resolution/"><u>Mastering Network Key Harmony: 5 Steps for Windows Error Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-read-aloud-fix-restoring-speech-for-word-documents/"><u>Microsoft Read Aloud Fix: Restoring Speech for Word Documents</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/navigating-new-tech-trends-with-toms-hardware-experts/"><u>Navigating New Tech Trends with Tom's Hardware Experts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/next-gen-of-video-visionaries-for-2024/"><u>Next Gen of Video Visionaries for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/one-account-gpo-tailoring-in-the-modern-windows-environment-11-11/"><u>One-Account GPO Tailoring in the Modern Windows Environment (11, 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-cursor-lighting-with-windows-11-tips/"><u>Optimize Your Cursor Lighting with Windows 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-directive-not-empty-hurdle-insights-to-eradicate-error-0x80070091/"><u>Overcoming the Directive Not Empty Hurdle: Insights to Eradicate Error 0X80070091</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pc-awakening-guide-navigating-windows-8-revival-strategies/"><u>PC Awakening Guide: Navigating Windows' 8 Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-your-audio-screen-recordings-using-the-snipping-tool-max-156/"><u>Perfect Your Audio Screen Recordings Using the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-remedying-windows-11-package-complications/"><u>Quick Fixes: Remedying Windows 11 Package Complications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscovering-vanished-windows-6-techniques-for-win11/"><u>Rediscovering Vanished Windows: 6 Techniques for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-rearranged-keystrokes-in-operating-systems/"><u>Remedying Rearranged Keystrokes in Operating Systems</u></a></li>
<li><a href="https://fox-that.techidaily.com/reviving-iphone-volume-buttons-7-essential-repair-tips-you-must-try/"><u>Reviving iPhone Volume Buttons: 7 Essential Repair Tips You Must Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-windows-11-on-classics-utilizing-windows-to-go-and-rufus-guide/"><u>Running Windows 11 on Classics - Utilizing Windows To Go & Rufus Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-authentication-disabling-questions-on-windows-11-local-account/"><u>Silent Authentication: Disabling Questions on Windows 11 Local Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-excel-display-in-windows-notepad/"><u>Solutions for Excel Display in Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-in-windows-update-for-1011-os/"><u>Solving Error 0X80246007 in Windows Update for 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-multilingual-translation-the-power-of-windows-shortcut-hotkeys/"><u>Speedy Multilingual Translation: The Power of Windows Shortcut Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-snip-and-sketch-obstacles-to-perfectly-capture-entire-screen/"><u>Tackle Snip & Sketch Obstacles to Perfectly Capture Entire Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-gaps-within-explore-interface-elements/"><u>Tackling Gaps Within Explore Interface Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-low-adoption-rate-of-windows-11-seven-points/"><u>The Low Adoption Rate of Windows 11: Seven Points</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/tips-to-reduce-compression-artifacts-in-obs/"><u>Tips to Reduce Compression Artifacts in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-yuzus-performance-on-pcs/"><u>Turbocharging Yuzu's Performance on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-additional-options-with-the-widget-bar-in-windows-11/"><u>Unlocking Additional Options with the Widget Bar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-guide-differentiate-hdd-and-ssd/"><u>Windows Guide: Differentiate HDD and SSD</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/your-guide-to-the-best-cloud-storage-options-android-2024/"><u>Your Guide to the Best-Cloud Storage Options (Android, 2024)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>