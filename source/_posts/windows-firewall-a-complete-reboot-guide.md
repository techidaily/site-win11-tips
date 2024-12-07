---
title: "Windows Firewall: A Complete Reboot Guide"
date: 2024-12-04T20:01:05.661Z
updated: 2024-12-06T16:24:44.999Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Firewall: A Complete Reboot Guide"
excerpt: "This Article Describes Windows Firewall: A Complete Reboot Guide"
keywords: Windows Firewall Guide,Rebooting Firewall Tips,Security Settings Guide,Firewall Best Practices,Enhance PC Protection,Network Safety Instructions,Secure Firewall Strategies
thumbnail: https://thmb.techidaily.com/36f771b0e455ffd27a9b597a4a43e9338a94fa4efcb33fd8811a101c2c676422.png
---

## Windows Firewall: A Complete Reboot Guide

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-path-to-stunning-hdr-portraits/"><u>[New] The Ultimate Path to Stunning HDR Portraits</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-from-video-to-gif-seamless-process-for-vimeo-content/"><u>[Updated] From Video to GIF Seamless Process for Vimeo Content</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-how-to-relive-facebooks-yesteryears-instructions-for-digital-devices/"><u>[Updated] How to Relive Facebook's Yesteryears - Instructions for Digital Devices</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-perfect-timekeeping-a-guide-to-adding-timestamps-in-youtube-links/"><u>2024 Approved Perfect Timekeeping A Guide to Adding Timestamps in YouTube Links</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-win11s-color-changing-features/"><u>Configuring Win11's Color-Changing Features</u></a></li>
<li><a href="https://buynow-info.techidaily.com/differences-between-sonys-ps5-slim-model-and-full-sized-console/"><u>Differences Between Sony's PS5 Slim Model and Full-Sized Console</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-resolving-the-windows-0xc000012f-stop-error/"><u>Effortless Solutions: Resolving the Windows 0xC000012F Stop Error</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/effortless-steps-to-blur-distractions-in-google-meets/"><u>Effortless Steps to Blur Distractions in Google Meets</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-realme-c53-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Realme C53 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-protection-into-windows-11s-edge-browser/"><u>Integrating Advanced Protection Into Windows 11'S Edge Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-customized-windows-mixer-levels/"><u>Keeping Your Customized Windows Mixer Levels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-size-changes-using-your-computers-keys-to-resize-software-in-win11/"><u>Navigating Size Changes: Using Your Computer's Keys to Resize Software in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-disabled-windows-update-issue/"><u>Overcoming the Disabled Windows Update Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-0x80860010-application-overload-trouble/"><u>Overcoming Windows' 0X80860010 Application Overload Trouble</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-download-of-realtek-alc-audio-drivers-compatible-with-windows-11/"><u>Quick Download of Realtek ALC Audio Drivers Compatible with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screen-size-snafus-in-windows-how-to-correct-them/"><u>Screen Size Snafus in Windows: How to Correct Them</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-up-your-game-with-these-9-improvements-in-outlook-windows-edition/"><u>Step Up Your Game with These 9 Improvements in Outlook, Windows Edition</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-readiness-enabling-tpm-secure-boot-pre-upgrade/"><u>Windows 11 Readiness: Enabling TPM, Secure Boot Pre-Upgrade</u></a></li>
</ul></div>

