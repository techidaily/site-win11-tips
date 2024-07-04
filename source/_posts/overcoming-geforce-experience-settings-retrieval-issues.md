---
title: Overcoming GeForce Experience Settings Retrieval Issues
date: 2024-06-25T16:21:34.331Z
updated: 2024-06-26T16:21:34.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming GeForce Experience Settings Retrieval Issues
excerpt: This Article Describes Overcoming GeForce Experience Settings Retrieval Issues
keywords: Fix GeForce Glitches,Retrieve GFX Options,Overcome GeForce Errors,Access GeForce Preferences,Resolve GPU Settings Fails,Unlock GTX Configurations,Tackle RTX Interface Issues
thumbnail: https://thmb.techidaily.com/15954b5de302fb65bb19b216711303e6c7127c1ad83145148cdedf78055491f8.png
---

## Overcoming GeForce Experience Settings Retrieval Issues

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
<li><a href="https://win11-tips.techidaily.com/step-by-step-creating-self-extracting-fx-in-win11/"><u>Step-by-Step: Creating Self-Extracting FX in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-zero-error-mystery-in-windows-11-updates/"><u>Unraveling Zero-Error Mystery in Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-win11-wi-fi-accessibility-with-9-steps/"><u>Securing Win11 Wi-Fi Accessibility with 9 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-non-working-windows-lock-screen-delay/"><u>Reviving Non-Working Windows Lock Screen Delay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-shortcut-tactics-for-optimal-voice-input-on-win-11/"><u>Ultimate Shortcut Tactics for Optimal Voice Input on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-resource-allocation-within-wsl-android-environment/"><u>Tailoring Resource Allocation Within WSL-Android Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-steam-downloads-stopping-unexpected-declines/"><u>Speed up Steam Downloads: Stopping Unexpected Declines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cryptographic-shielding-data-safety-in-networked-drives/"><u>Cryptographic Shielding: Data Safety in Networked Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-non-changeable-sleepwake-modes-in-windows-11/"><u>Circumventing Non-Changeable Sleep/Wake Modes in Windows 11</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-pinnacle-top-5-ultra-light-action-camera-list/"><u>[Updated] Pinnacle Top 5 Ultra-Light Action Camera List</u></a></li>
<li><a href="https://extra-tips.techidaily.com/hasty-and-hassle-free-images-on-windows-11/"><u>Hasty & Hassle-Free Images on Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unveiling-the-mystery-mastering-attention-grabbing-posts-on-instagram/"><u>Unveiling the Mystery  Mastering Attention-Grabbing Posts on Instagram</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-oppo-reno-9a-by-fonelab-android-recover-video/"><u>How to recover old videos from your Oppo Reno 9A</u></a></li>
<li><a href="https://video-capture.techidaily.com/your-journey-through-the-world-of-iphone-memos-for-2024/"><u>Your Journey Through the World of iPhone Memos for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/audio-acquirers-almanac-save-and-scrutinize-songs/"><u>Audio Acquirer's Almanac  Save & Scrutinize Songs</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-boosting-video-success-tips-from-top-50plus-quotes-on-tiktok/"><u>[New] In 2024, Boosting Video Success  Tips From Top 50+ Quotes on TikTok</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-elevate-your-whatsapp-status-with-these-top-rated-video-makers/"><u>In 2024, Elevate Your WhatsApp Status with These Top-Rated Video Makers</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-video-editing-hack-speed-up-or-slow-down-clips-in-camtasia/"><u>In 2024, Video Editing Hack Speed Up or Slow Down Clips in Camtasia</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/infusing-life-into-ppt-with-professional-voiceovers-for-2024/"><u>Infusing Life Into PPT with Professional Voiceovers for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>