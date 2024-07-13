---
title: "Accessing D: Drive Folder in Windows Explorer"
date: 2024-07-12T17:53:39.845Z
updated: 2024-07-13T17:53:39.845Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accessing D: Drive Folder in Windows Explorer"
excerpt: "This Article Describes Accessing D: Drive Folder in Windows Explorer"
keywords: "Windows Explorer Access,Drive Exploration,Windows File Folder,Navigate Windows D:,View D:Drive,Direct Drive Access,Drives in Windows OS"
thumbnail: https://thmb.techidaily.com/b0350890102e8bceb542486b6a13817e51d92335c8505179cd1df5114471ab31.jpg
---

## Accessing D: Drive Folder in Windows Explorer

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
<li><a href="https://win11-tips.techidaily.com/the-guide-to-instant-uninstalling-via-windows-shortcuts/"><u>The Guide to Instant Uninstalling via Windows Shortcuts</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-meizu-21-pro-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Meizu 21 Pro Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-making-the-most-of-both-worlds-tweeting-and-sending-videos-with-whatsapp/"><u>2024 Approved  Making the Most of Both Worlds  Tweeting & Sending Videos with WhatsApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-vlc-unrecognized-media-issue/"><u>Overcoming Windows VLC Unrecognized Media Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://extra-skills.techidaily.com/open-source-chill-beats-for-2024/"><u>Open Source Chill Beats for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-xiaomi-redmi-k70-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-shortage-of-physical-storage-space-vm-errors/"><u>Resolving Shortage of Physical Storage Space (VM) Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-explorer-onedrive-as-a-launchpad/"><u>Mastering File Explorer: OneDrive as a Launchpad</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-the-digital-space-with-impactful-fb-giveaway-posts/"><u>In 2024, Navigating the Digital Space with Impactful FB Giveaway Posts</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-10-premium-text-tricks-for-videos/"><u>[Updated] 10 Premium Text Tricks for Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-illuminate-your-recording-setup-how-to-prevent-a-dark-screen-on-obs/"><u>In 2024, Illuminate Your Recording Setup  How to Prevent a Dark Screen on OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-y100i-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo Y100i Quickly | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-a-newbies-compendium-of-best-cinematography-devices-35mm-pands-for-2024/"><u>[Updated] A Newbie's Compendium of Best Cinematography Devices (35Mm-P&S) for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-unlocking-creativity-top-10-insider-canva-tricks/"><u>[New] Unlocking Creativity  Top 10 Insider Canva Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-file-explorer-in-windows-10plus/"><u>Jumpstart File Explorer in Windows 10+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-experience-classic-ps1-games-with-leading-emulators/"><u>[New] Experience Classic PS1 Games with Leading Emulators</u></a></li>
<li><a href="https://some-guidance.techidaily.com/strategies-for-identifying-lowest-cloud-data-rates-for-2024/"><u>Strategies for Identifying Lowest Cloud Data Rates for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-seamless-mp4-extraction-your-fb-video-fix/"><u>[New] 2024 Approved  Seamless MP4 Extraction – Your FB Video Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-samsung-galaxy-s24-ultra-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Samsung Galaxy S24 Ultra</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-streamline-your-recordings-fix-frames-out-of-sync-in-obs/"><u>2024 Approved  Streamline Your Recordings  Fix Frames Out of Sync in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-tecno-spark-10c-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Tecno Spark 10C? Fixed | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-audio-formatting-guide-from-srt-to-xmlssa-ttml-etc/"><u>In 2024, Audio Formatting Guide  From SRT to XML/SSA, TTML, Etc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-clis-for-efficient-task-management-windows-11/"><u>Integrating CLIs for Efficient Task Management (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-sound-level-configurations-in-windows/"><u>Restoring Default Sound Level Configurations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-google-pixel-7a-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Google Pixel 7a Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-finding-your-voice-on-youtube-a-guide-to-selective-audiences/"><u>[Updated] In 2024, Finding Your Voice on YouTube  A Guide to Selective Audiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/game-stability-avoiding-rtx-crashes/"><u>Game Stability: Avoiding RTX Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-route-to-your-windows-disk-space-win-1011/"><u>Quick Route to Your Windows Disk Space (Win 10/11)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-4-techniques-for-effective-android-content-capturing-for-2024/"><u>[New] 4 Techniques for Effective Android Content Capturing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-x80072f30-in-windows/"><u>Resolving Microsoft Store Error X80072F30 in Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snapchats-own-creativity-lab-inspire-over-a-hundred-private-stories-with-original-titles/"><u>[New] Snapchat's Own Creativity Lab  Inspire over a Hundred Private Stories with Original Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-no-write-error-a-guide-for-windows-users/"><u>Tackling the No Write Error: A Guide for Windows Users</u></a></li>
</ul></div>
