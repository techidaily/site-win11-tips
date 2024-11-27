---
title: "Resolving the Error: Image ID 0X80780119 in Windows"
date: 2024-11-23T17:49:17.334Z
updated: 2024-11-27T16:20:58.493Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving the Error: Image ID 0X80780119 in Windows"
excerpt: "This Article Describes Resolving the Error: Image ID 0X80780119 in Windows"
keywords: Fixing Windows Image Error,Troubleshooting Windows ID Error,Resolve Image Issue 0X80780119,Correcting Windows Image ID Error,Windows Error,Addressing Windows Image ID Fault,Fixing Windows Image 0X80780119 Error
thumbnail: https://thmb.techidaily.com/6169c8a9aeeb67674aa07a2a9dad06d0ae5fef5e196eb54e46717e8334c8bace.jpg
---

## Resolving the Error: Image ID 0X80780119 in Windows

 Creating a system image backup is essential in protecting your data and ensuring system recoverability, but the process of doing so might not always go smoothly. One such error that the users often encounter is the System Restore error 0x80780119, which prevents the users from completing the backup process.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If any issues are found, Windows will prompt you to repair them. Follow the on-screen instructions to proceed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Choose the targeted drive and click on the **Configure** button.  
![Click on the Configure button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/configure-button.jpg)
6. Enable the **Turn on system protection** option and click **Apply** \> **OK** to save the changes.  
![Enable system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-system-protection.jpg)

 You can now close the System Protection dialog and check if the issue is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://screen-recording.techidaily.com/new-best-5-webcams-with-mic-for-2024/"><u>[New] Best 5 Webcams with Mic for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chromes-unwanted-tab-behavior-stop-and-reverse/"><u>Chrome's Unwanted Tab Behavior: Stop and Reverse</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/efficiently-convert-videos-to-hevc-format-using-handbrake-complete-encoder-setup-tutorial/"><u>Efficiently Convert Videos to HEVC Format Using Handbrake – Complete Encoder Setup Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-muting-pc-sound-boosting-options/"><u>Guide to Muting PC Sound Boosting Options</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-messages-on-y56-5g-by-fonelab-android-recover-messages/"><u>How to restore wiped messages on Y56 5G</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-vivo-t2-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Vivo T2 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-the-windows-engine-crafting-and-deciphering-system-data/"><u>Inside the Windows Engine: Crafting & Deciphering System Data</u></a></li>
<li><a href="https://fox-glue.techidaily.com/mobile-cinema-apples-no1-8-pack-free-and-paid-film-app-guide-for-2024/"><u>Mobile Cinema Apple's No.1, 8-Pack Free & Paid Film App Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/past-perspectives-present-7-features-from-older-windows-versions/"><u>Past Perspectives Present: 7 Features From Older Windows Versions</u></a></li>
<li><a href="https://win-best.techidaily.com/resmi-petualangan-untuk-memulihkan-informasi-di-ssd-yang-tidak-dapat-dibuka/"><u>Resmi Petualangan Untuk Memulihkan Informasi Di SSD Yang Tidak Dapat Dibuka</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-time-travel-reimagining-windows-11-as-98/"><u>Tech Time Travel: Reimagining Windows 11 as 98</u></a></li>
<li><a href="https://buynow-info.techidaily.com/transform-your-drive-with-the-escort-ix-the-cutting-edge-ai-jammer-for-smart-drivers/"><u>Transform Your Drive with the Escort iX: The Cutting-Edge AI Jammer for Smart Drivers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/transforming-gaming-how-three-major-pc-manufacturers-are-revolutionizing-the-experience-with-chrome-powered-devices-insights-from-zdnet/"><u>Transforming Gaming: How Three Major PC Manufacturers Are Revolutionizing the Experience with Chrome-Powered Devices - Insights From ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-esd-data-into-linuxwindows-iso-formats/"><u>Transitioning ESD Data Into Linux/Windows ISO Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-discontent-in-windows-11-upgrades/"><u>Unveiling the Discontent in Windows 11 Upgrades</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-convert-optimize-and-thrill-the-best-vr-video-conversion-software-for-2024/"><u>Updated Convert, Optimize, and Thrill The Best VR Video Conversion Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrar-archive-success-nine-ways-to-prevent-checksum-errors/"><u>WinRAR Archive Success: Nine Ways to Prevent Checksum Errors</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    