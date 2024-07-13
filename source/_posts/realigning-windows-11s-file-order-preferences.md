---
title: Realigning Windows 11'S File Order Preferences
date: 2024-07-12T17:25:52.857Z
updated: 2024-07-13T17:25:52.857Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Realigning Windows 11'S File Order Preferences
excerpt: This Article Describes Realigning Windows 11'S File Order Preferences
keywords: Win11 File Organize,Realign W11 Files,Windows 11 Setup,Change W11 Folder,Rearrange W11 Order,New W11 Sorting,W11 File Arrangement
thumbnail: https://thmb.techidaily.com/d2d94c4e77b77ed0c83b7c2ce10b6132329d863043aff159270d3e923d41f323.jpg
---

## Realigning Windows 11'S File Order Preferences

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

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on [how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will [open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.
6. Similarly, delete the**Bags** folder and close the Registry window.

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
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-emulated-titles-in-playnite/"><u>Seamless Integration of Emulated Titles in Playnite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-voice-commands-keyboard-shortcut-essentials/"><u>Mastering Windows 11'S Voice Commands: Keyboard Shortcut Essentials</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-streamlining-discovery-the-key-to-effective-video-titling/"><u>[Updated] Streamlining Discovery  The Key to Effective Video Titling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-lag-and-enhance-fps-in-roblox-win-edition/"><u>Minimize Lag & Enhance FPS in Roblox Win Edition</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-on-apple-iphone-7-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons On Apple iPhone 7? Find the Best Solution Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-in-microsoft-essential-gratis-tools-for-win11/"><u>Masterclass in Microsoft: Essential Gratis Tools for Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-samsung-galaxy-m14-5g-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Samsung Galaxy M14 5G?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-microsoft-store-functionality-in-windows-11/"><u>Restoring Microsoft Store Functionality in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-video-brand-enhancement-embedding-logoswatermarks-for-youtube-shows/"><u>2024 Approved  Video Brand Enhancement  Embedding Logos/Watermarks for YouTube Shows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-8-popular-streaming-audio-recorder-that-you-cant-miss/"><u>Updated 8 Popular Streaming Audio Recorder That You Cant Miss</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-monetization-showdown-dailymotion-vs-youtubes-financial-gains/"><u>Video Monetization Showdown  Dailymotion vs Youtube's Financial Gains</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-youtube-vs-vimeo-exploring-user-experience-variance/"><u>[New] YouTube vs Vimeo  Exploring User Experience Variance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-screen-quiet-disable-win11-folders/"><u>Mastering Screen Quiet: Disable Win11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-troubled-waters-in-windows-mail-app-with-0x800713f/"><u>Navigating Through Troubled Waters in Windows Mail App with 0X800713F</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-ultimate-showdown-vlc-versus-mpc-in-video-viewing/"><u>[New] 2024 Approved  The Ultimate Showdown  VLC Versus MPC in Video Viewing</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-f54-5g-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy F54 5G Phone without PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-dns-configuration-process-on-windows-11/"><u>Navigating the DNS Configuration Process on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purple-pandemonium-restore-your-pcs-color-calibration/"><u>Purple Pandemonium? Restore Your PC's Color Calibration</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-satirical-video-gems-the-ultimate-list-of-humor-channels/"><u>[New] Satirical Video Gems  The Ultimate List of Humor Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-emulators-selecting-best-windows-imitations-for-switch-games/"><u>Leading Emulators: Selecting Best Windows Imitations for Switch Games</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-xiaomi-redmi-k70-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Xiaomi Redmi K70 Unlock Without Password</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-conductors-toolkit-unpackaging-the-finest-digital-audio-workstations-for-2024/"><u>The Conductors Toolkit Unpackaging the Finest Digital Audio Workstations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-action-steps-for-correcting-workspace-glitches-on-winos/"><u>Instant Action Steps for Correcting Workspace Glitches on WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-win-lsa-troubleshooting/"><u>Mastering the Art of Win LSA Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protect-your-pc-identifying-the-7-most-suspicious-windows-processes/"><u>Protect Your PC: Identifying the 7 Most Suspicious Windows Processes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-tecno-camon-20-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Tecno Camon 20 Phone? Unlock It Now</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-business-of-blogging-and-earning-on-youtube-platform/"><u>[Updated] The Business of Blogging and Earning on YouTube Platform</u></a></li>
<li><a href="https://network-issues.techidaily.com/bluescreen-of-death-in-windows-solved-by-dxgkrnlsys-fix/"><u>BlueScreen of Death in Windows Solved by dxgkrnl.sys Fix</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-masterful-moment-preservation-a-gif-collectors-dream-toolkit-for-2024/"><u>[Updated] Masterful Moment Preservation - A Gif Collector's Dream Toolkit for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-a-dive-into-aerialbroadcasting-tech-dji-vs-gopro-vs-insta360-showdown/"><u>In 2024, A Dive Into Aerial/Broadcasting Tech  DJi vs GoPro vs Insta360 Showdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-utorrent-performance-in-win-os/"><u>Optimizing uTorrent Performance in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slick-techniques-for-masking-windows-11-task-view/"><u>Slick Techniques for Masking Windows 11 Task View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-net-speeds-unlock-efficient-adapter-checking/"><u>Navigate Net Speeds: Unlock Efficient Adapter Checking</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-nokia-c210-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/gamers-playbook-the-best-capture-tools-for-pcmac-gamers-for-2024/"><u>Gamer's Playbook  The Best Capture Tools for PC/Mac Gamers for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-step-into-professional-photoshop-mastering-luts-in-cs6cc/"><u>2024 Approved  Step Into Professional Photoshop  Mastering LUTs in CS6/CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unpair-and-reconnect-devices-effortlessly-on-win-11/"><u>How to Unpair and Reconnect Devices Effortlessly on Win 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-apple-iphone-7-plus-location-on-viber-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change/Fake Your Apple iPhone 7 Plus Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-your-windows-overcome-geforce-experience-failures/"><u>Mend Your Windows: Overcome GeForce Experience Failures</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-streamline-your-viewing-the-facebook-auto-play-guide/"><u>[Updated] 2024 Approved  Streamline Your Viewing  The Facebook Auto-Play Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-and-cpu-efficiency-in-browsers-a-windowsmacoschromeos-comparison/"><u>Memory and CPU Efficiency in Browsers: A Windows/macOS/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-connection-between-windows-11-and-print-devices/"><u>Restoring Connection Between Windows 11 and Print Devices</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-guide-to-montage-apps-8-leading-options-iphoneandroid-for-2024/"><u>The Ultimate Guide to Montage Apps  8 Leading Options (iPhone/Android) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-1110-setup-with-rightful-permissions/"><u>Navigating Windows 11/10 Setup with Rightful Permissions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-top-10-mac-screenshotters-and-recorders-reviewed/"><u>[New] Top 10 Mac Screenshotters and Recorders Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-protection-activating-tpm-and-secure-boot-before-w11-update/"><u>Prioritize Protection: Activating TPM and Secure Boot Before W11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-11-admin-details-effectively/"><u>Revamp Your Windows 11 Admin Details Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-functional-headphonesspeakers-in-windows/"><u>Resolving Non-Functional Headphones/Speakers in WINDOWS</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-transform-low-res-videos-into-high-definition-masterpieces/"><u>2024 Approved Transform Low-Res Videos Into High-Definition Masterpieces</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-harnessing-customer-stories-for-brand-growth-for-2024/"><u>[Updated] Harnessing Customer Stories for Brand Growth for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapidly-reach-word-definitions-on-your-system/"><u>Rapidly Reach Word Definitions on Your System</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Honor X50i+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-broken-system-defragmenter-execution/"><u>Rectifying Broken System Defragmenter Execution</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-terror-in-towns-selecting-the-best-8-zombie-gaming-titles-for-2024/"><u>[New] Terror in Towns  Selecting the Best 8 Zombie Gaming Titles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-disabled-windows-update-service/"><u>Immediate Actions for Disabled Windows Update Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-how-to-setup-touch-typing-feature-on-your-windows-device/"><u>Learn How To Setup Touch Typing Feature on Your Windows Device</u></a></li>
</ul></div>
