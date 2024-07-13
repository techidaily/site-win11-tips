---
title: Ignite Old PCs with Windows 11 Version 22H2
date: 2024-07-12T17:33:58.698Z
updated: 2024-07-13T17:33:58.698Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ignite Old PCs with Windows 11 Version 22H2
excerpt: This Article Describes Ignite Old PCs with Windows 11 Version 22H2
keywords: Ignite Old PCs,Windows 11 Upgrade,22H2 Release,Old PC Revival,Free OS Update,Legacy Systems Focus,Microsoft Windows X
thumbnail: https://thmb.techidaily.com/b940b6b0f5ea7e32cad1821c53c7dd63eece1d15c1851d2a65f8ffeb1e28c4c2.jpg
---

## Ignite Old PCs with Windows 11 Version 22H2

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to [create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

## 1\. Download the Windows 11 22H2 ISO
![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)

 You can [legally download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft server directly or using Media Creation Tool. For this guide, we’ll use Media Creation Tool to download the ISO image file.

1. Go to the [Microsoft Software Download page](https://www.microsoft.com/software-download/windows11) .
2. Click on**Download Now** under**Create Windows 11 Installation Media.**
3. Run the**mediacreationtool.exe** file and accept the license terms.
4. Review the selected language and edition. To change the language, uncheck**Use the recommended options for this PC** and select your preferred language.
5. Click**Next** .
6. Select the**ISO file** option in the**Choose which media to use** dialog.
7. Select the download location and click**Save** . Make sure the selected partition has enough space available.
8. Media Creation Tool will start downloading the ISO to your local drive. This process may take some time, depending on your Internet connection. So wait for the download to complete.
9. Once the download is complete, click**Finish** and follow the next step to download Windows 10 ISO.

## 2\. Download a Windows 10 ISO
![windows 10 download ISO preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-10-download-iso-preference.jpg)

 You’ll need to modify the Windows 11 ISO by replacing the appraiserress.dll with a version available in Windows 10 ISO. This DLL file is responsible for performing a hardware check during an upgrade.

To download Windows 10 ISO:

1. Go to [Windows 10 download page](https://www.microsoft.com/en-us/software-download/windows10) .
2. Click the**Download Now** button under**Create Windows 10 installation media** .
3. Run the**mediacreationtool.exe** file to open Windows 10 Setup dialog.
4. Click on**Accept** .
5. In the**What do you want to do** screen, select**Create installation media** and click**Next** .
6. Check if the language, edition, and architecture preferences are set correctly. If not, click on**Use the recommended options for this** **device** and set your preferences.
7. Next, select the**ISO file** option and click**Next** .
8. Select the download location and click**Save** .
9. The downloading process may take several minutes to complete. So wait for the process to complete and click**Finish** once done.

 Once you have both the ISO files saved, follow the next step to extract and modify the Windows 11 ISO.

## 3\. Modify the Windows 11 ISO to Bypass Hardware Check During the Upgrade

 The following steps involve extracting the Windows 10 ISO and copying the appraiserress.dll file. Next, move the copied DLL file to the Windows 11 ISO’s sources folder. Here’s how to do it.

1. Right-click on the**Windows 10 ISO** file and select**Mount** . This will create a new virtual DVD Drive and open the ISO folder.  
![mount windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/mount-windows-10-iso.jpg)
2. Open the**Sources** folder and locate the**appraiserres.dll** file. Copy the**DLL** file and move it to a different folder.  
![copy appraiserres dll windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-appraiserres-dll-windows-10-iso.jpg)
3. Next, extract the Windows 11 ISO to a different folder. You can [use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
![extract windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/extract-windows-11-iso.jpg)
4. Open the Windows 11 ISO's extracted folder and then the**Source** folder.
5. Next, copy and paste the**appraiserres.dll** file copied from Windows 10 ISO into Windows 11 ISO's**Sources** folder.

1. Select**Replace the file in the destination** to confirm the action.  
![replace the file in the destination appraiserrs ll windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-the-file-in-the-destination-appraiserrs-ll-windows-11-iso.jpg)
2. Next, disconnect your PC from the Internet. This prevents the setup from downloading updated files during installation and overwriting the modified dll file.
3. Once the Internet is disabled, open the extracted Windows 11 ISO folder and double-click on the**Setup file** . Click**Yes** if prompted by UAC.
4. In the**Windows 11 Setup** dialog, click on**Change how Setup downloads updates.**  
![windows 11 setup not right now updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-not-right-now-updates.jpg)
5. Next, select**Note right now.** This will prevent the Windows setup from finding and installing newer updates causing the upgrade process to fail on unsupported hardware.  
![windows 11 setup choose what to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-choose-what-to-install.jpg)
6. In the**Choose what to keep** screen, select**Keep personal files and apps.**
7. Click**Next** and then click on**Accept** .  
![windows 11 setup ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-ready-to-install.jpg)
8. Next, click on**Install** to install Windows 11 version 22H2 while keeping your personal files and apps.
9. Leave your computer idle until the installation process is complete. After the restart, you’ll have the latest Windows 11 22H2 running on your computer.

To check your Windows specification:

![check windows specification windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/check-windows-specification-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**About** .
3. Under Windows specifications, you’ll see**Version 22H2** if the upgrade was successful.

## 4\. Go Back to the Previous Version
![go back windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/go-back-windows-11.jpg)

 If you run into an issue after the upgrade, you can use the**Go back** option to undo the update and restore the earlier version of Windows 11\. However, the "Go back" option is only available for seven days since the upgrade. After that, the option will be greyed out.

To go back to the previous version:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Recovery** .
3. Click on**Go back** under**Recovery options** . Then, follow the on-screen instructions to uninstall the Windows 22H2 update.

## Installing Windows 11 22H2 on Unsupported Hardware

 It is easy to bypass the Windows 11 system hardware requirements when you want to perform a clean install. However, to perform an upgrade, you’ll need to modify the appraiserress.dll file and then run the setup.

 While the upgrade is possible for now, the lack of future automatic Windows updates makes maintaining the PC a complicated task. If upgrading to Windows 11 is not a must, you can stick to Windows 10 on older hardware, which will continue to receive support until late 2025.


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
<li><a href="https://extra-skills.techidaily.com/2024-approved-pivot-from-srt-to-professional-audio-standards-with-confidence/"><u>2024 Approved  Pivot From SRT to Professional Audio Standards with Confidence</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-secure-your-favorite-igtv-videos-download-strategies-for-pcmac-os-users/"><u>In 2024, Secure Your Favorite IGTV Videos  Download Strategies for PC/Mac OS Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-from-marks-acquiring-unmarked-stock-photography/"><u>2024 Approved  Free From Marks  Acquiring Unmarked Stock Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298161302-overcoming-grayed-out-screensaver-in-win-os-top-fixes/"><u>Overcoming Grayed-Out Screensaver in Win OS: Top Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306931208-opening-troubled-chrome-remediation-tips-for-win11-users-here/"><u>Opening Troubled Chrome: Remediation Tips for Win11 Users Here.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-fast-assist-procedure/"><u>Activating Windows 11’S Fast Assist Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tricks-to-correct-your-pcs-pink-screen-misstep/"><u>5 Tricks to Correct Your PC's Pink Screen Misstep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-the-most-ignored-yet-crucial-windows-11-features/"><u>A Guide to the Most Ignored Yet Crucial Windows 11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimum-ssd-speed-on-windows-via-ssdfresh/"><u>Achieve Optimum SSD Speed on Windows via SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284654722-software-environment-setup/"><u>Software Environment Setup:</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-methods-for-image-warping/"><u>[New] Innovative Methods for Image Warping</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-manual-for-ws11s-software-reset/"><u>A Step-By-Step Manual for WS11's Software Reset</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-top-ways-to-make-fast-motion-video-on-iphone-solved/"><u>New In 2024, Top Ways to Make Fast Motion Video on iPhone Solved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719275215540-reduce-clutter-increase-efficiency-one-antivirus-rule/"><u>Reduce Clutter, Increase Efficiency: One Antivirus Rule</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-handy-tutorial-to-combat-xfffeeee-in-windows/"><u>A Handy Tutorial to Combat XFFFEEEE in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guidetosettingupdarkinterfaceonwinnotepad/"><u>A GuideToSettingUpDarkInterfaceOnWinNotepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-access-boosting-morning-routine-and-note-openings/"><u>Accelerated Access: Boosting Morning Routine & Note Openings</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-synthetic-soundscape-pioneers-unveiling-the-top-ai-composers/"><u>Updated 2024 Approved Synthetic Soundscape Pioneers Unveiling the Top AI Composers</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-create-a-windows-11-bootable-usb-drive/"><u>3 Ways to Create a Windows 11 Bootable USB Drive</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-using-system-restore-in-windows-os/"><u>A Detailed Walkthrough of Using System Restore in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steams-offline-content-servers-problem-in-windows/"><u>Addressing Steam's Offline Content Servers Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-health-monitoring-set-up-full-charge-indicators-in-win11/"><u>Accelerating Battery Health Monitoring: Set Up Full Charge Indicators in Win11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-earn-with-each-screen-capture/"><u>[Updated] 2024 Approved  Earn With Each Screen Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-sevenfold-approach-to-fix-sync-errors-with-google-drive/"><u>A Sevenfold Approach to Fix Sync Errors with Google Drive</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-vivo-t2-5g-easily-by-drfone-android/"><u>How To Unlock a Vivo T2 5G Easily?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-how-to-record-audio-on-powerpoint-windows-and-mac/"><u>In 2024, How to Record Audio on PowerPoint? Windows and Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360119482-revolutionize-windows-experience-overcome-incompatibilities-now/"><u>Revolutionize Windows Experience: Overcome Incompatibilities Now</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleash-creativity-the-ultimate-selection-of-online-jpg-to-gif-tools/"><u>Unleash Creativity  The Ultimate Selection of Online JPG to GIF Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-disable-usb-selective-suspend-in-windows-11/"><u>3 Quick Ways to Disable USB Selective Suspend in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-beginners-path-to-mastering-mouse-controls-on-win11/"><u>A Beginner's Path to Mastering Mouse Controls on Win11</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-vivo-y100a-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Vivo Y100A Wont Charge | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-faulty-volume-adjustment-sliders/"><u>Addressing Faulty Volume Adjustment Sliders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-procedure-for-windows-photo-viewer-in-win11/"><u>Activation Procedure for Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370071964-resolve-wwin-plus-p-non-functionality-in-windows-systems/"><u>Resolve WWin + P Non-Functionality in Windows Systems.</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-overview-of-best-luts-for-vlog/"><u>New Overview of Best LUTs for Vlog</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-tips-for-keeping-your-iphones-memories-in-order-and-backed-up-on-icloud/"><u>2024 Approved  Top Tips for Keeping Your iPhone's Memories in Order and Backed Up on iCloud</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/how-to-make-slow-motion-videos-for-instagram/"><u>How to Make Slow Motion Videos for Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tips-to-tell-if-your-pc-needs-restarting/"><u>5 Tips to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-establish-java-development-kit-in-windows-11/"><u>A Complete Walkthrough to Establish Java Development Kit in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-widget-bar-features/"><u>Activating Windows 11 Widget Bar Features</u></a></li>
</ul></div>
