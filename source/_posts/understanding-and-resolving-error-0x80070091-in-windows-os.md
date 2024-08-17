---
title: Understanding and Resolving Error 0X80070091 in Windows OS
date: 2024-08-16T02:41:40.359Z
updated: 2024-08-17T02:41:40.359Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding and Resolving Error 0X80070091 in Windows OS
excerpt: This Article Describes Understanding and Resolving Error 0X80070091 in Windows OS
keywords: Fixing Error XO70070091,Stop Windows 0XError,Resolve OS Failure X070070091,Troubleshoot Win0X070070091,Overcome XP0X070070091 Error,Eliminate Windows 0XO70070091,Cure XO70070091 in OS Errors
thumbnail: https://thmb.techidaily.com/73182ed54b3d34ca981abeae24ed800ccc098d1b157cf1a2528e89d05cbc2979.jpg
---

## Understanding and Resolving Error 0X80070091 in Windows OS

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-from-sketchpad-to-screen-a-guide-to-starting-live-on-tiktok-from-desktop/"><u>[New] 2024 Approved  From Sketchpad to Screen – A Guide to Starting LIVE on TikTok From Desktop</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-8-best-webspots-free-eco-backdrops-and-footage-collection-for-2024/"><u>[New] 8 Best Webspots  FREE Eco-Backdrops and Footage Collection for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-top-tier-video-transcription-aid-automated/"><u>[New] In 2024, Top-Tier Video Transcription Aid, Automated!</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-exploration-of-final-cut-pros-powerful-tools-and-features/"><u>[New] In-Depth Exploration of Final Cut Pro’s Powerful Tools and Features</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-pro-chromebook-zoom-usage-techniques/"><u>[New] Pro Chromebook Zoom Usage Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-visualcut-pro/"><u>[New] VisualCut Pro</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-cutting-edge-techniques-making-mac-videos-for-snapchat/"><u>[Updated] 2024 Approved  Cutting-Edge Techniques  Making Mac Videos for Snapchat</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-cutting-edge-camera-technology-for-youtube-stars-for-2024/"><u>[Updated] Cutting-Edge Camera Technology For YouTube Stars for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-join-the-trendsetters-club-with-monthly-1k-followers/"><u>[Updated] In 2024, Join the Trendsetters Club with Monthly 1K Followers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-navigating-iphone-camera-for-nighttime-pics/"><u>[Updated] Navigating iPhone Camera for Nighttime Pics</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-seamless-cinema-experience-free-and-paid-iphones-app-list/"><u>[Updated] Seamless Cinema Experience  Free & Paid iPhones App List</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-snicker-scribbles-humorhub/"><u>[Updated] Snicker Scribbles  HumorHub</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-create-an-nft-easily-an-ultimate-guide-for-beginners/"><u>2024 Approved  How to Create an NFT Easily  An Ultimate Guide for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-apps-to-increase-the-volume-beyond-100-percent-in-windows/"><u>4 Apps to Increase the Volume Beyond 100 Percent in Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/a-comprehensive-list-of-mac-methods-to-record-minecraft-play-for-2024/"><u>A Comprehensive List of Mac Methods to Record Minecraft Play for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-win-hardware-testing-with-these-premier-graphics-tools/"><u>Ace Win Hardware Testing with These Premier Graphics Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-file-locks-turn-off-read-only-windows-mode/"><u>Altering File Locks: Turn Off Read-Only Windows Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-digital-snare-spotting-invisible-threats/"><u>Avoid the Digital Snare: Spotting Invisible Threats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-saved-audio-configurations-winvolume-hacks/"><u>Bring Back Saved Audio Configurations: WinVolume Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-compatibility-with-windows-11-explained/"><u>Chrome Compatibility with Windows 11 Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-os-synergy-creating-a-linux-vm-inside-windows-using-hyper-v/"><u>Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-wont-start-spotify-on-windows-1011-platforms/"><u>Curing Won't Start Spotify on Windows 10/11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-code-effective-techniques-to-neutralize-wacatacbml/"><u>Deciphering the Code: Effective Techniques to Neutralize Wacatac.B!ml</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-new-tech-in-microsoft-teams/"><u>Enhancing Performance: New Tech in Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-0x800f0845-from-windows-updates/"><u>Eradicating 0X800f0845 From Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-winning-with-the-windows-11-bar/"><u>Essential Strategies for Winning with the Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-commands-learn-the-top-20-cmd-tricks/"><u>Essential Windows Commands: Learn the Top 20 CMD Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-and-engage-with-10-key-network-settings-in-winos/"><u>Explore and Engage with 10 Key Network Settings in WinOS</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ring-mobile-youtube-usage-on-different-oses/"><u>Exploring Mobile YouTube Usage on Different OSes</u></a></li>
<li><a href="https://change-location.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/gaming-on-a-budget-top-10-free-game-download-sites-for-pc-and-android-for-2024/"><u>Gaming on a Budget Top 10 Free Game Download Sites for PC and Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-installing-programs-despite-windows-admin-blocks/"><u>Guidelines for Installing Programs Despite Windows Admin Blocks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-install-microsoft-defender-application-guard-for-edge-in-windows-11/"><u>How to Install Microsoft Defender Application Guard for Edge in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-secure-your-windows-mixer-preferences-settings/"><u>How To Secure Your Windows Mixer Preferences Settings</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-track-imei-number-of-realme-narzo-60-pro-5g-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Realme Narzo 60 Pro 5G Through Google Earth?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-asus-rog-phone-7-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Asus ROG Phone 7 without App | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-from-iphone-12-mini-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock From iPhone 12 mini - 4 Easy Ways</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-huawei-nova-y71-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Huawei Nova Y71</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-from-good-to-great-elevate-reactions-in-youtube-videos-with-these-3-strategies/"><u>In 2024, From Good to Great  Elevate Reactions in YouTube Videos with These 3 Strategies</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-s17-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo S17 Pro to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-ultimate-guide-of-hdr-photo-on-iphone-camera/"><u>In 2024, The Ultimate Guide of HDR Photo on iPhone Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-privacy-activating-controlled-folder-access-in-windows-11/"><u>Mastering Privacy: Activating Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-troubleshoot-avidemux-audio-problems-step-by-step-guide-2023-for-2024/"><u>New Troubleshoot Avidemux Audio Problems Step-by-Step Guide 2023 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepad-woes-on-pc-7-steps-to-reopen-the-favorite-text-editor/"><u>Notepad Woes on PC: 7 Steps to Reopen the Favorite Text Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-vlc-unrecognized-media-issue/"><u>Overcoming Windows VLC Unrecognized Media Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-lost-connectivity-winos-strategies/"><u>Rebooting Lost Connectivity: WinOS Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-and-render-vintage-videos-with-windows-madvr/"><u>Revamp and Render Vintage Videos with Windows MadVR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-the-malfunction-of-windows-delete-operation/"><u>Reversing the Malfunction of Windows Delete Operation</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/revolutionary-amazon-echo-show-10-gen-3-review-the-smart-assistant-that-follows-you-everywhere/"><u>Revolutionary Amazon Echo Show 10 (Gen 3) Review: The Smart Assistant That Follows You Everywhere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-rockalldlldll-absence-in-windows-systems/"><u>Solving 'Rockalldll.dll' Absence in Windows Systems</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-vivo-y56-5g-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Vivo Y56 5G FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/terrarium-tales-the-top-five-gold-quests/"><u>Terrarium Tales  The Top Five Gold Quests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-vivo-y36-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Vivo Y36 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-printer-functionality-within-edge-guard/"><u>Triggering Printer Functionality Within Edge Guard</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ultimate-guide-to-ring-video-doorbell-2-a-comprehensive-review/"><u>Ultimate Guide to Ring Video Doorbell 2: A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-runtime-brokers-in-computing/"><u>Unraveling the Mystery of Runtime Brokers in Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-playnite-integrating-virtual-game-archives/"><u>Winning Playnite: Integrating Virtual Game Archives</u></a></li>
</ul></div>
