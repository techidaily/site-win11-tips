---
title: Tackling the Incorrect File History Options in Windows
date: 2024-08-28T01:13:00.661Z
updated: 2024-08-29T01:13:00.661Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the Incorrect File History Options in Windows
excerpt: This Article Describes Tackling the Incorrect File History Options in Windows
keywords: Windows File Backup Mistakes,Correcting Windows Save Paths,Fixing Windows Restore Errors,Optimizing Windows Archive Settings,Windows History Save Adjustments,Preventing Data Loss in Windows,Ensuring Accurate Windows Recovery
thumbnail: https://thmb.techidaily.com/40d2bba30d8d7204e00531f0c8ae5a0019fd1a9406955c448a3c7d8503274e5e.jpg
---

## Tackling the Incorrect File History Options in Windows

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a[problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control** in the box and press**Enter** .
3. Click the**View by** drop-down menu and select**Large icons** .
4. Select**File History** from the Control Panel menu items.
5. Click the**Select drive** option from the left sidebar.
6. Select your preferred drive from the list and click**OK** .  
![Select File History Drive Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-file-history-drive-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
 After selecting your preferred drive, you’ll have to restart the File History feature on Windows. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to open the search menu.
2. Type**file history** in the search box and select the first result that appears.
3. In the Control Panel window that opens, click the**Turn off** button.
4. Wait for a few seconds and click the**Turn on** button.  
![Turn On File History in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-file-history-in-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to[show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

1. Open the Windows search menu.
2. Type**File Explorer Options** in the search box and press**Enter** .
3. Switch to the**View** tab and check the**Show hidden files, folders, and drives** option.
4. Hit**Apply** followed by**OK** .

 Now, delete the File History data from your system by following the steps below.

1. Press**Win + E** to open File Explorer.
2. Type the following path in the File Explorer’s address bar and press**Enter** .  
`%UserProfile%\AppData\Local\Microsoft\Windows\FileHistory`
3. Press**Ctrl + A** to select all the folders and click the**trash icon** at the top to delete them.  
![Delete File Hisotry AppData](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-file-hisotry-appdata.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## Fixing File History Errors on Windows

 After you apply the fixes listed above, the File History error should no longer bother you.

 Tired of dealing with File History errors on your Windows device? It might be a good idea to use a cloud storage service or third-party backup software to protect your important data.


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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-follow-the-flow-of-forum-fancies/"><u>[New] 2024 Approved  Follow the Flow of Forum Fancies</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-dark-moments-bright-shots-a-photographers-nighttime-guide/"><u>[New] Dark Moments, Bright Shots  A Photographer’s Nighttime Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-efficiently-organizing-online-gatherings-via-zoom-for-2024/"><u>[New] Efficiently Organizing Online Gatherings via Zoom for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-how-to-engage-fans-through-real-time-streams-mobile-edition/"><u>[New] In 2024, How to Engage Fans Through Real-Time Streams  Mobile Edition</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-simplify-your-social-media-uploading-multiple-photos-and-vids-on-ig/"><u>[New] In 2024, Simplify Your Social Media  Uploading Multiple Photos and Vids on IG</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-scripted-temporal-displacements-in-film-production/"><u>[New] Scripted Temporal Displacements in Film Production</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unlocking-user-preferences-with-instagrams-real-time-feedback/"><u>[New] Unlocking User Preferences with Instagram's Real-Time Feedback</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-8-best-multiple-video-call-and-chat-tools-for-conference-and-friends/"><u>[Updated] 2024 Approved  8 Best Multiple Video Call & Chat Tools for Conference and Friends</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-unifiedvision-mixer-hub/"><u>[Updated] 2024 Approved  UnifiedVision Mixer Hub</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-iview-harmony-ios-and-macos-slideshow-tool/"><u>[Updated] In 2024, IView Harmony  IOS & macOS Slideshow Tool</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-a-to-z-guide-to-recording-games-using-obs-for-2024/"><u>[Updated] The A-to-Z Guide to Recording Games Using OBS for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-create-captivating-photos-adding-motion-blur-in-photoshop/"><u>2024 Approved  Create Captivating Photos  Adding Motion Blur in Photoshop</u></a></li>
<li><a href="https://android-unlock.techidaily.com/7-ways-to-unlock-a-locked-samsung-galaxy-f15-5g-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Samsung Galaxy F15 5G Phone</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722119857126-avoid-downloading-the-malicious-google-bard-program-its-a-risk/"><u>Avoid Downloading the Malicious Google Bard Program - It's a Risk!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/comprehensive-guide-on-downloading-and-upgrading-epson-printer-drivers-specifically-tailored-for-windows-10-users/"><u>Comprehensive Guide on Downloading and Upgrading Epson Printer Drivers Specifically Tailored for Windows 10 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-rdp-error-codes-in-modern-windows-systems/"><u>Decoding RDP Error Codes in Modern Windows Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discounted-price-alert-high-resolution-8k-phrozen-sonic-mini-s-resin-3d-printer-for-325-only/"><u>Discounted Price Alert: High-Resolution 8K Phrozen Sonic Mini S Resin 3D Printer for $325 Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-the-most-effective-tool-for-win-soft-dependency/"><u>Discovering the Most Effective Tool for Win Soft Dependency</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-pokegoplusplus-still-work-on-apple-iphone-8-plusipad-drfone-by-drfone-virtual-ios/"><u>Does PokeGo++ still work on Apple iPhone 8 Plus/iPad? | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-m-audio-ultradj-fast-track-input-transformer-for-free/"><u>Download M-Audio UltraDJ Fast Track Input Transformer for Free!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-policy-management-using-gpresult/"><u>Empowering Policy Management Using GPResult</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-writing-capability-in-windows-1011/"><u>Enhancing File Writing Capability in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-system-safety-with-new-passwords-in-win-11/"><u>Enhancing System Safety with New Passwords in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-admin-command-execution-without-hurdles/"><u>Ensuring Admin Command Execution Without Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-procedure-to-clear-steams-domain-name-service-caches/"><u>Essential Procedure to Clear Steam's Domain Name Service Caches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-the-admin-restriction-error-message-on-pcs/"><u>How to Bypass the Admin Restriction Error Message on PCs</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Realme GT 5? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-game-bars-pc-doesnt-meet-hardware-requirements-for-captures-error-in-windows/"><u>How to Fix Game Bar’s “PC Doesn't Meet Hardware Requirements for Captures” Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-perform-common-windows-actions-with-shortcuts/"><u>How to Perform Common Windows Actions With Shortcuts</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-pinpoint-premium-video-keywords-on-youtube/"><u>How to Pinpoint Premium Video Keywords on YouTube</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-apple-id-activation-lock-on-apple-iphone-7-by-drfone-ios/"><u>How to Unlock Apple ID Activation Lock On Apple iPhone 7?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-samsung-galaxy-xcover-7-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Samsung Galaxy XCover 7 to iPhone | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-vivo-v30-pro-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Vivo V30 Pro Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-realme-v30-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Realme V30 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-oneplus-nord-ce-3-5g-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from OnePlus Nord CE 3 5G to iPod | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-nokia-130-music-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Nokia 130 Music Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-search-for-integrity-how-to-filter-out-fake-windows-apps/"><u>In Search for Integrity: How to Filter Out Fake Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-11-for-effective-task-juggling/"><u>Leveraging Windows 11 for Effective Task Juggling</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/mac-users-guide-convert-youtube-music-files-to-mp3/"><u>Mac Users' Guide  Convert YouTube Music Files to MP3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-full-privilege-access-to-terminal-a-snap-shot/"><u>Make Full-Privilege Access to Terminal A Snap Shot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-concurrent-archive-decompression-in-a-digital-age/"><u>Mastering Concurrent Archive Decompression in a Digital Age</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gpos-on-user-profiles-in-windows-11-and-11/"><u>Mastering GPOs on User Profiles in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11-integrating-advanced-run-command/"><u>Maximizing Windows 11: Integrating Advanced Run Command</u></a></li>
<li><a href="https://fox-that.techidaily.com/missing-texts-on-iphone-heres-how-to-restore-sync-with-android-phones/"><u>Missing Texts on iPhone? Here's How to Restore Sync with Android Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-extender-writes-to-reduce-power-draw/"><u>Optimizing Extender' Writes to Reduce Power Draw</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x80041015-on-windows-a-step-by-step-guide/"><u>Overcoming Error 0X80041015 on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-errors-when-attempting-to-login-to-battlenet/"><u>Overcoming Errors When Attempting to Login to Battle.net</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-input-sluggishness-in-win-os-via-7-fixes/"><u>Overcoming Input Sluggishness in WIN OS via 7 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-text-display-error-w11s-msresource-challenge/"><u>Overcoming Text Display Error: W11's MsResource Challenge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-desktop-image-in-windows-easily/"><u>Personalizing Your Desktop Image in Windows Easily</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/protecting-your-work-youtube-copyright-essentials-explained/"><u>Protecting Your Work  YouTube Copyright Essentials Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-your-pcs-overwatch-2-lossed-graphic-error/"><u>Resolving Your PC’s Overwatch 2 Lossed Graphic Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-lost-luster-how-to-repeat-steam-accomplishments/"><u>Restore Lost Luster: How to Repeat Steam Accomplishments</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/secure-total-visual-display-for-2024/"><u>Secure Total Visual Display for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-navigation-window-11-power-user-guide/"><u>Simplify Navigation: Window 11 Power User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-system-crash-code-0xc0000001/"><u>Steps to Resolve System Crash: Code 0xC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-integrate-onedrive-and-microsoft-id/"><u>Streamline Your Workflow: Integrate OneDrive & Microsoft ID</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-win-10-and-11-networks-with-telnet-easily/"><u>Tailoring Win 10 & 11 Networks with Telnet Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-and-powershell-a-study-on-their-contrasting-traits/"><u>Terminal & PowerShell: A Study on Their Contrasting Traits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-windows-user-manual-for-speech-to-text-conversion/"><u>The Complete Window's User Manual for Speech-to-Text Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-consequences-of-muting-windows-11-notification-tones/"><u>The Consequences of Muting Windows 11 Notification Tones</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-editors-path-to-seamless-inshot-joins/"><u>The Editor's Path to Seamless Inshot Joins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-maximize-laptop-lifespan-power-management-basics/"><u>Tips: Maximize Laptop Lifespan - Power Management Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumphant-tech-revival-quick-windows-resets-in-3-steps/"><u>Triumphant Tech Revival: Quick Windows Resets in 3 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-deletion-keys-in-windows/"><u>Troubleshooting Non-Functional Deletion Keys in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-ssds-syncing-ssd-fresh-and-windows/"><u>Turbocharge SSDs: Syncing SSD Fresh & Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/unlocking-cinematic-potential-advanced-fcpx-techniques-for-2024/"><u>Unlocking Cinematic Potential Advanced FCPX Techniques for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlocking-the-secrets-of-lithuanian-language-at-home/"><u>Unlocking the Secrets of Lithuanian Language at Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-system-accessibility-context-menu-enhancement-in-win1011/"><u>Upgrade System Accessibility: Context Menu Enhancement in Win10/11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/voice-over-strategies-for-powerpoint-success-stories-for-2024/"><u>Voice-Over Strategies for PowerPoint Success Stories for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-rebirth-bright-screen-after-update-fallout/"><u>Win11 Rebirth: Bright Screen After Update Fallout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-active-windows-sound-services/"><u>Winning Back Active Windows Sound Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-lossed-rendering-support-in-overwatch-2/"><u>Winning Back Lossed Rendering Support in Overwatch 2</u></a></li>
</ul></div>
