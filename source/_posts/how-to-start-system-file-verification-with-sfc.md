---
title: How to Start System File Verification with SFC
date: 2024-06-25T16:57:16.293Z
updated: 2024-06-26T16:57:16.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Start System File Verification with SFC
excerpt: This Article Describes How to Start System File Verification with SFC
keywords: Verify SFC Files,Perform SFC Check,Windows SFC Utility,Run SFC Command,SFC Error Resolution,System File Integrity,Repairing Windows Files
thumbnail: https://thmb.techidaily.com/6cd087da3f927fb5541ee18a5c4f27fd477ab52940ff719d4e3de086cc546e4e.jpg
---

## How to Start System File Verification with SFC

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

## How to Run a System File Checker Scan on Windows

 To use the SFC, you need to run a single command in Command Prompt. Here’s how:

1. Press**Win + S** to open Windows Search and type**command prompt** in the search box.
2. This will bring up**Command Prompt** in the search result. Click on the**Run as administrator** option.  
![Run Command Prompt Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-Command-Prompt-Using-Windows-Search.jpg)
3. Click**Yes** in the UAC prompt to allow Command Prompt to make changes to your computer.
4. In Command Prompt, enter the below command, and then hit the**Enter** key:  
`SFC /scannow`

 If you’re unfamiliar with operating system files, please read our guide on [what system files are on Windows](https://www.makeuseof.com/windows-system-files-guide/) . And to learn everything you need to know about Command Prompt, you can check out our [beginner's guide to Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .

## What Happens After I Run the System File Checker?

 After the System File Checker completes its scan, it will display a message in the Command Prompt window with the results.

 If your system files are okay, you’ll see a message that says "Windows Resource Protection did not find any integrity violations." If SFC found and fixed all problematic files, the message will read "Windows Resource Protection found corrupt files and successfully repaired them."

![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

## Other SFC Commands You Can Run on Windows

 The**SFC /scannow** isn’t the only System File Checker Command you can run. Here are a couple more and what they do:

| SFC Command | Description                                                                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /verifyonly | Run this command if you want SFC to check for problematic operating system files without fixing them.                                                                                                                                                                             |
| /scanfile   | Run this command if you want SFC to check a specific file for problems and fix it if it does have them. For example, Here’s the full command for checking and fixing the**user32.dll** file:**SFC /scanfile=c:\\windows\\system32\\user32.dll**                                   |
| /verifyfile | Run this command if you only want to check a particular system file for problems. Even if SFC finds an issue with the file, it will not repair it. For example, Here’s the full command for checking the**user32.dll** file:**SFC /verifyfile=c:\\windows\\system32\\user32.dll** |
| /offbootdir | Run this command to tell the SFC which directory contains a bootable version of Windows. You need to do this every time you use the tool outside of Windows. For example, to select the**E:** drive on your PC, enter**/offbootdir=e:\\**                                         |
| /offwindir  | Run this command to tell the SFC which folder in the directory — the one you specified with the**SFC /offbootdir** command — contains Windows. For example, enter**/offwindir=e:\\windows** to tell the System File Checker that Windows is on the**E:** drive.                   |

## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by [creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.

## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

## Running the System File Checker, Demystified

 We have only just begun to scratch the surface of what you can do with the System File Checker on Windows 10 and 11\. However, now that you know**how to run SFC** (both in and out of Windows), you can use the tool effectively to troubleshoot problems with operating system files.

 Using the SFC effectively is a necessary skill for every Windows user, and it’s just one of the many tools you can use to fix problems on your Windows computer.


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
<li><a href="https://win11-tips.techidaily.com/steps-to-enable-digital-supervision-in-windows-11-pcs/"><u>Steps to Enable Digital Supervision in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguarding-internal-builds-in-windows-11/"><u>Safeguarding Internal Builds in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/concealing-taskview-in-window-11-taskbar-design/"><u>Concealing TaskView in Window 11 Taskbar Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-restore-your-microsoft-store-registrations-win-11/"><u>Fix and Restore Your Microsoft Store Registrations (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-organize-your-notes-visually-with-obsidian-canvas/"><u>How to Organize Your Notes Visually With Obsidian Canvas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-escape-the-slow-gpsvc-cycle/"><u>Expert Tips to Escape the Slow GPSVC Cycle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-network-drive-management-with-ease-and-security-win11/"><u>Master Network Drive Management with Ease and Security (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-recognized-hdd-problems-in-a-step-by-step-windows-11-process/"><u>Fixing Non-Recognized HDD Problems in a Step-by-Step Windows 11 Process</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-through-the-eyes-of-one-a-critical-look-at-3dr/"><u>[Updated] Through the Eyes of One  A Critical Look at '3DR'</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-boost-focus-and-style-with-top-rated-frames-in-ig-photography/"><u>[Updated] Boost Focus & Style with Top-Rated Frames in IG Photography</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-voiceover-techniques-for-tiktok-video-amplification/"><u>[New] Voiceover Techniques for TikTok Video Amplification</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-oneplus-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on OnePlus</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-best-video-translator-app-for-pc-you-cannot-miss/"><u>New Best Video Translator App for PC You Cannot Miss</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/how-add-emojisstickers-to-videos-on-pcmacmobileonline-for-2024/"><u>How Add Emojis/Stickers to Videos on PC/Mac/Mobile/Online for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-melody-manual-grab-listen-and-scrutinize-songs/"><u>[New] In 2024, Melody Manual  Grab, Listen & Scrutinize Songs</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/identifying-creator-types-six-intriguing-youtube-categorization-tests/"><u>Identifying Creator Types  Six Intriguing YouTube Categorization Tests</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-samsung-galaxy-z-fold-5-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Samsung Galaxy Z Fold 5 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-auditory-delights-in-cinema-celebrating-the-best-8-film-soundscapes-for-2024/"><u>Updated Auditory Delights in Cinema - Celebrating the Best 8 Film Soundscapes for 2024</u></a></li>
</ul></div>
