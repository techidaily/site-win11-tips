---
title: Correcting Erroneous OneDrive Tags in Windows File System
date: 2024-07-12T17:26:22.704Z
updated: 2024-07-13T17:26:22.704Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Erroneous OneDrive Tags in Windows File System
excerpt: This Article Describes Correcting Erroneous OneDrive Tags in Windows File System
keywords: Correct Drives Filename Errors,Fix OneDrive Tag Issues,Unify File Titles Across OS,Realign Windows Drive Labels,Rectify Tags in OneDrive Files,Adjust Windows File System Tags,Harmonize Shared Folder Names
thumbnail: https://thmb.techidaily.com/c4666c711fc9c9a338b2d08e469c371e9c8d5fe0d21f3a3c14a777e4b40a0530.jpg
---

## Correcting Erroneous OneDrive Tags in Windows File System

 Have you encountered the "the tag present in the reparse point buffer is invalid" error when altering a folder or deleting it on your Windows device? You may have encountered this error when accessing a folder via Command Prompt or File Explorer, mainly for files and folders synced to OneDrive. How does this error occur? OneDrive is the source of the error.

 In this article, we'll explain the causes of this error and provide you with possible solutions to resolve it.

## What Causes "The Tag Present in the Reparse Point Buffer Is Invalid" on Windows?

 As mentioned earlier, the error is caused by a problem with OneDrive sync. It could be that the folder you're trying to access is corrupt, or that there is an issue with other system files preventing OneDrive from syncing successfully.

 There are several ways in which the "the tag present in the reparse point buffer is invalid" error can appear. Here are the two most common ones:

* Error 0x80071129: The tag present in the reparse point buffer is invalid
* Location not found: The tag present in the reparse point buffer is invalid

 "Error 0x80071129" or "Location not found" appears as the title of the error window, while the main part of the error appears in the error window. Any variation of this error has nearly the same causes, regardless of its nature. In light of that, similar fixes are effective in resolving the issue. Let's see how you can fix it.

## But First, Some Preliminary Checks

 Apply the following preliminary checks before attempting the major fixes:

* Pause the OneDrive sync and try opening the folder again.
* Restart your device once.
* Log out of your OneDrive account.
* If you have made any changes to the problematic folder on OneDrive, go back and revert them for a while.

 If the above preliminary checks do not solve the problem and the issue persists, start implementing the remaining fixes.

## 1\. Run a CHKDSK Scan

 For Windows users, CHKDSK is a go-to utility for scanning and fixing hard drive problems. Whenever users encounter a hard drive error or an issue with the data stored on their drive, the CHKDSK scan proves to be a godsend.

 This scan may be helpful to fix the issue under discussion since "the tag present in the reparse point buffer is invalid" is also associated with an inability to access a particular file correctly. Therefore, follow the steps below to run the CHKDSK scan before you attempt any other repair or fix:

1. In the Windows Search box, type**"Command Prompt** .**"**
2. Right-click the**Command Prompt** app and click**Run as administrator** .
3. Enter the following command in the Command Prompt app:  
`Chkdsk C: /f /r`
4. Then press**Enter** .  
![Running Check Disk Scan in Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/running-check-disk-scan-in-windows-command-prompt.jpg)

 Here,**C:** refers to the drive where your operating system is installed. If your operating system resides on a different drive, change the command accordingly. Also, don't forget to enter the**"/f"** and**"/r"** parameters since these are needed to fix errors, locate bad sectors, and recover corrupted information.

 The CHKDSK scan has the greatest chance of adequately fixing the error under discussion. However, if it doesn't resolve the problem, you can move on to the next solution.

## 2\. Run the DISM and SFC Scan

 Like CHKDSK, SFC and DISM scans can be used when your system behaves strangely. Initially, you should run the SFC scan because it usually resolves the issue. However, if it fails to diagnose the problem or run, you should run a DISM scan.

 Performing both scans ensures that your device does not have corrupted system files causing the trouble. To run both scans, follow these steps:

1. Open Command Prompt as an administrator.
2. To run the SFC scan, type the following command and press**Enter** :  
`SFC /scannow`
3. To run the DISM scan, type the following command and press**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 To better understand the results of these scans, see our [article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

## 4\. Remove the Passwords From the Problematic Files

 Has this error occurred after password-protecting a synced file on OneDrive? In this case, you should go to OneDrive, check the history of modified files, and restore the problematic file to a previous version. Our article on [recovering OneDrive files from version history](https://www.makeuseof.com/tag/restore-onedrive-files-version-history/#rolling-back-a-file) explains how to roll back a file. Reset OneDrive if this fix does not solve the problem.

## 5\. Reset OneDrive

 Resetting the app or service is a good troubleshooting step for problems that don't resolve with general fixes. Therefore, if none of the fixes have worked so far, you should reset OneDrive. Remember that resetting OneDrive will not delete your data, but you'll have to set up the sync connection again.

 In our article on [how to fix OneDrive when you can't open the files](https://www.makeuseof.com/ways-fix-onedrive-when-you-cannot-open-your-files/#reset-onedrive) , we have explained how to reset OneDrive. Follow the instructions in the article to reset OneDrive, and hopefully, you will be able to fix the issue. However, if that also fails to work and the error appears periodically, you can delete or relocate the problematic file or folder.

## 6\. Delete or Relocate the Problematic File

 If all else fails, delete or relocate the problematic file. However, before you do that, you need to pause the OneDrive sync and leave it for an hour. Then, access your OneDrive online and remove the synced file from there.

 Once done, you should turn off your device's internet connection and [start Windows 11 in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) (or [Windows 10](https://www.makeuseof.com/tag/boot-windows-10-safe-mode/) if you're using an older version). Afterward, navigate to your local drive, where the problematic file is located. Delete it from there and restart your device normally.

 If the file you are experiencing the error with has value to you and you cannot delete it, move it to another computer and delete it from your primary device. Hopefully, relocating or deleting the file will prevent the error from occurring again.

## Keep Annoying OneDrive Errors at Bay

 It can be very frustrating to encounter the "The tag present in the reparse point buffer is invalid" error when making changes to our files. If you apply the fixes in the article, hopefully, you'll be able to fix the error and reaccess your files. If nothing works, you can move it elsewhere and delete it from your primary drive.


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
<li><a href="https://win11-tips.techidaily.com/old-school-explorer-revival-strategies/"><u>Old-School Explorer Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-peak-performance-taming-vanguards-cpu-power-draw-in-windows/"><u>Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-intelligent-interface-ais-role-in-windows-evolution/"><u>The Intelligent Interface: AI's Role in Windows Evolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reveal-hidden-configurations-unearth-missing-controls-in-win11/"><u>Reveal Hidden Configurations: Unearth Missing Controls in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-windows-11-desktop-menu-layout/"><u>Personalizing Your Windows 11 Desktop Menu Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-1011-photography-setup/"><u>Streamlining Windows 10/11 Photography Setup</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-apex-legends-crossplay-how-to-turn-it-off-and-platform-choosing-guide/"><u>[New] In 2024, Apex Legends Crossplay  How to Turn It Off & Platform Choosing Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-oneplus-11r-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-cleansing-windows-arp-cache/"><u>Understanding and Cleansing Windows ARP Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-cheat-sheet-for-ms-project-keys/"><u>The Ultimate Cheat Sheet for MS Project Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-overcoming-windows-run-time-errors/"><u>Unraveling the Mystery: Overcoming Windows 'Run-Time Errors'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-taskbar-absence-during-full-screen-mode/"><u>Tackling Taskbar Absence During Full-Screen Mode</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-leverage-google-voices-features-secure-and-capture-every-call-interaction-for-2024/"><u>Updated Leverage Google Voices Features Secure and Capture Every Call Interaction for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-it-admin-access-restricted-on-windows/"><u>Resolving 'IT Admin Access Restricted' On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-overlapping-app-symbols-on-pc-screen/"><u>Rectifying Overlapping App Symbols on PC Screen</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-cutting-edge-creativity-on-tiktok-mastering-video-designs-in-minutes/"><u>In 2024, Cutting-Edge Creativity on TikTok  Mastering Video Designs in Minutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-not-responding-problem-for-spotify-software/"><u>Resolving the Not Responding Problem for Spotify Software</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-crafting-impeccable-crossfades-with-premiere-pro/"><u>[New] Crafting Impeccable Crossfades with Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-0x80072f8f-0x20000-error-on-pcs/"><u>Resolving 0X80072f8f-0x20000 Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-pathway-for-purchasing-adobe-from-microsoft/"><u>Seamless Pathway for Purchasing Adobe From Microsoft</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mobile-filmmaking-mastery-creating-impactful-youtube-thumbnails/"><u>In 2024, Mobile Filmmaking Mastery  Creating Impactful YouTube Thumbnails</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-audio-integration-in-canva-videos/"><u>2024 Approved  Mastering Audio Integration in Canva Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-glitches-to-achieve-uninterrupted-gameplay-win-11/"><u>Overcoming Steam Glitches to Achieve Uninterrupted Gameplay Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-elusive-windows-search-responses/"><u>Recovering Elusive Windows Search Responses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-win-gameplay-with-dxvk-why-gamers-should-care/"><u>Maximize Win Gameplay with DXVK – Why Gamers Should Care</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-boosting-virtualbox-version-70-on-windows-11/"><u>Step-by-Step Guide: Boosting VirtualBox Version 7.0 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-surprising-alerts-in-windows-security/"><u>Troubleshooting Surprising Alerts in Windows Security</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sci-fis-virtual-quest-the-best-movies-to-discover-alien-universes/"><u>In 2024, Sci-Fi's Virtual Quest  The Best Movies to Discover Alien Universes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/channel-charisma-techniques-for-amplifying-youtube-visibility-for-2024/"><u>Channel Charisma  Techniques for Amplifying YouTube Visibility for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-instagram-image-addition-playbook/"><u>In 2024, The Instagram Image Addition Playbook</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-fast-track-converting-your-srt-files-to-text-format-today/"><u>[New] Fast Track  Converting Your SRT Files to Text Format Today</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-teaming-up-for-duet-video-on-tiktok/"><u>[Updated] Teaming Up for Duet Video on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-gaming-picking-the-perfect-install-drive/"><u>Streamlined Gaming: Picking the Perfect Install Drive</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-leverage-loops-for-stirring-instagram-engagement-and-likes/"><u>[Updated] Leverage Loops for Stirring Instagram Engagement & Likes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-win-11-gaming-landscape-with-these-fps-counters/"><u>Mastering the Win 11 Gaming Landscape with These FPS Counters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-the-must-have-msistore-tools/"><u>Unlock Potential: The Must-Have MSIStore Tools</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-oppo-reno-8t-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Oppo Reno 8T 5G</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-best-free-video-cutter-tools-our-expert-recommendations-for-2024/"><u>Updated Best Free Video Cutter Tools Our Expert Recommendations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovery-of-missing-widgets-and-icons-on-windows-11/"><u>Recovery of Missing Widgets and Icons on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-protocol-port-vulnerability-check-for-windows/"><u>Network Protocol Port Vulnerability Check for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-steam-downloads-stopping-unexpected-declines/"><u>Speed up Steam Downloads: Stopping Unexpected Declines</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-enhance-yt-experience-the-most-outstanding-reaction-ideas/"><u>[Updated] Enhance YT Experience  The Most Outstanding Reaction Ideas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-app-crash-common-issues-and-fixes/"><u>Resolving Windows App Crash: Common Issues & Fixes</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-8-plus-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 8 Plus to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-intrusions-top-7-windows-safeguarding-methods/"><u>Preventing Intrusions: Top 7 Windows Safeguarding Methods</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-revolutionize-your-audio-pazera-free-extractor-insights/"><u>[Updated] Revolutionize Your Audio  Pazera Free Extractor Insights</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-generate-a-costless-film-with-accompaniment-of-melodies/"><u>New In 2024, Generate a Costless Film with Accompaniment of Melodies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-problematic-java-setup-on-windows-pcs/"><u>Unblocking Problematic Java Setup on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-order-7-methods-for-windows-users-disrupted-google-drive/"><u>Restore Order: 7 Methods for Windows Users, Disrupted Google Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-switching-back-the-windows-11-search-icons/"><u>Steps for Switching Back the Windows 11 Search Icons</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-hidden-screenshotters-concealed-photography-on-the-snapchat-app/"><u>[New] 2024 Approved  Hidden ScreenShotters  Concealed Photography on the Snapchat App</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/effortless-video-rotation-discover-the-top-10-online-tools/"><u>Effortless Video Rotation Discover the Top 10 Online Tools</u></a></li>
<li><a href="https://extra-information.techidaily.com/apex-storage-wizards-best-of-android-cloud-for-2024/"><u>Apex Storage Wizards  Best of Android Cloud for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-dive-deep-into-the-digital-world-adding-panoramic-photos-to-your-feed/"><u>[Updated] 2024 Approved  Dive Deep Into the Digital World  Adding Panoramic Photos to Your Feed</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-venturing-through-tiktoks-anime-landscape-choreographies-melodic-intrigues-and-visual-delights/"><u>[Updated] In 2024, Venturing Through TikTok’s Anime Landscape  Choreographies, Melodic Intrigues and Visual Delights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-mysteries-inside-its-registry-files/"><u>Unraveling Windows 11'S Mysteries: Inside Its Registry Files</u></a></li>
</ul></div>
