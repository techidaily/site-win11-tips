---
title: The Path to Reinstating Default Windows Backups
date: 2024-06-25T17:06:34.698Z
updated: 2024-06-26T17:06:34.698Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Path to Reinstating Default Windows Backups
excerpt: This Article Describes The Path to Reinstating Default Windows Backups
keywords: Restoring Windows Backup,Windows Defrag & Repair,Data Recovery Tool,System File Checker Fix,Registry Correction Guide,WinRE Boot Success,Default Backups Reinstated
thumbnail: https://thmb.techidaily.com/f9a9cc9d25c2277c00a95f3b41983be5b23439a73a148ad43909fb1af78cba44.jpg
---

## The Path to Reinstating Default Windows Backups

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
<li><a href="https://win11-tips.techidaily.com/synchronizing-camera-use-among-windows-programs/"><u>Synchronizing Camera Use Among Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-latency-strategies-to-fasten-windows-discord/"><u>Lowering Latency: Strategies to Fasten Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-eliminate-path-error-in-windows/"><u>Guide to Eliminate PATH Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-erratic-print-device-in-os/"><u>Troubleshooting Erratic Print Device in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/documentation-skills-snapping-windows-uac-prompts/"><u>Documentation Skills: Snapping Windows UAC Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-file-transfer-via-winrar-6-corrective-steps-for-sums/"><u>Secure File Transfer via WinRAR: 6 Corrective Steps for Sums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-personalized-lock-patterns-on-windows-11/"><u>Mastering Personalized Lock Patterns on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-cant-access-mail-alert-on-windows-11s-mail-app/"><u>Unveiling Fixes for Can't Access Mail Alert on Windows 11'S Mail App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-flawless-display-with-win11-settings/"><u>Achieve Flawless Display with Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-novel-way-to-manage-galaxy-devices-with-windows-11/"><u>A Novel Way to Manage Galaxy Devices with Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-realme-c51-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Realme C51 | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/5-best-sites-for-quick-templates-on-youtube-for-2024/"><u>5 Best Sites for Quick Templates on YouTube for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-to-sonic-treasures-downloading-app-based-audio-content/"><u>In 2024, Navigating to Sonic Treasures  Downloading App-Based Audio Content</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/unlocking-facebook-financial-gains-a-step-by-step-guide/"><u>Unlocking Facebook Financial Gains  A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-twitch-to-facebook-broadcasting-best-practices/"><u>[New] 2024 Approved  Twitch to Facebook Broadcasting Best Practices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unlock-the-power-of-pinterest-top-5-free-extractors-at-hand/"><u>[New] Unlock the Power of Pinterest  Top 5 Free Extractors at Hand</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/ride-the-waves-with-top-tier-surf-cameras-for-2024/"><u>Ride the Waves with Top-Tier Surf Cameras for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-the-best-tools-for-crafting-unforgettable-highlight-reels/"><u>New 2024 Approved The Best Tools for Crafting Unforgettable Highlight Reels</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-best-10-free-video-translators-to-mitigate-translation-risks/"><u>Updated In 2024, Best 10 Free Video Translators to Mitigate Translation Risks</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-how-to-put-music-over-a-video/"><u>New In 2024, How to Put Music Over a Video?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>