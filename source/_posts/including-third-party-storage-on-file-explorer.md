---
title: Including Third-Party Storage on File Explorer
date: 2024-07-12T16:35:34.899Z
updated: 2024-07-13T16:35:34.899Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Including Third-Party Storage on File Explorer
excerpt: This Article Describes Including Third-Party Storage on File Explorer
keywords: CloudFileStorage,FileExplorerIntegration,ExtraBackupOptions,StorageToolsAccess,SecureSyncPlatforms,ThirdPartySaving,ExplorerCloudUploading
thumbnail: https://thmb.techidaily.com/0275b65ec50c26c096fbd58891ad5416742f7595ba3ecd2f30cf7442df5bd214.png
---

## Including Third-Party Storage on File Explorer

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

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/updated-fine-tuning-team-call-aesthetics-pre-and-post-customization/"><u>[Updated] Fine-Tuning Team Call Aesthetics  Pre & Post Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-user-support-4-new-windows-features/"><u>Transforming User Support: 4 New Windows Features</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-12-mini-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 12 mini to other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-screen-sharing-showdown-obs-vs-twitch-studio-face-off/"><u>[Updated] Screen Sharing Showdown  OBS vs Twitch Studio Face-Off</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-youtubes-entry-level-manual-for-effective-channel-creation/"><u>[New] Youtube's Entry-Level Manual for Effective Channel Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-task-managers-welcome-screenscape-in-win11/"><u>Adjusting Task Manager's Welcome Screenscape in Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-crafting-the-ideal-youtube-playlist-an-easy-step-by-step-method/"><u>2024 Approved  Crafting the Ideal YouTube Playlist  An Easy, Step-by-Step Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/universal-font-collection-windows-installation-steps/"><u>Universal Font Collection: Windows Installation Steps</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-itel-a70-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Itel A70 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-premier-screen-picks-for-ps5-and-xbox-games/"><u>[New] The Premier Screen Picks for PS5 and Xbox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-aural-anomaly-fixing-audacity-writes-on-wos/"><u>Tackling the Aural Anomaly: Fixing Audacity' Writes on WOS</u></a></li>
<li><a href="https://extra-information.techidaily.com/maximizing-impact-when-to-start-your-podcast/"><u>Maximizing Impact  When to Start Your Podcast</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-breaking-down-barriers-with-shared-youtube-curations-for-2024/"><u>[Updated] Breaking Down Barriers with Shared YouTube Curations for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-essential-breakdown-for-wm6-setup-for-2024/"><u>[Updated] Essential Breakdown for WM6 Setup for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-pathway-for-changing-login-method-from-pin-to-passwords-on-windows-11/"><u>Unveiling the Pathway for Changing Login Method From PIN to Passwords on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-outlook-problems-on-pcs/"><u>Understanding and Fixing Outlook Problems on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-removing-virtualization-support-on-win11/"><u>Tips for Removing Virtualization Support on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/using-dialer-in-win-11/"><u>Using Dialer in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-on-or-off-windows-digital-protection-filter/"><u>Switching on or Off Windows' Digital Protection Filter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-service-management-for-optimized-windows-11/"><u>Strategic Service Management for Optimized Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-updating-window-11s-context-menu/"><u>Streamlining Tasks: Updating Window 11'S Context Menu</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/frost-giants-clash-gods-of-war-ragnarok-unleashed/"><u>Frost Giants Clash  Gods of War, Ragnarok Unleashed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-for-windows-1011-search-that-fails-to-display-output/"><u>Troubleshooting for Windows 10/11 Search that Fails to Display Output</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-free-video-editor-options-for-beginners-desktop-online-and-mobile/"><u>Updated Free Video Editor Options for Beginners Desktop, Online, and Mobile</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-virtual-warriors-journey-7-intense-fps-games-for-2024/"><u>[New] Virtual Warriors’ Journey - 7 Intense FPS Games for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-build-at-home-an-affordable-and-versatile-virtual-reality-headset/"><u>In 2024, Build at Home an Affordable and Versatile Virtual Reality Headset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-aggregatorhostexe-windows-functionality-and-safety-concerns/"><u>Understanding AggregatorHost.exe: Windows' Functionality & Safety Concerns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-keyboard-command-center-mastery-of-shortcuts-for-fixed-paste-tasks/"><u>Win11's Keyboard Command Center: Mastery of Shortcuts for Fixed Paste Tasks</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-swiftly-overcome-video-send-errors-in-facebook-chat-for-iphones-android/"><u>[New] Swiftly Overcome Video Send Errors in Facebook Chat for iPhones, Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-inactive-windows-file-alignment-service/"><u>Solutions for Inactive Windows File Alignment Service</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-ultimate-guide-to-iphoneipad-screenshot-tools/"><u>2024 Approved  The Ultimate Guide to iPhone/iPad Screenshot Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/pixelperfect-pro-focus-on-mac-and-windows-snaps/"><u>PixelPerfect Pro  Focus on Mac & Windows Snaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipgear-gone-wrong-nine-effective-tips-to-get-it-running-again/"><u>SnipGear Gone Wrong? Nine Effective Tips to Get It Running Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-microsofts-copilot-key-for-windows-11-users/"><u>Unveiling the Secrets of Microsoft's Copilot Key for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-unregistered-package-error-in-win11-images/"><u>Steps to Resolve Unregistered Package Error in Win11 Images</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-3-actionable-ways-to-create-countdown-animation-for-videos/"><u>In 2024, 3 Actionable Ways to Create Countdown Animation for Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-spotlight-techniques-for-android-videography/"><u>In 2024, Spotlight Techniques for Android Videography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-failed-updates-error-0x800f0845/"><u>Steps to Fix Failed Updates - Error 0X800f0845</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-behind-the-scenes-guide-to-elusive-instagram-tools/"><u>[Updated] Behind-the-Scenes Guide to Elusive Instagram Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-why-drives-vanish-on-windows-fix-guide-required/"><u>Unveiling Why Drives Vanish on Windows - Fix Guide Required</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-adjustments-for-enhanced-windows-bar/"><u>Step-by-Step Adjustments for Enhanced Windows Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-win-microphone-functionality/"><u>Troubleshoot Win Microphone Functionality</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/precision-shade-modifier-for-2024/"><u>Precision Shade Modifier for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-troubleshooting-tactics-for-non-functional-firefox-in-windows/"><u>7 Troubleshooting Tactics for Non-Functional Firefox in Windows</u></a></li>
</ul></div>
