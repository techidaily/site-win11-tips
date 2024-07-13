---
title: A Straightforward Approach to Discovering RAM in Windows
date: 2024-07-12T17:00:09.064Z
updated: 2024-07-13T17:00:09.064Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Straightforward Approach to Discovering RAM in Windows
excerpt: This Article Describes A Straightforward Approach to Discovering RAM in Windows
keywords: RAM Windows Search Guide,Windows Find RAM Memory,RAM Locator for PCs,Tracking System RAM Windows,Simple RAM Identify Windows,Discover Windows RAM Quickly,Find RAM in Windows Easy Way
thumbnail: https://thmb.techidaily.com/0f034b01e896bfeb1b76fcb002ff3f08bf8065e806075d9660abdc53bcbc29eb.jpg
---

## A Straightforward Approach to Discovering RAM in Windows

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
<li><a href="https://win11-tips.techidaily.com/tackling-directx-download-errors-on-windows/"><u>Tackling DirectX Download Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multilingual-mastery-harnessing-the-power-of-hotkey-translations-in-windows-11/"><u>Multilingual Mastery: Harnessing the Power of Hotkey Translations in Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-pinnacle-of-recording-quality-9-mic-devices-rated-best/"><u>[Updated] In 2024, Pinnacle of Recording Quality  9 Mic Devices Rated Best</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-first-time-filmmakers-guide-to-gear-selection-for-2024/"><u>The First-Time Filmmaker's Guide to Gear Selection for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-pc-protection-limiting-multiple-antiviruses/"><u>Optimal PC Protection: Limiting Multiple Antiviruses</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-pairing-b-clips-with-main-shots-for-2024/"><u>The Art of Pairing B-Clips with Main Shots for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-steam-gaming-glory-a-how-to-manual/"><u>Reviving Lost Steam Gaming Glory: A How-To Manual</u></a></li>
<li><a href="https://vp-tips.techidaily.com/evaluating-a-64gb-drive-writable-by-videos/"><u>Evaluating a 64GB Drive' Writable by Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-leading-edge-best-9-filter-tips-for-live-broadcasts/"><u>[Updated] Leading Edge  Best 9 Filter Tips for Live Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-virtual-memory-for-performance-gain/"><u>Revamping Virtual Memory for Performance Gain</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-keep-microsoft-teams-from-crashing-win11-win10/"><u>Tips to Keep Microsoft Teams From Crashing Win11, Win10</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-best-windows-10-screen-capture-software/"><u>[Updated] In 2024, Best Windows 10 Screen Capture Software</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-enhancing-youtube-content-via-finalcut-pro-techniques/"><u>[Updated] Enhancing YouTube Content via FinalCut Pro Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-win-11-with-confident-system-setup/"><u>Transitioning to Win 11 with Confident System Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-backups-to-original-win-standards/"><u>Tailoring Your Backups to Original Win Standards</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-oppo-k11-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Oppo K11 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-overhead-memory-usage-by-malware-detectors/"><u>Reducing Overhead Memory Usage by Malware Detectors</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, Top 11 Free Apps to Check IMEI on Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/underrated-yet-stunning-best-windows-11-themes/"><u>Underrated, Yet Stunning: Best Windows 11 Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-address-failed-lunar-client-startup-errors/"><u>Solutions to Address Failed Lunar Client Startup Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-your-w11-browser-by-altering-startup/"><u>Personalize Your W11 Browser by Altering Startup</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-password-on-your-iphone-6s-drfone-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID Password On your iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unwrapping-the-truth-behind-windows-error-code-0x80073d26/"><u>Unwrapping the Truth Behind Windows' Error Code 0X80073D26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-boot-up-a-guide-to-startup-service-management/"><u>Navigate Through Windows Boot-Up: A Guide to Startup Service Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-notes-no-downloads-windows-11-secrets/"><u>Take Notes, No Downloads: Windows 11 Secrets</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-say-goodbye-to-clutter-how-to-convert-dvds-to-digital-files/"><u>Updated 2024 Approved Say Goodbye to Clutter How to Convert DVDs to Digital Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-winexe-creation-from-batch-scripts/"><u>Unveiling WinEXE Creation From Batch Scripts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-failed-retrieval-error-with-geforce-x/"><u>Quick Fixes for Failed Retrieval Error with GeForce X</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-top-video-highlight-creators-desktop-and-mobile-options/"><u>New In 2024, Top Video Highlight Creators Desktop and Mobile Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-using-dark-theme-in-notepad/"><u>Understanding and Using Dark Theme in Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-sudden-device-disconnection-dxgi/"><u>Remedy for Sudden Device Disconnection (DXGI)</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-mac-vlc-trimming-made-easy-preserve-video-quality/"><u>2024 Approved Mac VLC Trimming Made Easy Preserve Video Quality</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-seamlessly-transition-media-formats-with-free-downloader/"><u>[Updated] In 2024, Seamlessly Transition Media Formats with Free Downloader</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-elevate-your-edits-the-2-way-filmora-method-to-top-tiktok-reactions/"><u>2024 Approved  Elevate Your Edits – The 2-Way Filmora Method to Top TikTok Reactions</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-system-of-apple-iphone-15-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of Apple iPhone 15 Pro? | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-how-to-draw-cartoons-step-by-step-with-this-guide/"><u>New 2024 Approved How to Draw Cartoons Step by Step with This Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-quest-preventing-crashes-on-your-pcs-platform/"><u>Securing Your Quest: Preventing Crashes on Your PC's Platform</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-trim-youtube-videos-like-a-pro/"><u>[New] In 2024, How to Trim YouTube Videos Like a Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-monitor-mastery-personalized-pixelation-per-system-screen/"><u>Multi-Monitor Mastery: Personalized Pixelation per System Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-web-pages-to-desktop-level-with-windows-guide/"><u>Taking Web Pages to Desktop Level with Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-windows-issue-file-explorer-failsafe-mode/"><u>Solve Windows Issue: File Explorer Failsafe Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-microsofts-windows-1111-shop-hurdle/"><u>Overcoming Microsoft's Windows 11/11 Shop Hurdle</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Nokia C02? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-depth-guide-to-simple-high-dynamic-range-for-2024/"><u>In-Depth Guide to Simple High Dynamic Range for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11-troubleshooters-for-optimal-performance/"><u>Realigning Windows 11 Troubleshooters for Optimal Performance</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveiling-premium-displays-the-ultimate-guide-for-xbox-s-series-x/"><u>2024 Approved  Unveiling Premium Displays  The Ultimate Guide for Xbox S Series X</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-metaverse-giggle-guide-generating-20plus-amusing-virtual-creations/"><u>2024 Approved  Metaverse Giggle Guide  Generating 20+ Amusing Virtual Creations</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-htc-u23-pro-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost HTC U23 Pro for Free? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unidentified-devices-on-windows-1011/"><u>Troubleshooting Unidentified Devices on Windows 10/11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-samsung-galaxy-a15-5g-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/from-zero-to-hero-on-instagram-top-5-tips-with-examples-from-elites/"><u>From Zero to Hero on Instagram  Top 5 Tips with Examples From Elites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-proxy-settings-glitch/"><u>Quick Fix for Windows Proxy Settings Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-zip-file-errors-a-win-11-remedy-plan/"><u>Overcoming Zip File Errors: A Win 11 Remedy Plan</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-curb-energy-drain-while-playing-games-on-pc/"><u>Strategies to Curb Energy Drain While Playing Games on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-for-windows-11s-0x8004def5-glitches/"><u>Swift Solutions for Windows 11'S 0X8004DEF5 Glitches</u></a></li>
</ul></div>
