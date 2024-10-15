---
title: Revitalizing Window's Folder Display Methods
date: 2024-10-07T18:38:12.939Z
updated: 2024-10-15T04:53:34.350Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revitalizing Window's Folder Display Methods
excerpt: This Article Describes Revitalizing Window's Folder Display Methods
keywords: Revitalize FileViewer,FolderDisplayTechUpdate,EnhancedFolderView,WindowsFoldersRenewed,RefreshWindowNav,ImprovedFileDisp,ModernFolderShowcase
thumbnail: https://thmb.techidaily.com/fb9800d0908e1be810fcc7b3cec05fac87c5747d21be749110f5088c0bdb4490.jpg
---

## Revitalizing Window's Folder Display Methods

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997630/19272" target="_top" id="1997630">
  <img src="//a.impactradius-go.com/display-ad/19272-1997630" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997630/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047361/19272" target="_top" id="2047361">
  <img src="//a.impactradius-go.com/display-ad/19272-2047361" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997662/19272" target="_top" id="1997662">
  <img src="//a.impactradius-go.com/display-ad/19272-1997662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997662/19272" style="position:absolute;visibility:hidden;" border="0" />
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

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-audiophiles-dilemma-podcast-or-youtube-dominance-for-2024/"><u>[New] Audiophile's Dilemma Podcast or YouTube Dominance for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-no-limit-video-recorders-the-best-12-picks/"><u>[New] In 2024, No Limit Video Recorders - The Best 12 Picks</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-free-world-quest-the-elite-10-mmo-rankings/"><u>[Updated] Free World Quest The Elite 10 MMO Rankings</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-the-evolved-examination-of-sony-bdp-s3700/"><u>2024 Approved The Evolved Examination of Sony BDP-S3700</u></a></li>
<li><a href="https://vp-tips.techidaily.com/beginning-film-making-download-previews/"><u>Beginning Film Making Download Previews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-windows-hello-fingerprint-sign-in-process/"><u>Configuring Windows Hello Fingerprint Sign-In Process</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-oppo-reno-11f-5g-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Oppo Reno 11F 5G PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-use-phone-clone-to-migrate-your-oppo-a78-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Use Phone Clone to Migrate Your Oppo A78 Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-media-player-on-pc-a-step-by-step-guide/"><u>Launching Windows Media Player on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-widest-use-of-windows-pcs-through-advanced-tdarr-integration/"><u>Make Widest Use of Windows PCs Through Advanced Tdarr Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masked-management-eliminate-start-menus-power-icon/"><u>Masked Management: Eliminate Start Menu's Power Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-your-microsoft-store-credentials/"><u>Regain Your Microsoft Store Credentials</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-tutorial-removing-your-likes-from-the-entire-spotify-playlist/"><u>Step-by-Step Tutorial: Removing Your Likes From the Entire Spotify Playlist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-rufus-and-tpmsecure-boot-in-win11/"><u>The Ultimate Guide to Rufus and TPM/Secure Boot in Win11</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-hub-in-depth-reviews-and-guides-by-toms-hardware/"><u>Tom's Tech Hub: In-Depth Reviews and Guides by Tom's Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-key-disparities-between-in-store-and-distant-windows-installs/"><u>Understanding Key Disparities Between In-Store & Distant Windows Installs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-credentials-made-simple-the-ultimate-list-of-11-access-methods/"><u>Win11 Credentials Made Simple: The Ultimate List of 11 Access Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-clean-canvas-the-ad-free-promise/"><u>Windows 11'S Clean Canvas: The Ad-Free Promise</u></a></li>
</ul></div>

