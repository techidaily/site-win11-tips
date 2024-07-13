---
title: Strategies for Clearing Admin Not Allowed Message in OS
date: 2024-07-12T17:41:41.332Z
updated: 2024-07-13T17:41:41.332Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Clearing Admin Not Allowed Message in OS
excerpt: This Article Describes Strategies for Clearing Admin Not Allowed Message in OS
keywords: Admin Access Fix Guide,Bypass Admin Error,No Admin Error Removal,Override Admin Denied,Clear Admin Restriction,Eliminate Admin Block,Remove Admin Message
thumbnail: https://thmb.techidaily.com/04b5de1b8632b8069ff9f587e17e0dbf1c9f260b061902685aa6f6d586835f1d.jpg
---

## Strategies for Clearing Admin Not Allowed Message in OS

 Some users have posted on troubleshooting forums about a “Page not available” error that occurs when they open Windows Security. The “Page not available” error message says, “Your IT Administrator has limited access to some areas of this app.” That error message appears within Windows Security, and users can’t access that app’s antivirus settings because of it.

 This error message suggests another administrative user has applied restrictions to Windows Security. However, it often arises on standalone PCs that aren’t connected to an organization network. This is how you can fix the “Your IT administrator has limited access” error.

## 1\. Change Your User Account to an Admin Account

 You shouldn’t usually need admin rights to access Windows Security. However, make sure you’re signed in to an admin account to ensure you have full system permissions. If you’re utilizing a standard account, change it to an administrator one. You can do that with one of the methods outlined in this guide to [changing user account type in Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) .

![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)

## 2\. Uninstall Third-Party Security Software

 Have you installed a third-party antivirus app on your PC? If so, that security software could be by conflicting with Microsoft Defender and causing the “Page not available” error. Try uninstalling the third-party antivirus utility you’ve installed with a method in our guide to [removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . Or utilize a dedicated removal tool for your antivirus app if there’s one available.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option-3.jpg)

## 3\. Remove Any Work or School Accounts

 Have you connected your PC with any school or work organization account? If so, such an account could be restricting access to Windows Security settings. Try disconnecting your PC from the school or work in Settings as follows:

1. Bring up Settings and click that app’s**Accounts** tab (or category).
2. Scroll down to select the**Access work or school navigation** option.
3. Click a connected work or school account to expand it.  
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)
4. Press the**Disconnect** button and select**Yes** .

## 4\. Disable the Turn Off Microsoft Defender Antivirus Policy

 Some Windows Pro and Enterprise users have confirmed they’ve fixed the “Page not available” error by disabling a**Turn off Microsoft Defender Antivirus** policy. So, check that policy setting even if you can’t recall changing it yourself. This is how you can check and disable the**Turn Off Microsoft Defender Antivirus** Group Policy setting in Windows Pro and Enterprise:

1. To access the file search box, hold the Windows logo key and press S.
2. Type**gpedit.msc** inside the file search box.
3. Double-click**gpedit.msc** to [open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window.
4. Next, double-click**Computer Configuration** and**Administrative Templates** within Group Policy Editor’s sidebar.
5. Expand the**Windows Components** folder in the sidebar.

1. Click**Microsoft Defender Antivirus** to select that policy.  
![Microsoft Defender Antivirus settings in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-antivirus-settings.jpg)
2. Then double-click**Turn off Microsoft Defender Antivirus** .
3. Click**Disabled** if the**Turn off Microsoft Defender Antivirus** policy is enabled.  
![The Turn off Microsoft Defender Antivirus window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-turn-off-microsoft-defender-antivirus-window.jpg)
4. Select the policy’s**Apply** and**OK** options.
5. Double-click**Allow antimalware to startup with normal priority** and select to disable that policy as outlined in the previous two steps as well.  
![The Allow antimalware service to startup with normal priority window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-antimalware-service-window.jpg)
6. Next, click**Client Interface** within the Microsoft Defender Antivirus settings.  
![Allow antimalware service to startup with normal priority](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/client-interface-setting.jpg)
7. Double-click the**Enable headless UI mode** policy to view it.  
![The Client Interface settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-headless-ui-mode.jpg)
8. Select**Disabled** \>**Apply** \>**OK** in the Enable headless UI mode policy window.

## 5\. Run a PowerShell Command

 Running a set-MpPreference PowerShell command is a widely confirmed potential resolution for the “Page not available” error. The confirmed command disables Microsoft Defender’s UI lockdown mode. You can run that PowerShell command like this:

1. Activate the Windows search utility.
2. Input a**PowerShell** search phrase to find that command-line app.
3. Open PowerShell with elevated permissions by right-clicking the search result for that command-line app and selecting**Run as administrator** .
4. Input this**MpPreference** command and press**Return** :  
`set-MpPreference -UILockdown`  
![The set-Mppreference PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-set-mppreference-command.jpg)
5. Exit PowerShell and open Windows Security again to see if the error persists.

## 6\. Repair/Reset Windows Security

 Windows Security is a UWP app for which you can select**Repair** and**Reset** Settings options that can resolve various issues. Those options are there to help users fix apps that aren’t working right. So, try selecting Windows Security’s**Repair** and**Reset** options to see if they make any difference.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button.jpg)

 Our article [about resetting Windows apps](https://www.makeuseof.com/windows-reset-app/) tells you how to access the**Reset** button. The**Repair** button is just above the**Reset** option. It’s recommended to select**Repair** first since that doesn’t affect app data.

## 7\. Modify the Registry via Command Prompt

 Users also confirm that running a series of Command Prompt commands that modify the registry can resolve the “Page not available” issue. As those are reg delete commands, we recommend you back up the registry before applying this potential fix. Then try running the registry commands for erasing policies like this:

 Open the utility for finding files and apps with the**Windows** logo +**S** key combination.

1. Find the Command Prompt by typing in a**CMD** search phrase.
2. Click the Command Prompt app with the mouse’s right button to select a**Run as administrator** context menu option.
3. Execute the following commands separately, pressing**Enter** after inputting each one:  
`reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\Software \Microsoft\WindowsSelfHost" /f  

reg delete "HKLM\Software\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware  

reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f  

reg delete "HKCU\Software\Policies" /f  

reg delete "HKLM\Software\Microsoft\Policies" /f`
4. Input**exit** in the Command Prompt to close the app.  
![The reg delete command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reg-delete.jpg)
5. Open the Start menu, select**Power** , and press the**Restart** button.

## 8\. Perform a System Restore

 If the “Page not available” error remains after applying other potential solutions, try performing a system restore. That might work if you can select a restore point predating the “Page not available” error on your PC. Rolling Windows back to an earlier time could undo any system changes that caused the issue to arise.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-resotre-window.jpg)

 Our guide on [creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) provides instructions for rolling back Windows with System Restore. Choose the oldest restore point you can. However, remember that you’ll probably need to reinstall some software packages installed after the restore point’s date.

## Start Utilizing Windows Security Again

 The potential solutions covered in this guide address many of the primary causes for that error occurring. So, they’ll probably get the “Page not available” error sorted on most users’ Windows 11/10 PCs. Fixing the “Page not available” error will enable you to access all the settings in Windows Security again.

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
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-realme-note-50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-printing-at-your-fingertips-slow-printer-remedies-in-windows/"><u>Fast Printing at Your Fingertips: Slow Printer Remedies in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-masterminds-of-memorable-discord-symbols-revealed/"><u>2024 Approved  Masterminds of Memorable Discord Symbols Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-notepad-blockade-uncover-the-7-pathways-to-access-it-again/"><u>Windows Notepad Blockade: Uncover the 7 Pathways to Access It Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-hard-drives-performance-defrag-guide-for-win11/"><u>Enhance Hard Drives Performance: Defrag Guide for Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-meizu-21-pro-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Meizu 21 Pro to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ideal-choices-for-comprehensive-movement-recording/"><u>In 2024, Ideal Choices for Comprehensive Movement Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-package-blockage-a-window-solution-for-error-fixes/"><u>Disabling Package Blockage: A Window Solution for Error Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-update-anomaly-error-0xca00a009/"><u>Eliminating Windows Update Anomaly: Error 0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-core-data-an-analysis-of-the-registry/"><u>Unlocking Windows 11'S Core Data: An Analysis of the Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-flawless-display-with-win11-settings/"><u>Achieve Flawless Display with Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-efficient-wsl-2-on-windows/"><u>Winning Strategies for Efficient WSL 2 on Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-behind-the-camera-glory-spotlight-on-top-10-female-youtubers-for-2024/"><u>[Updated] Behind-the-Camera Glory  Spotlight on Top 10 Female YouTubers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-to-the-upcoming-sudo-integration/"><u>Adapting to the Upcoming Sudo Integration</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-on-iphone-11-by-drfone-ios/"><u>How to Bypass iCloud Lock on iPhone 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streamline-animated-subscribe-buttons-in-filmora-for-youtube-success/"><u>In 2024, Streamline Animated Subscribe Buttons in Filmora for YouTube Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-yourphoneexe-phone-link-in-windows-1110-should-you-disable-it/"><u>What Is YourPhone.exe (Phone Link) in Windows 11/10? Should You Disable It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-editorial-techniques-select-from-the-top-8-video-trimming-titles/"><u>Winning Editorial Techniques: Select From The Top 8 Video Trimming Titles</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-comedic-counterpoints-funny-song-flips/"><u>[Updated] Comedic Counterpoints  Funny Song Flips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/driving-impact-with-data-informed-spotify-ads/"><u>Driving Impact with Data-Informed Spotify Ads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-systems-analyzers-for-windows/"><u>Essential Systems Analyzers for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/forge-ahead-with-stronger-windows-security-top-four-password-keepers/"><u>Forge Ahead with Stronger Windows Security: Top Four Password Keepers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-server-slips-for-smooth-ms-store-in-windows-os/"><u>Conquering Server Slips for Smooth MS Store in Windows OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-top-15-ae-title-tricks-for-dynamic-content-headers-for-2024/"><u>[Updated] Top 15 AE Title Tricks for Dynamic Content Headers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-upgrading-isnt-feeling-right-for-many-to-windows-11/"><u>Why Upgrading Isn't Feeling Right for Many to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-visual-elements-from-search-bar/"><u>How to Clear Visual Elements From Search Bar</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-engaging-consumers-effectively-through-snapbiz-insights/"><u>[Updated] 2024 Approved  Engaging Consumers Effectively Through SnapBiz Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/find-out-if-your-pc-is-a-win11-ready-machine/"><u>Find Out if Your PC Is a Win11-Ready Machine</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-dot-file-by-digital-signature-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to sign .dot file by digital signature</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-discover-the-best-instagram-video-editors-for-mobile-devices/"><u>[New] In 2024, Discover the Best Instagram Video Editors for Mobile Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-sound-glitch-error-0xc00d36b4-on-win11/"><u>Bypassing Sound Glitch: Error 0XC00D36B4 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-out-onedrive-from-your-pcs-file-explorer-screenshot/"><u>How to Cut Out OneDrive From Your PC's File Explorer Screenshot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-game-bar-errors-on-underpowered-systems/"><u>Addressing Game Bar Errors on Underpowered Systems</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/discovering-the-speedy-scaling-channels-among-youtube-titans-for-2024/"><u>Discovering the Speedy Scaling Channels Among YouTube Titans for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-the-newest-viral-phenomena-on-tiktok/"><u>[Updated] In 2024, The Newest Viral Phenomena on TikTok</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-perfecting-hp-screen-capture-top-4-methods-unveiled/"><u>[New] 2024 Approved  Perfecting HP Screen Capture  Top 4 Methods Unveiled</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-excel-file-couldnt-open-in-protected-view-stellar-by-stellar-guide/"><u>How to Fix Excel File Couldnt Open in Protected View | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-winservicesexe-operations/"><u>Demystifying WinServices.exe Operations</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-a-lost-apple-iphone-8-plus-for-free-drfone-by-drfone-virtual-ios/"><u>How to Track a Lost Apple iPhone 8 Plus for Free? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-stepping-up-advanced-techniques-for-w11-gamers/"><u>[New] In 2024, Stepping Up  Advanced Techniques for W11 Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-onedrive-invalid-tag-error-in-windows-file-system/"><u>Eliminating the OneDrive Invalid Tag Error in Windows File System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-slow-computer-wake-up-the-complete-window-11-startup-guide/"><u>Conquering Slow Computer Wake-Up: The Complete Window 11 Startup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/checking-audio-device-integrity-on-windows/"><u>Checking Audio Device Integrity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-flickering-win1011-screens/"><u>Efficient Fixes for Flickering WIN10/11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-pathways-to-launching-windows-fix/"><u>Essential Pathways to Launching Windows FIX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-disabled-windows-application/"><u>How to Enable Disabled Windows Application</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-finding-repository-of-explosive-roar-samples/"><u>Updated 2024 Approved Finding Repository of Explosive Roar Samples</u></a></li>
</ul></div>
