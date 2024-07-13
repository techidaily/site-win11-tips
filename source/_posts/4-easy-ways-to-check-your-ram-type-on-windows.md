---
title: 4 Easy Ways to Check Your RAM Type on Windows
date: 2024-07-12T17:56:29.774Z
updated: 2024-07-13T17:56:29.774Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Easy Ways to Check Your RAM Type on Windows
excerpt: This Article Describes 4 Easy Ways to Check Your RAM Type on Windows
keywords: RAM Check Guide Windows,Windows RAM Type Test,Learn RAM Identification,Windows RAM Verification,Find Windows RAM Type,Identify Windows RAM Model,Check RAM Type Windows
thumbnail: https://thmb.techidaily.com/4820926913a4a1263a46714c8a07c6721c528103224c7dceab692252cbf067a0.jpg
---

## 4 Easy Ways to Check Your RAM Type on Windows

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

## 1\. How to Check the RAM Type With Command Prompt

 The most straightforward to check the RAM type on your Windows PC is via Command Prompt. You can use this method even [if you're a beginner with the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/), as it only requires you to run a single command.

 Here's how you can check the RAM type on Windows using the Command Prompt:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. In the console, type the command mentioned below and press **Enter**.  
`wmic memorychip get devicelocator, memorytype`
4. Note down the code number under the **MemoryType** column.  
![Check Memory Type Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-command-prompt.jpg)

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/fixing-extract-to-temp-folder-error-1152-on-win/"><u>Fixing 'Extract to Temp Folder Error 1152' On Win</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-lace-footage-with-music-using-premiere-pro/"><u>[New] Lace Footage with Music Using Premiere Pro</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-ultimate-11-handy-apps-for-on-the-go-music-mixing/"><u>New In 2024, Ultimate 11 Handy Apps for On-the-Go Music Mixing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-unfreeze-steam-and-resume-gaming-on-windows-11/"><u>How To Swiftly Unfreeze Steam and Resume Gaming on Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-leading-digital-recorder-suites/"><u>2024 Approved  Leading Digital Recorder Suites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-activate-hyper-v-in-windows-11/"><u>Quick Guide to Activate Hyper-V in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-enhance-video-visibility-with-effective-thumbnail-scaling/"><u>[New] 2024 Approved  Enhance Video Visibility with Effective Thumbnail Scaling</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-creating-jpeg-on-png-image-files-from-the-video-you-recorded-with-a-smartphone-or-a-professional-video-camera-takes-only-a-few-moments-of-your-time-/"><u>Updated Creating JPEG on PNG Image Files From the Video You Recorded with a Smartphone or a Professional Video Camera Takes only a Few Moments of Your Time. Here Are some Best Video to Image Converters You Ca for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icloud-on-windows-common-fixes-for-download-problems/"><u>ICloud on Windows: Common Fixes for Download Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-identifying-devices-with-windows-tools/"><u>In-Depth Analysis: Identifying Devices with Windows Tools</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-image-illumination-the-essential-list-of-frame-enhancing-apps/"><u>2024 Approved  Image Illumination  The Essential List of Frame-Enhancing Apps</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-realme-note-50-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Realme Note 50</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-upgrading-old-pcs-to-22h2/"><u>Navigating New Horizons: Upgrading Old PCs to 22H2</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-motorola-moto-g23-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Motorola Moto G23 Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-unveiling-the-trailblazers-shaping-discords-visual-language/"><u>[Updated] 2024 Approved  Unveiling the Trailblazers Shaping Discord's Visual Language</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-elite-scripting-developing-a-countdown-mechanism-in-obs/"><u>In 2024, Elite Scripting  Developing a Countdown Mechanism in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-editing-text-via-snipping-tool/"><u>Expert Guide: Editing Text via Snipping Tool</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-rap-music-selection-for-beginners-how-to-select-beats-and-bases/"><u>New In 2024, Rap Music Selection for Beginners How to Select Beats and Bases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-automating-dns-client-service-configuration/"><u>Guide to Automating DNS Client Service Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-your-guide-to-windows-11-audio-control/"><u>Navigating with Ease: Your Guide to Windows 11 Audio Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-usb-connection-in-windows-11/"><u>Reestablishing USB Connection in Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-oneplus-nord-ce-3-lite-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from OnePlus Nord CE 3 Lite 5G Phones with/without a PC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-vivo-v27-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Vivo V27 Pro without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-admin-level-command-prompt-in-windows-11-pro/"><u>Initiating Admin-Level Command Prompt in Windows 11 Pro</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/polite-phrasing-a-step-towards-cultural-competence/"><u>Polite Phrasing: A Step Towards Cultural Competence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-zero-error-in-windows-sandbox-missing-hypervisor-solution/"><u>Fixing Zero Error in Windows Sandbox - Missing Hypervisor Solution</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-mastering-tiktoks-visuals-a-comprehensive-aspect-ratio-guide/"><u>In 2024, Mastering TikToks Visuals A Comprehensive Aspect Ratio Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-invalid-captcha-on-steam/"><u>Guide to Correcting Invalid CAPTCHA on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-the-top-6-win-tracking-software-choices/"><u>Propel Productivity: The Top 6 Win Tracking Software Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rearrange-screen-alignment-for-windows-users/"><u>Rearrange Screen Alignment for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-the-clipboard-in-windows-11-with-user-centric-features/"><u>Reimagining the Clipboard in Windows 11 with User-Centric Features</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Infinix Note 30 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-virtual-marketing-realms/"><u>Navigating Virtual Marketing Realms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/post-update-failure-navigating-disconnect-in-windows-discord/"><u>Post-Update Failure: Navigating Disconnect in Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fractured-fort-knox-continue-current-cybersecurity/"><u>Fractured Fort Knox? Continue Current Cybersecurity</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/mocroscreen-recording-ads/"><u>MocroScreen Recording Ads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/install-update-and-remove-with-precision-using-windows-package-manager/"><u>Install, Update & Remove with Precision Using Windows Package Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-virtual-memory-in-windows-11-for-maximum-performance/"><u>Fine-Tuning Virtual Memory in Windows 11 for Maximum Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-lost-window-pans-in-windows-11/"><u>Reconnecting Lost Window Pans in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-circumvent-ms-defender-block-on-other-av-tools/"><u>How to Circumvent MS Defender Block on Other AV Tools</u></a></li>
</ul></div>
