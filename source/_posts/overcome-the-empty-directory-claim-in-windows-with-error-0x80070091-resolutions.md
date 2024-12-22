---
title: Overcome the Empty Directory Claim in Windows with Error 0X80070091 Resolutions
date: 2024-12-14T17:51:20.279Z
updated: 2024-12-22T02:24:18.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcome the Empty Directory Claim in Windows with Error 0X80070091 Resolutions
excerpt: This Article Describes Overcome the Empty Directory Claim in Windows with Error 0X80070091 Resolutions
keywords: Windows Directory Error,Overcoming 0X80070091,Empty Folder Fix,Direct Access Issue,WinError Resolution,File Not Found Error,Path Corruption Remedy
thumbnail: https://thmb.techidaily.com/b8ee7f668d81642e85ade38e34abffd540ab85d6f715874a1c53fa95c5d6dc9a.png
---

## Overcome the Empty Directory Claim in Windows with Error 0X80070091 Resolutions

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-lab.techidaily.com/nveiling-effective-techniques-for-youtube-video-thumbnail-designs-for-2024/"><u>[New] Unveiling Effective Techniques for YouTube Video Thumbnail Designs for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-maximize-meeting-success-top-recording-tools/"><u>[Updated] Maximize Meeting Success Top Recording Tools</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-an-exclusive-review-of-lgs-innovative-4k-screen-tech/"><u>2024 Approved An Exclusive Review of LG's Innovative 4K Screen Tech</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/50plus-most-popular-english-spanish-cognates-and-false-cognates/"><u>50+ Most Popular English-Spanish Cognates and False Cognates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-the-path-easy-fixes-for-clipchamp-on-windows-11/"><u>Clear the Path: Easy Fixes for ClipChamp on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-experience-with-thx-sound/"><u>Enhancing Windows Experience with THX Sound</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>How to get the dragon scale and evolution-enabled pokemon On Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-remedy-correcting-disk-read-issues/"><u>Immediate Remedy: Correcting Disk Read Issues</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-realme-narzo-60-pro-5g-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-guide-to-disassembling-beat-elements-in-digital-music-files/"><u>In 2024, Guide to Disassembling Beat Elements in Digital Music Files</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-the-audio-files-new-world-how-to-convert-srt-effortlessly/"><u>In 2024, The Audio Files' New World How to Convert SRT Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/picking-your-future-operating-system-evaluate-homes-vs-pro-win11-features/"><u>Picking Your Future Operating System: Evaluate Homes Vs. Pro Win11 Features</u></a></li>
<li><a href="https://games-able.techidaily.com/playstations-top-10-best-buys-for-the-holiday/"><u>PlayStation's Top 10 Best Buys for the Holiday</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-play-integrating-ps1-games-into-win-via-duckstation/"><u>Seamless Play: Integrating PS1 Games Into WIN via Duckstation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-disregard-fake-virus-alert-from-chrome/"><u>Steps to Disregard Fake Virus Alert From Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-event-log-operations/"><u>Streamlining Windows Event Log Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-route-to-new-location-for-onedrive-folder-in-microsofts-os/"><u>The Route to New Location for OneDrive Folder in Microsoft's OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-ignoring-misleading-anti-virus-alerts-in-chrome/"><u>Tutorial: Ignoring Misleading Anti-Virus Alerts in Chrome</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/winx-dvd-ripper-complete-edition-updated-history-and-new-capabilities-revealed/"><u>WinX DVD Ripper Complete Edition Updated History & New Capabilities Revealed</u></a></li>
</ul></div>

