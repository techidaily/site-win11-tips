---
title: Steps to Correct OneDrive's Invalid Blob Tag Error on PC
date: 2024-07-12T17:36:23.206Z
updated: 2024-07-13T17:36:23.206Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Correct OneDrive's Invalid Blob Tag Error on PC
excerpt: This Article Describes Steps to Correct OneDrive's Invalid Blob Tag Error on PC
keywords: Fixing Invalid Blob in OneDrive,OneDrive Error Resolution Guide,Cure Blob Tag Glitch OneDrive,Overcoming OneDrive Blob Issue,Rectify OneDrive File Mistake,Correcting OneDrive Invalid Data,Troubleshoot OneDrive Error #123
thumbnail: https://thmb.techidaily.com/23f15d03527dcdfd4e30255dbd41a14d668e3faafe915e31c07d32bad6007903.png
---

## Steps to Correct OneDrive's Invalid Blob Tag Error on PC

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
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2023how-to-share-videos-on-twitter-on-your-phone-without-retweeting-for-2024/"><u>2023|How to Share Videos on Twitter on Your Phone Without Retweeting for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-fixing-unexpected-system-call-failures-on-win1011/"><u>Guide: Fixing Unexpected System Call Failures on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/never-again-struggle-with-file-explorer-on-windows-11/"><u>Never Again Struggle with File Explorer on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reduce-windows-surrounders-feature/"><u>How To Reduce Windows Surrounders Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-pasting-feature-in-chrome-edge-firefox-oses/"><u>Unblocking Pasting Feature in Chrome, Edge, Firefox OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-w11-utilizing-error-lookup-tool-features/"><u>Troubleshooting W11: Utilizing Error Lookup Tool Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gaming-smoother-with-warhammer-40k-on-windows-no-more-stutters/"><u>Gaming Smoother with Warhammer 40K on Windows, No More Stutters</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-top-8-undead-adventures-ultimate-zombie-game-guide/"><u>[Updated] In 2024, Top 8 Undead Adventures  Ultimate Zombie Game Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-creation-from-batch-to-exe-on-pc/"><u>Streamlining File Creation From Batch to EXE on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-broken-enter-button-on-pc/"><u>Fixing Broken Enter Button on PC</u></a></li>
<li><a href="https://screen-recording.techidaily.com/augmenting-your-stardew-experience-with-seven-top-mods-for-2024/"><u>Augmenting Your Stardew Experience with Seven Top Mods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-fix-it-steps-to-eradicate-win10-blue-screen/"><u>Proven Fix-It Steps to Eradicate Win10 Blue Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-back-to-joy-playing-classics-on-dosbox-x/"><u>Jump Back to Joy: Playing Classics on DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-world-of-pc-chips-identifying-gen-through-windows-8-ways/"><u>Navigating the World of PC Chips – Identifying Gen Through Windows (8 Ways)</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-apple-id-from-iphone-13-pro-max-without-password-by-drfone-ios/"><u>How to Remove Apple ID from iPhone 13 Pro Max without Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-default-windows-configuration/"><u>Tips for Restoring Default Windows Configuration</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/introduction/"><u>Introduction</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-vivo-v30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-realme-11-5g-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-free-invitation-video-software-our-top-recommendations/"><u>Updated Free Invitation Video Software Our Top Recommendations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microsoft-store-error-0x80073d26/"><u>Troubleshooting Microsoft Store Error 0X80073D26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-default-file-savings-in-windows-pcs/"><u>How to Solve Default File Savings in Windows PCs</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-on-apple-iphone-12-mini-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code On Apple iPhone 12 mini in the Best Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-science-of-storage-sizing-in-windows-through-powershell/"><u>Mastering the Science of Storage Sizing in Windows Through Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-your-user-experience-customizing-windows-11-defaults/"><u>Enhancing Your User Experience: Customizing Windows 11 Defaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screenshare-success-crafting-unique-wallpapers-per-windows-1011-monitor/"><u>Screenshare Success: Crafting Unique Wallpapers per Windows 10/11 Monitor</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-best-of-the-best-top-free-video-editors-for-mp4-files/"><u>2024 Approved Best of the Best Top Free Video Editors for MP4 Files</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-server-executed-failed-mystery/"><u>Unraveling the 'Server Executed Failed' Mystery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-revive-slowq-bittorrent-progress-on-pc/"><u>Strategies to Revive Slowq Bittorrent Progress on PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-cerebral-showcase-gk-video-challenge-network/"><u>In 2024, Cerebral Showcase - GK Video Challenge Network</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-best-5-youtube-tag-generators-and-tips-to-tag-videos-properly/"><u>[New] Best 5 YouTube Tag Generators & Tips to Tag Videos Properly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-hidden-remove-button-for-windows-11-security/"><u>Reactivating Hidden 'Remove' Button for Windows 11 Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-playbook-winning-at-ps1-gaming-on-windows-duckstation-edition/"><u>The Ultimate Playbook: Winning at PS1 Gaming on Windows - Duckstation Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-rectifying-obs-studio-server-connectivity-hiccups/"><u>Essential Tips for Rectifying OBS Studio Server Connectivity Hiccups</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-unearthing-the-obscured-videotapes/"><u>[New] YouTube  Unearthing the Obscured Videotapes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-final-cut-pro-mastery-secrets-revealed/"><u>2024 Approved  Free Final Cut Pro Mastery  Secrets Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-space-on-your-disk-keep-files-and-free-up-room-in-win11-max-156-chars/"><u>Saving Space on Your Disk: Keep Files & Free Up Room in Win11 (Max 156 Chars)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-supreme-selection-ideal-sierra-dvd-and-video-apps/"><u>In 2024, Supreme Selection  Ideal Sierra Dvd & Video Apps</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-oppo-reno-10-5g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Oppo Reno 10 5G to Another | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/15-best-stop-motion-films-of-all-time-for-2024/"><u>15 Best Stop Motion Films of All Time for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-picture-perfect-your-essential-guide-to-uploading-on-youtube/"><u>[New] Picture Perfect  Your Essential Guide to Uploading on YouTube</u></a></li>
<li><a href="https://driver-install.techidaily.com/simple-steps-restarting-bluetooth-on-windows-1111/"><u>Simple Steps: Restarting Bluetooth on Windows 11/11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-tiktok-video-safeguarding-on-smartphones-uncovered/"><u>In 2024, TikTok Video Safeguarding on Smartphones Uncovered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sign-out-failures-from-non-standard-windows-applications/"><u>Resolving Sign-Out Failures From Non-Standard Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-not-certified-by-microsoft-on-pc/"><u>Troubleshooting 'App Not Certified by Microsoft' On PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapidly-engageturn-off-bings-ai-window-chat/"><u>Rapidly Engage/Turn Off Bing's AI Window Chat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-seamless-installation-windows-11-in-place-upgrade-techniques/"><u>Mastering the Seamless Installation: Windows 11 In-Place Upgrade Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-dark-mode-in-notepad-on-windows-10-and-11/"><u>How to Enable Dark Mode in Notepad on Windows 10 & 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/comparing-leading-free-and-paid-zoom-transcription-systems-for-2024/"><u>Comparing Leading Free & Paid Zoom Transcription Systems for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-vintage-gaming-journey-integrating-trophies-via-retroarch/"><u>Transform Your Vintage Gaming Journey: Integrating Trophies via Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installation-failure-in-discord-for-win-1011/"><u>Troubleshooting Installation Failure in Discord for Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keys-fans-ultimate-guide-to-score-lifetime-windows-11-at-unbeatable-price/"><u>Keys Fans' Ultimate Guide to Score Lifetime Windows 11 at Unbeatable Price</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-disk-space-safely/"><u>Maximizing Windows Disk Space Safely</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-samsung-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Samsung</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-restoring-standard-user-permissions/"><u>Mastering Windows 11: Restoring Standard User Permissions</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-top-5-mac-alternatives-to-bandicam-for-video-capture/"><u>[New] 2024 Approved  Top 5 Mac Alternatives to Bandicam for Video Capture</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-pinnacle-of-vr-how-htc-vive-transforms-playtime-for-2024/"><u>The Pinnacle of VR  How HTC Vive Transforms Playtime for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-capturing-the-cloud-proven-methods-for-perfecting-drones-in-post-production/"><u>[Updated] Capturing the Cloud  Proven Methods for Perfecting Drones in Post-Production</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-controlling-devices-on-dormant-windows-systems/"><u>Strategies for Controlling Devices on Dormant Windows Systems</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-iphone-15-drfone-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-failed-remotes-a-step-by-step-guide-for-windows-users/"><u>Resetting Failed Remotes: A Step-By Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11s-zip-compression-issues-quickly/"><u>Fixing Windows 11'S Zip Compression Issues Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disrupt-a-persistent-dark-theme-on-windows/"><u>How to Disrupt a Persistent Dark Theme on Windows</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-unleash-your-creativity-top-14-video-editing-software-for-vloggers/"><u>New Unleash Your Creativity Top 14 Video Editing Software for Vloggers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-non-windows-tools-that-outperform-snipping-tool/"><u>Essential Non-Windows Tools That Outperform Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-screens-skip-pin-in-windows-11-projections/"><u>Unlocking Screens: Skip PIN in Windows 11 Projections</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-mastering-windows-11-photo-and-video-import-magic/"><u>2024 Approved  Mastering Windows 11  Photo & Video Import Magic</u></a></li>
</ul></div>
