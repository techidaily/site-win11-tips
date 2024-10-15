---
title: "Restoring Folder Layouts: Windows 11'S Standard Setting"
date: 2024-10-10T02:16:05.258Z
updated: 2024-10-15T01:23:33.502Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080328/19272" target="_top" id="2080328">
  <img src="//a.impactradius-go.com/display-ad/19272-2080328" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080328/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148773/18498" target="_top" id="2148773">
  <img src="//a.impactradius-go.com/display-ad/18498-2148773" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148773/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-capturing-live-gaming-decide-on-obsshadowplay-for-2024/"><u>[New] Capturing Live Gaming - Decide on OBS/ShadowPlay for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-hidden-paths-to-pristine-stock-photography/"><u>[New] The Hidden Paths to Pristine Stock Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-executable-format-pe/"><u>Exploring Windows Executable Format (PE)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-make-word-open-email-attachments-in-read-only-by-default/"><u>Guidelines to Make Word Open Email Attachments in Read-Only by Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disguise-taskbars-search-in-windows-11/"><u>How To Disguise Taskbar's Search in Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-google-pixel-7a-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Google Pixel 7a Back to Operation | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-video-mastery-on-instagram-tips-and-tricks/"><u>In 2024, Video Mastery on Instagram Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-look-for-task-managers-launch-screen-win11/"><u>New Look for Task Manager's Launch Screen (Win11)</u></a></li>
<li><a href="https://blog-min.techidaily.com/powerful-dvd-unlocker-securely-extract-convert-and-transfer-your-disc-content-fast-with-gpu-boosted-performance-in-winx-dvd-ripper-plus/"><u>Powerful DVD Unlocker: Securely Extract, Convert & Transfer Your Disc Content Fast With GPU-Boosted Performance in WinX DVD Ripper Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-tech-top-laptops-ifa-2023/"><u>Trailblazing Tech: Top Laptops IFA 2023</u></a></li>
<li><a href="https://blog-min.techidaily.com/verzerrte-dvd-videos-retten-wie-man-mit-handbrake-unter-windows-11-erfolgreich-korrigiert/"><u>Verzerrte DVD-Videos Retten: Wie Man Mit HandBrake Unter Windows 11 Erfolgreich Korrigiert</u></a></li>
<li><a href="https://win-able.techidaily.com/warframe-lag-problems-now-fixed-and-smooth-gaming-experience/"><u>Warframe Lag Problems - Now Fixed and Smooth Gaming Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ip-port-inspection-strategies/"><u>Windows IP Port Inspection Strategies</u></a></li>
</ul></div>

