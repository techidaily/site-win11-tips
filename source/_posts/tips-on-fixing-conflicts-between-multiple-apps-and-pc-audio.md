---
title: Tips on Fixing Conflicts Between Multiple Apps & PC Audio
date: 2024-09-28T23:45:00.181Z
updated: 2024-10-03T17:49:44.748Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips on Fixing Conflicts Between Multiple Apps & PC Audio
excerpt: This Article Describes Tips on Fixing Conflicts Between Multiple Apps & PC Audio
keywords: Multi-App Audio Harmony,Resolving App Audio Clashes,PC Audio Conflict Solutions,Unify PC Multimedia Apps,Mitigate Audio App Conflicts,Fixing App Sound Issues,Balance Multiple App Audio
thumbnail: https://thmb.techidaily.com/f7e33e46d8576e8a405f890f9187eb22b423a0b9361503ab0ea4cb809046ec66.jpg
---

## Tips on Fixing Conflicts Between Multiple Apps & PC Audio

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
5. Open the**Advanced** tab in the**Properties** dialog.  
![disable exclusive mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-exclusive-mode.jpg)
6. Uncheck the **Allow application to take exclusive control of this device** and**Give exclusive mode application priority** options.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016165/19272" target="_top" id="2016165">
  <img src="//a.impactradius-go.com/display-ad/19272-2016165" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016165/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

## 4\. Disable and Re-Enable the Sound Output Device

 You can temporarily disable and re-enable the audio device to fix any glitches causing the device to malfunction. You can[disable the audio device](https://www.makeuseof.com/enable-disable-sound-output-devices-in-windows/) using the Settings app and Device Manager.

 To disable the audio device, right-click on the audio device and select**Disable device** in**Device Manager** . Next, right-click on the audio device and**Enable Device** . Close Device Manager and check for any improvements.

## 5\. Uninstall and Reinstall the Audio Device and Driver

![Uninstalling an audio device in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/uninstalling-audio-device-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2148129/17093" target="_top" id="2148129">
  <img src="//a.impactradius-go.com/display-ad/17093-2148129" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2148129/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also troubleshoot your audio problems by uninstalling the audio device and the associated drivers. Reinstalling the audio device can help if the sound problem is due to corrupt audio drivers.

To uninstall your audio device on Windows:

1. Press**Win + X** to open the**WinX menu** .
2. Select**Device Manager** for the menu.
3. In Device Manager, expand the**Audio inputs and output section** .
4. Right-click on your audio device and select**Uninstall device** .
5. Read the warning and click**Uninstall** to confirm the action. Wait for the device to uninstall.

 You may see a yellow exclamation mark on the uninstalled audio device. To reinstall the driver, click on**File** and select**Scan for hardware changes** . This should reinstall the sound device and driver. If not, restart your computer. As the system restarts, Windows will reinstall the missing audio device driver and restore sound on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151890/7443" target="_top" id="2151890">
  <img src="//a.impactradius-go.com/display-ad/7443-2151890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Perform a Driver Rollback

 If you have an external sound card and have installed an update, try a driver rollback. A new driver update can sometimes create more problems than it intends to fix. You can use the device driver rollback feature in Device Manager to undo the changes and reinstall the older version of the driver.

 You can[roll back a driver using Windows Device Manager](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . In Device Manager, expand the**Sound, Video, and Game Controllers** section. Next, access your external sound card properties to perform a rollback.

 If the Roll Back Driver option is greyed out, it means the option is unavailable for the selected device. In this instance, uninstall the existing audio device driver and download an older version of the driver from your sound card manufacturer's website. Your sound card manufacturer may also have a newer driver version available. If available, install the latest version and check for any improvements.

## 7\. Install Pending Windows Updates

![windows 11 view update history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winodws-11-view-update-history.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036472/19272" target="_top" id="2036472">
  <img src="//a.impactradius-go.com/display-ad/19272-2036472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036472/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If it is a Windows-specific issue, installing pending Windows updates can fix the problem. Check the Windows updates page for newer updates and install them to see if that helps resolve the issue.

 To install Windows update, go to**Settings > Windows Update** and click**Check for updates** . Windows will populate the screen with all the pending updates. You can install the updates or selectively install any audio device updates.

## 8\. Check for Third-Party App Conflict

![volume mixer windows 11 view audio applications](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/volume-mixer-windows-11-view-audio-applications.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the issue persists, check if there is a third-party app conflict. You can use Volume Mixer to view applications accessing the audio devices and close the problematic app to fix the problem. Here’s how to do it.

1. Press**Win + R** to open Run.
2. Type**sndvol** and click**OK** to open Volume Mixer.
3. The**Application** column will show all the apps using your audio device.

 To close the app, open the system tray, right-click the app icon, and select**Quit** . You can also force close the app using Task Manager. If the issue persists, uninstall the problematic app to restore the audio to your computer.

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-10-best-inspirational-movies-that-will-make-you-feel-motivated/"><u>[New] 2024 Approved 10 Best Inspirational Movies That Will Make You Feel Motivated</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-from-good-to-great-videos-the-20-essential-shortcuts-for-success/"><u>[New] 2024 Approved From Good to Great Videos The 20 Essential Shortcuts for Success</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-guide-clearing-up-youtube-watchlater-stored-list/"><u>[New] 2024 Approved Guide Clearing Up YouTube Watchlater Stored List</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-effortlessly-record-macos-content-and-display-for-2024/"><u>[New] Effortlessly Record macOS Content & Display for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-masterful-thumbnails-in-a-flash-professional-valorant-creations/"><u>[New] In 2024, Masterful Thumbnails in a Flash Professional Valorant Creations</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-monitoring-your-instagram-fan-loss-rate/"><u>2024 Approved Monitoring Your Instagram Fan-Loss Rate</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-tecno-spark-10-4g-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Tecno Spark 10 4G Fingerprint Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-xbox-gaming-avoid-drive-selection-stress/"><u>Effortless Xbox Gaming: Avoid Drive Selection Stress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elusive-disappearance-of-taskbars-control-in-win-11/"><u>Elusive Disappearance of TaskBar's Control in Win 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-10-motivational-films-for-a-zestful-life/"><u>In 2024, Top 10 Motivational Films for a Zestful Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-typing-mastery-through-typingaid/"><u>Rapid Typing Mastery Through TypingAid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-deleted-execution-records-on-windows/"><u>Recovering Deleted Execution Records on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-microsoft-store-error-on-win11-with-code-0x80073cf3/"><u>Remedying the Microsoft Store Error on Win11 with Code 0X80073cf3</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/scrutinizing-nw-ws623s-unique-design-traits/"><u>Scrutinizing NW-WS623's Unique Design Traits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-start-csgo-in-windows-11-successfully/"><u>Strategies to Start CS:GO in Windows 11 Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-settings-through-alomware-applications/"><u>Transforming Windows Settings Through AlomWare Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-opening-shared-windows-folders/"><u>Troubleshooting: Opening Shared Windows Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-msvcr110dll-missing-error-and-how-do-you-fix-it/"><u>What Is the Msvcr110.dll Missing Error and How Do You Fix It?</u></a></li>
</ul></div>

