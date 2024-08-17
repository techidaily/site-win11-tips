---
title: Resolving Non-Primary App Uses Computer Audio Devices
date: 2024-08-16T01:55:15.415Z
updated: 2024-08-17T01:55:15.415Z
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

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
4. Click the**Startup** type drop-down and select**Automatic** .
5. Click**Apply** and**OK** to save the changes.  
![windows audio service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-startup-type-automatic.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. If the service is not running, right-click on**Windows Audio** and select**Start** .
7. Close the Services snap-in and restart your PC. After the restart, your audio device should start working again.

## 4\. Disable and Re-Enable the Sound Output Device

 You can temporarily disable and re-enable the audio device to fix any glitches causing the device to malfunction. You can [disable the audio device](https://www.makeuseof.com/enable-disable-sound-output-devices-in-windows/) using the Settings app and Device Manager.

 To disable the audio device, right-click on the audio device and select**Disable device** in**Device Manager** . Next, right-click on the audio device and**Enable Device** . Close Device Manager and check for any improvements.

## 5\. Uninstall and Reinstall the Audio Device and Driver
![Uninstalling an audio device in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/uninstalling-audio-device-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform a Driver Rollback

 If you have an external sound card and have installed an update, try a driver rollback. A new driver update can sometimes create more problems than it intends to fix. You can use the device driver rollback feature in Device Manager to undo the changes and reinstall the older version of the driver.

 You can [roll back a driver using Windows Device Manager](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . In Device Manager, expand the**Sound, Video, and Game Controllers** section. Next, access your external sound card properties to perform a rollback.

 If the Roll Back Driver option is greyed out, it means the option is unavailable for the selected device. In this instance, uninstall the existing audio device driver and download an older version of the driver from your sound card manufacturer's website. Your sound card manufacturer may also have a newer driver version available. If available, install the latest version and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-luminous-likes-three-proven-ways-for-insta-highlights/"><u>[New] 2024 Approved  Luminous Likes  Three Proven Ways for Insta Highlights</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-a-deep-dive-into-selecting-tiktok-screenshots/"><u>[New] A Deep Dive Into Selecting TikTok Screenshots</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-best-titles-google-cardboards-most-immersive-vr-games/"><u>[New] Best Titles  Google Cardboard's Most Immersive VR Games</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-innovative-facebook-enhancement-using-letterbox-technique/"><u>[Updated] 2024 Approved  Innovative Facebook Enhancement  Using Letterbox Technique</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-master-the-pinning-process-for-a-personal-touch-in-snapchat/"><u>[Updated] 2024 Approved  Master the Pinning Process for a Personal Touch in Snapchat</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-from-raw-to-refined-mastering-the-art-of-pc-video-editing-on-windows/"><u>[Updated] From Raw to Refined  Mastering the Art of PC Video Editing on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-instagram-watchers-unveiling-who-sees-your-content/"><u>[Updated] In 2024, Instagram Watchers  Unveiling Who Sees Your Content</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unveiling-hidden-gems-instagrams-download-secrets/"><u>[Updated] In 2024, Unveiling Hidden Gems  Instagram's Download Secrets</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-guide-to-vr-and-ar-game-apps-for-phones/"><u>[Updated] The Ultimate Guide to VR and AR Game Apps for Phones</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-starting-with-a-gopro-essential-upgrades-for-new-filmmakers/"><u>2024 Approved  Starting with a GoPro  Essential Upgrades for New Filmmakers</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-on-iphone-7-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out On iPhone 7 How to Bypass?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-no-privileges-errors-in-win11-systems/"><u>Correcting No Privileges Errors in Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-gpresult-a-key-to-gpo-data-interpretation/"><u>Decoding GPResult: A Key to GPO Data Interpretation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-mechanics-of-windows-exepe/"><u>Decoding the Mechanics of Windows EXE/PE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-linguistic-transitions-mastering-windows-hotkey-combinations/"><u>Effortless Linguistic Transitions: Mastering Windows Hotkey Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-11-to-dolby-atmos-system-level/"><u>Elevate Windows 11 to Dolby Atmos System Level</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-connectivity-configure-dns-on-windows-11/"><u>Enhancing Connectivity: Configure DNS on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/erase-incompatibility-warning-label-in-win11-os/"><u>Erase Incompatibility Warning Label in Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-non-microsoft-verified-application-warnings/"><u>Handling Non-Microsoft Verified Application Warnings</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-oppo-find-x6-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-windows-11-taskbar-stability/"><u>Improving Windows 11 Taskbar Stability</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tapping-into-community-spirit-a-guide-to-thriving-fb-gifting-campaigns/"><u>In 2024, Tapping Into Community Spirit  A Guide to Thriving FB Gifting Campaigns</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tutorial-for-downloading-movie-maker-6-on-windows/"><u>In 2024, Tutorial for Downloading Movie Maker 6 on Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-windows-10-webcam-recording-made-easy-top-10-software/"><u>New 2024 Approved Windows 10 Webcam Recording Made Easy Top 10 Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-local-sam-service-issues/"><u>Overcoming Local SAM Service Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-quit-required-error-when-using-roblox/"><u>Overcoming Quit Required Error when Using Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productivity-prodigies-unveiling-the-wins-best-software-solutions/"><u>Productivity Prodigies: Unveiling the Win's Best Software Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-a-zero-cost-locally-accessible-gpt-on-your-pc-use-gpt4all/"><u>Run a Zero-Cost, Locally Accessible GPT on Your PC – Use GPT4All.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/start-menu-sleight-stealthy-key-concealment/"><u>Start Menu Sleight: Stealthy Key Concealment</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/streaming-success-seekers-deciphering-the-platform-winner-vimeo-vs-youtubeplusdailymotion-for-2024/"><u>Streaming Success Seekers  Deciphering The Platform Winner - Vimeo vs YouTube+Dailymotion for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-speed-conquering-windows-11-slowdowns-immediately/"><u>Streamline Speed: Conquering Windows 11 Slowdowns Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-11-management-processes-settings-and-custom-themes/"><u>Streamlining Windows 11 Management: Processes, Settings, & Custom Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-slate-device-implementing-windows-11s-user-friendly-taskbar/"><u>Transforming Your Slate Device: Implementing Windows 11'S User-Friendly Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-secrets-where-are-bsod-logs-stored/"><u>Unlocking the Secrets: Where Are BSOD Logs Stored?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-win11s-secrets-to-eliminate-bluescreen-issues/"><u>Unlocking Win11's Secrets to Eliminate Bluescreen Issues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unraveling-ai-chat-expertise-gpt-versus-bings-bot/"><u>Unraveling AI Chat Expertise: GPT versus Bing's Bot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-warriors-fixed-wobbling-arrows-await/"><u>Window Warriors, Fixed Wobbling Arrows Await</u></a></li>
</ul></div>
