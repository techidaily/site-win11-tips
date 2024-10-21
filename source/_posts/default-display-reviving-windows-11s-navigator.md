---
title: "Default Display: Reviving Windows 11'S Navigator"
date: 2024-10-20T00:49:35.076Z
updated: 2024-10-21T00:36:33.669Z
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
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-comprehensively-understanding-ios-visual-record-function/"><u>[New] Comprehensively Understanding IO’s Visual Record Function</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-comprehensive-guide-to-rl-streaming-setup/"><u>[Updated] 2024 Approved Comprehensive Guide to RL Streaming Setup</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-top-10-road-racers-playlist/"><u>[Updated] 2024 Approved Top 10 Road Racers Playlist</u></a></li>
<li><a href="https://buynow-help.techidaily.com/boost-your-smartphone-reception-elite-signal-amplifiers-ranked/"><u>Boost Your Smartphone Reception: Elite Signal Amplifiers Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-invisible-button-on-taskview-bar/"><u>Crafting an Invisible Button on TaskView Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-creating-slideshow-magic-and-spot-corrections-in-windows-11-photos/"><u>Expert Tips for Creating Slideshow Magic and Spot Corrections in Windows 11 Photos</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-amd-rx-6800-xt-up-to-date-with-latest-windows-compatible-drivers/"><u>Get Your AMD RX 6800 XT Up-to-Date with Latest Windows Compatible Drivers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-bypass-apple-iphone-6s-plus-passcode-easily-video-inside-by-drfone-ios/"><u>How to Bypass Apple iPhone 6s Plus Passcode Easily Video Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-new-wins-setbacks-to-standard-users/"><u>Navigating Through New Wins: Setbacks to Standard Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/straightforward-stories-essence/"><u>Straightforward Stories' Essence</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-12-prominent-oppo-reno-10-proplus-5g-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Oppo Reno 10 Pro+ 5G Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-netgear-nighthawk-x6-wi-fi-expansion-unit-a-full-feature-breakdown/"><u>Ultimate Guide to Netgear Nighthawk X6 Wi-Fi Expansion Unit - A Full Feature Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-quick-keyboard-shortcut-guide/"><u>Windows 11: Quick Keyboard Shortcut Guide</u></a></li>
</ul></div>

