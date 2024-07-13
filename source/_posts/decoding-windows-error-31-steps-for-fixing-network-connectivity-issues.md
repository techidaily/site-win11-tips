---
title: "Decoding Windows Error 31: Steps for Fixing Network Connectivity Issues"
date: 2024-07-12T17:10:47.630Z
updated: 2024-07-13T17:10:47.630Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding Windows Error 31: Steps for Fixing Network Connectivity Issues"
excerpt: "This Article Describes Decoding Windows Error 31: Steps for Fixing Network Connectivity Issues"
keywords: WinError_31Solution,WindowsNetworkFix,NetworkConnectIssueResolve,31ErrorWindowsTroubleshoot,FixNetWinError31,RestoreWinNetworkLink,ConnectivitySolution31
thumbnail: https://thmb.techidaily.com/c2931b7c0e4d12082380cc3ad2ba8216e12e1526e01d0d5b5d3b87f43d01c2dd.jpg
---

## Decoding Windows Error 31: Steps for Fixing Network Connectivity Issues

 Are you encountering an error message on Windows that reads "network adapter error code 31: this device is not working properly"? This error often occurs due to a corrupted or incorrect version of the network adapter driver installed on your PC.

 As such, let's explore all the ways to fix the network adapter error code 31 on Windows.

## 1\. Check for Any Pending Network Driver Updates

 First off, check to see if your network driver has any pending updates. While you can update the drivers for the device connected to your computer using Device Manager, we don't recommend it, as Device Manager often fails to find the most recent updates for the driver.

 You will most likely find the latest network driver on your computer manufacturer's website, so check who made your PC and visit their website for details. If you use an external network adapter, visit the adapter manufacturer's website instead.

 Additionally, you can also find new drivers using your manufacturer's proprietary system management tool. For example, with Lenovo and HP computers, you can use the Lenovo Vantage and HP Support Assistant utility to find and install new drivers for your network adapter and other devices.

## 2\. Perform a Driver Roll Back

 If you believe a recent driver update is causing the error, you can use the**Roll Back Driver** option to perform a rollback and reinstall the previous version of the network adapter driver.

To perform a network driver rollback:

1. Press**Win + R** to open Run.
2. Type**devmgmt** .**msc** and click**OK** to open Device Manager.
3. In Device Manager, expand the**Network Adapters** section.  
![device manager network adapter properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/device-manager-network-adapter-properties.jpg)
4. Right-click on your network device and select**Properties** .
5. In the**Properties** dialog, open the**Driver** tab.  
![device manager network driver roll back driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/device-manager-network-driver-roll-back-driver-1.jpg)
6. Click the**Roll Back Driver** button. If the option is**greyed out** , your computer doesn't have an older driver to perform a rollback. Check your manufacturer's website to see if they have older drivers in an archive.
7. Next, in the confirmation dialog, give a reason and click**Yes** .
8. Once the driver rollback is complete, check if the problem is resolved. If not, check if you can perform another rollback for the network device driver to see if that helps.

## 3\. Perform a Network Reset

 Windows 10 and 11 feature a "network reset" option. This will remove and reinstall the network drivers and other networking components to their factory defaults to help you fix network adapter issues on your computer.

To perform a network reset:

1. Press**Win + I** to open**Settings** .
2. Open the**Network & internet** tab in the left pane.
3. Click on**Advanced network settings** .
4. ![advanced network settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11.jpg)  
 Next, click on**Network reset** .
5. ![advanced network settings windows 11 network reset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset.jpg)  
 Click on**Reset now** and click**Yes** to rest your network settings.  
![advanced network settings windows 11 network reset reset now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset-reset-now.jpg)
6. Your PC will restart during the process.

## 3\. Delete the Corrupted Network Config File on Older Machines
![delete config value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-config-value-registry-editor.jpg)

 On an older Windows Vista or XP computer, you can resolve the issue by tweaking a registry entry. You need to delete a corrupt config key in Registry Editor and then uninstall the device from Device Manager to fix the error.

 The following steps only apply to a Windows computer running Vista or XP.

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .
3. In Registry Editor, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Network\`
4. In the right pane, locate the**Config** value.
5. Next, right-click on the**Config** value and select**Delete** .
6. Click**Yes** to confirm the action.

 Once the key is deleted, you'll need to remove and reinstall the network driver. You can do it using Device Manager, as shown in the step below.

 Note that modifications to some registry entries may fail due to insufficient permission issues. If you get an error when deleting the Config value, take full ownership of the registry key and then try again. Our guide on [how to take full ownership of registry keys on Windows 10](https://www.makeuseof.com/windows-10-full-ownership-registry/) will work on older systems too.

## 4\. Reinstall Your Network Adapter Driver

 You can manually uninstall your network adapter device and driver to perform a network reset on older Windows versions. You can use the reliable Device Manager to uninstall your network devices.

1. Open Device Manager (see [how to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) for detailed steps).
2. Next, expand the**Network Adapters** section.
3. Right-click on the network adapter and select**Uninstall Device.**  
![uninstall network device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-device-device-manager.jpg)
4. In the confirmation dialog, check the**Attempt to remove the driver for this device** option.  
![uninstall network driver device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-driver-device-device-manager.jpg)
5. Click**Uninstall** to confirm the action.

 Once uninstalled, restart your PC. After the restart, Windows will automatically detect connected but unrecognized devices and install the necessary drivers.

 If Windows fails to install the driver, open**Device Manager** , right-click on your network adapter and select**Update driver** . You can also download the latest drivers from your computer manufacturer's website, as shown in step one.

## 6\. Perform a System Restore

 This error can occur if Windows modifies your network adapter settings during an update. You can use a restore point to undo the changes and restore the computer to its earlier state. Since Windows automatically creates a new restore point before installing an update, you should be able to find a recent restore point to undo the changes.

To perform a restore point:

1. Press the**Win** key and type**restore point.**
2. Click on**Create a restore point** from the search result.
3. In the**System Protection** dialog, click the**System Restore** button.  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
4. In the**System Restore** dialog, click**Next** to view all the available restore points. Additionally, check the**Show more restore points** option to view older restore points.
5. Select the most recent restore point and click**Next** .  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
6. Confirm your restore point and read the description to understand what apps and data on your PC are affected.
7. Click**Finish** to initialize the system restore process. Your PC will restart and may take some time to finish. Your PC will restart and show a system restore success or failure message.

 If the restore process fails, try it again. At times, it may take more than one attempt to get it right. If the computer is restored, it should hopefully restore the old network driver configuration and fix the error.

## Fix the Network Adapter Code 31 Error on Windows

 Network adapter code 31 is one of the many errors that can cause your network adapter to malfunction. To fix the error, check if you have the latest network adapter driver installed. If necessary, perform a driver rollback, clean up corrupt registry value or perform a system restore.

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-dynamic-duo-approach-using-two-photos-in-one-instagram-story/"><u>[New] 2024 Approved  The Dynamic Duo Approach  Using Two Photos in One Instagram Story</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-creating-accessible-multilingual-content-on-igtv/"><u>[Updated] In 2024, Creating Accessible Multilingual Content on IGTV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-increase-the-performance-of-android-studio-on-windows/"><u>How to Increase the Performance of Android Studio on Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-10-best-free-subtitle-makers-to-add-subtitles-to-video-online-for-2024/"><u>New 10 Best Free Subtitle Makers to Add Subtitles to Video Online for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-harmonizing-your-camera-and-drone-with-a-pro-gimbal/"><u>2024 Approved  Harmonizing Your Camera and Drone with a Pro Gimbal</u></a></li>
<li><a href="https://screen-recording.techidaily.com/gameplay-memories-preserved-unveiling-6-minecraft-tips-for-2024/"><u>Gameplay Memories Preserved  Unveiling 6 Minecraft Tips for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-15-pro-to-androidios-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 15 Pro to Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-how-to-optimize-windows-11-settings/"><u>Master Your Machine: How to Optimize Windows 11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-and-resolving-windows-11-thumbnail-missing-issue/"><u>Identifying & Resolving Windows 11 Thumbnail Missing Issue</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-the-best-video-creation-tools-with-music-and-audio-options/"><u>New 2024 Approved The Best Video Creation Tools with Music and Audio Options</u></a></li>
<li><a href="https://screen-recording.techidaily.com/premier-slide-to-video-software/"><u>Premier Slide-to-Video Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-stalling-fixing-microsoft-teams-in-ws11ws10/"><u>Overcoming Stalling: Fixing Microsoft Teams in WS11/WS10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-system-freeze-operation-failed-code-0x0000011b/"><u>Resolving System Freeze: Operation Failed Code 0X0000011B</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-elevate-your-online-presence-making-videos-on-mobile/"><u>[New] Elevate Your Online Presence  Making Videos on Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-code-0xa00f4289-in-wincams/"><u>Navigating Through Code 0xA00F4289 in WinCams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-heart-of-your-system-pc-manager-for-w11/"><u>Configuring the Heart of Your System: PC Manager for W11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-cutting-the-clutter-eschewing-fb-video-ads/"><u>[New] In 2024, Cutting the Clutter  Eschewing FB Video Ads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rapid-launcher-loading/"><u>Mastering the Art of Rapid Launcher Loading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-permission-problems/"><u>Mastery over Windows Permission Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-efficiency-with-these-5-must-have-apps-on-windows-11/"><u>Enhance Efficiency with These 5 Must-Have Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-to-know-your-characters-on-windows-11/"><u>Get to Know Your Characters on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unlocking-cross-media-sharing-power-twitterfacebook/"><u>[New] Unlocking Cross-Media Sharing Power (Twitter/Facebook)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsofts-safe-mode-only-coding/"><u>Navigating Through Microsoft's Safe Mode Only Coding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-broken-disk-organization-in-os/"><u>Addressing Broken Disk Organization in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-administrative-roadblocks-during-software-setup/"><u>Navigating Administrative Roadblocks During Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-poise-and-precision-from-any-corner-of-the-globe/"><u>Navigating with Poise and Precision From Any Corner of the Globe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-download-performance-in-the-microsoft-app-shop/"><u>Maximizing Download Performance in the Microsoft App Shop</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-free-3d-animation-apps-for-android-and-iphone-a-comprehensive-guide-for-2024/"><u>New Free 3D Animation Apps for Android and iPhone A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disable-default-settings-keep-your-usb-running-on-windows-11/"><u>Disable Default Settings - Keep Your USB Running on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-languages-change-navigating-hotkeys-in-windows-11-and-11-pro/"><u>Quick Languages Change: Navigating Hotkeys in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-value-save-on-upgrade-with-windows-11-pro-key/"><u>Maximize Value, Save on Upgrade with Windows 11 Pro Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bypass-oculus-setup-failures-in-windows-1110/"><u>Quick Guide to Bypass Oculus Setup Failures in Windows 11/10</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-motorola-g54-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Motorola G54 5G Phones with/without a PC</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-9-apple-iphone-se-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-ios/"><u>Top 9 Apple iPhone SE Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-bluetooth-pin-verification-hitch-on-win11w10-pcs/"><u>How To Fix Bluetooth PIN Verification Hitch on Win11/W10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-power-to-edit-and-markup-in-windows-based-pdfs/"><u>Regain Power to Edit and Markup in Windows-Based PDFs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/kickstarting-with-gopro-the-top-10-list-of-perks-for-2024/"><u>Kickstarting with GoPro  The Top 10 List of Perks for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-breaking-the-mold-unique-post-vidcon-events/"><u>[Updated] Breaking the Mold  Unique Post-VidCon Events</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-screenplay-excellence-genre-based-achievement-showcase/"><u>[Updated] Screenplay Excellence  Genre-Based Achievement Showcase</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-methods-for-windows-easy-access-center-entry/"><u>5 Methods for Windows Easy Access Center Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eject-incompatible-setup-warnings-in-win11/"><u>Eject Incompatible Setup Warnings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-silent-audio-devices-pc-edition/"><u>Revive Silent Audio Devices – PC Edition</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-how-to-record-desktop-on-windows-8-effortlessly-for-2024/"><u>[Updated] How To Record Desktop on Windows 8 Effortlessly for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-windows-11s-photo-application-blurring-feature/"><u>Expert Guide to Windows 11'S Photo Application Blurring Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-signed-file-barrier-for-system-upgrades/"><u>Overcoming Non-Signed File Barrier for System Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-classic-diablo-a-beginners-guide/"><u>Mastering Classic Diablo: A Beginner's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-connection-issues-dissolving-ea-errors/"><u>Winning Over Connection Issues: Dissolving EA Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-spontaneous-file-explorer-opens/"><u>Disabling Spontaneous File Explorer Opens</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/how-to-guide-elevating-gameplay-recordings-via-obs-for-2024/"><u>How-To Guide  Elevating Gameplay Recordings via OBS for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-from-mundane-to-marvelous-proven-methods-to-record-everyday-life-and-adventures-in-sims-4/"><u>[Updated] In 2024, From Mundane to Marvelous  Proven Methods to Record Everyday Life and Adventures in Sims 4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-8-strategies-for-neutralizing-pink-displays/"><u>Windows Woes: 8 Strategies for Neutralizing Pink Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-file-tracking-the-ultimate-guide-to-copying-windows-11-filesystem-trails-6-methods/"><u>Winning at File Tracking: The Ultimate Guide to Copying Windows 11 Filesystem Trails (6 Methods)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/a-step-by-step-guide-to-elevate-your-stream-on-youtube-for-2024/"><u>A Step-by-Step Guide to Elevate Your Stream on YouTube for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Honor X8b | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-webp-visualization-with-these-excellent-tools/"><u>Enhance WebP Visualization with These Excellent Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-windows-error-0x80040610-for-outlook/"><u>Mastering the Resolution of Windows Error 0X80040610 for Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-lowered-cpu-demand-for-windows-hosts/"><u>Navigating Lowered CPU Demand for Windows Hosts</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-stream-anything-the-ultimate-chromecast-video-playback-guide/"><u>In 2024, Stream Anything The Ultimate Chromecast Video Playback Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-digital-marketing-triumphs-for-2024/"><u>The Ultimate Guide to Digital Marketing Triumphs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-to-standard-power-plans-guide-for-win-11/"><u>Rebooting to Standard Power Plans: Guide for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-uninstall-quickly-in-windows-11/"><u>Navigating to Uninstall Quickly in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-elevate-views-not-video-length-expert-guide-to-yt-desc-templates/"><u>2024 Approved  Elevate Views, Not Video Length  Expert Guide to YT Desc Templates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-defective-gestures-in-microsofts-os/"><u>Fixing Defective Gestures in Microsoft's OS</u></a></li>
</ul></div>
