---
title: Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide
date: 2024-07-12T17:14:32.988Z
updated: 2024-07-13T17:14:32.988Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide
excerpt: This Article Describes Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide
keywords: Fixing Error 0X80070003,Windows Error Resolution,WinError Code Repair,Overcoming Blue Screen,Step-by-Step System Fix,Troubleshoot WinError,ZeroX Error Guide
thumbnail: https://thmb.techidaily.com/5f066f9d9f5dd144763c4bbeccea3e56ce5ff6713b3a3e310bb03e72d6daf58f.jpg
---

## Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also [run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.


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
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-oneplus-11-5g-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your OnePlus 11 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-taskmanager-with-a-new-cli-tab-windows-11/"><u>How to Elevate TaskManager with a New CLI Tab (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-successful-java-setup-in-windows/"><u>Strategies for Successful Java Setup in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-silent-windows-headset-mic/"><u>Resuscitating Silent Windows Headset Mic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-windows-aggressive-contrast-mode/"><u>Silence Windows' Aggressive Contrast Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-dll-not-loading-error-in-windows-steam-client/"><u>Fixing Dll Not Loading Error in Windows Steam Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-reactivate-googles-nearby-share-app/"><u>Essential Tips to Reactivate Google's Nearby Share App</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-expertly-curated-list-premium-ubuscreen-recorder-apps/"><u>2024 Approved  Expertly Curated List  Premium UbuScreen Recorder Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-editing-tasks-with-powertoys-text-tools/"><u>Simplify Editing Tasks with PowerToys' Text Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/standardizing-your-windows-system-backups/"><u>Standardizing Your Windows System Backups</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-infinix-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Infinix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-tracking-with-windows-live-tiles/"><u>Mastering Device Tracking with Windows Live Tiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-identify-non-recognized-usb-devices-on-win-11/"><u>Steps to Identify Non-Recognized USB Devices on Win 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-top-5-methods-for-capturing-sound-in-windows-11/"><u>In 2024, Top 5 Methods for Capturing Sound in Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-preserve-audio-perfection-how-to-convert-video-to-mp3-without-quality-loss-for-2024/"><u>New Preserve Audio Perfection How to Convert Video to MP3 without Quality Loss for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-financial-finesse-top-business-strategy-titles-reviewed/"><u>[Updated] 2024 Approved  Financial Finesse  Top Business Strategy Titles Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-system-file-verification-with-sfc/"><u>How to Start System File Verification with SFC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-issue-error-code-0x80073712/"><u>Resolving Windows Update Issue: Error Code 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-customize-twitter-video-snapshot/"><u>2024 Approved  Customize Twitter Video Snapshot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategizing-user-focused-gpo-settings-for-windows-1111-oses/"><u>Strategizing User-Focused GPO Settings for Windows 11/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-error-0x80300024-in-winxp/"><u>Steps for Rectifying Error 0X80300024 in WinXP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-amd-installer-crash-in-windows/"><u>Quick Fixes for the AMD Installer Crash in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-for-clearing-false-device-error-on-pcs/"><u>Expert Guide for Clearing False Device Error on PCs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/expertly-edit-your-imagery-with-top-androidios-montage-apps/"><u>Expertly Edit Your Imagery with Top Android/iOS Montage Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locating-and-opening-system32-windows-11/"><u>Locating and Opening System32 (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-resolving-active-directory-printer-issues-on-win11/"><u>Tips & Tricks for Resolving Active Directory Printer Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-11-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-error-0x0000011b-on-operations/"><u>Tackling Windows 11'S Error 0X0000011B on Operations</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-seamless-slidecasts-combining-webcam-and-ppt/"><u>[Updated] 2024 Approved  Seamless Slidecasts  Combining Webcam and PPT</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/social-media-showdown-which-platform-dominates-likes-or-tiktok/"><u>Social Media Showdown  Which Platform Dominates, Likes or TikTok?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-accelerated-cinematography-best-5-diy-hacks-for-quick-learning/"><u>2024 Approved  Accelerated Cinematography  Best 5 DIY Hacks for Quick Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-vm-choices-to-upgrade-windows-11-performance/"><u>Superior VM Choices To Upgrade Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-hello-for-secure-user-access/"><u>Enabling Windows Hello for Secure User Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-game-launch-freezes-steps-to-mend-windows-11-steam/"><u>Troubleshooting Game Launch Freezes: Steps to Mend Windows 11 Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotlight-on-7-irksome-windows-11-aesthetics/"><u>Spotlight on 7 Irksome Windows 11 Aesthetics</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-blur-facesbackgroundimages-in-photoshop/"><u>In 2024, How to Blur Faces/Background/Images in Photoshop</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-sign-a-excel-2007-files-electronically-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How do i sign a Excel 2007 files electronically</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-msvcrt120dll-on-your-computer/"><u>Overcoming Missing Msvcrt120dll on Your Computer</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-14-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 14 Pro Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-the-path-to-pristine-playback-overcoming-audio-distortion-obstacles/"><u>New 2024 Approved The Path to Pristine Playback Overcoming Audio Distortion Obstacles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-manipulate-text-illumination-in-windows-11/"><u>Quickly Manipulate Text Illumination in Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-mastering-the-art-of-transferring-instagram-footage-to-pcmac/"><u>In 2024, Mastering the Art of Transferring Instagram Footage to PC/Mac</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-instagrams-trust-tales-decoding-the-power-of-selfies/"><u>In 2024, Instagram's Trust Tales  Decoding the Power of Selfies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-disable-virtual-machine-feature-in-windows-11/"><u>Instructions: Disable Virtual Machine Feature in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-audio-liberation-nine-simple-methods-for-mp4-sound-retrieval-future-edition/"><u>Updated 2024 Approved Audio Liberation Nine Simple Methods for MP4 Sound Retrieval, Future Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-with-leading-winning-apps-for-windows/"><u>Supercharge with Leading Winning Apps for Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-chromebook-screen-capture-simplified-into-four-methods/"><u>2024 Approved  Chromebook Screen Capture  Simplified Into Four Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-word-clarity-with-windows-11-help/"><u>Expedite Word Clarity with Windows 11 Help</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-clear-visuals-step-by-step-guide-for-picsart-backdrop-removal/"><u>[New] Clear Visuals  Step-By-Step Guide for Picsart Backdrop Removal</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-from-sd-to-hd-a-beginners-guide-to-pixel-size-and-video-quality/"><u>New 2024 Approved From SD to HD A Beginners Guide to Pixel Size and Video Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-gaming-e84-fix-for-steam-windows/"><u>Streamline Your Gaming: E84 Fix for Steam Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-fine-tune-your-igtv-videos-appeal-a-tale-of-titles-and-descriptions/"><u>[New] Fine-Tune Your IGTV Video's Appeal  A Tale of Titles & Descriptions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Tecno Spark 10 5G? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-balancing-act-managing-your-off-facebook-activity-displays/"><u>2024 Approved  The Balancing Act  Managing Your Off-Facebook Activity Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-another-program-uses-device-auditory-fault/"><u>Tackling 'Another Program Uses Device' Auditory Fault</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-nvidia-configurations-on-windows-os/"><u>How to Recover NVIDIA Configurations on Windows OS</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-vivo-y200-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Vivo Y200 by Name | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-sudo-tool-is-coming-to-windows-how-and-why-to-use-it/"><u>The Sudo Tool Is Coming to Windows: How and Why to Use It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimalist-workstations-with-windows-os/"><u>Minimalist Workstations with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-new-age-of-computing-from-w10s-familiarity-to-w11s-novelty/"><u>The New Age of Computing: From W10's Familiarity to W11's Novelty</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-xiaomi-13-ultra-by-drfone-android/"><u>Universal Unlock Pattern for Xiaomi 13 Ultra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-linux-with-windows-tools/"><u>Enhancing Linux with Windows Tools</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-edits-with-these-top-5-tools-no-youtube/"><u>Elevate Your Edits with These Top 5 Tools (No Youtube)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11s-revamped-widget-interface/"><u>Implementing Windows 11'S Revamped Widget Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-power-peaks-controlling-wlanext-usage/"><u>Taming Power Peaks: Controlling WLANEXT Usage</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-top-10-real-time-audio-amplifiers-for-windows-os/"><u>New Top 10 Real-Time Audio Amplifiers for Windows OS</u></a></li>
</ul></div>
