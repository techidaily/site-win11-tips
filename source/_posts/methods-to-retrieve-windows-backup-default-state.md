---
title: Methods to Retrieve Windows Backup Default State
date: 2024-10-27T18:22:25.633Z
updated: 2024-11-01T18:12:16.453Z
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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144287/7443" target="_top" id="2144287">
  <img src="//a.impactradius-go.com/display-ad/7443-2144287" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144287/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://coinrule.sjv.io/c/5597632/1958378/18409" target="_top" id="1958378">
  <img src="//a.impactradius-go.com/display-ad/18409-1958378" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1958378/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximize-impact-with-insightful-youtube-stats-analysis/"><u>[Updated] Maximize Impact with Insightful YouTube Stats Analysis</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-framemorph-editor/"><u>2024 Approved FrameMorph Editor</u></a></li>
<li><a href="https://games-able.techidaily.com/effortless-ssd-swap-for-improved-gaming-experience/"><u>Effortless SSD Swap for Improved Gaming Experience</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/experience-a-budget-friendly-fitness-with-the-fitbit-versa-in-depth-review/"><u>Experience a Budget-Friendly Fitness with the Fitbit Versa – In-Depth Review</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-copy-contacts-from-apple-iphone-13-pro-max-to-sim-drfone-by-drfone-transfer-from-ios/"><u>How to Copy Contacts from Apple iPhone 13 Pro Max to SIM? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-failing-display-connection-on-pcs/"><u>How to Rectify Failing Display Connection on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-windows-non-responsive-performance-chart/"><u>Improving Windows' Non-Responsive Performance Chart</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-poco-c51-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Poco C51 Phone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-oppo-reno-10-proplus-5g-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Oppo Reno 10 Pro+ 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-file-thumbnails-in-windows-11-how-to-repair/"><u>Invisible File Thumbnails in Windows 11 – How to Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-installed-devices-message-on-pcs/"><u>Overcoming 'No Installed Devices' Message on PCs</u></a></li>
<li><a href="https://win-solutions.techidaily.com/quick-fixes-for-roblox-crashing-problems-top-six-hacks-for-pc-users/"><u>Quick Fixes for Roblox Crashing Problems: Top Six Hacks for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-obstacles-to-unique-printer-id/"><u>Removing Obstacles to Unique Printer ID</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-restoring-windows-google-nearby-share/"><u>Step-By-Step Guide to Restoring Windows Google Nearby Share</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-try-connections-fiasco-with-this-guide-for-pcs/"><u>Tackle 'Try Connections' Fiasco with This Guide for PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-best-of-ice-artistry-2022-edition/"><u>The Best of Ice Artistry 2022 Edition</u></a></li>
</ul></div>

