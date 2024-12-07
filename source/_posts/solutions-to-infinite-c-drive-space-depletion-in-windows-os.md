---
title: "Solutions to Infinite C: Drive Space Depletion in Windows OS"
date: 2024-11-29T19:56:11.356Z
updated: 2024-12-07T01:56:42.526Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Solutions to Infinite C: Drive Space Depletion in Windows OS"
excerpt: "This Article Describes Solutions to Infinite C: Drive Space Depletion in Windows OS"
keywords: WinOS Cleanup Guide,DriveSpace Recovery Tips,Endless C Drive Fix,Clearing Infinite C Storage,Optimize Windows Space Usage,Depleted C Drive Solutions,Resetting Windows Disk Limit
thumbnail: https://thmb.techidaily.com/9cb4bb095934cdbe52cf30982bf7e5d8440404211e93965b72d3f210e8935545.jpg
---

## Solutions to Infinite C: Drive Space Depletion in Windows OS

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [Start With These Quick Maintenance Tips](#start-with-these-quick-maintenance-tips)
* [Scan for Malware](#scan-for-malware)
* [Run Disk Cleanup](#run-disk-cleanup)
* [Use CHKDSK to Find File System Errors](#use-chkdsk-to-find-file-system-errors)
* [Manage Your System Restore Points](#manage-your-system-restore-points)
* [Extend the C: Partition](#extend-the-c-partition)
* [Stop Your Computer From Hibernating](#stop-your-computer-from-hibernating)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Relocate personal folders and change the default save location to free up space on the C: drive.
* Use Windows Defender or third-party antivirus software to scan for malware and remove any hidden infections.
* Run Disk Cleanup to safely delete temporary files and manage the WinSxs system folder size.

 The C: drive in a Windows 11 or 10 PC contains the Windows installation files, along with other important files and folders, that all take up space. But if you notice the C: drive on your Windows computer fills up repeatedly, it may be a deeper issue that you should fix.

## Start With These Quick Maintenance Tips

 The C: drive might keep filling up because you store everything there instead of partitioning your physical drive. Try relocating personal folders to another partition or an external drive to free up some space. Additionally, [change the default save location for files and folders](https://www.makeuseof.com/windows-change-save-location/) so that new downloads are automatically saved elsewhere.

 Also, check your installed apps and remove anything unnecessary. Even if you didn’t recently install any new apps, your system might contain [bloatware or unnecessary software you can remove](https://www.makeuseof.com/tag/10-windows-programs-uninstall/).

 If you need more solutions to free up the C: drive, follow the tips below.

## 1\. Scan for Malware

 Viruses and other malware are some of the most common perpetrators behind unusual storage use on your hard drive. Thus, the first step you should take after noticing a C: drive storage issue is scanning for infection.

 Windows Defender does the job well and provides adequate protection against all types of PC malware. While it has real-time protection, you should perform a full system scan to detect any hidden malware on your computer:

1. In the Start menu search bar or Windows Search, type **Windows Security**.
2. Click on the Windows Security app from the results. You'll recognize its shield icon.
3. On the next screen, click on **Virus & threat protection**.
4. Under **Current Threats**, click **Scan options**.
5. On the next screen, ensure that the **Full Scan** option is selected.
6. Click on **Scan now**.
7. Wait for Windows to finish scanning the computer for viruses.

![Windows Defender scan options.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/scan-options-windows-11.jpg)

 While the scan is in progress, you may notice a slowdown in your computer. It's recommended you postpone any resource-intensive tasks until the scan is over. If you use third-party antivirus software, you can perform a full scan by opening the application's dashboard (usually in the **System Tray**) and proceeding from there. The exact method differs across different antivirus vendors.

 If this ends up being the source of your problem, see the [steps you should take upon discovering malware on your computer](http://www.makeuseof.com/tag/10-steps-to-take-when-you-discover-malware-on-your-computer/).

## 2\. Run Disk Cleanup

 Temporary files, such as thumbnails and previous Windows updates, take up a lot of space on your hard drive. The Disk Cleanup utility in Windows can help you [safely delete temporary files, old copies of Windows Update files, Windows upgrade logs, and more](https://www.makeuseof.com/tag/delete-windows-files-folders/):

1. Type **Disk Cleanup** in the Start menu search bar or Windows Search.
2. Right-click on **Disk Cleanup > Run as administrator** from the search results.
3. Select **Local Disk (C:)** from the disk selection menu and click **OK**.
4. Under **Files to delete**, check options such as temporary internet files, thumbnails, and previous Windows installations and updates. Note that you won't be able to roll back Windows updates if you check the **Windows Update Cleanup** option.
5. Click **OK**.
6. On the next prompt, click **Delete files**.
7. Wait for Disk Cleanup to do its job.

![Disk Cleanup options in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/disk-cleanup-tool-windows-11.jpg)

 Disk Cleanup is also recommended to [manage the massive WinSxs (Windows Side-by-Side) system folder](https://www.makeuseof.com/tag/manage-winsxs-folder-windows/). This Windows component stocks different versions of DLL, EXE, and OCX files. It plays a vital role as it helps update Windows without overwriting or deleting critical files, and in case of a crash, it can help roll back changes. However, WinSxs can balloon up to a size of 5-10GB.

 Windows automatically manages the WinSxs folder, but it may be easier to run the Disk Cleanup tool to reduce its size.

## 3\. Use CHKDSK to Find File System Errors

 Logical errors on your storage disk can cause all sorts of malfunctions. This includes the incorrect reading of free disk space and storage allocation issues. You can perform a CHKDSK scan using Windows Command Prompt or the Local Disk properties menu to fix this.

### How to Run CHKDSK Using Command Prompt

 CHKDSK is a Windows utility that scans and fixes logical errors on your SSD or hard drive. To use it:

1. Type **cmd** in Windows search.
2. Right-click on **Command Prompt > Run as administrator**.
3. In the CMD console, enter **chkdsk C: /f** and press **Enter**.
4. CHKDSK will scan the C: drive for errors and automatically fix them upon detection.
5. Restart your computer after the scan is complete.

![The CHKDSK fix command in Command Prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-command-prompt.jpg)

### How to Run CHKDSK Using Drive Properties

 If you prefer to use CHKDSK without the command line, use this method:

1. Open **File Explorer** using the **Win + E** shortcut.
2. Navigate to **This PC**.
3. Right-click on **Local Disk (C:)**.
4. Click on **Properties**.
5. Choose the **Tools** tab.
6. Under Error Checking, click **Check.** You will need administrative privileges to go through with the scan.
7. Click on the **Scan Drive** option when prompted.

![Fix disk errors using Properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-properties.jpg)

## 4\. Manage Your System Restore Points

 System Restore is a critical Windows feature that allows you to restore your computer to a previous state in case of problems. But System Restore Points can take up a lot of space on your PC, depending upon how you've configured the function.

 To adjust the space that System Restore points take up, follow these steps:

1. Type **System Restore** in the Start menu search bar and click **Create a restore point**.
2. Under **Protection Settings**, select **Local Disk (C:)** in the **Available Drives** box, then hit **Configure**.
3. In the next window, move the **Max Usage** slider to the left. The further left, the less space System Restore will use to make restore points.
4. Click **OK > OK** once you're satisfied.

![System Restore Points configuration menu.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/system-restore-points-space-management.jpg)

 Alternatively, you can [delete unneeded System Restore points](https://www.makeuseof.com/ways-delete-system-restore-points-in-windows/) to free up additional space on your computer.

## 5\. Extend the C: Partition

 If you're sure that the storage issue on your computer is not the result of anything above, it may be worth extending the storage space on the C: partition. Of course, this is only possible if you have multiple partitions on your drive, or unallocated space is available.

 All these operations can be performed using Disk Management:

1. Press **Win + R** to open the Run box. Type **diskmgmt.msc** and press **Enter**.
2. In the **Disk Management** window, right-click on **Local Disk (C:)**.
3. Click on the **Extend Volume** option.  
   1. If it's grayed out, no unallocated space is available on your storage device. To [unallocate space from another partition](https://www.makeuseof.com/merge-partitions-windows/), right-click the partition and select **Shrink Volume**. Then enter the amount of space you want to reallocate.
4. In the **Extend Volume Wizard**, click **Next**.
5. Adjust the amount of space you want to add to the C: drive using the **Select the amount of space in MB** option.
6. Click **Next >** **Finish**.

![Disk Management home screen in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/disk-management-windows-11.jpg)

## 6\. Stop Your Computer From Hibernating

 When your computer enters hibernation mode, it saves energy by shutting your system off completely, while enabling you to pick up your work from where you left off. While this may be convenient, hibernation files can fill up your C: drive.

 To turn off hibernation, launch Command Prompt with administrative rights (right-click the Start button for a shortcut) and run this command:

`powercfg.exe /hibernate off`

 As your computer will no longer hibernate, be sure to save all your work before leaving your desk.

 If you need more help keeping the C: drive clutter-free, you can use a third-party app to clean your disk. Besides freeing up space on your C: drive, these tools could improve your computer’s overall performance.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Relocate personal folders and change the default save location to free up space on the C: drive.
* Use Windows Defender or third-party antivirus software to scan for malware and remove any hidden infections.
* Run Disk Cleanup to safely delete temporary files and manage the WinSxs system folder size.

 The C: drive in a Windows 11 or 10 PC contains the Windows installation files, along with other important files and folders, that all take up space. But if you notice the C: drive on your Windows computer fills up repeatedly, it may be a deeper issue that you should fix.

## Start With These Quick Maintenance Tips

 The C: drive might keep filling up because you store everything there instead of partitioning your physical drive. Try relocating personal folders to another partition or an external drive to free up some space. Additionally, [change the default save location for files and folders](https://www.makeuseof.com/windows-change-save-location/) so that new downloads are automatically saved elsewhere.

 Also, check your installed apps and remove anything unnecessary. Even if you didn’t recently install any new apps, your system might contain [bloatware or unnecessary software you can remove](https://www.makeuseof.com/tag/10-windows-programs-uninstall/).

 If you need more solutions to free up the C: drive, follow the tips below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Scan for Malware

 Viruses and other malware are some of the most common perpetrators behind unusual storage use on your hard drive. Thus, the first step you should take after noticing a C: drive storage issue is scanning for infection.

 Windows Defender does the job well and provides adequate protection against all types of PC malware. While it has real-time protection, you should perform a full system scan to detect any hidden malware on your computer:

1. In the Start menu search bar or Windows Search, type **Windows Security**.
2. Click on the Windows Security app from the results. You'll recognize its shield icon.
3. On the next screen, click on **Virus & threat protection**.
4. Under **Current Threats**, click **Scan options**.
5. On the next screen, ensure that the **Full Scan** option is selected.
6. Click on **Scan now**.
7. Wait for Windows to finish scanning the computer for viruses.

![Windows Defender scan options.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/scan-options-windows-11.jpg)

 While the scan is in progress, you may notice a slowdown in your computer. It's recommended you postpone any resource-intensive tasks until the scan is over. If you use third-party antivirus software, you can perform a full scan by opening the application's dashboard (usually in the **System Tray**) and proceeding from there. The exact method differs across different antivirus vendors.

 If this ends up being the source of your problem, see the [steps you should take upon discovering malware on your computer](http://www.makeuseof.com/tag/10-steps-to-take-when-you-discover-malware-on-your-computer/).

## 2\. Run Disk Cleanup

 Temporary files, such as thumbnails and previous Windows updates, take up a lot of space on your hard drive. The Disk Cleanup utility in Windows can help you [safely delete temporary files, old copies of Windows Update files, Windows upgrade logs, and more](https://www.makeuseof.com/tag/delete-windows-files-folders/):

1. Type **Disk Cleanup** in the Start menu search bar or Windows Search.
2. Right-click on **Disk Cleanup > Run as administrator** from the search results.
3. Select **Local Disk (C:)** from the disk selection menu and click **OK**.
4. Under **Files to delete**, check options such as temporary internet files, thumbnails, and previous Windows installations and updates. Note that you won't be able to roll back Windows updates if you check the **Windows Update Cleanup** option.
5. Click **OK**.
6. On the next prompt, click **Delete files**.
7. Wait for Disk Cleanup to do its job.

![Disk Cleanup options in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/disk-cleanup-tool-windows-11.jpg)

 Disk Cleanup is also recommended to [manage the massive WinSxs (Windows Side-by-Side) system folder](https://www.makeuseof.com/tag/manage-winsxs-folder-windows/). This Windows component stocks different versions of DLL, EXE, and OCX files. It plays a vital role as it helps update Windows without overwriting or deleting critical files, and in case of a crash, it can help roll back changes. However, WinSxs can balloon up to a size of 5-10GB.

 Windows automatically manages the WinSxs folder, but it may be easier to run the Disk Cleanup tool to reduce its size.

## 3\. Use CHKDSK to Find File System Errors

 Logical errors on your storage disk can cause all sorts of malfunctions. This includes the incorrect reading of free disk space and storage allocation issues. You can perform a CHKDSK scan using Windows Command Prompt or the Local Disk properties menu to fix this.

### How to Run CHKDSK Using Command Prompt

 CHKDSK is a Windows utility that scans and fixes logical errors on your SSD or hard drive. To use it:

1. Type **cmd** in Windows search.
2. Right-click on **Command Prompt > Run as administrator**.
3. In the CMD console, enter **chkdsk C: /f** and press **Enter**.
4. CHKDSK will scan the C: drive for errors and automatically fix them upon detection.
5. Restart your computer after the scan is complete.

![The CHKDSK fix command in Command Prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### How to Run CHKDSK Using Drive Properties

 If you prefer to use CHKDSK without the command line, use this method:

1. Open **File Explorer** using the **Win + E** shortcut.
2. Navigate to **This PC**.
3. Right-click on **Local Disk (C:)**.
4. Click on **Properties**.
5. Choose the **Tools** tab.
6. Under Error Checking, click **Check.** You will need administrative privileges to go through with the scan.
7. Click on the **Scan Drive** option when prompted.

![Fix disk errors using Properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-properties.jpg)

## 4\. Manage Your System Restore Points

 System Restore is a critical Windows feature that allows you to restore your computer to a previous state in case of problems. But System Restore Points can take up a lot of space on your PC, depending upon how you've configured the function.

 To adjust the space that System Restore points take up, follow these steps:

1. Type **System Restore** in the Start menu search bar and click **Create a restore point**.
2. Under **Protection Settings**, select **Local Disk (C:)** in the **Available Drives** box, then hit **Configure**.
3. In the next window, move the **Max Usage** slider to the left. The further left, the less space System Restore will use to make restore points.
4. Click **OK > OK** once you're satisfied.

![System Restore Points configuration menu.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/system-restore-points-space-management.jpg)

 Alternatively, you can [delete unneeded System Restore points](https://www.makeuseof.com/ways-delete-system-restore-points-in-windows/) to free up additional space on your computer.

## 5\. Extend the C: Partition

 If you're sure that the storage issue on your computer is not the result of anything above, it may be worth extending the storage space on the C: partition. Of course, this is only possible if you have multiple partitions on your drive, or unallocated space is available.

 All these operations can be performed using Disk Management:

1. Press **Win + R** to open the Run box. Type **diskmgmt.msc** and press **Enter**.
2. In the **Disk Management** window, right-click on **Local Disk (C:)**.
3. Click on the **Extend Volume** option.  
   1. If it's grayed out, no unallocated space is available on your storage device. To [unallocate space from another partition](https://www.makeuseof.com/merge-partitions-windows/), right-click the partition and select **Shrink Volume**. Then enter the amount of space you want to reallocate.
4. In the **Extend Volume Wizard**, click **Next**.
5. Adjust the amount of space you want to add to the C: drive using the **Select the amount of space in MB** option.
6. Click **Next >** **Finish**.

![Disk Management home screen in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/disk-management-windows-11.jpg)

## 6\. Stop Your Computer From Hibernating

 When your computer enters hibernation mode, it saves energy by shutting your system off completely, while enabling you to pick up your work from where you left off. While this may be convenient, hibernation files can fill up your C: drive.

 To turn off hibernation, launch Command Prompt with administrative rights (right-click the Start button for a shortcut) and run this command:

`powercfg.exe /hibernate off`

 As your computer will no longer hibernate, be sure to save all your work before leaving your desk.

 If you need more help keeping the C: drive clutter-free, you can use a third-party app to clean your disk. Besides freeing up space on your C: drive, these tools could improve your computer’s overall performance.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Relocate personal folders and change the default save location to free up space on the C: drive.
* Use Windows Defender or third-party antivirus software to scan for malware and remove any hidden infections.
* Run Disk Cleanup to safely delete temporary files and manage the WinSxs system folder size.

 The C: drive in a Windows 11 or 10 PC contains the Windows installation files, along with other important files and folders, that all take up space. But if you notice the C: drive on your Windows computer fills up repeatedly, it may be a deeper issue that you should fix.

## Start With These Quick Maintenance Tips

 The C: drive might keep filling up because you store everything there instead of partitioning your physical drive. Try relocating personal folders to another partition or an external drive to free up some space. Additionally, [change the default save location for files and folders](https://www.makeuseof.com/windows-change-save-location/) so that new downloads are automatically saved elsewhere.

 Also, check your installed apps and remove anything unnecessary. Even if you didn’t recently install any new apps, your system might contain [bloatware or unnecessary software you can remove](https://www.makeuseof.com/tag/10-windows-programs-uninstall/).

 If you need more solutions to free up the C: drive, follow the tips below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Scan for Malware

 Viruses and other malware are some of the most common perpetrators behind unusual storage use on your hard drive. Thus, the first step you should take after noticing a C: drive storage issue is scanning for infection.

 Windows Defender does the job well and provides adequate protection against all types of PC malware. While it has real-time protection, you should perform a full system scan to detect any hidden malware on your computer:

1. In the Start menu search bar or Windows Search, type **Windows Security**.
2. Click on the Windows Security app from the results. You'll recognize its shield icon.
3. On the next screen, click on **Virus & threat protection**.
4. Under **Current Threats**, click **Scan options**.
5. On the next screen, ensure that the **Full Scan** option is selected.
6. Click on **Scan now**.
7. Wait for Windows to finish scanning the computer for viruses.

![Windows Defender scan options.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/scan-options-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 While the scan is in progress, you may notice a slowdown in your computer. It's recommended you postpone any resource-intensive tasks until the scan is over. If you use third-party antivirus software, you can perform a full scan by opening the application's dashboard (usually in the **System Tray**) and proceeding from there. The exact method differs across different antivirus vendors.

 If this ends up being the source of your problem, see the [steps you should take upon discovering malware on your computer](http://www.makeuseof.com/tag/10-steps-to-take-when-you-discover-malware-on-your-computer/).

## 2\. Run Disk Cleanup

 Temporary files, such as thumbnails and previous Windows updates, take up a lot of space on your hard drive. The Disk Cleanup utility in Windows can help you [safely delete temporary files, old copies of Windows Update files, Windows upgrade logs, and more](https://www.makeuseof.com/tag/delete-windows-files-folders/):

1. Type **Disk Cleanup** in the Start menu search bar or Windows Search.
2. Right-click on **Disk Cleanup > Run as administrator** from the search results.
3. Select **Local Disk (C:)** from the disk selection menu and click **OK**.
4. Under **Files to delete**, check options such as temporary internet files, thumbnails, and previous Windows installations and updates. Note that you won't be able to roll back Windows updates if you check the **Windows Update Cleanup** option.
5. Click **OK**.
6. On the next prompt, click **Delete files**.
7. Wait for Disk Cleanup to do its job.

![Disk Cleanup options in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/disk-cleanup-tool-windows-11.jpg)

 Disk Cleanup is also recommended to [manage the massive WinSxs (Windows Side-by-Side) system folder](https://www.makeuseof.com/tag/manage-winsxs-folder-windows/). This Windows component stocks different versions of DLL, EXE, and OCX files. It plays a vital role as it helps update Windows without overwriting or deleting critical files, and in case of a crash, it can help roll back changes. However, WinSxs can balloon up to a size of 5-10GB.

 Windows automatically manages the WinSxs folder, but it may be easier to run the Disk Cleanup tool to reduce its size.

## 3\. Use CHKDSK to Find File System Errors

 Logical errors on your storage disk can cause all sorts of malfunctions. This includes the incorrect reading of free disk space and storage allocation issues. You can perform a CHKDSK scan using Windows Command Prompt or the Local Disk properties menu to fix this.

### How to Run CHKDSK Using Command Prompt

 CHKDSK is a Windows utility that scans and fixes logical errors on your SSD or hard drive. To use it:

1. Type **cmd** in Windows search.
2. Right-click on **Command Prompt > Run as administrator**.
3. In the CMD console, enter **chkdsk C: /f** and press **Enter**.
4. CHKDSK will scan the C: drive for errors and automatically fix them upon detection.
5. Restart your computer after the scan is complete.

![The CHKDSK fix command in Command Prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### How to Run CHKDSK Using Drive Properties

 If you prefer to use CHKDSK without the command line, use this method:

1. Open **File Explorer** using the **Win + E** shortcut.
2. Navigate to **This PC**.
3. Right-click on **Local Disk (C:)**.
4. Click on **Properties**.
5. Choose the **Tools** tab.
6. Under Error Checking, click **Check.** You will need administrative privileges to go through with the scan.
7. Click on the **Scan Drive** option when prompted.

![Fix disk errors using Properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Manage Your System Restore Points

 System Restore is a critical Windows feature that allows you to restore your computer to a previous state in case of problems. But System Restore Points can take up a lot of space on your PC, depending upon how you've configured the function.

 To adjust the space that System Restore points take up, follow these steps:

1. Type **System Restore** in the Start menu search bar and click **Create a restore point**.
2. Under **Protection Settings**, select **Local Disk (C:)** in the **Available Drives** box, then hit **Configure**.
3. In the next window, move the **Max Usage** slider to the left. The further left, the less space System Restore will use to make restore points.
4. Click **OK > OK** once you're satisfied.

![System Restore Points configuration menu.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/system-restore-points-space-management.jpg)

 Alternatively, you can [delete unneeded System Restore points](https://www.makeuseof.com/ways-delete-system-restore-points-in-windows/) to free up additional space on your computer.

## 5\. Extend the C: Partition

 If you're sure that the storage issue on your computer is not the result of anything above, it may be worth extending the storage space on the C: partition. Of course, this is only possible if you have multiple partitions on your drive, or unallocated space is available.

 All these operations can be performed using Disk Management:

1. Press **Win + R** to open the Run box. Type **diskmgmt.msc** and press **Enter**.
2. In the **Disk Management** window, right-click on **Local Disk (C:)**.
3. Click on the **Extend Volume** option.  
   1. If it's grayed out, no unallocated space is available on your storage device. To [unallocate space from another partition](https://www.makeuseof.com/merge-partitions-windows/), right-click the partition and select **Shrink Volume**. Then enter the amount of space you want to reallocate.
4. In the **Extend Volume Wizard**, click **Next**.
5. Adjust the amount of space you want to add to the C: drive using the **Select the amount of space in MB** option.
6. Click **Next >** **Finish**.

![Disk Management home screen in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/disk-management-windows-11.jpg)

## 6\. Stop Your Computer From Hibernating

 When your computer enters hibernation mode, it saves energy by shutting your system off completely, while enabling you to pick up your work from where you left off. While this may be convenient, hibernation files can fill up your C: drive.

 To turn off hibernation, launch Command Prompt with administrative rights (right-click the Start button for a shortcut) and run this command:

`powercfg.exe /hibernate off`

 As your computer will no longer hibernate, be sure to save all your work before leaving your desk.

 If you need more help keeping the C: drive clutter-free, you can use a third-party app to clean your disk. Besides freeing up space on your C: drive, these tools could improve your computer’s overall performance.

### Key Takeaways

* Relocate personal folders and change the default save location to free up space on the C: drive.
* Use Windows Defender or third-party antivirus software to scan for malware and remove any hidden infections.
* Run Disk Cleanup to safely delete temporary files and manage the WinSxs system folder size.

 The C: drive in a Windows 11 or 10 PC contains the Windows installation files, along with other important files and folders, that all take up space. But if you notice the C: drive on your Windows computer fills up repeatedly, it may be a deeper issue that you should fix.

## Start With These Quick Maintenance Tips

 The C: drive might keep filling up because you store everything there instead of partitioning your physical drive. Try relocating personal folders to another partition or an external drive to free up some space. Additionally, [change the default save location for files and folders](https://www.makeuseof.com/windows-change-save-location/) so that new downloads are automatically saved elsewhere.

 Also, check your installed apps and remove anything unnecessary. Even if you didn’t recently install any new apps, your system might contain [bloatware or unnecessary software you can remove](https://www.makeuseof.com/tag/10-windows-programs-uninstall/).

 If you need more solutions to free up the C: drive, follow the tips below.

## 1\. Scan for Malware

 Viruses and other malware are some of the most common perpetrators behind unusual storage use on your hard drive. Thus, the first step you should take after noticing a C: drive storage issue is scanning for infection.

 Windows Defender does the job well and provides adequate protection against all types of PC malware. While it has real-time protection, you should perform a full system scan to detect any hidden malware on your computer:

1. In the Start menu search bar or Windows Search, type **Windows Security**.
2. Click on the Windows Security app from the results. You'll recognize its shield icon.
3. On the next screen, click on **Virus & threat protection**.
4. Under **Current Threats**, click **Scan options**.
5. On the next screen, ensure that the **Full Scan** option is selected.
6. Click on **Scan now**.
7. Wait for Windows to finish scanning the computer for viruses.

![Windows Defender scan options.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/scan-options-windows-11.jpg)

 While the scan is in progress, you may notice a slowdown in your computer. It's recommended you postpone any resource-intensive tasks until the scan is over. If you use third-party antivirus software, you can perform a full scan by opening the application's dashboard (usually in the **System Tray**) and proceeding from there. The exact method differs across different antivirus vendors.

 If this ends up being the source of your problem, see the [steps you should take upon discovering malware on your computer](http://www.makeuseof.com/tag/10-steps-to-take-when-you-discover-malware-on-your-computer/).

## 2\. Run Disk Cleanup

 Temporary files, such as thumbnails and previous Windows updates, take up a lot of space on your hard drive. The Disk Cleanup utility in Windows can help you [safely delete temporary files, old copies of Windows Update files, Windows upgrade logs, and more](https://www.makeuseof.com/tag/delete-windows-files-folders/):

1. Type **Disk Cleanup** in the Start menu search bar or Windows Search.
2. Right-click on **Disk Cleanup > Run as administrator** from the search results.
3. Select **Local Disk (C:)** from the disk selection menu and click **OK**.
4. Under **Files to delete**, check options such as temporary internet files, thumbnails, and previous Windows installations and updates. Note that you won't be able to roll back Windows updates if you check the **Windows Update Cleanup** option.
5. Click **OK**.
6. On the next prompt, click **Delete files**.
7. Wait for Disk Cleanup to do its job.

![Disk Cleanup options in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/disk-cleanup-tool-windows-11.jpg)

 Disk Cleanup is also recommended to [manage the massive WinSxs (Windows Side-by-Side) system folder](https://www.makeuseof.com/tag/manage-winsxs-folder-windows/). This Windows component stocks different versions of DLL, EXE, and OCX files. It plays a vital role as it helps update Windows without overwriting or deleting critical files, and in case of a crash, it can help roll back changes. However, WinSxs can balloon up to a size of 5-10GB.

 Windows automatically manages the WinSxs folder, but it may be easier to run the Disk Cleanup tool to reduce its size.

## 3\. Use CHKDSK to Find File System Errors

 Logical errors on your storage disk can cause all sorts of malfunctions. This includes the incorrect reading of free disk space and storage allocation issues. You can perform a CHKDSK scan using Windows Command Prompt or the Local Disk properties menu to fix this.

### How to Run CHKDSK Using Command Prompt

 CHKDSK is a Windows utility that scans and fixes logical errors on your SSD or hard drive. To use it:

1. Type **cmd** in Windows search.
2. Right-click on **Command Prompt > Run as administrator**.
3. In the CMD console, enter **chkdsk C: /f** and press **Enter**.
4. CHKDSK will scan the C: drive for errors and automatically fix them upon detection.
5. Restart your computer after the scan is complete.

![The CHKDSK fix command in Command Prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-command-prompt.jpg)

### How to Run CHKDSK Using Drive Properties

 If you prefer to use CHKDSK without the command line, use this method:

1. Open **File Explorer** using the **Win + E** shortcut.
2. Navigate to **This PC**.
3. Right-click on **Local Disk (C:)**.
4. Click on **Properties**.
5. Choose the **Tools** tab.
6. Under Error Checking, click **Check.** You will need administrative privileges to go through with the scan.
7. Click on the **Scan Drive** option when prompted.

![Fix disk errors using Properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-properties.jpg)

## 4\. Manage Your System Restore Points

 System Restore is a critical Windows feature that allows you to restore your computer to a previous state in case of problems. But System Restore Points can take up a lot of space on your PC, depending upon how you've configured the function.

 To adjust the space that System Restore points take up, follow these steps:

1. Type **System Restore** in the Start menu search bar and click **Create a restore point**.
2. Under **Protection Settings**, select **Local Disk (C:)** in the **Available Drives** box, then hit **Configure**.
3. In the next window, move the **Max Usage** slider to the left. The further left, the less space System Restore will use to make restore points.
4. Click **OK > OK** once you're satisfied.

![System Restore Points configuration menu.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/system-restore-points-space-management.jpg)

 Alternatively, you can [delete unneeded System Restore points](https://www.makeuseof.com/ways-delete-system-restore-points-in-windows/) to free up additional space on your computer.

## 5\. Extend the C: Partition

 If you're sure that the storage issue on your computer is not the result of anything above, it may be worth extending the storage space on the C: partition. Of course, this is only possible if you have multiple partitions on your drive, or unallocated space is available.

 All these operations can be performed using Disk Management:

1. Press **Win + R** to open the Run box. Type **diskmgmt.msc** and press **Enter**.
2. In the **Disk Management** window, right-click on **Local Disk (C:)**.
3. Click on the **Extend Volume** option.  
   1. If it's grayed out, no unallocated space is available on your storage device. To [unallocate space from another partition](https://www.makeuseof.com/merge-partitions-windows/), right-click the partition and select **Shrink Volume**. Then enter the amount of space you want to reallocate.
4. In the **Extend Volume Wizard**, click **Next**.
5. Adjust the amount of space you want to add to the C: drive using the **Select the amount of space in MB** option.
6. Click **Next >** **Finish**.

![Disk Management home screen in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/disk-management-windows-11.jpg)

## 6\. Stop Your Computer From Hibernating

 When your computer enters hibernation mode, it saves energy by shutting your system off completely, while enabling you to pick up your work from where you left off. While this may be convenient, hibernation files can fill up your C: drive.

 To turn off hibernation, launch Command Prompt with administrative rights (right-click the Start button for a shortcut) and run this command:

`powercfg.exe /hibernate off`

 As your computer will no longer hibernate, be sure to save all your work before leaving your desk.

 If you need more help keeping the C: drive clutter-free, you can use a third-party app to clean your disk. Besides freeing up space on your C: drive, these tools could improve your computer’s overall performance.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-the-art-of-capturing-sound-via-mac/"><u>[New] In 2024, The Art of Capturing Sound via Mac</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-power-of-persuasion-how-to-boost-instagram-post-reach/"><u>[New] The Power of Persuasion How to Boost Instagram Post Reach</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-unrestricted-display-save-tool/"><u>[Updated] In 2024, Unrestricted Display Save Tool</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-gb-for-a-continuous-video-watched-daily/"><u>2024 Approved GB for a Continuous Video Watched Daily</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-the-science-of-swift-facebook-visuals/"><u>2024 Approved The Science of Swift Facebook Visuals</u></a></li>
<li><a href="https://win-able.techidaily.com/conquer-the-battlefront-a-step-by-step-solution-to-dev-error-6068-in-mws-latest-conflict/"><u>Conquer the Battlefront: A Step-by-Step Solution to Dev Error 6068 in MW's Latest Conflict</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-11-writable-memory-protection/"><u>Correcting Windows 11' Writable Memory Protection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhome-explained-mastering-windows-11-upgrades/"><u>DevHome Explained: Mastering Windows 11 Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-code-0x80070141-making-unreachable-devices-connectable/"><u>Eliminating Error Code 0X80070141: Making Unreachable Devices Connectable</u></a></li>
<li><a href="https://win11-tips.techidaily.com/flattening-the-cornered-look-of-win11/"><u>Flattening the Cornered Look of Win11</u></a></li>
<li><a href="https://win-unique.techidaily.com/guia-paso-a-paso-para-reducir-el-tamano-de-la-imagen-del-sistema-al-disco-duro/"><u>Guía Paso a Paso Para Reducir El Tamaño De La Imagen Del Sistema Al Disco Duro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-error-code-0x80-point-to-point-link-failure-on-windows/"><u>How to Handle Error Code: 0X80 Point-to-Point Link Failure on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-set-up-custom-hotkeys-for-pasting-pre-defined-text-snippets-in-windows-10-and-11/"><u>How to Set Up Custom Hotkeys for Pasting Pre-Defined Text Snippets in Windows 10 & 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-revolutionize-earning-with-youtube-short-tactics/"><u>In 2024, Revolutionize Earning with Youtube Short Tactics</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-2024-approved-how-to-use-korean-to-english-video-translators-for-creators/"><u>New 2024 Approved How To Use Korean to English Video Translators for Creators</u></a></li>
<li><a href="https://win-able.techidaily.com/noise-problem-in-evil-genius-2-here-are-proven-audio-troubleshooting-tips/"><u>Noise Problem in 'Evil Genius 2'? Here Are Proven Audio Troubleshooting Tips!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-devices-with-synapse-on-windows-11/"><u>Reviving Dormant Devices with Synapse on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-erroneous-code-fixing-0x800713f-mail-glitch-in-windows-11/"><u>Tackling Erroneous Code: Fixing 0X800713F Mail Glitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-tricks-for-resolving-obs-studios-disconnect-issue-on-windows-pcs/"><u>Top 7 Tricks for Resolving OBS Studio's Disconnect Issue on Windows PCs</u></a></li>
</ul></div>

