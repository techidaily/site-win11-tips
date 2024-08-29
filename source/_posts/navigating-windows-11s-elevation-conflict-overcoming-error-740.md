---
title: "Navigating Windows 11'S Elevation Conflict: Overcoming Error #740"
date: 2024-08-28T01:14:19.543Z
updated: 2024-08-29T01:14:19.543Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Windows 11'S Elevation Conflict: Overcoming Error #740"
excerpt: "This Article Describes Navigating Windows 11'S Elevation Conflict: Overcoming Error #740"
keywords: Win11ElevationError,ResolveWin11Error740,FixWin11ElevationConflict,Windows11ErrorResolution,OvercomingWindowsError740,Win11HeightIssueSolution,Error740InWin11Navigation
thumbnail: https://thmb.techidaily.com/cc4de72d7f182f924611ffcdd9be6d67698446b35913acbf3e4fc8c5af445646.jpg
---

## Navigating Windows 11'S Elevation Conflict: Overcoming Error #740

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://buynow-marvelous.techidaily.com/yakuza-like-a-dragon-review-the-essential-role-playing-journey-you-need-to-embark-on/"><u>'Yakuza: Like a Dragon' Review - The Essential Role-Playing Journey You Need to Embark On</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-ladies-of-youtube-discovering-top-10-female-influencers/"><u>[New] 2024 Approved  Ladies of YouTube  Discovering Top 10 Female Influencers</u></a></li>
<li><a href="https://youtube-data.techidaily.com/rafting-yt-masterpieces-for-igtv-showcase/"><u>[New] Crafting YT Masterpieces for IGTV Showcase</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-growth-hurdle-cleared-500-subscribers-win/"><u>[New] In 2024, Growth Hurdle Cleared  500 Subscribers Win</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-leading-lists-compelling-google-cardboard-vr-game-selections/"><u>[New] Leading Lists  Compelling Google Cardboard VR Game Selections</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-safekeeping-sensitive-visuals-from-public-eyes/"><u>[New] Safekeeping Sensitive Visuals From Public Eyes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-shining-up-photos-on-instagram-three-effective-ways-for-2024/"><u>[New] Shining Up Photos on Instagram  Three Effective Ways for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-guide-to-decreasing-sounds-prominence-in-lumafusion/"><u>[New] The Ultimate Guide to Decreasing Sounds' Prominence in Lumafusion</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-5-effective-ways-of-resizing-your-igtv-videos-for-2024/"><u>[Updated] 5 Effective Ways of Resizing Your IGTV Videos for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-from-beginner-to-expert-in-funimate-for-2024/"><u>[Updated] From Beginner to Expert in Funimate for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-from-concept-to-completion-an-instagram-video-strategy-manual-for-2024/"><u>[Updated] From Concept to Completion  An Instagram Video Strategy Manual for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-tech-savvy-strategies-to-maximize-whiteboard-functionality-across-devices/"><u>[Updated] Tech-Savvy Strategies to Maximize Whiteboard Functionality Across Devices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-master-igtv-edits-top-10-tools-ranked/"><u>2024 Approved  Master IGTV Edits  Top 10 Tools Ranked</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/affordable-lenovo-tab-m10-hd-202n-review-ultimate-guide-for-web-browsing-and-media-streaming/"><u>Affordable Lenovo Tab M10 HD 202N Review: Ultimate Guide for Web Browsing & Media Streaming</u></a></li>
<li><a href="https://extra-information.techidaily.com/asmr-quality-meets-economic-realities-for-2024/"><u>ASMR Quality Meets Economic Realities for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-garmin-vivomove-hr-watch-review-elegant-design-meets-fitness-tracking/"><u>Comprehensive Garmin Vivomove HR Watch Review - Elegant Design Meets Fitness Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/data-synchronization-merging-in-win1011-systems/"><u>Data Synchronization: Merging in WIN10/11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/decided-no-endorsement-of-opengl-by-drivers/"><u>Decided: No Endorsement of OpenGL by Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-internal-auditory-graph-layouts/"><u>Deciphering Windows' Internal Auditory Graph Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-requires-elevation-error-in-windows-11-devices/"><u>Eliminating the Requires Elevation Error in Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-invisible-windows-11-account-entry-screen/"><u>Fixes for Invisible Windows 11 Account Entry Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-homescreen-activation-in-windows-11/"><u>Guide to Homescreen Activation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-perform-common-windows-actions-with-shortcuts/"><u>How to Perform Common Windows Actions With Shortcuts</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-elevate-video-calls-browse-through-our-top-5-hd-webcams-and-mics/"><u>In 2024, Elevate Video Calls - Browse Through Our Top 5 HD Webcams & Mics</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-open-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Open to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-mastering-massive-igtv-audience-engagement-essential-steps/"><u>In 2024, Mastering Massive IGTV Audience Engagement  Essential Steps</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-apple-iphone-15-plus-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock On your Apple iPhone 15 Plus</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-technology-with-toms-hardware-expertise-the-definitive-guide/"><u>Mastering Technology with Tom's Hardware Expertise - The Definitive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11-integrating-advanced-run-command/"><u>Maximizing Windows 11: Integrating Advanced Run Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ms-project-skills-keyboard-speedup-secrets/"><u>MS Project Skills: Keyboard Speedup Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-speeds-in-windows-edge-win10win11/"><u>Overcoming Low Speeds in Windows Edge (Win10/Win11)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/polishing-your-figma-creations-expert-backdrop-extraction/"><u>Polishing Your Figma Creations  Expert Backdrop Extraction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-default-settings-for-folder-display-mode/"><u>Reclaiming Default Settings for Folder Display Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-lost-5ghz-connectivity-for-your-windows-11-pc/"><u>Regain Lost 5GHz Connectivity for Your Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-fidelity-in-windows-colors/"><u>Reigniting Fidelity in Windows Colors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-wireless-network-detection-on-windows-11/"><u>Reigniting Wireless Network Detection on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-your-pcs-overwatch-2-lossed-graphic-error/"><u>Resolving Your PC’s Overwatch 2 Lossed Graphic Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reboot-and-reset-file-explorer-ui/"><u>Strategies to Reboot and Reset File Explorer UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-win-10-and-11-networks-with-telnet-easily/"><u>Tailoring Win 10 & 11 Networks with Telnet Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taskers-puzzle-edge-and-other-processes/"><u>Tasker's Puzzle: Edge and Other Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-better-sighting-of-tasks-on-windows-desktops/"><u>Techniques for Better Sighting of Tasks on Windows Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-windows-user-manual-for-speech-to-text-conversion/"><u>The Complete Window's User Manual for Speech-to-Text Conversion</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-insiders-look-at-online-television-unveiling-the-secrets-of-smart-tvs/"><u>The Insider's Look at Online Television: Unveiling the Secrets of Smart TVs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-maximize-laptop-lifespan-power-management-basics/"><u>Tips: Maximize Laptop Lifespan - Power Management Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-tactics-for-vmstart-disruptions-on-wm11os/"><u>Top 8 Tactics for VMstart Disruptions on WM11OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-resolving-windows-discord-latency-issues/"><u>Troubleshooting: Resolving Windows Discord Latency Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-complexities-of-microsofts-error-0x80040610/"><u>Unraveling the Complexities of Microsoft's Error 0X80040610</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-system-accessibility-context-menu-enhancement-in-win1011/"><u>Upgrade System Accessibility: Context Menu Enhancement in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-free-space-tackling-temporary-files-head-on/"><u>Win-Free Space: Tackling Temporary Files Head On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-photos-command-center-key-navigation/"><u>Windows Photos: Command Center Key Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-active-windows-sound-services/"><u>Winning Back Active Windows Sound Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-lossed-rendering-support-in-overwatch-2/"><u>Winning Back Lossed Rendering Support in Overwatch 2</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-infinix-smart-7-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/your-go-to-list-of-11-most-reliable-free-online-film-download-sites/"><u>Your Go-To List of 11 Most Reliable Free Online Film Download Sites</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>