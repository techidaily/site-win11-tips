---
title: "Balancing Security & Usability: User Access Levels on Windows"
date: 2024-07-12T18:01:20.667Z
updated: 2024-07-13T18:01:20.667Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Balancing Security & Usability: User Access Levels on Windows"
excerpt: "This Article Describes Balancing Security & Usability: User Access Levels on Windows"
keywords: SecureUsabilityAccess,UXWindowsSecurityLvl,UsableAccessControlWin,BalancedUserPermissions,SecurityInUAWin,AccessLevelBalanceWin,UsageSecurityWindows
thumbnail: https://thmb.techidaily.com/302790bfdd6c387be2ce7104b2f0ec7045e52a09e036ffbf26a83ecf9455ec5e.jpg
---

## Balancing Security & Usability: User Access Levels on Windows

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/adjust-homescreen-links-without-changing-start-menu/"><u>Adjust Homescreen Links without Changing Start Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-in-a-chip-size-world/"><u>Best Windows in a Chip Size World</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitter-jokes-made-accessible-with-3-simple-steps-pc-for-2024/"><u>Twitter Jokes Made Accessible with 3 Simple Steps (PC) for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-11-pro-max-to-roku-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 11 Pro Max to Roku? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unveiling-the-secrets-of-color-mastery-11-tutorials/"><u>[Updated] Unveiling the Secrets of Color Mastery (11 Tutorials)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-health-through-interactive-device-tracking/"><u>Boost System Health Through Interactive Device Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-crashes-in-the-epic-launcher-for-win-users/"><u>Avoidance of Crashes in the Epic Launcher for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11s-temptations-top-8-cautions/"><u>Avoiding Windows 11'S Temptations: Top 8 Cautions</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-what-is-google-podcast-app/"><u>New In 2024, What Is Google Podcast App?</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-the-top-free-video-editors-for-avi-file-conversion/"><u>2024 Approved The Top Free Video Editors for AVI File Conversion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/gifs-that-speak-volumes-unveiling-6-critical-strategies-for-memetic-design-for-2024/"><u>GIFs That Speak Volumes  Unveiling 6 Critical Strategies for Memetic Design for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-strengthening-video-impact-with-professional-audio-cues/"><u>[Updated] Strengthening Video Impact with Professional Audio Cues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balance-performance-with-media-consumption-in-windows/"><u>Balance Performance with Media Consumption in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-bios-access-during-windows-initialization/"><u>Avoiding Unwanted BIOS Access During Windows Initialization</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-connectivity-boost-for-windows-11-webcams/"><u>Android Connectivity Boost for Windows 11 Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-real-time-performance-of-win-11-task-manager/"><u>Adjusting Real-Time Performance of Win 11 Task Manager</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/live-stream-on-youtube-using-zoom/"><u>Live Stream on YouTube Using Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-generated-windows-keys-unveiling-potential-perils/"><u>AI-Generated Windows Keys: Unveiling Potential Perils</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alleviating-resource-drain-by-ntoskrnlexe/"><u>Alleviating Resource Drain by Ntoskrnl.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjustment-assistants-best-windows-utilities-for-date-tweaking/"><u>Adjustment Assistants: Best Windows Utilities for Date Tweaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-soon-will-expire-warning-on-microsoft-os/"><u>Avoiding Soon Will Expire Warning on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-black-remote-desktop-display/"><u>Addressing Window's Black Remote Desktop Display</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tiktok-refresh-mishap-immediate-solutions-needed/"><u>TikTok Refresh Mishap  Immediate Solutions Needed</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-music-integrated-video-editing-software-top-picks-for-2024/"><u>Updated Music-Integrated Video Editing Software Top Picks for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/digital-duel-diaries-record-galaxy-gamer-stories/"><u>Digital Duel Diaries  Record Galaxy Gamer Stories</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/in-2024-whats-your-youtube-revenue-breakdown-per-branded-playlist/"><u>In 2024, What's Your Youtube Revenue Breakdown per Branded Playlist?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-unleash-the-power-of-fcpx-plugins-troubleshooting-and-fixing-common-issues/"><u>2024 Approved Unleash the Power of FCPX Plugins Troubleshooting and Fixing Common Issues</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-mastering-profit-on-facebook-essential-insights-and-hacks/"><u>[New] In 2024, Mastering Profit on Facebook  Essential Insights & Hacks</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-text-to-speech-excellence-on-discord-your-ultimate-manual/"><u>[New] In 2024, Text-To-Speech Excellence on Discord - Your Ultimate Manual</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-become-a-discord-conversation-maestro-expert-pinning-tips/"><u>[New] 2024 Approved  Become a Discord Conversation Maestro  Expert Pinning Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-boot-on-windows-sound-service-efficiency/"><u>Boosting Boot-On Windows Sound Service Efficiency</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/"><u>'Mirthful Missions' - Delving Into The Goofy Movie VHS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-security-incorporating-advanced-firewalls-in-the-context-menu/"><u>Augment Windows Security: Incorporating Advanced Firewalls in the Context Menu</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-9-tips-you-must-know-when-shooting-a-360-degree-video/"><u>2024 Approved  9 Tips You Must Know when Shooting a 360 Degree Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-speech-converter-transcribe-talk-with-whisper-in-windows/"><u>Become a Speech Converter: Transcribe Talk with Whisper in Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-activation-lock-on-iphone-6s-plus-or-ipad-by-drfone-ios/"><u>In 2024, How to Bypass Activation Lock on iPhone 6s Plus or iPad?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-media-mobility-in-apples-ecosystem/"><u>Mastering Media Mobility in Apple's Ecosystem</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-efficiently-access-your-facebook-lite-videos-with-these-top-apps-of-2023/"><u>[Updated] Efficiently Access Your Facebook Lite Videos with These Top Apps of 2023</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Reasons why Pokémon GPS does not Work On Apple iPhone 14 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-immediate-help-tool-on-windows-modern-os/"><u>Beginning Immediate Help Tool on Windows Modern OS</u></a></li>
<li><a href="https://discord-videos.techidaily.com/premier-font-generators-transforming-discord-channels/"><u>Premier Font Generators  Transforming Discord Channels</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-tecno-spark-10c-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Tecno Spark 10C FRP Android 10/11/12/13</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Nubia Z50 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-gaming-prowess-mastering-adventure-games-in-high-definition-hd/"><u>Boost Your Gaming Prowess: Mastering Adventure Games in High-Definition HD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-premature-edge-activation-in-w11/"><u>Avoid Premature Edge Activation in W11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-capture-the-essence-of-xiaomis-latest-smartphones/"><u>In 2024, Capture the Essence of Xiaomi's Latest Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advance-your-dev-workflow-with-wsl-2-best-practices-for-windows/"><u>Advance Your Dev Workflow with WSL 2 Best Practices for Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-charting-the-evolution-of-windows-movie-maker/"><u>[Updated] Charting the Evolution of Windows Movie Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-to-master-voice-activated-accessibility-on-windows/"><u>Advanced Techniques to Master Voice-Activated Accessibility on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-safety-wins-7-top-rated-zero-cost-pass-gen-software/"><u>Boost System Safety: Win's 7 Top Rated Zero-Cost Pass Gen Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-system-a-strategy-for-fixing-0x800700e9-in-xbox-game-passwindows-11/"><u>Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blue-screen-bane-11-tricks-for-windows-11/"><u>Beat the Blue Screen Bane: 11 Tricks for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-address-roblox-glitches/"><u>Approaches to Address Roblox Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-smooth-operations-for-11-windows-errors/"><u>Beat the Blues: Smooth Operations for 11 Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adobe-validation-skip-pop-ups-on-pc/"><u>Adobe Validation: Skip Pop-Ups on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-efficiency-the-ultimate-guide-to-wintools/"><u>Boost Windows Efficiency: The Ultimate Guide to Wintools</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-flv-editor-for-windows-8-professional-video-editing-made-easy/"><u>In 2024, Best FLV Editor for Windows 8 Professional Video Editing Made Easy</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>