---
title: "Default Display: Reviving Windows 11'S Navigator"
date: 2024-10-11T08:58:42.975Z
updated: 2024-10-15T03:35:29.218Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Default Display: Reviving Windows 11'S Navigator"
excerpt: "This Article Describes Default Display: Reviving Windows 11'S Navigator"
keywords: Win11NaviRestore,NaviWin11Update,ReviverNaviWindows,DefaultNaviDisplay,WindowsNaviRevive,NavigatorWin11Fix,NaviWindows11Default
thumbnail: https://thmb.techidaily.com/600ab240c6c8b1ad864f3c8d1c4daad9b77c19a5afa889dc63fba4f50be8c27e.jpg
---

## Default Display: Reviving Windows 11'S Navigator

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2068433/7443" target="_top" id="2068433">
  <img src="//a.impactradius-go.com/display-ad/7443-2068433" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068433/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-realtime-game-scorekeeper/"><u>[New] In 2024, RealTime Game Scorekeeper</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-in-depth-analysis-of-best-practices-in-valheim-agriculture/"><u>[Updated] 2024 Approved In-Depth Analysis of Best Practices in Valheim Agriculture</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/defining-output-impedance-in-electronics-and-audio-systems/"><u>Defining Output Impedance in Electronics and Audio Systems</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-save-windows-spotlight-pictures-to-use-as-wallpapers-when-you-want/"><u>How to Save Windows Spotlight Pictures to Use as Wallpapers When You Want</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-canon-mx340-software-updates-for-windows-operating-systems-win-1087/"><u>Latest Canon MX340 Software Updates for Windows Operating Systems (Win 10/8/7)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-video-cutting-solutions-on-your-windows-11-system/"><u>Masterful Video Cutting Solutions on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-output-with-windows-streamlined-launcher/"><u>Maximize Output with Windows' Streamlined Launcher</u></a></li>
<li><a href="https://fox-access.techidaily.com/monitor-mastery-understanding-the-benefits-of-ultrawide-vs-uhd-4k/"><u>Monitor Mastery Understanding the Benefits of UltraWide vs UHD 4K</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-the-8-most-common-mistakes-for-beginners-to-skip/"><u>Navigating Windows 11: The 8 Most Common Mistakes for Beginners to Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-analysis-creating-and-interpreting-data/"><u>Navigating Windows Analysis: Creating & Interpreting Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-troubled-windows-11-calendars/"><u>Resetting Techniques for Troubled Windows 11 Calendars</u></a></li>
<li><a href="https://blog-min.techidaily.com/step-by-step-guide-setting-up-the-newsmaxtv-plugin-on-your-android-tv-and-streaming-gadgets/"><u>Step-by-Step Guide: Setting Up the NewsmaxTV Plugin on Your Android TV & Streaming Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-implement-without-obstacles-win11-version-22h2-update/"><u>Tactics to Implement Without Obstacles: Win11 Version 22H2 Update</u></a></li>
<li><a href="https://win-trending.techidaily.com/1728465936297-windows-10/"><u>Windows 10 で簡単なクリーンアップ - 更新ファイルを効果的に管理</u></a></li>
</ul></div>

