---
title: Can’t Delete Temporary Files in Windows? Try These Fixes
date: 2025-01-24T01:18:26.306Z
updated: 2025-01-25T00:04:46.545Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Can’t Delete Temporary Files in Windows? Try These Fixes
excerpt: This Article Describes Can’t Delete Temporary Files in Windows? Try These Fixes
keywords: Delete Temp Files Windows,Remove Windows Trash Files,Clear Windows Cache,Fixed Deleting Temp Files,Unblock Windows Space,Clean Windows Temporary Data,Fix Delete Files Error
thumbnail: https://thmb.techidaily.com/dc0976bf992fc8f3795e090c13f66cb1c6f1455915fe3cbbbf65ceba836d3f9e.jpg
---

## Can’t Delete Temporary Files in Windows? Try These Fixes

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/updated-essentials-of-drafting-engaging-vlogger-speeches-for-2024/"><u>[Updated] Essentials of Drafting Engaging Vlogger Speeches for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-exceptional-sound-value-for-aspiring-asmr-artists/"><u>2024 Approved Exceptional Sound Value for Aspiring ASMR Artists</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-how-to-leverage-longer-vids-on-instagram-effectively/"><u>2024 Approved How to Leverage Longer Vids on Instagram Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debugging-code-0xc0000142-on-windows-oses/"><u>Debugging Code 0XC0000142 on Windows OSes</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210630768-9783986537524-dark-persuasion/"><u>DАRK PЕRSUАSION | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-system-performance-with-clean-media-consumption/"><u>Enhancing System Performance with Clean Media Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-windows-11s-software-distro-and-catroot2-restart/"><u>Essential Steps for Windows 11'S Software Distro and Catroot2 Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-memory-allocation-by-antivirus-software/"><u>Fine-Tuning Memory Allocation by Antivirus Software</u></a></li>
<li><a href="https://vp-tips.techidaily.com/flvswfweb-movavi/"><u>FLVからSWFへの完全無償Web動画変換 - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/growth-tactics-for-windows-storage-preserve-information/"><u>Growth Tactics for Windows Storage, Preserve Information</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-breaking-down-discords-report-mechanism-for-clarity-and-action/"><u>In 2024, Breaking Down Discord’s Report Mechanism for Clarity and Action</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Oppo A78? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-revitalize-your-reels-selecting-the-best-5-enhancers/"><u>In 2024, Revitalize Your Reels Selecting the Best 5 Enhancers</u></a></li>
<li><a href="https://video-capture.techidaily.com/master-the-mind-discovering-elite-game-rooms/"><u>Master the Mind Discovering Elite Game Rooms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-on-customizing-programs-for-windows-11-users/"><u>Masterclass on Customizing Programs for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-pubg-restoring-saving-settings-in-windows-systems/"><u>Mastering PUBG: Restoring Saving Settings in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-reopening-calendars-and-mail/"><u>Mastering the Art of Reopening Calendars and Mail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-resource-usage-settings-in-the-windows-subsystem/"><u>Navigating Resource Usage Settings in the Windows Subsystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-start-menu-uncluttered-by-ads/"><u>Win 11'S Start Menu - Uncluttered by Ads</u></a></li>
</ul></div>

