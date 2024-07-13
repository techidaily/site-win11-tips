---
title: Addressing OneDrive's Faulty Blob Tag Errors in Windows
date: 2024-07-12T17:55:35.838Z
updated: 2024-07-13T17:55:35.838Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing OneDrive's Faulty Blob Tag Errors in Windows
excerpt: This Article Describes Addressing OneDrive's Faulty Blob Tag Errors in Windows
keywords: OneDrive Blob Errors Fix,Blob Tag Issues Windows,Overcome OneDrive Error,Fixing Drives Blob Faults,Resolve OneDrive Tag Mistakes,Windows Storage Error Remedy,Addressing OneDrive Tag Glitches
thumbnail: https://thmb.techidaily.com/21f134ff6252e8b65e4072cbcc9d1f7716bea3abeb6dec26820e9ae291c1ae1c.jpg
---

## Addressing OneDrive's Faulty Blob Tag Errors in Windows

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

## 2\. Run the DISM and SFC Scan

 Like CHKDSK, SFC and DISM scans can be used when your system behaves strangely. Initially, you should run the SFC scan because it usually resolves the issue. However, if it fails to diagnose the problem or run, you should run a DISM scan.

 Performing both scans ensures that your device does not have corrupted system files causing the trouble. To run both scans, follow these steps:

1. Open Command Prompt as an administrator.
2. To run the SFC scan, type the following command and press**Enter** :  
`SFC /scannow`
3. To run the DISM scan, type the following command and press**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 To better understand the results of these scans, see our [article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

## 4\. Remove the Passwords From the Problematic Files

 Has this error occurred after password-protecting a synced file on OneDrive? In this case, you should go to OneDrive, check the history of modified files, and restore the problematic file to a previous version. Our article on [recovering OneDrive files from version history](https://www.makeuseof.com/tag/restore-onedrive-files-version-history/#rolling-back-a-file) explains how to roll back a file. Reset OneDrive if this fix does not solve the problem.

## 5\. Reset OneDrive

 Resetting the app or service is a good troubleshooting step for problems that don't resolve with general fixes. Therefore, if none of the fixes have worked so far, you should reset OneDrive. Remember that resetting OneDrive will not delete your data, but you'll have to set up the sync connection again.

 In our article on [how to fix OneDrive when you can't open the files](https://www.makeuseof.com/ways-fix-onedrive-when-you-cannot-open-your-files/#reset-onedrive) , we have explained how to reset OneDrive. Follow the instructions in the article to reset OneDrive, and hopefully, you will be able to fix the issue. However, if that also fails to work and the error appears periodically, you can delete or relocate the problematic file or folder.

## 6\. Delete or Relocate the Problematic File

 If all else fails, delete or relocate the problematic file. However, before you do that, you need to pause the OneDrive sync and leave it for an hour. Then, access your OneDrive online and remove the synced file from there.

 Once done, you should turn off your device's internet connection and [start Windows 11 in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) (or [Windows 10](https://www.makeuseof.com/tag/boot-windows-10-safe-mode/) if you're using an older version). Afterward, navigate to your local drive, where the problematic file is located. Delete it from there and restart your device normally.

 If the file you are experiencing the error with has value to you and you cannot delete it, move it to another computer and delete it from your primary device. Hopefully, relocating or deleting the file will prevent the error from occurring again.

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
<li><a href="https://win11-tips.techidaily.com/steer-clear-of-stuck-arrows-in-windows/"><u>Steer Clear of Stuck Arrows in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-simplify-network-connection-configurations-in-winos/"><u>10 Ways to Simplify Network Connection Configurations in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-different-methods-to-unlock-your-apple-iphone-15-pro-by-drfone-ios/"><u>In 2024, Different Methods To Unlock Your Apple iPhone 15 Pro</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-detecting-crystalline-collision-audio/"><u>Updated 2024 Approved Detecting Crystalline Collision Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-remote-desktop-connection-tool-in-windows-11/"><u>10 Ways to Open the Remote Desktop Connection Tool in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-and-craft-of-podcast-storytelling/"><u>[New] The Art and Craft of Podcast Storytelling</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-10-highest-performing-business-youtube-platforms-explained/"><u>[Updated] 10 Highest Performing Business YouTube Platforms Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719241162172-update-drivers-make-sure-your-graphics-card-drivers-are-up-to-date-for-optimal-performance/"><u>Update Drivers: Make Sure Your Graphics Card Drivers Are up to Date for Optimal Performance.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/12-superfluous-windows-tools-you-can-live-without/"><u>12 Superfluous Windows Tools You Can Live Without</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-next-generation-of-green-visual-effects-tools-for-2024/"><u>[Updated] Next Generation of Green Visual Effects Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-straightforward-steps-to-engage-repair-tool/"><u>10 Straightforward Steps to Engage Repair Tool</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-tune-up-guide-new-gadgets-reviewed/"><u>[New] 2024 Approved  Tune-Up Guide  New Gadgets Reviewed</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-best-strategies-for-saving-igtv-videos-mobilely/"><u>[Updated] In 2024, The Best Strategies for Saving IGTV Videos Mobilely</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitter-livestreaming-a-comprehensive-guide/"><u>Twitter Livestreaming  A Comprehensive Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-mp4-video-editing-on-a-budget-top-10-free-tools/"><u>In 2024, MP4 Video Editing on a Budget Top 10 Free Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-tips-for-restoring-fbm-functionality-on-desktop/"><u>10 Key Tips for Restoring FBM Functionality on Desktop</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-the-path-to-tiktok-stardom-increasing-your-views-likes-and-more/"><u>[New] The Path to TikTok Stardom  Increasing Your Views, Likes, and More</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-breakthrough-techniques-in-youtube-content-creation/"><u>[New] Breakthrough Techniques in YouTube Content Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10plus-strategies-for-system-settings-entry/"><u>10+ Strategies for System Settings Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-power-enable-the-outlook-preview-app/"><u>Unlock Windows' Power: Enable the Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-fast-passes-to-the-control-settings-hub/"><u>11 Fast Passes to the Control Settings Hub</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-troubleshooting-error-connecting-to-the-apple-id-server-on-apple-iphone-13-pro-by-drfone-ios/"><u>In 2024, Troubleshooting Error Connecting to the Apple ID Server On Apple iPhone 13 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719202889022-efficient-tips-for-resolving-common-windows-problems/"><u>Efficient Tips for Resolving Common Windows Problems</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-unveiling-the-magic-of-clear-audio-eliminating-ambient-noises-using-audacity/"><u>[New] Unveiling the Magic of Clear Audio  Eliminating Ambient Noises Using Audacity</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/prime-tools-and-techniques-image-to-video-conversion/"><u>Prime Tools and Techniques  Image-to-Video Conversion</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-sharpsight-screen-snag-report/"><u>[New] SharpSight Screen Snag Report</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-weekly-must-see-elite-igtv-talents/"><u>[New] In 2024, Weekly Must-See  Elite IGTV Talents</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-navigating-through-the-essentials-of-snap-camera-on-ms-teams/"><u>[Updated] 2024 Approved  Navigating Through the Essentials of Snap Camera on MS Teams</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximizing-your-videos-reach-a-guide-to-legal-yield-boosting/"><u>[Updated] Maximizing Your Video's Reach  A Guide to Legal Yield Boosting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-perfect-your-tiktok-with-these-stitching-techniques-for-2024/"><u>[New] Perfect Your TikTok With These Stitching Techniques for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-free-or-paid-the-complete-guide-to-joining-disconitro/"><u>2024 Approved  Free or Paid? The Complete Guide to Joining DiscoNitro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-dilemma-obs-not-opening-on-windows/"><u>Resolving the Dilemma: OBS Not Opening on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-fixes-for-fbm-not-working-here/"><u>10 Essential Fixes for FBM Not Working Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-11-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 11 Blue Screen Error</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-rediscovering-archived-discussions-on-reddit-now/"><u>[Updated] Rediscovering Archived Discussions on Reddit Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719233153106-eliminate-printer-problems-fast-win11-fixed/"><u>Eliminate Printer Problems Fast: Win11 Fixed!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-ensuring-your-shorts-videos-thumbnail-shows-up/"><u>[Updated] 2024 Approved  Ensuring Your Shorts Video's Thumbnail Shows Up</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-samsung-galaxy-s24-ultra-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Samsung Galaxy S24 Ultra FRP Bypass With Best Methods</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-professional-photogridding-services-to-polish-your-art/"><u>In 2024, Professional Photogridding Services to Polish Your Art</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719203477260-how-to-unfreeze-google-chrome-in-windows-11-fastly-find-out-now/"><u>How to Unfreeze Google Chrome in Windows 11 Fastly? Find Out Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719205412582-shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719192555427-environment-variables-configuration/"><u>Environment Variables Configuration:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-command-routes-for-fast-diagnostic-center-entry/"><u>10 Command Routes for Fast Diagnostic Center Entry</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-charting-the-stars-instagrams-leading-25-trailblazers-in-digital-dominion/"><u>[Updated] 2024 Approved  Charting the Stars  Instagram’s Leading 25 Trailblazers in Digital Dominion</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-reducing-jitter-in-visual-content-creation/"><u>[New] Reducing Jitter in Visual Content Creation</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-design-your-dream-invite-10-top-free-online-video-makers/"><u>New Design Your Dream Invite 10 Top Free Online Video Makers</u></a></li>
<li><a href="https://review-topics.techidaily.com/new-iphone-6s-plus-restore-from-icloud-stuck-on-time-remaining-estimating-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>New iPhone 6s Plus Restore from iCloud Stuck on Time Remaining Estimating | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-s-mode-imply-in-windows-11-upgrade/"><u>What Does 'S Mode' Imply in Windows 11 Upgrade?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-strategies-for-managing-windows-connections-tool/"><u>10 Key Strategies for Managing Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-simplified-techniques-to-winrm-tool/"><u>10 Simplified Techniques to WinRM Tool</u></a></li>
</ul></div>
