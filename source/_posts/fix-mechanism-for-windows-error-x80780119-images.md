---
title: Fix Mechanism for Windows Error X80780119 Images
date: 2024-06-25T16:20:20.275Z
updated: 2024-06-26T16:20:20.275Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Mechanism for Windows Error X80780119 Images
excerpt: This Article Describes Fix Mechanism for Windows Error X80780119 Images
keywords: Windows Error Fixer,X80780119 Image Repair,Windows Diagnostics Tool,Corrupt Image Resolver,Windows System Error Guide,X80780119 Image Troubleshooter,Windows File Restoration Kit
thumbnail: https://thmb.techidaily.com/61c513946ca67c4ebe171c06eca13adeadd0c93b5bf89d5e42f26ac56570469b.jpg
---

## Fix Mechanism for Windows Error X80780119 Images

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

## 2\. Check and Repair Disk Errors

 You might also be facing the system restore issue due to disk errors in the system.

 During the backup process, the system needs to read data from the targeted disk and write it to the backup destination. If there is an issue with the disk, the system may have issues reading the data or might write corrupted data in the backup file, which can result in different errors.

 Additionally, your disk might have bad sectors which cannot store data properly and might also prevent the system from reading data during the backup process.

 To ensure this isn’t the case in your situation, it is best to check the disk for errors using the built-in utilities offered by Windows. The first tool that we recommend [using is the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) which can be used via Command Prompt. It works by scanning the system and checking the integrity of the disk. If a problem is identified, CHKDSK will attempt to fix it automatically.

 Alternatively, you can head over to the File Explorer and follow these steps:

1. In File Explorer, head over to the root of the drive you want to check and right-click on it.
2. Choose **Properties** from the context menu.
3. In the Properties dialog, navigate to the **Tools** tab and move to the **Error checking** section.
4. Click on the **Check** button here and wait for the system to complete the scan. This may take some time, depending upon the size of your disk.  
![Run the error checking tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/error-checking-tool.jpg)

 If any issues are found, Windows will prompt you to repair them. Follow the on-screen instructions to proceed.

## 3\. Enable System Protection

 Several users also noticed that they were facing the problem due to the system protection feature being disabled for the targeted drive. If you have this option disabled in your system, we suggest enabling it and checking if that makes any difference.

 Here is how you can do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Navigate to **System** \> **About**.
3. Head over to the **Device specifications** section and click on the **System protection** option.  
![Click on the System protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection-options.jpg)
4. In the following dialog, head over to the **System Protection** tab.
5. Choose the targeted drive and click on the **Configure** button.  
![Click on the Configure button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/configure-button.jpg)
6. Enable the **Turn on system protection** option and click **Apply** \> **OK** to save the changes.  
![Enable system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-system-protection.jpg)

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/innovative-windows-local-space-management-tips-no-file-removal-max-156-chars/"><u>Innovative Windows Local Space Management Tips (No File Removal) (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-efficient-bluescreenview-use/"><u>Essential Tips for Efficient BlueScreenView Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-copilot-key-what-does-it-mean-for-your-windows-11-pc/"><u>Microsoft's Copilot Key: What Does It Mean For Your Windows 11 PC?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-administered-window-on-os-x/"><u>Guidelines for Administered Window on OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-winning-with-the-windows-11-bar/"><u>Essential Strategies for Winning with the Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-suppression-of-windows-11-notifications/"><u>Immediate Suppression of Windows 11 Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-device-disconnection-on-win-1011/"><u>Navigating and Fixing Device Disconnection on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-integrating-airpods-with-windows/"><u>Efficient Method: Integrating AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-correcting-code-0x0000004e-in-os/"><u>Techniques for Correcting Code 0X0000004E in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-functionality-reprogramming-fn-keys-on-modern-windows-pcs/"><u>Enhance Functionality: Reprogramming FN Keys on Modern Windows PCs</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-how-to-record-a-podcast-effortlessly-a-step-by-step-guide/"><u>2024 Approved How to Record a Podcast Effortlessly A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unlock-facebook-ad-success-with-these-3-adapted-writing-techniques/"><u>Unlock Facebook Ad Success with These 3 Adapted Writing Techniques</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-14-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 14 To Other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/the-art-of-expanded-viewport-in-social-vids-for-2024/"><u>The Art of Expanded Viewport in Social Vids for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-oneplus-ace-2v-by-drfone-android/"><u>In 2024, How to Bypass FRP from OnePlus Ace 2V?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-must-try-titles-for-tranquil-touchscreen-time/"><u>[Updated] In 2024, Must-Try Titles for Tranquil Touchscreen Time</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/convert-and-share-simplified-mp3-to-youtube-process-3-phases-for-2024/"><u>Convert & Share  Simplified MP3 to YouTube Process [3 Phases] for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-obs-streaming-windows-and-mac-guide/"><u>[New] In 2024, OBS Streaming [Windows and Mac Guide]</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-pushing-creative-boundaries-utilizing-advanced-techniques-for-luts-in-after-effects/"><u>[New] Pushing Creative Boundaries  Utilizing Advanced Techniques for LUTs in After Effects</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-remedy-screen-disruptions-during-live-streams/"><u>[New] Remedy Screen Disruptions During Live Streams</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>