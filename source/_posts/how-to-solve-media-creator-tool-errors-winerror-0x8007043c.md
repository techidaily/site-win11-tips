---
title: "How to Solve Media Creator Tool Errors: WinError 0X8007043C"
date: 2024-07-12T17:21:27.987Z
updated: 2024-07-13T17:21:27.987Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Solve Media Creator Tool Errors: WinError 0X8007043C"
excerpt: "This Article Describes How to Solve Media Creator Tool Errors: WinError 0X8007043C"
keywords: Media Creator Fix Guide,Resolving WinError 0X8007043c,WinError Error Solution,Media Tool Error Troubleshooting,Handling WinError in Windows,Eliminating WinError Media Errors,Solve WinError 0X8007043C Issue
thumbnail: https://thmb.techidaily.com/a8037b9cb425e19a9ec57f5feba58cc91bfb4e98ab568e20793fc881abc0b40e.jpg
---

## How to Solve Media Creator Tool Errors: WinError 0X8007043C

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
<li><a href="https://windows11.techidaily.com/improving-workflow-integration-adding-shortcuts-to-the-wordpad-menu-of-windows-11/"><u>Improving Workflow Integration: Adding Shortcuts to the WordPad Menu of Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-ensure-periscope-videos-are-secured-post-record-for-2024/"><u>How to Ensure Periscope Videos Are Secured Post-Record for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatenighttimedisplaynotepadwin/"><u>ActivateNighttimeDisplayNotepadWin</u></a></li>
<li><a href="https://screen-capture.techidaily.com/crafting-flawless-game-captures-roblox-and-macos-techniques-for-2024/"><u>Crafting Flawless Game Captures  Roblox & macOS Techniques for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Samsung Galaxy S23 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-turn-filter-keys-on-or-off-on-windows/"><u>4 Ways to Turn Filter Keys On or Off on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-gameplay-9-tricks-to-end-wwe-2k23-freezes-in-windows/"><u>Accelerate Gameplay: 9 Tricks to End WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-collage-artistry-with-precision/"><u>Mastering Collage Artistry with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-a-quake-environment-via-terminals/"><u>Accessing a Quake Environment via Terminals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-copy-file-and-folder-paths-in-windows-11/"><u>6 Ways to Copy File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-on-windows-1011s-audio-upgrade/"><u>A Comprehensive Tutorial on Windows 10/11'S Audio Upgrade</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/how-to-remove-audio-from-video-online/"><u>How to Remove Audio From Video Online?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-free-up-local-drive-space-without-deleting-files-on-windows-11/"><u>8 Ways to Free Up Local Drive Space Without Deleting Files on Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-capturing-stills-in-time-a-guide-to-slow-motion-on-ig/"><u>In 2024, Capturing Stills in Time  A Guide to Slow Motion on IG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-beginning-navigating-3-reset-routes/"><u>A Fresh Windows Beginning: Navigating 3 Reset Routes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-day-windows-productivity-software-that-works-wonders/"><u>Ace Your Day: Windows Productivity Software That Works Wonders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719310221725-tame-frozen-windows-handbraked-beast/"><u>Tame Frozen Windows-Handbraked Beast!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719324521716-elevating-your-windows-screenshot-game-with-these-fixes/"><u>Elevating Your Windows Screenshot Game with These Fixes.</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-masterful-mobile-and-desktop-sound-alteration-tools/"><u>[Updated] Masterful Mobile & Desktop Sound Alteration Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306648168-fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now!</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-from-concepts-to-shares-your-guide-to-metaverse-meme-creation/"><u>[New] From Concepts to Shares  Your Guide to Metaverse Meme Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessible-beginnings-on-windows-for-first-timers/"><u>Accessible Beginnings on Windows for First-Timers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-bluetooth-remotes-and-controllers-for-easy-shooting/"><u>[Updated] Bluetooth Remotes and Controllers for Easy Shooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-mfc71udll-missing-issue-in-windows/"><u>Addressing Mfc71u.dll Missing Issue in Windows</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-the-ultimate-iphone-converter-top-6-free-applications-to-use/"><u>2024 Approved  The Ultimate iPhone Converter  Top 6 Free Applications to Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-efficient-workflow-multi-screen-settings-in-win11/"><u>Achieve Efficient Workflow: Multi-Screen Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719362383486-enhance-full-screen-screenshot-success-in-windows-snip-and-sketch-tool/"><u>Enhance Full-Screen Screenshot Success in Windows' Snip & Sketch Tool.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-vanishing-hardware-problems-in-dm/"><u>Address Vanishing Hardware Problems In DM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-low-quality-steam-streams/"><u>Addressing Low Quality Steam Streams</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-create-impact-with-intro-excellence-best-free-services-reviewed-for-2024/"><u>[Updated] Create Impact with Intro Excellence  Best Free Services Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-available-device-driver-issue-in-os-update/"><u>Addressing 'No Available' Device Driver Issue in OS Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-how-to-open-excel-files-in-notepad-correctly/"><u>Addressing: How to Open Excel Files in Notepad Correctly</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-8-plus-to-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 8 Plus To Android devices? | Dr.fone</u></a></li>
<li><a href="https://ai-video.techidaily.com/updated-2024-approved-best-10-free-video-translators-to-mitigate-translation-risks/"><u>updated 2024 Approved Best 10 Free Video Translators to Mitigate Translation Risks</u></a></li>
<li><a href="https://extra-information.techidaily.com/audiovisual-anthems-blending-music-into-instagram-videos/"><u>Audiovisual Anthems  Blending Music Into Instagram Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accurate-atmospheres-expert-picks-of-windows-11s-weather-apps/"><u>Accurate Atmospheres: Expert Picks of Windows 11'S Weather Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-system-file-checker-a-quick-tutorial/"><u>Activating System File Checker: A Quick Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719258042287-reclaiming-chrome-in-w11-easy-to-follow-remediation-tips/"><u>Reclaiming Chrome in W11 - Easy-to-Follow Remediation Tips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/implementing-look-up-tables-luts-to-elevate-design-work/"><u>Implementing Look-Up Tables (LUTs) to Elevate Design Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-responsive-sound-adjustment-settings/"><u>Addressing Non-Responsive Sound Adjustment Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-insights-on-staying-with-older-windows-editions/"><u>7 Insights on Staying with Older Windows Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719348732386-cant-capture-sound-in-obs-on-win-11-solve-it-now/"><u>Can't Capture Sound in OBS on Win 11? Solve It Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inaccessible-values-in-windows-applications/"><u>Addressing Inaccessible Values in Windows Applications</u></a></li>
</ul></div>
