---
title: Step Into the World of Windows 11 Home
date: 2024-08-16T02:23:54.586Z
updated: 2024-08-17T02:23:54.586Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step Into the World of Windows 11 Home
excerpt: This Article Describes Step Into the World of Windows 11 Home
keywords: Windows 11 Launch,New OS Exploration,Upgrade to Windows 11,Windows Home Experience,Modern PC Upgrade,Windows 11 Features,Transitioning to Windows 11
thumbnail: https://thmb.techidaily.com/3a8d29dc752129bc6cecd890184a07ba60927370b95afc8af67003c49b108b72.jpg
---

## Step Into the World of Windows 11 Home

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-altitude-achieved-a-critical-look-at-gopro-karma/"><u>[New] 2024 Approved  Altitude Achieved  A Critical Look at GoPro Karma</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-free-fx-library-to-enhance-youtube-productions/"><u>[New] 2024 Approved  Free FX Library to Enhance YouTube Productions</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-navigating-through-an-absent-obs-camera-input/"><u>[New] In 2024, Navigating Through an Absent OBS Camera Input</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723004566236-solved-origin-crash-issue-quickly-and-easily/"><u>[Solved] Origin Crash Issue | Quickly & Easily</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-ultimate-guide-to-design-and-build-your-own-4k-editing-system/"><u>[Updated] The Ultimate Guide to Design and Build Your Own 4K Editing System</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-unleash-the-power-of-zoom-with-these-tips-for-2024/"><u>[Updated] Unleash the Power of Zoom with These Tips for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-syma-x5c-an-in-depth-beginners-guide-for-future-pilots/"><u>2024 Approved  Syma X5C  An In-Depth Beginner’s Guide for Future Pilots</u></a></li>
<li><a href="https://tech-hub.techidaily.com/barricade-web-from-robotic-crawlers/"><u>Barricade Web From Robotic Crawlers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-overcoming-launch-failures-in-obs-studio/"><u>Comprehensive Guide: Overcoming Launch Failures in OBS Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/controlling-metrics-on-your-windows-11-wifi-networks/"><u>Controlling Metrics on Your Windows 11 Wifi Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-missing-essentials-issue-on-windows-11-system/"><u>Correcting 'Missing Essentials' Issue on Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/countering-sudden-invisibility-in-win-based-gaming/"><u>Countering Sudden Invisibility in Win-Based Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-unique-look-for-your-window-terminal/"><u>Crafting a Unique Look for Your Window Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphraning-the-message-of-crossed-out-icons-on-files/"><u>Deciphraning: The Message of Crossed-Out Icons on Files</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diy-correct-that-mia-d3dx9-library-problem-once-and-for-all/"><u>DIY: Correct That MIA D3DX9 Library Problem Once and For All</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/easy-steps-on-how-to-create-a-new-apple-id-account-on-apple-iphone-15-plus-drfone-by-drfone-ios/"><u>Easy Steps on How To Create a New Apple ID Account On Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unauthorized-users-4-routines-for-restraining-windows-access/"><u>Eliminating Unauthorized Users: 4 Routines for Restraining Windows Access</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-narrative-youtube-stars-to-watch-out-for/"><u>Essential Narrative YouTube Stars to Watch Out For</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-command-management-in-windows-1011/"><u>Fast-Track Command Management in Windows 10/11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/get-palworld-running-again-quick-troubleshooting-guide/"><u>Get Palworld Running Again: Quick Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-access-the-protected-windowsapps-folder-on-windows/"><u>How to Access the Protected WindowsApps Folder on Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-restore-sound-functionality-in-a-laptop-with-no-output/"><u>How to Restore Sound Functionality in a Laptop with No Output</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-disabled-apple-iphone-12ipad-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Disabled Apple iPhone 12/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-robust-access-controls-via-powertoys/"><u>Implementing Robust Access Controls via PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-adding-items-to-win-11-contextual-menu/"><u>Innovative Approaches to Adding Items to Win 11 Contextual Menu</u></a></li>
<li><a href="https://youtube-help.techidaily.com/legal-boundaries-of-online-video-capturing-tools-for-2024/"><u>Legal Boundaries of Online Video Capturing Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-settings-in-windows-11-with-minimal-hassle/"><u>Mastering Mouse Settings in Windows 11 with Minimal Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-recovering-missing-regedit/"><u>Mastering the Art of Recovering Missing Regedit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outsmarting-windows-logon-requirements/"><u>Outsmarting Windows Logon Requirements</u></a></li>
<li><a href="https://buynow-help.techidaily.com/outstanding-value-and-efficiency-in-the-tp-link-archer-a6-ac1200-our-review-reveals-all/"><u>Outstanding Value & Efficiency in the TP-Link Archer A6 AC1200: Our Review Reveals All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-random-shortcut-activation-in-windows/"><u>Overcoming Random Shortcut Activation in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win11-how-to-resolve-stalled-file-transfers-4/"><u>Overcoming WIN11: How to Resolve Stalled File Transfers (4)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-spur-up-your-printers-speed/"><u>Quick Fixes to Spur Up Your Printer's Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-reactivating-fixed-menu-options-on-pc/"><u>Quick Steps for Reactivating Fixed Menu Options on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-graphics-drivers-on-windows-11-systems/"><u>Refreshing Graphics Drivers on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-windows-backup-configurations/"><u>Regaining Original Windows Backup Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-saving-woes-quickly-6-key-methods-for-powerpoint-in-windows/"><u>Resolve Saving Woes Quickly: 6 Key Methods for PowerPoint in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restrictions-on-windows-11-insider-edition-use/"><u>Restrictions on Windows 11 Insider Edition Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverting-window-11s-search-functionality-back-to-icons/"><u>Reverting Window 11'S Search Functionality Back to Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shed-heavy-weights-pure-power-windows-11-tiny/"><u>Shed Heavy Weights: Pure Power, Windows 11 Tiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reinstallation-when-applications-dont-start-on-ms-marketplace/"><u>Strategies for Reinstallation When Applications Don't Start on MS Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-understanding-your-last-windows-use/"><u>The Key to Understanding Your Last Windows Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-leading-windows-brightness-management-apps-and-utilities/"><u>The Leading Windows Brightness Management Apps & Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-windows-1011-icon-spacing-control-tutorial/"><u>Title: Windows 10/11 Icon Spacing Control Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-computere-clock-display-top-5-windows-screensaver-apps-for-dynamic-visuals/"><u>Transform Your Computer’e Clock Display: Top 5 Windows Screensaver Apps for Dynamic Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/twinning-inboxes-gmail-plus-outlook-for-windows-users-guide/"><u>Twinning Inboxes: Gmail + Outlook for Windows Users Guide</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-photos-from-honor-90-pro-by-fonelab-android-recover-photos/"><u>Undelete lost photos from Honor 90 Pro.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-and-restoring-itunes-on-windows-devices/"><u>Unfreezing and Restoring iTunes on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-your-pcs-onedrive-mysteries-solutions-here/"><u>Unraveling Your PC's OneDrive Mysteries: Solutions Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-monitoring-network-traffic-on-windows-11/"><u>Unveiling the Secrets of Monitoring Network Traffic on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-windows-11-functionality-with-a-powerful-run-feature/"><u>Upgrade Windows 11 Functionality with a Powerful Run Feature</u></a></li>
</ul></div>
