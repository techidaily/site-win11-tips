---
title: "Reset and Reactivate: A Windows User's Guide for MS Store"
date: 2024-08-16T02:28:52.529Z
updated: 2024-08-17T02:28:52.529Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reset and Reactivate: A Windows User's Guide for MS Store"
excerpt: "This Article Describes Reset and Reactivate: A Windows User's Guide for MS Store"
keywords: Windows Reset Tips,Revive MS Store Apps,MS Store Reinstalls,Troubleshoot MS Errors,Reactivate Windows Store,Fixing MS Store Issues,Restart Microsoft Services
thumbnail: https://thmb.techidaily.com/a6c09f57496c52b8e907a972b91ffe1ac4bdb6bfabe268a90cf22a89412c015d.jpg
---

## Reset and Reactivate: A Windows User's Guide for MS Store

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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users
![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-conquering-the-top-5-common-instagram-video-issues/"><u>[New] 2024 Approved  Conquering the Top 5 Common Instagram Video Issues</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-proven-methods-for-obtaining-free-picture-screens/"><u>[New] 2024 Approved  Proven Methods for Obtaining Free Picture Screens</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-microsofts-hololens-journey-from-vision-to-reality-for-2024/"><u>[New] Microsoft’s HoloLens Journey – From Vision to Reality for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-transform-your-ig-story-with-melodic-elements-without/"><u>[New] Transform Your IG Story with Melodic Elements (Without)</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-mastering-mobile-image-personalization-iphoneandroids-best-10-apps/"><u>[Updated] In 2024, Mastering Mobile Image Personalization  IPhone/Android's Best 10 Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-macos-sierra-switching-back-to-os-x-el-capitan/"><u>[Updated] MacOS Sierra  Switching Back To OS X El Capitan</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-practical-methods-for-capturing-vimeo-media-for-2024/"><u>[Updated] Practical Methods for Capturing Vimeo Media for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-effortless-giggle-editor/"><u>[Updated] Ultimate Effortless Giggle Editor</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-13-ways-to-fine-tune-colors-in-photoshop-effortlessly/"><u>2024 Approved  13 Ways to Fine-Tune Colors in Photoshop Effortlessly</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-best-5-gif-to-video-converter-online-no-need-to-download/"><u>2024 Approved  Best 5 GIF to Video Converter Online [No Need to Download]</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-codec-clash-determining-the-leader-in-video-quality/"><u>2024 Approved  Codec Clash  Determining the Leader in Video Quality</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-the-essentials-2023s-highest-ranked-twitter-content/"><u>2024 Approved  The Essentials  2023'S Highest-Ranked Twitter Content</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-infinix-gt-10-pro-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Infinix GT 10 Pro FRP</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723262328291-are-dual-core-cpus-over-not-with-intels-latest-310-leading-two-p-cores-on-geekbench/"><u>Are Dual-Core CPUs Over? Not with Intel's Latest 310 Leading Two P-Cores on Geekbench!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-file-explorer-menus-with-auto-update-features/"><u>Augmenting File Explorer Menus with Auto-Update Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-operators-downloading-deadlock-in-windows/"><u>Break Free From Operator's Downloading Deadlock in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-xc0f1103f-issues-with-geforce-now-on-win11/"><u>Correcting Xc0f1103f Issues with GeForce Now on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktops-uncluttered-remove-win11s-spotlight-symbol/"><u>Desktops Uncluttered: Remove Win11's Spotlight Symbol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-the-gaming-experience-winning-strategies-for-ps1-and-windows-duckstations-guide/"><u>Elevating the Gaming Experience: Winning Strategies for PS1 and Windows - Duckstation's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-code-0x80300024-on-windows-xp/"><u>Eliminating Error Code: 0X80300024 on Windows XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-secure-text-transfer-operation-steps-in-edges-shielded-environment-win11-version/"><u>Enabling Secure Text Transfer: Operation Steps in Edge's Shielded Environment, Win11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-wi-fi-management-with-win-11-tips/"><u>Enhance Your Wi-Fi Management with Win 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-by-fixing-menu-glitches/"><u>Enhancing User Experience by Fixing Menu Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resolve-steam-video-hiccups/"><u>Essential Steps to Resolve Steam Video Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-an-uncluttered-system-restart-in-windows-11-guide/"><u>Executing an Uncluttered System Restart in Windows 11: Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-installed-optional-windows-functions-a-7-step-guide/"><u>Fixing Non-Installed Optional Windows Functions: A 7-Step Guide</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-realme-gt-neo-5-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-samsung-galaxy-xcover-7-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of Samsung Galaxy XCover 7 on Mac?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-apple-iphone-13-mini-location-on-viber-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change/Fake Your Apple iPhone 13 mini Location on Viber | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-navigating-posting-strategies-after-instagrams-revisions/"><u>In 2024, Navigating Posting Strategies After Instagram’s Revisions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sculpting-images-selecting-the-right-aspect-ratio/"><u>In 2024, Sculpting Images  Selecting the Right Aspect Ratio</u></a></li>
<li><a href="https://extra-information.techidaily.com/income-patterns-in-the-podcast-industry/"><u>Income Patterns in the Podcast Industry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-windows-local-space-management-tips-no-file-removal-max-156-chars/"><u>Innovative Windows Local Space Management Tips (No File Removal) (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launch-in-pc-no-fee-clone-of-chatgpt-on-windows/"><u>Launch In-PC, No-Fee Clone of ChatGPT on Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-game-pass-access-restoration-in-win-oses/"><u>Mastering Game Pass Access Restoration in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-updater-failures-0xca00a009/"><u>Mastering the Art of Fixing Updater Failures #0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-shortcuts-for-microsoft-store-uwp/"><u>Mastering Windows Shortcuts for Microsoft Store UWP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows!</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-discover-the-truth-is-vn-video-editor-pro-a-top-notch-video-editor/"><u>New Discover the Truth Is VN Video Editor Pro a Top-Notch Video Editor?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-repositioning-in-the-windows-11-environment/"><u>OneDrive Repositioning in the Windows 11 Environment</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-graphics-card-failure-in-msi-afterburner-on-new-windows-11-operating-system/"><u>Overcoming Graphics Card Failure in MSI Afterburner on New Windows 11 Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-correcting-ipad-picture-importer-mishaps-in-windows/"><u>Quick Guide: Correcting iPad Picture Importer Mishaps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedies-for-non-functional-windows-alt-codes-49-characters/"><u>Quick Remedies for Non-Functional Windows Alt Codes (49 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-camera-not-detected-error-on-win11/"><u>Remedy for “Camera Not Detected” Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-amd-gpu-software-on-pcs/"><u>Restoring Functionality to AMD GPU Software on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-icon-alignment-in-windows-10/"><u>Simplify Icon Alignment in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-isdonedll-complications-quickly/"><u>Solving Windows ISDone.dll Complications Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-non-responsive-services-on-windows-pcs/"><u>Steps to Rectify Non-Responsive Services on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-microsoft-store-error-0x80073cf3/"><u>Strategies to Address Microsoft Store Error 0X80073cf3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-copy-pasting-predefined-text-with-windows-11-hotkeys/"><u>Streamline Copy-Pasting Predefined Text with Windows 11 Hotkeys</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamlining-virtual-meetings-in-google-mail-for-2024/"><u>Streamlining Virtual Meetings in Google Mail for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-start-troubles-in-csgo-and-w11/"><u>Tackling Non-Start Troubles in CS:GO & W11</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-guide-to-free-aesthetic-iphone-image-editing-software/"><u>The Ultimate Guide to FREE, Aesthetic iPhone Image Editing Software</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-shortcut-tactics-for-optimal-voice-input-on-win-11/"><u>Ultimate Shortcut Tactics for Optimal Voice Input on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-upgrade-error-xc004f050-code/"><u>Unblocking Windows Upgrade Error Xc004f050 Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mystery-of-windows-1011-failed-app-start/"><u>Unveiling the Mystery of Windows 10/11 Failed App Start</u></a></li>
</ul></div>
