---
title: Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11
date: 2024-07-12T16:51:33.156Z
updated: 2024-07-13T16:51:33.156Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11
excerpt: This Article Describes Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11
keywords: Fix CCleaner Woes,Repair CCleaner Windows,Restore CCleaner Function,Win10/Win11 CCleaner Fixed,Non-Working CCleaner Fixes,Enhance Windows Cleanup,Reinstate CCleaner Windows
thumbnail: https://thmb.techidaily.com/7b53187b4430cc2c3cbe56db79b5743ab13bdfc8c137447758d708535575ea61.png
---

## Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11

 CCleaner is one of the most widely utilized third-party system maintenance software packages for Windows 10 and 11 PCs. However, some users have reported on help forums they can’t utilize CCleaner because it’s not working for them. The CCleaner window doesn’t open when that software isn’t working.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.

## 1\. Try Opening CCleaner From Its Installation Directory

 Many users open CCleaner with desktop, taskbar, or Start menu shortcuts. However, CCleaner might not launch because of an issue with its shortcut. So, try opening CCleaner directly from its installation folder to see if that makes any difference. To do so, you’ll need to double-click the **CCleaner64.exe** application file within the software’s installation directory.

![The CCleaner.exe file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ccleaner-exe-file.jpg)

 If you can launch CCleaner from the installation directory, there must be an issue with the shortcut for opening that software. In this case, set up a new Windows desktop shortcut by right-clicking the CCleaner EXE file and selecting **Send to (Desktop)**. Then try opening the software with the new CCleaner shortcut.

## 2\. Run CCleaner With Administrator Rights

 It’s not usually an essential requirement to run CCleaner with admin rights for that software to work. However, sometimes CCleaner can fail to start because of permissions issues that running it as an administrator might address. You can quickly see if this potential resolution works by right-clicking CCleaner’s shortcut or the EXE file in the installation directory and selecting **Run as administrator**.

 If that works, set CCleaner to always run with elevated privileges. Then you won’t need to manually select to run CCleaner with admin rights every time you need to open it. This guide about [how to always run apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) includes instructions for permanently setting programs to start with elevated privileges.

![The RUn this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/run-this-program-as-adminstrator-option.jpg)

## 3\. Delete the CCleanerx64 Registry Key

 Many users have confirmed they’ve fixed CCleaner not working by deleting a CCleanerx64 registry key. Although a confirmed fix, we still recommend backing up the Windows registry before deleting keys. Then erase the CCleaner registry key as follows:

1. First, hold the **Windows** logo key and press **R** to start the Run accessory.
2. Type **regedit** into Run’s **Open** command box and click **O**K.
3. Then go to this registry location either by entering it into the address bar or by clicking the keys in the sidebar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`  
![The Image File Execution Options registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-image-file-executions-key.jpg)
4. Right-click on the **CCleaner64.exe** key and select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-ccleaner.jpg)
5. Select **Yes** on the Confirm Key Delete window prompt.
6. Click the Registry Editor app’s **X** Close window button and try opening CCleaner.

## 4\. Add CCleaner to Your Antivirus Software’s Exceptions List

 Antivirus programs that flag CCleaner as unwanted software can block that app from running. That’s more likely considering that this Piriform software has had its malware incidents in the past. Microsoft Defender was widely reported to flag CCleaner as unwanted software in 2020\. Some users have also confirmed disabling Trend Micro antivirus fixed CCleaner not working on their PCs.

 So, you might need to add CCleaner’s installation folder to your antivirus software’s exceptions list to fix that app not working. Our [guide to setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) provides guidelines for whitelisting software from the Microsoft Defender antivirus. If you utilize a third-party security app, add CCleaner to that software’s antivirus exclusion list.

![The Add an exclusion button in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-an-exclusion-button.jpg)

## 5\. Disable Your Active Firewalls

 CCleaner needs internet connectivity for updates, bug reporting, and its online features. Therefore, firewall blocks can be another cause for CCleaner not working. Disabling your PC’s firewall will ensure that it isn’t blocking CCleaner’s internet connectivity.

 This guide for [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) provides full instructions for turning off that firewall protection. Users with third-party firewalls installed can select to turn them off via their settings tabs. If you’ve installed third-party antivirus software, disable its firewall component if it has one.

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-defender-firewall3.jpg)

 Run CCleaner after turning off the firewall on your PC. The firewall was most likely causing the issue if the CCleaner software works when it's disabled. Add CCleaner to your firewall’s allowed app list to utilize that software with the firewall enabled. Our article about [allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) tells you how to add programs to Microsoft Defender Firewall’s allowed list.

## 6\. Run CCleaner After Clean-Booting Windows

 An app conflicting with the Piriform software could be another possible reason for CCleaner not working on your PC. Clean-booting Windows 11/10 will likely eliminate that potential cause. Setting a clean boot will disable most third-party startup programs and services that run in the background. Clean boot is like entering Windows safe mode, but it doesn’t disable any device drivers.

 To apply this possible solution for CCleaner not working, follow the instructions in this [how-to perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) guide. Restart Windows after disabling startup items via Task Manager and MSConfig, and then try opening CCleaner again. If the CCleaner software works after the clean boot, a disabled app or service is likely the culprit.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/services-tab4.jpg)

 What you do then is up to you. You can leave the boot setup as set or try to find out what was conflicting with the CCleaner software. To find what’s causing the issue, re-enable disabled startup items in a one-at-a-time fashion before every reboot until CCleaner stops working again. Then either permanently disable or uninstall the conflicting service or app.

## 7\. Reinstall CCleaner

 If CCleaner still isn’t working after applying the other troubleshooting methods in this guide, you might have to reinstall the software. This will refresh all CCleaner’s files and registry entries. You can remove CCleaner with most of the methods outlined in this article about [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). We recommend uninstalling with one of the best uninstaller utilities to remove all leftover debris.

![The Uninstall option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/programs-and-features-applet.jpg)

 You can reinstall a CCleaner UWP or desktop app. To get the desktop app, click **Free Download** on this [CCleaner page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2029956/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwu4WoBhBkEiwAojNdXkgjDRZcy77PTMyhMnePxm%5FBXllDabqSn%5FMd9yAkWVbfhL5dYhBFjBoCYbYQAvD%5FBwE). Double-click the **ccsetup615.exe** file in the folder it downloads to view the setup window. Then you can click **Install** within the setup wizard to reinstall CCleaner.

 If you want to try the UWP app instead, open the [CCleaner Microsoft Store page](https://apps.microsoft.com/store/detail/ccleaner/XPFCWP0SQWXM3V), click on the **Get in Store app**, and **Open Microsoft Store** options to access an installation option for CCleaner. Press the **Install** button for the app.

## Clean Up Your PC With CCleaner Again

 There’s no guaranteed way to fix CCleaner not working. However, the troubleshooting methods above will probably kick-start the CCleaner software for Windows 11/10 in most cases. Then you can clean up your Windows 11/10 PC with all the tools CCleaner has to offer again.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/updated-finding-and-accessing-your-personalized-musical-selection-zone-on-youtube-for-2024/"><u>[Updated] Finding and Accessing Your Personalized Musical Selection Zone on Youtube for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-enhancing-video-reach-convert-yt-to-igtv-for-2024/"><u>[Updated] Enhancing Video Reach  Convert YT to IGTV for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/adventures-in-virtuality-the-cream-of-the-crop-for-android-games-for-2024/"><u>Adventures in Virtuality  The Cream of the Crop for Android Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-clis-for-efficient-task-management-windows-11/"><u>Integrating CLIs for Efficient Task Management (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-most-popular-firefox-visual-recorders/"><u>[Updated] Most Popular Firefox Visual Recorders</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-for-students-discover-the-top-10-historical-youtube-channels-now/"><u>[Updated] For Students, Discover the Top 10 Historical YouTube Channels Now</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/maximize-your-impact-strategic-approaches-to-facebook-bios-for-2024/"><u>Maximize Your Impact  Strategic Approaches to Facebook Bios for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-dissecting-iconic-discord-emoticons-and-their-designers/"><u>[Updated] 2024 Approved  Dissecting Iconic Discord Emoticons and Their Designers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-laughing-matters-the-viral-meme-scoreboard/"><u>[Updated] 2024 Approved  Laughing Matters  The Viral Meme Scoreboard</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-easy-to-follow-setting-up-snapchat-on-a-mac/"><u>[Updated] 2024 Approved  Easy to Follow  Setting up Snapchat on a Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-route-to-your-windows-disk-space-win-1011/"><u>Quick Route to Your Windows Disk Space (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-x80072f30-in-windows/"><u>Resolving Microsoft Store Error X80072F30 in Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-transform-your-videos-with-slow-motion-a-free-guide-to-filmora/"><u>Updated 2024 Approved Transform Your Videos with Slow Motion A Free Guide to Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-instant-uninstalling-via-windows-shortcuts/"><u>The Guide to Instant Uninstalling via Windows Shortcuts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/seize-endless-photographic-content-from-elite-4-video-clips-for-2024/"><u>Seize Endless Photographic Content From Elite 4 Video Clips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-affected-device-access-post-error-code-22/"><u>How to Reset Affected Device Access Post-Error Code 22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-shortage-of-physical-storage-space-vm-errors/"><u>Resolving Shortage of Physical Storage Space (VM) Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-calendar-app-on-windows-11/"><u>How to Use the Calendar App on Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-oppo-k11-5g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Oppo K11 5G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-filmoras-quick-start-approach-for-youtube-trailers/"><u>[Updated] In 2024, Filmora's Quick-Start Approach for YouTube Trailers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-explorer-onedrive-as-a-launchpad/"><u>Mastering File Explorer: OneDrive as a Launchpad</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-best-free-recorder-options-watermark-free/"><u>In 2024, Best Free Recorder Options (Watermark-Free)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-11s-task-manager-launch-interface/"><u>Adjusting Windows 11'S Task Manager Launch Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-sound-level-configurations-in-windows/"><u>Restoring Default Sound Level Configurations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-no-write-error-a-guide-for-windows-users/"><u>Tackling the No Write Error: A Guide for Windows Users</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/exporting-snapchat-content-to-your-phones-gallery/"><u>Exporting SnapChat Content to Your Phone's Gallery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-install-microsoft-defender-application-guard-for-edge-in-windows-11/"><u>How to Install Microsoft Defender Application Guard for Edge in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-file-explorer-in-windows-10plus/"><u>Jumpstart File Explorer in Windows 10+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-vlc-unrecognized-media-issue/"><u>Overcoming Windows VLC Unrecognized Media Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-poco-c55-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Poco C55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-maximize-collaboration-via-zooms-share-feature/"><u>[New] 2024 Approved  Maximize Collaboration via Zoom's Share Feature</u></a></li>
</ul></div>
