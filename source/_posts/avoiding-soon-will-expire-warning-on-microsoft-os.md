---
title: Avoiding Soon Will Expire Warning on Microsoft OS
date: 2024-07-12T18:00:48.343Z
updated: 2024-07-13T18:00:48.343Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoiding Soon Will Expire Warning on Microsoft OS
excerpt: This Article Describes Avoiding Soon Will Expire Warning on Microsoft OS
keywords: Expiring Windows Update,Preventing OS Deprecation,Avoid Soon-to-End Software,Secure Outdated Systems,Protect MS OS Updates,Delay OS Discontinuation,Guard Against End-of-Life Warnings
thumbnail: https://thmb.techidaily.com/a1972899444c7fd6c447adfaf7d10b9ab8c7ebd024be2fc74b2760fa4d84aacb.jpg
---

## Avoiding Soon Will Expire Warning on Microsoft OS

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

## Why Does the “Your Windows License Will Expire Soon” Error Appear?

 The "Your Windows license will expire soon" error message can occur due to several factors, and here are the most prevalent ones:

* **Windows license is invalid:** Using an unauthorized or pirated version of Windows is one of the most common reasons why you might encounter this error message.
* **Hardware changes:** Performing hardware changes, such as replacing the motherboard in your system, can also lead to activation errors on Windows.
* **Connectivity issues:** Your computer might fail to connect to the Key Management Service (KMS) server due to network-related issues, resulting in activation errors.
* **Corrupt Activation Token files:** The **Tokens.dat** file contains the activation information for your Windows installation. If this file becomes inaccessible for some reason, you may encounter the “Your Windows license will expire soon” error on Windows.  
![Your Windows License Will Expire Soon Error on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/your-windows-license-will-expire-soon-error-on-windows.jpg)

 Now that you are aware of the common causes of this error, let's now focus on the potential solutions to resolve it.

## 1\. Apply Some Preliminary Fixes

 Before you try any advanced troubleshooting tips, it’s a good idea to start with some basic fixes.

* **Restart Windows Explorer:** Temporary issues with the Windows Explorer process can sometimes trigger the “Your Windows license will expire soon” error on your PC. If it’s nothing major, you should be able to fix it by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Run the SFC Scan:** It’s possible that Microsoft is having trouble authenticating your Windows license due to corrupt or damaged system files. To repair these files, you can try [running the System File Checker (SFC) scan on your PC](https://www.makeuseof.com/system-file-checker-sfc-windows/).
* **Scan for Malware:** Another potential factor contributing to Windows activation issues is malware infection. To address this, you can try [scanning your PC for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Microsoft Defender.

## 2\. Run the Activation Troubleshooter

 Both Windows 10 and 11 offer various troubleshooters for addressing common system issues. In this case, you can take help from the Windows Activation troubleshooter to fix any issues that may have caused the “Your Windows license will expire soon” error on your PC.

 To run the Activation troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Activation**.
3. Click the **Troubleshooter** button.  
![Running the Windows Activation Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/running-the-windows-activation-troubleshooter-1.jpg)

 Wait for the troubleshooter to do its thing, and then check if it resolves the error.

## 3\. Find Your Product Key and Activate Windows

 Another thing you can do to fix this error is to find your product key using the ShowKeyPlus app and then attempt to activate Windows again. Several users on the forums reported fixing the error with this method. You can also give it a go.

1. [Download the ShowKeyPlus app](https://www.microsoft.com/store/productId/9PKVZCPRX9NV) from the Microsoft Store.
2. Open the ShowKeyPlus app using the search menu.
3. Note down the **OEM key** in the **Home** tab.  
![ShowKeyPlus App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/showkeyplus-app-on-windows.jpg)
4. Press **Win + I** to open the Settings app.
5. In the **System** tab, click on **Activation**.
6. Click the **Change** button next to **Change product key**.
7. Enter the **OEM key** noted earlier and click **Next**.
8. Click the **Activate** button to confirm.  
![Update Product Key on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/update-product-key-on-windows.jpg)

## 4\. Activate Windows Using Command Prompt

 If you are unable to activate Windows via the Settings app, you can try to activate it through the Command Prompt. To do so, make sure that your PC is connected to the internet, and then use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **cmd** in the box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type **slmgr /ato** in the console and press Enter.  
![Activate Windows via Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/activate-windows-via-command-prompt.jpg)

 Wait for Command Prompt to validate your product key. You will see a message confirming the outcome of the activation process, whether it was successful or not. If the activation is successful, you should not see the “Your Windows license will expire soon” error after this.

## 5\. Rebuild the Tokens.dat File

 Tokens.dat is a system file related to Windows activation and licensing. If this file somehow gets corrupted, Windows may have trouble verifying the authenticity of your license and trouble you with the “Your Windows license will expire soon” error.

 You can try rebuilding the Tokens.dat file on your PC to see if that fixes the error. Here are the steps for the same.

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Type the following commands one by one and press **Enter** after each.  
`net stop sppsvc  
cd %windir%\system32\spp\store\2.0  
ren tokens.dat tokens.bar  
net start sppsvc  
cscript.exe %windir%\system32\slmgr.vbs /rilc`

 Restart your computer after running the above commands and then check if you still get the “Your Windows license will expire soon” error on your PC.

## 6\. Reset the Licensing Status

 In case your Windows license is not genuine, there's a workaround to dismiss the “Your Windows license will expire soon” message. This workaround involves resetting the activation period and [hiding the Activate Windows watermark](https://www.makeuseof.com/tag/remove-activate-windows-10-watermark/) via Command Prompt. Here are the steps you can follow.

1. [Open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **slmgr /rearm** in the console and press **Enter**.
3. Restart your PC after running the command.  
![Reset the Activation Timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-activation-timer.jpg)

 It's worth noting that you can only utilize the above command a few times. Eventually, you will have to obtain a genuine Windows license to eliminate the error message permanently.

## Fixing the “Your Windows License Will Expire Soon” Error on Windows

 Since Microsoft limits access to various personalization and security features on systems with inactivated Windows licenses, it’s vital to troubleshoot errors like the “Your Windows license will expire soon”. One of the above fixes should help you resolve the error message on your Windows computer. However, if nothing works, you can consider reaching out to Microsoft tech support as a last resort.

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-nokia-150-2023-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Nokia 150 (2023) Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-photographing-windows-user-acknowledgments/"><u>Best Practices for Photographing Windows' User Acknowledgments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-docx-to-pdf-conversion-on-modern-windows/"><u>Advanced Tips for Docx-to-PDF Conversion on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-bonanza-get-your-deal-612-for-eternal-windows-10/"><u>Black Friday Bonanza: Get Your Deal - $6.12 for Eternal Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-plan-for-windows-users-when-bitlocker-isnt-an-option/"><u>Backup Plan for Windows Users When BitLocker Isn't an Option</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-eating-entertainment-tiktoks-top-culinary-shows/"><u>[Updated] Eating Entertainment  TikTok's Top Culinary Shows</u></a></li>
<li><a href="https://howto.techidaily.com/fix-oppo-find-n3-flip-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Oppo Find N3 Flip Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elite-channel-explorer-discover-prime-video-status-for-2024/"><u>Elite Channel Explorer  Discover Prime Video Status for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-pitfalls-with-microsoft-teams-how-to-conquer-error-80080300/"><u>Avoiding Pitfalls with Microsoft Teams: How to Conquer Error 80080300</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-stealth-tactics-eliminate-11s-search-icon/"><u>Advanced Stealth Tactics: Eliminate 11'S Search Icon</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hasty-hacks-for-enhancing-personal-movie-making/"><u>2024 Approved  Hasty Hacks for Enhancing Personal Movie Making</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-efficient-w11-microphone-use/"><u>Beginner's Guide: Efficient W11 Microphone Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-capture-for-underpowered-computers/"><u>Adjusting Windows Capture for Underpowered Computers</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-elevate-photo-fidelity-larger-not-lesser/"><u>2024 Approved  Elevate Photo Fidelity - Larger, Not Lesser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-windows-11-highlighted-icons-for-tidy-desktop/"><u>Banish Windows 11 Highlighted Icons for Tidy Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-lighter-browsing-options-best-in-class-for-ram-consumption/"><u>Assessing Lighter Browsing Options: Best in Class for RAM Consumption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-assistants-impact-on-windows-11-experience/"><u>AI Assistant's Impact on Windows 11 Experience</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-breaking-down-t-series-income-mechanism-on-youtube/"><u>In 2024, Breaking Down T-Series Income Mechanism on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-rename-made-easy-the-powerof-tools-guide/"><u>Batch-Rename Made Easy: The PowerOf Tools Guide</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-kapwing-tutorial-converting-videos-to-slow-motion-in-minutes/"><u>2024 Approved Kapwing Tutorial Converting Videos to Slow Motion in Minutes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-step-by-step-blueprint-crafting-engaging-youtube-content-via-windows-movie-maker/"><u>2024 Approved  Step-by-Step Blueprint  Crafting Engaging YouTube Content via Windows Movie Maker</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-navigating-frame-rate-control-for-optimal-viewing-on-snapchat-for-2024/"><u>[New] Navigating Frame Rate Control for Optimal Viewing on Snapchat for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Oppo A58 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-auto-lock-on-windows-tips-and-tricks/"><u>Avoiding Auto-Lock on Windows: Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-avenue-windows-11-disabling-tactics/"><u>Avoidance Avenue: Windows 11 Disabling Tactics</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-efficiency-boost-discover-the-top-5-youtube-shorteners/"><u>[Updated] Efficiency Boost  Discover the Top 5 YouTube Shorteners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-frustration-curing-win-error-1-in-minecraft/"><u>Avoiding Frustration: Curing Win Error 1 in Minecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminals-user-privilege-settings/"><u>Adjusting Windows Terminal's User Privilege Settings</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-unleash-your-creativity-top-apple-video-editing-apps/"><u>2024 Approved Unleash Your Creativity Top Apple Video Editing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-graphical-performance-in-windows-11s-safeguard-feature/"><u>Amplifying Graphical Performance in Windows 11'S Safeguard Feature</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-maintaining-continuous-connections-on-snapchat-tips-and-tricks/"><u>[Updated] Maintaining Continuous Connections on Snapchat  Tips & Tricks</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-reasons-for-unexpected-cut-off-in-imovie/"><u>[Updated] Reasons for Unexpected Cut-Off in iMovie</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-visionary-vistas-the-ultimate-list-of-motivating-ig-images/"><u>[Updated] In 2024, Visionary Vistas  The Ultimate List of Motivating IG Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-persistent-edge-shortcuts/"><u>Avoiding Persistent Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-functionality-and-visual-impact-of-win11-taskbar-icons/"><u>Boosting Functionality & Visual Impact of Win11 Taskbar Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-sfx-strategies-for-windows-11-users/"><u>Advanced SFX Strategies for Windows 11 Users</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unlocking-organic-growth-your-afb-playbook/"><u>In 2024, Unlocking Organic Growth  Your AFB Playbook</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-erase-your-tiktok-signatures-with-apps-on-devices/"><u>[Updated] In 2024, Erase Your TikTok Signatures with Apps on Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlock-cracked-staying-secure-yet-unmoved/"><u>BitLock Cracked: Staying Secure Yet Unmoved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-the-ultimate-guide-to-wpm-in-windows-11/"><u>Boost Your Workflow: The Ultimate Guide to WPM in Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/treaming-success-updated-youtube-revenue-policies/"><u>[New] Streaming Success  Updated YouTube Revenue Policies</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-audio-conversion-made-easy-top-12-software-solutions/"><u>Updated Audio Conversion Made Easy Top 12 Software Solutions</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aoemi-for-streamlined-file-management-on-two-independent-windows-systems/"><u>AOEMi for Streamlined File Management on Two Independent Windows Systems</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-driving-engagement-and-visibility-effective-strategies-for-fb-video-marketing/"><u>[Updated] 2024 Approved  Driving Engagement and Visibility  Effective Strategies for FB Video Marketing</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-fresh-installation-displays-fail-to-start/"><u>Addressing Windows' Fresh Installation: Displays Fail To Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11-start-menu-preferences/"><u>Altering Windows 11 Start Menu Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-creating-efficient-troubleshooter-tools-shortcuts/"><u>Boost Productivity: Creating Efficient Troubleshooter Tools Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-mouse-pointer-style-in-winxpvista7/"><u>Adjusting Mouse Pointer Style in WinXP/Vista/7</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-discover-the-best-video-trimmers-for-desktop-and-online-use-for-2024/"><u>New Discover the Best Video Trimmers for Desktop and Online Use for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-downtime-disaster-essential-steps-for-checking-windows-11-device-availability/"><u>Avoid Downtime Disaster: Essential Steps for Checking Windows 11 Device Availability</u></a></li>
<li><a href="https://activate-lock.techidaily.com/4-things-you-must-know-about-apple-iphone-13-pro-activation-lock-by-drfone-ios/"><u>4 Things You Must Know About Apple iPhone 13 Pro Activation Lock</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unlocking-the-secrets-to-successful-360-streaming-on-fb-for-2024/"><u>Unlocking the Secrets to Successful 360 Streaming on FB for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/memetic-flesh-eater-artist/"><u>Memetic Flesh Eater Artist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-strengths-of-win11-in-compare-with-macos/"><u>Analyzing the Strengths of Win11 in Compare with MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approach-to-reveal-hidden-drives-on-windows/"><u>Approach to Reveal Hidden Drives on Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/windows-11-the-ultimate-screen-grabber-collection/"><u>Windows 11  The Ultimate Screen Grabber Collection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-outputs-with-savvy-techniques/"><u>Amplify Windows 11 Outputs with Savvy Techniques</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-capturing-cultures-a-step-by-step-guide-for-aspiring-travel-vloggers-for-2024/"><u>[New] Capturing Cultures  A Step-by-Step Guide for Aspiring Travel Vloggers for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713942663900-4-ways-to-merge-mp4-and-mp3-for-2024/"><u>4 Ways to Merge MP4 and MP3 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-wows-endless-loop-fix-error-132-in-win-editions/"><u>Avoid WoW's Endless Loop: Fix Error 132 in Win Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insider-look-at-microsofts-revolutionary-copilot-tool/"><u>An Insider Look at Microsoft's Revolutionary Copilot Tool</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/selective-movie-tease-treasury/"><u>Selective Movie Tease Treasury</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-protection-with-new-firewall-add-ons-in-the-context-menu/"><u>Boost Windows 11 Protection with New Firewall Add-Ons in the Context Menu</u></a></li>
<li><a href="https://some-guidance.techidaily.com/uncover-ustream-plus-alternatives-for-2024/"><u>Uncover Ustream Plus Alternatives for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-moviemaster-for-macos-for-2024/"><u>New MovieMaster for macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-single-board-gadgets/"><u>Best Windows Single-Board Gadgets</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>