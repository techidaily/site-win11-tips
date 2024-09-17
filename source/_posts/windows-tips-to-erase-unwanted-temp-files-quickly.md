---
title: Windows Tips to Erase Unwanted Temp Files Quickly
date: 2024-09-13T21:21:29.369Z
updated: 2024-09-17T07:04:55.324Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Tips to Erase Unwanted Temp Files Quickly
excerpt: This Article Describes Windows Tips to Erase Unwanted Temp Files Quickly
keywords: Windows Cleanup Guide,Delete Temp Files Fast,Windows Free Up Space,Optimize PC Speed,Remove Temporary Icons,Clear Windows Cache Quickly,Unused Files Erase Tips
thumbnail: https://thmb.techidaily.com/10c291d26c69b79184acc714bd905fecf227774d1628ff4b17b2024d943bf02d.jpg
---

## Windows Tips to Erase Unwanted Temp Files Quickly

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

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
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-secret-whatsapp-techniques-for-maximum-impact/"><u>2024 Approved Secret WhatsApp Techniques for Maximum Impact</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/apple-iphone-8-plus-mirror-to-pc-top-apps-you-must-know-drfone-by-drfone-ios/"><u>Apple iPhone 8 Plus Mirror to PC? Top Apps You Must Know | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/best-tools-for-retrieving-lost-or-unreadable-drives-partition-recovery-solutions/"><u>Best Tools for Retrieving Lost or Unreadable Drives: Partition Recovery Solutions</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-it-tecno-camon-20-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Tecno Camon 20 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/innovative-ai-names-for-podcasts-the-ultimate-guide-for-2024/"><u>Innovative AI Names for Podcasts – The Ultimate Guide for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagram-pro-tips-effortless-video-upload-from-pcmac/"><u>Instagram Pro Tips Effortless Video Upload From PC/Mac</u></a></li>
<li><a href="https://extra-hints.techidaily.com/master-class-on-cutting-unwanted-backdrops/"><u>Master Class on Cutting Unwanted Backdrops</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-solutions-for-resolving-hp-envy-7640-printer-drivers/"><u>Quick Solutions for Resolving HP ENVY 7640 Printer Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-no-sound-recognition-by-windows-operating-system/"><u>Reversing No Sound Recognition by Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-system-mastering-three-windows-restarts/"><u>Revitalize Your System: Mastering Three Windows Restarts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-bsod-fix-in-windows-vmware-edition/"><u>Steps for BSOD Fix in Windows: VMware Edition</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    