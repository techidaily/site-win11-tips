---
title: Revitalizing Window's Folder Display Methods
date: 2024-10-06T16:53:49.388Z
updated: 2024-10-09T03:06:35.460Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://electronicx.pxf.io/c/5597632/1167086/14483" target="_top" id="1167086">
  <img src="//a.impactradius-go.com/display-ad/14483-1167086" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1167086/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484940/16446" target="_top" id="1484940">
  <img src="//a.impactradius-go.com/display-ad/16446-1484940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484940/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-share-your-stories-with-lush-soundtracks/"><u>[New] 2024 Approved Share Your Stories with Lush Soundtracks</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-17-best-lights-and-lighting-equipment-for-youtube-videos/"><u>[Updated] 2024 Approved 17 Best Lights and Lighting Equipment for YouTube Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-focus-on-the-essentials-the-compreenas-for-removing-youtube-channels/"><u>[Updated] 2024 Approved Focus on the Essentials The Compreenas for Removing Youtube Channels</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-smooth-sailing-in-transforming-ppt-slides-into-videos/"><u>2024 Approved Smooth Sailing in Transforming PPT Slides Into Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-eye-candy-for-digital-performances/"><u>2024 Approved Ultimate Eye Candy for Digital Performances</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enrich-windows-11-notepad-through-synergistic-tech/"><u>Enrich Windows 11 Notepad Through Synergistic Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-page-not-rendered-in-ms-marketplace/"><u>How to Rectify Page Not Rendered in MS Marketplace</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-establishing-an-individual-identity-on-youtube-platform/"><u>In 2024, Establishing an Individual Identity on YouTube Platform</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-the-ultimate-productivity-playlist-podcast-inspired-tasks/"><u>In 2024, The Ultimate Productivity Playlist Podcast-Inspired Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-this-non-adobe-windows-errors/"><u>Overcoming 'This Non-Adobe' Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-file-transfers-on-win11-pcs-1/"><u>Strategies to Improve File Transfers on WIN11 PCs (1)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-dusk-drawers-of-microsoft-paint/"><u>The Dusk Drawers of Microsoft Paint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-insights-what-patch-wxx-brings-to-windows-11/"><u>Upgrade Insights: What Patch W.x.x Brings to Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Motorola Edge 40 | Dr.fone</u></a></li>
</ul></div>

