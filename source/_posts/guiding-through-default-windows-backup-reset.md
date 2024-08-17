---
title: Guiding Through Default Windows Backup Reset
date: 2024-08-16T01:52:45.981Z
updated: 2024-08-17T01:52:45.981Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guiding Through Default Windows Backup Reset
excerpt: This Article Describes Guiding Through Default Windows Backup Reset
keywords: Windows Backup Tutorial,Reset Guide Windows,Default Backup Steps,Windows Data Protection,Windows Recovery Procedures,System Backup Solutions,Reset Windows Safely
thumbnail: https://thmb.techidaily.com/4e54d2ee69e2d3cc5b62664f281e174d4bc506ec5c304888c5062a8c04d6107f.jpg
---

## Guiding Through Default Windows Backup Reset

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/new-behind-the-scenes-making-melodic-tiktoks/"><u>[New] Behind the Scenes  Making Melodic TikToks</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-leading-psp-ios-game-simulators-our-2023s-choices/"><u>[New] In 2024, Leading PSP iOS Game Simulators - Our 2023'S Choices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-tinytake-screen-recorder-review/"><u>[New] TinyTake Screen Recorder Review</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-gamers-almanac-expert-tips-to-record-and-save-your-minecraft-sessions/"><u>[Updated] 2024 Approved  Gamer's Almanac  Expert Tips to Record and Save Your Minecraft Sessions</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-aural-alchemy-transforming-imovie-videos-with-music/"><u>[Updated] Aural Alchemy  Transforming iMovie Videos with Music</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-comprehensive-examination-gopro-hero4-silver-version/"><u>[Updated] Comprehensive Examination  GoPro HERO4 Silver Version</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-branding-with-visuals-inserting-watermarks-into-youtube-vids/"><u>[Updated] In 2024, Branding with Visuals  Inserting Watermarks Into YouTube Vids</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-free-to-fortune-carryminatis-youtube-transformation-ajey/"><u>[Updated] In 2024, From Free to Fortune  CarryMinati’s YouTube Transformation (Ajey)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-google-meet-unlocked-a-free-in-depth-user-manual/"><u>[Updated] In 2024, Google Meet Unlocked  A Free, In-Depth User Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-snipping-tool-with-a-simple-key-combo-on-win-11/"><u>Activating Snipping Tool with a Simple Key Combo on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-cmd-guru-understand-these-20-crucial-commands/"><u>Become a CMD Guru: Understand These 20 Crucial Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-improving-windows-11s-trouble-resolution-tools/"><u>Bridging Gaps: Improving Windows 11'S Trouble Resolution Tools</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-common-steam-connectivity-issues/"><u>Bypassing Common Steam Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cybersecurity-insight-key-windows-activities-that-could-conceal-threats/"><u>Cybersecurity Insight: Key Windows Activities That Could Conceal Threats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-error-0x80131500-on-microsoft-store/"><u>Disabling Error 0X80131500 on Microsoft Store</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/discovering-the-marvels-of-the-samsung-un65ru8000fxza-a-review-focused-on-style-and-advanced-features/"><u>Discovering the Marvels of the Samsung UN65RU8000FXZA - A Review Focused on Style and Advanced Features</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-installation-how-to-download-and-set-up-hp-universal-printer-software-for-windows/"><u>Easy Installation: How to Download and Set Up HP Universal Printer Software for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-window-management-active-periods-not-permanent-disruptions/"><u>Efficient Window Management: Active Periods, Not Permanent Disruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-management-navigating-taskbar-with-windows-hotkeys/"><u>Effortless Management: Navigating Taskbar with Windows Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-pc-performance-insider-tips-on-wintools/"><u>Elevate PC Performance: Insider Tips on WinTools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-windows-storage-the-top-free-volume-boosters-list/"><u>Enhance Your Windows Storage: The Top Free Volume Boosters List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-flawed-windows-safety-features-in-win-11/"><u>Fixing Flawed Windows Safety Features in Win 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/future-of-computing-best-5-ai-hardware-advances/"><u>Future of Computing: Best 5 AI Hardware Advances</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-the-windows-11-taskbar-teams-chat-removal-will-impact-you/"><u>How the Windows 11 Taskbar Teams Chat Removal Will Impact You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-iphone-image-import-something-went-wrong-error-in-windows-10-and-11/"><u>How to Fix the iPhone Image Import “Something Went Wrong” Error in Windows 10 & 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-realme-note-50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-personalize-your-macs-finder-display-settings-for-efficient-organization/"><u>How to Personalize Your Mac's Finder Display Settings for Efficient Organization</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-vivo-s18e-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-enhancing-youtube-video-screens-without-barriers/"><u>In 2024, Enhancing YouTube Video Screens  Without Barriers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-samsung-galaxy-f54-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Samsung Galaxy F54 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-themes-for-enhanced-terminal-views/"><u>Innovative Themes for Enhanced Terminal Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-fixing-media-creators-error-0x8007043c/"><u>Methods for Fixing Media Creator's Error 0X8007043C</u></a></li>
<li><a href="https://fox-that.techidaily.com/quick-solutions-how-to-repair-imessage-issues-on-your-ios-devices/"><u>Quick Solutions: How to Repair iMessage Issues on Your iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-grammarly-a-dead-service-on-your-desktop/"><u>Reactivating Grammarly, a Dead Service on Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-windows-hosts-overuse-a-guide/"><u>Reducing Windows Host's Overuse: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-re-entry-to-your-shared-windows-spot/"><u>Seamless Re-Entry to Your Shared Windows Spot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-pc-manager-on-windows-11-a-quick-guide/"><u>Setting Up PC Manager on Windows 11 – A Quick Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-lava-yuva-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-performance-essential-strategies-with-windows-11/"><u>Skyrocket Your Performance: Essential Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-seamless-windows-notepad-functioning/"><u>Steps to Ensure Seamless Windows Notepad Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-non-operational-windows-apps/"><u>Steps to Recover Non-Operational Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-rectify-bluetooth-check-pin-error-in-windows-oses/"><u>Strategies to Rectify Bluetooth Check Pin Error in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-evolutionary-leap-with-ai-copilot-in-windows-11-life/"><u>The Evolutionary Leap with AI Copilot in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-cost-free-windows-audio-cleaners/"><u>Top 5 Cost-Free Windows Audio Cleaners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-enabledisable-bing-ai-on-windows-11-search-bar/"><u>Turbo Enable/Disable: Bing AI on Windows 11 Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-26/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/vocal-vanishing-act-how-to-seamlessly-remove-singers-voice-from-an-audio-track-using-audacity-tools/"><u>Vocal Vanishing Act How to Seamlessly Remove Singers Voice From an Audio Track Using Audacity Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
</ul></div>
