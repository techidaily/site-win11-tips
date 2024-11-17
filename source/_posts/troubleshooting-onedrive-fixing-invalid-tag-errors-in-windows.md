---
title: "Troubleshooting OneDrive: Fixing Invalid Tag Errors in Windows"
date: 2024-11-13T16:01:14.407Z
updated: 2024-11-17T16:51:29.802Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting OneDrive: Fixing Invalid Tag Errors in Windows"
excerpt: "This Article Describes Troubleshooting OneDrive: Fixing Invalid Tag Errors in Windows"
keywords: OneDrive Troubleshoot,Invalid Tags Solve,Fix Error Windows,Microsoft Drive Fix,OneDrive Fix Steps,Tag Error Resolve,OneDrive Validation
thumbnail: https://thmb.techidaily.com/c44b3c2a949ed90a1a74d6b8f5c0458cbf8a943f8d64ce0fc757b91844bd2888.jpg
---

## Troubleshooting OneDrive: Fixing Invalid Tag Errors in Windows

 Have you encountered the "the tag present in the reparse point buffer is invalid" error when altering a folder or deleting it on your Windows device? You may have encountered this error when accessing a folder via Command Prompt or File Explorer, mainly for files and folders synced to OneDrive. How does this error occur? OneDrive is the source of the error.

 In this article, we'll explain the causes of this error and provide you with possible solutions to resolve it.

## What Causes "The Tag Present in the Reparse Point Buffer Is Invalid" on Windows?

 As mentioned earlier, the error is caused by a problem with OneDrive sync. It could be that the folder you're trying to access is corrupt, or that there is an issue with other system files preventing OneDrive from syncing successfully.

 There are several ways in which the "the tag present in the reparse point buffer is invalid" error can appear. Here are the two most common ones:

* Error 0x80071129: The tag present in the reparse point buffer is invalid
* Location not found: The tag present in the reparse point buffer is invalid

 "Error 0x80071129" or "Location not found" appears as the title of the error window, while the main part of the error appears in the error window. Any variation of this error has nearly the same causes, regardless of its nature. In light of that, similar fixes are effective in resolving the issue. Let's see how you can fix it.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## But First, Some Preliminary Checks

 Apply the following preliminary checks before attempting the major fixes:

* Pause the OneDrive sync and try opening the folder again.
* Restart your device once.
* Log out of your OneDrive account.
* If you have made any changes to the problematic folder on OneDrive, go back and revert them for a while.

 If the above preliminary checks do not solve the problem and the issue persists, start implementing the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 To better understand the results of these scans, see our[article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-mastering-the-game-discover-these-top-12-pc-clickers/"><u>[New] 2024 Approved Mastering the Game Discover These Top 12 PC Clickers</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-samsung-camera-toolkit-review-2023-edition/"><u>[New] In 2024, Samsung Camera Toolkit Review – 2023 Edition</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-advanced-methods-for-desktopmobile-screen-casting/"><u>[Updated] Advanced Methods for Desktop/Mobile Screen Casting</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-effortless-audio-downloads-these-24-tools-split-youtube-sounds-for-2024/"><u>[Updated] Effortless Audio Downloads These 24 Tools Split YouTube Sounds for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-ranking-the-best-ios-devices-tools-to-download-fb-movies-and-tunes/"><u>[Updated] In 2024, Ranking the Best iOS Devices' Tools to Download FB Movies & Tunes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-engage-listeners-through-instagram-and-podcasts/"><u>2024 Approved How To Engage Listeners Through Instagram & Podcasts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-time-lapse-magic-capturing-moments-with-an-ipad/"><u>2024 Approved Time-Lapse Magic Capturing Moments with an iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-most-effective-win-pc-tracking-apps-today/"><u>Discover the Most Effective Win PC Tracking Apps Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/echo-chatters-how-to-fix-silent-microphones-on-google-meet-windows/"><u>Echo Chatters: How to Fix Silent Microphones on Google Meet, Windows</u></a></li>
<li><a href="https://fox-zero.techidaily.com/effortless-folder-discovery-using-advanced-search-tool/"><u>Effortless Folder Discovery Using Advanced Search Tool</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/essential-insights-on-how-long-it-takes-to-set-up-windows-11-a-complete-overview/"><u>Essential Insights on How Long It Takes to Set Up Windows 11 - A Complete Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-climate-tools-for-w10w11-users/"><u>Exclusive Climate Tools for W10/W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-way-user-access-control-works-for-administrators-on-windows/"><u>How to Change the Way User Access Control Works for Administrators on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-touchpad-sensitivity-on-windows-11-laptops/"><u>How to Change Touchpad Sensitivity on Windows 11 Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vlc-format-error-on-windows-systems/"><u>Overcoming VLC Format Error on Windows Systems</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/revolutionize-your-business-with-these-essential-five-ai-tools/"><u>Revolutionize Your Business With These Essential Five AI Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-game-controllers-dualshock-for-pcs/"><u>Seamless Game Controllers: DualShock for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unshackle-notepad-quick-efficient-ways-to-restart-on-windows-pcs/"><u>Unshackle Notepad: Quick, Efficient Ways to Restart on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-enablingdisabling-usb-device-access/"><u>Windows Security: Enabling/Disabling USB Device Access</u></a></li>
</ul></div>

