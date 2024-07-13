---
title: Resolving Default Path Problems on Windows 10/11
date: 2024-07-12T16:41:02.318Z
updated: 2024-07-13T16:41:02.318Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Default Path Problems on Windows 10/11
excerpt: This Article Describes Resolving Default Path Problems on Windows 10/11
keywords: Windows Default Fix Guide,Win10/11 Path Resolution,Default Route Correction,WinOS 10/11 Problems,Navigate OS Paths Issue,Fix Windows Explorer Error,System Directories Solution
thumbnail: https://thmb.techidaily.com/b707c0511382e78c7bbc2631c8c2ac749bfdb8b7dcef137c48ff3983d7a66e67.jpg
---

## Resolving Default Path Problems on Windows 10/11

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/in-2024-acclaimed-top-15-android-virtualization-apps-for-developers/"><u>In 2024, Acclaimed Top 15 Android Virtualization Apps for Developers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-proven-strategies-to-solve-windows-update-woes/"><u>10 Proven Strategies to Solve Windows Update Woes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-cricket-apple-iphone-6s-for-free-by-drfone-ios/"><u>How To Unlock Cricket Apple iPhone 6s for Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-tactics-for-control-panel-entry/"><u>10 Essential Tactics for Control Panel Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719241162172-update-drivers-make-sure-your-graphics-card-drivers-are-up-to-date-for-optimal-performance/"><u>Update Drivers: Make Sure Your Graphics Card Drivers Are up to Date for Optimal Performance.</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-your-roadmap-to-acquiring-facebooks-esteemed-verification-for-2024/"><u>[Updated] Your Roadmap to Acquiring Facebook’s Esteemed Verification for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-beginners-guide-capturing-youtube-videos-as-screencasts-without-payment/"><u>[New] In 2024, Beginner's Guide  Capturing YouTube Videos as Screencasts Without Payment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719204304616-gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-methods-to-resuscitate-windows-system-backup/"><u>13 Methods to Resuscitate Windows System Backup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-10-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 10 Blue Screen Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719225198037-epic-launcher-removal-woes-in-windows-11-fix-now/"><u>Epic Launcher Removal Woes in Windows 11: Fix Now</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/best-10-spotify-recorders/"><u>Best 10 Spotify Recorders</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/top-8-audio-capture-tools-for-live-broadcasts-and-recordings/"><u>Top 8 Audio Capture Tools for Live Broadcasts and Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255310971-jump-over-compatibility-obstacles-with-these-simple-fixes/"><u>Jump Over Compatibility Obstacles with These Simple Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-display-settings-in-windows-11/"><u>10 Ways to Open the Display Settings in Windows 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/windows-11-essential-mastery-guide-for-2024/"><u>Windows 11  Essential Mastery Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-system-restore-on-windows-11/"><u>11 Ways to Open System Restore on Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/mastering-aspect-ratio-in-final-cut-pro-essential-skills-for-video-editors-for-2024/"><u>Mastering Aspect Ratio in Final Cut Pro Essential Skills for Video Editors for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-iphoneipad-masterclass-crafting-engaging-interview-and-exploration-podcasts/"><u>[New] IPhone/iPad Masterclass  Crafting Engaging Interview and Exploration Podcasts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-effective-procedures-for-screen-capturing-live-telecasts/"><u>[New] In 2024, Effective Procedures for Screen Capturing Live Telecasts</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-there-we-introduce-you-3-simple-options-for-recording-video-games-with-ease/"><u>In 2024, There We Introduce You 3 Simple Options for Recording Video Games with Ease</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-find-your-perfect-match-with-these-best-5-iphone-pods/"><u>In 2024, Find Your Perfect Match with These Best 5 iPhone Pods</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-top-10-digital-audio-workstation-tools-free-vs-paid-options/"><u>Updated Top 10 Digital Audio Workstation Tools Free vs Paid Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255690388-pro-tips-to-improve-your-snip-and-sketch-screenshot-experience/"><u>Pro Tips to Improve Your Snip & Sketch Screenshot Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-the-control-panel-on-windows/"><u>11 Ways to Open the Control Panel on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-fix-a-cursor-when-it-moves-on-its-own-in-windows-11/"><u>10 Ways to Fix a Cursor When It Moves On Its Own in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-remote-desktop-connection-tool-in-windows-11/"><u>10 Ways to Open the Remote Desktop Connection Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-tips-to-fix-windows-system-restore/"><u>13 Tips to Fix Windows System Restore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-simplified-techniques-to-winrm-tool/"><u>10 Simplified Techniques to WinRM Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-fast-passes-to-the-control-settings-hub/"><u>11 Fast Passes to the Control Settings Hub</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-realme-c55-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-tips-for-restoring-fbm-functionality-on-desktop/"><u>10 Key Tips for Restoring FBM Functionality on Desktop</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-creative-potential-access-free-sfx-for-2024/"><u>Unlock Creative Potential, Access Free SFX for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719233153106-eliminate-printer-problems-fast-win11-fixed/"><u>Eliminate Printer Problems Fast: Win11 Fixed!</u></a></li>
</ul></div>
