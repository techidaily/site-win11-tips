---
title: Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11
date: 2024-08-16T02:02:02.288Z
updated: 2024-08-17T02:02:02.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11
excerpt: This Article Describes Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11
keywords: Install Microsoft Store,Store Reinstall Guide,Windows Store Apps,Reinstall Store Apps,Windows 10 Store Restore,Microsoft Store Reset,Restore Store on Windows
thumbnail: https://thmb.techidaily.com/a208b6b47f62fc53f6719bf37fb44710d3bca87f00271cab6e02272f4110e26d.jpg
---

## Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users
![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users
![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://extra-tips.techidaily.com/new-accelerate-your-facebook-video-journey-in-depth-app-and-extension-guide/"><u>[New] Accelerate Your Facebook Video Journey  In-Depth App & Extension Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-experience-the-next-level-of-virtual-reality-with-htcs-vive-headset/"><u>[New] Experience the Next Level of Virtual Reality with HTC's Vive Headset</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-top-12-wildlife-wonders-for-your-android-device/"><u>[New] In 2024, Top 12 Wildlife Wonders for Your Android Device</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-optimal-ram-assignment-for-superior-minecraft-gaming/"><u>[New] Optimal Ram Assignment for Superior Minecraft Gaming</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-transform-your-editing-master-the-fade-effect/"><u>[New] Transform Your Editing  Master the Fade Effect</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-essential-tips-for-high-quality-ipad-screenshots/"><u>[Updated] 2024 Approved  Essential Tips for High-Quality iPad Screenshots</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-friendly-reminder-how-to-chill-at-someones-tiktok-party/"><u>[Updated] 2024 Approved  Friendly Reminder  How To Chill at Someone's TikTok Party</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-recording-your-live-feed-without-spending-a-dime/"><u>[Updated] 2024 Approved  Recording Your Live Feed without Spending a Dime</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-essential-listing-of-the-best-5-iphone-friendly-podcast-tools/"><u>[Updated] In 2024, Essential Listing of the Best 5 iPhone-Friendly Podcast Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-seamlessly-screen-record-the-mi-11-user-manual-for-2024/"><u>[Updated] Seamlessly Screen Record  The Mi 11 User Manual for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-2023s-enhanced-sony-s3700-overview/"><u>[Updated] Unveiling 2023'S Enhanced Sony S3700 Overview</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fabricate-a-one-of-a-kind-internet-joke/"><u>2024 Approved  Fabricate a One-of-a-Kind Internet Joke</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premium-listing-of-free-cross-platform-4k-uhd-player-apps/"><u>2024 Approved  Premium Listing of Free, Cross-Platform 4K UHD Player Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-precise-methods-to-resolve-onedrive-errors/"><u>6 Precise Methods to Resolve OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-gaining-entry-into-windows-11s-application-repository/"><u>A Guide to Gaining Entry Into Windows 11'S Application Repository</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-steam-contact-issues-on-win11/"><u>A Step-by-Step Guide to Fixing Steam Contact Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-gameplay-9-tricks-to-end-wwe-2k23-freezes-in-windows/"><u>Accelerate Gameplay: 9 Tricks to End WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-gmail-to-windows-outlook-seamless-integration-method/"><u>Adding Gmail to Windows Outlook: Seamless Integration Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-id-inaccuracy-in-windows-11/"><u>Addressing System ID Inaccuracy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-mobility-center-activation-in-w11-systems/"><u>Avoid Mobility Center Activation in W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-screen-glitches-in-modern-operating-systems/"><u>Banishing Screen Glitches in Modern Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-extended-storage-mediocre-execution/"><u>Blackview MiniPC: Extended Storage, Mediocre Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-hotkeys-for-instantaneous-windows-redos/"><u>Boost Efficiency: Hotkeys for Instantaneous Windows Redos</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/breaking-through-youtubes-walls-using-advanced-creator-studio-skills/"><u>Breaking Through YouTube's Walls Using Advanced Creator Studio Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-enhancement-streamlined-file-exploration-for-windows-11/"><u>Effortless Enhancement: Streamlined File Exploration for Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/essential-guide-to-installing-msi-b350-toms-hardware-drivers-on-windows-11windows-7/"><u>Essential Guide to Installing MSI B350 TOM'S HARDWARE Drivers on Windows 11/Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-find-and-install-updates-for-your-canon-mg2520-printer-driver-on-windows-computers/"><u>How to Find & Install Updates for Your Canon MG2520 Printer Driver on Windows Computers</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-poco-m6-5g-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-techniques-for-modifying-voice-on-instagram-profiles/"><u>In 2024, Techniques for Modifying Voice on Instagram Profiles</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-the-ring-with-video-recording-who-will-triumph-obs-or-bandicam-in-2024/"><u>In the Ring with Video Recording  Who Will Triumph, OBS or Bandicam, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-11-and-intel-unison-for-smooth-phone-integration/"><u>Leveraging Windows 11 & Intel Unison for Smooth Phone Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-task-tracking-in-project-management/"><u>Master the Art of Task Tracking in Project Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338441167-navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298161302-overcoming-grayed-out-screensaver-in-win-os-top-fixes/"><u>Overcoming Grayed-Out Screensaver in Win OS: Top Fixes</u></a></li>
<li><a href="https://extra-support.techidaily.com/pioneering-strategies-for-success-in-the-spotify-ad-arena-for-2024/"><u>Pioneering Strategies for Success in the Spotify Ad Arena for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premium-vector-image-hubs-ranked-1-to-10-for-2024/"><u>Premium Vector Image Hubs Ranked #1 to #10 for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/probing-deep-into-inshots-editing-capabilities-for-2024/"><u>Probing Deep Into InShot's Editing Capabilities for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-permission-errors-a-step-by-step-guide-on-windows/"><u>Resolving Permission Errors: A Step-by-Step Guide on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-dilemma-obs-not-opening-on-windows/"><u>Resolving the Dilemma: OBS Not Opening on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/savory-showcase-inspiring-recipe-channels-that-thrive/"><u>Savory Showcase  Inspiring Recipe Channels That Thrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steer-clear-of-stuck-arrows-in-windows/"><u>Steer Clear of Stuck Arrows in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-path-upgrading-your-vm-software-from-virtualbox-v6-to-v7-in-win11/"><u>Step-by-Step Path: Upgrading Your VM Software From VirtualBox v6 to v7 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-changing-app-size-using-pc-keys-on-windows-11/"><u>Tips for Changing App Size Using PC Keys on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-power-enable-the-outlook-preview-app/"><u>Unlock Windows' Power: Enable the Outlook Preview App</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/unlocking-the-secrets-of-duplicating-your-tiktok-aura/"><u>Unlocking the Secrets of Duplicating Your TikTok Aura</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-s-mode-imply-in-windows-11-upgrade/"><u>What Does 'S Mode' Imply in Windows 11 Upgrade?</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>What is Geo-Blocking and How to Bypass it On Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
</ul></div>
