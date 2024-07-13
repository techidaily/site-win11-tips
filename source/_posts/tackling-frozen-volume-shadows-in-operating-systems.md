---
title: Tackling Frozen Volume Shadows in Operating Systems
date: 2024-07-12T17:13:29.755Z
updated: 2024-07-13T17:13:29.755Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Frozen Volume Shadows in Operating Systems
excerpt: This Article Describes Tackling Frozen Volume Shadows in Operating Systems
keywords: Freeze Vol Shadow Fix OS,OS Frozen Volume Shades,Resolving Ice Volume Shadows,Frosty Shadow Reduction OS,Thawing OS Vol Shade Issue,De-Freeze Shadows Operating,Eliminate Freezing Shadows OS
thumbnail: https://thmb.techidaily.com/0b4741c5a95a2eb27426575b3e77bfe93d41de0ce8390e58e556e7c4a810a2f7.jpg
---

## Tackling Frozen Volume Shadows in Operating Systems

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot
![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-implementing-bluescreenview-strategies/"><u>Detailed Guide to Implementing BlueScreenView Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-speed-minimizing-applications-via-keyboard-shortcuts/"><u>Unleash Speed: Minimizing Applications via Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-calc-app-for-night-time-viewing-dark-mode-tutorial/"><u>Adapt Calc App for Night-Time Viewing: Dark Mode Tutorial</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-seekingsuperiorcameraspost-mycam-for-2024/"><u>[Updated] SeekingSuperiorCamerasPost-MyCam for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-file-access-failures-in-microsoft-office-outlook/"><u>Correcting File Access Failures in Microsoft Office Outlook</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-demystifying-discord-nitro-perks-and-strategies-for-obtaining-it/"><u>[New] 2024 Approved  Demystifying Discord Nitro  Perks & Strategies for Obtaining It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-loop-of-0xf0831-error-in-win11-os/"><u>Breaking the Loop of 0XF0831 Error in Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-decoding-password-demand/"><u>Winning Back Access: Decoding Password Demand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-remedying-directdraw-disruptions-in-win1011/"><u>Expert Guide: Remedying DirectDraw Disruptions in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-yuzu-fps-on-pc-systems/"><u>Enhancing Yuzu FPS on PC Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-high-cpu-usage-by-windows-ums-for-vanguard-users/"><u>Unraveling High CPU Usage by Windows’ UMS for Vanguard Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-speed-for-swift-steam-content-delivery/"><u>Enhance PC Speed for Swift Steam Content Delivery</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-iptv-transmission-across-devices/"><u>[New] IPTV Transmission Across Devices</u></a></li>
<li><a href="https://fox-access.techidaily.com/high-end-streaming-gear-for-professionals/"><u>High-End Streaming Gear for Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-failures-on-older-windows-versions/"><u>Troubleshooting Installer Failures on Older Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-windows-11s-stealthy-taskbar-spotlight/"><u>Triggering Windows 11'S Stealthy Taskbar Spotlight</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-ig-vids-mastery-for-effective-marketing-step-by-step-guide-to-success-for-2024/"><u>[Updated] IG Vids Mastery for Effective Marketing  Step-by-Step Guide to Success for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-using-windows-11-calendar/"><u>A Practical Approach to Using Windows 11 Calendar</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-end-your-youtube-void-top-10-insights-on-igniting-video-interest-for-2024/"><u>[New] How To End Your Youtube Void  Top 10 Insights on Igniting Video Interest for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-11-to-windows-10-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 11 to Windows 10? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-exploration-of-theta-s-capabilities/"><u>2024 Approved  In-Depth Exploration of Theta S Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inactive-windows-system-voices/"><u>Addressing Inactive Windows System Voices</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-samsung-frp-bypass-by-drfone-android/"><u>About Samsung FRP Bypass</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-lenssnap-feature-examination/"><u>2024 Approved  LensSnap Feature Examination</u></a></li>
<li><a href="https://screen-capture.techidaily.com/exclusive-list-the-premier-gb-emulators-android/"><u>Exclusive List  The Premier GB Emulators, Android</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-snapchat-ad-101-create-stunning-and-effective-snapchat-ads/"><u>2024 Approved  Snapchat Ad 101  Create Stunning & Effective Snapchat Ads</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-vivo-s18-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-barriers-to-running-powershell-scripts-in-windows/"><u>Dismantling Barriers to Running PowerShell Scripts in Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-cricket-ultimate-guide-to-live-streaming-selection-for-2024/"><u>Top Cricket  Ultimate Guide to Live Streaming Selection for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-media-maker-tool-error-x90017-on-windows/"><u>Unraveling Media Maker Tool Error X.90017 On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-potential-masterful-docx-to-pdf-migration/"><u>Unlocking Windows 11'S Potential: Masterful DOCX to PDF Migration</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-innovative-thumbnail-tips-for-mac-users-youtube/"><u>2024 Approved  Innovative Thumbnail Tips for Mac Users - YouTube</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-the-creme-de-la-creme-of-4k-video-content/"><u>2024 Approved The Crème De La Crème of 4K Video Content</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-exploring-whatsapps-sound-transfers/"><u>2024 Approved  Exploring WhatsApp's Sound Transfers</u></a></li>
</ul></div>
