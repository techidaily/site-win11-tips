---
title: Reviving Typical Directory Display Order in Win11
date: 2024-07-12T16:54:38.280Z
updated: 2024-07-13T16:54:38.281Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving Typical Directory Display Order in Win11
excerpt: This Article Describes Reviving Typical Directory Display Order in Win11
keywords: Win11 Directory Order Revival,Directory Display Layout Win11,Win11 UI Update,Reimagined Directory View,Win11 Display Adjustment,Win11 Typical Arrangement,Renewing Windows 11 DIR,Win11 Dir Relaunch,Win11 DIR Layout Update,Windows 11 UI Revamp,Win11 Display Refresh,Optimize Win11 DIR,Renewed Win11 Order,Win11 Directory Reimage
thumbnail: https://thmb.techidaily.com/e937c769751b4b8235d825da190a8de514c18ce6c728b4bc630fa21c8db2efdc.jpg
---

## Reviving Typical Directory Display Order in Win11

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
<li><a href="https://win11-tips.techidaily.com/deciph-written-as-a-dialogue-between-two-characters-user-and-assistant-in-an-online-forum-setting-discussing-the-topic-of-what-is-aggregatorhostexe-on-windo37/"><u>Deciph Written as a Dialogue Between Two Characters (User and Assistant) in an Online Forum Setting Discussing the Topic of What Is AggregatorHost.exe on Windows, and Is It Safe?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-0x800f0845-from-windows-updates/"><u>Eradicating 0X800f0845 From Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-resolving-outlook-errors-on-windows/"><u>Expert Tips: Resolving Outlook Errors on Windows</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-masterclass-in-making-engaging-video-lessons-your-step-by-step-guide-for-youtube/"><u>[Updated] 2024 Approved  Masterclass in Making Engaging Video Lessons  Your Step-by-Step Guide for YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-computing-the-ai-enhanced-windows/"><u>Transforming Computing: The AI-Enhanced Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-restore-your-microsoft-store-registrations-win-11/"><u>Fix and Restore Your Microsoft Store Registrations (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-overcome-response-incorrect-message/"><u>Easily Overcome Response Incorrect Message</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-ranking-the-best-lego-stop-motion-producers/"><u>Updated Ranking the Best Lego Stop Motion Producers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-online-journey-the-guide-to-win-net-health/"><u>Uninterrupted Online Journey: The Guide to Win Net Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-secure-your-windows-environment-with-these-4-tactics/"><u>Access Denied: Secure Your Windows Environment with These 4 Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directives-for-managing-setup-service-state-in-windows/"><u>Directives for Managing Setup Service State in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-preparedness-generate-boot-media-in-three-steps/"><u>Windows 11 Preparedness: Generate Boot Media in Three Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-high-contrast-setting-in-windows/"><u>Turn Off High Contrast Setting in Windows</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-oppo-k11x-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Oppo K11x without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-missing-device-camera-in-windows-11/"><u>Steps to Correct Missing Device: Camera in Windows 11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-want-to-clone-voices-in-real-time-explore-these-github-repositories/"><u>New Want to Clone Voices in Real-Time? Explore These GitHub Repositories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-assurance-verify-windows-equipment-before-calling/"><u>Audio Visual Assurance: Verify Windows Equipment Before Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-search-on-windows-11-the-top-5-must-knows/"><u>Elevating Search on Windows 11: The Top 5 Must-Knows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-windows-solutions-for-multimedia-tasks/"><u>Superior Windows Solutions for Multimedia Tasks</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-discover-the-next-wave-of-effective-facebook-ad-techniques/"><u>2024 Approved  Discover the Next Wave of Effective Facebook Ad Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-a-three-dimensional-soundscape-in-windows-11/"><u>Achieving a Three-Dimensional Soundscape in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-playnite-integrating-virtual-game-archives/"><u>Winning Playnite: Integrating Virtual Game Archives</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-a-filmmakers-guide-to-blending-sound-and-visuals-with-magix-pro-software/"><u>New In 2024, A Filmmakers Guide to Blending Sound and Visuals with Magix Pro Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-switch-off-microsofts-assistant/"><u>Techniques to Switch Off Microsoft's Assistant</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-social-media-power-players-face-off-will-likes-triumph-over-tiktok/"><u>[Updated] Social Media Power Players Face-Off  Will Likes Triumph over TikTok?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-lock-on-time-for-windows-users/"><u>Automating Lock-On Time for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-and-engage-with-10-key-network-settings-in-winos/"><u>Explore and Engage with 10 Key Network Settings in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-taskbar-attachment-techniques/"><u>Windows 11 Taskbar Attachment Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-stronger-case-for-windows-11-over-macos/"><u>The Stronger Case for Windows 11 over MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directly-engage-with-images-in-windows-explorer/"><u>Directly Engage with Images in Windows Explorer</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harnessing-windows-10-tools-for-exquisite-video-editing/"><u>In 2024, Harnessing Windows 10 Tools for Exquisite Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-storage-demands-on-windows-os/"><u>Decoding the Storage Demands on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swashbucklers-overcome-delayed-gameplay-in-sw-bf2/"><u>Swift Swashbucklers: Overcome Delayed Gameplay in SW BF2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discreet-deletion-of-email-after-signing-in-windows/"><u>Discreet Deletion of Email After Signing In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-printer-functionality-within-edge-guard/"><u>Triggering Printer Functionality Within Edge Guard</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-on-iphone-15-plus-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out On iPhone 15 Plus How to Bypass?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-vivo-y02t-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Vivo Y02T</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/6-ways-to-mimic-professional-filming-gears/"><u>6 Ways to Mimic Professional Filming Gears</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-s24-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy S24 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-ultimate-guide-to-slow-motion-video-playback-on-vlc/"><u>Updated The Ultimate Guide to Slow Motion Video Playback on VLC</u></a></li>
</ul></div>
