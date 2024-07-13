---
title: Guiding Through Default Windows Backup Reset
date: 2024-07-12T17:14:00.442Z
updated: 2024-07-13T17:14:00.442Z
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
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-compatibility-challenges-with-intel-gpu/"><u>Guiding Users Through Compatibility Challenges with Intel GPU</u></a></li>
<li><a href="https://video-capture.techidaily.com/streamlined-recording-of-powerpoint-slides-via-webcam-for-2024/"><u>Streamlined Recording of PowerPoint Slides via Webcam for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-to-access-mspaint-in-windows-11/"><u>Discovering How to Access MSPaint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-hypervisorerror-blue-screen-on-windows-10-and-11/"><u>5 Ways to Fix the HYPERVISOR_ERROR Blue Screen on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-time-intensive-gpsvc-hangs/"><u>Eliminating Time-Intensive GPSVC Hangs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-vivo-s18e-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Vivo S18e</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-troubleshooting-iphone-camera-failing-to-autofocus/"><u>[New] Troubleshooting iPhone Camera Failing to Autofocus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-versatile-applications-top-10-ways-to-use-powertoys/"><u>Explore Versatile Applications: Top 10 Ways to Use PowerToys</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/best-15-subtitle-apps/"><u>Best 15 Subtitle Apps</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-driving-engagement-and-growth-the-role-of-brand-in-youtube-success/"><u>2024 Approved  Driving Engagement and Growth  The Role of Brand in YouTube Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-calculator-opening-method/"><u>Mastering Windows 11 Calculator Opening Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268439990-chrome-freeze-no-more-top-solutions-for-windows-11-users/"><u>Chrome Freeze No More: Top Solutions for Windows 11 Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-caps-lock-and-numeric-status-on-taskbar-tray-of-win11/"><u>Displaying Caps Lock & Numeric Status on Taskbar Tray of Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-files-in-flux-top-6-methods-to-extract-and-duplicate-windows-11-folder-trails/"><u>Finding Files in Flux: Top 6 Methods to Extract and Duplicate Windows 11 Folder Trails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-cant-access-mail-alert-on-windows-11s-mail-app/"><u>Unveiling Fixes for Can't Access Mail Alert on Windows 11'S Mail App</u></a></li>
<li><a href="https://fox-direct.techidaily.com/your-words-powered-by-ai-free-of-cost/"><u>Your Words Powered by AI, Free of Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-automation-for-batch-files/"><u>Mastering Windows Automation for Batch Files</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ideal-images-finding-the-perfect-screen-moments-for-2024/"><u>Ideal Images  Finding the Perfect Screen Moments for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-primes-textual-missteps-on-windows-11-desktops/"><u>Correct Prime's Textual Missteps on Windows 11 Desktops</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Asus ROG Phone 7 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-create-stunning-highlights-top-video-editing-tools-for-desktop-and-mobile/"><u>Updated 2024 Approved Create Stunning Highlights Top Video Editing Tools for Desktop and Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-access-to-registry-tools-in-win11/"><u>How to Manage Access to Registry Tools in Win11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-trending-beats-and-basic-tiktok-steps-for-2024/"><u>[New] Trending Beats and Basic TikTok Steps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-your-onedrive-to-a-desired-spot-on-win10/"><u>Transitioning Your OneDrive to a Desired Spot on Win10</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-top-12-audio-converters-a-comprehensive-review-for-2024/"><u>New Top 12 Audio Converters A Comprehensive Review for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-manual-timezone-setting-in-microsoft-os/"><u>Troubleshoot Manual Timezone Setting in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-dilemran-of-winscripterrors/"><u>Deciphering the Dilemran of WinScriptErrors</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-realme-narzo-60x-5g-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Realme Narzo 60x 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx939-dll-in-win11/"><u>Addressing Missing D3DX9_39 DLL in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-efficiently-extract-onedrive-from-windows-explorer/"><u>How To Efficiently Extract OneDrive From Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-management-adding-this-pc-to-windows-desktop/"><u>Window Management: Adding 'This PC' To Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-productivity-integrating-flow-launcher-into-daily-routine/"><u>Amplify Productivity: Integrating Flow Launcher Into Daily Routine</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-amass-1000-visionary-supporters-fast-track-style/"><u>In 2024, Amass 1,000 Visionary Supporters Fast-Track Style</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-tips-for-perfected-framing-implementing-letterboxing-on-social-media-for-2024/"><u>[Updated] Tips for Perfected Framing  Implementing Letterboxing on Social Media for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-streaming-mastery-record-hulu-playback-on-multiple-systems/"><u>2024 Approved  Streaming Mastery  Record Hulu Playback on Multiple Systems</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-haven-guide-top-3-non-youtube-video-portals/"><u>In 2024, The Haven Guide  Top 3 Non-Youtube Video Portals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-startup-the-comprehensive-guidebook/"><u>Master Your Windows Startup: The Comprehensive Guidebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-full-use-of-the-control-key-in-windows-11/"><u>Enabling Full Use of the Control Key in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-system-editor-access-control-on-windows-11/"><u>Techniques for System Editor Access Control on Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-mastering-tempo-sync-adjusting-video-clips-with-premiere-pros-audio-beatmap/"><u>Updated 2024 Approved Mastering Tempo Sync Adjusting Video Clips with Premiere Pros Audio Beatmap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-high-dpi-displays-a-windows-guide/"><u>Dealing with High DPI Displays: A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-setup-guide-for-steam-deck-owners/"><u>Windows Setup Guide for Steam Deck Owners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-system-exploration-in-win11-6-keyways-to-duplicating-file-and-folder-paths/"><u>File System Exploration in Win11: 6 Keyways to Duplicating File and Folder Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphered-defense-dont-shift-too-suddenly/"><u>Deciphered Defense? Don't Shift Too Suddenly</u></a></li>
<li><a href="https://extra-tips.techidaily.com/sprint-to-stunning-photos-in-win-11-edition/"><u>Sprint to Stunning Photos in Win 11 Edition</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-tailoring-content-to-trends-organic-growth-strategies-for-youtubers/"><u>[New] 2024 Approved  Tailoring Content to Trends  Organic Growth Strategies for YouTubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-unsolicited-opens-in-ms-store-on-windows-10/"><u>Halt Unsolicited Opens in MS Store on Windows 10</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-speaking-like-a-pro-tips-to-upgrade-your-google-meet-skills/"><u>2024 Approved  Speaking Like a Pro  Tips to Upgrade Your Google Meet Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-users-should-anticipate-sudo/"><u>Why Windows Users Should Anticipate Sudo</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-elite-recording-software-to-handle-ultra-hd-screenshots/"><u>[Updated] Elite Recording Software to Handle Ultra HD Screenshots</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-perfect-your-sound-game-with-these-step-by-step-tiktok-tips/"><u>[New] In 2024, Perfect Your Sound Game with These Step-by-Step TikTok Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-recording-basics-for-newcomers-on-win-11/"><u>Audio Recording Basics for Newcomers on Win 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/mastering-disconitro-the-ultimate-guide-for-freepaid-entry/"><u>Mastering DiscoNitro  The Ultimate Guide for Free/Paid Entry</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-infographic-mind-numbing-youtube-factsfigures-and-statistics-2017/"><u>2024 Approved  Infographic - Mind Numbing YouTube Facts,Figures and Statistics 2017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-linux-into-your-windows-desktop-world/"><u>Integrating Linux Into Your Windows Desktop World</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/navigate-and-network-adding-desktopmobile-friends/"><u>Navigate & Network  Adding Desktop/Mobile Friends</u></a></li>
</ul></div>
