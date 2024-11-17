---
title: "Reversing C: Drive Filling Mystery on PCs"
date: 2024-11-12T18:50:54.851Z
updated: 2024-11-17T19:00:00.678Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reversing C: Drive Filling Mystery on PCs"
excerpt: "This Article Describes Reversing C: Drive Filling Mystery on PCs"
keywords: PC C Drive Issues,Reverse PC Drives,Fix C Drive Errors,Clear C Drive Problems,Recover PC Storage,C Drive Restoration,Resolve Drives Malfunction
thumbnail: https://thmb.techidaily.com/2eefe00fc71984145735604d7f6409f58eabe8499747b0b476c4253bd9b978c9.jpg
---

## Reversing C: Drive Filling Mystery on PCs

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075483/7443" target="_top" id="2075483">
  <img src="//a.impactradius-go.com/display-ad/7443-2075483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075483/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885999/19272" target="_top" id="1885999">
  <img src="//a.impactradius-go.com/display-ad/19272-1885999" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885999/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Run CHKDSK Using Command Prompt

 CHKDSK is a Windows utility that scans and fixes logical errors on your SSD or hard drive. To use it:

1. Type **cmd** in Windows search.
2. Right-click on **Command Prompt > Run as administrator**.
3. In the CMD console, enter **chkdsk C: /f** and press **Enter**.
4. CHKDSK will scan the C: drive for errors and automatically fix them upon detection.
5. Restart your computer after the scan is complete.

![The CHKDSK fix command in Command Prompt.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/chkdsk-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139123/17108" target="_top" id="2139123">
  <img src="//a.impactradius-go.com/display-ad/17108-2139123" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139123/17108" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use CHKDSK to Find File System Errors

 Logical errors on your storage disk can cause all sorts of malfunctions. This includes the incorrect reading of free disk space and storage allocation issues. You can perform a CHKDSK scan using Windows Command Prompt or the Local Disk properties menu to fix this.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-essential-guide-to-the-top-10-video-calls-for-your-smartphone-for-2024/"><u>[New] Essential Guide to the Top 10 Video Calls for Your Smartphone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-robust-access-controls-via-powertoys/"><u>Implementing Robust Access Controls via PowerToys</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-iphone-13-pro-max-and-ipad-securely-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on iPhone 13 Pro Max and iPad Securely</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/m3-or-m2-macbook-air-expert-review-and-buyers-guide-by-zdnet-to-determine-apples-newest-laptop-contender/"><u>M3 or M2 MacBook Air? Expert Review & Buyer’s Guide by ZDNet to Determine Apple's Newest Laptop Contender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-saving-woes-quickly-6-key-methods-for-powerpoint-in-windows/"><u>Resolve Saving Woes Quickly: 6 Key Methods for PowerPoint in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restrictions-on-windows-11-insider-edition-use/"><u>Restrictions on Windows 11 Insider Edition Use</u></a></li>
<li><a href="https://extra-hints.techidaily.com/screencasting-app-performance-examination/"><u>ScreenCasting App Performance Examination</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721268067787-stellar/"><u>Stellarの修理施術を直ちに受ける方法</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-global-morning-routine-saying-hello-in-10-languages/"><u>The Global Morning Routine: Saying Hello in 10 Languages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-understanding-your-last-windows-use/"><u>The Key to Understanding Your Last Windows Use</u></a></li>
<li><a href="https://techtrends.techidaily.com/travel-tech-hacks-mastering-your-roku-setup-for-school-trips-and-hotel-getaways/"><u>Travel Tech Hacks: Mastering Your Roku Setup for School Trips and Hotel Getaways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/twinning-inboxes-gmail-plus-outlook-for-windows-users-guide/"><u>Twinning Inboxes: Gmail + Outlook for Windows Users Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-windows-11-functionality-with-a-powerful-run-feature/"><u>Upgrade Windows 11 Functionality with a Powerful Run Feature</u></a></li>
</ul></div>

