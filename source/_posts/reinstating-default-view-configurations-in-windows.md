---
title: Reinstating Default View Configurations in Windows
date: 2024-12-05T16:01:25.748Z
updated: 2024-12-13T00:24:59.831Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Default View Configurations in Windows
excerpt: This Article Describes Reinstating Default View Configurations in Windows
keywords: Win Default View Restore,Window Default Settings,Restore Windows View,Change Views Windows,Windows Default Configure,Default Windows Viewing,Windows View Defaults Revive
thumbnail: https://thmb.techidaily.com/270179364474a44da1eaeda7613c10f10260fff7aad4cae0d60acb9733eadc20.jpg
---

## Reinstating Default View Configurations in Windows

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
7. From the left pane, select**Desktop** as the location.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must[create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will[open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-5-simple-yet-powerful-strategies-to-skyrocket-your-youtube-views/"><u>[New] 2024 Approved 5 Simple Yet Powerful Strategies to Skyrocket Your YouTube Views</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-discover-the-top-free-platforms-for-youtube-ops-for-2024/"><u>[New] Discover the Top Free Platforms for YouTube Ops for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-mastering-your-video-projects-with-superior-recorder-software-for-2024/"><u>[New] Mastering Your Video Projects with Superior Recorder Software for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-proven-practice-for-preserving-playthroughs-tips-and-tricks-for-recording-roblox-gameplay-on-a-mac/"><u>[New] Proven Practice for Preserving Playthroughs Tips & Tricks for Recording Roblox Gameplay on a Mac</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-seamless-music-integration-transform-your-favorite-tunes-into-youtube-content/"><u>[Updated] Seamless Music Integration Transform Your Favorite Tunes Into YouTube Content</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-compare-the-best-free-screen-recorders-on-windows-os/"><u>2024 Approved Compare the Best Free Screen Recorders on Windows OS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-immediate-stop-of-automatic-video-capture-in-qt-player/"><u>2024 Approved Immediate Stop of Automatic Video Capture in QT Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-installing-and-updating-apps-via-wpm-in-windows-11/"><u>Comprehensive Guide to Installing and Updating Apps via WPM in Windows 11</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-insights-on-hostgators-cloud-and-shared-hosting-options-what-you-need-to-know/"><u>Expert Insights on HostGator's Cloud & Shared Hosting Options - What You Need to Know</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exploring-elementary-os-a-user-friendly-macos-inspired-alternative/"><u>Exploring Elementary OS: A User-Friendly, MacOS Inspired Alternative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-your-way-to-direct-pc-links-on-windows-11/"><u>Hacking Your Way to Direct PC Links on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-obs-studio-startup-blunders-win-edition/"><u>Preventing OBS Studio Startup Blunders (Win Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-non-operational-snapshot-creation/"><u>Remedying Non-Operational Snapshot Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-windows-emailcalendar-integrating-fav-photos/"><u>Revamp Windows Email/Calendar - Integrating Fav Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-the-window-11-help-service-breakdown/"><u>Solutions for the Window 11 Help Service Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-vanish-taskview-button-from-window-11/"><u>Strategies to Vanish TaskView Button From Window 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-ultimate-guidebook-to-making-wealth-on-instagram-for-2024/"><u>The Ultimate Guidebook to Making Wealth on Instagram for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-techniques-for-reviving-desktop-menus/"><u>Unveiling Techniques for Reviving Desktop Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-volume-mixer-explained-and-activated-steps/"><u>Windows 11'S Volume Mixer Explained and Activated Steps</u></a></li>
</ul></div>

