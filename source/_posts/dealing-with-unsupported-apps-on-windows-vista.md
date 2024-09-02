---
title: Dealing with Unsupported Apps on Windows Vista
date: 2024-09-01T05:14:33.985Z
updated: 2024-09-02T05:14:33.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with Unsupported Apps on Windows Vista
excerpt: This Article Describes Dealing with Unsupported Apps on Windows Vista
keywords: Vista Support Woes,Unsupported Windows Apps,Fixing Vista Software Errors,Windows Vista Compatibility,Troubleshoot Vista Apps,Update Vista Software,Eliminate Vista App Issues
thumbnail: https://thmb.techidaily.com/1f343cc2ca566c6b496acac107d8a3cfc474691f655f34c60ef016476e0a8a74.jpg
---

## Dealing with Unsupported Apps on Windows Vista

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
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-brighten-up-techniques-for-improving-video-lighting-on-youtube/"><u>[New] 2024 Approved  Brighten Up  Techniques for Improving Video Lighting on YouTube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-survivals-thrill-top-picks-for-heart-pounding-zombie-games/"><u>[Updated] 2024 Approved  Survival's Thrill  Top Picks for Heart-Pounding Zombie Games</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-discover-the-best-8-mirrorless-cameras-that-transform-vlogging/"><u>[Updated] In 2024, Discover the Best  8 Mirrorless Cameras That Transform Vlogging</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-essential-recording-strategies-how-to-capture-the-unrecorded-moments-on-discord/"><u>2024 Approved  Essential Recording Strategies  How to Capture the Unrecorded Moments on Discord</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-sleek-superior-substantial-reviewing-the-asus-mg28uq-4k-display/"><u>2024 Approved  Sleek, Superior, Substantial – Reviewing the ASUS MG28UQ 4K Display</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-photographers-guide-to-digital-cropting/"><u>2024 Approved  The Photographer's Guide to Digital Cropting</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/capturing-the-illusion-iphone-tricks-for-reflection-photography/"><u>Capturing the Illusion  IPhone Tricks for Reflection Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-method-to-delete-wsl/"><u>Comprehensive Method to Delete WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-operation-failure-x709-on-pc/"><u>Correcting Operation Failure X709 on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-out-delays-for-administrator-level-terminals/"><u>Cut Out Delays for Administrator-Level Terminals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designating-menu-triggers-for-software-patch-alerts/"><u>Designating Menu Triggers for Software Patch Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-diversity-of-windows-n-versions/"><u>Dissecting the Diversity of Windows N Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-steps-to-fix-windowss-dotnet-problems-max-156/"><u>Efficient Steps to Fix Windows's DotNet Problems (Max 156)</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/from-basics-to-advanced-toms-comprehensive-hardware-journey/"><u>From Basics to Advanced: Tom’s Comprehensive Hardware Journey</u></a></li>
<li><a href="https://fox-that.techidaily.com/guide-resolving-the-issue-when-whatsapp-wont-back-up-to-your-icloud-account/"><u>Guide: Resolving the Issue When WhatsApp Won't Back Up To Your iCloud Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-controlled-folder-access-in-windows-10-and-11/"><u>How to Enable Controlled Folder Access in Windows 10 & 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-madden-22-not-working-easily-and-quickly/"><u>How to Fix Madden 22 Not Working [Easily & Quickly]</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-bridging-social-media-and-television-with-live-streaming/"><u>In 2024, Bridging Social Media & Television with Live Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-eradicating-audacity-error-9999/"><u>Mastering the Art of Eradicating Audacity Error 9999</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-software-removal-windows-11-edition-143-chars/"><u>Navigating SoftWare Removal: Windows 11 Edition (143 Chars)</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/navigating-urban-terrain-with-ease-on-cycwagens-groundbreaking-electric-cargo-bike/"><u>Navigating Urban Terrain with Ease on CycWagen's Groundbreaking Electric Cargo Bike</u></a></li>
<li><a href="https://win-blog.techidaily.com/optimized-pc-settings-for-a-lag-free-deathloop-adventure-what-you-need-to-know/"><u>Optimized PC Settings for a Lag-Free Deathloop Adventure: What You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-approaches-for-effective-windows-file-browsing-sans-ls/"><u>Proven Approaches for Effective Windows File Browsing Sans LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-browsing-with-microsoft-edge-on-win10w11/"><u>Speeding Up Browsing with Microsoft Edge on Win10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/start-up-synergy-launching-sticky-notes-with-windows-logon/"><u>Start-Up Synergy: Launching Sticky Notes with Windows Logon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reestablishing-remote-network-links-in-winvpn/"><u>Strategies for Reestablishing Remote Network Links in WinVPN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-unavailable-error-on-your-pcs-windows-apps/"><u>Tackling the 'Unavailable' Error on Your PC's Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-charge-of-your-computer-task-manager-elevated-mode-demystified-in-win11/"><u>Take Charge of Your Computer: Task Manager Elevated Mode Demystified in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/total-eradication-of-wsl-from-windows-11-os/"><u>Total Eradication of WSL From Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unboxing-the-stars-latest-laptops-from-ifa-2023/"><u>Unboxing the Stars - Latest Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-secret-search-mechanism-of-windows-11/"><u>Unlock Secret Search Mechanism of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-secrets-quick-fixed-for-11-windows-issues/"><u>Unveiling Secrets: Quick Fixed for 11 Windows Issues</u></a></li>
</ul></div>
