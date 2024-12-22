---
title: Reverting Windows Viewer to Original Arrangement
date: 2024-12-14T20:14:00.464Z
updated: 2024-12-21T21:21:32.172Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reverting Windows Viewer to Original Arrangement
excerpt: This Article Describes Reverting Windows Viewer to Original Arrangement
keywords: Windows Default View,Restore Windows Layout,Renew Windows Display,Return Windows Settings,Fix Window Layouts,Reset Windows Panel,Revert Windows Screen
thumbnail: https://thmb.techidaily.com/6d87b1c3f35bd086cb57f3daa2bccf1c889bbcea516bdcb3d44c7df48b1c3e3d.jpg
---

## Reverting Windows Viewer to Original Arrangement

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-time-travel-with-your-phones-videos/"><u>[Updated] 2024 Approved Time Travel with Your Phone's Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-the-ultimate-tutorial-on-editing-youtube-videos/"><u>[Updated] In 2024, The Ultimate Tutorial on Editing YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-mc-lan-troubles-7-fixes-for-windows-users/"><u>Decoding MC LAN Troubles: 7 Fixes for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-desktop-space-display-gmail-on-pc-taskbar/"><u>Enhancing Desktop Space: Display Gmail on PC Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-cleanup-indispensable-windows-programs-for-removal/"><u>Essential Cleanup: Indispensable Windows Programs for Removal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-efficiently-pinpointing-hdd-or-ssd-on-your-computer/"><u>Expert Advice: Efficiently Pinpointing HDD or SSD on Your Computer</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-gionee-f3-pro-frp-bypass-by-drfone-android/"><u>In 2024, About Gionee F3 Pro FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-cpu-load-wmi-worker-fixes/"><u>Lowering Cpu Load: WMI Worker Fixes</u></a></li>
<li><a href="https://fox-access.techidaily.com/masterful-cloud-keeping-best-service-picks/"><u>Masterful Cloud Keeping Best Service Picks</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-the-fixes-resolving-roblox-launch-failures/"><u>Mastering the Fixes: Resolving Roblox Launch Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/post-cortana-era-brings-4-enhanced-windows-features/"><u>Post-Cortana Era Brings 4 Enhanced Windows Features</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016713890-pubg-communication-breakdown-solve-your-voice-chat-dilemmas-with-these-simple-steps/"><u>PUBG Communication Breakdown? Solve Your Voice Chat Dilemmas with These Simple Steps</u></a></li>
<li><a href="https://buynow-help.techidaily.com/sonys-budget-camcorder-high-image-quality-wins/"><u>Sony's Budget Camcorder: High Image Quality Wins</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-google-pixel-5-examined-where-budget-meets-high-end-in-a-smartphone-review/"><u>The Google Pixel 5 Examined: Where Budget Meets High-End in a Smartphone Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/untethered-accessibility-windows-edition-of-onedrive/"><u>Untethered Accessibility: Windows Edition of OneDrive</u></a></li>
</ul></div>

