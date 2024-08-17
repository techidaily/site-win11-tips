---
title: Overcoming File Access Barriers with PowerShell
date: 2024-08-16T02:32:00.477Z
updated: 2024-08-17T02:32:00.477Z
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

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-perfect-virtual-presentations-using-video-filters-on-zoom/"><u>[New] 2024 Approved  Perfect Virtual Presentations  Using Video Filters on Zoom</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-step-by-step-guide-to-using-youtubes-creative-commons-license-for-2024/"><u>[New] A Step-by-Step Guide to Using YouTube's Creative Commons License for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-beyond-basic-filters-elevating-your-snapchat-game/"><u>[New] Beyond Basic Filters  Elevating Your Snapchat Game</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-effortlessly-record-macos-content-and-display-for-2024/"><u>[New] Effortlessly Record macOS Content & Display for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-framefixer-analysis-all-inclusive-report/"><u>[New] FrameFixer Analysis – All-Inclusive Report</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-tactics-to-quiet-down-distractions-during-google-meets/"><u>[Updated] 2024 Approved  Tactics to Quiet Down Distractions During Google Meets</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-convert-and-share-simplified-mp3-to-youtube-process-3-phases/"><u>[Updated] In 2024, Convert & Share  Simplified MP3 to YouTube Process [3 Phases]</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-the-video-creators-guide-to-igtv-and-youtube-finding-the-right-fit/"><u>[Updated] In 2024, The Video Creator’s Guide to IGTV & YouTube  Finding the Right Fit</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-inside-the-cut-an-in-depth-look-at-d500-4k/"><u>[Updated] Inside the Cut  An In-Depth Look at D500 4K</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-ultimate-choice-for-live-tv-access-with-regional-networks-2024-edition/"><u>[Updated] Ultimate Choice for Live TV Access with Regional Networks, 2024 Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-step-by-step-strategies-to-thrive-on-reddit/"><u>2024 Approved  Step-by-Step Strategies to Thrive on Reddit</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-honor-x9b-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Honor X9b | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/breaking-down-backwards-compatibility-between-sony-consoles/"><u>Breaking Down Backwards Compatibility Between Sony Consoles</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/capturing-your-screen-apoyser-amongst-top-software-competitors/"><u>Capturing Your Screen  Apoyser Amongst Top Software Competitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-addressing-non-installed-hdd-in-windows-11/"><u>Comprehensive Guide to Addressing Non-Installed HDD in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-repairing-windows-error-0x80040610-in-outlook/"><u>Comprehensive Guide: Repairing Windows Error 0X80040610 in Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-windows-11-taskbar-end-task-ability/"><u>Configuring Windows 11 Taskbar: End Task Ability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-meaning-and-solution-of-winerror-0x80071a90/"><u>Decoding the Meaning & Solution of WinError 0X80071a90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-privilege-restrictions-for-windows-installer-success/"><u>Easing Privilege Restrictions for Windows Installer Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-to-enhance-windows-high-dpi-scaling/"><u>Effective Fixes to Enhance Windows High DPI Scaling</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/elite-screen-recording-software-unlimited-recordings/"><u>Elite Screen Recording Software, Unlimited Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-visibility-of-the-taskbar-with-maximized-window/"><u>Ensuring Visibility of the Taskbar With Maximized Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-underutilized-tools-for-system-monitoring/"><u>Exploring the Underutilized Tools for System Monitoring</u></a></li>
<li><a href="https://win11-tips.techidaily.com/full-uninstallation-blueprint-for-wsl-in-modern-windows/"><u>Full Uninstallation Blueprint for WSL in Modern Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-or-dfu-mode-on-apple-iphone-6s-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery or DFU Mode on Apple iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-the-mist-of-talos-extender/"><u>How to Mend the Mist of Talos Extender</u></a></li>
<li><a href="https://os-tips.techidaily.com/how-to-retrieve-data-from-an-iphone-backup-in-itunes-or-icloud-on-your-mac/"><u>How to Retrieve Data From an iPhone Backup in iTunes or iCloud on Your Mac</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-xiaomi-redmi-note-12t-pro-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Xiaomi Redmi Note 12T Pro to Apple TV | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-test-a-microphone-on-windows-pc/"><u>How to Test a Microphone on Windows PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-track-imei-number-of-oneplus-12-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of OnePlus 12 Through Google Earth?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-15-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 15 to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/identify-these-six-inexpensive-ai-services-akin-to-sora/"><u>Identify These Six Inexpensive AI Services Akin to Sora</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Honor X9b? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-galactic-game-guide-the-top-10-affordable-mmo-titles/"><u>In 2024, Galactic Game Guide  The Top 10 Affordable MMO Titles</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-inside-look-at-vimeo-and-youtubes-market-strategies/"><u>In 2024, Inside Look at Vimeo and YouTube’s Market Strategies</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-select-15-professional-luts-to-boost-gopro-cinematography/"><u>In 2024, Select 15 Professional LUTs to Boost GoPro Cinematography</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-top-offline-iphone-and-ipad-games-fun-without-wi-fi/"><u>In 2024, Top Offline iPhone & iPad Games – Fun Without Wi-Fi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-win-11-games-in-no-time-the-ultimate-guide-to-boosting-your-playstyle/"><u>Master Win 11 Games in No Time: The Ultimate Guide to Boosting Your Playstyle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-windows-artistry-with-these-7-distinguished-drawing-tools/"><u>Masterful Windows Artistry with These 7 Distinguished Drawing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-disconnected-network-via-windows-settings/"><u>Reconnecting Disconnected Network via Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-situation-when-another-software-overrides-speakers/"><u>Remedying the Situation When Another Software Overrides Speakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-unconnect-error-for-windows-nvidia-applications/"><u>Removing Unconnect Error for Windows' Nvidia Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-your-digital-footprint-windows-login-guide/"><u>Removing Your Digital Footprint: Windows Login Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-link-failures-spotify-in-windows-11-environments/"><u>Resolving Link Failures: Spotify in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-0x80072746-email-failure-on-windows-pc/"><u>Resolving the 0X80072746 Email Failure on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/script-for-setting-up-ms-word-opening-email-attachments-without-edit-options/"><u>Script for Setting Up MS Word: Opening Email Attachments Without Edit Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-amd-graphics-drivers-update-for-windows-11-pcs/"><u>Step-by-Step AMD Graphics Drivers Update for Windows 11 PCs</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-solutions-stabilizing-slime-rancher-gameplay-on-pc-systems/"><u>Step-by-Step Solutions: Stabilizing Slime Rancher Gameplay on PC Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-resetting-video-driver-errors/"><u>Steps to Fix Resetting Video Driver Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-storage-with-ntfs-compression-in-win11/"><u>Streamline Storage with NTFS Compression in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedy-dealing-with-roblox-error-code-262/"><u>Swift Remedy: Dealing with Roblox Error Code 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-insufficient-rights-error-during-windows-installation/"><u>Tackling Insufficient Rights Error During Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-drive-camouflage-in-w11w10/"><u>The Art of Drive Camouflage in W11/W10</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-gptbot-saga-ai-evolution-and-its-contentious-internet-stance/"><u>The GPTBot Saga - AI Evolution & Its Contentious Internet Stance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-upgrade-error-xc004f050/"><u>Troubleshooting Windows Upgrade Error Xc004f050</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-guide-to-convert-srt-to-txt-in-minutes-for-2024/"><u>Ultimate Guide to Convert SRT to TXT in Minutes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-windows-error-0xc0000001-quickly/"><u>Understanding & Fixing Windows Error 0xC0000001 Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-potential-pinning-to-windows-11-bar/"><u>Unleash Potential: Pinning to Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-best-windows-photo-organizers-listed-here/"><u>Unveiling the Best Windows Photo Organizers Listed Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-ancient-pcs-for-modern-operations-using-windows-to-go-and-rufus/"><u>Upgrading Ancient PCs for Modern Operations: Using Windows To Go and Rufus</u></a></li>
</ul></div>
