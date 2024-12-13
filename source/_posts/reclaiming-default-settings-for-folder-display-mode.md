---
title: Reclaiming Default Settings for Folder Display Mode
date: 2024-12-06T22:22:02.155Z
updated: 2024-12-12T16:32:38.334Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Default Settings for Folder Display Mode
excerpt: This Article Describes Reclaiming Default Settings for Folder Display Mode
keywords: Reclaim Folder Views,Reset Folders Display,Revise Folder Mode,Change Folder Display,Fix Default FolderView,Update Folder Settings,Modify Directory ViewMode
thumbnail: https://thmb.techidaily.com/3269c858221e8ab75b91d65fc2cbdc3bf0d972fb510d01ae54b3ad8d22470d02.jpg
---

## Reclaiming Default Settings for Folder Display Mode

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-top-fbx-capture-tools-beyond-traditional-recorders-for-2024/"><u>[New] Top FBX Capture Tools Beyond Traditional Recorders for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-fresh-perspectives-on-logo-design-for-podcast-brands/"><u>[Updated] Fresh Perspectives on Logo Design for Podcast Brands</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-converting-videos-to-gifs-online-the-ultimate-youtube-resource/"><u>[Updated] In 2024, Converting Videos to Gifs Online The Ultimate YouTube Resource</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-turning-horizons-into-heights-uploading-videos-to-igtv/"><u>2024 Approved Turning Horizons Into Heights Uploading Videos to IGTV</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/editorial-powerhouses-free-for-web-enthusiasts-for-2024/"><u>Editorial Powerhouses Free for Web Enthusiasts for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/get-your-video-dimensions-spot-on-for-instagram-sharing-for-2024/"><u>Get Your Video Dimensions Spot-On for Instagram Sharing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-corrections-for-failing-windows-batch-jobs/"><u>Mastering Corrections for Failing Windows Batch Jobs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-call-recording-a-step-by-step-guide/"><u>Mastering Windows Call Recording: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-and-personalizing-fn-keys-for-wins-pcs/"><u>Optimizing and Personalizing FN Keys for Wins PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-common-errors-to-restore-functionality-of-thaumaturge-application-on-personal-computers/"><u>Solving Common Errors to Restore Functionality of Thaumaturge Application on Personal Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-the-start-menu-initiate-file-explorer-via-onedrive-shortcuts/"><u>Tailoring the Start Menu: Initiate File Explorer via OneDrive Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-comprehensible-guide-to-winning-at-ps1-in-windows-duckstation-way/"><u>The Comprehensible Guide to Winning at PS1 in Windows - Duckstation Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-imessage-on-your-desktop-or-laptop/"><u>Unlocking the Power of iMessage on Your Desktop or Laptop</u></a></li>
</ul></div>

