---
title: Realigning Windows 11'S File Order Preferences
date: 2024-06-25T16:54:49.840Z
updated: 2024-06-26T16:54:49.840Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Realigning Windows 11'S File Order Preferences
excerpt: This Article Describes Realigning Windows 11'S File Order Preferences
keywords: Win11 File Organize,Realign W11 Files,Windows 11 Setup,Change W11 Folder,Rearrange W11 Order,New W11 Sorting,W11 File Arrangement
thumbnail: https://thmb.techidaily.com/d2d94c4e77b77ed0c83b7c2ce10b6132329d863043aff159270d3e923d41f323.jpg
---

## Realigning Windows 11'S File Order Preferences

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
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on [how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will [open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.
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
<li><a href="https://win11-tips.techidaily.com/effortless-cleaning-for-a-functional-windows-11-space/"><u>Effortless Cleaning for a Functional Windows 11 Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-power-of-placement-comments-in-windows-explorer/"><u>Unveiling the Power of Placement Comments in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-disabled-windows-application/"><u>How to Enable Disabled Windows Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directives-for-managing-setup-service-state-in-windows/"><u>Directives for Managing Setup Service State in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-update-files-are-missing-error-0x80070003-on-windows/"><u>How to Fix the Update Files Are Missing Error 0X80070003 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/legacy-tech-lifeline-atlasos-revival-plan/"><u>Legacy Tech Lifeline: AtlasOS Revival Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-stop-motion-animation-on-the-cloud-a-step-by-step-guide-and-alternatives-for-2024/"><u>New Stop Motion Animation on the Cloud A Step-by-Step Guide and Alternatives for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-time-saving-hacks-for-recording-instagram-stories/"><u>[New] 2024 Approved  Time-Saving Hacks for Recording Instagram Stories</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-the-essential-guide-to-recording-dynamic-digital-audio-broadcasts/"><u>2024 Approved The Essential Guide to Recording Dynamic Digital Audio Broadcasts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-essential-9-gif-recipes-for-capturing-windows-graphics-fun/"><u>In 2024, Essential 9 GIF Recipes for Capturing Windows Graphics Fun</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>In 2024, Apply These Techniques to Improve How to Detect Fake GPS Location On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-compre-written-guide-on-incorporating-markup-features-in-youtube/"><u>2024 Approved  Compre Written Guide on Incorporating Markup Features in YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-instagram-video-editor-how-to-edit-instagram-video/"><u>[Updated] 2024 Approved  Instagram Video Editor  How to Edit Instagram Video</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-techniques-for-quieting-breeze-induced-noise-in-multiplatform-videos/"><u>Updated 2024 Approved Techniques for Quieting Breeze-Induced Noise in Multiplatform Videos</u></a></li>
</ul></div>
