---
title: Unraveling Windows' Code 0X80780119 Restore Mishap
date: 2024-11-20T16:49:31.160Z
updated: 2024-11-27T17:15:00.647Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling Windows' Code 0X80780119 Restore Mishap
excerpt: This Article Describes Unraveling Windows' Code 0X80780119 Restore Mishap
keywords: WinRestoreError,OS_Code0X8078,XPErrorCorrection,Windows0X8078Fix,MishapWindowsCode,OS0X8078Recovery,RestoreErrorWindows
thumbnail: https://thmb.techidaily.com/c572e526911ff13873cfea2690ee252e9ff11a89ced90101624b46320eed1514.jpg
---

## Unraveling Windows' Code 0X80780119 Restore Mishap

 Creating a system image backup is essential in protecting your data and ensuring system recoverability, but the process of doing so might not always go smoothly. One such error that the users often encounter is the System Restore error 0x80780119, which prevents the users from completing the backup process.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

## Why Are You Unable to Create a System Image?

 If you are unable to create a system image due to the error 0x80780119, it might be because of one or more of the following reasons:

* **Insufficient disk space**: Restore points take up space in the drive they are saved, and so to create new restore points on your computer, you must have sufficient disk space available. In case you are running out of space on your system, you are likely to face the error at hand.
* **Incorrect backup settings**: Your backup settings must be configured correctly. If there is an issue with these settings, the System Restore will encounter issues while creating a restore point.
* **External drive issues**: If you are using an external drive for backup, it is essential to ensure that it is connected to the system properly and is functioning. In case there is an issue with the external drive due to any of these problems, the System Restore utility might return the error 0x80780119\.
* **Corrupt system files**: The critical system files that are essential to create restore points and use the System Restore utility might have gotten corrupt, which is leading to the error under discussion.
* **Antivirus interruption**: If you are using a security program on your computer, there is a chance that it is blocking the restore tool from functioning properly. This typically happens when you are using a third-party antivirus solution.

 Regardless of what might be resulting in the problem in your case, the solutions we have listed below are sure to help you get the restore utility back on track. Proceed with the solutions one by one and follow the steps carefully for successful execution.

## 1\. Free Up Disk Space

 When you create a restore point in Windows, the system requires sufficient space on the destination drive to store all the backup files. If you do not have enough space, the System Restore is likely to return errors like the 0x80780119 error.

 This is why, before moving onto the complex troubleshooting methods, we recommend you ensure you have sufficient space available on the destination drive. If you are low on space, you can free it up by removing unnecessary files. Here are a few areas to focus on:

* **Temporary files**: Temporary files and other unnecessary data can be cleaned up by [using the Disk Cleanup tool](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/). It will list down all such files, and you can then specify which to remove. Simply type “Disk Cleanup” in the search area on your taskbar and click **Open** to launch the utility.
* **Downloads folder**: Access the Download folder in File Explorer and delete all the files you no longer need.
* **Uninstall unused programs**: If there are apps that you do not use anymore, head over to the Control Panel to uninstall them from the system. This will free up a great amount of space that can be used by the System Restore utility.

 In case you have large files or folders that you do not want to remove but also don’t need immediately, you can consider moving them to an external drive to free up space.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Check and Repair Disk Errors

 You might also be facing the system restore issue due to disk errors in the system.

 During the backup process, the system needs to read data from the targeted disk and write it to the backup destination. If there is an issue with the disk, the system may have issues reading the data or might write corrupted data in the backup file, which can result in different errors.

 Additionally, your disk might have bad sectors which cannot store data properly and might also prevent the system from reading data during the backup process.

 To ensure this isn’t the case in your situation, it is best to check the disk for errors using the built-in utilities offered by Windows. The first tool that we recommend[using is the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) which can be used via Command Prompt. It works by scanning the system and checking the integrity of the disk. If a problem is identified, CHKDSK will attempt to fix it automatically.

 Alternatively, you can head over to the File Explorer and follow these steps:

1. In File Explorer, head over to the root of the drive you want to check and right-click on it.
2. Choose **Properties** from the context menu.
3. In the Properties dialog, navigate to the **Tools** tab and move to the **Error checking** section.
4. Click on the **Check** button here and wait for the system to complete the scan. This may take some time, depending upon the size of your disk.  
![Run the error checking tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/error-checking-tool.jpg)

 If any issues are found, Windows will prompt you to repair them. Follow the on-screen instructions to proceed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Enable System Protection

 Several users also noticed that they were facing the problem due to the system protection feature being disabled for the targeted drive. If you have this option disabled in your system, we suggest enabling it and checking if that makes any difference.

 Here is how you can do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Navigate to **System** \> **About**.
3. Head over to the **Device specifications** section and click on the **System protection** option.  
![Click on the System protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection-options.jpg)
4. In the following dialog, head over to the **System Protection** tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Choose the targeted drive and click on the **Configure** button.  
![Click on the Configure button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/configure-button.jpg)
6. Enable the **Turn on system protection** option and click **Apply** \> **OK** to save the changes.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-system-protection.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can now close the System Protection dialog and check if the issue is resolved.

## 4\. Delete USN Journal

 The USN Journal (Update Sequence Number Journal) is a feature in the NTFS file system that tracks all the changes made on a disk. It is stored in the reserved partition and over time, it can consume a significant amount of your disk space, which may be preventing a restore point from being created.

 You can reclaim this disk space by deleting the USN Journal. Doing so will also eliminate the possibility of any conflicts that might be arising due to inconsistencies between the journal and the files being backed up.

 Here is how you can do that:

1. Type "Create and format hard disk partitions" in Windows search and click **Open**.
2. In the following window, right-click on the **System Reserved** volume and choose **Change Drive Letter and Paths** from the context menu.
3. Now, click on the **Add** button.
4. In the next dialog, choose **Assign the following drive letter** and click **OK**.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Once done, press the **Win** \+ **R** keys together to open Run.
6. Type "cmd" in Run and click **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
7. Confirm your action in the UAC prompt.
8. Execute the following commands in Command Prompt one by one:  
`fsutil usn queryjournal F:fsutil usn deletejournal /N /D F:`

 After the commands are executed, you can close Command Prompt and check if the issue is resolved.

## Create a Backup Without Any More Errors on Windows

 Ensuring the protection of your data should be your foremost priority, and a system image backup plays a vital role in safeguarding against unforeseen data loss. With the solutions above, you should be able to get the System Restore utility up and running in no time. However, if the problem persists, you can consider reporting the issue to Microsoft and try the specific solutions they suggest. Till then, you can switch to a third-party backup tool to safeguard your data.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-navigating-fee-free-discord-videos-download-handheld-and-workstation-guide/"><u>[New] In 2024, Navigating Fee-Free Discord Videos Download Handheld & Workstation Guide</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-listeners-lexicon-selecting-solid-offline-recording-tools/"><u>[New] Listeners' Lexicon Selecting Solid Offline Recording Tools</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-easy-steps-to-document-video-calls-for-2024/"><u>[Updated] Easy Steps to Document Video Calls for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-next-gen-sky-dome-cutting-edge-cloud-services-of-2024/"><u>[Updated] Next-Gen Sky Dome Cutting-Edge Cloud Services of 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-windows-admin-blacklist/"><u>Circumventing Windows Admin Blacklist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-challenge-of-microsoft-powerpoint-prints-on-windows/"><u>Conquering the Challenge of Microsoft PowerPoint Prints on Windows</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/correcting-contact-details-in-protonvpn-extension/"><u>Correcting Contact Details in ProtonVPN Extension</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-interaction-with-windows-copilot-and-vivetool/"><u>Enhancing User Interaction with Windows Copilot and ViveTool</u></a></li>
<li><a href="https://change-location.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-elite-list-of-best-online-sound-capturing-devices-2023/"><u>In 2024, Elite List of Best Online Sound Capturing Devices 2023</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/iphone-handbooks-downloading-made-easy-access-documentation-for-every-version/"><u>IPhone Handbooks Downloading Made Easy: Access Documentation for Every Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-audio-subtitle-coordination-with-prime-and-windows-11/"><u>Master Audio-Subtitle Coordination with Prime & Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/no-strings-attached-top-free-video-editing-software-without-watermarks/"><u>No Strings Attached Top Free Video Editing Software without Watermarks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-workflow-assign-winos-command-shortcuts/"><u>Optimize Workflow: Assign WinOS Command Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-challenges-in-activating-dormant-windows-extras/"><u>Overcome Challenges in Activating Dormant Windows Extras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolve-windows-stores-error-0x80073d26/"><u>Quick Guide to Resolve Windows Store's Error 0X80073D26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-operations-with-task-scheduler-controls/"><u>Seamless File Operations with Task Scheduler Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-cross-platform-efficiency-using-samsungs-dex/"><u>The Key to Cross-Platform Efficiency: Using Samsung's DeX</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-your-disabled-apple-iphone-14-pro-max-without-itunes-in-5-ways-drfone-by-drfone-ios/"><u>Unlock Your Disabled Apple iPhone 14 Pro Max Without iTunes in 5 Ways | Dr.fone</u></a></li>
</ul></div>

