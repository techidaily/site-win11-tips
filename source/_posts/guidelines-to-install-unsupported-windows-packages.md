---
title: Guidelines to Install Unsupported Windows Packages
date: 2024-07-12T17:21:21.503Z
updated: 2024-07-13T17:21:21.503Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines to Install Unsupported Windows Packages
excerpt: This Article Describes Guidelines to Install Unsupported Windows Packages
keywords: Windows Package Guide,Unsupported OS Update,Illegal Windows Extensions,Secure Win Installs,Avoiding Windows Risk,Safe System Upgrades,Compliance with Windows Policy
thumbnail: https://thmb.techidaily.com/cc90cfb91ad0a20c12f9d720fc85b3d9e0382268e1d979284c574fcec450998c.jpg
---

## Guidelines to Install Unsupported Windows Packages

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

## 1\. Install the Msixbundle App Files Using PowerShell
![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

 You can use [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to sideload and install msix files on your Windows computer. This should also work if you are trying to sideload an app that is not Store signed.

 To install the app, you can use the Add-AppxPackage cmdlet in PowerShell with administrative privilege.

Follow these steps to sideload msix files using PowerShell.

1. Press the**Win** key and type**PowerShell.**
2. Right-click o**n Windows PowerShell** and select**Run as administrator.**
3. In the PowerShell window, type the following command and press Enter:  
`Add-AppxPackage -Path $MsixFilePath`
4. In the above command, replace MsixFilePath with the file path of the msix file saved on your PC. For example, if you want to run a Msixbundle file is located in**"C:\\Users\\Username\\Downloads\\Msixbundle"** the full command to install the file should look like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
5. To get the file path, right-click on the package and select**Copy as path** .
6. Next, press**Enter** and wait as PowerShell installs the app.
7. Once installed, type exit and press Enter to close Command Prompt.

## 2\. Install Msixbundle Apps Using the App Installer
![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the [App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

## Install Msixbundle, Appx, and AppxPackage on Windows 10 and 11

 This error is often triggered when you try to install a non-Store signed app package with restricted capabilities on your Windows computer. Fortunately, you can work around this restriction using PowerShell or App Installer.


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
<li><a href="https://youtube-videos.techidaily.com/updated-demystifying-the-art-behind-live-video-thumbnails/"><u>[Updated] Demystifying the Art Behind Live Video Thumbnails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-roadmap-for-smoother-files-transfer-in-win11-systems-1/"><u>A Roadmap for Smoother Files Transfer in WIN11 Systems (1)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-proven-steps-for-effortless-creation-of-youtube-shorts-credits/"><u>In 2024, Proven Steps for Effortless Creation of YouTube Shorts Credits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319856563-turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatedarkinterfaceinnotepadwinoses/"><u>ActivateDarkInterfaceInNotepadWinOSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-shown-pc-monitor-at-startup/"><u>Addressing Non-Shown PC Monitor at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-premium-zero-cost-windows-media-tools/"><u>7 Premium Zero-Cost Windows Media Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719262774069-your-on-premise-window-to-a-costless-chatgpt-clone-via-gpt4all/"><u>Your On-Premise Window to a Costless ChatGPT Clone via GPT4All.</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-elevate-your-banner-game-mastering-visual-branding-techniques/"><u>[Updated] Elevate Your Banner Game  Mastering Visual Branding Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-way-to-view-your-files-noteworthy-updates-in-windows-11/"><u>A New Way to View Your Files: Noteworthy Updates in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-restoring-your-windows-11-media-softwares-health/"><u>A Guide to Restoring Your Windows 11 Media Software's Health</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/roducing-channel-trailer-synopses-a-guide/"><u>[New] Producing Channel Trailer Synopses  A Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-finding-the-social-beacons-in-your-interests-digital-landscape/"><u>[Updated] In 2024, Finding the Social Beacons in Your Interests’ Digital Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-creative-methods-for-cooling-your-pc/"><u>8 Creative Methods for Cooling Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-personalizing-windows-using-winbubble/"><u>A Step-by-Step Guide to Personalizing Windows Using WinBubble</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-best-apps-for-3d-video-intros-on-social-platforms/"><u>[New] Best Apps for 3D Video Intros on Social Platforms</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-artisans-approach-crafting-unique-shareable-youtube-shorts/"><u>[Updated] The Artisan's Approach  Crafting Unique, Shareable YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-success-winning-strategies-for-windows/"><u>Achieve Academic Success: Winning Strategies for Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-visual-vibes-mastering-trendy-video-effects/"><u>In 2024, Visual Vibes Mastering Trendy Video Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inconsistent-thx-sound-on-pcs/"><u>Addressing Inconsistent THX Sound on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-loading-device-drivers-in-windows-11/"><u>Addressing Non-Loading Device Drivers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-temporarily-bypassing-windows-11s-safety-measures/"><u>A Quick Guide: Temporarily Bypassing Windows 11'S Safety Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-for-switching-from-pin-to-passwords-in-windows-11-user-interface/"><u>A Guide for Switching From PIN to Passwords in Windows 11 User Interface</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-unlocking-social-networks-the-pathway-to-a-facebook-profile/"><u>[New] 2024 Approved  Unlocking Social Networks  The Pathway to a Facebook Profile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382307115-addressing-wwinplusprint-error-on-your-computer-successfully/"><u>Addressing WWin+Print Error on Your Computer Successfully</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-on-iphone-15-pro-max-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock on iPhone 15 Pro Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-power-management-hiding-dim-display/"><u>Accessing Power Management: Hiding 'Dim Display'</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-ringsong-blueprint-guide-for-turning-tamil-tracks-into-notifications/"><u>[Updated] In 2024, RingSong Blueprint  Guide for Turning Tamil Tracks Into Notifications</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-cooldown-chart-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-workflow-customizing-windows-clipboard/"><u>Accelerated Workflow: Customizing Windows Clipboard</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-are-you-prepared-for-the-changed-facebook-algorithm/"><u>2024 Approved  Are You Prepared for the Changed Facebook Algorithm?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-hotkey-hits-unlock-maximum-auto-click-potential/"><u>5 Hotkey Hits: Unlock Maximum Auto Click Potential</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-turn-your-videos-into-treasures-a-guide-to-creating-home-dvds/"><u>New 2024 Approved Turn Your Videos Into Treasures A Guide to Creating Home DVDs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-11-safe-mode-6-routes-covered/"><u>Accessing Windows 11 Safe Mode: 6 Routes Covered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreran-analysis-of-8-w11-design-choices/"><u>A Compreran Analysis of 8 W11 Design Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-with-efficient-cmd-commands-top-20/"><u>Accelerate Tasks with Efficient CMD Commands (Top 20)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-encompass-entire-webpage-in-view/"><u>[Updated] Encompass Entire Webpage in View</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-sleep-aid-asmr-techniques-unveiled/"><u>2024 Approved  Sleep Aid  ASMR Techniques Unveiled</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/3-ways-to-export-contacts-from-apple-iphone-se-2020-to-excel-csv-and-vcard-easily-drfone-by-drfone-transfer-from-ios/"><u>3 Ways to Export Contacts from Apple iPhone SE (2020) to Excel CSV & vCard Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-11-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-hang-error-dxgierrordevicehunk-on-windows/"><u>Addressing the HANG Error: DXGI_ERROR_DEVICE_HUNK on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719317772933-reconcile-your-win-plus-print-discrepinasions-with-effective-solutions/"><u>Reconcile Your Win + Print Discrepinasions with Effective Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-hyper-v-on-your-windows-11-pc/"><u>Activating Hyper-V on Your Windows 11 PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-xiaomi-13t-pro-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Xiaomi 13T Pro Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-signs-its-probably-time-to-factory-reset-your-windows-pc/"><u>4 Signs It's Probably Time to Factory Reset Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-package-registration-hurdles-in-win11-image-files/"><u>Addressing Package Registration Hurdles in Win11 Image Files</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-balancing-content-creation-and-employment/"><u>2024 Approved  Balancing Content Creation and Employment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ancient-windows-features-you-can-still-find-in-windows-11/"><u>7 Ancient Windows Features You Can Still Find in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-ps5xbox-series-x-gaming-sets-the-top-5-list/"><u>In 2024, PS5/Xbox Series X Gaming Sets  The Top 5 List</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hidden-in-plain-sight-top-e-shops-for-buying-enigmatic-box-collections/"><u>[New] Hidden in Plain Sight  Top E-Shops for Buying Enigmatic Box Collections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-microsoft-project-keyboard-shortcuts/"><u>A Complete Guide to Microsoft Project Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719383078548-unfreeze-handbrake-on-widows-effortlessly/"><u>Unfreeze HandBrake on Widows, Effortlessly!</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-evaluating-earnings-from-one-million-youtube-watches/"><u>2024 Approved  Evaluating Earnings From One Million YouTube Watches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-an-innovative-auto-refresh-check-option-to-the-windows-ui/"><u>Adding an Innovative Auto-Refresh Check Option to the Windows UI</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-apple-iphone-13-pro-fix-now-drfone-by-drfone-virtual-ios/"><u>3uTools Virtual Location Not Working On Apple iPhone 13 Pro? Fix Now | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-14-plus-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 14 Plus System? | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-10-best-discord-plugins-to-improve-using-experience/"><u>[Updated] 10 Best Discord Plugins to Improve Using Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-the-no-servers-found-error-in-apex-legends-for-windows/"><u>9 Ways to Fix the No Servers Found Error in Apex Legends for Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-epic-prank-ideas-with-a-twist-of-anime-on-tiktok/"><u>2024 Approved  Epic Prank Ideas with a Twist of Anime on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-single-board-computers-that-run-windows/"><u>4 Single-Board Computers That Run Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ad-free-horizon-your-future-with-w11s-start-menu/"><u>Ad-Free Horizon: Your Future with W11's Start Menu</u></a></li>
</ul></div>
