---
title: Overhauling Deactivated Temperature Control on WinOS
date: 2024-08-16T02:36:39.445Z
updated: 2024-08-17T02:36:39.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overhauling Deactivated Temperature Control on WinOS
excerpt: This Article Describes Overhauling Deactivated Temperature Control on WinOS
keywords: Windows Temp Fix Guide,Reactivate OS Temperature Control,WinOS Cooling Adjustment,Overhaul Deactivated WinTemp,Restore Temp Settings WinXP,Temperature Control WinReg,Revive XP Temp Controls
thumbnail: https://thmb.techidaily.com/333b95c20ee75bfb354881848c952d7c6576f1601ed8967bdbaf6f2fda50fa89.jpg
---

## Overhauling Deactivated Temperature Control on WinOS

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://facebook-video-footage.techidaily.com/new-how-to-embed-a-youtube-playlist-on-a-website-for-2024/"><u>[New] How to Embed A YouTube Playlist On a Website for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-master-your-media-comprehensive-guide-to-instagram-converters-windowsmac-for-2024/"><u>[New] Master Your Media  Comprehensive Guide to Instagram Converters (Windows/Mac) for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ini-magnate-ryan-kajis-staggering-income-from-video-platform-for-2024/"><u>[New] Mini Magnate  Ryan Kaji’s Staggering Income From Video Platform for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-vanguard-audio-visual-makers-virtual-showcase/"><u>[New] The Vanguard Audio-Visual Makers' Virtual Showcase</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-automatic-youtube-playback-made-simple-for-social-networking-sites-like-facebook/"><u>[Updated] Automatic YouTube Playback Made Simple for Social Networking Sites Like Facebook</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-charting-your-path-to-youtube-affiliate-status-with-10k-vistas-goal/"><u>[Updated] Charting Your Path to YouTube Affiliate Status with 10K Vistas Goal</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-dancefloor-dynamics-top-rated-dj-video-selections-for-2024/"><u>[Updated] Dancefloor Dynamics  Top-Rated DJ Video Selections for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-unlocking-the-seo-puzzle-strategies-that-elevate-your-podcasts/"><u>[Updated] In 2024, Unlocking the SEO Puzzle  Strategies That Elevate Your Podcasts</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-decipher-youtubes-mysteries-with-advanced-insights-from-social-blade/"><u>2024 Approved  Decipher YouTube's Mysteries with Advanced Insights From Social Blade</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-essential-vlogging-topics-to-explore-now/"><u>2024 Approved  Essential Vlogging Topics to Explore Now</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-steam-software-file-recovery-problem/"><u>Addressing Steam Software File Recovery Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-your-pc-reboot-journey-with-these-trios/"><u>Craft Your PC Reboot Journey with These Trios</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-lasting-trash-area-on-your-windows-desktop-space/"><u>Creating a Lasting Trash Area on Your Windows Desktop Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-to-the-core-how-to-fix-win-error-31-in-windows/"><u>Cutting to the Core: How to Fix WIN Error 31 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-to-access-windows-troubleshooting-with-hotkeys/"><u>Efficient Ways to Access Windows Troubleshooting with Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-essential-services-for-seamless-windows-11-launches/"><u>Enabling Essential Services for Seamless Windows 11 Launches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-user-sign-in-after-setbacks/"><u>Enabling Windows User Sign-In After Setbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-disks-understanding-the-c-and-d-narrative/"><u>Examining Disks: Understanding the C & D Narrative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-quick-uninstall-of-win11-printers/"><u>Expert Guide: Quick Uninstall of Win11 Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-problem-when-multiple-apps-claim-same-audio/"><u>Fixing the Problem When Multiple Apps Claim Same Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-dated-devices-to-future-proof-systems-with-app-transfer/"><u>From Dated Devices to Future-Proof Systems with App Transfer</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-started-with-brother-l2700dw-printer-comprehensive-driver-downloads-and-setup-for-windows-users/"><u>Get Started with Brother L2700DW Printer: Comprehensive Driver Downloads and Setup for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-admin-policy-block-in-windows-software-setup/"><u>How to Bypass 'Admin Policy' Block in Windows Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-update-directx-on-your-pc/"><u>How to Download and Update DirectX on Your PC</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-motorola-g24-power-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Motorola G24 Power If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-your-steam-library-auto-synchronize-properly/"><u>How to Make Your Steam Library Auto-Synchronize Properly</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-15-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 15 To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-numeric-precision-the-art-of-editing-tiktok-counts/"><u>In 2024, Numeric Precision  The Art of Editing TikTok Counts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-transform-your-social-media-impact-through-effective-live-broadcasts/"><u>In 2024, Transform Your Social Media Impact Through Effective Live Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-windows-calculator-app-less-bright/"><u>Make Windows Calculator App Less Bright</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-interface-woes-top-5-windows-correction-tips/"><u>Mastering Interface Woes: Top 5 Windows Correction Tips</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-countdown-in-minutes-a-3-part-guide-to-fcpx-timers/"><u>New In 2024, Countdown in Minutes A 3-Part Guide to FCPX Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-unforeseen-system-shuts-in-win11/"><u>Preventing Unforeseen System Shuts in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-stubborn-shift-on-pc/"><u>Quick Fixes for Stubborn Shift on PC.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-balanced-sound-from-both-sides-of-win-headphones/"><u>Restoring Balanced Sound From Both Sides of WIN Headphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-microsoft-words-speech-functionality-on-pc/"><u>Reviving Microsoft Word's Speech Functionality on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/security-first-in-upgrade-to-windows-11/"><u>Security First in Upgrade to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-system-essential-techniques-for-managing-windows-folders/"><u>Simplify Your System: Essential Techniques for Managing Windows Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stopping-accidental-shortcuts-at-work/"><u>Solutions for Stopping Accidental Shortcuts at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-other-application-happens-with-sound-errors/"><u>Steps to Solve Other Application Happens with Sound Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-way-to-manage-your-stickies-across-devices/"><u>The Easy Way to Manage Your Stickies Across Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-step-by-step-guide-to-convert-your-voice-into-written-words-on-windows/"><u>The Step-by-Step Guide to Convert Your Voice Into Written Words on Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-guide-to-video-call-capturing-on-devices/"><u>The Ultimate Guide to Video Call Capturing on Devices</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-xiaomi-redmi-note-12-pro-4g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Xiaomi Redmi Note 12 Pro 4G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-potential-of-android-and-windows-11-as-one-display/"><u>Unleashing the Potential of Android and Windows 11 as One Display</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581230819-what-language-is-spoken-in-croatia/"><u>What Language Is Spoken In Croatia?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-updates-made-simple-resolving-error-0xc1900101/"><u>Win11 Updates Made Simple: Resolving Error 0xC1900101</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-check-up-activation-verification-steps/"><u>Windows 11 Check-Up: Activation Verification Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-users-prefer-cleaner-start-menus/"><u>Windows 11 Users Prefer Cleaner Start Menus</u></a></li>
</ul></div>
