---
title: Resolving Prioritize Disk Format in Windows Errors
date: 2024-07-12T17:39:17.810Z
updated: 2024-07-13T17:39:17.810Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Prioritize Disk Format in Windows Errors
excerpt: This Article Describes Resolving Prioritize Disk Format in Windows Errors
keywords: Fixing Disk Error Windows,Resolve File Format WinErr,Fixing Windows Filesystem Issue,Address Disk Errors Windows,Correcting Disk Format WinError,Tackle Windows Format Fault,Solving WinDisk Error Problem
thumbnail: https://thmb.techidaily.com/c80fad792e3cb229a3e653969139437b39335328a63ecf71a877586d96fe497a.jpg
---

## Resolving Prioritize Disk Format in Windows Errors

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-store-complete-online-interface/"><u>[New] Store Complete Online Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-storyteller-a-step-by-step-guide/"><u>Launching Windows 11'S Storyteller: A Step-by-Step Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Oppo Find X7? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-build-custom-text-transcription-software-on-windows-with-whisper/"><u>How to Build Custom Text Transcription Software on Windows with Whisper</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gopro-vs-sony-battle-royale-for-ultimate-action-cameras-for-2024/"><u>GoPro Vs. Sony  Battle Royale for Ultimate Action Cameras for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-closed-folder-issues-in-winxpxo11-on-double-click/"><u>How to Tackle Closed Folder Issues in WinXP/XO11 on Double-Click</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-visual-voyage-amds-radeon-reborn-for-2024/"><u>[New] Visual Voyage  AMD's Radeon Reborn for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-windows-file-not-found-error/"><u>Methods to Overcome Windows 'File Not Found' Error</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-crafting-compelling-short-videos-for-youtube-a-top-10-list/"><u>[New] Crafting Compelling Short Videos for YouTube - A Top 10 List</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-splice-video-editing-app-an-exhaustive-review-of-its-tools-and-functionality/"><u>New In 2024, Splice Video Editing App An Exhaustive Review of Its Tools and Functionality</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-challenge-accepted-top-10-tiktok-trends-you-should-try/"><u>2024 Approved  Challenge Accepted  Top 10 TikTok Trends You Should Try</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-rhythmcutter-studio-high-end-audio-in-every-frame/"><u>2024 Approved  RhythmCutter Studio  High-End Audio in Every Frame</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-techniques-to-accelerate-steam-downloads-on-windows/"><u>Master Techniques to Accelerate Steam Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-lsassexe-unable-to-locate-error-simple-steps/"><u>Fixing 'lsass.exe' Unable to Locate Error - Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-deletion-in-windows-11-115-chars/"><u>Mastering Software Deletion in Windows 11 (115 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-windows-applications-without-admin-rights/"><u>How to Manage Windows Applications Without Admin Rights</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-stabilize-iphone-videos-3-ways/"><u>In 2024, How to Stabilize iPhone Videos? [3-Ways]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-windows-11-shutdown-time-for-tasks-in-progress/"><u>Modifying Windows 11 Shutdown Time for Tasks in Progress</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-next-gen-entertainment-experience-scrutiny/"><u>2024 Approved  Next-Gen Entertainment Experience Scrutiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insiders-look-at-windows-boot-configuration-management/"><u>Insider's Look at Windows Boot Configuration Management</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-infinix-hot-30i-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Infinix Hot 30i PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-microsofts-phone-link-application-functionality/"><u>Decoding Microsoft's Phone Link Application Functionality</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-delete-all-photos-from-iphone-11-beyond-scope-of-recovery-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Delete All Photos from iPhone 11 Beyond Scope of Recovery? | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-auto-time-zone-switches-in-microsofts-operating-system/"><u>Bypassing Auto Time Zone Switches in Microsoft's Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-keyboard-commands-to-sharpen-your-3d-skills/"><u>Essential Keyboard Commands to Sharpen Your 3D Skills</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-masters-tutorial-total-deep-dive-into-xmedia-suite-workshop/"><u>[New] Master's Tutorial  Total Deep Dive Into XMedia Suite Workshop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-disconnects-and-fixes-javascript-issues-in-discord-win-11/"><u>Mastering Disconnects & Fixes: JavaScript Issues in Discord Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-wls-techniques-unlocking-the-full-power-of-wsl-2-in-win-oses/"><u>Pro WLS Techniques: Unlocking the Full Power of WSL 2 in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-become-a-social-butterfly-engage-in-fb-live-on-your-roku-box-for-2024/"><u>[New] Become a Social Butterfly  Engage in FB Live on Your Roku Box for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-java-development-kit-setup-in-windows-11/"><u>Essential Steps to Java Development Kit Setup in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mend-window-11-glitchy-screens/"><u>Mend: Window 11 Glitchy Screens</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Realme Narzo 60 5G? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/factory-reset-on-iphone-6s-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ideal-start-kit-top-gopro-supplementary-gear-for-2024/"><u>Ideal Start Kit  Top GoPro Supplementary Gear for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hilarious-guide-crafting-memes-with-ease/"><u>2024 Approved  Hilarious Guide  Crafting Memes with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fn-key-techniques-for-efficient-windows-use/"><u>Fn Key Techniques for Efficient Windows Use</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-quotable-content-essential-lyrics-for-virality-on-tiktok/"><u>[New] Quotable Content  Essential Lyrics for Virality on TikTok</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-elevate-your-filmmaking-skills-for-ig-reels-for-2024/"><u>[Updated] Elevate Your Filmmaking Skills for IG Reels for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-windows-background-save-spot-in-11/"><u>How to Find Window's Background Save Spot in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-fixes-for-non-responsive-backlight-on-windows-pcs/"><u>Five Fixes for Non-Responsive Backlight on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-clicking-away-how-to-instantly-load-apk-files-on-windows-11/"><u>Double-Clicking Away: How to Instantly Load APK Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-camera-saving-errors/"><u>Guiding Through Windows Camera Saving Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-cleaning-for-a-functional-windows-11-space/"><u>Effortless Cleaning for a Functional Windows 11 Space</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-apple-iphone-12-pro-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On Apple iPhone 12 Pro</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-smoother-rides-with-htc-vive-anti-nausea-tips/"><u>[New] Smoother Rides with HTC Vive  Anti-Nausea Tips</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-your-blueprint-for-broadcasting-live-on-facebook/"><u>2024 Approved  Your Blueprint for Broadcasting Live on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-directories-a-breeze-with-win11-essentials/"><u>Making Directories a Breeze with Win11 Essentials</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-from-instant-sharing-to-long-term-storage-snapshots-journey/"><u>[New] 2024 Approved  From Instant Sharing to Long-Term Storage  Snapshots' Journey</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-optimal-viewing-angles-for-fb-videos/"><u>[New] In 2024, Optimal Viewing Angles for FB Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-obstacles-for-secure-memory-settings-in-new-windows-11/"><u>Clearing Obstacles for Secure Memory Settings in New Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-quick-video-recorder-download-and-record-video/"><u>[Updated] Quick Video Recorder Download and Record Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-admin-restrictions-on-windows-safety-settings/"><u>Bypassing Admin Restrictions on Windows Safety Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-security-faults-and-fixes/"><u>Navigating Through Windows Security Faults & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-resolution-of-windows-error-1132-in-zoom/"><u>Master the Resolution of Window's Error 1132 in Zoom</u></a></li>
</ul></div>
