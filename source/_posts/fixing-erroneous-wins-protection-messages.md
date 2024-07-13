---
title: Fixing Erroneous WINS Protection Messages
date: 2024-07-12T17:14:57.444Z
updated: 2024-07-13T17:14:57.444Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Erroneous WINS Protection Messages
excerpt: This Article Describes Fixing Erroneous WINS Protection Messages
keywords: Error-Free DNS,Winsock Repair Guide,Resolve WINS Issues,Fix WINS Mistakes,Correct DNS Misconfig,Stop Erroneous WINS,Secure DNS Messages
thumbnail: https://thmb.techidaily.com/37cbd79bb1dc4f01076609d4f2040fc4f61e96fa43faa2585a2bbac8dade3639.jpg
---

## Fixing Erroneous WINS Protection Messages

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
<li><a href="https://win11-tips.techidaily.com/tackling-missing-mcuicnt-file-execution-issue-on-windows/"><u>Tackling Missing McUICnt File Execution Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-system-advanced-techniques-to-revise-the-windows-registry-in-command-prompt/"><u>Unlock Your System: Advanced Techniques to Revise the Windows Registry in Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-silent-camera-activation-in-windows-11/"><u>Bypassing Silent Camera Activation in Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-mastering-discord-message-pinning-essentials/"><u>In 2024, Mastering Discord  Message Pinning Essentials</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-pro-gamers-equipment-showcase-series/"><u>[New] Pro Gamer's Equipment Showcase Series</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-exception-interrupted-glitches-in-windows-systems/"><u>Combat 'Exception Interrupted' Glitches in Windows Systems</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/reel-your-best-footage-from-instagram-with-these-aids/"><u>Reel Your Best Footage From Instagram With These Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snip-and-sketch-vs-prtsc-which-screen-capture-wins/"><u>Snip & Sketch Vs. PrtSc: Which Screen Capture Wins?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-this-article-introduce-tips-on-how-to-stream-any-video-format-to-google-chromecast/"><u>New This Article Introduce Tips on How to Stream Any Video Format to Google Chromecast</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-oppo-a78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conducting-an-intuitive-in-place-windows-11-transition/"><u>Conducting an Intuitive, In-Place Windows 11 Transition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-the-ideal-placement-for-onedrive-on-windows-11/"><u>Crafting the Ideal Placement for OneDrive on Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-a-novices-vision-on-vectors-categories-explored-and-apps/"><u>[Updated] In 2024, A Novice's Vision on Vectors  Categories Explored and Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719233145490-win-plus-print-problem-heres-your-quick-windows-fix-guide/"><u>Win + Print Problem? Here's Your Quick Windows Fix Guide.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719283991472-update-windows-11-ensure-your-system-is-up-to-date-for-any-built-in-improvements-and-fixes-regarding-display-settings/"><u>Update Windows 11: Ensure Your System Is up to Date for Any Built-In Improvements and Fixes Regarding Display Settings.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-administrator-security-configs/"><u>Steps to Tackle Windows Administrator Security Configs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-perfecting-phone-screenshots-with-snapchat/"><u>[New] 2024 Approved  Perfecting Phone Screenshots with Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-cleaning-up-the-icon-cache/"><u>Best Practices for Cleaning Up the Icon Cache</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-key-steps-in-manipulating-song-pace-in-spotify-app/"><u>In 2024, Key Steps in Manipulating Song Pace in Spotify App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-notepads-display-from-light-to-dark-theme-win-11/"><u>Transitioning Notepad's Display From Light to Dark Theme (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-successfully-locating-policy-management-tools/"><u>Steps to Successfully Locating Policy Management Tools</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-capture-cumulative-chronicles/"><u>In 2024, Capture Cumulative Chronicles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-memory-detection-problems/"><u>Understanding and Fixing Memory Detection Problems</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-top-10-free-video-editing-software-options-for-windows-for-2024/"><u>New Top 10 Free Video Editing Software Options for Windows for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-create-slow-motion-videos-using-final-cut-pro-with-ease/"><u>Updated In 2024, Create Slow Motion Videos Using Final Cut Pro with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speak-write-and-transform-an-intuitive-guide-to-text-generation-with-windows-whisper/"><u>Speak, Write and Transform: An Intuitive Guide to Text Generation with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-5-steps-to-reset-windows-defender-status/"><u>Troubleshooting Guide: 5 Steps to Reset Windows Defender Status</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-notable-creators-superior-insta-highlight-craftsmen-for-2024/"><u>[Updated] Notable Creators  Superior Insta Highlight Craftsmen for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-stable-internet-windows-edition-guide/"><u>Troubleshooting Stable Internet: Windows Edition Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-superior-webcams-revolutionizing-podcast-recording/"><u>2024 Approved  Superior Webcams Revolutionizing Podcast Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-undetermined-value-messages-on-windows/"><u>Solutions for 'Undetermined' Value Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-clearing-windowss-prior-passcode/"><u>Winning Back Access: Clearing “Windows's Prior Passcode”</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-your-computers-print-command-conundrum-with-effective-tips/"><u>Solving Your Computer's Print Command Conundrum with Effective Tips.</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-unlocking-desktop-recording-the-ezvide-approach/"><u>[Updated] In 2024, Unlocking Desktop Recording - The EZvide Approach</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-cutting-edge-top-8-free-online-video-tools-for-2024/"><u>[Updated] Cutting Edge  Top 8 Free Online Video Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-removing-signature-rejection-on-pcs/"><u>Strategies for Removing Signature Rejection on PCs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/top-10-economical-pc-monitoring-and-capture-tools/"><u>Top 10 Economical PC Monitoring and Capture Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-shutdown-playbook-avoiding-windows-11-activities/"><u>The Shutdown Playbook: Avoiding Windows 11 Activities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-should-you-care-about-runtime-brokers-on-your-system/"><u>Why Should You Care About Runtime Brokers on Your System?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-assessing-the-value-of-4-second-rapid-subscriptions-on-youtube-for-2024/"><u>[Updated] Assessing the Value of 4-Second Rapid Subscriptions on Youtube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-tasks-with-these-8-best-rated-window-pomodoros/"><u>Streamline Your Tasks With These 8 Best-Rated Window Pomodoros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-savvy-tips-restarting-windows-11-apps/"><u>Tech Savvy Tips: Restarting Windows 11 Apps</u></a></li>
</ul></div>
