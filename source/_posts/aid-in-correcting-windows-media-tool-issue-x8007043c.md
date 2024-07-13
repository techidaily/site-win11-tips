---
title: Aid in Correcting Windows' Media Tool Issue X.8007043C
date: 2024-07-12T18:04:17.278Z
updated: 2024-07-13T18:04:17.278Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Aid in Correcting Windows' Media Tool Issue X.8007043C
excerpt: This Article Describes Aid in Correcting Windows' Media Tool Issue X.8007043C
keywords: Fix Media Tool Error Windows,Resolve WinMedia Problem,Address Windows Media Tool Fault,Correct Media Tool Issue Window,Unlock X.8007043C WinTool,Tackle Media Tool Windows Glitch,Solve Media Error Code 8007043C
thumbnail: https://thmb.techidaily.com/c6a00ed9bc739f2f19c543f786366f0b15e1dcc95bf3f36705f1220c5880cb1d.jpg
---

## Aid in Correcting Windows' Media Tool Issue X.8007043C

 The Media Creation Tool lets you upgrade your PC to a new Windows version or create a bootable Windows USB drive. At times, when you try to run the tool, you may encounter the error code 0x8007043C - 0x90017.

 The primary reason for this error is insufficient permission to run the tool or if it has been blocked from running on your PC. You can unblock it from the tool's properties to fix the error. Here is how to fix the Media Creation Tool 0x8007043C - 0x90017 error and perform an upgrade or create a bootable drive.

## 1\. Run the Media Creation Tool as an Administrator

 You can fix permission issues by executing the Media Creation Tool with administrator privileges. By default, the tool does not require administrator rights to run. But you can [manually run Windows apps as an administrator](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) to see if that resolves the error.

To run Media Creation Tool as administrator:

1. Open File Explorer and navigate to where you have saved the**mediacreationtool.exe** file.
2. Right-click on the**Mediacreationtool.exe** file and select**Run as administrator.**  
![run media creation tool as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-media-creation-tool-as-administrator.jpg)
3. Click**Yes** when prompted by UAC. Wait for the tool to launch and check for any improvements.

## 2\. Unblock the Media Creation Tool

 Windows can block suspicious executable files from running to protect your computer. However, it can also block genuine files due to false positives.

 If you have downloaded the Media Creation Tool from the Microsoft website, check if the file is blocked on your PC. If yes, you can unblock the executable file from the Properties dialog. Here’s how to do it.

1. Navigate to the location where the Media Creation Tool is saved.
2. Select and right-click on the tool and select**Properties** .
3. In the**General** tab, locate the**Security** section.
4. Next, check the**Unblock** option.  
![unblock media creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unblock-media-creation-tool.jpg)
5. Click**Apply** , and the security option will disappear.
6. Next, click**OK** to apply the changes.
7. Run the Media Creation Tool again, and it should work without the 0x8007043C - 0x90017 error.

## 3\. Install Any Pending Windows Updates

 If the error occurs during an upgrade, ensure you have installed all the latest updates available for your PC. Often Windows updates consist of performance improvements and bug fixes. Install all the updates to see if that helps you resolve any issues interrupting the upgrade process.

To update your Windows computer:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows update** tab in the left pane.
3. Click on**Check for updates** to find the pending updates.  
![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)
4. If available, click on**Download & Install** and wait for the updates to install. Restart your PC and run the tool again to see if the error is resolved.

## 4\. Run the Windows Update Troubleshooter

 The built-in Windows Update troubleshooter is a great way to fix Windows Update issues on Windows 11\. It will scan the system for issues and try to fix them automatically.

To run the Windows Update Troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .  
![Windows 11 settings troubleshoot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-troubleshoot.jpg)
3. Next, click on**Other troubleshooters.**  
![Windows-11-settings-troubleshoot-other-troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-troubleshoot-other-troubleshooters.jpg)
4. Under the**Most frequent** section, click the**Run** button for**Windows Update.**  
![windows update troubleshooter run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-run.jpg)
5. The update troubleshooter will initialize diagnostic and scan for issues. If found, it will apply the fix and show a status report. With the Windows Update dialog open, run Media Creation Tool and check if the error is resolved.
6. If not, click**No** in the Windows Update troubleshooter dialog.
7. Next, click on**View detailed** information. Here you can view the issues found and potential issues that were checked.

## 5\. Check for a Third-Party Antivirus Conflict

 Third-party antivirus can be overzealous and block genuine system modifications as malicious. You can disable the security app temporarily to determine if your third-party antivirus is triggering the error.

 Once disabled, relaunch the Media Creation Tool and check if the error persists. If not, check and reconfigure your antivirus settings or switch to one of the [best antivirus solutions on Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) .

## 6\. Run the DISM and System File Checker Tool

 Deployment Image Servicing and Management (DISM) is a command-line tool to repair your Windows 10 and 11 images. It can look for corrupted or missing system files and repair them to fix critical errors on your PC.

 System File Checker utility can help you fix malfunctioning Windows functions. It will scan the system for issues and, if detected, restore the necessary files to fix the problem. You can run the DISM and System File Checker tools in tandem to get the best result. Here’s how to do it.

To run the DISM and System File Checker Tool:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command** **Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command to run the DISM tool:  
DISM.exe /Online /Cleanup-image /Restorehealth
4. ![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dism-scan-health-restore-health-command-prompt.jpg)  
 Press**Enter** to execute the command. It may take some time for the process to complete. Once the process reaches 100%, you can run the System File Checker tool.
5. Type the following command and press**Enter** to run the System File Checker utility:  
sfc /scannow
6. The verification can take several minutes. So wait for the verification to reach 100%. The return will indicate if any issue is found and if the tool was able to fix it.
7. Type**exit** and press**Enter** to close the Command Prompt.

## 7\. Use Rufus to Create a Bootable USB Drive

 While Media Creation Tools lets you create a bootable drive, it is not your only option. You can use a popular third-party app, Rufus, to [create a bootable Windows USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/) . You can [download a Windows 11 ISO file](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft servers and then use it to create an installation media using Rufus.

 Rufus is safe to use and offers some customization, such as choosing a partition format. You can also download the ISO file using Rufus.

## 8\. Perform a Repair Reinstall or Clean Install Windows

 Before we do a full clean of Windows, consider performing a repair reinstall. This allows you to perform an in-place upgrade and [reinstall the Windows OS without deleting your files and apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) .

 If all else fails, a clean install may be necessary. Make sure to create a backup of your data and then learn [how to clean install Windows 11](https://www.makeuseof.com/how-to-clean-install-windows-11/) .

## Fixing the Media Creation Tool Error 0x8007043C - 0x90017 Error

 The 0x8007043C - 0x90017 Media Creation Tool error is often due to an insufficient permission issue. You can unblock the utility in the Properties dialog to run the utility without the error. Only in rare instances, you may need to perform a clean install due to system file corruption.


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
<li><a href="https://instagram-videos.techidaily.com/updated-crafting-visual-narratives-adding-memorable-story-emoji-images-for-2024/"><u>[Updated] Crafting Visual Narratives  Adding Memorable Story Emoji Images for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-realme-narzo-n55-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Realme Narzo N55 FRP Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-taskbar-size-step-by-step-guide/"><u>Altering Taskbar Size: Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-the-legalities-of-capturing-live-video-on-online-platforms-youtube/"><u>[Updated] In 2024, The Legalities of Capturing Live Video on Online Platforms (YouTube)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altwindirstat-strategies-for-effective-disk-space-management/"><u>AltWinDirStat Strategies for Effective Disk Space Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windowed-app-movement-windows-task-managing-tips/"><u>Avoiding Windowed App Movement: Windows Task Managing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-space-for-storage-sluggishness-sets-in/"><u>Blackview: Space for Storage, Sluggishness Sets In</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-reno-8t-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo Reno 8T to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginner-friendly-guide-setting-up-the-jdk-on-windows-11/"><u>Beginner-Friendly Guide: Setting Up the JDK on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-pc-display-orientation-via-windows/"><u>Adjust PC Display Orientation via Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pushing-boundaries-my-quest-to-overcome-app-guard-censorship/"><u>Pushing Boundaries: My Quest to Overcome App Guard Censorship</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resource-allocation-for-ntoskrnlexe/"><u>Balancing Resource Allocation for Ntoskrnl.exe</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-exploring-the-magic-of-ai-selfie-generators/"><u>New Exploring the Magic of AI Selfie Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-managing-users-via-command-prompt/"><u>Advanced Tips for Managing Users via Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-not-recognized-issues-in-windows-with-these-fixes/"><u>Banish 'Not Recognized' Issues in Windows with These Fixes</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-navigating-the-apple-podcast-platform/"><u>In 2024, Navigating the Apple Podcast Platform</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-data-realm-renaissance-pioneering-cloud-services-s-needs/"><u>[New] Data Realm Renaissance  Pioneering Cloud Services 'S Needs</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-from-the-apple-iphone-15-plus-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock From the Apple iPhone 15 Plus Without Previous Owner?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-hotkeys-for-instantaneous-windows-redos/"><u>Boost Efficiency: Hotkeys for Instantaneous Windows Redos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-nvidia-writes-of-error-3-in-win1011/"><u>Avoiding NVIDIA' Writes of Error 3 in Win10/11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/mobile-video-to-audio-conversion-made-easy-top-apps-reviewed-for-2024/"><u>Mobile Video to Audio Conversion Made Easy Top Apps Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-integration-in-windows-11-for-effective-multitasking/"><u>Android Integration in Windows 11 for Effective Multitasking</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/stop-frames-dropping-obs-troubleshooting-guide-for-2024/"><u>Stop Frames Dropping  OBS Troubleshooting Guide for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-viral-eats-top-10-tiktok-cooking-challenges/"><u>In 2024, Viral Eats  Top 10 TikTok Cooking Challenges</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-monetary-gains-mr-beast-in-focus/"><u>In 2024, Monetary Gains  Mr. Beast in Focus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-pitfalls-of-mysterious-obs-studio-recordings/"><u>Avoiding the Pitfalls of Mysterious OBS Studio Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-peaceful-slumber-for-your-w11-gadgets-at-rest/"><u>Automate Peaceful Slumber for Your W11 Gadgets at Rest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-win11-notepad-with-genius-mentor/"><u>Augment Win11 Notepad with Genius Mentor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-copy-pasting-expertise/"><u>Boost Your Typing, Copy-Pasting Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/arrow-anomalies-unveiled-and-resolved-for-windows-users/"><u>Arrow Anomalies Unveiled and Resolved for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-app-size-efficiency/"><u>Assessing Windows App Size Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/behind-closed-curtains-of-windows-how-to-open-hidden-self-assessment-tool/"><u>Behind Closed Curtains of Windows: How to Open Hidden Self-Assessment Tool</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-five-best-free-fb-video-downloader-hacks/"><u>In 2024, Five Best Free FB Video Downloader Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-development-with-these-wsl-2-secrets/"><u>Boost Your Development with These WSL 2 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-browser-safety-on-windows-11-with-the-implementation-of-defender-aguard/"><u>Boost Browser Safety on Windows 11 with the Implementation of Defender Aguard</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-backtrack-with-flair-ingenious-ways-to-watch-youtube-reverse/"><u>2024 Approved  Backtrack with Flair  Ingenious Ways to Watch Youtube Reverse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-performance-by-enabling-automatic-file-deletion-in-winos/"><u>Boost System Performance by Enabling Automatic File Deletion in WINOS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-fine-tuning-audacitys-decibel-settings-for-perfect-balance/"><u>2024 Approved Fine-Tuning Audacitys Decibel Settings for Perfect Balance</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-poco-c50-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Poco C50 Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-the-comprehensible-guide-for-resolving-error-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Beating the Bug: The Comprehensible Guide for Resolving Error 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-dynamic-background-anytime/"><u>Adjusting Your Windows Dynamic Background Anytime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-microsofts-new-taskbar-helper-in-windows-11-streamlines-tasks/"><u>AI Integration: Microsoft's New Taskbar Helper in Windows 11 Streamlines Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-organization-in-windows-discover-5-key-folder-insights/"><u>Boost Organization in Windows - Discover 5 Key Folder Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-to-windows-webcam-conversion-guide-for-windows-11-users/"><u>Android to Windows Webcam Conversion Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminal-backdrop/"><u>Adjusting Windows Terminal Backdrop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-optimal-action-capture-software-insights/"><u>In 2024, Optimal Action Capture Software Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-apps-with-efficient-internet-fixes/"><u>Boost Your Windows Apps with Efficient Internet Fixes</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-imovie-for-pc-discover-the-top-10-video-editing-alternatives/"><u>New 2024 Approved IMovie for PC Discover the Top 10 Video Editing Alternatives</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-beyond-virtualdub-discover-the-top-video-editing-software-options/"><u>Updated 2024 Approved Beyond Virtualdub Discover the Top Video Editing Software Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-operations-efficient-data-alignment-in-win11/"><u>Boost Operations: Efficient Data Alignment in Win11</u></a></li>
</ul></div>
