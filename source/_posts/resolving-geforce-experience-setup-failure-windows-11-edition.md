---
title: Resolving GeForce Experience Setup Failure, Windows 11 Edition
date: 2024-06-25T16:51:16.345Z
updated: 2024-06-26T16:51:16.345Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving GeForce Experience Setup Failure, Windows 11 Edition
excerpt: This Article Describes Resolving GeForce Experience Setup Failure, Windows 11 Edition
keywords: Fix GeForce Xe,WinXe RSetup Fails,XP Fixer Guide,Graphics Fix Windows 11,GeForce Error Resolution,Setup Failure Fixing,GeForce Fix Tips
thumbnail: https://thmb.techidaily.com/91dc46c6cc6911e9915591791566cdaadd16613fc33817ba0857c51273b662cd.JPG
---

## Resolving GeForce Experience Setup Failure, Windows 11 Edition

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-starting-csgo-in-w11/"><u>Mastering the Art of Starting CS:GO in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-repair-exploration-sifting-through-disms-role-with-chkdsksfc/"><u>System Repair Exploration: Sifting Through DISM's Role with CHKDSK/SFC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-installing-java-in-windows-environment/"><u>Solutions for Non-Installing Java in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-keyboard-shortcuts-next-to-power-icon/"><u>Tailoring Windows 11: Keyboard Shortcuts Next to Power Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-network-errors-a-guide-for-windows-11-users/"><u>Eliminating Network Errors: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-windows-service-reactivation/"><u>Optimal Windows Service Reactivation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-shutdownrestart-blockage-due-to-deceptive-apps-in-windows/"><u>Counteracting Shutdown/Restart Blockage Due to Deceptive Apps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-to-reviving-frozen-start-button/"><u>Methodical Approach to Reviving Frozen Start Button</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-adjustments-nine-fixes-to-smooth-out-windows-11-gaming/"><u>Accelerated Adjustments: Nine Fixes to Smooth Out Windows 11 Gaming</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-honor-magic-vs-2-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Honor Magic Vs 2 Location by Number | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-essential-methodologies-in-capturing-web-radio-audio/"><u>2024 Approved  Essential Methodologies in Capturing Web Radio Audio</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-vn-video-editor-for-windows-a-brief-overview-for-2024/"><u>Updated VN Video Editor for Windows A Brief Overview for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-quick-fixes-screen-capturing-on-instagrams-feed/"><u>[New] Quick Fixes  Screen Capturing on Instagram's Feed</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-poco-x6-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Poco X6 Location by Number | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-the-pathway-to-authenticity-becoming-a-trusted-disco-member/"><u>2024 Approved  The Pathway to Authenticity  Becoming a Trusted Disco Member</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/peeling-back-the-layers-of-visual-past-a-guide-to-fb-image-searching-reversed/"><u>Peeling Back the Layers of Visual Past  A Guide to FB Image Searching (Reversed)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-sizzling-snaps-from-tiktoks-culinary-kings-and-queens/"><u>[Updated] 2024 Approved  Sizzling Snaps From TikTok’s Culinary Kings & Queens</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>