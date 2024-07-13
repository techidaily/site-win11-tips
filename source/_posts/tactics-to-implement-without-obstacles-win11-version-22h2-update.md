---
title: "Tactics to Implement Without Obstacles: Win11 Version 22H2 Update"
date: 2024-07-12T17:31:12.237Z
updated: 2024-07-13T17:31:12.237Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tactics to Implement Without Obstacles: Win11 Version 22H2 Update"
excerpt: "This Article Describes Tactics to Implement Without Obstacles: Win11 Version 22H2 Update"
keywords: Win11 Update Guide,Upgrade Win11 Smoothly,No-Obstacle Win11 Fixes,Easy Win11 Latest Patch,Win11 Version Update Tips,Hassle-Free Win11 Update 22H2,Secure Win11 H2 Upgrade Methods
thumbnail: https://thmb.techidaily.com/07d8502ce17333e6cd775d39369b0980ba5462f8a32cd1145e8a4d708fb6bf52.png
---

## Tactics to Implement Without Obstacles: Win11 Version 22H2 Update

 Microsoft released its first Windows 11 build version update in September 2022\. The 22H2 update has added a slew of new Windows 11 features and options. Many users are now installing that update via Settings.

 However, some users have reported in forums that they can’t upgrade Windows 11 to the 22H2 version. Those users have said that updates get stuck at percentage marks when they try to download and install them from Settings. Some users see error codes like 0x800f0806 for that update. This is how you can fix the Windows 11 22H2 update not installing.

## 1\. Run Windows 11’s Troubleshooter for Updates

 The Windows Update troubleshooter is there to check for and resolve issues with the update process. That troubleshooter isn’t guaranteed to fix all update errors, but it might fix Windows 11’s 22H2 update not installing for some users at least. You can run the Windows Update troubleshooter in the following steps:

1. Press**Win** +**I** to open**Settings** .
2. Select the**System** tab’s**Troubleshoot** option.
3. Click**Other trouble-shooters** to reach the troubleshooting utilities.
4. Select**Run** for the Windows Update troubleshooter.  
![The Run button for Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-run-button-for-windows-update-1.jpg)
5. Wait for the troubleshooter to detect issues and display an outcome. It will usually automatically apply fixes for detected issues.

## 2\. Disconnect Non-Essential External Hardware and Peripherals From PC

 It's recommended that users unplug non-essential hardware from PCs before attempting to upgrade to a new Windows 11 version. Doing so will ensure that there aren't any non-essential hardware devices that can potentially interrupt or conflict with the upgrade process. You'll still need your mouse and keyboard of course, but disconnect all the following non-essential peripherals:

* Headphones
* External storage drives
* Printers
* Scanners
* Speakers (they're not essential)
* Gamepads
* USB Hubs
* Webcams
* Microphones
* Secondary monitors (you only need one)

## 3\. Run a System File and Deployment Image Scan

 System file corruption can cause Windows update errors to arise. You can check for and remedy corrupted files by running a System File Checker scan in the Command Prompt. It’s also recommended to run a Deployment Image Servicing and Management scan to check the system image before that. This is how to run both scanning tools in Windows 11.

1. Open the file search tool with the**Windows** +**S** hotkey.
2. Search for Command Prompt by inputting**cmd** in the text box.
3. Right-click Command Prompt inside the search tool’s results to select a**Run as administrator** option.
4. Start by inputting this command and pressing**Enter** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Then run the SFC tool by typing in the following command and pressing**Return** :  
`sfc /scannow`
6. Wait for the SFC scan to show an outcome message in the Command Prompt.

## 4\. Free Up Some Drive Storage Space

 You’ll need at least 64 gigabytes of drive storage space available for the Windows 11 22H2 update. So, check your hard drive has enough space for the 22H2 update before installing it.

 If it doesn’t, free up the required drive storage space for the update by erasing superfluous files and uninstalling Windows software. Check out our [Cleanup recommendations guide](https://www.makeuseof.com/free-storage-space-with-cleanup-recommendations/) for further details about how to create storage space via Settings.

![Cleanup recommendations in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/cleanup-recommendations-1.jpg)

## 5\. Check If the Dependency Services for Windows Update are Enabled

 The Windows Update service has some service dependencies that need to be enabled and running. Windows 11 22H2 update issues will likely arise if necessary prerequisite services are disabled. You can make sure the Windows Module Installer, BITS, and CryptSvc services are enabled like this:

1. Open Windows 11’s Services utility. You can check out our [how-to-open Services guide](https://www.makeuseof.com/windows-11-open-services-app/) for further instructions.
2. Double-click**Windows Module Installer** to view a properties window for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/windows-modules-installer-1.jpg)
3. Select the**Automatic** start option for the service on its**Startup type** drop-down menu.
4. Click**Start** on the properties window if the service isn’t running.  
![The Windows Modules Installer service properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/a-service-properties-window-1.jpg)
5. Select**Apply** \>**OK** to set the service’s settings.
6. Repeat the previous four steps for the Background Intelligent Transfer Service, Cryptographic Service, and Windows Update services.

## 6\. Make Sure .NET Framework 3.5 is Enabled

 The .NET Framework 3.5 feature also needs to be enabled for the Windows Update service to work. That should be enabled by default in Windows 11, but some users may still need to turn on .NET Framework 3.5\. This is how you can make sure .NET Framework 3.5 is enabled in Windows 11:

1. Open the file and app search utility by pressing the**Windows** +**S** key combo.
2. Enter**Windows features** in the**Type here to search** box.
3. Click the**Turn Windows features on or off** applet in the search tool.
4. Select the**.NET Framework 3.5** checkbox if that feature isn’t enabled.  
![The Windows Features window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-features-window-1.jpg)
5. Also, click the**.NET Framework 4.8** checkbox if it’s not selected.
6. Press the**OK** button in the Windows Features window.
7. Then click**Yes** to install.
8. Restart Windows 11 after installing the feature.

## 7\. Reset the Components for Windows Update

 Windows 11 22H2 update issues can also arise because of corrupted update components. You can repair the update components by resetting them. This troubleshooting method involves restarting update services and refreshing the catroot2 and SoftwareDistribution folders by renaming them. You can reset components for Windows updates with the Command Prompt like this:

1. Open Command Prompt with elevated permissions, as outlined in steps one to three of method two.
2. Then stop four services by inputting and executing the following commands:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
3. Next, rename the SoftwareDistribution folder by executing this command:  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren SoftwareDistribution command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-ren-softwaredistribution-command-1.jpg)
4. Input this rename catroot2 command and press**Return** :  
`ren C:\Windows\System32\catroot2 Catroot2.old`  
![The ren catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-ren-catroot2-folder-1.jpg)
5. Then restart the services with these commands:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`
6. Close Command Prompt, and select**Restart** on your Start menu.

## 8\. Turn Off Third-Party Antivirus Utilities

 Some third-party antivirus utilities can mistakenly interfere with the update process for Windows 11’s 22H2 update. To stop this from happening, disable real-time scanning for third-party antivirus software.

 If you have a third-party antivirus tool installed, right-click its system tray icon and select a context menu option to turn off its shield for a few hours; then try upgrading Windows 11 to the 22H2 version with the antivirus software disabled.

 AVG and Avast are two antivirus software packages that often generate Windows update errors. Those antivirus tools have also been incompatible with some Windows 10 builds. If you have either of those two installed, consider uninstalling them instead of merely disabling their shields.

## 9\. Disable Kernel DMA Protection

 Some users have said the Kernel DMA Protection security feature in Windows 11 causes the 22H2 update to fail when enabled. If that feature is enabled on your desktop or laptop, disabling it could fix the Windows 11 22H2 not installing. To check if Kernel DMA Protection is enabled,[open the System Information app](https://www.makeuseof.com/windows-11-check-system-information/) and look for that feature in the**System Summary** section.

![The Kernel DMA Protection system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-kernal-dma-system-detail-1.jpg)

 The only way to turn off Kernel DMA Protection is to disable a setting for it in the BIOS (Basic Input Output System). You can access Basic Input Output System settings on Windows 11/10 PCs as outlined within our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) . Look for and disable a Kernel DMA Protection setting on a**Security** tab within the BIOS.

## 10\. Update Your PC's Drivers

 Outdated device drivers can cause Windows upgrade issues. So, we recommend that you generally update device drivers on your PC. The quickest way to do that is to utilize a driver updater tool like Driver Booster.

 A Driver Booster scan will show you what devices on your PC have antiquated drivers. You can also select an**Update Now** option in that software to update the drivers for listed devices. Our [Driver Booster guide](https://www.makeuseof.com/update-windows-drivers-driver-booster-8/) includes instructions for updating drivers with that software.

![Driver Booster 8](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/driver-booster2.jpg)

 Alternatively, you may be able to install some new drivers with optional Windows updates. This is how you can check available optional updates in Windows 11:

1. [Open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and its**Windows Update** tab.
2. Select**Advanced options** to bring up some configuration settings for updates.
3. Click**Optional updates** to see if there are any driver updates available.
4. Select the checkboxes for driver updates there.
5. Click the**Download and install** option for selected driver updates.

## 11\. Install the 22H2 Update via the Installation Assistant

 This final resolution is more of a workaround than a fix for the 22H2 update not installing via Settings. Instead of using Settings, try upgrading with the Windows 11 Installation Assistant. We have a full guide that tells you [how to use the Installation Assistant](https://www.makeuseof.com/windows-11-installation-assistant-guide/) for updating Windows 11.

![The Windows 11 Update Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-11-update-assistant.jpg)

## Discover the Windows 11 2022 Update

 Those possible solutions will likely resolve most 22H2 update errors for the majority of users. The resolutions on Microsoft’s [Windows update troubleshooting](https://support.microsoft.com/en-us/windows/troubleshoot-problems-updating-windows-188c2b0f-10a7-d72f-65b8-32d177eb136c#WindowsVersion=Windows%5F11) page might also help some users fix Windows 11’s 22H2 update not installing. With that issue fixed, you can discover all the interesting new features and options in the Windows 11 2022 Update.

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
<li><a href="https://win11-tips.techidaily.com/resolving-d3dx939dll-loss-in-windows-11/"><u>Resolving D3DX9_39.dll Loss in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-error-unending-teams-sign-in-requests/"><u>Overcoming Windows Error: Unending Teams Sign-In Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-methods-to-identify-system-gadgets/"><u>Proven Windows Methods to Identify System Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-command-gain-admin-status/"><u>Regain Command - Gain Admin Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-this-file-cannot-be-previewed-error-in-outlook-for-windows/"><u>How to Fix the This File Cannot Be Previewed Error in Outlook for Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/unleashing-potential-in-screen-recording-expertise-in-adobe-captivate/"><u>Unleashing Potential in Screen Recording  Expertise in Adobe Captivate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-non-verified-error-during-windows-file-installation/"><u>Solving the Non-Verified Error During Windows File Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-demanded-assets-error-in-windows-1011-environments/"><u>Overcoming Demanded Assets Error in Windows 10/11 Environments</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-step-by-step-for-efficient-ipad-screen-recordings/"><u>[Updated] Step-by-Step for Efficient iPad Screen Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-options-picking-right-nvidia-driver-type-for-you/"><u>Navigating Options, Picking Right Nvidia Driver Type For You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reopen-a-closed-nvidia-control-panel-on-windows-11/"><u>How to Reopen a Closed Nvidia Control Panel on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-driver-initialization-failure-in-windows-11/"><u>Solutions for Driver Initialization Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resolving-user-not-found-issue-windows-1011/"><u>Steps for Resolving 'User Not Found' Issue: Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rejuvenate-itunes-that-wont-respond-on-windows/"><u>How to Rejuvenate iTunes That Won't Respond on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-expanded-pinned-area-on-windows-11-ui/"><u>Techniques for Expanded Pinned Area on Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-an-additional-monitor-without-gui-chipset/"><u>How to Use an Additional Monitor Without GUI Chipset</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-reverse-rhythms-2023s-most-memorable-inverted-melodies/"><u>New 2024 Approved Reverse Rhythms 2023S Most Memorable Inverted Melodies</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-the-nuances-of-premieres-fullscreen-mode/"><u>Navigating the Nuances of Premiere's Fullscreen Mode</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>How to share/fake gps on Uber for Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-cinema-crafting-excellence-top-5-camera-skills-to-hone/"><u>In 2024, Cinema Crafting Excellence  Top 5 Camera Skills to Hone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-red-magic-8s-pro-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Red Magic 8S Pro.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejoining-fall-guys-fixing-connectivity-issues-on-pc/"><u>Rejoining Fall Guys: Fixing Connectivity Issues on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-virtualbox-usb-connection-issue-on-windows-devices/"><u>Overcoming VirtualBox USB Connection Issue on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-mic-malfunctions-in-windows-os/"><u>Overcoming Xbox Mic Malfunctions in Windows OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-complete-guide-to-morphvox-voice-changer/"><u>[New] Complete Guide to MorphVOX Voice Changer</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-visionscreenshot-elite-best-for-mac-and-windows-snaps/"><u>In 2024, VisionScreenshot Elite  Best for Mac & Windows Snaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-troubleshooting-failed-capture-on-win11/"><u>Methods for Troubleshooting Failed Capture on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-stuck-windows-enter-function/"><u>Mending the Stuck Windows 'Enter' Function</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-the-ultimate-list-of-top-10-tiktok-analytic-software-for-2024/"><u>[Updated] The Ultimate List of Top 10 TikTok Analytic Software for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-narakeet-review-convenient-text-to-speech-voice-maker-for-2024/"><u>Updated Narakeet Review Convenient Text to Speech Voice Maker for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-creators-vs-youtubes-profit-policies-for-2024/"><u>[New] Creators Vs. YouTube's Profit Policies for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-content-extractor-the-best-of-the-rest-for-2024/"><u>Instagram Content Extractor  The Best of the Rest for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-cutting-edge-6-urban-designs-in-mc/"><u>[New] In 2024, Cutting-Edge 6 Urban Designs in MC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/starting-from-scratch-video-gear-insights-for-2024/"><u>Starting From Scratch  Video Gear Insights for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-the-art-of-visual-branding-with-professional-grade-fb-covers/"><u>[New] In 2024, The Art of Visual Branding with Professional-Grade FB Covers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restoring-functionality-fix-media-on-win11/"><u>Mastering the Art of Restoring Functionality: Fix Media on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ifttt-and-microsoft-to-dot-synergy-explained/"><u>IFTTT & Microsoft To-Dot Synergy Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-windows-1011-interrupt-crashes/"><u>Strategies for Tackling Windows 10/11 INTERRUPT Crashes</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-essential-guide-affordable-and-user-friendly-audio-noise-reduction-tools-for-2024/"><u>New Essential Guide Affordable & User-Friendly Audio Noise Reduction Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storeroom-in-mp60-speed-still-scarce/"><u>Storeroom in MP60, Speed Still Scarce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-highlight-the-mouse-cursor-in-windows-11-and-11/"><u>How to Highlight the Mouse Cursor in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-isarcextract-error-in-windows-11-updates/"><u>Overcoming ISArcExtract Error in Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unsuited-file-vlc-problem/"><u>Overcoming Windows' 'Unsuited File' VLC Problem</u></a></li>
</ul></div>
