---
title: "DISM Strategies: Reviving Windows 11 Images"
date: 2024-07-12T17:04:27.481Z
updated: 2024-07-13T17:04:27.481Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes DISM Strategies: Reviving Windows 11 Images"
excerpt: "This Article Describes DISM Strategies: Reviving Windows 11 Images"
keywords: Win11 Image Update,Revive Win11 Screens,Dism Techniques for Win11,Optimize Win11 Display,Windows Recovery via Dism,Enhance Win11 Images,Resurrect Win11 Graphics
thumbnail: https://thmb.techidaily.com/de59f9b5780463def4cb9ce5b3382a49671007046477b96e6adff7ee7d6b4151.jpg
---

## DISM Strategies: Reviving Windows 11 Images

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command
![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

## Run the DISM RestoreHealth Command to Repair the Windows System Image
![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility
![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-top-7-audio-de-singer-tools-for-effective-vocal-elimination/"><u>New 2024 Approved Top 7 Audio De-Singer Tools for Effective Vocal Elimination</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-master-flv-video-editing-on-windows-8-tips-and-tricks/"><u>New Master FLV Video Editing on Windows 8 Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-disabled-windows-application/"><u>How to Enable Disabled Windows Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedy-steps-for-immediate-failure-in-adding-your-folder-to-onedrive/"><u>Swift Remedy Steps for Immediate Failure in Adding Your Folder to OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0x80070522-unlocking-client-privileges-in-windows-1110/"><u>Troubleshooting Error 0X80070522: Unlocking Client Privileges in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-schedule-breakdown-quickly/"><u>Troubleshoot Windows Schedule Breakdown Quickly</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveiling-storytelling-through-scenery/"><u>2024 Approved  Unveiling Storytelling Through Scenery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-home-page-from-the-settings-app-in-windows-11/"><u>How to Remove the Home Page From the Settings App in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vanishing-folder-icons-in-explore/"><u>Overcoming Vanishing Folder Icons in Explore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-recovery-on-windows-11-pro/"><u>Streamlining Data Recovery on Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantaneous-transcription-experience-with-whisper-desktop/"><u>Instantaneous Transcription Experience with Whisper Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unauthorized-save-errors-in-microsoft-os/"><u>Troubleshooting Unauthorized Save Errors in Microsoft OS</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-leading-smartphototech-ai-edition-advantages/"><u>2024 Approved  Leading SmartPhotoTech  AI Edition Advantages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-prime-video-text-barriers-on-windows-11/"><u>Overcoming Prime Video Text Barriers on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-honor-magic5-ultimate-screen-sharing-drfone-by-drfone-android/"><u>How To Do Honor Magic5 Ultimate Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-cannot-add-columns-error-in-ms-excel-for-windows-users/"><u>Tackling the 'Cannot Add Columns' Error in MS Excel for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/premier-window-warriors-championing-stronger-passwords-today/"><u>Premier Window Warriors: Championing Stronger Passwords Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-networking-essential-pre-call-tests-for-webcamsmics/"><u>Navigating Networking: Essential Pre-Call Tests for Webcams/Mics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-predominant-anydesk-issues-in-os/"><u>Strategies to Correct Predominant AnyDesk Issues in OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-extract-focus-from-logitech-cam-feed/"><u>2024 Approved  Extract Focus From Logitech Cam Feed</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-25-essential-hashtags-for-increased-instagram-engagement/"><u>2024 Approved  25 Essential Hashtags for Increased Instagram Engagement</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-kickstart-your-video-enhancement-game-with-snapchat/"><u>[Updated] Kickstart Your Video Enhancement Game with Snapchat</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-depth-analysis-the-dynamics-of-v-tubers/"><u>In-Depth Analysis  The Dynamics of V-Tubers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/obs-revived-camera-back-to-life/"><u>OBS Revived  Camera Back to Life</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-inside-the-score-understanding-aspect-ratios-for-video-success/"><u>2024 Approved  Inside The Score  Understanding ASPECT RATIOS for Video Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-snip-and-sketch-shortcut/"><u>Launching Windows 11'S Snip & Sketch Shortcut</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-list-top-7-methods-to-grow-storage-without-paying/"><u>The Essential List: Top 7 Methods to Grow Storage Without Paying</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-channel-acquisition-101-maximizing-youtubers-earnings/"><u>2024 Approved  Channel Acquisition 101  Maximizing Youtubers' Earnings</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-snapchat-downloads-for-mac-easy-steps-included/"><u>[Updated] In 2024, Snapchat Downloads for Mac - Easy Steps Included</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-mastering-volume-transitions-keyframe-techniques-in-filmora-mac/"><u>Updated 2024 Approved Mastering Volume Transitions Keyframe Techniques in Filmora (Mac)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-connection-in-windows-ethernet/"><u>Overcoming No Connection in Windows Ethernet</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-mastering-media-marketing-essential-ig-video-editors-for-2024/"><u>[Updated] Mastering Media Marketing  Essential IG Video Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/paperless-pages-winning-window-based-notepad-substitutes/"><u>Paperless Pages: Winning Window-Based Notepad Substitutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-experience-mastering-windows-11s-search-tool/"><u>Jumpstart Your PC Experience: Mastering Windows 11’S Search Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storage-soaring-speeds-stalling-mp60-model/"><u>Storage Soaring, Speeds Stalling - MP60 Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-windows-environment-top-6-innovative-android-apps/"><u>Transform Your Windows Environment: Top 6 Innovative Android Apps</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-dynamic-movement-analysis-a-complete-examination/"><u>[New] 2024 Approved  Dynamic Movement Analysis  A Complete Examination</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-spark-interest-with-style-mixing-tiktoks-genius-techniques-for-insta-for-2024/"><u>[Updated] Spark Interest with Style  Mixing TikTok's Genius Techniques for Insta for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-share-issue-on-geforce-experience-windows-1011/"><u>Solving Share Issue on GeForce Experience (Windows 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screens-in-win11-with-ease/"><u>Overcoming Black Screens in Win11 with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-guide-initiating-screen-capture-on-win-11/"><u>Quick Start Guide: Initiating Screen Capture on Win 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/streamline-screen-recording-with-these-windows-tools-for-2024/"><u>Streamline Screen Recording with These Windows Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/operas-plight-unleash-it-from-windows-freeze/"><u>Opera's Plight? Unleash It From Windows Freeze!</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-s23-ultra-can-t-play-avchd-mts-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Samsung Galaxy S23 Ultra can’t play AVCHD .mts video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-value-with-smart-acquisition-of-windows-10-product-keys/"><u>Maximizing Value with Smart Acquisition of Windows 10 Product Keys</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-do-you-unlock-your-apple-iphone-x-learn-all-4-methods-by-drfone-ios/"><u>In 2024, How Do You Unlock your Apple iPhone X? Learn All 4 Methods</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/rapid-rendering-powerpoint-recordings/"><u>Rapid Rendering  PowerPoint Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-utorrent-peer-relationships-on-win/"><u>Reestablishing uTorrent Peer Relationships on Win</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-stream-anything-to-chromecast-the-ultimate-video-format-guide/"><u>Updated Stream Anything to Chromecast The Ultimate Video Format Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-commands-to-access-pc-health-stats/"><u>Step-by-Step Commands to Access PC Health Stats</u></a></li>
</ul></div>
