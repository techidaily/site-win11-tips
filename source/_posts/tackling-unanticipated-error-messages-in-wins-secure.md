---
title: Tackling Unanticipated Error Messages in WINS Secure
date: 2024-07-12T17:45:50.673Z
updated: 2024-07-13T17:45:50.673Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Unanticipated Error Messages in WINS Secure
excerpt: This Article Describes Tackling Unanticipated Error Messages in WINS Secure
keywords: WinErrorSolving,SecurityWinFixes,ErrorMessagingWin,UnforeseenWinErrors,WINSecureCodingTips,SecureWinTroubleshoot,FixUnanticipatedWindows
thumbnail: https://thmb.techidaily.com/2453bc5c0249af0de921ee166f14d8e128b375913b07ba9cca730be764e6c410.jpg
---

## Tackling Unanticipated Error Messages in WINS Secure

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
<li><a href="https://pokemon-go-android.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-realme-12-proplus-5g-to-mac-drfone-by-drfone-android/"><u>How to Mirror Realme 12 Pro+ 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/comprehensive-guide-advanced-avs-sound-editing-tools-and-comparative-analysis-for-2024/"><u>Comprehensive Guide Advanced AVS Sound Editing Tools and Comparative Analysis for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-12-mini-with-a-mask-on-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 12 mini with a Mask On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-read-only-mode-a-guide-for-windows-users/"><u>Disabling Read-Only Mode: A Guide for Windows Users</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-vivo-y27s-by-drfone-android/"><u>Three Ways to Sim Unlock Vivo Y27s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-efficiency-5-best-apps-to-create-animated-clock-screen-savers-on-pcs/"><u>Accelerate Efficiency: 5 Best Apps to Create Animated Clock Screen Savers on PCs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-premium-4k-screen-capturing-solutions/"><u>[Updated] 2024 Approved  Premium 4K Screen Capturing Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-to-follow-pathway-accessing-wordpad-on-pcs/"><u>Easy-to-Follow Pathway: Accessing WordPad on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wisdom-three-routes-to-your-games-data/"><u>Windows Wisdom: Three Routes to Your Games' Data</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-top-10-affordable-mobile-video-services/"><u>[New] Navigating Top 10 Affordable Mobile Video Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-broken-enter-button-on-pc/"><u>Fixing Broken Enter Button on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-non-windows-tools-that-outperform-snipping-tool/"><u>Essential Non-Windows Tools That Outperform Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/engage-your-phones-dialer-with-ease-windows-11/"><u>Engage Your Phone's Dialer with Ease, Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-realme-11-pro-by-fonelab-android-recover-video/"><u>How to restore wiped videos on Realme 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-effective-steps-for-lifelong-disabling-of-windows-defender/"><u>5 Effective Steps for Lifelong Disabling of Windows Defender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-your-user-experience-customizing-windows-11-defaults/"><u>Enhancing Your User Experience: Customizing Windows 11 Defaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-how-to-engage-telnet-securely/"><u>Windows 11: How to Engage Telnet Securely</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-optimal-room-decorations-for-livestreams/"><u>[New] Optimal Room Decorations for Livestreams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-mail-troubleshooting-unraveling-the-zero-x-eight-oh-three-one-f-mystery/"><u>Windows Mail Troubleshooting: Unraveling the Zero X Eight Oh Three One F Mystery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-rectifying-obs-studio-server-connectivity-hiccups/"><u>Essential Tips for Rectifying OBS Studio Server Connectivity Hiccups</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mastering-polska-accelerated-learning/"><u>Mastering Polska: Accelerated Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-eliminating-no-servers-found-in-apex-legends-(156-chars/"><u>Troubleshooting: Eliminating 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12-pro-4g-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Xiaomi Redmi Note 12 Pro 4G for Free? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-check-your-windows-computers-model-name/"><u>6 Ways to Check Your Windows Computer's Model Name</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-sound-convergence-10-premier-blenders-for-podcasters/"><u>[Updated] Sound Convergence  10 Premier Blenders for Podcasters</u></a></li>
<li><a href="https://video-capture.techidaily.com/shooter-synergy-crafting-a-list-of-top-7-game-battles-for-2024/"><u>Shooter Synergy  Crafting a List of Top 7 Game Battles for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/unraveling-the-mysteries-of-quantum-hdr-for-2024/"><u>Unraveling the Mysteries of Quantum HDR for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-ultimate-guide-to-blurring-videos-on-iphone-and-android/"><u>New The Ultimate Guide to Blurring Videos on iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-how-to-reinstall-java-correctly/"><u>Unlocking Windows: How to Reinstall Java Correctly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-ms-teams-error-80080300-fixes-for-w11-users/"><u>Breaking Down MS Teams Error 80080300: Fixes for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-gestures-for-efficient-browsing-in-edge-win-11-edition/"><u>Enabling Gestures for Efficient Browsing in Edge, Win 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-speed-status-in-windows-desktop-area/"><u>Effortless Speed Status in Windows Desktop Area</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-total-control-guide-powerdirector-user-manual/"><u>[Updated] Total Control Guide  PowerDirector User Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-study-experience-dive-into-asus-vivobook-s-15/"><u>Elevate Your Study Experience: Dive Into ASUS Vivobook S 15</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-filmora-torrent-risks-how-to-download-it-safely-and-for-free-for-2024/"><u>Updated Filmora Torrent Risks How to Download It Safely and for Free for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-complete-guide-to-reversed-videos-on-instagram/"><u>In 2024, The Complete Guide to Reversed Videos on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-edge-linger-handling-windows-11-background-tasks/"><u>Does Edge Linger? Handling Windows 11 Background Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-a-convenient-upgrade-notification-toolbar-in-windows-1111/"><u>Adding a Convenient Upgrade Notification Toolbar in Windows 11/11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-ultimate-guide-to-unlocking-your-apple-iphone-xs-max-on-metropcs-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Unlocking Your Apple iPhone XS Max on MetroPCS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/calculating-filesize-and-capacity-the-ultimate-powershell-exercise/"><u>Calculating Filesize and Capacity: The Ultimate PowerShell Exercise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-user-dissatisfaction-with-microsofts-latest-update/"><u>Decoding User Dissatisfaction with Microsoft's Latest Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-wi-fi-potential-in-windows-11-with-these-tips/"><u>Unlock Full Wi-Fi Potential in Windows 11 with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ram-management-for-effective-cross-platform-communication/"><u>Efficient RAM Management for Effective Cross-Platform Communication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-fury-not-frustration-fixing-lag-in-sw-battlefront-2/"><u>Unleash Fury, Not Frustration: Fixing Lag in SW Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-password-entry-for-instantaneous-win-11-connections/"><u>Bypassing Password Entry for Instantaneous Win 11 Connections</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-the-compreenas-for-effective-screenshares-on-zoom/"><u>[Updated] 2024 Approved  The Compreenas for Effective Screenshares on Zoom</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-for-beginners-leveraging-facebook-data-with-ease/"><u>[New] For Beginners  Leveraging Facebook Data with Ease</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/powerpoint-presentations-enhancing-clarity-with-voiceovers/"><u>PowerPoint Presentations  Enhancing Clarity with Voiceovers</u></a></li>
</ul></div>
