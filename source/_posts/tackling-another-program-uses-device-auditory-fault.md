---
title: Tackling 'Another Program Uses Device' Auditory Fault
date: 2024-08-16T01:38:59.217Z
updated: 2024-08-17T01:38:59.217Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling 'Another Program Uses Device' Auditory Fault
excerpt: This Article Describes Tackling 'Another Program Uses Device' Auditory Fault
keywords: Device Use Errors,Audio Device Fault,Devices Conflict Sound,Cross-Program Audio Issue,Unauthorized Device Access,Interference in Audio Programming,Managing Audio Device Errors
thumbnail: https://thmb.techidaily.com/4cdd8afbaa8b657928993c65ff49e85d13ed5759387c65adfd46afd484910746.jpg
---

## Tackling 'Another Program Uses Device' Auditory Fault

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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. Select the audio device in the**Sound** dialog and click the**Properties** button.
5. Open the**Advanced** tab in the**Properties** dialog.  
![disable exclusive mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-exclusive-mode.jpg)
6. Uncheck the **Allow application to take exclusive control of this device** and**Give exclusive mode application priority** options.
7. Click**Apply** and**OK** to save the changes.

 Restart your computer and check if the error is resolved and if the audio device is working again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Change Windows Audio Service Startup Type

 Windows Audio service is responsible for managing audio devices connected to your computer. If the service is disabled or not running, your audio device can stop working.

 By default, it is set to start automatically as you power on your device. Check if the Startup type for Windows Audio is set to Manually. If yes, reconfigure it to start automatically to fix audio problems.

To change the Windows Audio service Startup type:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** to open the**Services** snap-in.
3. In the**Services** window, locate and double-click on**Windows Audio** service.  
![windows audio service properties services snap in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-properties-services-snap-in.jpg)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If it is a Windows-specific issue, installing pending Windows updates can fix the problem. Check the Windows updates page for newer updates and install them to see if that helps resolve the issue.

 To install Windows update, go to**Settings > Windows Update** and click**Check for updates** . Windows will populate the screen with all the pending updates. You can install the updates or selectively install any audio device updates.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Check for Third-Party App Conflict
![volume mixer windows 11 view audio applications](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/volume-mixer-windows-11-view-audio-applications.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 If the issue persists, check if there is a third-party app conflict. You can use Volume Mixer to view applications accessing the audio devices and close the problematic app to fix the problem. Here’s how to do it.

1. Press**Win + R** to open Run.
2. Type**sndvol** and click**OK** to open Volume Mixer.
3. The**Application** column will show all the apps using your audio device.

 To close the app, open the system tray, right-click the app icon, and select**Quit** . You can also force close the app using Task Manager. If the issue persists, uninstall the problematic app to restore the audio to your computer.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-comprehensive-guide-to-youtubes-subscription-advantages/"><u>[New] 2024 Approved  Comprehensive Guide to YouTube's Subscription Advantages</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-designing-dynamic-denouements/"><u>[New] Designing Dynamic Denouements</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ow-to-trim-youtube-videos-for-2024/"><u>[New] How to Trim YouTube Videos for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-optimal-screen-capture-techniques-tunefab-style/"><u>[New] In 2024, Optimal Screen Capture Techniques - Tunefab Style</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-lively-registration-and-unregistration-guide/"><u>[New] Lively Registration & Unregistration Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-overcoming-instagram-video-errors-solutions-now-for-2024/"><u>[New] Overcoming Instagram Video Errors  Solutions Now for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ultimate-collection-free-3d-text-psds-galore/"><u>[New] Ultimate Collection  FREE 3D Text PSDs Galore</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-fives-finest-tools-for-rapid-video-frame-capturing/"><u>[Updated] 2024 Approved  Five's Finest Tools for Rapid Video Frame Capturing</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-snapchat-setup-guide-for-mac-devices/"><u>[Updated] 2024 Approved  Snapchat Setup Guide for Mac Devices</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-unlocking-video-dominance-hashtag-hacks-exposed/"><u>[Updated] In 2024, Unlocking Video Dominance  Hashtag Hacks Exposed</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-smooth-watchers-guide-to-pacing-down-videos-on-youtube-60-chars-minor-exception-due-to-title-length-but-provides-rich-context/"><u>[Updated] The Smooth Watcher's Guide to Pacing Down Videos on YouTube (60 Chars, Minor Exception Due to Title Length but Provides Rich Context)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-top-10-yoga-youtube-channel-to-help-you-stay-fit/"><u>[Updated] Top 10 Yoga YouTube Channel to Help You Stay Fit</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-5-free-screen-recorders-on-windows-10/"><u>[Updated] Top 5 Free Screen Recorders on Windows 10</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-complete-beginners-reference-to-final-cut-pro/"><u>2024 Approved  Complete Beginner's Reference to Final Cut Pro</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-using-inbuilt-recorders-for-screen-capture-on-huaweis-mate-and-p-series-devices/"><u>2024 Approved  Using Inbuilt Recorders for Screen Capture on Huawei's Mate and P Series Devices</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-motorola-moto-g84-5g-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Motorola Moto G84 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-window-into-evolution-noteworthy-windows-11-file-enhancements/"><u>A Window Into Evolution: Noteworthy Windows 11 File Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inadequate-usb-support-on-desktops/"><u>Addressing Inadequate USB Support on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-reactivating-deactivated-voice-command/"><u>Addressing Windows 11: Reactivating Deactivated Voice Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-variance-in-procedures-for-local-and-remote-windows-reinstallations/"><u>Analyzing the Variance in Procedures for Local and Remote Windows Reinstallations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Avoidance of Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-hurdles-of-xbox-game-pass-error-code-0-essential-tips-for-windows-11-users/"><u>Avoiding the Hurdles of Xbox Game Pass Error Code 0: Essential Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-old-file-management-interface/"><u>Bringing Back Old File Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-windows-problems-effective-assistance-guide/"><u>Conquer Windows Problems: Effective Assistance Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-fatal-javascript-issue-with-ease-on-win-11-discord/"><u>Conquering Fatal Javascript Issue with Ease on Win 11 Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-camera-omission-from-windows-dm-display/"><u>Correct Camera Omission From Windows' DM Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-taming-high-cpu-use-in-modern-windows-host/"><u>Deciphering and Taming High CPU Use in Modern Windows Host</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-webbrowsers-for-lighter-system-resource-use-on-os-x-windows-chromeos/"><u>Efficient Webbrowsers for Lighter System Resource Use on OS X, Windows, ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-scripts-the-winexe-transformation-tutorial/"><u>Elevate Your Scripts: The WinEXE Transformation Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-checks-when-windows-obs-studio-wont-launch/"><u>Essential Checks When Windows' OBS Studio Won't Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tricks-to-jumpstart-a-nonfunctional-terminal/"><u>Essential Tricks to Jumpstart a Nonfunctional Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-portals-to-nintendo-switch-gaming/"><u>Essential Windows Portals to Nintendo Switch Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-failed-security-codes-in-epic-games-launcher-on-windows-pcs/"><u>Fixes for Failed Security Codes in Epic Games Launcher on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-fixing-windows-error-code-0xc00000f-instantly/"><u>Guidelines to Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-resolve-windows-11-search-tool-errors/"><u>Guides to Resolve Windows 11 Search Tool Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-colored-display-in-windows-based-devices/"><u>How to Adjust Colored Display in Windows-Based Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-an-additional-monitor-without-gui-chipset/"><u>How to Use an Additional Monitor Without GUI Chipset</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-elevating-presentations-with-adobe-captivate-skills/"><u>In 2024, Elevating Presentations with Adobe Captivate Skills</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-leverage-your-influence-top-10-igtv-video-tactics-for-brands/"><u>In 2024, Leverage Your Influence  Top 10 IGTV Video Tactics for Brands</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-unveiling-the-high-res-sky-scenes-with-mi-drone/"><u>In 2024, Unveiling the High-Res Sky Scenes with Mi Drone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-snapchat-enhancing-images-and-videos-for-2024/"><u>Mastering Snapchat  Enhancing Images & Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-stuck-windows-enter-function/"><u>Mending the Stuck Windows 'Enter' Function</u></a></li>
<li><a href="https://fox-http.techidaily.com/mold-personal-memes-that-resonate-for-2024/"><u>Mold Personal Memes That Resonate for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-options-picking-right-nvidia-driver-type-for-you/"><u>Navigating Options, Picking Right Nvidia Driver Type For You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-virtualbox-usb-connection-issue-on-windows-devices/"><u>Overcoming VirtualBox USB Connection Issue on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-mic-malfunctions-in-windows-os/"><u>Overcoming Xbox Mic Malfunctions in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-methods-to-identify-system-gadgets/"><u>Proven Windows Methods to Identify System Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-command-gain-admin-status/"><u>Regain Command - Gain Admin Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resolving-user-not-found-issue-windows-1011/"><u>Steps for Resolving 'User Not Found' Issue: Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-winscomrssvdll-issues-during-system-boot/"><u>Steps to Address WinscomrssvDll Issues During System Boot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-longer-pins-in-windows-11-and-11/"><u>The Ultimate Checklist: Longer PINs in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-intel-unison-for-windows-11-calling/"><u>The Ultimate Guide to Intel Unison for Windows 11 Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-brightness-managers-for-windows-multiscreen-professionals/"><u>The Ultimate List of Brightness Managers For Windows Multiscreen Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-steam-downloads-for-windows-users/"><u>Turbo-Charging Steam Downloads for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-microsofts-ai-assistive-functions/"><u>Understanding Microsoft's AI Assistive Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-display-options-with-these-10-tips/"><u>Unlocking Windows 11 Display Options with These 10 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-and-powershell-identifying-what-sets-them-aside/"><u>Windows Terminal and PowerShell: Identifying What Sets Them Aside</u></a></li>
</ul></div>
