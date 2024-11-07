---
title: Methods for Refreshing Default Windows Backups
date: 2024-11-02T22:26:03.058Z
updated: 2024-11-06T19:57:09.724Z
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
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129741/7443" target="_top" id="2129741">
  <img src="//a.impactradius-go.com/display-ad/7443-2129741" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129741/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2027181/19272" target="_top" id="2027181">
  <img src="//a.impactradius-go.com/display-ad/19272-2027181" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027181/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/n-2024-avoiding-files-enjoying-animated-gifs-youtube-video-mastery/"><u>[New] In 2024, Avoiding Files, Enjoying Animated GIFs YouTube Video Mastery</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-scrutinizing-if-opinions-on-items-are-paid-for/"><u>[New] In 2024, Scrutinizing if Opinions on Items Are Paid For</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-enhance-video-production-7-best-free-sounds-for-editors/"><u>[Updated] In 2024, Enhance Video Production - 7 Best Free Sounds for Editors</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-your-speech-any-sound-discover-the-best-vocal-transformation-tools-on-android/"><u>[Updated] Your Speech, Any Sound Discover the Best Vocal Transformation Tools on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-win32keygen-virus-steps-for-secure-removal/"><u>Deciphering Win32/Keygen Virus: Steps for Secure Removal</u></a></li>
<li><a href="https://video-capture.techidaily.com/easy-steps-how-to-record-on-vimeo-for-2024/"><u>Easy Steps How to Record on Vimeo for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/keeping-track-of-itunes-audio-visual-files/"><u>Keeping Track of iTunes Audio-Visual Files</u></a></li>
<li><a href="https://driver-install.techidaily.com/no-more-headaches-with-hp-laserjet-1020-drivers/"><u>No More Headaches with HP LaserJet 1020 Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-failing-displays-a-guide-for-windows-users/"><u>Remedying Failing Displays: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-malwarebytes-access-on-windows-10-11-after-failure/"><u>Restoring Malwarebytes Access on Windows 10, 11 After Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-unlocking-the-potential-of-windows-connections/"><u>The Insider's Guide: Unlocking the Potential of Windows Connections</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-reviews-and-specs/"><u>Tom's Tech Reviews & Specs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transcribing-spoken-language-fast-whisper-desktop-skills/"><u>Transcribing Spoken Language Fast: Whisper Desktop Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-task-managers-misleading-cpu-data/"><u>Troubleshooting Windows Task Manager's Misleading CPU Data</u></a></li>
<li><a href="https://extra-hints.techidaily.com/win11s-top-5-no-cost-screen-recorders-updated-guide/"><u>Win11's Top 5 No-Cost Screen Recorders - Updated Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    