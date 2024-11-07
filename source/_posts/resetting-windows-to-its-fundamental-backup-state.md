---
title: Resetting Windows to Its Fundamental Backup State
date: 2024-11-01T13:37:06.745Z
updated: 2024-11-07T13:02:39.920Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Windows to Its Fundamental Backup State
excerpt: This Article Describes Resetting Windows to Its Fundamental Backup State
keywords: Reset Window Backup,System Restore,Initial Backup Set,Clearing OS Cache,Fresh OS Start,Windows Factory Reset,Base State Recovery
thumbnail: https://thmb.techidaily.com/219754861571baaffef2dbde1c4e47ea4bf551dd4082ac6c30e6e25f75285938.jpg
---

## Resetting Windows to Its Fundamental Backup State

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036496/19272" target="_top" id="2036496">
  <img src="//a.impactradius-go.com/display-ad/19272-2036496" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036496/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123726/7443" target="_top" id="2123726">
  <img src="//a.impactradius-go.com/display-ad/7443-2123726" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123726/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-helps.techidaily.com/new-unveiling-the-best-free-video-player-vlc-versus-mpc/"><u>[New] Unveiling the Best Free Video Player VLC versus MPC</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-generating-auto-subscribe-urls-for-youtube-channels/"><u>[Updated] In 2024, Generating Auto Subscribe URLs for YouTube Channels</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-ultimate-guide-to-cost-effective-media-providers-online/"><u>[Updated] The Ultimate Guide to Cost-Effective Media Providers Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dont-get-duped-unveiling-fake-windows-software-tricks/"><u>Don't Get Duped! Unveiling Fake Windows Software Tricks</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-on-reviving-computers-with-no-power-issues-diy-solutions/"><u>Expert Tips on Reviving Computers with No Power Issues - DIY Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-restoring-defaults-for-win11-terminal/"><u>Guide to Restoring Defaults for Win11 Terminal</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-poco-c51-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Poco C51 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-meizu-21-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oneplus-nord-ce-3-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track OnePlus Nord CE 3 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-update-problem-zeroerror-80073712/"><u>Overcoming Update Problem: ZeroError 80073712</u></a></li>
<li><a href="https://facebook.techidaily.com/social-savings-and-serenity-the-9-reasons-to-be-online-for-life/"><u>Social Savings & Serenity: The 9 Reasons to Be Online for Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-your-windows-mouse-quick-fixes/"><u>Stabilizing Your Windows Mouse - Quick Fixes</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-gaming-device-razers-hot-swappable-keyboard/"><u>The Ultimate Gaming Device: Razer's Hot-Swappable Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-11s-unusual-zero-error/"><u>Troubleshoot Windows 11'S Unusual Zero-Error</u></a></li>
</ul></div>

