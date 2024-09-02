---
title: Resolving Windows Installer Errors for Non-Compatible Apps
date: 2024-09-01T05:22:07.412Z
updated: 2024-09-02T05:22:07.412Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Windows Installer Errors for Non-Compatible Apps
excerpt: This Article Describes Resolving Windows Installer Errors for Non-Compatible Apps
keywords: Fixing Windows Install Failures,Resolve MSI Errors in Windows,Handling Incompatible WinApps,Troubleshoot WinInstaller Issues,Addressing Non-Compatible Apps Errors,Mitigate Unsupported Windows Installs,Solving App Install Conflicts
thumbnail: https://thmb.techidaily.com/035705869a176d12c457c62dcd5ac8433382a242da2e6ee8d5c9aeccc24af52d.jpg
---

## Resolving Windows Installer Errors for Non-Compatible Apps

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

 You can use[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to sideload and install msix files on your Windows computer. This should also work if you are trying to sideload an app that is not Store signed.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to[create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the[App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-elite-race-games-collection-guide/"><u>[New] 2024 Approved  Elite Race Games Collection Guide</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-engaging-viewers-and-vendors-a-guide-to-yt-sponsorships/"><u>[New] 2024 Approved  Engaging Viewers and Vendors  A Guide to YT Sponsorships</u></a></li>
<li><a href="https://youtube-web.techidaily.com/levating-youtube-live-with-high-quality-webcam-cameras-for-2024/"><u>[New] Elevating YouTube Live with High-Quality Webcam Cameras for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-mastering-full-view-fb-movie-magic/"><u>[New] In 2024, Mastering Full-View Fb Movie Magic</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-live-recording-analyzer/"><u>[Updated] Live Recording Analyzer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commercial-clutter-cleared-windows-start-edition/"><u>Commercial Clutter Cleared: Windows Start Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-and-rectifying-windowss-c0000005-complication/"><u>Demystifying and Rectifying Windows's C0000005 Complication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-repairing-error-0xc0000001/"><u>Diagnosing and Repairing Error 0xC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-system-performance-new-approach-to-icon-cache/"><u>Enhancing System Performance: New Approach to Icon Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-insights-budgeted-windows-11-codes/"><u>Exclusive Insights: Budgeted Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-to-windows-11-safe-mode-via-easy-methods/"><u>Fast Track to Windows 11 Safe Mode via Easy Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-bluetooth-absence-rediscover-devices-mgr-win/"><u>Fix Bluetooth Absence, Rediscover Devices Mgr WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-cloud-errors-in-windows/"><u>Fixing Steam Cloud Errors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-preventing-default-saving-issues-in-win/"><u>Guide to Preventing Default Saving Issues in Win</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-realme-c67-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Realme C67 5G Phone that is Locked?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-realme-narzo-n55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-samsung-galaxy-f04-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Xiaomi Redmi Note 13 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-cutting-edge-fb-video-ads-mastery-with-free-toolset/"><u>In 2024, Cutting-Edge FB Video Ads  Mastery with FREE Toolset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-safeguard-windows-without-bitlocker/"><u>Innovative Ways to Safeguard Windows Without BitLocker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-game-running-fixes-for-roblox-on-windows-pcs/"><u>Keeping Your Game Running: Fixes for Roblox on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-maintaining-reliable-windows-notepad-performance/"><u>Mastery in Maintaining Reliable Windows Notepad Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-fast-windows-11-app-accessing-techniques/"><u>Mastery of Fast Windows 11 App Accessing Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimization-techniques-for-quick-epic-game-access/"><u>Optimization Techniques for Quick Epic Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-dll-not-found-problem-with-steamui/"><u>Overcoming DLL Not Found Problem with SteamUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-activation-error-0x8007251d-a-step-by-step-guide/"><u>Resolving Windows Activation Error 0X8007251D: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-printer-connectivity-failures-in-windows-11/"><u>Solutions for Printer Connectivity Failures in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pcs-safety-audit-with-wins-11-tactics/"><u>Streamline Your PC's Safety Audit with Wins 11 Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-pointers-pace-turn-off-acceleration-in-windows-11/"><u>Taming the Pointer's Pace: Turn Off Acceleration In Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-silent-voice-finding-expression-in-a-muted-world/"><u>The Silent Voice: Finding Expression in a Muted World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-palette-of-digital-artistic-possibilities-on-win10/"><u>The Ultimate Palette of Digital Artistic Possibilities on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-recover-from-lost-connection-error-in-win/"><u>Tips to Recover From Lost Connection Error in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-changes-in-windows-ui-and-layout/"><u>Top 6 Changes in Windows UI and Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-loadlibrary-err-87-misstep/"><u>Troubleshooting LoadLibrary Err 87 Misstep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-headset-with-single-side-functioning/"><u>Troubleshooting Windows Headset with Single Side Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-fixing-0x0000004e-in-windows-1011/"><u>Unraveling and Fixing 0X0000004E in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-isnt-my-usb-mouse-working-on-my-laptop-top-repair-strategies-inside/"><u>Why Isn't My USB Mouse Working on My Laptop? Top Repair Strategies Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-secrets-automating-selective-file-shifts/"><u>Windows 11 Secrets: Automating Selective File Shifts</u></a></li>
</ul></div>
