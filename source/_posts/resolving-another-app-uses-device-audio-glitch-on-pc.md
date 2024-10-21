---
title: Resolving 'Another App Uses Device' Audio Glitch on PC
date: 2024-10-15T17:20:05.366Z
updated: 2024-10-20T22:39:06.210Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving 'Another App Uses Device' Audio Glitch on PC
excerpt: This Article Describes Resolving 'Another App Uses Device' Audio Glitch on PC
keywords: Fix Audio Glitch App Issue,Unique Device Usage Error,Stop Other Apps Sound Interference,Resolve Device Conflict Sound,Eliminate Cross-App Audio Bug,Address PC Audio Clashing,Tackle Duplicate App Audio
thumbnail: https://thmb.techidaily.com/3376b29faa2d3197bcfcb2a2edc1961849ab5554465668491f874fa276d36a0e.jpg
---

## Resolving 'Another App Uses Device' Audio Glitch on PC

 The audio device on your Windows computer can simultaneously play audio from multiple sources. However, at times, the audio stops playing with the error "this device is being used by another application".

 This is error is often a case of incorrectly configured Windows Audio service. Other times, the audio issue is due to a corrupt audio device driver. Here we show you how to troubleshoot the "this device is being used by another application" error and restore audio on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Audio Troubleshooter

![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)

 Windows has a built-in audio troubleshooter to find and fix issues with playing audio. The troubleshooter looks for common audio issues and tries to fix them automatically.

To run the audio troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Troubleshoot** .
3. Click on**Other troubleshooters** .
4. Next, click the**Run** button for**Playing Audio** . Wait for the audio troubleshooter to scan for issues. Then select the affected audio device and click**Next** .
5. Follow the on-screen instructions and check if the error is resolved.

## 2\. Disable Exclusive Mode for the Audio Device

 By default, Windows applications can take exclusive control of the audio device. While enabling this option shouldn’t cause any issues, some apps may prevent the device from being used by other audio services. To fix the problem, disable exclusive mode to stop applications from taking exclusive control of the audio device.

To disable Exclusive Mode for the audio device on Windows:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Sound** .
3. Scroll down and click on**More sound settings** .  
![more sound settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/more-sound-settings-windows-11.jpg)
4. Select the audio device in the**Sound** dialog and click the**Properties** button.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Open the**Advanced** tab in the**Properties** dialog.  
![disable exclusive mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-exclusive-mode.jpg)
6. Uncheck the **Allow application to take exclusive control of this device** and**Give exclusive mode application priority** options.
7. Click**Apply** and**OK** to save the changes.

 Restart your computer and check if the error is resolved and if the audio device is working again.

## 3\. Change Windows Audio Service Startup Type

 Windows Audio service is responsible for managing audio devices connected to your computer. If the service is disabled or not running, your audio device can stop working.

 By default, it is set to start automatically as you power on your device. Check if the Startup type for Windows Audio is set to Manually. If yes, reconfigure it to start automatically to fix audio problems.

To change the Windows Audio service Startup type:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** to open the**Services** snap-in.
3. In the**Services** window, locate and double-click on**Windows Audio** service.  
![windows audio service properties services snap in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-properties-services-snap-in.jpg)
4. Click the**Startup** type drop-down and select**Automatic** .
5. Click**Apply** and**OK** to save the changes.  
![windows audio service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-startup-type-automatic.jpg)
6. If the service is not running, right-click on**Windows Audio** and select**Start** .
7. Close the Services snap-in and restart your PC. After the restart, your audio device should start working again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902309/19272" target="_top" id="1902309">
  <img src="//a.impactradius-go.com/display-ad/19272-1902309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902309/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable and Re-Enable the Sound Output Device

 You can temporarily disable and re-enable the audio device to fix any glitches causing the device to malfunction. You can[disable the audio device](https://www.makeuseof.com/enable-disable-sound-output-devices-in-windows/) using the Settings app and Device Manager.

 To disable the audio device, right-click on the audio device and select**Disable device** in**Device Manager** . Next, right-click on the audio device and**Enable Device** . Close Device Manager and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535">
  <img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Uninstall and Reinstall the Audio Device and Driver

![Uninstalling an audio device in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/uninstalling-audio-device-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049363/7443" target="_top" id="2049363">
  <img src="//a.impactradius-go.com/display-ad/7443-2049363" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049363/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also troubleshoot your audio problems by uninstalling the audio device and the associated drivers. Reinstalling the audio device can help if the sound problem is due to corrupt audio drivers.

To uninstall your audio device on Windows:

1. Press**Win + X** to open the**WinX menu** .
2. Select**Device Manager** for the menu.
3. In Device Manager, expand the**Audio inputs and output section** .
4. Right-click on your audio device and select**Uninstall device** .
5. Read the warning and click**Uninstall** to confirm the action. Wait for the device to uninstall.

 You may see a yellow exclamation mark on the uninstalled audio device. To reinstall the driver, click on**File** and select**Scan for hardware changes** . This should reinstall the sound device and driver. If not, restart your computer. As the system restarts, Windows will reinstall the missing audio device driver and restore sound on your computer.

## 6\. Perform a Driver Rollback

 If you have an external sound card and have installed an update, try a driver rollback. A new driver update can sometimes create more problems than it intends to fix. You can use the device driver rollback feature in Device Manager to undo the changes and reinstall the older version of the driver.

 You can[roll back a driver using Windows Device Manager](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . In Device Manager, expand the**Sound, Video, and Game Controllers** section. Next, access your external sound card properties to perform a rollback.

 If the Roll Back Driver option is greyed out, it means the option is unavailable for the selected device. In this instance, uninstall the existing audio device driver and download an older version of the driver from your sound card manufacturer's website. Your sound card manufacturer may also have a newer driver version available. If available, install the latest version and check for any improvements.

## 7\. Install Pending Windows Updates

![windows 11 view update history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winodws-11-view-update-history.jpg)

 If it is a Windows-specific issue, installing pending Windows updates can fix the problem. Check the Windows updates page for newer updates and install them to see if that helps resolve the issue.

 To install Windows update, go to**Settings > Windows Update** and click**Check for updates** . Windows will populate the screen with all the pending updates. You can install the updates or selectively install any audio device updates.

## 8\. Check for Third-Party App Conflict

![volume mixer windows 11 view audio applications](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/volume-mixer-windows-11-view-audio-applications.jpg)

 If the issue persists, check if there is a third-party app conflict. You can use Volume Mixer to view applications accessing the audio devices and close the problematic app to fix the problem. Here’s how to do it.

1. Press**Win + R** to open Run.
2. Type**sndvol** and click**OK** to open Volume Mixer.
3. The**Application** column will show all the apps using your audio device.

 To close the app, open the system tray, right-click the app icon, and select**Quit** . You can also force close the app using Task Manager. If the issue persists, uninstall the problematic app to restore the audio to your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044582/7443" target="_top" id="2044582">
  <img src="//a.impactradius-go.com/display-ad/7443-2044582" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044582/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing the Audio Device in Use By Another Application Error

 This error is often the result of an audio device driver problem. To fix the error, check if a new driver is available. If not, perform a rollback to install the previous driver version. Also, disable exclusive application access to audio devices and configure the Windows Audio service to start automatically.

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
<li><a href="https://fox-access.techidaily.com/updated-comprehensive-sierras-icloud-drives-the-full-experience-for-2024/"><u>[Updated] Comprehensive Sierra's iCloud Drives – The Full Experience for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-enriching-vlog-topics-to-share/"><u>[Updated] In 2024, Enriching Vlog Topics to Share</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-harmonic-hits-how-to-choose-the-perfect-song-for-ig-videos/"><u>[Updated] In 2024, Harmonic Hits How to Choose the Perfect Song for IG Videos</u></a></li>
<li><a href="https://blog-min.techidaily.com/1725284915574-mac-avchdmkvwmvmp4/"><u>最新 Mac 專業轉換工具: 支援 AVCHD、MKV、WMV、MP4 - 官方網站便利選擇</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/enhancing-customer-onboarding-with-mobile-ocr-technology/"><u>Enhancing Customer Onboarding with Mobile OCR Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-managing-app-packages-using-wingetui-in-windows-11/"><u>Essential Guide to Managing App Packages Using WingetUI in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expediting-the-epic-games-universe-download-process/"><u>Expediting the Epic Games Universe Download Process</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-vivo-y100i-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Vivo Y100i? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-photo-capture-file-creation-failed-camera-app-error-on-windows-10-and-11/"><u>How to Fix the “Photo Capture File Creation Failed” Camera App Error on Windows 10 & 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-instagram-fan-count-decline-identify-losses/"><u>In 2024, Instagram Fan Count Decline Identify Losses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-icon-cache-via-command-line/"><u>Optimizing Icon Cache via Command Line</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-detectable-disk-error/"><u>Overcoming Non-Detectable Disk Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-sign-in-challenges-tackling-the-user-profile-service-error-in-windows-11/"><u>Overcoming Sign-In Challenges: Tackling the User Profile Service Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-error-microsoft-store-0x80073cf3/"><u>Overcoming Windows 11 Error: Microsoft Store 0X80073cf3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-microsoft-store-crash-resolve-error-code-x800704cf/"><u>Tackling Microsoft Store Crash: Resolve Error Code X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-bestowed-powers-via-command-line/"><u>Windows 11: Bestowed Powers via Command Line</u></a></li>
</ul></div>

