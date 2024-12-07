---
title: Reclaiming Custom Settings with New View Restores
date: 2024-12-04T17:28:10.389Z
updated: 2024-12-06T17:59:32.336Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-blog.techidaily.com/n-2024-comedy-chorus-satirical-song-selections/"><u>[New] In 2024, Comedy Chorus Satirical Song Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-20plus-crucial-configuration-tweaks-revealed/"><u>Enhancing Windows 11: 20+ Crucial Configuration Tweaks Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-event-viewer-not-working-in-windows-11/"><u>How to Fix the Event Viewer Not Working in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-infinix-smart-7-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Infinix Smart 7 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-mastering-lengthy-iphone-photo-captures/"><u>In 2024, Mastering Lengthy iPhone Photo Captures</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-perfecting-your-tone-techniques-for-zoom-podcast-sessions/"><u>In 2024, Perfecting Your Tone Techniques for ZOOM Podcast Sessions</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-quick-and-easy-channels-personalize-your-youtube-url-now/"><u>In 2024, Quick and Easy Channels Personalize Your YouTube URL Now</u></a></li>
<li><a href="https://tech-revival.techidaily.com/iphone-mkv/"><u>IPhone用マルチメディア再生: MKVフォーマットへの対応方法を学ぶ【第２章】</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/key-fact-5-hrams-role-high-resolution-accurate-mass-spectrometry-provides-precise-mz-values-enabling-the-distinction-of-molecular-formulas-with-high-confide75/"><u>Key Fact #5: HRAM's Role - High-Resolution Accurate Mass Spectrometry Provides Precise M/Z Values, Enabling the Distinction of Molecular Formulas with High Confidence.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-event-viewer-failures-in-windows-11/"><u>Mitigating Event Viewer Failures in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-external-monitor-offline-in-windows-systems/"><u>Overcoming External Monitor Offline in Windows Systems</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/rising-to-fame-tiktoks-most-shared-reactions/"><u>Rising to Fame TikTok's Most Shared Reactions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/risks-involved-in-ai-crafted-windows-11-codes/"><u>Risks Involved in AI-Crafted Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-circle-again-top-5-family-safe-fixes/"><u>Securing Your Circle Again: Top 5 Family Safe Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-win1011s-audacity-audio-glitches/"><u>Solving Win10/11's Audacity Audio Glitches</u></a></li>
<li><a href="https://discover-docs.techidaily.com/step-by-step-tutorial-transitioning-from-traditional-hard-drive-to-enhanced-sshd-in-windows-operating-systems-windows-11-10-8-7/"><u>Step-by-Step Tutorial: Transitioning From Traditional Hard Drive to Enhanced SSHD in Windows Operating Systems (Windows 11, 10, 8, 7)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-pre-win-11-systems-with-latest-os/"><u>Transforming Pre-Win 11 Systems with Latest OS</u></a></li>
</ul></div>

