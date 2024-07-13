---
title: A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater
date: 2024-07-12T17:50:15.917Z
updated: 2024-07-13T17:50:15.917Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater
excerpt: This Article Describes A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater
keywords: Win11 Update Guide,Windows 11 H2 Installer,Win11 V22H2 Installation,WIN11v22Updater Steps,Upgrade to Win11H2,Win11 22H2 Update Plan,Execute Windows 11 H2 Patch
thumbnail: https://thmb.techidaily.com/d222a947a358a9a5da5a72c775e634907e671d005e0a2808f2ac3a2ab7305bec.jpg
---

## A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater

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
<li><a href="https://howto.techidaily.com/poco-m6-5g-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Poco M6 5G Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-live-service-disruptions-on-pcs/"><u>Troubleshooting Xbox Live Service Disruptions on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-bluetooth-issue-here-are-9-quick-cures-to-restore-your-link/"><u>Win 11'S Bluetooth Issue? Here Are 9 Quick Cures to Restore Your Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-environment-with-portable-utility-icons/"><u>Streamlining Windows Environment with Portable Utility Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-beginners-handbook-to-free-chessboard-soccer-management/"><u>The Complete Beginner’s Handbook to Free Chessboard Soccer Management</u></a></li>
<li><a href="https://some-techniques.techidaily.com/frame-finesse-selecting-superior-video-cams-for-slow-motion-for-2024/"><u>Frame Finesse  Selecting Superior Video Cams for Slow Motion for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-essential-online-capture-for-tech-enthusiasts/"><u>[Updated] In 2024, Essential Online Capture for Tech Enthusiasts</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-embellish-your-discord-conversations-like-a-pro/"><u>2024 Approved  Embellish Your Discord Conversations Like a Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-blanking-and-flashing-windows-11-screen/"><u>Stop Blanking and Flashing Windows 11 Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stifling-windows-restart-requests/"><u>Stifling Windows Restart Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-vs-powershell-a-closer-look-at-their-differences/"><u>Terminal Vs. PowerShell: A Closer Look at Their Differences</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-se-2022-to-android-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone SE (2022) To Android? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-4-ways-to-unlock-iphone-7-plus-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock iPhone 7 Plus to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-xiaomi-redmi-k70-pro-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Xiaomi Redmi K70 Pro Phone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-oppo-find-x7-easily-by-drfone-android/"><u>How To Unlock a Oppo Find X7 Easily?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-a-neat-system-restart-in-windows-11/"><u>The Essential Guide to a Neat System Restart in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipmagic-disrupted-methods-to-reset-and-revive/"><u>SnipMagic Disrupted? Methods to Reset and Revive</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-oppo-a56s-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Oppo A56s 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-constant-edge-activity-in-windows-11/"><u>Understanding Constant Edge Activity in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-the-way-you-search-on-windows-11/"><u>Revamp the Way You Search on Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-essential-bandicam-know-how-a-complete-review/"><u>In 2024, Essential Bandicam Know-How - A Complete Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-workflow-paste-and-mouse-jump-techniques/"><u>Accelerate Workflow: Paste & Mouse Jump Techniques</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hidden-history-unveiled-understanding-off-facebook-data/"><u>2024 Approved  Hidden History Unveiled  Understanding Off-Facebook Data</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-speedy-glimpse-through-windows-files-for-2024/"><u>[Updated] Speedy Glimpse Through Windows Files for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-faster-file-transfers-with-utorrent-on-win-computers/"><u>Unlock Faster File Transfers with uTorrent on Win Computers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ow-to-design-a-great-gaming-youtube-banner-with-templates-for-2024/"><u>[New] How to Design a Great Gaming YouTube Banner with Templates for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-camera-failure-on-photovideo-saving/"><u>Repairing Windows Camera Failure on Photo/Video Saving</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-vivo-y100i-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforcing-the-resilience-of-windows-11-taskbar/"><u>Reinforcing the Resilience of Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realign-subtitles-in-prime-video-elevate-your-windows-11-experience/"><u>Realign Subtitles in Prime Video, Elevate Your Windows 11 Experience</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-mastering-in-stream-ads-on-facebook-configuration-and-analysis-guide/"><u>[Updated] In 2024, Mastering In-Stream Ads on Facebook  Configuration & Analysis Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-installation-privilege-denial-problem/"><u>Solving Windows Installation Privilege Denial Problem</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-google-pixel-8-pro-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Google Pixel 8 Pro Phone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-combat-windows-minimizing-glitches/"><u>Strategies to Combat Windows Minimizing Glitches</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/the-best-of-the-best-8-mac-movie-creation-tools-you-need-for-2024/"><u>The Best of the Best 8 Mac Movie Creation Tools You Need for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-digital-space-with-win-11-sketching-techniques/"><u>Redefine Your Digital Space with Win 11 Sketching Techniques</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-efficient-solutions-for-youtube-short-snags/"><u>2024 Approved  Efficient Solutions for YouTube Short Snags</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2023-top-8-facebook-movie-downloaders/"><u>[Updated] 2023 | Top 8 Facebook Movie Downloaders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-streamlining-with-new-folder-placement/"><u>Step-by-Step Guide to Streamlining with New Folder Placement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhinge-your-onedrive-link-from-microsoft-profile-in-windows/"><u>Unhinge Your OneDrive Link From Microsoft Profile in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-glitches-to-ensure-smooth-gameplay-on-windows-11/"><u>Tackling Steam Glitches to Ensure Smooth Gameplay on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-chrome-on-a-windows-desktop/"><u>Unblocking Chrome on a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-0x887a0006-device-hang-fixes/"><u>Resolving Error Code 0X887A0006: Device Hang Fixes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-in-depth-asmr-video-insights/"><u>[New] In-Depth ASMR Video Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-files-directories-for-game-access/"><u>Winning at Files: Directories for Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-error-code-0x80070570-for-corrupted-items/"><u>Steps to Resolve Windows Error Code 0X80070570 for Corrupted Items</u></a></li>
<li><a href="https://youtube-web.techidaily.com/he-content-dilemma-deciding-on-the-best-platform-igtv-or-youtube-for-2024/"><u>[New] The Content Dilemma  Deciding on the Best Platform - IGTV or YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-default-path-problems-on-windows-1011/"><u>Resolving Default Path Problems on Windows 10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-a-straightforward-approach-beginners-guide-to-creating-nfts/"><u>[Updated] A Straightforward Approach  Beginner's Guide to Creating NFTs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reenergizing-your-dead-wireless-hotspot-in-windows-11/"><u>Reenergizing Your Dead Wireless Hotspot in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-laptop-or-desktops-past/"><u>Unraveling Windows Laptop or Desktop's Past</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1716069411954-new-how-to-manual-for-creating-an-inclusive-and-productive-skype-chat-room-accessible-by-both-windows-and-mac-users-for-2024/"><u>[New] How-To Manual for Creating an Inclusive and Productive Skype Chat Room Accessible by Both Windows & Mac Users. For 2024</u></a></li>
</ul></div>
