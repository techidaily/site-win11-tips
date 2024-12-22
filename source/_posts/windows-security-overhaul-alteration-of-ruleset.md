---
title: "Windows Security Overhaul: Alteration of Ruleset"
date: 2024-12-15T17:12:27.378Z
updated: 2024-12-22T03:33:18.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Security Overhaul: Alteration of Ruleset"
excerpt: "This Article Describes Windows Security Overhaul: Alteration of Ruleset"
keywords: Windows Security Update,Rule Set Revision,System Safety Overhaul,Cyber Guard Renewal,Secure OS Enhancement,Policy Change Notification,Threat Defense Overhaul
thumbnail: https://thmb.techidaily.com/4fad5dfb068fa17bd11d3278f05324268f19f0e4e3fba2cd6b2af2a6f5ad615e.jpg
---

## Windows Security Overhaul: Alteration of Ruleset

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-the-invisible-hand-mastering-windows-11s-media-imports/"><u>[Updated] 2024 Approved The Invisible Hand Mastering Windows 11'S Media Imports</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-writers-almanac-crafting-compelling-biographies-on-facebook/"><u>2024 Approved The Writer's Almanac Crafting Compelling Biographies on Facebook</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-understanding-the-edge-of-av1-in-video-encoding/"><u>2024 Approved Understanding the Edge of AV1 in Video Encoding</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-step-by-step-guide-to-desktop-image-fusion-for-2024/"><u>A Step-by-Step Guide to Desktop Image Fusion for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/defeat-diablo-immortal-pc-crashes-expert-tips-and-solutions-for-smooth-gaming/"><u>Defeat Diablo Immortal PC Crashes: Expert Tips and Solutions for Smooth Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-the-authorization-manager-in-windows-11/"><u>How to Open the Authorization Manager in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-y78plus-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Y78+</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ring-online-video-earnings-for-2024/"><u>Mastering Online Video Earnings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-key-choices-in-procuring-a-laptop-windows-style/"><u>Navigating Key Choices in Procuring a Laptop Windows Style</u></a></li>
<li><a href="https://some-techniques.techidaily.com/nvidia-streamlines-its-array-of-pc-software-offerings/"><u>NVIDIA Streamlines Its Array of PC Software Offerings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-obstacles-reinstate-mspm-in-windows-7/"><u>Overcome Obstacles: Reinstate MSPM in Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reduce-noise-simplifying-windows-11-shutdown/"><u>Reduce Noise: Simplifying Windows 11 Shutdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-headset-mic-connectivity-issues/"><u>Resolving Windows Headset Mic Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slow-sell-of-windows-11-why-users-prefer-the-oldie/"><u>Slow Sell of Windows 11: Why Users Prefer the Oldie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-reconnecting-malwarebytes-services-in-windows-11-os/"><u>Steps for Reconnecting Malwarebytes Services in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-arrange-bunched-up-taskbar-icons/"><u>Strategies to Arrange Bunched-Up Taskbar Icons</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-zte-nubia-z60-ultra-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On ZTE Nubia Z60 Ultra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-the-fix-for-security-snags/"><u>Unlocking Windows: The Fix for Security Snags</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-create-custom-avatars-with-these-free-online-face-generators/"><u>Updated In 2024, Create Custom Avatars with These Free Online Face Generators</u></a></li>
</ul></div>

