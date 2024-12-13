---
title: "Windows Security Overhaul: Alteration of Ruleset"
date: 2024-12-12T02:45:36.368Z
updated: 2024-12-12T16:11:38.284Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-master-the-art-of-live-streaming-snapchat-videos/"><u>[New] 2024 Approved Master the Art of Live Streaming Snapchat Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-crafting-the-perfect-blend-in-minutes-with-picshot/"><u>[New] Crafting the Perfect Blend in Minutes with Picshot</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-maximize-your-library-a-comprehensive-list-of-online-mp3-tag-editor-powerhouses/"><u>2024 Approved Maximize Your Library A Comprehensive List of Online MP3 Tag Editor Powerhouses</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-guide-free-driver-software-for-optimal-functionality-of-your-hp-designjet-500/"><u>Complete Guide: Free Driver Software for Optimal Functionality of Your HP Designjet 500</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transforming-png-images-into-bmp-format-with-movavi/"><u>Free Online Converter: Transforming PNG Images Into BMP Format with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-para-cambiar-tu-fotografia-de-alta-calidad-dng-a-jpg-gratuito-usando-la-herramienta-en-linea-de-movavi/"><u>Guía Para Cambiar Tu Fotografía De Alta Calidad: DNG a JPG Gratuito Usando La Herramienta en Línea De Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-delete-a-specific-windows-bt-directory/"><u>How to Delete a Specific Windows ~BT Directory</u></a></li>
<li><a href="https://extra-resources.techidaily.com/luminous-android-videography-techniques/"><u>Luminous Android Videography Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/m4r-a-wav-sin-costo-el-poder-de-la-conversion-online-por-movavi/"><u>M4R a WAV Sin Costo: El Poder De La Conversión Online Por Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-flac-mp3/"><u>Movavi의 웹사이트에서 FLAC 파일을 MP3로 가용성 향상: 원격 무료 바이트 정렬과 전환</u></a></li>
<li><a href="https://article-helps.techidaily.com/navigating-the-top-10-ios-gif-apps-for-2024/"><u>Navigating the Top 10 iOS GIF Apps for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/premier-10-moba-titles-for-android-devotees/"><u>Premier 10 MOBA Titles for Android Devotees</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicktime-video-downsizing-made-simple-achieve-smaller-sizes-using-just-4-basic-tricks/"><u>QuickTime Video Downsizing Made Simple: Achieve Smaller Sizes Using Just 4 Basic Tricks</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-retailers-offering-discounts-on-ipad-pro-ipad-air-and-new-apple-pencil-pro-secure-your-early-bird-preorder-today/"><u>Top Retailers Offering Discounts on iPad Pro, iPad Air & New Apple Pencil Pro: Secure Your Early Bird Preorder Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wmv-online-mjpeg-converter/"><u>WMV 이미지/비디오를 자동화된 바이트 스트림으로 무료로 변환: Online MJPEG Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-ogg-movavi/"><u>웹 내 MP4 포맷터를 무료로 사용자가 사용하기 위해 OGG 형식으로 변환 - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-wmv/"><u>최선의 MP4, WMV 바인딩: 영상 변환에 대한 전문가 권장</u></a></li>
</ul></div>

