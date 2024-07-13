---
title: Altering Privilege Levels for Non-Administrators on Windows OS
date: 2024-07-12T18:08:10.955Z
updated: 2024-07-13T18:08:10.955Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Privilege Levels for Non-Administrators on Windows OS
excerpt: This Article Describes Altering Privilege Levels for Non-Administrators on Windows OS
keywords: Admin Rights Limitation,Privilege Control Windows,NT User Privileges,Regular Account Security,Non-Admin Access,OS Permissions Restrict,Secure User Levels
thumbnail: https://thmb.techidaily.com/5350e79af12b414e304e4335d5b2d88e62b5e0973ecd1f3c8cd4da92e1845552.jpeg
---

## Altering Privilege Levels for Non-Administrators on Windows OS

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
<li><a href="https://some-techniques.techidaily.com/new-from-analog-archives-to-digital-epics-creating-videos-from-older-photographs/"><u>[New] From Analog Archives to Digital Epics  Creating Videos From Older Photographs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-recording-rapture-screensavers-review-march-2023-for-2024/"><u>[New] Recording Rapture  ScreenSavers Review – March 2023 for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/whispers-from-the-past-secrets-unveiled-in-age-old-texts-for-2024/"><u>Whispers From the Past  Secrets Unveiled in Age-Old Texts for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/step-by-step-refresh-microsoft-mouse-driver-on-windows/"><u>Step-by-Step: Refresh Microsoft Mouse Driver on Windows</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-unleashing-potential-the-best-anime-ideas-in-videos/"><u>[New] 2024 Approved  Unleashing Potential  The Best Anime Ideas in Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-the-default-display-on-task-manager-windows-11/"><u>Alter the Default Display on Task Manager (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-startup-efficiency-altering-boot-menu-delay/"><u>Boosting Startup Efficiency: Altering Boot Menu Delay</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-become-a-pro-at-mac-webcam-video-recording-in-5-steps/"><u>[New] In 2024, Become a Pro at Mac Webcam Video Recording in 5 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-special-612-unlimited-win10-life/"><u>Black Friday Special: $6.12, Unlimited Win10 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-size-upgrade-speed-downgrade/"><u>Blackview MiniPC: Size Upgrade, Speed Downgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-in-win11-with-custom-cmd-commands/"><u>Boosting Efficiency in Win11 with Custom Cmd Commands</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-expert-guide-3-ways-to-keep-track-of-live-discord-events/"><u>In 2024, Expert Guide  3 Ways to Keep Track of Live Discord Events</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-10-must-try-microphones-for-exceptional-asmr-sounds/"><u>[New] In 2024, 10 Must-Try Microphones for Exceptional ASMR Sounds</u></a></li>
<li><a href="https://unlock-android.techidaily.com/lock-your-infinix-smart-8-plus-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Infinix Smart 8 Plus Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-breathtaking-lyric-videos-made-easy-by-lyric-video-maker/"><u>[New] 2024 Approved  Breathtaking Lyric Videos Made Easy by Lyric Video Maker</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-infinix-zero-30-5g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Infinix Zero 30 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-output-the-best-apps-to-maximize-windows-efficiency/"><u>Boost Your Output: The Best Apps to Maximize Windows Efficiency</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-swift-remedies-to-hypervisor-bsos-in-winxose/"><u>Beat the Blues: Swift Remedies to Hypervisor BSOS in WINXOSE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-search-and-highlight-settings/"><u>Adjusting Your Window's Search and Highlight Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-guide-to-extend-windows-10-shutdown-duration/"><u>Advanced Guide to Extend Windows 10 Shutdown Duration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battle-bugs-tackling-skyrims-extension-failure/"><u>Battle Bugs: Tackling Skyrim's Extension Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-buffer-rates-to-minimize-lag-with-vlc/"><u>Adjusting Buffer Rates to Minimize Lag with VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-file-management-using-checkbox-for-selections-in-win11/"><u>Boost File Management: Using Checkbox for Selections in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-network-settings-a-guide-for-win11/"><u>Adjust Network Settings: A Guide for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-insights-with-resource-tracking-tiles/"><u>Boost System Insights with Resource Tracking Tiles</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-rapid-reverse-how-to-flip-your-stream-sides/"><u>[Updated] The Rapid Reverse  How to Flip Your Stream-Sides</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2023-guide-to-affordable-laptop-dvd-players-for-2024/"><u>[Updated] 2023 Guide to Affordable Laptop DVD Players for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-epic-battle-royale-thumbnails-done-fast/"><u>[Updated] Epic Battle Royale Thumbnails, Done Fast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-with-these-12-unneeded-windows-programs/"><u>Boost Performance with These 12 Unneeded Windows Programs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-navigating-the-digital-maze-to-save-snaps-from-social-media/"><u>[New] 2024 Approved  Navigating the Digital Maze to Save Snaps From Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unauthorized-profiles-on-pcs-win1011-guide/"><u>Addressing Unauthorized Profiles on PCs: Win10/11 Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-vivo-y02t-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Vivo Y02T Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-epic-viewership-winners-youtubes-ultimate-list/"><u>[New] 2024 Approved  Epic Viewership Winners  YouTube's Ultimate List</u></a></li>
<li><a href="https://extra-information.techidaily.com/flashing-lights-of-olympic-speed/"><u>Flashing Lights of Olympic Speed</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-realme-v30-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Realme V30 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-by-rebooting-windows-11-ram/"><u>Boost Performance by Rebooting Windows 11 RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11s-default-silent-camera-alert-setting/"><u>Altering Windows 11'S Default Silent Camera Alert Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-fn-key-behavior-for-efficiency/"><u>Altering Windows Fn Key Behavior for Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-cortana-microsofts-four-future-plans/"><u>Beyond Cortana: Microsoft's Four Future Plans</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/skip-past-fb-video-ads-effectively/"><u>Skip Past FB Video Ads Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/app-aesthetics-the-hidden-culprits-in-windows-11-performance-drop/"><u>App Aesthetics: The Hidden Culprits in Windows 11 Performance Drop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-excessive-cpu-demand-by-windows-extender/"><u>Avoiding Excessive CPU Demand by Windows Extender</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-discover-the-best-gaming-intro-software-top-10-picks-for-windows-and-mac-users-for-2024/"><u>Updated Discover the Best Gaming Intro Software Top 10 Picks for Windows and Mac Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-crashing-keep-your-file-explorer-fixed-in-windows-11/"><u>Avoid Crashing: Keep Your File Explorer Fixed in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-temp-in-windows-11-systems/"><u>Balancing CPU Temp in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-taskbar-performance-on-win11/"><u>Boosting Taskbar Performance on Win11</u></a></li>
<li><a href="https://fox-http.techidaily.com/10-best-lightroom-alternatives-free-and-paid/"><u>10 Best Lightroom Alternatives [Free & Paid]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-desktop-interactivity-the-widget-approach-in-win-11/"><u>Augmenting Desktop Interactivity: The Widget Approach in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tweak-the-mouse-pointer-accessibility-settings-on-windows-11/"><u>How to Tweak the Mouse Pointer Accessibility Settings on Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-unleash-creativity-transformative-techniques-with-snapchat-photos/"><u>In 2024, Unleash Creativity  Transformative Techniques with Snapchat Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-steam-authentication-setbacks-in-rust-for-windows-users/"><u>Avoiding Steam Authentication Setbacks in Rust for Windows Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-default-screen-saver-in-windows-11/"><u>Adjusting Default Screen Saver in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-past-erasing-defenders-track-of-security-efforts/"><u>Banish the Past: Erasing Defender’s Track of Security Efforts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-your-quake-experience-via-terminal/"><u>Beginning Your Quake Experience via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-file-disposal-in-windows-for-efficiency-gains/"><u>Automate File Disposal in Windows for Efficiency Gains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-crashes-on-windows-11-10/"><u>Avoiding Teamsters Crashes on Windows 11, 10</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-giggle-engine-for-the-internet/"><u>2024 Approved  Giggle Engine for the Internet</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirror-your-apple-iphone-15-pro-display-drfone-by-drfone-ios/"><u>How to Screen Mirror your Apple iPhone 15 Pro Display? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-insight-with-elevated-task-manager-access-on-win11/"><u>Boosting System Insight with Elevated Task Manager Access on Win11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/swift-remedies-to-rescue-your-windows-10-photos-app-for-2024/"><u>Swift Remedies to Rescue Your Windows 10 Photos App for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-xiaomi-redmi-k70-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Xiaomi Redmi K70? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-the-media-playback-windows-media-player/"><u>Beginning the Media Playback: Windows Media Player</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-preserve-audio-perfection-how-to-convert-video-to-mp3-without-quality-loss/"><u>2024 Approved Preserve Audio Perfection How to Convert Video to MP3 without Quality Loss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-in-windows-11/"><u>Boosting File Management in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificinas-intelligence-microsofts-innovative-ai-addition-to-windows-11-taskbar/"><u>Artificinas Intelligence: Microsoft’s Innovative AI Addition to Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-start-menu-efficiency-in-the-world-of-windows-11/"><u>Boost Your Start Menu Efficiency in the World of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-the-basics-excellent-replacements-for-windows-11-defaults/"><u>Beyond the Basics: Excellent Replacements for Windows 11 Defaults</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>