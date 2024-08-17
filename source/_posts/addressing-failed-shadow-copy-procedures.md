---
title: Addressing Failed Shadow Copy Procedures
date: 2024-08-16T01:18:24.038Z
updated: 2024-08-17T01:18:24.038Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Failed Shadow Copy Procedures
excerpt: This Article Describes Addressing Failed Shadow Copy Procedures
keywords: Shadow Copy Fail,File Sync Errors,Backup Restart,Storage Recovery,Data Safeguard,Archive Corruption,Save Exceptions
thumbnail: https://thmb.techidaily.com/696965aa1a0f4c21fdfd456761bb63f354f50ffc3b27173b44a827d0fae8995e.jpg
---

## Addressing Failed Shadow Copy Procedures

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-secrets-to-mass-downloading-videos-from-tiktok/"><u>[New] 2024 Approved  Secrets to Mass Downloading Videos From TikTok</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-ultimate-how-to-applying-captions-to-pictures-in-pcmac-environments/"><u>[New] 2024 Approved  The Ultimate How-To  Applying Captions to Pictures in PC/Mac Environments</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-transforming-your-android-into-a-broadcast-hub/"><u>[New] 2024 Approved  Transforming Your Android Into a Broadcast Hub</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-maximize-video-impact-with-full-screen-settings/"><u>[New] In 2024, Maximize Video Impact with Full-Screen Settings</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-art-of-extended-frame-videos-on-iphone/"><u>[New] In 2024, The Art of Extended Frame Videos on iPhone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-reimagining-storytelling-through-vr-screens/"><u>[New] Reimagining Storytelling Through VR Screens</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-free-film-festivals-at-your-fingertips-top-10-picks-for-viewers/"><u>[Updated] 2024 Approved  Free Film Festivals at Your Fingertips - Top 10 Picks for Viewers</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-how-to-spice-up-your-discord-conversations-with-interactive-content-like-gifs/"><u>[Updated] 2024 Approved  How to Spice Up Your Discord Conversations with Interactive Content Like GIFs</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-from-challenges-to-characters-best-gif-converters-for-tiktoks-for-2024/"><u>[Updated] From Challenges to Characters  Best GIF Converters for TikToks for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-imovie-tricks-for-perfecting-your-video-introduction-craft/"><u>[Updated] IMovie Tricks for Perfecting Your Video Introduction Craft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-steps-to-wipe-your-drives-partitions-in-windows/"><u>4 Easy Steps to Wipe Your Drive's Partitions in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-framework-for-employing-videos-in-educational-settings/"><u>A Framework for Employing Videos in Educational Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimal-performance-kali-on-windows/"><u>Achieve Optimal Performance: Kali on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-of-error-80080300-a-guide-to-enhanced-teamwork-on-windows/"><u>Breaking Barriers of Error 80080300: A Guide to Enhanced Teamwork on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-dxgierror-with-device-reattachment/"><u>Combat DXGI_ERROR with Device Reattachment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-prompt-pranks-engage-in-5-digital-delights/"><u>Command Prompt Pranks: Engage in 5 Digital Delights</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-review-of-kootek-laptop-cooler-an-excellent-multifunctional-choice/"><u>Comprehensive Review of Kootek Laptop Cooler: An Excellent Multifunctional Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-strategies-for-overcoming-file-access-barriers-in-windows/"><u>Comprehensive Strategies for Overcoming File Access Barriers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-and-configuring-your-win11-screensavers/"><u>Crafting and Configuring Your Win11 Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-windows-navigator-placement-of-this-pc-icons/"><u>Customizing Windows Navigator: Placement of 'This PC' Icons</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Poco F5 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-in-windows-11-notepad/"><u>Enhancing User Experience in Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-the-prospects-why-choose-win11-over-macos/"><u>Examining the Prospects: Why Choose Win11 Over MacOS</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-video-editing-magic-top-special-effects-apps-for-ios-and-android-for-2024/"><u>Free Video Editing Magic Top Special Effects Apps for iOS and Android for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/how-to-facetime-on-android-easily-for-2024/"><u>How To Facetime on Android Easily for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-xiaomi-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Xiaomi Phone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-boosting-clickthrough-rates-with-attention-grabbing-youtube-thumbnails/"><u>In 2024, Boosting Clickthrough Rates with Attention-Grabbing YouTube Thumbnails</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Realme 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-rapid-video-grabber-and-audible-guide-system/"><u>In 2024, Rapid Video Grabber & Audible Guide System</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-ultimate-guide-to-movie-trailer-makers-for-mac-and-windows-users/"><u>In 2024, Ultimate Guide to Movie Trailer Makers for Mac and Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-power-off-windows-11-when-not-in-use/"><u>Instantly Power Off Windows 11 When Not in Use</u></a></li>
<li><a href="https://games-able.techidaily.com/journey-through-the-best-of-indie-game-realms/"><u>Journey Through the Best of Indie Game Realms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-aligning-sticky-notes-in-w11/"><u>Mastering the Art of Aligning Sticky Notes in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-modifying-windows-files/"><u>Mastering the Art of Modifying Windows Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-task-runner-error-code-0x8007000f-in-winos/"><u>Mastery over Task Runner Error Code 0X8007000f in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-monitor-mastery-personalized-pixelation-per-system-screen/"><u>Multi-Monitor Mastery: Personalized Pixelation per System Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-pc-protection-limiting-multiple-antiviruses/"><u>Optimal PC Protection: Limiting Multiple Antiviruses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-sudden-device-disconnection-dxgi/"><u>Remedy for Sudden Device Disconnection (DXGI)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-quest-preventing-crashes-on-your-pcs-platform/"><u>Securing Your Quest: Preventing Crashes on Your PC's Platform</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/shutter-speed-mastery-for-chromebook-users-method-4/"><u>Shutter Speed Mastery for Chromebook Users (Method #4)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-for-windows-11s-0x8004def5-glitches/"><u>Swift Solutions for Windows 11'S 0X8004DEF5 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-mute-microphone-issue-during-video-recordings/"><u>Tackling Mute Microphone Issue During Video Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-web-pages-to-desktop-level-with-windows-guide/"><u>Taking Web Pages to Desktop Level with Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-keep-microsoft-teams-from-crashing-win11-win10/"><u>Tips to Keep Microsoft Teams From Crashing Win11, Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/underrated-yet-stunning-best-windows-11-themes/"><u>Underrated, Yet Stunning: Best Windows 11 Themes</u></a></li>
</ul></div>
