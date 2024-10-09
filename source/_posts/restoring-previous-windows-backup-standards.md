---
title: Restoring Previous Windows Backup Standards
date: 2024-10-01T19:04:58.777Z
updated: 2024-10-09T05:45:33.937Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Previous Windows Backup Standards
excerpt: This Article Describes Restoring Previous Windows Backup Standards
keywords: Windows Restore,Data Recovery,Save Old Settings,Backup Protocols,System Reinstate,Standard Revival,Backup Standards Fix
thumbnail: https://thmb.techidaily.com/c3feb7e5b167df5f057578cdbf724989b5f25148052cd8949359804b1109e7ca.png
---

## Restoring Previous Windows Backup Standards

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-unlocking-perfect-presentation-youtubes-video-ratio-insights/"><u>[New] 2024 Approved Unlocking Perfect Presentation YouTube's Video Ratio Insights</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-soft-sonata-reducing-volume-in-os/"><u>[Updated] Soft Sonata Reducing Volume in OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/6-proven-ways-to-unlock-sony-xperia-1-v-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Sony Xperia 1 V Phone When You Forget the Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-overwatch-2-device-rendering-issue/"><u>How to Address Overwatch 2 Device Rendering Issue</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-hit-list-top-10-songs-in-one-place/"><u>In 2024, Hit List Top 10 Songs in One Place</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/microsoft-mouse-driver-update-procedure-for-windows-users/"><u>Microsoft Mouse Driver Update Procedure for Windows Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/mp4-mp3-mpe-movavi/"><u>MP4를 MP3로 구독하기 MPE 서버 제공 – Movavi 편집기</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-fast-track-to-film-fame-easy-movie-creation-secrets-for-2024/"><u>New Fast Track to Film Fame Easy Movie Creation Secrets for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-dll-loss-mfc71u-on-windows-systems/"><u>Overcoming DLL Loss: Mfc71u on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-deactivated-temperature-control-on-winos/"><u>Overhauling Deactivated Temperature Control on WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-avoid-keyboard-triggers-without-intent/"><u>Techniques to Avoid Keyboard Triggers without Intent</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-for-smooth-launching-of-genshin-impact/"><u>Troubleshooting Tips for Smooth Launching of Genshin Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-eliminate-xbox-game-pass-error-0x00000001/"><u>Troubleshooting Windows 11: Eliminate Xbox Game Pass Error 0X00000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-accessing-and-deleting-your-usage-logs/"><u>Windows 11: Accessing & Deleting Your Usage Logs</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    