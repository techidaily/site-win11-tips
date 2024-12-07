---
title: Five Steps to Overhaul Firewall Settings on Windows
date: 2024-12-02T22:29:07.403Z
updated: 2024-12-06T18:09:53.521Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Five Steps to Overhaul Firewall Settings on Windows
excerpt: This Article Describes Five Steps to Overhaul Firewall Settings on Windows
keywords: Firewall Revamp Guide,Windows Firewall Update,Security Settings Renewal,Network Safety Enhancement,Firewall Configuration Boost,Secure Windows Guarding,Optimize Firewall Controls
thumbnail: https://thmb.techidaily.com/06b7f9bb308a2f230442ff554dbb6dddbc8b32cf4318fa7b79eedb41360cb388.jpg
---

## Five Steps to Overhaul Firewall Settings on Windows

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://techidaily.com/best-fixes-for-xiaomi-redmi-note-12t-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Xiaomi Redmi Note 12T Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-ms-teams-error-80080300-fixes-for-w11-users/"><u>Breaking Down MS Teams Error 80080300: Fixes for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-system-integration-windows-plus-kali-linux-setup/"><u>Conquering System Integration: Windows + Kali Linux Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-broken-enter-button-on-pc/"><u>Fixing Broken Enter Button on PC</u></a></li>
<li><a href="https://sound-issues.techidaily.com/full-diagnosis-and-treatment-for-beyond-the-wire-mic-troubleshooting/"><u>Full Diagnosis & Treatment for 'Beyond The Wire' Mic Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gaming-smoother-with-warhammer-40k-on-windows-no-more-stutters/"><u>Gaming Smoother with Warhammer 40K on Windows, No More Stutters</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-xiaomi-redmi-k70-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Xiaomi Redmi K70 FRP In 3 Different Ways</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-seamlessly-install-newest-kodi-version-on-your-windows-10-device-a-comprehensive-tutorial/"><u>How To Seamlessly Install Newest Kodi Version on Your Windows 10 Device - A Comprehensive Tutorial</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-passfab-apple-iphone-6s-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>In 2024, PassFab Apple iPhone 6s Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-science-of-storage-sizing-in-windows-through-powershell/"><u>Mastering the Science of Storage Sizing in Windows Through Powershell</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premium-picks-a-list-of-must-play-google-cardboard-vr-games-for-2024/"><u>Premium Picks A List of Must-Play Google Cardboard VR Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-missed-specification-alert-on-windows-11/"><u>Silence Missed Specification Alert on Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-truth-behind-chatgpt-jailbreak-failures-unveiling-7-critical-reasons/"><u>The Truth Behind ChatGPT Jailbreak Failures: Unveiling 7 Critical Reasons</u></a></li>
</ul></div>

