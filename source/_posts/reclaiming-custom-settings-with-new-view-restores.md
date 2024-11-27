---
title: Reclaiming Custom Settings with New View Restores
date: 2024-11-24T16:21:47.966Z
updated: 2024-11-27T18:18:11.775Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Custom Settings with New View Restores
excerpt: This Article Describes Reclaiming Custom Settings with New View Restores
keywords: Reclaim Custom Configs,New View Resets,Setting Overhaul Guide,View Preservation Tips,Restore Settings Ease,Custom Config Redoing,View Update Steps
thumbnail: https://thmb.techidaily.com/d156dc661c6f6baa9eb3b5c3ab4152f8f8f4fcdc0dbe084557e36eab0ab2db64.jpeg
---

## Reclaiming Custom Settings with New View Restores

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-videos.techidaily.com/new-ace-your-youtube-livestreams-mastering-broadcast-techniques-using-wirecast/"><u>[New] Ace Your Youtube Livestreams Mastering Broadcast Techniques Using WireCast</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-core-concepts-in-digital-animation/"><u>[New] Core Concepts in Digital Animation</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-10-no-cost-image-servers-always-preserve-your-pics/"><u>[New] Top 10 No-Cost Image Servers, Always Preserve Your Pics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deactivating-cortana-service-in-win11/"><u>Deactivating Cortana Service in Win11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-to-download-csr-bluetooth-driver-software-now-online/"><u>Easy-to-Download CSR Bluetooth Driver Software Now Online!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-invisible-results-from-windows-1011s-search-feature/"><u>Fixing Invisible Results From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/from-novice-to-pro-learn-how-to-take-perfect-screenshots-on-any-computer/"><u>From Novice to Pro: Learn How to Take Perfect Screenshots on Any Computer</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-constant-crashes-in-sony-vegas-video-editing-software-expert-advice/"><u>How to Fix Constant Crashes in Sony Vegas Video Editing Software: Expert Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-for-spotify-error-on-frozen-windows-11-devices/"><u>Immediate Fixes for Spotify Error on Frozen Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-microsoft-store-glitches-via-server-corrections-on-win-1111/"><u>Overcoming Microsoft Store Glitches via Server Corrections on Win 11/11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/premium-inflatable-hot-tub-picks-elevate-your-relaxation-game-cnet/"><u>Premium Inflatable Hot Tub Picks : Elevate Your Relaxation Game | CNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-win11s-application-dimensions/"><u>Tailoring Win11's Application Dimensions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-the-preferred-pdf-application-in-windows/"><u>Tweaking the Preferred PDF Application in Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-guide-to-overcome-recurring-outlook-program-hiccups/"><u>Ultimate Guide to Overcome Recurring Outlook Program Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-quick-access-for-the-snipping-tool-on-win-11/"><u>Utilizing Quick Access for the Snipping Tool on Win 11</u></a></li>
</ul></div>

