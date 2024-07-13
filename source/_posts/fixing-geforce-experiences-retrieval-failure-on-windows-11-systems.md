---
title: Fixing GeForce Experience's Retrieval Failure on Windows 11 Systems
date: 2024-07-12T17:30:37.341Z
updated: 2024-07-13T17:30:37.341Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing GeForce Experience's Retrieval Failure on Windows 11 Systems
excerpt: This Article Describes Fixing GeForce Experience's Retrieval Failure on Windows 11 Systems
keywords: Win11 GeForce Fix,Retrieve Error Resolve,GTX Failsync Repair,Graphics XP Windows,Nvidia Experience Cure,Xbox Series Fixing,Display Adapter Recovery
thumbnail: https://thmb.techidaily.com/7fc466e5e2b7732daf41c9b5f420c5c5add88815dae1954866b21ab967027c21.jpg
---

## Fixing GeForce Experience's Retrieval Failure on Windows 11 Systems

 GeForce Experience is software with which users can usually optimize their games. However, some GeForce Experience users can’t optimize games with that software because of an “unable to retrieve settings” error. Some users see that error message when they click games’ thumbnails in GeForce Experience.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.

## 1\. Run GeForce Experience With Administrative Rights

 A few players have said running GeForce Experience with admin rights resolved the “Unable to retrieve settings” error for them. So, that’s a simple resolution worth trying. To see if that works for you, bring up the Windows search tool and input GeForce Experience. Then right-click the GeForce Experience search result to select **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option4.jpg)

 If that works, set GeForce Experience to always run with elevated user rights. Then you won’t need to select the **Run as administrator** option all the time. Our guide for [always running apps as an administrator on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) tells you how to set software packages to start with elevated permissions.

## 2\. Remove Scan Locations

 Some GeForce Experience users confirm that removing scan locations and rescanning fixes the “Unable to retrieve settings” error. This is how you can remove scan locations in GeForce Experience:

1. Open the GeForce Experience window.
2. Click the **Settings** button by your user account name.  
![The Settings menu button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/settings-button.jpg)
3. Select the **Games & Apps** tab.
4. Then select a scan location and click **Remove**. Repeat this step to remove all scan locations shown.  
![The Remove button for scan locations](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-button.jpg)
5. Press the **Scan Now** button to rescan.

## 3\. Delete the CefCache Folder

 CefCache is a GeForce Experience folder that stores cached data. GeForce Experience optimization issues can arise when that cache includes corrupted configuration files. You might be able to resolve the “Unable to retrieve settings” error by deleting the CafCache folder like this:

1. Ensure GeForce Experience isn’t already running by closing it on the taskbar and the system tray. Right-click the NVIDIA system tray and select **Exit** to close GeForce Experience there.
2. Open File Explorer (press **Win + E**) and input this path in the folder address bar:  
`C:\Users\<user folder>\AppData\Local\NVIDIA Corporation\NVIDIA GeForce Experience`  
![The CefCache folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/cefcache-folder.jpg)
3. Right-click the **CefCache** folder to select **Delete**.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-button.jpg)
4. Then launch the GeForce Experience software.
5. Input your GeForce Experience account details again and click **Log In**.

## 4\. Restore Default NVIDIA 3D Settings

 Restoring the NVIDIA 3D Settings to default is another potential fix for the “Unable to retrieve settings” error that has worked for some users. Applying this resolution will reset all 3D settings you’ve changed in the NVIDIA Control panel to a default configuration. You can apply this potential resolution as follows:

1. Right-click on the NVIDIA logo inside the system tray area to select **Control Panel**.
2. Next, select **Manage 3D** settings in the NVIDIA Control Panel.
3. Click **Restore** on the **Global Settings** tab.  
![The Restore button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/restore-button.jpg)
4. Select **Yes** to reset the settings.

## 5\. Delete the Steam User Data

 The “Unable to retrieve settings” error can arise for Steam games because of a data conflict with Steam. Players have confirmed erasing data in a Steam userdata subfolder works for fixing this issue. So, that’s a possible resolution recommended for all players who’ve got Steam installed. Clear Steam’s userdata folder like this:

1. Simultaneously press **Win + X** and select the File Explorer shortcut.
2. Input this userdata folder path in Explorer’s address bar:  
`C:\Program Files\Steam\userdata`  
![Steam's userdata folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/userdata-folder.jpg)
3. Right-click a subfolder that doesn’t have any numbers in its name within the userdata folder and select **Delete**.
4. Repeat the previous step to delete all subfolders in userdata with non-numeric titles like anonymous, etc.

## 6\. Perform Some Generic Windows Fixes

 There are a few Windows-based fixes you can try to get rid of this error.

### Erase Temporary Windows Data

 The Temp folder stores temporary files. GeForce Experience users confirm deleting data in that Temp folder can fix the “Unable to retrieve settings” issue. So, try eradicating data in that folder with one of the methods in our guide to [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/)[in Windows 11](http://www.makeuseof.com/windows-11-delete-temporary-files/).

![disk-cleanup-tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disk-cleanup-tool.jpg)

### Install the Latest NVIDIA Driver for Your GPU

 Although less likely, corrupted NVIDIA GPU driver files can feasibly cause the “Unable to retrieve settings” error to arise. In this case, installing the latest NVIDIA graphics drivers could be a solution for some users. Uninstall your PC’s current NVIDIA graphics driver and install the latest one by downloading it from the NVIDIA website.

 Follow the instructions in our guide to [installing and cleanly reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) to apply this potential fix with the DDU software.

![The NVIDIA driver downloads page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-driver-downloads.jpg)

### Disable Third-Party Antivirus Tools

 If you’ve got third-party antivirus software installed on your Windows PC, that might be blocking GeForce Experience from accessing certain folders and optimizing settings. BitDefender Total Security is one antivirus utility widely confirmed to cause this issue. Those users who've confirmed that needed to disable BitDefender to resolve the issue.

 So, try disabling BitDefender or any other third-party antivirus software to see if that makes a difference. You can disable real-time scanning by right-clicking an antivirus tool in the Windows system tray and selecting to disable or turn it off from the context menu. Select to temporarily disable the antivirus scanning for about an hour or so and then open GeForce Experience.

### Reinstall GeForce Experience

 Reinstalling GeForce Experience might be a necessary potential fix for the “Unable to retrieve files” error if others fail. That will replace any corrupted GeForce Experience files that could be causing glitches. Remove GeForce Experience with a method in this guide to [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option3.jpg)

 Restart the PC before reinstalling GeForce Experience. Then head over to this [GeForce Experience](https://www.nvidia.com/en-gb/geforce/geforce-experience/download/) webpage and click **Download Now**. Open the folder your browser usually downloads files to and double-click the GeForce Experience setup wizard. Go through the installer’s steps to reinstall the software.

## Optimize Your Games With GeForce Experience

 Many GeForce Experience users have fixed the “unable to retrieve settings” error in Windows with the resolutions above. You may have to try applying a few of them to get the issue sorted since there are quite a few potential causes for this error. Then you can quickly and fully optimize all your favorite games with GeForce Experience again.

 However, remember that there are numerous ways to optimize Windows games without GeForce Experience. You can optimize gaming by enabling or even disabling certain Windows features and closing background apps. Plus, you can manually adjust the graphical settings in the NVIDIA Control Panel or games to optimize Windows gaming.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-discovering-the-true-significance-of-pfp-in-tiktok-world/"><u>[New] In 2024, Discovering the True Significance of PFP in TikTok World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-changing-app-size-using-pc-keys-on-windows-11/"><u>Tips for Changing App Size Using PC Keys on Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-track-lost-friends-on-instagram/"><u>[Updated] 2024 Approved  Track Lost Friends on Instagram</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-can-i-unlock-my-apple-iphone-14-plus-after-forgetting-my-pin-code-by-drfone-ios/"><u>How Can I Unlock My Apple iPhone 14 Plus After Forgetting my PIN Code?</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-quick-curving-techniques-for-modern-photoshop-artists/"><u>In 2024, Quick Curving Techniques for Modern Photoshop Artists</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/5-ways-to-record-webinar-for-free-for-2024/"><u>5 Ways to Record Webinar for Free for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-crafting-compelling-content-with-macootd-tiktoks/"><u>2024 Approved  Crafting Compelling Content with MacOOTD TikToks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-xbox-game-pass-error-0x000-on-windows-11-systems/"><u>Understanding and Correcting Xbox Game Pass Error 0X000_ on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-to-windows-birthplace-points/"><u>Trailblazing to Windows' Birthplace Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-fixes-for-fbm-not-working-here/"><u>10 Essential Fixes for FBM Not Working Here</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-live-the-future-with-mycam-video-recording-revolution/"><u>[Updated] Live the Future with MyCam  Video Recording Revolution</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-apple-iphone-15-plus-location-by-number-drfone-by-drfone-virtual-ios/"><u>How to Track Apple iPhone 15 Plus Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-power-enable-the-outlook-preview-app/"><u>Unlock Windows' Power: Enable the Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-simplify-network-connection-configurations-in-winos/"><u>10 Ways to Simplify Network Connection Configurations in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719203477260-how-to-unfreeze-google-chrome-in-windows-11-fastly-find-out-now/"><u>How to Unfreeze Google Chrome in Windows 11 Fastly? Find Out Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhindered-wi-fi-on-your-desktop-9-strategies-for-win11-users/"><u>Unhindered Wi-Fi on Your Desktop: 9 Strategies for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-pioneering-technologies-vr-applications/"><u>[Updated] Pioneering Technologies  VR Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-straightforward-steps-to-engage-repair-tool/"><u>10 Straightforward Steps to Engage Repair Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-dilemma-obs-not-opening-on-windows/"><u>Resolving the Dilemma: OBS Not Opening on Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-discord-vs-skype-selecting-your-communication-platform/"><u>2024 Approved  Discord vs Skype  Selecting Your Communication Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-setup-a-closer-look/"><u>Windows 11 Setup: A Closer Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-unveiling-the-mystery-of-facebooks-status-video-downloads/"><u>[Updated] 2024 Approved  Unveiling the Mystery of Facebook's Status Video Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-strategies-for-managing-windows-connections-tool/"><u>10 Key Strategies for Managing Window's Connections Tool</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-advanced-techniques-developing-elapsed-time-features-in-obs-software/"><u>[New] 2024 Approved  Advanced Techniques  Developing Elapsed Time Features in OBS Software</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-oppo-reno-8t-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-top-5-grievances-from-windows-11-users/"><u>Unveiling the Top 5 Grievances From Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-s-mode-imply-in-windows-11-upgrade/"><u>What Does 'S Mode' Imply in Windows 11 Upgrade?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steer-clear-of-stuck-arrows-in-windows/"><u>Steer Clear of Stuck Arrows in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/12-superfluous-windows-tools-you-can-live-without/"><u>12 Superfluous Windows Tools You Can Live Without</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-top-10-escape-room-games-you-should-try/"><u>[New] In 2024, Top 10 Escape Room Games You Should Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/how-to-rank-your-facebook-page/"><u>How to Rank Your Facebook Page</u></a></li>
</ul></div>
