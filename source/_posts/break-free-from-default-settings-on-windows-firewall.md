---
title: Break Free From Default Settings on Windows Firewall
date: 2025-01-24T00:19:48.493Z
updated: 2025-01-25T01:14:27.125Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Break Free From Default Settings on Windows Firewall
excerpt: This Article Describes Break Free From Default Settings on Windows Firewall
keywords: Firewall Basics,Customize WinFirewall,Opt Out Defaults,Firewall Security,Advanced Firewall Control,Disable Default Rules,Enhance Firewall Settings
thumbnail: https://thmb.techidaily.com/9e9b99a6d9a89547d11f6e0d3b7ad397a8c45980a1b807a51ada942660956a43.jpg
---

## Break Free From Default Settings on Windows Firewall

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)

## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-taming-high-quality-streams-obs/"><u>[New] 2024 Approved Taming High-Quality Streams (OBS)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-share-smart-techniques-for-youtube-playlist-dispersal/"><u>[New] Share Smart Techniques for YouTube Playlist Dispersal</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-economic-estimation-funds-required-for-song-visualization/"><u>[Updated] In 2024, Economic Estimation Funds Required For Song Visualization</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-oneplus-ace-2v-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On OnePlus Ace 2V without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-no-sound-issue-from-connected-hardware-in-windows/"><u>Clearing Up No Sound Issue From Connected Hardware in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-pc-hardware-identifiers-in-windows-systems/"><u>Decoding PC Hardware Identifiers in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-and-starting-snipping-tool-with-ease/"><u>Finding and Starting Snipping Tool with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bring-back-your-pcs-bluetooth-in-windows-11-with-these-9-tips/"><u>How to Bring Back Your PC’s Bluetooth in Windows 11 with These 9 Tips</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-ace-2-pro-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Ace 2 Pro</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-excellent-macos-converters-top-5-picklist/"><u>In 2024, Excellent macOS Converters Top 5 Picklist</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-from-apple-iphone-se-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code From Apple iPhone SE in the Best Ways</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-lullaby-movies-assessment-and-overview/"><u>In 2024, Lullaby Movies Assessment & Overview</u></a></li>
<li><a href="https://win-exclusive.techidaily.com/mastering-video-editing-simple-techniques-for-incorporating-voiceovers-quickly-and-effectively/"><u>Mastering Video Editing: Simple Techniques for Incorporating Voiceovers Quickly and Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-persistent-windows-10-bsod-problems/"><u>Solutions for Persistent Windows 10 BSOD Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-overlapping-camera-usage-on-your-pc/"><u>Solving Overlapping Camera Usage on Your PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-guide-setting-up-the-videodevil-plug-in-on-kodi-version-19-matrix/"><u>Step-by-Step Guide: Setting Up the VideoDevil Plug-In on Kodi Version 19 Matrix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-zerodxgerror-in-windows-11/"><u>Strategies for Fixing ZeroDXGError in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insight-into-devhome-for-seamless-win11-experience/"><u>The Insight Into DevHome for Seamless Win11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-apps-for-windowsandroid/"><u>Top 8 Cross-Platform Apps for Windows/Android</u></a></li>
</ul></div>

