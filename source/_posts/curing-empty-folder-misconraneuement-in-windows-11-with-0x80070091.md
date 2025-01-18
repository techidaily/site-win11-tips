---
title: Curing Empty Folder Misconraneuement in Windows 11 with #0X80070091
date: 2025-01-15T16:47:35.023Z
updated: 2025-01-18T18:36:44.926Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-ultimate-smartphone-selection-for-superior-video-recording/"><u>[New] 2024 Approved Ultimate Smartphone Selection for Superior Video Recording</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-master-youtube-management-a-detailed-plan-for-watch-later-and-playlists/"><u>[Updated] Master YouTube Management A Detailed Plan for Watch Later and Playlists</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-premium-windows-10-screen-recording-software/"><u>[Updated] Premium Windows 10 Screen Recording Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2023windows-movie-maker11/"><u>2023年最好的免费Windows Movie Maker替代品：探索11种功能丰富的视频编辑工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp2mp3-movavi/"><u>優化MP2為MP3的無限制線上移動 - 運用Movavi 解決方案</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/call-transcriber-iphone-2024-speaker-device/"><u>Call Transcriber IPhone 2024 Speaker Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effektivt-bearbetar-audiofilmer-ivan-med-movavi-din-gamla-ljudbittarrat-ratt-utanfor-tiden/"><u>Effektivt Bearbetar Audiofilmer - Ivån Med Movavi: Din Gamla Ljudbittarrat Rätt Utanför Tiden</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-manage-both-ethernet-and-wi-fi-networks-simultaneously-in-windows/"><u>How to Manage Both Ethernet & Wi-Fi Networks Simultaneously in Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-harmony-and-code-the-elite-circle-s-digital-compositional-geniuses/"><u>In 2024, Harmony and Code The Elite Circle S Digital Compositional Geniuses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mov-mxf-movavi-0/"><u>MOV 파일을 MXF로 이식: MOVavi에서 비용 0%의 온라인 제공</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mpg-conversion-of-ram-a-complimentary-online-service-with-moveai-tech-solutions/"><u>MPG Conversion of RAM: A Complimentary Online Service with MoveAI Tech Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-bmp-to-png-conversion-by-movavi-get-it-free/"><u>Online BMP to PNG Conversion by Movavi: Get It FREE!</u></a></li>
<li><a href="https://win-help.techidaily.com/protegez-vos-fichiers-avec-confiance-le-remplacement-superieur-de-diskgenius-pour-la-protection-des-donnees/"><u>Protégez Vos Fichiers Avec Confiance: Le Remplacement Superieur De DiskGenius Pour La Protection Des Données</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unlock-the-secrets-to-social-media-success-with-igtv-hashtag-techniques-for-2024/"><u>Unlock the Secrets to Social Media Success with IGTV Hashtag Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aiff-m4amp3/"><u>무료 AIFF 매니페스트를 M4A/MP3로 바꾸기 - 이식센터에서 원통</u></a></li>
</ul></div>

