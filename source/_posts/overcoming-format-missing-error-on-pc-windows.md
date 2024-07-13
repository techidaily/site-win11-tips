---
title: Overcoming 'Format Missing' Error on PC Windows
date: 2024-07-12T16:43:00.429Z
updated: 2024-07-13T16:43:00.429Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming 'Format Missing' Error on PC Windows
excerpt: This Article Describes Overcoming 'Format Missing' Error on PC Windows
keywords: Fix Format Error (Windows),Resolve WinError,Stop Format Mismatch,Clear File Formatting Issues,Eliminate 'No Format' Error,Windows File Fixation,Eradicate PC Format Failure
thumbnail: https://thmb.techidaily.com/31fd63ab910fdd0bfef9c588934b4c990590f2025d46dff0a5963e90a62a92d8.jpg
---

## Overcoming 'Format Missing' Error on PC Windows

 We use external flash drives and hard disks on a regular basis for file transfer and sharing. While cloud sharing is gaining popularity, physical disk sharing is still best suited for large or personal files. You can connect multiple USB devices on your system at the same time and move data from one drive to others.

 But some users encounter the "You Need To Format The Disk In Drive before you can use it" error. It forces you to format the disk before you can use it. However, it isn’t a sensible option if you have important files on the disk. We will list multiple methods using which you can reassess your disk drive. Let’s begin.

## What Are the Reasons Behind the Error Message?

 You can see the “Format Disk in drive” message due to one or more of the following reasons:

1. The USB drive or the port is malfunctioning.
2. The device drivers of the disk are corrupt or outdated.
3. Malware is preventing access to the disk.
4. Core system files have gone missing or corrupt.
5. A third-party app is conflicting with system apps and services.

## Methods to Fix the “You Need to Format the Disk in Drive Before You Can Use It” Error

 Try out the following methods to fix the disk error message and save your data stored on it:

###

### 1\. Check the USB Drive

 If connecting the USB drive to any USB port on your system produces the same error, then unplug it. Connect it to another computer and check if it shows up in Device Manager and you can access the file contents without any issues. If it works, create a copy of all your data on that system for backup purposes.

### 2\. Perform a Complete Shutdown

[Microsoft enables Fast Start-up](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) in newer versions of the Windows operating system by default. It hibernates the system and kernel-level processes so your system boots up faster after a shutdown.

 But if the core system services encounter a glitch and stop working properly, you will see the error message every time. So, performing a complete shutdown can help in restarting all core services.

Repeat the following steps:

1. Press**Win + R** to launch the Run command box.
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to open Command Prompt with administrator privileges.
3. Input the following command and press the enter key:**shutdown /s /f /t 0**  
![Perform a Complete Shutdown](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/perform-a-complete-shutdown.jpg)
4. It will take longer than usual for your system to shut down. Power it on again and open File Explorer.
5. Click on the USB disk and check if you are able to access the files on it.

### 3\. Do a Clean Boot

 Third-party applications and services can interfere with system apps and impede their normal functioning. So,[perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) of your system. It will disable all the third-party services and programs from running at startup. If you are able to access the disk now, repeat the clean boot process while enabling third-party services one by one to isolate the culprit program.

### 4\. Change the USB Drive Letter Using Disk Management

 Changing the drive letter could help in resolving the USB drive error on your system and make it accessible. Repeat the following steps to change the drive letter:

1. Press**Win + R** to open the Run dialog box. Type**diskmgmt.msc** and press the enter key.
2. In the Disk Management window, find your USB disk drive and right-click on it.
3. Select the**Change Drive Letter and Paths** option from the context menu.
4. Click on the**Change** button. Then, click on the**arrow** button to expand the drop-down list and select a drive letter from it.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Lastly, click on the**OK** button. Reconfirm your decision and click on the**Yes** button to change the Drive letter.
6. You will see a system notification informing you about the Drive letter change and mounting the drive.
7. Press**Win + E** to open the File Explorer and check whether the USB drive is accessible or not.

### 5\. Scan the Hard Disk Using CHKDSK

 It is possible for the USB disk to contain bad files and sectors; due to which Windows asks you to format it before usage. But you can leverage the inbuilt CHKDSK utility to scan the USB disk for errors and fix them for you. It will scan all the files on the disk and repair the drive. You can either use the [command prompt method or Run CheckDisk](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) using the Properties window in File Explorer.

### 6\. Run an SFC and DISM Scan

 If the check disk doesn’t do any good, and you still have the error, it is possible that your system files are missing or corrupt.[Start with an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to check and replace any corrupt system files. Follow that up with a [DISM scan to fix the Windows installation image](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . Make sure you have an active internet connection to run the DISM scan without any issues.

### 7\. Use a Linux Installation Media to Access the USB Disk Drive

 This method is more of a workaround to not lose your data. If you don’t have a second system nearby, you can [create a Linux installation media](https://www.makeuseof.com/tag/install-ubuntu-computer-using-usb-flash-drive/) and use the Try Ubuntu mode to mount and access the contents of the USB disk. It will save the effort of searching for another computer, and you can successfully create a backup of the USB disk.

 To access the USB disk using Linux installation media repeat the following steps:

1. Plug the Linux installation media into your system.
2. Press the**Esc** key and power on your system to enter the boot devices menu. Select the Linux installation media and boot it up.
3. In the Grub menu, select the**Try or install Ubuntu** option. Wait for the setup Window to launch and then click on the**Try Ubuntu** option.
4. Go to the left-hand side menu and click on the**Files** app.  
![Use a Linux Installation Media to Access the USB Disk Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/use-a-linux-installation-media-to-access-the-usb-disk-drive.jpg)
5. Click on the USB disk name in the navigation pane to open it. Now, you can copy these files to another location on your hard drive or an external hard disk.
6. After you finish copying the contents of the USB disk, click on the power icon and choose the Power off option to close the Try Ubuntu mode.

### 8\. Try Generic Fixes for Drive Formatting Issues

 If none of those worked, it's time to apply more general fixes before diving into more drastic measures. There are a few different error messages related to storage drive formatting issues that Windows can throw, and all of them share some common fixes.

 As such, check out [how to fix format disk errors on Windows without formatting your drive](<http://How> to Fix Format Disk Errors Without Formatting Your Hard Drive on Windows) for more tips.

### 9\. Reset Windows

 If nothing seems to work, and you see the error with every USB disk you try to connect to the system, consider a complete Windows reset. It will remove all your system files and installed apps (though you can choose to keep personal files on the system drive).

 However, before [performing a System Reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try [System Restore](https://www.makeuseof.com/windows-reset-system-restore-difference/) using any available System Restore points. If that fails, and a reset doesn't seem to work, you can [factory reset your Windows computer](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) .

## Access USB Disk Contents Without Formatting

 It is a bad idea to click on the Format button when File Explorer prompts you to do it to access the USB disk. Firstly, try to check the hardware malfunctions and salvage the data on the USB disk. You can use another system or create a Linux installation media to access files on the USB disk.

 If SFC and DISM fail to repair the system, and you still see the error with every USB disk you connect to your system, reset your Windows computer.

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
<li><a href="https://win11-tips.techidaily.com/interacting-with-network-drives-from-smartphones/"><u>Interacting with Network Drives From Smartphones</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-seamlessly-connect-with-friends-and-family-via-skype-call/"><u>[Updated] In 2024, Seamlessly Connect with Friends & Family via Skype Call</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-0x0000004e-in-windows-a-quick-guide/"><u>Fixing Error 0X0000004E in Windows: A Quick Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-downloading-your-youtube-watch-lists-step-by-step/"><u>[Updated] In 2024, Downloading Your YouTube Watch Lists  Step by Step</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-speed-up-epic-games-launcher-downloads-on-windows/"><u>How to Speed Up Epic Games Launcher Downloads on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unlocking-the-secrets-of-instagrams-video-capsule/"><u>[Updated] Unlocking the Secrets of Instagram's Video Capsule</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-the-must-have-msistore-tools/"><u>Unlock Potential: The Must-Have MSIStore Tools</u></a></li>
<li><a href="https://some-approaches.techidaily.com/techniques-for-transferring-media-between-two-iphones-for-2024/"><u>Techniques for Transferring Media Between Two iPhones for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-cut-edit-repeat-top-10-free-video-editors-for-ubuntu/"><u>Updated In 2024, Cut, Edit, Repeat Top 10 Free Video Editors for Ubuntu</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-the-art-of-shopping-spree-videography/"><u>[Updated] Mastering the Art of Shopping Spree Videography</u></a></li>
<li><a href="https://vp-tips.techidaily.com/zerobackground-pro-precision-erasing-for-photos-for-2024/"><u>ZeroBackground Pro  Precision Erasing for Photos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-path-to-w11-audio-recording/"><u>Beginner's Path to W11 Audio Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-windows-notifications-for-essential-only/"><u>Adjust Windows Notifications for Essential Only</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-comprehensible-guide-to-selecting-popular-youtube-openings/"><u>[Updated] The Comprehensible Guide to Selecting Popular YouTube Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-file-extractions-with-win11-sefx-magic/"><u>Elevating File Extractions with Win11 SEFx Magic</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-getting-started-with-discord-stickers-mastery/"><u>2024 Approved  Getting Started with Discord Stickers Mastery</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-things-you-should-know-when-unlocking-total-wireless-of-iphone-14-pro-by-drfone-ios/"><u>In 2024, Things You Should Know When Unlocking Total Wireless Of iPhone 14 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-bygone-era-to-future-tech-using-windows-7-key-in-11-setup/"><u>From Bygone Era to Future Tech: Using Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-a-step-by-step-guide-to-leveraging-the-whiteboard-feature-in-remote-tech-sessions-for-2024/"><u>[New] A Step-by-Step Guide to Leveraging the Whiteboard Feature in Remote Tech Sessions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-eliminate-path-error-in-windows/"><u>Guide to Eliminate PATH Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-non-successful-updates-in-windows-discord/"><u>Dealing with Non-Successful Updates in Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-update-faults-windows-xp-x8019/"><u>Eradicating Update Faults: Windows XP, X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-put-a-windows-computer-to-sleep/"><u>9 Ways to Put a Windows Computer to Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-windows-users-to-fix-f429f-camera-app-hurdle/"><u>Guiding Windows Users to Fix F429F Camera App Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-your-path-upgrading-outdated-windows-driver-tech/"><u>Clear Your Path: Upgrading Outdated Windows Driver Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-call-failed-error-on-win1011/"><u>Guidelines for Overcoming 'Call Failed' Error on Win10/11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-free-to-learn-4-youtube-channels-unlocking-the-secrets-of-background-substitution/"><u>[Updated] Free-to-Learn  4 YouTube Channels Unlocking the Secrets of Background Substitution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-automatic-restarts-on-windows-11-devices/"><u>Conquering Automatic Restarts on WIndows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-find-feature-in-windows-11-taskbar-activation-guide/"><u>Instant Find Feature in Windows 11 Taskbar – Activation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-printmanagementmsc-not-found-error-on-windows/"><u>How to Fix the Printmanagement.msc Not Found Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-mysteries-inside-its-registry-files/"><u>Unraveling Windows 11'S Mysteries: Inside Its Registry Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restarting-windows-updates/"><u>Mastering the Art of Restarting Windows Updates</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/s-leading-video-editors-for-music-and-sound-effects-for-2024/"><u>S Leading Video Editors for Music and Sound Effects for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digitally-delving-opening-game-directories-on-windows/"><u>Digitally Delving: Opening Game Directories on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-via-cli-registry-edition/"><u>Advanced Windows Customization via CLI: Registry Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-mouse-game-with-cross-border-powertoys-techniques/"><u>Elevate Your Mouse Game with Cross-Border PowerToys Techniques</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-leading-gamers-in-tiktok-world/"><u>[New] In 2024, Leading Gamers in TikTok World</u></a></li>
<li><a href="https://youtube-help.techidaily.com/maximizing-impact-with-creative-video-titles-for-2024/"><u>Maximizing Impact with Creative Video Titles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-windows-subsystem-enhance-linux-presence/"><u>Does Windows Subsystem Enhance Linux Presence?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-overcoming-windows-run-time-errors/"><u>Unraveling the Mystery: Overcoming Windows 'Run-Time Errors'</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-vivo-s18-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Vivo S18 Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-craft-of-simultaneous-unzipping-with-windows-tools/"><u>Master the Craft of Simultaneous Unzipping with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-daily-productivity-the-top-6-apps-for-windows-11-users/"><u>Mastering Daily Productivity: The Top 6 Apps For Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-lockout-try-these-hacks/"><u>Microsoft Store Lockout? Try These Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-switch-nat-settings-in-windows-oses/"><u>How to Effortlessly Switch NAT Settings in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-failures-from-windows-memory-tool/"><u>How To Rectify Failures From Windows Memory Tool</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-earn-while-playing-games-online-for-2024/"><u>[Updated] Earn While Playing Games Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evaluating-the-need-for-maintaining-pagefilesys-filespace/"><u>Evaluating the Need for Maintaining Pagefile.sys Filespace</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-precisionsync-analyst-perspectives/"><u>[New] PrecisionSync Analyst Perspectives</u></a></li>
</ul></div>
