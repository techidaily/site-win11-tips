---
title: Windows Troubleshooting for Elusive Temp Files
date: 2024-07-12T17:07:28.652Z
updated: 2024-07-13T17:07:28.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Troubleshooting for Elusive Temp Files
excerpt: This Article Describes Windows Troubleshooting for Elusive Temp Files
keywords: Windows File Cleanup,Temp Fix in Windows,Delete Unused Temp Folders,Win Temp File Issues,Temporary Files Removal,Troubleshoot Win Temp,Elusive Temp File Resolve
thumbnail: https://thmb.techidaily.com/c7faa06295ae09ceb9c04771af8ef4a70065bcb58f83238cd328dc914caf4d9a.jpg
---

## Windows Troubleshooting for Elusive Temp Files

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

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

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
<li><a href="https://eaxpv-info.techidaily.com/updated-harness-the-power-of-youtube-videos-to-create-stunning-gifs-online-for-2024/"><u>[Updated] Harness the Power of Youtube Videos to Create Stunning Gifs Online for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-smart-social-media-strategies-from-youtube-to-facebook/"><u>In 2024, Smart Social Media Strategies  From YouTube To Facebook</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-bandicam-vs-camtasia-which-one-is-better-in-2024/"><u>[New] Bandicam vs Camtasia, Which One Is Better, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-winerror-0xc0000005/"><u>Mastering the Art of Fixing WinError 0Xc0000005</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-effortless-edits-streamlining-your-tiktok-archives-excessive-saves/"><u>In 2024, Effortless Edits  Streamlining Your TikTok Archive's Excessive Saves</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-capturecore-an-exhaustive-look-at-new-recording-technology/"><u>2024 Approved  'CaptureCore'  An Exhaustive Look at New Recording Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-chromes-system-time-a-fix-guide-windows/"><u>Realigning Chrome's System Time: A Fix Guide (Windows)</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/10-top-must-have-gear-items-for-youtubers-for-2024/"><u>10 Top Must-Have Gear Items for YouTubers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-access-mastering-network-drives-in-win11/"><u>Seamless File Access: Mastering Network Drives in Win11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-full-guide-to-funcall-voice-changer-and-its-alternatives/"><u>New Full Guide to Funcall Voice Changer and Its Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-non-scrollability-of-ranges-in-excel-windows/"><u>Prevent Non-Scrollability of Ranges in Excel, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-must-have-android-apps-for-windows-users/"><u>Nine Must-Have Android Apps for Windows Users</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-cutting-edge-chapter-tactics-to-complement-your-youtube-presentations-for-2024/"><u>[Updated] Cutting-Edge Chapter Tactics to Complement Your YouTube Presentations for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-movie-maker-for-kids-teach-kids-to-make-a-movie/"><u>2024 Approved Movie Maker for Kids Teach Kids to Make a Movie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-up-output-the-power-of-flow-launcher-unveiled/"><u>Scaling Up Output: The Power of Flow Launcher Unveiled</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-spotlight-on-tiktoks-newest-dance-moves/"><u>[Updated] 2024 Approved  Spotlight on TikTok's Newest Dance Moves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-launchers-security-failures-on-windows-systems/"><u>Navigating Launcher's Security Failures on Windows Systems</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-instant-guide-image-to-thumbnail-magic-for-your-youtube-channel/"><u>2024 Approved  Instant Guide  Image-To-Thumbnail Magic for Your YouTube Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-approach-to-editing-windows-registry-with-command-prompt/"><u>Stepwise Approach to Editing Windows Registry with Command Prompt</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-digital-arcade-over-a-hundred-game-channels/"><u>[Updated] 2024 Approved  Digital Arcade  Over a Hundred Game Channels</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-expert-guide-streaming-and-saving-hulu-seasons-flawlessly/"><u>2024 Approved  Expert Guide  Streaming and Saving Hulu Seasons Flawlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-display-at-operating-system-kickoff/"><u>Resolving Non-Display at Operating System Kickoff</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-gazescope-grading-guide/"><u>[Updated] GazeScope Grading Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-desktop-icon-update-process-on-windows/"><u>Simplifying Desktop Icon Update Process on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timely-tactics-effective-execution-of-ping-commands/"><u>Timely Tactics: Effective Execution of Ping Commands</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-honor-100-pro-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Honor 100 Pro Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-efficiency-guide/"><u>Mastering Windows 11: Efficiency Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-selecting-the-right-video-subscription-plan-at-vimeo/"><u>In 2024, Selecting the Right Video Subscription Plan at Vimeo</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ltimate-students-guide-to-historical-channels-1-10-for-2024/"><u>[New] Ultimate Students' Guide to Historical Channels #1-10 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-on-windows-11-updates/"><u>Solving Error 0X80246007 on Windows 11 Updates</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-discover-how-you-can-use-vectorscope-to-adjust-luminance-color-grading-and-more-in-your-video-editing-projects/"><u>Updated 2024 Approved Discover How You Can Use Vectorscope to Adjust Luminance, Color Grading, and More in Your Video Editing Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-list-of-windows-note-taking-aids/"><u>Ultimate List of Windows Note-Taking Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rectifying-device-is-unreachable-error-in-windows/"><u>Mastering the Art of Rectifying Device Is Unreachable Error in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-realme-gt-neo-5-se-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Realme GT Neo 5 SE Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reverse-winerror-exit-point-failure/"><u>Steps to Reverse WinError Exit Point Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-approach-to-bypassing-no-permission-on-pc/"><u>Step-by-Step Approach to Bypassing 'No Permission' On PC</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-boosting-vimeo-video-playback-tips-and-tricks/"><u>In 2024, Boosting Vimeo Video Playback  Tips and Tricks</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-prime-ringtone-retailers-for-game-of-thrones-fans/"><u>2024 Approved  Prime Ringtone Retailers for Game of Thrones Fans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-device-hang-on-windows-11-zerodxgieror/"><u>Overcoming the Device Hang on Windows 11 (ZeroDXGIEror)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-and-permanently-discard-a-partition-on-windows-pc/"><u>How to Swiftly and Permanently Discard a Partition on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-solving-obs-errors-windows-edition/"><u>Understanding and Solving OBS Errors: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-1053-unresponsive-service-issue/"><u>Tackling Windows Error 1053: Unresponsive Service Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-level-windows-photos-shortcut-guide/"><u>Pro-Level Windows Photos Shortcut Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-extend-wait-time-before-shutting-down-in-windows-10/"><u>Tactics to Extend Wait Time Before Shutting Down in Windows 10</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-itel-a70-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Itel A70.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peering-into-ftdibussys-an-analysis-of-windows-memory-controls/"><u>Peering Into ftdibus.sys: An Analysis of Windows' Memory Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-faded-screen-settings-in-uefi/"><u>Restoring Faded Screen Settings in UEFI</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-threefold-mastery-in-copy-for-social-media-campaigns-increasing-impact-with-every-word/"><u>[Updated] 2024 Approved  Threefold Mastery in Copy for Social Media Campaigns – Increasing Impact with Every Word</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/maximize-your-storage-tips-and-tricks-for-liberating-space-for-fcpx/"><u>Maximize Your Storage Tips and Tricks for Liberating Space for FCPX</u></a></li>
<li><a href="https://vp-tips.techidaily.com/proven-strategies-for-powerful-customer-success-stories-on-screen/"><u>Proven Strategies for Powerful Customer Success Stories on Screen</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/elevate-and-accelerate-vimeo-videos-for-2024/"><u>Elevate and Accelerate Vimeo Videos for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/all-you-need-to-know-about-mega-greninja-for-vivo-y100t-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/severing-the-ties-unlink-onedrive-from-your-msid-on-windows/"><u>Severing the Ties: Unlink OneDrive From Your MSID on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-installation-and-usage-of-ms-store-themes/"><u>Navigate With Style: Installation and Usage of MS Store Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stuck-keys-alert-restoring-order-in-windows/"><u>Stuck Keys Alert: Restoring Order in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-instructions-for-installing-chrome-on-windows-11/"><u>Stepwise Instructions for Installing Chrome on Windows 11</u></a></li>
</ul></div>
