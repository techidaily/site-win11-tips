---
title: Recovering Original Windows Backup Configs
date: 2024-11-23T16:50:17.490Z
updated: 2024-11-27T17:19:31.579Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Recovering Original Windows Backup Configs
excerpt: This Article Describes Recovering Original Windows Backup Configs
keywords: WinBackupRestore,Windows XP Recovery,SystemConfigWindowsXP,XP BackupRecoverySol,RestoreWinx64Backups,XPProfessionalRestore,ReinstateWindowsXP
thumbnail: https://thmb.techidaily.com/2f486f4dd87aa179d36ac9cfba84a9e655bb2170ba42ee253c3df8a8c92937c0.jpg
---

## Recovering Original Windows Backup Configs

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-from-idea-to-rss-producing-a-podcast-feed-for-2024/"><u>[New] From Idea to RSS Producing a Podcast Feed for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-how-to-use-zoom-in-your-daily-gmail-routine-for-2024/"><u>[New] How to Use Zoom in Your Daily Gmail Routine for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-step-by-step-saving-tweet-vids-on-androids/"><u>[Updated] 2024 Approved Step-By-Step Saving Tweet Vids on Androids</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comparing-cost-and-style-the-motorola-one-challenges-the-iphone-experience/"><u>Comparing Cost and Style: The Motorola One Challenges the iPhone Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-the-faulty-escape-functionality-in-your-windows-environment/"><u>Fix the Faulty Escape Functionality in Your Windows Environment</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/global-market-access-for-singapore-smbs-through-amazons-new-e-commerce-collaboration-as-covered-by-zdnet/"><u>Global Market Access for Singapore SMBs Through Amazon's New E-Commerce Collaboration, as Covered by ZDNet</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-poco-x5-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Poco X5 to Outlook | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-m34-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy M34 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-scrutinizing-the-premier-collection-of-affordable-lut-files/"><u>In 2024, Scrutinizing the Premier Collection of Affordable LUT Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-network-related-error-on-ges-interface/"><u>Resolving Network-Related Error on GE's Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-perfect-nvidia-drivers-for-your-needs/"><u>Selecting Perfect Nvidia Drivers for Your Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmatched-efficiency-the-best-of-wins-optimization-aids/"><u>Unmatched Efficiency: The Best of Win's Optimization Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-art-of-windows-11s-in-place-revamping/"><u>Unveiling the Art of Windows 11'S In-Place Revamping</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    