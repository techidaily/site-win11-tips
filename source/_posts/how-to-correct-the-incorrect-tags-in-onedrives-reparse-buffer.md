---
title: How to Correct the Incorrect Tags in OneDrive’s Reparse Buffer
date: 2024-11-15T20:01:01.458Z
updated: 2024-11-17T19:43:17.938Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct the Incorrect Tags in OneDrive’s Reparse Buffer
excerpt: This Article Describes How to Correct the Incorrect Tags in OneDrive’s Reparse Buffer
keywords: OneDrive Tag Correction Guide,Reparse Buffer Error Fixing,Onedrive Sync Issue Resolution,Correcting Tags in Cloud Storage,Microsoft OneDrive Optimization,Tagging Adjustments for Drive,OneDrive Data Synchronization
thumbnail: https://thmb.techidaily.com/f5d1594082aca6452dbc25a49388a37fc7e84721f123ecd76572cb92530c4365.jpg
---

## How to Correct the Incorrect Tags in OneDrive’s Reparse Buffer

 Have you encountered the "the tag present in the reparse point buffer is invalid" error when altering a folder or deleting it on your Windows device? You may have encountered this error when accessing a folder via Command Prompt or File Explorer, mainly for files and folders synced to OneDrive. How does this error occur? OneDrive is the source of the error.

 In this article, we'll explain the causes of this error and provide you with possible solutions to resolve it.

## What Causes "The Tag Present in the Reparse Point Buffer Is Invalid" on Windows?

 As mentioned earlier, the error is caused by a problem with OneDrive sync. It could be that the folder you're trying to access is corrupt, or that there is an issue with other system files preventing OneDrive from syncing successfully.

 There are several ways in which the "the tag present in the reparse point buffer is invalid" error can appear. Here are the two most common ones:

* Error 0x80071129: The tag present in the reparse point buffer is invalid
* Location not found: The tag present in the reparse point buffer is invalid

 "Error 0x80071129" or "Location not found" appears as the title of the error window, while the main part of the error appears in the error window. Any variation of this error has nearly the same causes, regardless of its nature. In light of that, similar fixes are effective in resolving the issue. Let's see how you can fix it.

## But First, Some Preliminary Checks

 Apply the following preliminary checks before attempting the major fixes:

* Pause the OneDrive sync and try opening the folder again.
* Restart your device once.
* Log out of your OneDrive account.
* If you have made any changes to the problematic folder on OneDrive, go back and revert them for a while.

 If the above preliminary checks do not solve the problem and the issue persists, start implementing the remaining fixes.

## 1\. Run a CHKDSK Scan

 For Windows users, CHKDSK is a go-to utility for scanning and fixing hard drive problems. Whenever users encounter a hard drive error or an issue with the data stored on their drive, the CHKDSK scan proves to be a godsend.

 This scan may be helpful to fix the issue under discussion since "the tag present in the reparse point buffer is invalid" is also associated with an inability to access a particular file correctly. Therefore, follow the steps below to run the CHKDSK scan before you attempt any other repair or fix:

1. In the Windows Search box, type**"Command Prompt** .**"**
2. Right-click the**Command Prompt** app and click**Run as administrator** .
3. Enter the following command in the Command Prompt app:  
`Chkdsk C: /f /r`
4. Then press**Enter** .  
![Running Check Disk Scan in Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/running-check-disk-scan-in-windows-command-prompt.jpg)

 Here,**C:** refers to the drive where your operating system is installed. If your operating system resides on a different drive, change the command accordingly. Also, don't forget to enter the**"/f"** and**"/r"** parameters since these are needed to fix errors, locate bad sectors, and recover corrupted information.

 The CHKDSK scan has the greatest chance of adequately fixing the error under discussion. However, if it doesn't resolve the problem, you can move on to the next solution.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run the DISM and SFC Scan

 Like CHKDSK, SFC and DISM scans can be used when your system behaves strangely. Initially, you should run the SFC scan because it usually resolves the issue. However, if it fails to diagnose the problem or run, you should run a DISM scan.

 Performing both scans ensures that your device does not have corrupted system files causing the trouble. To run both scans, follow these steps:

1. Open Command Prompt as an administrator.
2. To run the SFC scan, type the following command and press**Enter** :  
`SFC /scannow`
3. To run the DISM scan, type the following command and press**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 To better understand the results of these scans, see our[article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove the Passwords From the Problematic Files

 Has this error occurred after password-protecting a synced file on OneDrive? In this case, you should go to OneDrive, check the history of modified files, and restore the problematic file to a previous version. Our article on[recovering OneDrive files from version history](https://www.makeuseof.com/tag/restore-onedrive-files-version-history/#rolling-back-a-file) explains how to roll back a file. Reset OneDrive if this fix does not solve the problem.

## 5\. Reset OneDrive

 Resetting the app or service is a good troubleshooting step for problems that don't resolve with general fixes. Therefore, if none of the fixes have worked so far, you should reset OneDrive. Remember that resetting OneDrive will not delete your data, but you'll have to set up the sync connection again.

 In our article on[how to fix OneDrive when you can't open the files](https://www.makeuseof.com/ways-fix-onedrive-when-you-cannot-open-your-files/#reset-onedrive) , we have explained how to reset OneDrive. Follow the instructions in the article to reset OneDrive, and hopefully, you will be able to fix the issue. However, if that also fails to work and the error appears periodically, you can delete or relocate the problematic file or folder.

## 6\. Delete or Relocate the Problematic File

 If all else fails, delete or relocate the problematic file. However, before you do that, you need to pause the OneDrive sync and leave it for an hour. Then, access your OneDrive online and remove the synced file from there.

 Once done, you should turn off your device's internet connection and[start Windows 11 in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) (or[Windows 10](https://www.makeuseof.com/tag/boot-windows-10-safe-mode/) if you're using an older version). Afterward, navigate to your local drive, where the problematic file is located. Delete it from there and restart your device normally.

 If the file you are experiencing the error with has value to you and you cannot delete it, move it to another computer and delete it from your primary device. Hopefully, relocating or deleting the file will prevent the error from occurring again.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148649/16836" target="_top" id="2148649">
  <img src="//a.impactradius-go.com/display-ad/16836-2148649" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148649/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Keep Annoying OneDrive Errors at Bay

 It can be very frustrating to encounter the "The tag present in the reparse point buffer is invalid" error when making changes to our files. If you apply the fixes in the article, hopefully, you'll be able to fix the error and reaccess your files. If nothing works, you can move it elsewhere and delete it from your primary drive.

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
<li><a href="https://facebook-video-share.techidaily.com/new-essential-knowledge-for-youtube-short-creators-for-2024/"><u>[New] Essential Knowledge for YouTube Short Creators for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-selecting-superior-hdr-cameras-a-buyers-guide/"><u>[New] Selecting Superior HDR Cameras A Buyer's Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-unveiling-the-most-shared-stock-photos-and-backstories-for-2024/"><u>[Updated] Unveiling the Most Shared Stock Photos & Backstories for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-slippery-slope-of-simulated-support-instagram-style/"><u>2024 Approved The Slippery Slope of Simulated Support, Instagram Style</u></a></li>
<li><a href="https://fox-direct.techidaily.com/building-a-custom-google-cardboard-for-immersive-experience/"><u>Building a Custom Google Cardboard for Immersive Experience</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/chatbot-conundrum-gpt-plus-or-the-puzzle-of-perplexity/"><u>ChatBot Conundrum: GPT Plus or the Puzzle of Perplexity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dispatcher-for-mmc-preventing-cannot-create-errors/"><u>Dispatcher for MMC: Preventing 'Cannot Create' Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-frustrating-camera-errors-code-0xa00f4289/"><u>Eliminating Frustrating Camera Errors: Code 0xA00F4289</u></a></li>
<li><a href="https://extra-tips.techidaily.com/exclusive-access-to-pinnacle-android-viewer/"><u>Exclusive Access to Pinnacle Android Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-0x800704cf-glitch-windows-11/"><u>Fixing Microsoft Store 0X800704CF Glitch Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-mastering-video-capturing-step-by-step-manual/"><u>In 2024, Mastering Video Capturing Step-by-Step Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-legacy-keys-an-insiders-look-at-narrator-shortcuts/"><u>Leveraging Legacy Keys: An Insider's Look at Narrator Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-win-11-installation-essential-usb-techniques-for-3-methods/"><u>Navigating Win 11 Installation: Essential USB Techniques for 3 Methods</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-messages-from-oppo-reno-10-pro-5g-by-fonelab-android-recover-messages/"><u>Possible solutions to restore deleted messages from Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-steams-captcha-failed-issue/"><u>Quick Fixes for Steam's 'CAPTCHA Failed' Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-os-experience-auto-updates-graphics-card-swap-in-win10/"><u>Seamless OS Experience: Auto Updates, Graphics Card Swap in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-downloads-with-these-5-torrent-clients/"><u>Streamline Your Downloads with These 5 Torrent Clients</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-guide-to-splitting-videos-in-full-hd-keeping-quality-and-resolution-intact/"><u>Ultimate Guide to Splitting Videos in Full HD - Keeping Quality and Resolution Intact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-to-eradicate-windows-error-code-0x800704b3/"><u>Unlocking Secrets to Eradicate Windows' Error Code: 0X800704B3</u></a></li>
</ul></div>

