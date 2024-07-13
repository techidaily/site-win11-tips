---
title: How to Fix Windows Security’s “Unexpected Error” In Windows 11 & 11
date: 2024-07-12T16:59:28.566Z
updated: 2024-07-13T16:59:28.566Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Windows Security’s “Unexpected Error” In Windows 11 & 11
excerpt: This Article Describes How to Fix Windows Security’s “Unexpected Error” In Windows 11 & 11
keywords: Windows 11 Error Fix,Fixing Windows Security Error,Resolve Windows Error Quickly,WinErrorSolution Guide,Stop UX Errors in Windows,Windows XP11 Security Fixes,Eliminate Windows Unexpected Error
thumbnail: https://thmb.techidaily.com/815fea7976911214190dec2e4ce8ef31c5b56fc35aca9555d7d0112a6571e067.jpg
---

## How to Fix Windows Security’s “Unexpected Error” In Windows 11 & 11

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our [guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on [utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
4. Type**DisableAntiSpyware** in the DWORD’s text box.
5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
7. Select**OK** to confirm the value for the DWORD.

## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about [resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the [Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
9. Select**Done** to finish.
10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this [Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out [our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
4. Click**Not Configured** if that policy is set to**Enabled** .  
![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
5. Select the policy’s**Apply** and**OK** options.

## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to [performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the [Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://games-able.techidaily.com/no-subscribing-to-higher-costs-at-ea-play/"><u>No Subscribing to Higher Costs at EA Play</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ultimate-roguelike-rankings-the-best-10-games/"><u>[Updated] Ultimate Roguelike Rankings  The Best 10 Games</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-vivo-v27-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Vivo V27</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-a-toolbar-update-check-feature-into-windows-11plus11-interface/"><u>Integrating a Toolbar Update Check Feature Into Windows 11+11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-functional-copy-paste-in-chromeedgefirefox-windows/"><u>Fixing Non-Functional Copy-Paste in Chrome/Edge/Firefox Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/office-integration-a-concise-guide-to-windows-1011/"><u>Office Integration: A Concise Guide to Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-audio-cd-production-from-mp3-files-an-efficient-guide-to-using-imgburn-in-windows/"><u>Mastering Audio CD Production From MP3 Files: An Efficient Guide to Using ImgBurn in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-blocked-app-alert-on-windows-systems/"><u>Removing Blocked App Alert on Windows Systems</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-discovering-where-youtube-video-management-happens/"><u>[New] 2024 Approved  Discovering Where YouTube Video Management Happens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-windows-app-speed-revitalize-their-web-connection/"><u>Propel Window's App Speed: Revitalize Their Web Connection</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/1716464268823-masterful-mythos-youtubes-finest-magic-tricks/"><u>Masterful Mythos  YouTube's Finest Magic Tricks!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mute-unnecessary-system-updates-on-windows-11/"><u>Mute Unnecessary System Updates on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-the-new-windows-taskbar-design/"><u>Maximizing the New Windows Taskbar Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-dxgi-error-messages-windows-1011/"><u>Navigating Through DXGI Error Messages (Windows 10/11)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-selective-alert-tunes-prime-audio-spots/"><u>[New] Selective Alert Tunes  Prime Audio Spots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-edge-always-active-on-windows-11-guide/"><u>Is Edge Always Active on Windows 11? Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-a-non-functional-windows-download-folder/"><u>Methods to Reactivate a Non-Functional Windows Download Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-proxy-configurations-on-windows-11/"><u>Mastering the Art of Proxy Configurations on Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-ultimate-guide-on-converting-word-to-srt/"><u>New Ultimate Guide on Converting Word to SRT</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-easycapture-prox-diagnosis/"><u>In 2024, EasyCapture ProX Diagnosis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-correcting-rdp-fails-in-modern-windows-os/"><u>Preventing and Correcting RDP Fails in Modern Windows OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-keep-an-eye-out-for-insta-follower-fleece/"><u>[Updated] 2024 Approved  Keep an Eye Out for Insta Follower Fleece</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-snapping-in-depth-guide-to-powertoy-window-layouts/"><u>Master the Art of Snapping: In-Depth Guide to PowerToy Window Layouts</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-branding-success-on-fb-through-immersive-cover-videos/"><u>[New] Branding Success on FB Through Immersive Cover Videos</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-8-best-music-production-software-for-mac-and-windows/"><u>In 2024, 8 Best Music Production Software for Mac and Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-minimizing-cpu-load-on-computers/"><u>Mastery of Minimizing CPU Load on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-faulty-resource-monitors-on-windows-11/"><u>Resetting Techniques for Faulty Resource Monitors on Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-video-formatting-made-easy-change-shape-size-and-aspect-ratio-for-2024/"><u>New Video Formatting Made Easy Change Shape, Size, and Aspect Ratio for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-updater-error-0xca00a009/"><u>Repairing Windows Updater Error #0xCA00A009</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-the-ultimate-guide-to-drying-out-distorted-sounds-three-effective-methods/"><u>Updated The Ultimate Guide to Drying Out Distorted Sounds Three Effective Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-sandbox-no-hypervisor-was-found-0xc0351000-error/"><u>How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-custom-window-bg-in-winterm/"><u>Implementing Custom Window Bg in WinTerm</u></a></li>
<li><a href="https://extra-tips.techidaily.com/hdr-tech-review-auroras-place-among-leaders/"><u>HDR Tech Review  Aurora's Place Among Leaders</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-picshots-wizardry-in-photo-collage-crafting/"><u>In 2024, Picshot's Wizardry in Photo Collage Crafting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructingdarkmodeonwindowsnotepad/"><u>InstructingDarkModeOnWindowsNotepad</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/smooth-out-flares-on-window-11/"><u>Smooth Out Flares on Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-fixing-nvidia-cp-error-in-ws1110/"><u>Methodical Approach: Fixing Nvidia CP Error in WS11/10</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-visions-instructions-for-posting-songs-on-youtube-for-2024/"><u>Vocal Visions  Instructions for Posting Songs on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-bandwidth-visualization-for-users/"><u>Real-Time Bandwidth Visualization for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-task-managers-dominance-over-desktop-applications/"><u>Mastering Task Manager's Dominance Over Desktop Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070522-resolving-client-permissions-issue-on-windows-systems/"><u>Overcoming 0X80070522: Resolving Client Permissions Issue on Windows Systems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-vivo-v30-pro-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Vivo V30 Pro to New Phone | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-honor-magic-vs-2-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Honor Magic Vs 2 | Dr.fone</u></a></li>
</ul></div>
