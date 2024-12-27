---
title: Curing Empty Folder Misconraneuement in Windows 11 with #0X80070091
date: 2024-12-22T18:19:30.795Z
updated: 2024-12-27T23:15:26.778Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Curing Empty Folder Misconraneuement in Windows 11 with #0X80070091
excerpt: This Article Describes Curing Empty Folder Misconraneuement in Windows 11 with #0X80070091
keywords: Fixing #0X80070091 Error,Resolve Empty Folder Issue,Windows 11 File Misalignment,Cure #0X80070091 Windows Error,Remedy Null Files in WS11,Fix Empty Folder in Win11,Resolve #0X80070091 Miscellaneous
thumbnail: https://thmb.techidaily.com/eb4342f3aa6f1684d24f86318d0e954640b0c7c9aedf2dd2ccacfdac421d6e8a.jpg
---

## Curing Empty Folder Misconraneuement in Windows 11 with #0X80070091

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-essential-steps-for-adobe-presenter-recordings/"><u>[New] In 2024, Essential Steps for Adobe Presenter Recordings</u></a></li>
<li><a href="https://win-tricks.techidaily.com/1-top-substitutes-to-pandora-enhanced-options-for-online-radio-listeners/"><u>1. Top Substitutes to Pandora: Enhanced Options for Online Radio Listeners</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-unveiled-content-tweeting-high-definition-for-everyone/"><u>2024 Approved Unveiled Content Tweeting High Definition for Everyone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-legacy-lift-updating-old-games-location-in-windows-11/"><u>Digital Legacy Lift: Updating Old Games' Location in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-forcefully-remove-printers-from-windows-11-pro/"><u>How to Forcefully Remove Printers From Windows 11 Pro</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/invest-in-ig-success-the-top-6-secure-money-methods-for-2024/"><u>Invest in IG Success The Top 6 Secure Money Methods for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/mastering-the-r6-mistake-resolving-problem-code-3-0x00010am0b/"><u>Mastering the R6 Mistake - Resolving Problem Code 3-0X00010am0b</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-no-permission-error-in-windows-oses/"><u>Overcoming the No Permission Error in Windows OSes</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-samsung-galaxy-s24plus-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Samsung Galaxy S24+.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-wsl-register-failure-with-error-code-0x80370102/"><u>Resolving WSL Register Failure with Error Code 0X80370102</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-geforce-overlays-easy-steps-on-windows-pc/"><u>Stop GeForce Overlays: Easy Steps on Windows PC</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-big-reason-to-choose-apples-iphone-16-pro-instead-of-the-max-model-this-year-exclusive-findings/"><u>The Big Reason to Choose Apple's iPhone 16 Pro Instead of the Max Model This Year - Exclusive Findings</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-chatgpts-potential-with-easy-api-tutorials/"><u>Unlocking ChatGPT's Potential with Easy API Tutorials</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/wie-man-den-speicherplatz-effektiv-verwaltet-um-backups-unter-windows-10-zu-optimieren/"><u>Wie Man Den Speicherplatz Effektiv Verwaltet, Um Backups Unter Windows 10 Zu Optimieren</u></a></li>
</ul></div>

