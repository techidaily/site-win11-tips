---
title: Addressing Non-Loading Device Drivers in Windows 11
date: 2024-07-12T17:48:28.352Z
updated: 2024-07-13T17:48:28.352Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Non-Loading Device Drivers in Windows 11
excerpt: This Article Describes Addressing Non-Loading Device Drivers in Windows 11
keywords: Win11 Driver Loading Issues,Addressing DevDriver Errors,Windows 11 Unloading Problems,Fix Non-Loading Drivers in Win11,Device Driver Installation W11,Resolve Driver Not Loading Win11,Troubleshoot Unloaded Win11 Drivers
thumbnail: https://thmb.techidaily.com/1382e80fe89cdc85e3f86df652866f8b806d3041c2bfdfcea85ed48c584b9f54.JPG
---

## Addressing Non-Loading Device Drivers in Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

## 2\. Disable the Memory Integrity Feature

 Memory Integrity is a security feature that leverages virtualization to protect unauthorized programs from making changes to important security processes. But this security setting can prevent a driver from loading old or unsigned drivers from running on your PC.

 So, you must disable Memory Integrity. Repeat the following steps:

1. Press **Win + I** to open the Settings app.
2. Click on the **Privacy & security** option in the left-hand side menu.
3. Now, click on the **Windows Security** option.
4. Scroll down and click on the **Device Security** option.
5. Navigate to the Core Isolation section. Click on the **Core isolation details** option.
6. Disable the **toggle** present below the **Memory Integrity** option.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/disable-memory-integrity.jpg)
7. **Restart** your PC to apply the changes.

 Now, check if the “a driver cannot load on this device” still pops up.

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

## 4\. Modify the System Registry

 Corrupt registry entries for the device can also be a reason for the hardware device encountering the driver issue. So, you must modify the system registry and remove those corrupt entries for the device.

 Make sure to manually export a [backup of your PC registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) onto a removable drive, so you always have the option to revert to the last working configuration.

 Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User menu**. Click on the **Device Manager** option.
2. Locate the device facing driver issues and double-click on it to open its **Properties**.
3. Switch to the **Details** tab.
4. Click on the drop-down tab and click on the **Class GUID** option. It will display the GUID. **Copy** it to the clipboard.  
![Checking GUID in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/checking-guid-in-device-manager.jpg)
5. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Regedit** and press the **Ctrl + Shift + Enter** keys to open the Registry editor.
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-non-operational-windows-apps/"><u>Steps to Recover Non-Operational Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncharted-errors-the-8-most-crucial-mistakes-for-new-windows-11-users/"><u>Uncharted Errors: The 8 Most Crucial Mistakes for New Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-26/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-seamless-windows-notepad-functioning/"><u>Steps to Ensure Seamless Windows Notepad Functioning</u></a></li>
<li><a href="https://extra-hints.techidaily.com/exemplary-video-capture-top-5-slow-motion-cams/"><u>Exemplary Video Capture  Top 5 Slow Motion Cams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-unlock-a-locked-out-windows-11-with-error-22/"><u>Strategies to Unlock a Locked Out Windows 11 with Error 22</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/ai-portrait-generator-getting-closer-to-the-artistic-marvels/"><u>AI Portrait Generator Getting Closer to the Artistic Marvels</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-multi-lens-modifiers-for-creative-video-effects/"><u>In 2024, Multi-Lens Modifiers for Creative Video Effects</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-iphone-13-pro-and-ipad-securely-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on iPhone 13 Pro and iPad Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/transform-your-footage-how-to-create-stunning-3d-videos-on-windows-for-2024/"><u>Transform Your Footage How to Create Stunning 3D Videos on Windows for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-avc-player-on-devices/"><u>Ultimate AVC Player on Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-meizu-21-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Meizu 21 for Free? | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-explore-online-communities-with-youtube-monetization-opportunities/"><u>[New] 2024 Approved  Explore Online Communities with YouTube Monetization Opportunities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-strategies-for-sustained-top-level-visibility-on-win-os/"><u>Sticky Notes Strategies for Sustained Top-Level Visibility on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-dissecting-iconic-discord-emoticons-and-their-designers/"><u>2024 Approved  Dissecting Iconic Discord Emoticons and Their Designers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-itel-a70-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Itel A70?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-repeatedly-accessing-cmos-settings/"><u>Stop Windows From Repeatedly Accessing CMOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-tutorials-for-new-folder-navigation-in-win11/"><u>Tactical Tutorials for New Folder Navigation in Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-11-best-location-changers-for-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-zte-nubia-z60-ultra-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost ZTE Nubia Z60 Ultra Device</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-seamless-video-playback-a-facebook-feature-explanation/"><u>[New] 2024 Approved  Seamless Video Playback  A Facebook Feature Explanation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-users-with-erratic-gesture-inputs-in-windows/"><u>Assisting Users with Erratic Gesture Inputs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-11-bluetooth-try-connecting-error/"><u>Steps to Resolve Windows 11 Bluetooth 'Try Connecting' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-christmas-ify-your-windows-11/"><u>7 Ways to Christmas-Ify Your Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-money-matters-finns-financial-framework/"><u>[Updated] In 2024, Money Matters  Finn's Financial Framework</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-mastering-the-art-top-5-hand-to-hand-combat-games/"><u>[Updated] Mastering the Art  Top 5 Hand-to-Hand Combat Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-enabledisable-bing-ai-on-windows-11-search-bar/"><u>Turbo Enable/Disable: Bing AI on Windows 11 Search Bar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-set-up-iphone-7-plus-face-id-by-drfone-ios-unlock-ios-unlock/"><u>How to Set up iPhone 7 Plus Face ID?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-invalid-steam-response-issue/"><u>Steps to Resolve Invalid Steam Response Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-from-your-apple-iphone-15-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock from your Apple iPhone 15 and iPad?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-window-lock-out-duration-in-windows/"><u>Customize Window Lock-Out Duration in Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/turning-off-two-factor-authentication-on-apple-iphone-6s-plus-5-tips-you-must-know-by-drfone-ios/"><u>Turning Off Two Factor Authentication On Apple iPhone 6s Plus? 5 Tips You Must Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stabilizing-dwarf-fortress-on-win/"><u>Solutions for Stabilizing Dwarf Fortress on Win</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-master-the-art-of-editing-on-sierra-with-1-5-tools/"><u>2024 Approved  Master the Art of Editing on Sierra with #1-#5 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-2023-convert-facebook-video-to-mp4-720p1080phd-online-and-free/"><u>[New] 2024 Approved  2023 | Convert Facebook Video to MP4 720P/1080p/HD Online and Free?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-troubled-tracker-fixes-for-frozen-torrents/"><u>Tackling the Troubled Tracker: Fixes for Frozen Torrents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-workshop-generating-and-deciphering-system-insights/"><u>The Windows Workshop: Generating & Deciphering System Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-re-entry-to-your-shared-windows-spot/"><u>Seamless Re-Entry to Your Shared Windows Spot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-final-cut-pro-color-grading-essentials-for-2024/"><u>Updated Final Cut Pro Color Grading Essentials for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-realme-gt-5-pro-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Realme GT 5 Pro Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-lol-playtime-uninterrupted-in-windows/"><u>Strategies to Keep LoL Playtime Uninterrupted in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-evolutionary-leap-with-ai-copilot-in-windows-11-life/"><u>The Evolutionary Leap with AI Copilot in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-routines-to-pause-windows-and-office-software-updates/"><u>4 Routines to Pause Windows & Office Software Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-calculator-activation/"><u>Steps for Windows 11 Calculator Activation</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-upgrade-your-call-game-with-these-top-6-android-and-ios-voice-changing-tools-for-2024/"><u>New Upgrade Your Call Game with These Top 6 Android & iOS Voice-Changing Tools for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-affordable-tactics-for-combining-media-with-literature/"><u>In 2024, Affordable Tactics for Combining Media with Literature</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-step-by-step-tiktok-usage-for-mac-and-pc-users/"><u>2024 Approved  Step-by-Step TikTok Usage for Mac and PC Users</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/producing-an-expressive-tiktok-conclusion-snippet-for-2024/"><u>Producing an Expressive TikTok Conclusion Snippet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719307808288-tackling-windows-glitches-find-solutions-now/"><u>Tackling Windows Glitches: Find Solutions Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-open-minds-open-tech-easeus-report/"><u>In 2024, Open Minds, Open Tech - EaseUS Report</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-device-based-access-commence-google-meet-chat/"><u>[New] In 2024, Device-Based Access  Commence Google Meet Chat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-pc-manager-on-windows-11-a-quick-guide/"><u>Setting Up PC Manager on Windows 11 – A Quick Guide</u></a></li>
</ul></div>
