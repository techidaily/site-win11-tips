---
title: Tackling Frozen Volume Shadows in Operating Systems
date: 2024-08-16T01:54:20.381Z
updated: 2024-08-17T01:54:20.381Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Frozen Volume Shadows in Operating Systems
excerpt: This Article Describes Tackling Frozen Volume Shadows in Operating Systems
keywords: Freeze Vol Shadow Fix OS,OS Frozen Volume Shades,Resolving Ice Volume Shadows,Frosty Shadow Reduction OS,Thawing OS Vol Shade Issue,De-Freeze Shadows Operating,Eliminate Freezing Shadows OS
thumbnail: https://thmb.techidaily.com/0b4741c5a95a2eb27426575b3e77bfe93d41de0ce8390e58e556e7c4a810a2f7.jpg
---

## Tackling Frozen Volume Shadows in Operating Systems

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

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 6\. Set Windows to Perform a Clean Boot
![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-content.techidaily.com/new-direct-video-delivery-facebook-to-whatsapp-connection-for-2024/"><u>[New] Direct Video Delivery  Facebook to WhatsApp Connection for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-an-anthology-of-admiration-highlighting-top-10-reddit-threads/"><u>[New] In 2024, An Anthology of Admiration  Highlighting Top 10 Reddit Threads</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-audiovisual-fusion-incorporating-songs-in-ig-media/"><u>[New] In 2024, Audiovisual Fusion  Incorporating Songs in IG Media</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-perfect-full-screen-display-on-fb-videos-step-by-step-for-2024/"><u>[New] Perfect Full-Screen Display on FB Videos, Step by Step for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/nlock-8-youtube-fitness-ideas-for-viewers-active-participation-for-2024/"><u>[New] Unlock 8 YouTube Fitness Ideas for Viewers' Active Participation for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-crafting-captivating-reels-musical-integration-strategies/"><u>[Updated] Crafting Captivating Reels  Musical Integration Strategies</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-enhance-well-being-and-flexibility-with-these-outstanding-channels-for-2024/"><u>[Updated] Enhance Well-Being & Flexibility with These Outstanding Channels for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-explore-top-rated-windows-10-video-capture-software/"><u>[Updated] Explore Top-Rated Windows 10 Video Capture Software</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-avoid-and-reverse-strikes-on-your-youtube-channel-for-2024/"><u>[Updated] How to Avoid and Reverse Strikes on Your YouTube Channel for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-top-25-mentors-in-modern-social-media-mastery-on-instagram/"><u>[Updated] In 2024, Top 25 Mentors in Modern Social Media Mastery on Instagram</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-the-essence-of-pixiz-crafting-compelling-stills-to-video-transformations-for-2024/"><u>[Updated] The Essence of Pixiz  Crafting Compelling Stills-to-Video Transformations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-guide-to-managing-windows-key/"><u>A Comprehensible Guide to Managing Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guidetosettingupdarkinterfaceonwinnotepad/"><u>A GuideToSettingUpDarkInterfaceOnWinNotepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-handy-tutorial-to-combat-xfffeeee-in-windows/"><u>A Handy Tutorial to Combat XFFFEEEE in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-for-moving-programs-in-windows-11/"><u>A Step-by-Step Approach for Moving Programs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abort-windows-over-the-top-contrast-mode/"><u>Abort Windows' Over-the-Top Contrast Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-advanced-settings-for-windows-11s-bar/"><u>Achieve Advanced Settings for Windows 11'S Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-system-restore-five-tactics/"><u>Activating System Restore: Five Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ad-free-horizon-your-future-with-w11s-start-menu/"><u>Ad-Free Horizon: Your Future with W11's Start Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-printer-offline-errors-in-windows-11/"><u>Addressing 'Printer Offline' Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-internal-error-during-win10-remote-access/"><u>Addressing Internal Error During Win10 Remote Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-connected-systems-error-windows/"><u>Addressing No Connected Systems Error Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-selectable-items-on-microsofts-new-os/"><u>Addressing Non-Selectable Items on Microsoft's New OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-phantom-noise-fixing-inactive-notifications-from-phone-link/"><u>Addressing Phantom Noise: Fixing Inactive Notifications From Phone Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-absence-of-msvcr110dll-a-guide/"><u>Addressing the Absence of msvcr110.dll: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unauthorized-profiles-on-pcs-win1011-guide/"><u>Addressing Unauthorized Profiles on PCs: Win10/11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-and-reset-windows-11s-touch-keyboard-layout/"><u>Adjust and Reset Windows 11'S Touch Keyboard Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-insights-into-integrating-disjoint-windows-partitions/"><u>Advanced Insights Into Integrating Disjoint Windows Partitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-settings-for-drive-mappings-win11/"><u>Advanced Settings for Drive Mappings (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-file-interaction-utilizing-checkbox-filters-on-win11/"><u>Amplify File Interaction: Utilizing Checkbox Filters on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-app-size-efficiency/"><u>Assessing Windows App Size Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/atlasos-makeover-new-life-for-vintage-pcs/"><u>AtlasOS Makeover: New Life for Vintage PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-free-software-picks-with-maximum-safety-standards/"><u>Best Free Software Picks with Maximum Safety Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-windows-file-structure-max-156/"><u>Best Practices for Windows File Structure (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blank-screenshare-reconnecting-windows-microphone-to-google-meet/"><u>Blank Screenshare: Reconnecting Windows Microphone to Google Meet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bluetooth-harmony-linking-airpods-with-windows/"><u>Bluetooth Harmony: Linking AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-efficiency-the-ultimate-guide-to-wintools/"><u>Boost Windows Efficiency: The Ultimate Guide to Wintools</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-apple-iphone-xs-drfone-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/elevate-your-marvel-gaming-experience-the-ultimate-guide-to-fixing-guardians-of-the-galaxy-on-pc/"><u>Elevate Your Marvel Gaming Experience - The Ultimate Guide to Fixing Guardians of the Galaxy on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319213526-essential-tips-for-a-working-winshift/"><u>Essential Tips for a Working WinShift.</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-poco-f5-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Poco F5 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719203477260-how-to-unfreeze-google-chrome-in-windows-11-fastly-find-out-now/"><u>How to Unfreeze Google Chrome in Windows 11 Fastly? Find Out Now</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-itel-p55t-by-drfone-android/"><u>In 2024, How to Bypass FRP from Itel P55T?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-locked-apple-id-on-iphone-11-by-drfone-ios/"><u>In 2024, How to Fix Locked Apple ID on iPhone 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-iphone-12-mini-online-without-jailbreak-by-drfone-ios/"><u>In 2024, How to Unlock SIM Card on iPhone 12 mini online without jailbreak</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-tricks-for-capturing-video-tweets-and-converting-to-audible-format/"><u>In 2024, Tricks for Capturing Video Tweets and Converting to Audible Format</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206718516-laptop-mouse-malfunctions-heres-how-to-restore-functionality-and-beat-the-lag/"><u>Laptop Mouse Malfunctions? Here's How to Restore Functionality and Beat the Lag!</u></a></li>
<li><a href="https://data-wizards.techidaily.com/next-move-after-advanced-video-fix-failure/"><u>Next Move After Advanced Video Fix Failure</u></a></li>
<li><a href="https://extra-support.techidaily.com/revitalize-your-photos-bringing-back-photo-viewer-in-win-11-for-2024/"><u>Revitalize Your Photos  Bringing Back Photo Viewer in Win 11 for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/selecting-the-best-hdr-cameras-simplified-for-2024/"><u>Selecting the Best HDR Cameras Simplified for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719309481571-streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-password-cracking-tools-for-itel-s23plus-by-drfone-android/"><u>Top 10 Password Cracking Tools For Itel S23+</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-potential-a-guide-to-what-chatgpt-jailbreaking-involves/"><u>Unlocking Potential: A Guide to What ChatGPT Jailbreaking Involves</u></a></li>
</ul></div>
