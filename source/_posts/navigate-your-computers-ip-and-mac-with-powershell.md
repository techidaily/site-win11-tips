---
title: Navigate Your Computer's IP and MAC with Powershell
date: 2024-07-12T17:20:27.932Z
updated: 2024-07-13T17:20:27.932Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate Your Computer's IP and MAC with Powershell
excerpt: This Article Describes Navigate Your Computer's IP and MAC with Powershell
keywords: PC IP Addressing,MAC Addressing Windows,PC PowerShell Commands,Find PC IP Address,Locate MAC Address,System Network Info,PowerShell Netconfig
thumbnail: https://thmb.techidaily.com/2cb259c465a86a9d87c2ab8ed232a243225880491ec4b7484688140a5b3e77f5.jpg
---

## Navigate Your Computer's IP and MAC with Powershell

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-master-the-art-of-ios-screen-recording/"><u>In 2024, Master the Art of iOS Screen Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failed-writable-operation-files-in-windows/"><u>Addressing Failed Writable Operation Files in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Xiaomi Redmi A2+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/concealing-taskview-in-window-11-taskbar-design/"><u>Concealing TaskView in Window 11 Taskbar Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-purpose-and-use-of-microsofts-phone-link-app/"><u>Deciphering the Purpose and Use of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-efficient-qr-codes-on-windows-systems/"><u>Unlocking Secrets: Efficient QR Codes on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-computer-experience-with-these-6-tools/"><u>Accelerate Your Computer Experience with These 6 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-hdr-on-windows-11-an-in-depth-explanation/"><u>Decoding HDR on Windows 11: An In-Depth Explanation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-intel-unison-for-convenient-windows-11-calls/"><u>Making the Most of Intel Unison for Convenient Windows 11 Calls</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-conquering-the-world-of-instagram-reels-tips-inside/"><u>[Updated] In 2024, Conquering the World of Instagram Reels – Tips Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-forth-invisible-5ghz-connections-with-these-fixes/"><u>Bring Forth Invisible 5GHz Connections with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-mac-locations-on-your-windows-11-system/"><u>Deciphering MAC Locations on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-secure-testing-solution-enabling-and-configuring-sandbox/"><u>Win 11'S Secure Testing Solution: Enabling and Configuring Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-enterprise-restricted-chromeedge-settings-on-desktop-pcs/"><u>Addressing Enterprise-Restricted Chrome/Edge Settings on Desktop PCs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-unveiling-vidmas-video-capturing-excellence/"><u>[New] 2024 Approved  Unveiling Vidma's Video Capturing Excellence</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-blueprint-for-stellar-tiktok-campaigns-and-social-media-conquests-for-2024/"><u>[Updated] Blueprint for Stellar TikTok Campaigns and Social Media Conquests for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/challenging-the-status-quo-embracing-individuality-in-restricted-settings/"><u>Challenging the Status Quo: Embracing Individuality in Restricted Settings</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-iphone-8-by-drfone-ios/"><u>How To Change Your Apple ID Password On your iPhone 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-unseen-resurrect-off-screen-windows-in-win1011/"><u>Unlock the Unseen: Resurrect Off-Screen Windows in Win10/11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/lullaby-videos-a-study-on-sleep-inducing-stories-for-2024/"><u>Lullaby Videos  A Study on Sleep-Inducing Stories for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-a-revenue-generating-online-presence/"><u>Crafting a Revenue-Generating Online Presence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-defusing-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Deciphering and Defusing Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-conquering-win-errors/"><u>The Ultimate Guide to Conquering Win Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-visual-fields-in-windows-systems/"><u>Altering Visual Fields in Windows Systems</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-strategies-in-tagging-and-titling-videos-for-success/"><u>2024 Approved  Strategies in Tagging and Titling Videos for Success</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-comparative-review-of-premium-streaming-services/"><u>2024 Approved  Comparative Review of Premium Streaming Services</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/best-5-solutions-on-how-to-add-emojis-to-iphone-for-2024/"><u>Best 5 Solutions on How to Add Emojis to iPhone for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-screencaptureelite-the-5-star-apeaksoft-evaluation/"><u>[New] 2024 Approved  ScreenCaptureElite – The 5-Star Apeaksoft Evaluation</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-nubia-z50-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Vivo Y36? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-integration-in-modern-windows-11/"><u>Telnet Integration in Modern Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-choosing-the-right-display-tvs-vs-projectors-in-a-4k-era/"><u>[Updated] Choosing the Right Display  TVs vs Projectors in a 4K Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-gap-for-sd-detectability-by-explore-window/"><u>Bridge Gap for SD Detectability by Explore Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-windows-11-pc-manager-tools-guide/"><u>Enhance Productivity: Windows 11 PC Manager Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-video-processing-on-windows-embrace-distributed-power-via-tdarr/"><u>Elevate Video Processing on Windows: Embrace Distributed Power via Tdarr</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-a-comprehensive-tutorial-changing-gender-in-social-media-images-for-2024/"><u>[New] A Comprehensive Tutorial  Changing Gender in Social Media Images for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sky-high-results-the-creme-de-la-liste-of-drone-editors/"><u>In 2024, Sky-High Results  The Crème De La Liste of Drone Editors</u></a></li>
<li><a href="https://ai-topics.techidaily.com/2024-approved-easy-tutorial-how-to-make-a-talking-cartoon-video-step-by-step/"><u>2024 Approved Easy Tutorial How To Make a Talking Cartoon Video Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-custom-keybinds-quick-paste-in-win-1011/"><u>Master Custom Keybinds: Quick Paste in Win 10/11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-boosting-your-channels-viewer-count-12-must-try-approaches/"><u>In 2024, Boosting Your Channel's Viewer Count - 12 Must-Try Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-reactivate-an-inactive-hotspot-in-windows-11/"><u>Guidelines to Reactivate an Inactive Hotspot in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-prime-practices-for-streaming-live-cricket-events/"><u>[Updated] Prime Practices for Streaming Live Cricket Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defender-cleanup-procedures-for-a-secure-and-streamlined-pc/"><u>Defender Cleanup Procedures for a Secure and Streamlined PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-buyers-guide-affordable-access-to-windows-11-vcs/"><u>A Buyer’s Guide: Affordable Access to Windows 11 VCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-for-alt-codes-failing-in-windows-60-characters/"><u>Effective Fixes for ALT Codes Failing in Windows (60 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-conflicts-for-print-job-success/"><u>Eradicating Conflicts for Print Job Success</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-video-creation-in-classroom-video-editing-tips-for-2024/"><u>[Updated] Video Creation in Classroom  Video Editing Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-failed-connectivity-issue-of-mb-in-windows-11/"><u>Addressing the Failed Connectivity Issue of MB in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/four-steps-for-pausing-windows-update/"><u>Four Steps for Pausing Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-cross-language-communication-with-windows-11-hotkeys/"><u>Accelerate Cross-Language Communication with Windows 11 Hotkeys</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-next-gen-gaming-the-best-oculus-players-uncovered/"><u>[Updated] 2024 Approved  Next-Gen Gaming  The Best Oculus Players Uncovered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-steps-to-correct-cannot-find-gpeditmsc-issue/"><u>Unveiling Steps to Correct Cannot Find Gpedit.msc Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-hidden-pin-removal-switch-in-windows-11/"><u>Unlocking Hidden Pin Removal Switch in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-navigating-instagrams-live-broadcasting/"><u>[New] In 2024, Navigating Instagram's Live Broadcasting</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-webinar-series-the-complete-guide-unpacked/"><u>New In 2024, Webinar Series The Complete Guide Unpacked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-e1-code-on-w10w11-systems/"><u>Eradicating Error E1 Code on W10/W11 Systems</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/innovative-apps-revolutionizing-video-talks/"><u>Innovative Apps Revolutionizing Video Talks</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-manual-for-mending-screen-size-issues-on-windows/"><u>A Step-by-Step Manual for Mending Screen Size Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-fn-key-operations-in-modern-windows-pcs/"><u>Decode FN Key Operations in Modern Windows PCs</u></a></li>
<li><a href="https://apple-account.techidaily.com/protecting-your-privacy-how-to-remove-apple-id-from-iphone-13-mini-by-drfone-ios/"><u>Protecting Your Privacy How To Remove Apple ID From iPhone 13 mini</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-epic-data-preservation-techniques/"><u>The Essentials of Epic Data Preservation Techniques</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-direct-to-streamer-duel-obs-vs-shadowtoolkit/"><u>[Updated] In 2024, Direct-to-Streamer Duel  OBS Vs. ShadowToolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-escape-the-slow-gpsvc-cycle/"><u>Expert Tips to Escape the Slow GPSVC Cycle</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pioneering-podcast-production-writing-and-examples-guide-for-2024/"><u>Pioneering Podcast Production  Writing & Examples Guide for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-11-easy-to-produce-vlog-projects-at-home/"><u>[Updated] 11 Easy-to-Produce Vlog Projects at Home</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-infinix-hot-30i-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Infinix Hot 30i FRP</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-end-screen-magic-free-templates-to-boost-video-appeal/"><u>[Updated] In 2024, End-Screen Magic  Free Templates to Boost Video Appeal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-repair-code-0xc00ce556-on-windows/"><u>Mastering Error Repair: Code 0xC00CE556 on WINDOWS</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-50-best-film-scores-an-assortment-for-every-video-format-and-theme/"><u>New 50 Best Film Scores An Assortment for Every Video Format and Theme</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-11-pro-without-swiping-up-6-ways-drfone-by-drfone-ios/"><u>How To Unlock iPhone 11 Pro Without Swiping Up? 6 Ways | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-sony-xperia-10-v-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Sony Xperia 10 V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-rapid-download-experience-at-ms-store/"><u>Tricks for Rapid Download Experience at MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-functionality-of-fn-keys-on-modern-pcs-windows-11/"><u>Configuring the Functionality of FN Keys on Modern PCs (Windows 11)</u></a></li>
</ul></div>
