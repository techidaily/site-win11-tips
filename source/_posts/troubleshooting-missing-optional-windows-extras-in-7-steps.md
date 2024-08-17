---
title: Troubleshooting Missing Optional Windows Extras in 7 Steps
date: 2024-08-16T01:39:07.109Z
updated: 2024-08-17T01:39:07.109Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Missing Optional Windows Extras in 7 Steps
excerpt: This Article Describes Troubleshooting Missing Optional Windows Extras in 7 Steps
keywords: Fix Windows Extras,Extras Rediscovery Guide,Reinstalling Windows Features,Opti Windows Troubleshooting,Restore Missing Options,Windows Extra Recovery,Steps to Addon Extras
thumbnail: https://thmb.techidaily.com/b75952ddf1d4af9f33bac9d924f7db98ead5f1ed4a0ce7215f6d5a9fade562b4.jpg
---

## Troubleshooting Missing Optional Windows Extras in 7 Steps

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the [DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the [ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best [ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try [installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online ![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME ![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.


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
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-a-list-makeup-tutorials-who-to-watch/"><u>[Updated] 2024 Approved  A-List Makeup Tutorials  Who to Watch ?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-screenmagic-pro-the-windows-10-companion/"><u>[Updated] In 2024, ScreenMagic Pro  The Windows 10 Companion</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-success-stories-adopting-viral-techniques-from-tiktok/"><u>[Updated] Instagram Success Stories  Adopting Viral Techniques From TikTok</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-phones-to-fantasy-crafting-a-home-for-vr-goggles/"><u>[Updated] Phones to Fantasy  Crafting a Home for VR Goggles</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-eliminate-clutter-on-tweet-feed-with-top-20-apps/"><u>2024 Approved  Eliminate Clutter on Tweet Feed with Top 20 Apps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-tips-for-shooting-quality-gopro-time-lapse-videos/"><u>2024 Approved  Pro Tips for Shooting Quality GoPro Time-Lapse Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-scripted-synergy-systems/"><u>2024 Approved  Scripted Synergy Systems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-soaring-with-mi-drone-an-in-depth-4k-study/"><u>2024 Approved  Soaring with MI Drone - An In-Depth 4K Study</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-unzipping-of-multiple-files-using-windows-tools/"><u>Accelerated Unzipping of Multiple Files Using Windows Tools</u></a></li>
<li><a href="https://program-issues.techidaily.com/breaking-down-the-delay-in-football-manager-2022-release-and-fixing-it/"><u>Breaking Down the Delay in Football Manager 2022 Release & Fixing It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-integration-of-apple-maps-on-pcs/"><u>Deciphering the Integration of Apple Maps on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-arp-cache-how-to-empty-it/"><u>Decoding Windows ARP Cache: How to Empty It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-windows-11-account-settings-center/"><u>Finding Windows 11 Account Settings Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-domain-services-printer-failures-on-newest-microsoft-os/"><u>Fixing Domain Services Printer Failures on Newest Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-automate-microsoft-to-do-with-ifttt/"><u>How to Automate Microsoft To Do With IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-windows-11-shutdown-with-open-filestasks/"><u>How to Control Windows 11 Shutdown with Open Files/Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-0x8007007e-error-code/"><u>How to Fix the Windows 0X8007007E Error Code</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-newest-canon-mg290er-driver-software-complete-guide/"><u>How to Get the Newest Canon MG290er Driver Software - Complete Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-windows-upgrade-failures-and-errors/"><u>How to Resolve Windows Upgrade Failures and Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-setup-virtualboxs-security-features-secure-boot-and-tpm/"><u>How to Setup VirtualBox's Security Features: Secure Boot & TPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-thrive-in-free-championship-football-simulator/"><u>How to Thrive in Free Championship Football Simulator</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-motorola-moto-g04-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Motorola Moto G04 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/image-editing-strategies-remove-unwanted-areas/"><u>Image Editing Strategies: Remove Unwanted Areas</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-depth-training-adopting-the-best-screen-recording-practices-with-adobe-captivate-for-2024/"><u>In-Depth Training  Adopting the Best Screen Recording Practices with Adobe Captivate for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-auto-lock-and-screensaver-configurations/"><u>Mastering Auto-Lock & Screensaver Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-double-click-3-essential-tips/"><u>Mastering Mouse Double-Click: 3 Essential Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-7-steps-to-mend-obs-server-link-error-in-windows/"><u>Navigating 7 Steps to Mend OBS Server Link Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepads-dark-shift-windows-11-guide/"><u>Notepad's Dark Shift: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-steam-for-seamless-gameplay-on-windows-11-devices/"><u>Realigning Steam for Seamless Gameplay on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-restarting-windows-11-apps/"><u>Reviving Your PC: Restarting Windows 11 Apps</u></a></li>
<li><a href="https://some-guidance.techidaily.com/roav-dashcam-c1-by-anker-comprehensive-review-for-safety-and-performance/"><u>Roav DashCam C1 by Anker - Comprehensive Review for Safety and Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipgear-gone-wrong-nine-effective-tips-to-get-it-running-again/"><u>SnipGear Gone Wrong? Nine Effective Tips to Get It Running Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-service-management-for-optimized-windows-11/"><u>Strategic Service Management for Optimized Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-updating-window-11s-context-menu/"><u>Streamlining Tasks: Updating Window 11'S Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-on-or-off-windows-digital-protection-filter/"><u>Switching on or Off Windows' Digital Protection Filter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-aural-anomaly-fixing-audacity-writes-on-wos/"><u>Tackling the Aural Anomaly: Fixing Audacity' Writes on WOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-removing-virtualization-support-on-win11/"><u>Tips for Removing Virtualization Support on Win11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-xiaomi-13t-pro-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Xiaomi 13T Pro Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-win-microphone-functionality/"><u>Troubleshoot Win Microphone Functionality</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ultimate-guide-leading-wireless-mice-ranked/"><u>Ultimate Guide: Leading Wireless Mice Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-aggregatorhostexe-windows-functionality-and-safety-concerns/"><u>Understanding AggregatorHost.exe: Windows' Functionality & Safety Concerns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/universal-font-collection-windows-installation-steps/"><u>Universal Font Collection: Windows Installation Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-keyboard-command-center-mastery-of-shortcuts-for-fixed-paste-tasks/"><u>Win11's Keyboard Command Center: Mastery of Shortcuts for Fixed Paste Tasks</u></a></li>
</ul></div>
