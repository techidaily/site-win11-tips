---
title: Methods for Refreshing Default Windows Backups
date: 2024-11-14T19:19:40.776Z
updated: 2024-11-17T16:46:43.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods for Refreshing Default Windows Backups
excerpt: This Article Describes Methods for Refreshing Default Windows Backups
keywords: WinBackupRefresh,WindowsRestoreOptions,UpdateSystemImage,DefaultWindowsSaveMethod,SystemRebootTechniques,OlderWindowsRecovery,BackupUpdateProcedure
thumbnail: https://thmb.techidaily.com/a23ef58f3369824904efee9f97817b15b093c9dc4ea1ce81d7226560e11dda64.jpg
---

## Methods for Refreshing Default Windows Backups

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068440/7443" target="_top" id="2068440">
  <img src="//a.impactradius-go.com/display-ad/7443-2068440" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068440/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-crafting-perfect-squares-imovie-guide-for-instagram-videos/"><u>[New] Crafting Perfect Squares IMovie Guide for Instagram Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-find-peace-and-power-the-10-greatest-yoga-channels-online-for-2024/"><u>[Updated] Find Peace & Power The 10 Greatest Yoga Channels Online for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-get-facebook-links-downloaded-top-8-tools-of-the-year-2023/"><u>[Updated] In 2024, Get Facebook Links Downloaded Top 8 Tools of the Year 2023</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-multitask-media-magic-employing-netflix-picture-in-picture/"><u>2024 Approved Multitask Media Magic Employing Netflix Picture-in-Picture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-into-browsing-after-your-windows-launch/"><u>Breaking Into Browsing After Your Windows Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-into-windows-11-appsfolder-a-step-by-step-walkthrough/"><u>Breaking Into Windows 11 AppsFolder: A Step-by-Step Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-into-windows-11-overcoming-slowdowns/"><u>Breathe Life Into Windows 11: Overcoming Slowdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-into-your-locked-windows-screen-saver/"><u>Breathe Life Into Your Locked Windows Screen Saver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-error-code-2e-restore-windows-update/"><u>Bypass Error Code 2E, Restore Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-error-blockers-fixing-amd-installation-woes/"><u>Bypassing Error Blockers: Fixing AMD Installation Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11s-local-user-security-qanda/"><u>Bypassing Windows 11'S Local User Security Q&A</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-download-or-install-icloud-on-windows-try-these-fixes/"><u>Can’t Download or Install iCloud on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-wisely-critical-considerations-in-procuring-a-laptop/"><u>Choosing Wisely: Critical Considerations in Procuring a Laptop</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-reno-11-5g-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Reno 11 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-cannot-reach-windows-installer-service-steps-and-solutions/"><u>Fixing 'Cannot Reach Windows Installer Service': Steps and Solutions</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-iphone-xr-without-passcode-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock iPhone XR without Passcode</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/iphone-xeasy-simple-guide-to-screen-capture-for-2024/"><u>IPhone Xeasy Simple Guide to Screen Capture for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-smart-8frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Smart 8FRP Lock</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-to-correctly-address-windows-10s-troubling-error-code-0x80n0541-for-seamless-updates/"><u>Step-by-Step Tutorial to Correctly Address Windows 10'S Troubling Error Code 0X80n0541 for Seamless Updates</u></a></li>
</ul></div>

