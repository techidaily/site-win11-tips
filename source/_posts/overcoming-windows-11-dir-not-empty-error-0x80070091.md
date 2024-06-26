---
title: Overcoming Windows 11 Dir Not Empty Error (0X80070091)
date: 2024-06-25T16:56:31.441Z
updated: 2024-06-26T16:56:31.441Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows 11 Dir Not Empty Error (0X80070091)
excerpt: This Article Describes Overcoming Windows 11 Dir Not Empty Error (0X80070091)
keywords: Win11 Error Solve,Clearing Directory Error,Unblocked File Fix,Windows 11 Fix Error,Erase Dir Not Empty Remedy,ZeroXError Correction,Direct Issue Resolution
thumbnail: https://thmb.techidaily.com/ea600fcdcc2d5739582790f8ecc24848128b14c3ba69f4885da8723ba49d2002.jpg
---

## Overcoming Windows 11 Dir Not Empty Error (0X80070091)

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
<li><a href="https://win11-tips.techidaily.com/maximize-functionality-with-these-8-bubbleui-upgrades/"><u>Maximize Functionality with These 8 BubbleUI Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-value-with-smart-acquisition-of-windows-10-product-keys/"><u>Maximizing Value with Smart Acquisition of Windows 10 Product Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-loading-device-drivers-on-windows-11/"><u>Fixing Non-Loading Device Drivers on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-desktop-layout-app-sizes-in-windows-11/"><u>Mastering Desktop Layout: App Sizes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-disabling-discords-auto-checkup-at-startup/"><u>Strategies for Disabling Discord's Auto-Checkup at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-complex-comic-formats-for-win11-users/"><u>Breaking Down Complex Comic Formats for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-sudden-screen-loss-during-win-games/"><u>Techniques to Overcome Sudden Screen Loss During WIN Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chocolatey-vs-wm-top-tools-for-windows-software-downloads/"><u>Chocolatey vs WM: Top Tools for Windows Software Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-screen-saver-wait-time/"><u>Optimize Windows Screen Saver Wait Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-geforce-experience-setup-failure-windows-11-edition/"><u>Resolving GeForce Experience Setup Failure, Windows 11 Edition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-enhancing-webcam-gaming-experience-and-quality/"><u>In 2024, Enhancing WebCam Gaming Experience & Quality</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-complete-activity-inspection-guide/"><u>In 2024, Complete Activity Inspection Guide</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-getting-to-know-more-about-the-video-editing-interface-of-wondershare-filmora/"><u>2024 Approved Getting To Know More About the Video Editing Interface of Wondershare Filmora</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/auditory-anchors-keeping-streamed-music-intact-for-2024/"><u>Auditory Anchors  Keeping Streamed Music Intact for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-soft-onset-showcasing/"><u>[New] Soft Onset Showcasing</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-extract-audio-from-instagram-easy-methods-revealed/"><u>New In 2024, Extract Audio From Instagram Easy Methods Revealed</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-oppo-find-n3-flip-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Oppo Find N3 Flip.</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-free-top-rated-tools-to-create-engaging-fb-video-content/"><u>2024 Approved  Free, Top-Rated Tools to Create Engaging FB Video Content</u></a></li>
</ul></div>
