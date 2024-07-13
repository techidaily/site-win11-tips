---
title: Overcoming File Access Barriers with PowerShell
date: 2024-07-12T16:34:50.276Z
updated: 2024-07-13T16:34:50.276Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming File Access Barriers with PowerShell
excerpt: This Article Describes Overcoming File Access Barriers with PowerShell
keywords: PowerShell Access Controls,File Permissions Scripting,Secure PowerShell Execution,Elevate Script Authority,Bypass Security Restrictions,Automate File Rights Management,Enhance PowerShell Security
thumbnail: https://thmb.techidaily.com/6095600b720da220ffffead1a4fc142237909794e0b00b8441f133e8ae3bdb81.jpg
---

## Overcoming File Access Barriers with PowerShell

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on [how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily


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
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-xbox-game-pass-error-0x000-on-windows-11-systems/"><u>Understanding and Correcting Xbox Game Pass Error 0X000_ on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-workflow-programmatic-shortcuts-in-winos/"><u>Streamline Workflow: Programmatic Shortcuts in WinOS</u></a></li>
<li><a href="https://article-posts.techidaily.com/listenleap-escaping-dacasts-grip-for-2024/"><u>ListenLeap  Escaping DaCast's Grip for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-mastering-mac-snipers-top-5-recommended-tools/"><u>[New] In 2024, Mastering Mac Snipers  Top 5 Recommended Tools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlocking-youtubes-potential-for-visual-storytelling/"><u>2024 Approved  Unlocking YouTube's Potential for Visual Storytelling</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unlocking-free-discovideo-on-pc-android-ios-without-payments-for-2024/"><u>[New] Unlocking Free DiscoVideo on PC, Android, iOS Without Payments for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-snapedit-101-simple-steps-to-stunning-photos/"><u>In 2024, Snapedit 101  Simple Steps to Stunning Photos</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-clear-screen-techniques-focus-on-your-message-not-the-ambiance/"><u>[New] Clear Screen Techniques  Focus on Your Message, Not the Ambiance</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-harness-the-power-of-online-cropping-to-elevate-your-photos/"><u>2024 Approved  Harness the Power of Online Cropping to Elevate Your Photos</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-a15-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy A15 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/mac-users-download-vllo-and-find-alternative-solutions/"><u>Mac Users Download VLLO and Find Alternative Solutions</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-xiaomi-14-ultra-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Xiaomi 14 Ultra Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-s-top-rated-video-editing-software-for-high-definition-videos/"><u>New In 2024, S Top-Rated Video Editing Software for High-Definition Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-idea-to-installment-making-custom-instagram-notifications-for-2024/"><u>From Idea to Installment  Making Custom Instagram Notifications for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-to-windows-birthplace-points/"><u>Trailblazing to Windows' Birthplace Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-cyber-voyage-checking-stable-connections-on-pc/"><u>Securing Your Cyber Voyage: Checking Stable Connections on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-most-reliable-brightness-tools-for-windows-multi-display-users/"><u>The 6 Most Reliable Brightness Tools For Windows Multi-Display Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-backup-routine-for-nvidia-panel-configurations/"><u>Re-Establishing Backup Routine for Nvidia Panel Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-intelligent-assistant-protocol-on-windows/"><u>Stopping Intelligent Assistant Protocol on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-permission-errors-a-step-by-step-guide-on-windows/"><u>Resolving Permission Errors: A Step-by-Step Guide on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-setup-a-closer-look/"><u>Windows 11 Setup: A Closer Look</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-vivo-x100-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Vivo X100 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-errors-in-win1011-0x8007045d/"><u>Solving Common Errors in Win10/11 - 0X8007045D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-audio-tracking-on-windows-powered-screencasts/"><u>Strategies for Audio Tracking on Windows-Powered Screencasts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-how-to-change-youtube-video-playback-speed-desktopmobile-for-2024/"><u>[Updated] How to Change YouTube Video Playback Speed [Desktop/Mobile] for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-13-pro-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 13 Pro Max without iTunes? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lowering-cpu-intensity-in-gaming-windows/"><u>Solutions for Lowering CPU Intensity in Gaming Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-synapse-functionality-with-razer-devices-on-windows/"><u>Restoring Synapse Functionality with Razer Devices on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-battery-alert-strategies-for-win-users/"><u>Proactive Battery Alert Strategies for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-office-error-0x80041015-in-ms-word-and-excel/"><u>Overcoming Office Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-realme-c33-2023-frp-bypass-by-drfone-android/"><u>About Realme C33 2023 FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-turn-up-the-volume-enabling-sound-on-tweeted-videos/"><u>[Updated] In 2024, Turn Up the Volume  Enabling Sound on Tweeted Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-top-5-grievances-from-windows-11-users/"><u>Unveiling the Top 5 Grievances From Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tech-companion-asus-vivobook-s-15-review/"><u>The Ultimate Tech Companion: Asus Vivobook S 15 Review</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-make-quick-work-of-long-videos-speed-up-playback-in-quicktime/"><u>2024 Approved Make Quick Work of Long Videos Speed Up Playback in QuickTime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-11s-default-touch-panel-settings-and-positioning/"><u>Restoring Windows 11'S Default Touch Panel Settings & Positioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-path-upgrading-your-vm-software-from-virtualbox-v6-to-v7-in-win11/"><u>Step-by-Step Path: Upgrading Your VM Software From VirtualBox v6 to v7 in Win11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-comprehensive-guide-to-locating-and-creating-superb-instagram-alarms/"><u>2024 Approved  A Comprehensive Guide to Locating and Creating Superb Instagram Alarms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-combination-of-files-in-windows-1011/"><u>Seamless Combination of Files in Windows 10/11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-15-top-video-to-gif-app-on-iphone-and-android/"><u>Updated 2024 Approved 15 Top Video to GIF App on iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-your-schedule-how-to-reset-windows-time-service/"><u>Sync Your Schedule: How to Reset Windows Time Service</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ver-the-top-10-historically-rich-youtube-tutorials/"><u>Discover the Top 10 Historically Rich YouTube Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-changing-app-size-using-pc-keys-on-windows-11/"><u>Tips for Changing App Size Using PC Keys on Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-obs-vs-shadowplay-the-ultimate-showdown-for-gamers-for-2024/"><u>[Updated] OBS vs ShadowPlay  The Ultimate Showdown for Gamers for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-poco-c50-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Poco C50 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-beginners-blueprint-to-creating-an-audio-book-with-ease-a-compreranly-updated-manual/"><u>New The Beginners Blueprint to Creating an Audio Book with Ease A Compreranly Updated Manual</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-knowing-all-ways-to-slow-down-video-with-adobe-premiere-pro/"><u>New 2024 Approved Knowing All Ways To Slow Down Video With Adobe Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhindered-wi-fi-on-your-desktop-9-strategies-for-win11-users/"><u>Unhindered Wi-Fi on Your Desktop: 9 Strategies for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-tips-stacking-windows-sticky-notes-high/"><u>Pro Tips: Stacking Windows Sticky Notes High</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unanticipated-error-messages-in-wins-secure/"><u>Tackling Unanticipated Error Messages in WINS Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-discord-installer-errors-on-windows-devices/"><u>Resolving Discord Installer Errors on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotting-large-files-and-drives-in-windows-storage-soup/"><u>Spotting Large Files & Drives in Windows Storage Soup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-restoration-techniques-to-reactivate-virus-protection-in-windows/"><u>Quick Restoration Techniques to Reactivate Virus Protection in Windows</u></a></li>
</ul></div>
