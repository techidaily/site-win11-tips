---
title: "Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes"
date: 2024-07-12T17:06:40.178Z
updated: 2024-07-13T17:06:40.178Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes"
excerpt: "This Article Describes Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes"
keywords: X80070091 Fix,Not Empty Assertion Disable,Software Debugging Guide,Practical X86 Debug Fixes,Memory Error Resolution,X86 Architecture Troubleshooting,System Compliance Adjustment
thumbnail: https://thmb.techidaily.com/3ad0b37de8405ddff0a5f39b812ec8d893ee35987fd8e7537df266174c877eec.jpg
---

## Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://win11-tips.techidaily.com/organizing-files-optimizing-drives-defrag-for-win11-users/"><u>Organizing Files, Optimizing Drives: Defrag for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumph-over-windows-11-theme-lockdown-a-registry-approach/"><u>Triumph Over Windows 11 Theme Lockdown: A Registry Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-steps-to-resolve-onedrive-server-crashes/"><u>Swift Steps to Resolve OneDrive Server Crashes</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-sony-xperia-5-v-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Sony Xperia 5 V FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regenerating-system-icons-in-windows-os/"><u>Regenerating System Icons in Windows OS</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-quick-and-easy-twitter-to-snapchat-video-sharing-tips-for-2024/"><u>[New] Quick & Easy Twitter to Snapchat Video Sharing Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-the-user-experience-in-win11-settings/"><u>Redesigning the User Experience in Win11 Settings</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-the-definitive-steps-for-online-streaming-audio-archiving/"><u>2024 Approved  The Definitive Steps for Online Streaming Audio Archiving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-security-top-5-fixes-for-access-denied-errors/"><u>Mastering Windows 11 Security: Top 5 Fixes for Access Denied Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-against-unexpected-scroll-behavior-in-os/"><u>Safeguard Against Unexpected Scroll Behavior in OS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-ultimate-list-best-mac-videos-grabber-software/"><u>[New] In 2024, Ultimate List  Best Mac Videos Grabber Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-pick-for-pen-notes-7-ultimate-windows-apps/"><u>Prime Pick for Pen Notes: 7 Ultimate Windows Apps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/picsart-shield-invisible-smile-vanished-gaze/"><u>Picsart Shield  Invisible Smile, Vanished Gaze</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-transforming-viewing-habits-with-fb-live-on-roku-for-2024/"><u>[Updated] Transforming Viewing Habits with FB Live on Roku for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-store-faults-rectify-error-0x80072f17/"><u>Mending Windows Store Faults: Rectify Error 0X80072f17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-usb-drive-problems-for-efficient-data-handling/"><u>Solving USB Drive Problems for Efficient Data Handling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-activate-folder-restrictions-in-windows/"><u>Step-by-Step Guide to Activate Folder Restrictions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-a-stuck-recycle-bin-on-microsofts-latest-os/"><u>Reviving a Stuck Recycle Bin on Microsoft's Latest OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/money-making-tactics-from-the-w11-windowware/"><u>Money-Making Tactics From the W11 Windowware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-modify-mouses-double-click-speed/"><u>Ultimate Guide to Modify Mouse's Double-Click Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-tips-for-photoshopping-on-windows-11/"><u>Troubleshooting Tips for Photoshopping on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-solutions-at-fingertips-customizing-shortcuts-for-win-11-repairs/"><u>Speedy Solutions at Fingertips: Customizing Shortcuts for Win 11 Repairs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-issues-a-comprehensible-guide-for-windows-11-users/"><u>Navigating Network Issues: A Comprehensible Guide for Windows 11 Users</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-stolen-apple-iphone-xs-in-different-conditionsin-by-drfone-ios/"><u>How To Unlock Stolen Apple iPhone XS In Different Conditionsin</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/techniques-to-increase-instagram-content-playback-speed/"><u>Techniques to Increase Instagram Content Playback Speed</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-top-android-apps-to-smooth-out-shaky-videos-for-2024/"><u>Updated Top Android Apps to Smooth Out Shaky Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-high-dpi-screen-resolution-problems-on-pcs/"><u>Tackling High DPI Screen Resolution Problems on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-instructions-downloading-and-installing-msixbundle-packages/"><u>Step-by-Step Instructions: Downloading & Installing MSixbundle Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fix-geforce-experience-on-windows-pcs/"><u>Quick Guide to Fix GeForce Experience on Windows PCs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/mov-file-handling-best-practices-on-windows-10-systems/"><u>.mov File Handling  Best Practices on Windows 10 Systems</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-tactics-for-increasing-campaign-efficiency-with-smart-hashtag-usage-on-fb/"><u>[New] In 2024, Tactics for Increasing Campaign Efficiency with Smart Hashtag Usage on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-0xc0000001-on-windows-os/"><u>Steps to Solve 0XC0000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scrutinizing-the-utility-of-windows-11-interface-components/"><u>Scrutinizing the Utility of Windows 11 Interface Components</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-clearing-up-sound-simplified-techniques-for-debouncing-ambient-noise-in-music-production/"><u>In 2024, Clearing Up Sound Simplified Techniques for Debouncing Ambient Noise in Music Production</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-surface-laptop-go-3-gains-processor-yet-fails-to-shine/"><u>Microsoft's Surface Laptop Go 3 Gains Processor, Yet Fails to Shine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/monetization-approaches-for-microsoft-and-windows-11/"><u>Monetization Approaches for Microsoft & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-pc-essential-free-tools-for-win11-users/"><u>Mastering Your PC: Essential Free Tools for Win11 Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On OnePlus Nord CE 3 5G? | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Oppo Find X7 | Dr.fone</u></a></li>
</ul></div>
