---
title: "Troubleshooting OneDrive: Fixing Invalid Tag Errors in Windows"
date: 2024-09-01T05:17:40.203Z
updated: 2024-09-02T05:17:40.203Z
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

## But First, Some Preliminary Checks

 Apply the following preliminary checks before attempting the major fixes:

* Pause the OneDrive sync and try opening the folder again.
* Restart your device once.
* Log out of your OneDrive account.
* If you have made any changes to the problematic folder on OneDrive, go back and revert them for a while.

 If the above preliminary checks do not solve the problem and the issue persists, start implementing the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
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

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To better understand the results of these scans, see our[article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

## 4\. Remove the Passwords From the Problematic Files

 Has this error occurred after password-protecting a synced file on OneDrive? In this case, you should go to OneDrive, check the history of modified files, and restore the problematic file to a previous version. Our article on[recovering OneDrive files from version history](https://www.makeuseof.com/tag/restore-onedrive-files-version-history/#rolling-back-a-file) explains how to roll back a file. Reset OneDrive if this fix does not solve the problem.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reset OneDrive

 Resetting the app or service is a good troubleshooting step for problems that don't resolve with general fixes. Therefore, if none of the fixes have worked so far, you should reset OneDrive. Remember that resetting OneDrive will not delete your data, but you'll have to set up the sync connection again.

 In our article on[how to fix OneDrive when you can't open the files](https://www.makeuseof.com/ways-fix-onedrive-when-you-cannot-open-your-files/#reset-onedrive) , we have explained how to reset OneDrive. Follow the instructions in the article to reset OneDrive, and hopefully, you will be able to fix the issue. However, if that also fails to work and the error appears periodically, you can delete or relocate the problematic file or folder.

## 6\. Delete or Relocate the Problematic File

 If all else fails, delete or relocate the problematic file. However, before you do that, you need to pause the OneDrive sync and leave it for an hour. Then, access your OneDrive online and remove the synced file from there.

 Once done, you should turn off your device's internet connection and[start Windows 11 in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) (or[Windows 10](https://www.makeuseof.com/tag/boot-windows-10-safe-mode/) if you're using an older version). Afterward, navigate to your local drive, where the problematic file is located. Delete it from there and restart your device normally.

 If the file you are experiencing the error with has value to you and you cannot delete it, move it to another computer and delete it from your primary device. Hopefully, relocating or deleting the file will prevent the error from occurring again.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-enhancing-instagram-presence-vimeo-videos-included-for-2024/"><u>[New] Enhancing Instagram Presence  Vimeo Videos Included for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-your-path-forward-on-youtube-self-publishing-vs-major-label-partnership/"><u>[Updated] Your Path Forward on YouTube  Self-Publishing vs Major Label Partnership</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elevate-reach-optimal-strategies-for-crafting-youtube-titles-and-tags/"><u>2024 Approved  Elevate Reach  Optimal Strategies for Crafting YouTube Titles & Tags</u></a></li>
<li><a href="https://fox-links.techidaily.com/4k-uxga-reality-check-detailed-review-of-asus-mg28uq/"><u>4K UXGA Reality Check - Detailed Review of ASUS MG28UQ</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-admin-restrictions-from-windows-security-error/"><u>Clearing Admin Restrictions From Windows Security Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-files-save-errors/"><u>Correcting Windows Files' Save Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-efficient-layout-the-tablet-bar-setup-in-windows-11/"><u>Crafting an Efficient Layout: The Tablet Bar Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-failed-setup-resolving-mspm-issues/"><u>Cure Failed Setup: Resolving MSPM Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodging-the-hurdle-of-microsoft-store-error-0x80072efd-on-windows-devices/"><u>Dodging the Hurdle of Microsoft Store Error 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-fluidity-of-video-playback-in-vlc-win/"><u>Enhancing Fluidity of Video Playback in VLC Win</u></a></li>
<li><a href="https://facebook.techidaily.com/essential-sites-and-locales-for-job-hunting-freelancer/"><u>Essential Sites & Locales for Job Hunting (Freelancer)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/evaluating-photoshop-sway-effective-or-not-for-2024/"><u>Evaluating Photoshop Sway  Effective or Not for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/expert-strategies-for-vocal-identity-on-instagram/"><u>Expert Strategies for Vocal Identity on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-new-heights-increasing-window-11-icon-size/"><u>Explore New Heights: Increasing Window 11 Icon Size</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-gaming-options-asus-steam-deck-vs-rog-ally/"><u>Exploring Gaming Options: ASUS Steam Deck Vs. ROG Ally</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-code-43-errors-for-nvidia-geforce-gtx-950-on-windows-10-platform-guide/"><u>Fixing Code 43 Errors for NVIDIA GeForce GTX 950 on Windows 10 Platform [Guide]</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-canon-printer-driver-downloads-compatible-with-windows-11-8-and-7/"><u>Free Canon Printer Driver Downloads: Compatible with Windows 11, 8 & 7</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-i-lost-half-a-decade-on-whatsapp-and-how-to-securely-prevent-such-losses-for-yourself/"><u>How I Lost Half a Decade on WhatsApp & How to Securely Prevent Such Losses for Yourself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-d3dx939dll-gap-on-windows-11/"><u>How to Mend D3DX9_39.dll Gap on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-off-virtualization-on-windows-11/"><u>How to Turn Off Virtualization on Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-motorola-moto-g73-5g-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Motorola Moto G73 5G</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-a-smooth-switch-of-qbittorrent-on-different-pcs/"><u>Leveraging a Smooth Switch of qBittorrent on Different PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixed-windows-update-issues/"><u>Mastering the Art of Fixed Windows Update Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-steps-of-modifying-win-11s-menu/"><u>Navigating Through the Steps of Modifying Win 11'S Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-dll-rockalldlldll-glitches/"><u>Overcoming 'Missing DLL: Rockalldll.dll' Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-obstacles-in-roblox-error-262-fixes/"><u>Overcoming Common Obstacles in Roblox Error 262 Fixes</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ssional-video-edits-simplified-by-youtube-studio-editor/"><u>Professional Video Edits Simplified by YouTube Studio Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-tricks-navigating-through-winerror-in-oculus-setup-for-ws11ws10/"><u>Proven Tricks: Navigating Through WinError in Oculus Setup for WS11/WS10</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-v29e-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on V29e</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-windows-11s-default-touch-interface-positioning/"><u>Redefining Windows 11'S Default Touch Interface Positioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-windows-error-code-0xc0000001-instances/"><u>Remedy for Windows Error Code 0XC0000001 Instances</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-keyboard-issues-in-the-windows-snipper/"><u>Resolving Keyboard Issues in the Windows Snipper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-steam-storage-write-failure/"><u>Resolving Windows' Steam Storage Write Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-mouse-interaction-with-windows-clicklock-feature/"><u>Revamping Mouse Interaction with Windows ClickLock Feature</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamline-your-day-multitask-mastery-for-the-podcast-aficionado-for-2024/"><u>Streamline Your Day  Multitask Mastery for the Podcast Aficionado for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/successfully-connect-your-epson-wf-amc320dwdc4ja-printer-with-windows-os-driver-download-and-installation-tips/"><u>Successfully Connect Your Epson WF-Amc320DW/DC4JA Printer with Windows OS: Driver Download and Installation Tips</u></a></li>
<li><a href="https://youtube-web.techidaily.com/outubers-playbook-achieving-content-stardom/"><u>The YouTuber's Playbook  Achieving Content Stardom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-desktop-image-save-path-in-windows-11/"><u>Tracking Desktop Image Save-Path in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-common-windows-app-glitches-7-fixes/"><u>Troubleshooting Common Windows App Glitches: 7 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-for-iphone-photo-import-error-on-windows-pc/"><u>Troubleshooting for iPhone Photo Import Error on Windows PC</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-predictive-ai-a-simplified-overview/"><u>Understanding Predictive AI - A Simplified Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-pros-and-cons-of-different-win-video-codes/"><u>Understanding the Pros & Cons of Different Win Video Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-secrets-to-a-responsive-esc-key-in-windows-systems/"><u>Unlock the Secrets to a Responsive Esc Key in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-admin-controls-in-windows-security-alert/"><u>Unlocking Admin Controls in Windows Security Alert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-integrating-previous-pc-software-with-newer-os/"><u>Unlocking Potential: Integrating Previous PC Software with Newer OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-the-component-services-of-windows-11/"><u>Unlocking Secrets: The Component Services of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-windows-correcting-access-violations/"><u>Winning Over Windows: Correcting Access Violations</u></a></li>
</ul></div>
