---
title: "Tackling DXGI Failure in Windows: Fix for Removed Devices"
date: 2024-07-12T17:09:22.726Z
updated: 2024-07-13T17:09:22.726Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling DXGI Failure in Windows: Fix for Removed Devices"
excerpt: "This Article Describes Tackling DXGI Failure in Windows: Fix for Removed Devices"
keywords: WinDXGIFailureFix,RemovedDeviceRepair,DeviceRecoverySolution,DXGIFailureHack,WindowsDevicesRestore,RemovedIDXGBugfix,DevicesSyncWindows
thumbnail: https://thmb.techidaily.com/c2e520b7fa2ea279c78f437762c6d9b1bb9afdd3b83c993e13cda25988d89dcf.png
---

## Tackling DXGI Failure in Windows: Fix for Removed Devices

 The DXGI\_ERROR\_DEVICE\_REMOVED error sometimes occurs when users try to start certain Windows games or when playing them. Players have reported this error to occur for games like FIFA 2022, Prepar3D, Need for Speed Rivals, Apex, and Crysis 3, among others. This DirectX error message says, “DirectX function ‘GetDeviceRemovedReason’ failed with DXGI\_ERROR\_DEVICE\_REMOVED.”

 Consequently, Windows games either don’t launch at all or crash with regularity because of the DXGI\_ERROR\_DEVICE\_REMOVED error. The error message highlights that something associated with your graphics card has gone wrong. As such, these potential resolutions can fix the DXGI\_ERROR\_DEVICE\_REMOVED error in Windows 10 and 11\.

## 1\. Modify the GraphicsDriver Registry Key

 Modifying the GraphicsDriver registry key is the most widely confirmed potential fix for the DXGI\_ERROR\_DEVICE\_REMOVED error. This resolution involves adding a TDR (Timeout Detection and Recovery) DWORD to the GraphicsDrivers key. Setting that DWORD to 0 disables TDR detection. You can apply this registry edit as follows:

1. Press **Win + S**, type **regedit** inside the search tool, and click **Registry Editor**.
2. Next, navigate to the GraphicsDrivers key at this registry location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
3. Right-click on **GraphicsDrivers** and select the context menu’s **New** and **DWORD** options.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-new-key-options.jpg)
4. Type in a **TdrLevel** title for the DWORD.
5. Double-click on **TdrLevel** to activate its **Value** box.
6. The DWORD’s value should already be set to zero by default. However, change that value to **0** if it’s not and click **OK**.  
![The TrdLevel DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/trdlevel-dword.jpg)
7. Now close Registry Editor, click **Start**, and select **Power** \> **Restart**.

 A few users also confirm deleting a TdrDelay QWORD in the same key can also work for fixing the DXGI\_ERROR\_DEVICE\_REMOVED error. If you can see a TdrDelay QWORD in the GraphicsDrivers key, try deleting it as well. To do so, right-click the **TdrDelay** QWORD and select **Delete**. Select **Yes** to confirm the erasure.

## 2\. Disable the Antialiasing Setting

 Antialiasing is a graphic setting that smoothens jagged lines when enabled. However, this graphical effect can sometimes cause crashing issues like the DXGI\_ERROR\_DEVICE\_REMOVED error. This is how you can turn off Antialiasing within the NVIDIA Control Panel:

1. Right-click on the NVIDIA logo in the system tray area and select **NVIDIA Control Panel**.  
![The NVIDIA Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-geforce-experience.jpg)
2. Click the **Manage 3D** settings navigation option within the sidebar.
3. Select NVIDIA Control Panel’s **Global Settings** tab.
4. Next, click the **Antialiasing – Mode** option and select **Off**.  
![The Antialising - Mode setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antialiasing.jpg)
5. Repeat the previous step for the **Antialiasing – Transparency**, **FXAA**, and **Gamma** correction options.
6. Then select **Apply** to set the new graphics options.

 You can also disable Antialiasing for AMD GPUs within the Radeon software. Check out our guide about [tweaking AMD Radeon settings](https://www.makeuseof.com/amd-radeon-settings-gaming-performance-windows/) for further details about how to turn off Antialiasing there.

## 3\. Turn Off the NVIDIA ShadowPlay (Overlay) Feature

 GeForce Experience’s ShadowPlay feature for game recording can place a notable burden on GPUs. So, we recommend that you turn that feature off for the sake of fixing the DXGI\_ERROR\_DEVICE\_REMOVED error if it’s enabled. You can turn off NVIDIA ShadowPlay in GeForce Experience like this:

1. To open GeForce Experience, right-click the NVIDIA system tray icon and select that software on the context menu.
2. Then click on the **cog** (Settings) button to access further options.  
![The Settings button in GeForce Experience.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/settings-button.jpg)
3. Toggle off the **In-Game Overlay** option.  
![The in-game overlay option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/in-game-overlay.jpg)
4. Exit the GeForce Experience software and try playing your games with ShadowPlay disabled.

## 4\. Turn Off the DLSS Graphics Setting

 Some players confirm disabling DLSS graphics settings in games fixes the DXGI\_ERROR\_DEVICE\_REMOVED error. If the affected game doesn’t always crash when you start it, try turning off its **DLSS** option. You can usually find that setting within a game’s video or graphics tab options.

![A DLSS option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dlss-option.jpg)

## 5\. Undo Overclocking

 Have you done any GPU or processor overclocking on your PC? If you have, that overclocking could have caused the DXGI\_ERROR\_DEVICE\_REMOVED error. Undo the overclocking with the software you applied it with. Or you can undo overclocking by [resetting the BIOS](https://www.makeuseof.com/tag/reset-bios-default-settings-computer/) (Basic Input Output System).

![MSI Afterburner homepage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/msi-afterburner.jpg)

## 6\. Run the DirectX Web Installer

 DXGI\_ERROR\_DEVICE\_REMOVED can occur because of DirectX issues. For example, some required DirectX components might be missing on your PC. You can address that by downloading and running the DirectX Web Installer like this:

1. Open this [DirectX download page](https://www.microsoft.com/en-us/download/details.aspx?id=35).
2. Click on the orange **Download** button to obtain a DirectX setup file.  
![The Download button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-button.jpg)
3. To view File Explorer, hold the **Windows** logo button and press **E**. Then open the folder containing the Microsoft DirectX End-User Runtime package.
4. Double-click **dxwebsetup.exe** to bring up an Installing Microsoft (R) DirectX (R) window.
5. Click **I accept the agreement** and **Next**.  
![I accept the agreement radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/i-accept-the-radio-button.jpg)
6. If you don’t want Bing Bar, uncheck the **Install the Bing Bar** option.
7. Select **Next** to install DirectX components.

## Try Some Generic Windows Fixes

 If nothing has worked yet, here are some generic fixes for GPU issues.

### Update the Graphics Driver for Your GPU

 The DXGI\_ERROR\_DEVICE\_REMOVED error message clearly says that this issue is often the result of a graphics driver crash. It also suggests users update their GPU graphics drivers to remedy the error. You can update your PC’s graphics driver with the methods covered in this guide to [updating a GPU’s driver in Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

### Cleanly Reinstall the Graphics Driver

 Cleanly reinstalling a graphics driver is a variation of the previous potential resolution for updating it. This involves completely uninstalling the current GPU driver and then installing the latest one. We recommend thoroughly uninstalling the graphics driver with the DDU software before installing the new one. You can apply this solution as covered in our [article about reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/).

![uninstall graphics drivers DDU](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-graphics-drivers-ddu.jpg)

##

### Run a Windows Memory Diagnostic Check

 Some users have said they needed to replace faulty RAM modules to resolve DXGI\_ERROR\_DEVICE\_REMOVED. So, try running a Windows Memory Diagnostic check if other resolutions here don’t work for you. Our guide to [resolving RAM issues with Windows Memory Diagnostic](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/) includes full instructions for utilizing that tool.

![The Windows Memory Diagnostic tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-windows-memory-diagnostic-tool.jpg)

 If that tool detects issues, removing the faulty RAM module from your PC will probably resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. However, you’ll still need enough RAM for the game. If removing RAM leaves insufficient system memory for the game, purchase and add a new RAM module to your PC.

## Enjoy Your Windows Games Again

 The potential fixes above have worked for many players who’ve needed to resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. That doesn’t necessarily mean they’re guaranteed fixes, but one will probably resolve that issue on your PC. Then you can play the Windows 11/10 games that error crashed without further issues.

 If the solutions above don’t resolve the DXGI\_ERROR\_DEVICE\_REMOVED error on your PC, there could be an issue with your graphics card. Persistent GPU crashing is one of the signs that it’s time to upgrade your graphics card.

 Consequently, Windows games either don’t launch at all or crash with regularity because of the DXGI\_ERROR\_DEVICE\_REMOVED error. The error message highlights that something associated with your graphics card has gone wrong. As such, these potential resolutions can fix the DXGI\_ERROR\_DEVICE\_REMOVED error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/addressing-the-hang-issue-dxgierrordevicehunk-on-windows/"><u>Addressing the Hang Issue: DXGI_ERROR_DEVICE_HUNK on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719366332809-trouble-at-clipcraft-unravel-fixes-today/"><u>Trouble at ClipCraft? Unravel Fixes Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-walkthrough-upgrading-surface-hardware/"><u>A Comprehensive Walkthrough: Upgrading Surface Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6plus-strategies-for-a-superior-windows-11-taskbar-use/"><u>6+ Strategies for a Superior Windows 11 Taskbar Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-symphony-of-sounds-taming-irq-noise/"><u>A Symphony of Sounds: Taming IRQ Noise</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-from-viewers-to-valuables-mastering-video-monetization-on-vimeo/"><u>In 2024, From Viewers to Valuables  Mastering Video Monetization on Vimeo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-common-failures-when-importing-iphones-to-windows/"><u>Addressing Common Failures When Importing iPhones to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-eradicating-d3d11-errors-in-w11-and-w10/"><u>A Step-by-Step Approach to Eradicating D3D11 Errors in W11 & W10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/joining-forces-in-video-marketing-on-youtube-for-2024/"><u>Joining Forces in Video Marketing on YouTube for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-ideal-replacements-for-obs-in-broadcasting-for-2024/"><u>[New] Ideal Replacements for OBS in Broadcasting for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-common-complaints-users-have-about-windows-11/"><u>5 Common Complaints Users Have About Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/non-fullscreen-displays-on-monitor-with-win10/"><u>Non-Fullscreen Displays on Monitor with Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-essential-tricks-for-a-better-windows-11-search/"><u>5 Essential Tricks for a Better Windows 11 Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-system-best-practices-for-dns-setup-in-windows-11/"><u>Accelerate Your System: Best Practices for DNS Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-microsoft-can-improve-phone-link-on-windows-11/"><u>7 Ways Microsoft Can Improve Phone Link on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-oppo-find-n3-flip-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Oppo Find N3 Flip Phone Network-Ready</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-reveal-the-vocalization-of-a-wolveshow/"><u>Updated In 2024, Reveal the Vocalization of a Wolveshow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380953369-swift-file-stewardship-streamlining-googledrive-and-dropbox-via-windows-c/"><u>Swift File Stewardship: Streamlining GoogleDrive & Dropbox via Windows C:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-dawn-for-windows-embracing-ai-innovations/"><u>A New Dawn for Windows: Embracing AI Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381156661-reactive-keys-reclaiming-shift-on-win/"><u>Reactive Keys: Reclaiming Shift on Win</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-from-apple-iphone-12-pro-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email From Apple iPhone 12 Pro? Heres the Best Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719357869666-quick-remedies-to-address-compatibility-issues-on-windows-xp/"><u>Quick Remedies to Address Compatibility Issues on Windows XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719383487316-overcoming-windows-obstacles-simple-effective-solutions/"><u>Overcoming Windows Obstacles: Simple, Effective Solutions!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266622683-rejuvenate-your-locked-shift-key-in-windows/"><u>Rejuvenate Your Locked Shift Key in Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-iphone-xr-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>Unlock iPhone XR With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-dance-away-stress-the-most-popular-country-tunes-tiktok-edition/"><u>[Updated] In 2024, Dance Away Stress  The Most Popular Country Tunes (TikTok Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-directx-update-problems-in-windows-os/"><u>Addressing DirectX Update Problems in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-easy-ways-to-improve-your-virtual-machine-performance-on-windows/"><u>6 Easy Ways to Improve Your Virtual Machine Performance on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/behind-the-colorscape-a-look-at-hps-z32-x-for-2024/"><u>Behind the Colorscape  A Look at HP’s Z32 X for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ingenious-ways-to-delete-a-drives-segmentation-in-windows/"><u>4 Ingenious Ways to Delete a Drive's Segmentation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-microsofts-administrative-default-configurations-in-windows-11/"><u>Addressing Microsoft's Administrative Default Configurations in Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/infinix-zero-30-5g-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Infinix Zero 30 5G Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-experience-classic-ps1-games-with-leading-emulators/"><u>In 2024, Experience Classic PS1 Games with Leading Emulators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-step-by-step-plan-msoffice-install-on-win11/"><u>A Complete Step-by-Step Plan: MSOffice Install on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382132283-boost-your-windows-screenshot-game-4-key-solutions/"><u>Boost Your Windows Screenshot Game: 4 Key Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-open-the-windows-internet-information-services-iis-manager/"><u>8 Ways to Open the Windows Internet Information Services (IIS) Manager</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-asmr-excellence-superior-performance-for-less-money/"><u>2024 Approved  ASMR Excellence  Superior Performance for Less Money</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-isdonedll-issue-on-w11-and-11x-systems/"><u>Addressing the ISDone.dll Issue on W11 & 11X Systems</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-xs-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone XS to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-how-to-record-video-on-google-hangouts/"><u>In 2024, How to Record Video on Google Hangouts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-lenovo-screenshots-made-quickly-and-easy/"><u>[New] In 2024, Lenovo Screenshots Made Quickly and Easy</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-capture-every-moment-essential-ways-for-google-meet-recordings/"><u>[Updated] In 2024, Capture Every Moment  Essential Ways for Google Meet Recordings</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/virtual-reality-camera-quest-wholl-win/"><u>Virtual Reality Camera Quest  Who'll Win?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-device-latency-error-x887a0006win11/"><u>Addressing the Device Latency Error X887A0006:Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-cortana-data-retrieval-for-windows-users/"><u>A Complete Walkthrough: Cortana Data Retrieval for Windows Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-oneplus-nord-n30-se-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your OnePlus Nord N30 SE Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-singers-dilemma-choosing-freedom-from-microphone-controls/"><u>A Singer's Dilemma: Choosing Freedom From Microphone Controls</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-crafting-a-hit-a-guide-to-making-popular-emote-videos-on-tiktok/"><u>[New] 2024 Approved  Crafting a Hit  A Guide to Making Popular Emote Videos on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-peak-performance-tweaking-amd-radeon-windows-settings/"><u>Achieve Peak Performance: Tweaking AMD Radeon Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-high-cpu-usage-dropbox-optimization-in-windows/"><u>Addressing High CPU Usage: Dropbox Optimization in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320814373-reclaim-control-of-freeze-shift-keys/"><u>Reclaim Control of Freeze Shift Keys.</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-expert-advice-for-capturing-evening-images/"><u>2024 Approved  Expert Advice for Capturing Evening Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-steps-pinpointing-policies-in-windows-environments/"><u>3 Steps: Pinpointing Policies in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-dimension-in-windows-11-understanding-the-role-of-copilot-key/"><u>A New Dimension in Windows 11: Understanding the Role of Copilot Key</u></a></li>
<li><a href="https://network-issues.techidaily.com/troubleshooting-absence-of-wi-fi-adapter-on-windows-11/"><u>Troubleshooting: Absence of Wi-Fi Adapter on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-make-windows-look-like-macos/"><u>5 Ways to Make Windows Look Like macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-a-missing-bluetooth-option-in-windows-11/"><u>9 Ways to Fix a Missing Bluetooth Option in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-lately-used-files-in-windows/"><u>A Step-by-Step Guide to Lately Used Files in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-optimizing-living-area-for-oculus-virtual-reality/"><u>In 2024, Optimizing Living Area for Oculus Virtual Reality</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-most-reliable-7-free-tools-to-extract-video-tags-on-youtube/"><u>[Updated] The Most Reliable 7 Free Tools to Extract Video Tags on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-power-up-window-10-and-11-with-keybinds/"><u>Accelerate Tasks: Power-Up Window 10 and 11 with Keybinds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-windows-iscsi-initiator/"><u>A Step-by-Step Guide to Using Windows iSCSI Initiator</u></a></li>
</ul></div>
