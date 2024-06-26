---
title: Navigating the Process of Win Backup Defaulting
date: 2024-06-25T16:25:58.478Z
updated: 2024-06-26T16:25:58.478Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Process of Win Backup Defaulting
excerpt: This Article Describes Navigating the Process of Win Backup Defaulting
keywords: Backup Restoration,Data Recovery,Default Status,Process Win Backup,Overcoming Failure,Win Backup Procedures,Resuming Lost Files
thumbnail: https://thmb.techidaily.com/2a9cc8bf4d555df620abafcb570dcc2752e8e2040a84b647ff438519a4be3866.jpg
---

## Navigating the Process of Win Backup Defaulting

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

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

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/the-basics-of-windows-canary-and-its-benefits/"><u>The Basics of Windows Canary and Its Benefits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719336383556-mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-admin-level-command-prompt-in-windows-11-pro/"><u>Initiating Admin-Level Command Prompt in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-overcome-ownership-challenges-with-org-managed-configurations-in-windows-11/"><u>Tips to Overcome Ownership Challenges with Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conducting-an-intuitive-in-place-windows-11-transition/"><u>Conducting an Intuitive, In-Place Windows 11 Transition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-window-updates-blocked-by-error-2e/"><u>Fix Window Updates Blocked by Error 2E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-future-windows-laptops-top-picks/"><u>The Ultimate Guide to Future Windows Laptops: Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-oculus-errors-on-ws11wc10-systems/"><u>Troubleshooting Oculus Errors on WS11/WC10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-persistent-enter-network-credentials-message-on-windows/"><u>How to Fix a Persistent Enter Network Credentials Message on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-muted-slack-notifications-on-windows-11/"><u>Addressing Muted Slack Notifications on Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-audiovisual-cooperation-the-duet-phenomenon/"><u>[Updated] 2024 Approved  Audiovisual Cooperation  The Duet Phenomenon</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-innovative-techniques-to-enhance-your-obs-broadcasts-android-for-2024/"><u>[Updated] Innovative Techniques to Enhance Your OBS Broadcasts (Android) for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-converting-zip-to-subrip-srt-format-a-step-by-step-guide/"><u>In 2024, Converting ZIP to SubRip (SRT) Format  A Step-by-Step Guide</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-convert-facebook-videos-to-mp3-top-online-tools/"><u>Updated Convert Facebook Videos to MP3 Top Online Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-oppo-find-x6-pro-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Oppo Find X6 Pro Device</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-troubleshoot-snapchat-camera-zoomed-in-issue-4-tips-for-2024/"><u>New Troubleshoot Snapchat Camera Zoomed in Issue 4 Tips for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-contacts-after-honor-play-7t-has-been-deleted-by-fonelab-android-recover-contacts/"><u>Recover your contacts after Honor Play 7T has been deleted.</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-maintaining-confidentiality-with-professional-zoom-recordings/"><u>[New] Maintaining Confidentiality with Professional Zoom Recordings</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-what-wikipedia-cant-tell-you-about-the-10-best-batman-cartoons/"><u>New In 2024, What Wikipedia Cant Tell You About the 10 Best Batman Cartoons</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Motorola Moto E13? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>