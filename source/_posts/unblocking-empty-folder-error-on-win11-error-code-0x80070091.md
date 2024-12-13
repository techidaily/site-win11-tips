---
title: Unblocking Empty Folder Error on Win11 (Error Code 0X80070091)
date: 2024-12-11T22:57:44.676Z
updated: 2024-12-13T01:34:21.043Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unblocking Empty Folder Error on Win11 (Error Code 0X80070091)
excerpt: This Article Describes Unblocking Empty Folder Error on Win11 (Error Code 0X80070091)
keywords: Win11 Folder Unlock Guide,Fix Code 0X80070091 Error,Empty Folder Windows Troubleshoot,Resolve WinError 0X80070091,Disable File System Errors,Overcome Win11 Empty Space Error,Unlock Windows Files Error Fix
thumbnail: https://thmb.techidaily.com/5835b7f75acb6f437f70d9b6865adddf58cf9307d1c89bac2789b98350d1bacd.jpg
---

## Unblocking Empty Folder Error on Win11 (Error Code 0X80070091)

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-data.techidaily.com/utting-costs-without-compromising-on-youtube-intros-quality/"><u>[New] Cutting Costs without Compromising on YouTube Intros Quality</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-craft-your-story-pace-with-instagrams-temp-control-feature/"><u>[Updated] Craft Your Story Pace with Instagram's Temp Control Feature</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-elevating-your-youtube-content-selecting-professional-gear-for-2024/"><u>[Updated] Elevating Your YouTube Content Selecting Professional Gear for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-key-sound-editing-solutions-for-video-bloggers-for-2024/"><u>[Updated] Key Sound Editing Solutions for Video Bloggers for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-navigating-new-horizons-the-essence-of-vr-travel/"><u>[Updated] Navigating New Horizons The Essence of VR Travel</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/achieve-maximum-direct3d-potential-with-gpu-acceleration-fixes/"><u>Achieve Maximum Direct3D Potential with GPU Acceleration Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customization-strategies-altering-functional-keys-in-windows-1011/"><u>Customization Strategies: Altering Functional Keys in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-grammarly-after-its-not-working-in-windows-10/"><u>Enabling Grammarly After It's Not Working in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-using-extra-monitors-without-graphic-chipset/"><u>Guide to Using Extra Monitors Without Graphic Chipset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-the-perplexing-app-could-not-be-started-error-code-0xc000003e-in-windows-11/"><u>How to Tackle the Perplexing App Could Not Be Started: Error Code 0XC000003E in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/path-pioneering-in-win11-unveiling-the-best-practices-6-keyways/"><u>Path Pioneering in Win11: Unveiling the Best Practices (6 Keyways)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/roblox-connectivity-woes-an-outage-across-the-board-or-user-specific-bugs/"><u>Roblox Connectivity Woes: An Outage Across The Board, or User-Specific Bugs?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-geforce-now-error-xc0f1103f-in-windows-11/"><u>Steps to Resolve GeForce Now Error Xc0f1103f in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-media-player-sources-not-found-on-windows-machines-solved/"><u>Troubleshooting Media Player Sources Not Found on Windows Machines [Solved]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-virtualization-potential-with-hyper-v-on-windows-11/"><u>Unleash Virtualization Potential with Hyper-V on Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unstuck-iphone-auto-focus-essential-fixes-and-advice/"><u>Unstuck iPhone Auto-Focus: Essential Fixes & Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-storage-management-for-your-apps/"><u>Windows Storage Management for Your Apps</u></a></li>
</ul></div>

