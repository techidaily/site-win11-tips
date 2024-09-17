---
title: Methods to Retrieve Windows Backup Default State
date: 2024-09-12T03:59:35.130Z
updated: 2024-09-17T08:43:16.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Retrieve Windows Backup Default State
excerpt: This Article Describes Methods to Retrieve Windows Backup Default State
keywords: Windows Recovery Options,Default Backup Restore,WinBackup Command Line,System Image Backups,WBExec Utility Use,CMD for Backup Retrieval,Windows System Image Scripts
thumbnail: https://thmb.techidaily.com/e937e68a5b9ec03875dd350ca4501bcb740dbcf769458408d36b67b305252021.jpg
---

## Methods to Retrieve Windows Backup Default State

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vimeo-videos.techidaily.com/new-stepwise-guide-integrating-subtitles-into-your-vimeo-content-for-2024/"><u>[New] Stepwise Guide Integrating Subtitles Into Your Vimeo Content for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-enhancing-virtual-meetings-how-to-use-discord-for-screenshots-for-2024/"><u>[Updated] Enhancing Virtual Meetings How to Use Discord for Screenshots for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/android-to-apple-how-to-transfer-photos-from-tecno-spark-20-proplus-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Android to Apple How To Transfer Photos From Tecno Spark 20 Pro+ to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/aspiring-pro-modders-expert-advice-and-essential-strategies/"><u>Aspiring Pro Modders: Expert Advice and Essential Strategies</u></a></li>
<li><a href="https://extra-tips.techidaily.com/exploring-2023s-standout-professional-360cameras/"><u>Exploring 2023'S Standout Professional 360°Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-frozen-windows-command-prompt-window/"><u>Fixing Frozen Windows Command Prompt Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-your-files-security-with-powertoys-locksmith/"><u>Perfecting Your Files' Security with PowerToys Locksmith</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-to-launch-and-setup-win-11s-sandbox/"><u>Stepwise Guide to Launch and Setup Win 11'S Sandbox</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-vivo-t2x-5g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Vivo T2x 5G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-silent-screencast-feedback-in-powerpoint/"><u>Troubleshooting Silent Screencast Feedback in PowerPoint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-onoff-touch-typing-on-your-windows-device/"><u>Turning On/Off Touch Typing on Your Windows Device</u></a></li>
</ul></div>

