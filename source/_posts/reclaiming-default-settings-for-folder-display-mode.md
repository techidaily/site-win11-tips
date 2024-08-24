---
title: Reclaiming Default Settings for Folder Display Mode
date: 2024-08-23T07:05:51.957Z
updated: 2024-08-24T07:05:51.957Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Default Settings for Folder Display Mode
excerpt: This Article Describes Reclaiming Default Settings for Folder Display Mode
keywords: Reclaim Folder Views,Reset Folders Display,Revise Folder Mode,Change Folder Display,Fix Default FolderView,Update Folder Settings,Modify Directory ViewMode
thumbnail: https://thmb.techidaily.com/3269c858221e8ab75b91d65fc2cbdc3bf0d972fb510d01ae54b3ad8d22470d02.jpg
---

## Reclaiming Default Settings for Folder Display Mode

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must[create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will[open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-methods-for-restoring-full-display-in-youtube-videos/"><u>[New] 2024 Approved  Methods for Restoring Full Display in YouTube Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-a-deeper-dive-understanding-ez-grabbers-capabilities/"><u>[New] A Deeper Dive  Understanding EZ Grabber's Capabilities</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-instant-sticker-transformation-your-guide-to-making-gifs-pop-in-telegram-and-more/"><u>[Updated] 2024 Approved  Instant Sticker Transformation  Your Guide to Making GIFs Pop in Telegram & More</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-obs-studio-vs-fraps-deciding-the-ultimate-screen-grab-software/"><u>[Updated] In 2024, OBS Studio vs Fraps  Deciding the Ultimate Screen Grab Software</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-the-ultimate-list-of-6-instagram-reel-enhancers/"><u>[Updated] In 2024, The Ultimate List of 6 Instagram Reel Enhancers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-the-art-of-creating-shareable-content-on-fb/"><u>[Updated] The Art of Creating Shareable Content on Fb</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-unseen-approaches-to-bypass-online-educational-content/"><u>[Updated] Unseen Approaches to Bypass Online Educational Content</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-enhanced-reality-gaming-top-10-pc-vr-players-for-virtual-adventures/"><u>2024 Approved  Enhanced Reality Gaming  Top 10 PC VR Players for Virtual Adventures</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-ipads-drawing-dynasty-top-8-sketch-apps/"><u>2024 Approved  IPad's Drawing Dynasty  Top 8 Sketch Apps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-video-to-dvd-burners-get-video-to-dvd-on-windows-mac-maveric-for-2024/"><u>Best Video to DVD Burners - Get Video to DVD on Windows / Mac (Maveric) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commanding-pcs-reactive-devices-during-rest/"><u>Commanding PC's Reactive Devices During Rest</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-resolve-windows-update-error-0x8024002e-once-and-for-all/"><u>Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All!</u></a></li>
<li><a href="https://article-helps.techidaily.com/craft-compelling-youtube-titles-faster-than-ever/"><u>Craft Compelling YouTube Titles Faster Than Ever</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-individualized-win11-screensavers/"><u>Designing Individualized Win11 Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/differences-highlighted-microsoft-and-local-account-divergences-on-pc/"><u>Differences Highlighted: Microsoft and Local Account Divergences on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-as-pie-fixing-the-top-11-windows-11-issues/"><u>Easy as Pie: Fixing the Top 11 Windows 11 Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-tips-for-resetting-ps5-gamepad/"><u>Essential Tips for Resetting PS5 Gamepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-quickly-engaging-windows-support-services/"><u>Expert Tips for Quickly Engaging Windows' Support Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/faster-start-up-methods-modify-windows-11s-booting-timeout/"><u>Faster Start-Up Methods: Modify Windows 11'S Booting Timeout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-portable-windows-devices/"><u>Five Portable Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-error-code-0x80073cf3-on-win11/"><u>Fixing Microsoft Store Error Code 0X80073CF3 on Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-blogging-to-broadcasting-scaling-up-your-youtube-presence-for-2024/"><u>From Blogging to Broadcasting  Scaling Up Your YouTube Presence for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-check-for-updates-context-menu-option-in-windows-11-and-11/"><u>How to Add a Check for Updates Context Menu Option in Windows 11 and 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-vivo-y36-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Vivo Y36?</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-from-motorola-razr-40-ultra-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Motorola Razr 40 Ultra Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-oneplus-nord-ce-3-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do OnePlus Nord CE 3 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oppo-a1-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Oppo A1 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-meizu-21-pro-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Meizu 21 Pro to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-and-fixing-windows-headset-mic-glitches/"><u>Identifying & Fixing Windows Headset Mic Glitches</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-top-no-fee-android-chat-apps-rated/"><u>In 2024, Top No-Fee Android Chat Apps Rated</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-tech-for-premium-macos-experience/"><u>Integrating Windows Tech for Premium macOS Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-windows-picture-cache-point/"><u>Locate Window’s Picture Cache Point</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-conflict-multiple-ms-logins/"><u>Mastering Device Conflict: Multiple MS Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-automatic-shutdowns-in-windows-11-os/"><u>Mitigating Automatic Shutdowns in Windows 11 OS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-fundamental-features-to-consider-when-selecting-an-audio-editor-for-mac-users-for-2024/"><u>New Fundamental Features to Consider When Selecting an Audio Editor for Mac Users for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-the-ultimate-guide-to-free-video-fx-apps-for-ios-and-android/"><u>New In 2024, The Ultimate Guide to Free Video FX Apps for iOS and Android</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/no-cost-to-you-heres-a-list-of-7-free-editing-apps/"><u>No Cost to You? Here's a List of 7 Free Editing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disk-read-issue-in-windows/"><u>Overcoming Disk Read Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-valorant-download-rate-woes-in-windows/"><u>Overcoming Low Valorant Download Rate Woes in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/picperfect-upgrade-mobile-photography-no-money-down/"><u>PicPerfect  Upgrade Mobile Photography No Money Down</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-looks-like-youre-stranded-from-xbox-app-windows/"><u>Removing the 'Looks Like You're Stranded' From Xbox App Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-fixing-the-to-do-syncheroom-dilemma/"><u>Swiftly Fixing the To Do Syncheroom Dilemma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-realign-windows-desktop-elements/"><u>Swiftly Realign Windows Desktop Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-concealreveal-windows-security-zones/"><u>Tactics to Conceal/Reveal Windows Security Zones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quick-and-easy-route-to-your-pcs-credential-vault-on-win11/"><u>The Quick and Easy Route to Your PC's Credential Vault on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-for-smooth-captions-essential-tips-on-windows-10/"><u>Troubleshoot for Smooth Captions: Essential Tips on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-0xc000003e-application-launch-failure-on-windows-11/"><u>Troubleshooting 0xC000003E Application Launch Failure on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-path-related-issues-in-windows-os/"><u>Troubleshooting Path-Related Issues in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-windows-monitoring-for-opened-apps/"><u>Turn Off Windows Monitoring for Opened Apps</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/vlog-basics-must-haves-for-first-timers/"><u>Vlog Basics  Must-Haves for First-Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-in-windows-should-you-delete-it/"><u>What Is Pagefile.sys in Windows? Should You Delete It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-edge-removal-made-simple/"><u>Win11 Edge Removal Made Simple</u></a></li>
</ul></div>
