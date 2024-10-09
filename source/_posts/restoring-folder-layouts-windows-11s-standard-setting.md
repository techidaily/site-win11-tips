---
title: "Restoring Folder Layouts: Windows 11'S Standard Setting"
date: 2024-10-04T01:19:39.266Z
updated: 2024-10-08T16:55:01.462Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Restoring Folder Layouts: Windows 11'S Standard Setting"
excerpt: "This Article Describes Restoring Folder Layouts: Windows 11'S Standard Setting"
keywords: Win11FolderLayoutReset,Windows11DefaultSetting,DefaultFoldersWindows11,RestoreWin11Layouts,FolderLayoutRestoreWin11,LayoutStandardSettingsWin11,11WindowsFolderReformat
thumbnail: https://thmb.techidaily.com/95716cb061a5dae526d57500a8951c520e1cad5f6661b79a6595a67d8bfbaed5.jpg
---

## Restoring Folder Layouts: Windows 11'S Standard Setting

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

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-efficient-techniques-unveiled-mastering-screen-recordings-with-showmore/"><u>[New] 2024 Approved Efficient Techniques Unveiled Mastering Screen Recordings with ShowMore</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-essential-tips-for-designing-engaging-fb-video-covers-for-2024/"><u>[New] Essential Tips for Designing Engaging FB Video Covers for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-quick-adjustment-invert-playback-on-vlc-interface-for-2024/"><u>[New] Quick Adjustment Invert Playback on VLC Interface for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-acoustic-additions-for-your-chat-status/"><u>[Updated] Acoustic Additions for Your Chat Status</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exceptional-appraisal-and-other-choices/"><u>[Updated] Exceptional Appraisal & Other Choices</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-fb-link-mastery-8-powerful-free-extractor-tools/"><u>2024 Approved FB Link Mastery 8 Powerful FREE Extractor Tools</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/altering-meeting-screens-in-microsoft-teams/"><u>Altering Meeting Screens in Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-options-boot-into-safe-mode-with-6-steps-in-windows-11/"><u>Convenient Options: Boot Into Safe Mode with 6 Steps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-to-overcome-common-windows-app-errors/"><u>Efficient Fixes to Overcome Common Windows App Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-silent-speech-problems-for-gamers-playing-on-pc/"><u>Fixing Silent Speech Problems for Gamers Playing on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-adjust-admin-managed-chromium-and-microsoft-edge-in-windows/"><u>Guidelines to Adjust Admin-Managed Chromium & Microsoft Edge in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-geforce-now-error-xc0f1103f-in-11/"><u>How to Rectify GeForce Now Error Xc0f1103f in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-device-latency-zerodxgierror-in-win11-pcs/"><u>How to Tackle Device Latency ZeroDXGIError in Win11 PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-shatter-the-scribbles-pure-videos-from-tiktok/"><u>In 2024, Shatter the Scribbles Pure Videos From TikTok</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlock-the-potential-of-photography-with-adobe-motion-blur/"><u>In 2024, Unlock the Potential of Photography with Adobe Motion Blur</u></a></li>
<li><a href="https://win11-tips.techidaily.com/novices-companion-to-windows-accessibility-features/"><u>Novice's Companion to Windows Accessibility Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-old-cursor-color-schemes-tips/"><u>Reviving Old Cursor Color Schemes: Tips</u></a></li>
</ul></div>

