---
title: Standardizing Your Windows System Backups
date: 2024-06-25T16:57:30.602Z
updated: 2024-06-26T16:57:30.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Standardizing Your Windows System Backups
excerpt: This Article Describes Standardizing Your Windows System Backups
keywords: Windows Backup Standardization,Regular Backup Procedures,Safe Data Recovery Plans,Consistent File Protection,Systematic Save Strategies,Routine PC Preservation,Secure Backups Essentials
thumbnail: https://thmb.techidaily.com/c3d35b16437bab1ad5b7b686beca2df570e5510e7d66b97529a73f9cf277751a.jpg
---

## Standardizing Your Windows System Backups

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

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

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-printer-linkup/"><u>Streamlining Windows Printer Linkup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-windows-11-language-line-from-status-bar/"><u>Hide Windows 11 Language Line From Status Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/closed-folder-fixes-for-w11w10-double-click-malfunction/"><u>Closed Folder Fixes for W11/W10 Double-Click Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-password-safety-tools-for-windows-11-users/"><u>Winning Password Safety Tools for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-erroneous-code-fixing-0x800713f-mail-glitch-in-windows-11/"><u>Tackling Erroneous Code: Fixing 0X800713F Mail Glitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/epic-games-troubleshooting-on-pc-focus-on-login-issues/"><u>Epic Games Troubleshooting on PC: Focus on Login Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-30015-26-in-m365-for-windows-computers/"><u>Resolving Error Code 30015-26 in M365 for Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/limiting-users-ability-to-modify-windows-safescreen/"><u>Limiting Users' Ability to Modify Windows SafeScreen</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-direct-mp4-uploader-for-facebook-services/"><u>[Updated] 2024 Approved  Direct MP4 Uploader for Facebook Services</u></a></li>
<li><a href="https://fox-direct.techidaily.com/navigating-the-multi-stream-experience-on-netflix-for-2024/"><u>Navigating the Multi-Stream Experience on Netflix for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-streaming-success-new-youtube-monetization-rules/"><u>[Updated] Streaming Success  New YouTube Monetization Rules</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/windows-video-editing-top-imovie-alternatives-for-pc-for-2024/"><u>Windows Video Editing Top iMovie Alternatives for PC for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/beat-the-purchase-free-fb-playlists-download-for-2024/"><u>Beat the Purchase  Free FB Playlists Download for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-step-into-the-rhythm-of-social-video-editing-with-music-for-2024/"><u>[Updated] Step Into the Rhythm of Social Video Editing with Music for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-illustrate-like-a-pro-selecting-superior-vector-image-creators/"><u>[New] Illustrate Like a Pro  Selecting Superior Vector Image Creators</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-sony-xperia-1-v-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Sony Xperia 1 V for Free? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-professional-photography-hacks-perfecting-motion-blur-with-adobe-tools/"><u>[Updated] Professional Photography Hacks  Perfecting Motion Blur with Adobe Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>