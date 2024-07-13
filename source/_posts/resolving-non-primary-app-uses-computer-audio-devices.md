---
title: Resolving Non-Primary App Uses Computer Audio Devices
date: 2024-07-12T17:12:19.978Z
updated: 2024-07-13T17:12:19.978Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Non-Primary App Uses Computer Audio Devices
excerpt: This Article Describes Resolving Non-Primary App Uses Computer Audio Devices
keywords: Primary App Audio Use,Unique Device Playback,Optimize Audio Outputs,Audio Non-Primary Use,Fixing Audio Device Links,Streamline Audio Functions,Redirect Non-Audio Uses
thumbnail: https://thmb.techidaily.com/799b62d064a45ec31383dad7a037b165e61e53db2f1095b1f1474aef4ef5c21f.png
---

## Resolving Non-Primary App Uses Computer Audio Devices

 The audio device on your Windows computer can simultaneously play audio from multiple sources. However, at times, the audio stops playing with the error "this device is being used by another application".

 This is error is often a case of incorrectly configured Windows Audio service. Other times, the audio issue is due to a corrupt audio device driver. Here we show you how to troubleshoot the "this device is being used by another application" error and restore audio on Windows.

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

 You can temporarily disable and re-enable the audio device to fix any glitches causing the device to malfunction. You can [disable the audio device](https://www.makeuseof.com/enable-disable-sound-output-devices-in-windows/) using the Settings app and Device Manager.

 To disable the audio device, right-click on the audio device and select**Disable device** in**Device Manager** . Next, right-click on the audio device and**Enable Device** . Close Device Manager and check for any improvements.

## 5\. Uninstall and Reinstall the Audio Device and Driver
![Uninstalling an audio device in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/uninstalling-audio-device-windows-11.jpg)

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

 You can [roll back a driver using Windows Device Manager](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . In Device Manager, expand the**Sound, Video, and Game Controllers** section. Next, access your external sound card properties to perform a rollback.

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
<li><a href="https://activate-lock.techidaily.com/effective-ways-to-fix-checkra1n-error-31-from-iphone-15-by-drfone-ios/"><u>Effective Ways To Fix Checkra1n Error 31 From iPhone 15</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-tecno-spark-20-proplus-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Tecno Spark 20 Pro+ Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-windows-11-and-parallels-confluence-in-macos/"><u>Achieving Windows 11 and Parallels Confluence in MacOS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-a-comprehensive-look-at-uploading-images-to-youtube/"><u>In 2024, A Comprehensive Look at Uploading Images to YouTube</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/transform-your-editing-master-the-fade-effect-for-2024/"><u>Transform Your Editing  Master the Fade Effect for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-restoring-essential-features-of-photo-viewer-on-win11/"><u>A Quick Guide to Restoring Essential Features of Photo Viewer on Win11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-mac-display-recorder-tips-and-tricks/"><u>[Updated] In 2024, Mac Display Recorder Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-phantom-noise-fixing-inactive-notifications-from-phone-link/"><u>Addressing Phantom Noise: Fixing Inactive Notifications From Phone Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-crash-code-0xc0000142-in-win11win7/"><u>Addressing Crash Code 0XC0000142 in WIN11/Win7</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-xiaomi-14-ultra-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Xiaomi 14 Ultra Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-prodigious-8-cameras-enhancing-video-quality-in-broadcast/"><u>In 2024, Prodigious 8 Cameras Enhancing Video Quality in Broadcast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-probing-program-hideouts-in-windows/"><u>A Practical Approach to Probing Program Hideouts in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-itel-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Itel Phone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-free-visual-storytelling-tools-intro-templates/"><u>[New] In 2024, Free Visual Storytelling Tools - Intro Templates</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-maximizing-impact-10-key-strategies-for-instagram-video-promotion/"><u>In 2024, Maximizing Impact  10 Key Strategies for Instagram Video Promotion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-settings-to-tweak-on-a-new-windows-11-install/"><u>8 Settings to Tweak on a New Windows 11 Install</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-oppo-a2-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Oppo A2 Device</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/expert-picks-best-voice-isolation-technologies-for-music-creators/"><u>Expert Picks Best Voice Isolation Technologies for Music Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreran-guide-to-windows-11-widget-toolbar-usage/"><u>A Compreran Guide to Windows 11 Widget Toolbar Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-deceptive-virus-notifications-on-windows-chrome/"><u>Addressing Deceptive Virus Notifications on Windows Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-access-dilemnas-on-windows-os/"><u>Addressing File Access Dilemnas on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373613156-unlock-windows-xp-potential-without-the-compatibility-tool/"><u>Unlock Windows XP Potential Without the Compatibility Tool.</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-innovative-igtv-thumbnail-upgrades-guide/"><u>2024 Approved  Innovative IGTV Thumbnail Upgrades Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/a-musical-guide-to-enhancing-slides-with-tunes-for-2024/"><u>A Musical Guide to Enhancing Slides with Tunes for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/elevate-your-editing-with-blend-mode-innovations-for-2024/"><u>Elevate Your Editing with Blend Mode Innovations for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-gadgets-to-reduce-camera-jiggle-effects/"><u>Best Gadgets to Reduce Camera Jiggle Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-easy-tips-for-memo-making-in-windows/"><u>7 Easy Tips for Memo-Making in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/simplified-live-mastery-one-channel-broadcast-strategies/"><u>Simplified LIVE Mastery  One-Channel Broadcast Strategies</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unveil-your-channels-potential-with-30-top-tier-free-intros/"><u>Unveil Your Channel's Potential with 30 Top-Tier Free Intros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376942389-windows-gptmimicry-a-costless-local-edition-via-gpt4all/"><u>Windows GPTMimicry: A Costless Local Edition via GPT4All.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-critical-tweaks-to-reactivate-firewall/"><u>4 Critical Tweaks to Reactivate Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-rectifying-windows-display-defects/"><u>7 Strategies for Rectifying Windows Display Defects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-open-the-file-history-in-windows-11/"><u>8 Ways to Open the File History in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-window-11-search-game-essential-tips-to-know/"><u>Ace Your Window 11 Search Game: Essential Tips to Know</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-instagram-tv-shutdown-procedure/"><u>[Updated] 2024 Approved  Instagram TV Shutdown Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719331271081-dual-virus-scanners-think-twice-windows/"><u>Dual Virus Scanners? Think Twice, Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/seamless-virtual-conferencing-in-gmail-via-zoom-best-practices/"><u>Seamless Virtual Conferencing in Gmail via Zoom Best Practices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-with-file-history-backup-on-windows/"><u>Addressing Error with File History Backup on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-open-disk-management-in-windows-10-and-11/"><u>4 Ways to Open Disk Management in Windows 10 and 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-accessible-speech-modification-tools-detailed-analysis-and-comparatives/"><u>In 2024, Accessible Speech Modification Tools Detailed Analysis and Comparatives</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-prime-software-catalog-for-ultra-hd-recording-needs/"><u>[Updated] 2024 Approved  Prime Software Catalog for Ultra HD Recording Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-pre-ultimate-computers-to-seniors-needs/"><u>Adapting Pre-Ultimate Computers to Seniors' Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719258280599-jump-over-the-endless-update-hurdle-quick-fixes-now/"><u>Jump Over The Endless Update Hurdle: Quick Fixes Now!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-insearchofimprovedcameratech-beyond-mycam/"><u>[New] In 2024, InSearchOfImprovedCameraTech Beyond MyCam</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-realme-narzo-n53-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Realme Narzo N53? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-camera-found-error-on-windows-11-os/"><u>Addressing No Camera Found Error on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-hyper-v-enablement-in-win11/"><u>A Comprehensive Guide to Hyper-V Enablement in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-journey-to-windows-11s-god-like-settings-mastery/"><u>A Journey to Windows 11'S God-Like Settings Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376441397-why-arent-window-11-thumbnail-images-displayed-solutions-available/"><u>Why Aren't Window 11 Thumbnail Images Displayed? Solutions Available</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-step-by-step-locating-your-next-social-video-fb-2023-for-2024/"><u>[Updated] Step-by-Step  Locating Your Next Social Video (FB 2023) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-cease-chromes-unintended-tabs/"><u>A Step-By-Step Guide to Cease Chrome's Unintended Tabs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-lively-discourse-evaluation-iteration-8/"><u>In 2024, Lively Discourse Evaluation - Iteration 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-guide-for-windows-11-spotless-restarts/"><u>A Comprehensible Guide for Windows 11 Spotless Restarts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-easy-steps-to-resolve-windows-interface-errors-quickly/"><u>5 Easy Steps to Resolve Windows' Interface Errors Quickly</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-highlighting-the-top-10-budget-friendly-video-communication-platforms-for-industry-and-academia/"><u>[New] Highlighting the Top 10 Budget-Friendly Video Communication Platforms  For Industry & Academia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-discords-non-display-errors-on-pc/"><u>Addressing Discord's Non-Display Errors on PC</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-complete-guide-to-cost-free-sound-capture-using-audacitys-tools/"><u>Updated The Complete Guide to Cost-Free Sound Capture Using Audacitys Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365152122-boost-windows-with-top-2023-ms-store-winners/"><u>Boost Windows with Top 2023 MS Store Winners!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719346952101-chatgpt-lite-free-self-hosted-windows-edition-with-gpt4all/"><u>ChatGPT Lite: Free Self-Hosted Windows Edition with GPT4All</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-experts-choice-optimal-free-digital-sound-cutter-platforms-accessible-via-the-web/"><u>Updated 2024 Approved Experts Choice Optimal, Free Digital Sound Cutter Platforms Accessible via the Web</u></a></li>
</ul></div>
