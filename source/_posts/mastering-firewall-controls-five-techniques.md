---
title: "Mastering Firewall Controls: Five Techniques"
date: 2024-12-20T07:59:45.079Z
updated: 2024-12-21T17:38:19.579Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Firewall Controls: Five Techniques"
excerpt: "This Article Describes Mastering Firewall Controls: Five Techniques"
keywords: Firewall Mastery,Firewall Controls Tips,Secure Network Defense,Firewalls Technique Guide,Advanced Firewall Use,Firewall Security Methods,Effective Firewall Strategies
thumbnail: https://thmb.techidaily.com/81c104f653fc6628652d6140a521e94570f22aa2499ea9263be6a00f18fb658c.jpg
---

## Mastering Firewall Controls: Five Techniques

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-hovers.techidaily.com/updated-innovative-prime-lenses-for-top-tier-film-projects/"><u>[Updated] Innovative Prime Lenses for Top-Tier Film Projects</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-the-blueprint-of-film-narrative-for-2024/"><u>[Updated] The Blueprint of Film Narrative for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-fixing-error-0x8007045d-in-win-os/"><u>Deciphering and Fixing Error 0X8007045D in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-linux-growth-via-wsl/"><u>Exploring Linux Growth via WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-ea-origin-games-not-launching-on-steam-for-windows/"><u>How to Fix EA Origin Games Not Launching on Steam for Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-nokia-c32-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Nokia C32 to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-oppo-reno-10-proplus-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from Oppo Reno 10 Pro+ 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-use-phone-clone-to-migrate-your-vivo-v29-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Use Phone Clone to Migrate Your Vivo V29 Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-windows-gpeditmsc-unavailability-quickly/"><u>Overcome Windows Gpedit.msc Unavailability Quickly</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/overcoming-ksuserdll-errors-fixes-for-when-the-file-isnt-found-or-is-missing/"><u>Overcoming Ksuser.dll Errors: Fixes for When the File Isn’t Found or Is Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-dxgi-device-freeze-in-win1011/"><u>Steps to Eliminate DXGI Device Freeze in Win10/11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-new-e-learning-standard-mondlys-german-linguistic-sovereignty/"><u>The New E-Learning Standard: Mondly’s German Linguistic Sovereignty</u></a></li>
</ul></div>

