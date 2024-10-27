---
title: Mitigating Invalid Reparse Buffer Tag Error with OneDrive
date: 2024-10-20T16:25:07.408Z
updated: 2024-10-26T21:48:45.695Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mitigating Invalid Reparse Buffer Tag Error with OneDrive
excerpt: This Article Describes Mitigating Invalid Reparse Buffer Tag Error with OneDrive
keywords: Invalid Reparse Fix,OneDrive Recovery,Reparse Tag Error,Error Mitigation 1Drive,OneDrive Data Fix,Reparse Buffer Error,1Drive Invalid Tag Resolution
thumbnail: https://thmb.techidaily.com/d62120d0f92dda8643d1fb18ba050a4238aed422d93382b937c3fa171ed251d1.jpg
---

## Mitigating Invalid Reparse Buffer Tag Error with OneDrive

 Have you encountered the "the tag present in the reparse point buffer is invalid" error when altering a folder or deleting it on your Windows device? You may have encountered this error when accessing a folder via Command Prompt or File Explorer, mainly for files and folders synced to OneDrive. How does this error occur? OneDrive is the source of the error.

 In this article, we'll explain the causes of this error and provide you with possible solutions to resolve it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes "The Tag Present in the Reparse Point Buffer Is Invalid" on Windows?

 As mentioned earlier, the error is caused by a problem with OneDrive sync. It could be that the folder you're trying to access is corrupt, or that there is an issue with other system files preventing OneDrive from syncing successfully.

 There are several ways in which the "the tag present in the reparse point buffer is invalid" error can appear. Here are the two most common ones:

* Error 0x80071129: The tag present in the reparse point buffer is invalid
* Location not found: The tag present in the reparse point buffer is invalid

 "Error 0x80071129" or "Location not found" appears as the title of the error window, while the main part of the error appears in the error window. Any variation of this error has nearly the same causes, regardless of its nature. In light of that, similar fixes are effective in resolving the issue. Let's see how you can fix it.

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

## 2\. Run the DISM and SFC Scan

 Like CHKDSK, SFC and DISM scans can be used when your system behaves strangely. Initially, you should run the SFC scan because it usually resolves the issue. However, if it fails to diagnose the problem or run, you should run a DISM scan.

 Performing both scans ensures that your device does not have corrupted system files causing the trouble. To run both scans, follow these steps:

1. Open Command Prompt as an administrator.
2. To run the SFC scan, type the following command and press**Enter** :  
`SFC /scannow`
3. To run the DISM scan, type the following command and press**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148648/16836" target="_top" id="2148648">
  <img src="//a.impactradius-go.com/display-ad/16836-2148648" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148648/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To better understand the results of these scans, see our[article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-support.techidaily.com/new-leveraging-azures-speech-to-text-for-enterprise-solutions/"><u>[New] Leveraging Azure's Speech-to-Text for Enterprise Solutions</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/astering-the-art-of-video-production-initial-setup-for-2024/"><u>[New] Mastering the Art of Video Production Initial Setup for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-full-screen-pro-tips-and-tricks-for-editors/"><u>[Updated] 2024 Approved Full Screen Pro Tips and Tricks for Editors</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-creating-seamless-zoom-experiences/"><u>[Updated] Creating Seamless Zoom Experiences</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-tecno-spark-20-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Tecno Spark 20 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commanding-your-digital-files-linking-dropbox-googledrive-to-c/"><u>Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-at-your-fingertips-discover-how-to-access-win11-disk-management/"><u>Efficiency at Your Fingertips: Discover How to Access Win11 Disk Management</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-network-locked-motorola-moto-g13-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Motorola Moto G13 Phone?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/leveraging-a-3-step-writing-system-for-social-media-success-with-fb-ads-for-2024/"><u>Leveraging a 3-Step Writing System for Social Media Success with FB Ads for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/meeting-prep-made-easy-webcam-and-microphone-checklist-windows/"><u>Meeting Prep Made Easy: Webcam & Microphone Checklist (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-call-failed-errors-on-windows-pcs/"><u>Mitigating Call Failed Errors on Windows PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/pioneers-in-the-realm-of-vr-viewing/"><u>Pioneers in the Realm of VR Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-opengl-errors-targeting-code-3-in-win11/"><u>Quick Fixes for OpenGL Errors: Targeting Code #3 in Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/remedies-for-disabling-obs-fullscreen-for-2024/"><u>Remedies for Disabling OBS Fullscreen for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-system-the-three-ways-to-a-new-start/"><u>Revive Your System: The Three Ways to a New Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-troubleshoot-and-stop-non-specific-audio-on-win-10/"><u>Steps to Troubleshoot and Stop 'Non-Specific Audio' On Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-user-profile-not-valid-errors-in-win10win11/"><u>Tackling User Profile Not Valid Errors in Win10/Win11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-second-generation-of-google-nest-hub-insights-a-missed-opportunity-without-cameras/"><u>The Second Generation of Google Nest Hub Insights - A Missed Opportunity Without Cameras?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-code-xc0000142-in-windows/"><u>Troubleshooting Code XC0000142 in Windows</u></a></li>
</ul></div>

