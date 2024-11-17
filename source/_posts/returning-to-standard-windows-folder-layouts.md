---
title: Returning to Standard Windows Folder Layouts
date: 2024-11-12T16:28:23.795Z
updated: 2024-11-17T19:30:28.668Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Returning to Standard Windows Folder Layouts
excerpt: This Article Describes Returning to Standard Windows Folder Layouts
keywords: Windows Default Layout Revival,Win Folder Standard Restore,Windows Ordinary Folders,Normalize Windows Paths,Fix Windows Folder Structure,Classic Windows Nesting,Revert Windows File Orchestration
thumbnail: https://thmb.techidaily.com/7ca1823a541bb8f1b1b4e3f36dc533291122ea53e71344224f2ca3a62defe8ec.jpg
---

## Returning to Standard Windows Folder Layouts

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
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934292/19272" target="_top" id="1934292">
  <img src="//a.impactradius-go.com/display-ad/19272-1934292" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934292/19272" style="position:absolute;visibility:hidden;" border="0" />
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
6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094429/7443" target="_top" id="2094429">
  <img src="//a.impactradius-go.com/display-ad/7443-2094429" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094429/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-tips.techidaily.com/new-boost-communication-capabilities-from-skype-to-zoom/"><u>[New] Boost Communication Capabilities From Skype to Zoom</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-nixing-the-green-glow-youtubes-mac-solution-manual/"><u>[New] Nixing the Green Glow YouTube's Mac Solution Manual</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-ultimate-budget-friendly-online-face-offs/"><u>[Updated] Ultimate Budget-Friendly Online Face-Offs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-zdsofts-edge-masterful-video-capture-analysis/"><u>2024 Approved ZDSoft's Edge Masterful Video Capture Analysis</u></a></li>
<li><a href="https://techtrends.techidaily.com/comment-corriger-le-desequilibre-aspectiel-dans-la-conversion-handbrake-vob-en-mp4/"><u>Comment Corriger Le Déséquilibre Aspectiel Dans La Conversion HandBrake VOB en MP4?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-your-clock-is-aheadbehind-error-in-chrome-for-windows/"><u>How to Fix the Your Clock Is Ahead/Behind Error in Chrome for Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-huawei-nova-y71-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Huawei Nova Y71 Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-steps-to-tackle-windows-activation-problem-code-0x803f700f/"><u>Key Steps to Tackle Windows Activation Problem Code 0X803F700f</u></a></li>
<li><a href="https://win-extraordinary.techidaily.com/moving-your-boot-volume-guide-for-transferring-system-reserved-across-drives-on-windows-pcs/"><u>Moving Your Boot Volume: Guide for Transferring 'System Reserved' Across Drives on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-non-opening-windows-command-prompt-woes/"><u>Navigating Non-Opening Windows Command Prompt Woes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-access-barriers-in-windows-a-powershell-solution/"><u>Overcoming Access Barriers in Windows: A PowerShell Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-windows-11-login-problems/"><u>Overcoming Common Windows 11 Login Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-extraneous-window-notifications/"><u>Preventing Extraneous Window Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-pc-fixes-for-a-stalled-windows-updates/"><u>Revive Your PC: Fixes for a Stalled Windows Updates</u></a></li>
<li><a href="https://techtrends.techidaily.com/solving-androids-wireless-security-issues-a-guide/"><u>Solving Android's Wireless Security Issues: A Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouse-quartet-of-social-media-navigating-facebook-twitter-instagram-and-youtube/"><u>The Powerhouse Quartet of Social Media: Navigating Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unchangeable-wallpapers-made-simple-in-win11/"><u>Unchangeable Wallpapers Made Simple in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-cplusplus-distribution-its-main-purpose/"><u>Visual C++ Distribution: Its Main Purpose</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-setup-simplified-a-steam-deck-tutorial/"><u>Windows Setup Simplified: A Steam Deck Tutorial</u></a></li>
</ul></div>

