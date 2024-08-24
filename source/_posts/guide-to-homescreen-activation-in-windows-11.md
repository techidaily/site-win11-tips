---
title: Guide to Homescreen Activation in Windows 11
date: 2024-08-23T07:05:39.834Z
updated: 2024-08-24T07:05:39.834Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Homescreen Activation in Windows 11
excerpt: This Article Describes Guide to Homescreen Activation in Windows 11
keywords: Win11 Homescreen Init,Enabling W11 Screen,Start Menu Setup,Windows 11 Guide,Home Screens Activation,New Windows Interface,W11 Initialization Steps
thumbnail: https://thmb.techidaily.com/d3d14caf519c1def322723a3dc59c24a3c8f8aedec1a3d79fbe40024b923c7fb.jpeg
---

## Guide to Homescreen Activation in Windows 11

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-capturing-honesty-a-comprehensive-guide-to-insta-self-verification-for-2024/"><u>[New] Capturing Honesty  A Comprehensive Guide to Insta Self-Verification for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-ensuring-flawless-sending-of-large-videos-from-iphone-to-mac-pc/"><u>[New] In 2024, Ensuring Flawless Sending of Large Videos From iPhone to Mac PC</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-pinnacle-sound-selections-android-based/"><u>[New] Pinnacle Sound Selections, Android-Based</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-iconic-writings-distinguishing-film-types/"><u>[Updated] Iconic Writings Distinguishing Film Types</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitters-space-best-practices-for-tiktok-videos/"><u>[Updated] Twitter's Space  Best Practices for TikTok Videos</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/11-must-watch-films-for-a-dose-of-inspiration-ranked/"><u>11 Must-Watch Films for a Dose of Inspiration: Ranked!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-decoding-igtv-video-statistics-for-better-insights/"><u>2024 Approved  Decoding IGTV Video Statistics for Better Insights</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-compilation-of-html5s-best-video-tools/"><u>2024 Approved  The Ultimate Compilation of HTML5's Best Video Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-the-ultimate-guide-to-frame-rates-for-video-recorders/"><u>2024 Approved  The Ultimate Guide to Frame Rates for Video Recorders</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/easy-implementation-of-snap-camera-on-ms-teams-for-2024/"><u>Easy Implementation of Snap Camera on MS Teams for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-geforce-nows-xc0f1103f-hitch-in-windows-11/"><u>Eliminate GeForce Now's Xc0f1103f Hitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-windows-11-is-operational-3-strategies/"><u>Ensuring Windows 11 Is Operational: 3 Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-windows-11-key-purchases/"><u>Essential Guide to Windows 11 Key Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/express-guide-to-determine-windows-11-gpu-variant/"><u>Express Guide to Determine Windows 11 GPU Variant</u></a></li>
<li><a href="https://techidaily.com/factory-reset-on-apple-iphone-14-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-the-most-out-of-windows-backup-features/"><u>Get the Most Out of Windows Backup Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-the-sid-of-any-user-in-windows-11/"><u>How to Find the SID of Any User in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-noisy-or-cracking-audio-outputs-on-windows-11-and-7-systems/"><u>How to Fix Noisy or Cracking Audio Outputs on Windows 11 and 7 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-screen-flickering-and-flashing-on-windows-10-and-11/"><u>How to Fix Screen Flickering and Flashing on Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-lost-windows-patch-service/"><u>How to Reactivate Lost Windows Patch Service</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-show-wi-fi-password-on-honor-magic-6-pro-by-drfone-android/"><u>How to Show Wi-Fi Password on Honor Magic 6 Pro</u></a></li>
<li><a href="https://extra-resources.techidaily.com/improving-speed-of-powerpoint-media-streaming/"><u>Improving Speed of PowerPoint Media Streaming</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-can-i-remove-the-apple-watch-activation-lock-by-iphone-xs-max-without-the-previous-owner-by-drfone-ios/"><u>In 2024, Can I Remove the Apple Watch Activation Lock By iPhone XS Max without the Previous Owner?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-11-ways-to-open-control-panel/"><u>Master Your Machine: 11 Ways to Open Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-words-best-windows-apps-for-writers/"><u>Mastering Words: Best Windows Apps for Writers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-win-11-experience-game-changing-advice-for-the-winning-side/"><u>Optimizing Your Win 11 Experience: Game-Changing Advice for the Winning Side</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-secure-authentication-problems-with-the-epic-launcher/"><u>Overcoming Secure Authentication Problems with the Epic Launcher</u></a></li>
<li><a href="https://extra-information.techidaily.com/pinpointing-the-premier-hdr-cameras-for-photography/"><u>Pinpointing the Premier HDR Cameras for Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bing-chat-integration-in-windows-11/"><u>Quick Guide to Bing Chat Integration in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-outlook-responses-a-windows-fix-guide/"><u>Quick Outlook Responses: A Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-preview-hurdles-in-windows-version-of-office-mail/"><u>Removing Preview Hurdles in Windows Version of Office Mail</u></a></li>
<li><a href="https://extra-skills.techidaily.com/reviewers-guide-to-yuneec-typhoon-h-performance-for-2024/"><u>Reviewer’s Guide to Yuneec Typhoon H Performance for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-windows-11s-ccleaner-functionality/"><u>Revitalizing Windows 11'S CCleaner Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-syncopation-combining-dropbox-and-googledrive-driveletters/"><u>Simplifying Syncopation: Combining Dropbox and GoogleDrive DriveLetters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-language-switching-made-simple-with-windows-keys/"><u>Speedy Language Switching Made Simple with Windows Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilize-your-game-solving-apex-legends-on-win11/"><u>Stabilize Your Game: Solving Apex Legends on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-setups-mastering-the-invisible-menu-features/"><u>Stealthy Setups: Mastering the Invisible Menu Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-commence-quickly-open-windows-and-sticky-notes/"><u>Streamlined Commence: Quickly Open Windows and Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-efficiency-in-windows-using-smart-launcher-tech/"><u>Supercharge Efficiency in Windows Using Smart Launcher Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-real-deal-on-applecareplus-does-the-extra-security-make-financial-sense/"><u>The Real Deal on AppleCare+ – Does the Extra Security Make Financial Sense?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-automated-file-deletion-on-windows/"><u>The Ultimate Guide to Automated File Deletion on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-windows-pens-tabs-ideal-notetakers/"><u>Top 7 Windows Pens' Tabs: Ideal Notetakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-to-emulate-macos-the-top-5-approaches/"><u>Transforming Windows to Emulate macOS: The Top 5 Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0x80070522-in-windows-regain-user-rights/"><u>Unraveling Error Code 0X80070522 in Windows: Regain User Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-modern-standby-a-critical-analysis/"><u>Unveiling Modern Standby: A Critical Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgraded-performance-ahead-steps-to-amplify-virtual-memory-in-windows-11/"><u>Upgraded Performance Ahead: Steps to Amplify Virtual Memory in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-should-i-do-if-i-cant-upgrade-my-pc-to-windows-11/"><u>What Should I Do If I Can't Upgrade My PC to Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-if-windows-wont-show-notification-badges-on-taskbar-icons/"><u>What to Do if Windows Won’t Show Notification Badges on Taskbar Icons</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>