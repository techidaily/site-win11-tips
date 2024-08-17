---
title: Tackling Qt Initialization Unsuccessful in Dev Environment
date: 2024-08-16T02:39:31.432Z
updated: 2024-08-17T02:39:31.432Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Qt Initialization Unsuccessful in Dev Environment
excerpt: This Article Describes Tackling Qt Initialization Unsuccessful in Dev Environment
keywords: Qt Init Failures,QT Dev Environment Issues,Qt Initialization Errors,Qt Compilation Troubleshooting,Dev Environment Qt Setup,Resolving Qt Load Failure,Correcting Qt Uninitialized
thumbnail: https://thmb.techidaily.com/a5a6155fc00c2184034c489f78d9dfa451dfb821e3d54808d5e05507218b1694.png
---

## Tackling Qt Initialization Unsuccessful in Dev Environment

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.
6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

 If the System File Checker didn’t fix the problem, there are[more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out[how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Uninstall Any Recent Windows Updates

 Sometimes, Windows display the “Application failed because no QT platform plugin could be initialized” error after a system update. In this case, you can load a restore point to undo the change and get rid of the error.

 But if there’s no restore point available, you can manually uninstall Windows updates.

1. Launch Windows Settings by pressing**Win + I** .
2. From the left pane, click**Windows Update > Update History** .
3. Head to**Related Settings** and click**Uninstall updates** .
4. Right-click the latest update and select**Uninstall** .

![Uninstall recent Windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-updates-1.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of the QT Error on Windows

 Hopefully, one or more of the above solutions helped you fix the “Application failed to start because no Qt platform plugin could be initialized” error.

 Sometimes, it’s difficult to figure out the exact cause of a Windows error, and reinstalling the app every time might not be the most efficient solution. To speed up the troubleshooting process, you should use one of the many Windows repair tools.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-optimizing-profits-on-youtube-studio-for-all-device-users/"><u>[New] Optimizing Profits on YouTube  Studio for All-Device Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-roundabout-viewpoint-versus-threefold-imaging/"><u>[Updated] Roundabout Viewpoint Versus Threefold Imaging</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-enhance-your-clips-with-these-top-5-macos-sierra-editors/"><u>2024 Approved  Enhance Your Clips with These Top 5 macOS Sierra Editors</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-free-world-quest-the-elite-10-mmo-rankings/"><u>2024 Approved  Free World Quest  The Elite 10 MMO Rankings</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-the-technical-edge-why-high-dynamic-range-triumphs-over-standard-dynamic-range/"><u>2024 Approved  The Technical Edge  Why High Dynamic Range Triumphs over Standard Dynamic Range</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-top-8-no-cost-4k-uhd-players-for-win-and-mac-users/"><u>2024 Approved  Top 8 No-Cost, 4K UHD Players for Win & Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tips-to-quickly-solve-windows-screen-problems/"><u>5 Tips to Quickly Solve Windows Screen Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-free-up-local-drive-space-without-deleting-files-on-windows-11/"><u>8 Ways to Free Up Local Drive Space Without Deleting Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-adding-emulators-to-playnite-on-pc/"><u>A Step-by-Step Guide: Adding Emulators to Playnite on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-health-monitoring-set-up-full-charge-indicators-in-win11/"><u>Accelerating Battery Health Monitoring: Set Up Full Charge Indicators in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-typing-top-7-tricks-for-fast-input-on-win-pcs/"><u>Accelerating Typing: Top 7 Tricks for Fast Input on Win PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-take-when-facing-invalid-name-on-pc/"><u>Actions to Take When Facing Invalid Name on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-amending-system-call-failures-in-modern-windows/"><u>Addressing and Amending System Call Failures in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-30015-26-in-microsoft-365-for-users/"><u>Addressing Error Code 30015-26 in Microsoft 365 for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-screen-tick/"><u>Addressing Window's 11 Screen Tick</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-clockdate-display-in-window-11-interface/"><u>Adjust Clock/Date Display in Window 11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-application-runtime-to-compensate-for-lack-of-qt-plugins/"><u>Adjusting Application Runtime to Compensate for Lack of Qt Plugins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-setup-service-operation-levels/"><u>Adjusting Windows Setup Service Operation Levels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-sign-in-restrictions-after-errors/"><u>Adjusting Windows Sign In Restrictions After Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-to-master-voice-activated-accessibility-on-windows/"><u>Advanced Techniques to Master Voice-Activated Accessibility on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-user-interface-customization-for-win-11/"><u>Advanced User Interface Customization for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alt-tab-techniques-efficiently-arrange-your-open-windows-win1110/"><u>Alt-Tab Techniques: Efficiently Arrange Your Open Windows (Win11/10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-access-windows-shared-folders/"><u>Android: Access Windows Shared Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-automatic-windows-updates/"><u>Banishing Automatic Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365152122-boost-windows-with-top-2023-ms-store-winners/"><u>Boost Windows with Top 2023 MS Store Winners!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-in-windows-11/"><u>Boosting File Management in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-net-speed-win-pc-download-acceleration-tips/"><u>Boosting Net Speed: Win-PC Download Acceleration Tips</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-installation-of-kyocera-printer-drivers-for-windows-users/"><u>Easy Installation of KYOCERA Printer Drivers for Windows Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Oppo K11x? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-locked-archives-to-laymans-subtitles-the-zip-to-srt-method/"><u>In 2024, From Locked Archives to Layman's Subtitles  The Zip To Srt Method</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-vivo-y36i-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Vivo Y36i to Another | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-innovating-your-ultimate-tiktok-seal/"><u>In 2024, Innovating Your Ultimate TikTok Seal</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/keep-an-eye-out-for-insta-follower-fleece/"><u>Keep an Eye Out for Insta Follower Fleece</u></a></li>
<li><a href="https://tech-revival.techidaily.com/launch-your-custom-ai-adventures-today-with-these-8-gpts/"><u>Launch Your Custom AI Adventures Today with These 8 GPTs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-xiaomi-mix-fold-3-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Xiaomi Mix Fold 3 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/taking-screenshot-on-windows-1187-for-2024/"><u>Taking Screenshot on Windows 11/8/7 for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-homeowners-handbook-for-powering-up-your-electric-car-overnight/"><u>The Ultimate Homeowner's Handbook for Powering Up Your Electric Car Overnight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719366332809-trouble-at-clipcraft-unravel-fixes-today/"><u>Trouble at ClipCraft? Unravel Fixes Today</u></a></li>
</ul></div>
