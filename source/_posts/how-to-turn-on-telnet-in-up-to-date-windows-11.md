---
title: How to Turn On Telnet in Up-to-Date Windows 11
date: 2024-08-16T02:47:23.156Z
updated: 2024-08-17T02:47:23.156Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Turn On Telnet in Up-to-Date Windows 11
excerpt: This Article Describes How to Turn On Telnet in Up-to-Date Windows 11
keywords: Enabling Telnet Windows 11,Windows 11 Telnet Setup,Activating Telnet Windows OS,Instal TELNET in Windows 11,Windows 11 Telnet Access,Turn On Telnet Win11,Enable Telnet Windows 11
thumbnail: https://thmb.techidaily.com/1fa3b9714516519d17cdc00ae160f98cb4b200553b264310d7d2980b9ce91d3e.jpg
---

## How to Turn On Telnet in Up-to-Date Windows 11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://article-tips.techidaily.com/new-in-2024-from-srt-to-the-future-mastering-xmlssattml-transforms/"><u>[New] In 2024, From SRT to the Future  Mastering XML/SSA/TTML Transforms</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-unlocking-the-hidden-power-of-instagrams-ask-emoji/"><u>[New] In 2024, Unlocking the Hidden Power of Instagram’s Ask Emoji</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-eye-popping-360-cameras-deciding-the-best/"><u>[Updated] In 2024, Eye-Popping 360 Cameras  Deciding the Best</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-make-any-tiktok-song-a-perfect-fit-for-your-mobile-device/"><u>[Updated] In 2024, Make Any TikTok Song a Perfect Fit for Your Mobile Device</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-basics-to-high-quality-srgb-vs-rgb/"><u>2024 Approved  From Basics to High-Quality  Srgb vs Rgb</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-navigating-the-musical-maze-copyright-rules-for-insta-users/"><u>2024 Approved  Navigating the Musical Maze  Copyright Rules for Insta Users</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-asus-rog-phone-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-drawing-apps-for-iphones-for-2024/"><u>Best Drawing Apps for iPhones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-cleaning-up-the-icon-cache/"><u>Best Practices for Cleaning Up the Icon Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-silent-camera-activation-in-windows-11/"><u>Bypassing Silent Camera Activation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-the-ideal-placement-for-onedrive-on-windows-11/"><u>Crafting the Ideal Placement for OneDrive on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-out-the-webp-savings-in-google-chrome-for-windows/"><u>Cutting Out the WebP Savings in Google Chrome for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-batch-script-execution-power/"><u>Elevate Your Batch Script Execution Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-empty-directory-error-code-0x80070091-in-win11/"><u>Eliminating Empty Directory Error Code 0X80070091 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-full-screen-freezes-in-sonic-on-w11/"><u>Eliminating Full-Screen Freezes in Sonic on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-inactive-push-notifications-for-outlook/"><u>Enabling Inactive Push Notifications for Outlook</u></a></li>
<li><a href="https://program-issues.techidaily.com/ensuring-smooth-gameplay-strategies-to-address-recurring-watch-dogs-legion-freezes-and-shutdowns-on-windows/"><u>Ensuring Smooth Gameplay: Strategies to Address Recurring Watch Dogs Legion Freezes and Shutdowns on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-friendly-forecast-tools/"><u>Essential Windows-Friendly Forecast Tools</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/honor-90-lite-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Honor 90 Lite ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-sandbox-no-hypervisor-was-found-0xc0351000-error/"><u>How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-find-my-friends-work-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructingdarkmodeonwindowsnotepad/"><u>InstructingDarkModeOnWindowsNotepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-a-toolbar-update-check-feature-into-windows-11plus11-interface/"><u>Integrating a Toolbar Update Check Feature Into Windows 11+11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-edge-always-active-on-windows-11-guide/"><u>Is Edge Always Active on Windows 11? Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-audio-cd-production-from-mp3-files-an-efficient-guide-to-using-imgburn-in-windows/"><u>Mastering Audio CD Production From MP3 Files: An Efficient Guide to Using ImgBurn in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-task-managers-dominance-over-desktop-applications/"><u>Mastering Task Manager's Dominance Over Desktop Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-minimizing-cpu-load-on-computers/"><u>Mastery of Minimizing CPU Load on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-fixing-nvidia-cp-error-in-ws1110/"><u>Methodical Approach: Fixing Nvidia CP Error in WS11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-dxgi-error-messages-windows-1011/"><u>Navigating Through DXGI Error Messages (Windows 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070522-resolving-client-permissions-issue-on-windows-systems/"><u>Overcoming 0X80070522: Resolving Client Permissions Issue on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-correcting-rdp-fails-in-modern-windows-os/"><u>Preventing and Correcting RDP Fails in Modern Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-updater-error-0xca00a009/"><u>Repairing Windows Updater Error #0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-faulty-resource-monitors-on-windows-11/"><u>Resetting Techniques for Faulty Resource Monitors on Windows 11</u></a></li>
<li><a href="https://techidaily.com/resolve-compile-error-in-hidden-module-in-excel-2021-causes-and-solutions-stellar-by-stellar-guide/"><u>Resolve Compile Error in Hidden Module in Excel 2021 Causes & Solutions | Stellar</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-sensations-navigating-facebook-twitter-instagram-and-youtubes-popularity/"><u>Social Sensations: Navigating Facebook, Twitter, Instagram and YouTube's Popularity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-installing-java-in-windows-environment/"><u>Solutions for Non-Installing Java in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-your-pc-mastering-the-art-of-program-minimization/"><u>Speed Up Your PC: Mastering the Art of Program Minimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stronger-defense-through-longer-passcodes-windows-11-and-11-tips/"><u>Stronger Defense Through Longer Passcodes: Windows 11 and 11 Tips</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-samsung-galaxy-a34-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Samsung Galaxy A34 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-needs-user-id-login-failures/"><u>Troubleshooting Windows Needs User ID Login Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultra-quick-turn-off-windows-11-dings/"><u>Ultra-Quick Turn Off Windows 11 Dings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719233145490-win-plus-print-problem-heres-your-quick-windows-fix-guide/"><u>Win + Print Problem? Here's Your Quick Windows Fix Guide.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-app-usage-a-comprehensive-review/"><u>Window's App Usage: A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-efficient-temperature-management-strategy/"><u>Windows' Efficient Temperature Management Strategy</u></a></li>
</ul></div>
