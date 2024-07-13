---
title: "How To Repair Image ID: 0X80780119 on Windows OS"
date: 2024-07-12T17:07:47.065Z
updated: 2024-07-13T17:07:47.065Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How To Repair Image ID: 0X80780119 on Windows OS"
excerpt: "This Article Describes How To Repair Image ID: 0X80780119 on Windows OS"
keywords: Fixing Windows Image Errors,ZeroID,Windows ID Repair Guide,Overcoming Windows Image Issues,Correct Image ID on PC,Troubleshoot WinImage ID Error,Fixing Corrupt OS Images
thumbnail: https://thmb.techidaily.com/aeb1adbf149584a341fb74f49144490d740789721f41a9cf0edd89a122f69cd4.jpg
---

## How To Repair Image ID: 0X80780119 on Windows OS

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-harnessing-the-power-of-hashtags-to-amplify-your-igtv-content/"><u>[Updated] In 2024, Harnessing the Power of Hashtags to Amplify Your IGTV Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-failures-from-windows-memory-tool/"><u>How To Rectify Failures From Windows Memory Tool</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-the-ultimate-guide-to-splitting-videos-in-windows-live-movie-maker-for-beginners/"><u>2024 Approved The Ultimate Guide to Splitting Videos in Windows Live Movie Maker for Beginners</u></a></li>
<li><a href="https://extra-information.techidaily.com/charming-calls-verify-if-vocal-alteration-apps-are-real-then-find-others-for-2024/"><u>Charming Calls  Verify if Vocal Alteration Apps Are Real, Then Find Others for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-speed-up-epic-games-launcher-downloads-on-windows/"><u>How to Speed Up Epic Games Launcher Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-directdraw-issues-on-windows-11-and-11-pros/"><u>Overcoming DirectDraw Issues on Windows 11 & 11 Pros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-domain-services-error-printer-issues-in-windows-11/"><u>Repairing Domain Services Error: Printer Issues in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-redmi-note-12-pro-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi Redmi Note 12 Pro 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/interacting-with-network-drives-from-smartphones/"><u>Interacting with Network Drives From Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-craft-of-simultaneous-unzipping-with-windows-tools/"><u>Master the Craft of Simultaneous Unzipping with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-primary-app-uses-computer-audio-devices/"><u>Resolving Non-Primary App Uses Computer Audio Devices</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-top-9-sparkle-effects-photo-and-video-editors-you-should-know/"><u>2024 Approved Top 9 Sparkle Effects Photo and Video Editors You Should Know</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-crafting-classic-cinematography-step-by-step-guide/"><u>[New] Crafting Classic Cinematography  Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-complexities-of-multimonitor-setup-in-windows-11/"><u>Navigating The Complexities of Multimonitor Setup in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-canine-howl-amalgam-sounds-and-effects-compilation/"><u>New In 2024, Canine Howl Amalgam Sounds & Effects Compilation</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-video-editing-software-for-mac-windows-movie-maker-alternatives/"><u>In 2024, Best Video Editing Software for Mac Windows Movie Maker Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-efficient-task-management-in-ms-project/"><u>Quick and Efficient Task Management in MS Project</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-0x800713f-mail-glitch/"><u>Resolving Windows' 0X800713F Mail Glitch</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-streamline-memory-management-via-mematic/"><u>[Updated] In 2024, Streamline Memory Management via Mematic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-challenges-in-full-screen-snip-and-sketch-capturing/"><u>Overcoming Challenges in Full-Screen Snip & Sketch Capturing</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-lasting-way-to-disconnect-from-youtube-shorts-for-2024/"><u>The Lasting Way to Disconnect From YouTube Shorts for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-honor-play-8t-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Honor Play 8T – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-captioning-hurdles-on-windows-10-devices/"><u>Solving Common Captioning Hurdles on Windows 10 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recognizing-unseen-sd-card-fix-for-windows-explorer/"><u>Recognizing Unseen SD Card: Fix for Windows Explorer</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-resonant-harmony-a-comprehensive-list-of-voice-enhancing-apps-for-all-audiences-and-budgets/"><u>New 2024 Approved Resonant Harmony A Comprehensive List of Voice-Enhancing Apps for All Audiences and Budgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-0x800f0922-error-quick-fixed-guide/"><u>Solving Windows 11'S 0X800F0922 Error - Quick Fixed Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-convert-youtube-videos-smoothly-into-professional-webm-files/"><u>[Updated] 2024 Approved  Convert YouTube Videos Smoothly Into Professional WebM Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-time-shifts-on-windows-a-guide/"><u>Preventing Time Shifts on Windows: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-fatal-0xf0831-bug/"><u>Resolving Windows 11'S Fatal 0xF0831 Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-switching-on-updated-widget-selection-interface-in-windows-11/"><u>Seamlessly Switching on Updated Widget Selection Interface in Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-fcp-voice-over-essentials-mastering-the-basics/"><u>New In 2024, FCP Voice Over Essentials Mastering the Basics</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-the-art-of-space-arrangement-in-fostering-a-high-performing-team/"><u>[New] The Art of Space Arrangement in Fostering a High-Performing Team</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Motorola Moto E13? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-data-flow-from-non-responsive-usb-devices-win-os/"><u>Restoring Data Flow From Non-Responsive USB Devices (Win OS)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-system-image-creation-on-windows/"><u>Simplified System Image Creation on Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ey-takeaways-on-youtube-tv-an-overview-of-its-advantages-for-2024/"><u>[New] Key Takeaways on YouTube TV  An Overview of Its Advantages for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-adjust-privacy-settings-for-secure-online-viewing/"><u>[Updated] 2024 Approved  Adjust Privacy Settings for Secure Online Viewing</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-crafting-compelling-gopro-livestreams-on-facebook-and-periscope/"><u>[New] In 2024, Crafting Compelling GoPro Livestreams on Facebook & Periscope</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-honor-90-pro-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Honor 90 Pro</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-top-10-gaming-pc-graphics-for-ultimate-youtube-viewing-experience/"><u>2024 Approved  Top 10 Gaming PC Graphics  For Ultimate YouTube Viewing Experience</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-honor-90-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Honor 90 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-daily-productivity-the-top-6-apps-for-windows-11-users/"><u>Mastering Daily Productivity: The Top 6 Apps For Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-qt-plugin-during-software-application-initiation/"><u>Overcoming Missing Qt Plugin During Software Application Initiation</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/unlocking-revenue-with-strategic-snapchat-promotions-for-2024/"><u>Unlocking Revenue with Strategic Snapchat Promotions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stuck-battlenet-login-screen/"><u>Solutions for Stuck Battle.net Login Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-find-feature-in-windows-11-taskbar-activation-guide/"><u>Instant Find Feature in Windows 11 Taskbar – Activation Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-oneplus-nord-3-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From OnePlus Nord 3 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-lockout-try-these-hacks/"><u>Microsoft Store Lockout? Try These Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restarting-windows-updates/"><u>Mastering the Art of Restarting Windows Updates</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-exploring-t-series-youtube-profit-strategy/"><u>[New] 2024 Approved  Exploring T-Series YouTube Profit Strategy</u></a></li>
</ul></div>
