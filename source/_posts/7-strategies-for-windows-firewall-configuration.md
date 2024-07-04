---
title: 7 Strategies for Windows Firewall Configuration
date: 2024-07-03T12:44:51.985Z
updated: 2024-07-04T12:44:51.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 7 Strategies for Windows Firewall Configuration
excerpt: This Article Describes 7 Strategies for Windows Firewall Configuration
keywords: WinFirewall Tips,SecureWindows Setup,Firewall Guard Steps,OptimizeWinSecurity,EnhanceWinGuard,WindowsFirewall Strategy,SafePC Networks
thumbnail: https://thmb.techidaily.com/9f88f4d439bd19afe08962ae532d3a6f41b689b2a4dc10b0fa384c3313d41768.jpg
---

## 7 Strategies for Windows Firewall Configuration

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

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
<li><a href="https://win11-tips.techidaily.com/guide-to-resetting-windows-11-applications/"><u>Guide to Resetting Windows 11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-in-use-files-errors-in-windows-152-chars/"><u>Addressing 'In-Use' Files Errors in Windows (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surreptitious-shutdown-strategy-for-windows-11/"><u>Surreptitious Shutdown Strategy for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-11-and-intel-unison-for-smooth-phone-integration/"><u>Leveraging Windows 11 & Intel Unison for Smooth Phone Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-upcoming-changes-with-windows-11-version-22h2/"><u>Delving Into Upcoming Changes with Windows 11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-app-experience-win11-color-automation/"><u>Tailoring Your App Experience: Win11 Color Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-non-crashy-windows-user-experience/"><u>Ensure Non-Crashy Windows User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-windows-screentime-intermission/"><u>A Comprehensible Window's Screentime Intermission</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-windows-error-code-0x80071a90/"><u>Understanding and Correcting Windows Error Code: 0X80071A90</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-tech-tips-streamlining-your-overwatch-video-recordings/"><u>2024 Approved  Tech Tips  Streamlining Your Overwatch Video Recordings</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-poco-c50-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-the-ultimate-guide-to-free-fb-downloaders/"><u>In 2024, The Ultimate Guide to Free FB Downloaders</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-how-to-change-your-phones-ringtone-picking-from-viral-tiktok-sounds/"><u>In 2024, How To Change Your Phone's Ringtone  Picking From Viral TikTok Sounds</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-convenient-way-to-mute-youtube-channels-on-pcmobile/"><u>[New] The Convenient Way to Mute Youtube Channels on PC/Mobile</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-videopad-video-editor-a-comprehensive-review-for-aspiring-filmmakers/"><u>Updated 2024 Approved Videopad Video Editor A Comprehensive Review for Aspiring Filmmakers</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-leading-stock-tutorials-channel-roundup/"><u>[New] 2024 Approved  Leading Stock Tutorials  Channel Roundup</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-put-iphone-15-pro-max-or-ipad-on-recovery-mode-step-by-step-tutorial-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Put iPhone 15 Pro Max or iPad on Recovery mode? (Step by Step Tutorial) | Stellar</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-unleashing-creativity-the-ultimate-guide-to-crafting-compelling-tiktok-captions/"><u>2024 Approved  Unleashing Creativity  The Ultimate Guide to Crafting Compelling TikTok Captions</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-mastering-fcp-5-essential-editing-tricks-to-elevate-your-workflow-for-2024/"><u>New Mastering FCP 5 Essential Editing Tricks to Elevate Your Workflow for 2024</u></a></li>
</ul></div>
