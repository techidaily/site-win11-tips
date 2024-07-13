---
title: Navigating the Process of Win Backup Defaulting
date: 2024-07-12T16:52:25.984Z
updated: 2024-07-13T16:52:25.984Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Process of Win Backup Defaulting
excerpt: This Article Describes Navigating the Process of Win Backup Defaulting
keywords: Backup Restoration,Data Recovery,Default Status,Process Win Backup,Overcoming Failure,Win Backup Procedures,Resuming Lost Files
thumbnail: https://thmb.techidaily.com/2a9cc8bf4d555df620abafcb570dcc2752e8e2040a84b647ff438519a4be3866.jpg
---

## Navigating the Process of Win Backup Defaulting

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tech-tip-how-to-turn-off-nvidia-ui/"><u>Tech Tip: How to Turn Off NVIDIA UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-role-of-windows-print-management-interface/"><u>Understanding the Role of Windows Print Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-winget-in-windows-11-environments/"><u>Reactivating Winget in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-the-ultimate-list-top-10-intro-maker-tools-online/"><u>Updated 2024 Approved The Ultimate List Top 10 Intro Maker Tools Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-roblox-error-262-instantly/"><u>Overcoming Roblox Error 262 Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-the-hidden-search-bar-in-win11s-task-manager/"><u>Revealing the Hidden Search Bar in Win11's Task Manager</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-expanding-your-fb-video-scope-full-hd/"><u>[Updated] Expanding Your Fb Video Scope  Full HD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-library-accessibility-on-win-11-pcs/"><u>Troubleshooting Steam Library Accessibility on Win 11 PCs</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-jump-cut-like-a-pro-advanced-editing-techniques-in-fcpx-for-2024/"><u>Updated Jump Cut Like a Pro Advanced Editing Techniques in FCPX for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-gadget-showdown-unlocking-iphone-vs-galaxy-with-facial-scans/"><u>2024 Approved  Gadget Showdown  Unlocking iPhone Vs. Galaxy with Facial Scans</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-y100t-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-next-gen-editing-experience-reviewed-magix-video-pro-x/"><u>[Updated] Next-Gen Editing Experience Reviewed  Magix Video Pro X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-engineering-the-taskbar-key-steps-to-better-windows-11-ux/"><u>Re-Engineering the Taskbar: Key Steps to Better Windows 11 UX</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-mastering-the-16x9-ratio-5-expert-calculator-hacks/"><u>New 2024 Approved Mastering the 16X9 Ratio 5 Expert Calculator Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-headset-microphone-blockage/"><u>Unblocking Windows Headset Microphone Blockage</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unlock-chromes-full-potential-with-pip-across-devices/"><u>[New] Unlock Chrome's Full Potential with PIP Across Devices</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-adaptive-content-strategies-for-optimal-youtube-performance/"><u>[New] 2024 Approved  Adaptive Content Strategies for Optimal YouTube Performance</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unpacking-the-essence-of-digital-tales/"><u>2024 Approved  Unpacking the Essence of Digital Tales</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-modern-standby-gets-a-bad-rap-in-windows/"><u>Why Modern Standby Gets a Bad Rap in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-cutting-the-fat-in-windows-11/"><u>The Ultimate Guide to Cutting the Fat in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-errors-on-windows-effective-fixes/"><u>Tackling OneDrive Errors on Windows: Effective Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-muted-windows-start-button-icon/"><u>Resurrecting Your Muted Windows Start Button Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-faulty-troubleshooters-in-windows-os/"><u>Reinvigorating Faulty Troubleshooters in Windows OS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-fundamentals-of-e-narrative-creation-for-2024/"><u>[Updated] Fundamentals of E-Narrative Creation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-winterminals-bg-pic/"><u>Setting WinTerminal's Bg Pic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-blocking-self-starting-windows-store/"><u>Strategies for Blocking Self-Starting Windows Store</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-how-to-embed-a-youtube-video-in-powerpoint-4-methods/"><u>[Updated] In 2024, How to Embed a YouTube Video in PowerPoint [4 Methods]</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-harmonious-majesties-a-treasury-of-royalty-free-cinematic-piano-music-for-film-and-video-production/"><u>Updated In 2024, Harmonious Majesties A Treasury of Royalty-Free Cinematic Piano Music for Film & Video Production</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-multiscreen-woes/"><u>Understanding Windows Multiscreen Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-your-snaps-with-these-6-steps-for-windows-11-users/"><u>Swivel Your Snaps with These 6 Steps for Windows 11 Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-engagement-mastery-how-to-craft-instagrams-best-puzzles/"><u>[Updated] 2024 Approved  Engagement Mastery  How to Craft Instagram's Best Puzzles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-banishing-the-persistent-pink-error-on-windows/"><u>The Ultimate Guide to Banishing the Persistent Pink Error on Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-prime-greener-recording-devices-utilization-tips/"><u>[New] Prime Greener Recording Devices  Utilization Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-running-sfc-on-windows/"><u>Understanding and Running SFC on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-are-m1-laptops-setting-the-standard-in-editing-studios/"><u>[Updated] Are M1 Laptops Setting the Standard in Editing Studios?</u></a></li>
</ul></div>
