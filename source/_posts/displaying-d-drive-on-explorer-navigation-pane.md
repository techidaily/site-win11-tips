---
title: "Displaying D: Drive on Explorer Navigation Pane"
date: 2024-08-28T01:11:57.709Z
updated: 2024-08-29T01:11:57.709Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Displaying D: Drive on Explorer Navigation Pane"
excerpt: "This Article Describes Displaying D: Drive on Explorer Navigation Pane"
keywords: Drive Display,Explorer Panes,Explore Navigation,Drive Views,File Browser,Navigational Panes,Storage Shows
thumbnail: https://thmb.techidaily.com/7f8f4d19272d4759318cbc88d919ca0c7c48f620077177c71b194a7d51d8ecab.jpg
---

## Displaying D: Drive on Explorer Navigation Pane

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-plex-vs-studio-prodigies/"><u>[New] 2024 Approved  Plex vs Studio Prodigies</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-how-to-skyrocket-likes-on-your-tiktok-unpack-sessions/"><u>[New] How to Skyrocket Likes on Your TikTok Unpack Sessions</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-the-obs-strategy-for-high-quality-skype-screens/"><u>[New] In 2024, The OBS Strategy for High-Quality Skype Screens</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-recorder-at-zero-free-capture-of-your-android-content-for-2024/"><u>[New] Recorder at Zero  Free Capture of Your Android Content for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-uncomplicated-video-snip-for-win10-users/"><u>[New] Uncomplicated Video Snip for Win10 Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-advanced-windows-11-video-recording-software-guide/"><u>[Updated] 2024 Approved  Advanced Windows 11 Video Recording Software Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-download-youtube-music-to-your-android-phone-top-6-free-apps/"><u>[Updated] 2024 Approved  Download YouTube Music to Your Android Phone  Top 6 Free Apps</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-mastery-in-making-the-perfect-match-of-drones-and-propellers/"><u>[Updated] 2024 Approved  Mastery in Making the Perfect Match of Drones and Propellers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-detecting-bots-amongst-your-brands-facebook-supporters/"><u>[Updated] In 2024, Detecting Bots Amongst Your Brand's Facebook Supporters</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-digital-workshop-archives/"><u>[Updated] In 2024, Digital Workshop Archives</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-precision-techniques-to-record-your-facetime-chats/"><u>[Updated] In 2024, Precision Techniques to Record Your FaceTime Chats</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-integrate-xp-moviemaker-from-digital-software-suite/"><u>[Updated] Integrate XP Moviemaker From Digital Software Suite</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-seamless-computer-based-tiktok-live-broadcast-setup/"><u>[Updated] Seamless Computer-Based TikTok LIVE Broadcast Setup</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-tailored-approaches-to-pc-screen-recordings-using-dell-for-2024/"><u>[Updated] Tailored Approaches to PC Screen Recordings Using Dell for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-design-your-closure-the-best-free-youtube-tutorials/"><u>2024 Approved  Design Your Closure  The Best Free YouTube Tutorials</u></a></li>
<li><a href="https://win-amazing.techidaily.com/boost-your-screen-quality-with-the-latest-display-driver-installations/"><u>Boost Your Screen Quality with the Latest Display Driver Installations</u></a></li>
<li><a href="https://win-answers.techidaily.com/call-of-duty-black-ops-4-not-launching-discover-how-to-fix-it-now/"><u>Call of Duty Black Ops 4 Not Launching? Discover How to Fix It Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-obstacles-for-win11s-optimal-ccleaner-use/"><u>Clearing Obstacles for Win11's Optimal CCleaner Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-a-python-server-on-windows-transfer-made-simple/"><u>Configuring a Python Server on Windows: Transfer Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-complete-spatial-soundscape-in-windows-11/"><u>Crafting a Complete Spatial Soundscape in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-windows-identity-user-name-transformation/"><u>Customizing Your Windows Identity: User Name Transformation</u></a></li>
<li><a href="https://facebook.techidaily.com/decoding-the-language-of-likes-reactions-and-more-in-fb/"><u>Decoding the Language of Likes, Reactions & More in FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-qr-scanning-in-the-windows-arena/"><u>Demystifying QR Scanning in the Windows Arena</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-and-fixing-vac-failed-on-your-pc/"><u>Dissecting and Fixing VAC Failed on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-windows-ipmac-using-powershell-techniques/"><u>Easy Windows IP/MAC: Using PowerShell Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-disk-space-on-win11-safely-keep-files-intact-max-156-chars/"><u>Enhancing Disk Space on Win11 Safely (Keep Files Intact, Max 156 Chars)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/epson-artisan-1430-printer-drivers-downloads-for-microsoft-windows-latest-version/"><u>Epson Artisan 1430 Printer Drivers Downloads for Microsoft Windows - Latest Version</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-info-processing-refunds-from-xbox-games/"><u>Essential Info: Processing Refunds From Xbox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-screen-capture-software-beyond-microsofts-snipping-capabilities/"><u>Essential Screen Capture Software Beyond Microsoft's Snipping Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essentials-of-windows-iscsi-initiator-and-access-methods/"><u>Essentials of Windows iSCSI Initiator and Access Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-move-and-copy-integration-for-enhanced-productivity/"><u>Expert Move and Copy Integration for Enhanced Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-the-missing-piece-reviving-windows-11s-lost-bluetooth/"><u>Fix the Missing Piece: Reviving Windows 11'S Lost Bluetooth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-convert-mp3-files-into-audible-cds-using-the-power-of-windows-and-imgburn/"><u>How to Convert Mp3 Files Into Audible CDs Using the Power of Windows and ImgBurn</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-hyper-v-on-the-latest-windows-11/"><u>How to Disable Hyper-V on the Latest Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-rockalldlldll-not-found-or-missing-error-on-windows-pc/"><u>How to Fix Rockalldll.dll Not Found or Missing Error on Windows PC</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-install-logitech-g920-software-on-your-pc-supports-windows-111087/"><u>How to Install Logitech G920 Software on Your PC - Supports Windows 11/10/8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-your-mouse-from-doing-backflips/"><u>How to Stop Your Mouse From Doing Backflips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-command-prompt-to-find-windows-errors-codes-and-fix-them/"><u>How to Use the Command Prompt to Find Windows Errors Codes and Fix Them</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-honor-magic5-ultimate-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-peek-at-the-cutting-edge-features-for-windows-users/"><u>In 2024, A Peek at the Cutting-Edge Features for Windows Users</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-navigating-youtube-for-ultimate-virtual-reality-adventures/"><u>In 2024, Navigating YouTube for Ultimate Virtual Reality Adventures</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-unmatched-video-upload-aides-to-twitter/"><u>In 2024, Unmatched Video Upload Aides to Twitter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-windows-11-more-engaging-with-themes/"><u>Make Windows 11 More Engaging with Themes</u></a></li>
<li><a href="https://some-skills.techidaily.com/master-iphone-multitasking-how-to-toggle-pip-on-youtube-app-for-2024/"><u>Master iPhone Multitasking  How to Toggle PIP on YouTube App for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-firewall-controls-five-techniques/"><u>Mastering Firewall Controls: Five Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-to-zero-clutter-windows-auto-delete-feature/"><u>Navigate to Zero Clutter: Windows' Auto-Delete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-xbox-app-store-crash-fixing-error-0x80073d26/"><u>Overcome Xbox App Store Crash: Fixing Error 0X80073D26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-microsoft-store-app-installation-errors/"><u>Overcoming Microsoft Store App Installation Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-system-call-error-in-windows-os/"><u>Overcoming System Call Error in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-perplexing-problem-of-windowss-c0000005/"><u>Overcoming the Perplexing Problem of Windows's C0000005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-picks-for-play-best-fps-counter-applications-on-your-windows-11-system/"><u>Prime Picks for Play: Best FPS Counter Applications on Your Windows 11 System</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/pros-choice-the-best-screen-recorders-for-editing/"><u>Pro's Choice  The Best Screen Recorders for Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverting-windows-viewer-to-original-arrangement/"><u>Reverting Windows Viewer to Original Arrangement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-a-step-by-step-windows-11-reboot-guide/"><u>Reviving Your PC: A Step-by-Step Windows 11 Reboot Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/safekeeping-sensitive-visuals-from-public-eyes/"><u>Safekeeping Sensitive Visuals From Public Eyes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-programs-against-windows-autoshrinks/"><u>Securing Programs Against Windows Autoshrinks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-0x800700e9-problem-in-xbox-game-pass-windows-11-edition/"><u>Solving 0X800700E9 Problem in Xbox Game Pass, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-guide-to-boost-gaming-with-tailored-amd-configurations/"><u>Strategic Guide to Boost Gaming with Tailored AMD Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-mobile-setup-with-one-click-apks-in-windows-11/"><u>Supercharge Your Mobile Setup with One Click APKs in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/tips-for-addressing-performance-errors-in-three-kingdoms-strategy-game/"><u>Tips for Addressing Performance Errors in Three Kingdoms Strategy Game</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/top-rated-online-video-editors-compatible-with-chromebook/"><u>Top-Rated Online Video Editors Compatible with Chromebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-workflow-essential-wins11-god-mode-tips/"><u>Transforming Workflow: Essential Wins11 God Mode Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-nvidia-cp-unresponsiveness-on-win-11/"><u>Troubleshooting Nvidia CP Unresponsiveness on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-onoff-the-power-modify-win11-registry-tools/"><u>Turn On/Off the Power: Modify Win11 Registry Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-list-of-windows-clients-for-sharing-files/"><u>Ultimate List of Windows Clients for Sharing Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-reducing-high-cpuram-demand-from-unrealcefsubprocess/"><u>Understanding & Reducing High CPU/RAM Demand From UnrealCEFSubprocess</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-implication-of-a-crossed-out-icon-in-explorer/"><u>What Is the Implication of a Crossed-Out Icon in Explorer?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-password-reset-lockout-period-change/"><u>Windows 10/11 Password Reset Lockout Period Change</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>