---
title: How to Run the System File Checker (SFC) in Windows
date: 2024-08-08T11:09:37.742Z
updated: 2024-08-09T11:09:37.742Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Run the System File Checker (SFC) in Windows
excerpt: This Article Describes How to Run the System File Checker (SFC) in Windows
keywords: SFC Execute Guide,SFC Repair Tool,Windows System Integrity,Running SFC Command,Fixing File Errors,OS File Checker,SFC Diagnostic Tool
thumbnail: https://thmb.techidaily.com/4d3965d206c3e8f9b4a9da6d71e7e79363ab237dd992d3524ab2a99d8d4908ed.jpg
---

## How to Run the System File Checker (SFC) in Windows

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

 If you’re unfamiliar with operating system files, please read our guide on[what system files are on Windows](https://www.makeuseof.com/windows-system-files-guide/) . And to learn everything you need to know about Command Prompt, you can check out our[beginner's guide to Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## What Happens After I Run the System File Checker?

 After the System File Checker completes its scan, it will display a message in the Command Prompt window with the results.

 If your system files are okay, you’ll see a message that says "Windows Resource Protection did not find any integrity violations." If SFC found and fixed all problematic files, the message will read "Windows Resource Protection found corrupt files and successfully repaired them."

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Other SFC Commands You Can Run on Windows

 The**SFC /scannow** isn’t the only System File Checker Command you can run. Here are a couple more and what they do:

| SFC Command | Description                                                                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /verifyonly | Run this command if you want SFC to check for problematic operating system files without fixing them.                                                                                                                                                                             |
| /scanfile   | Run this command if you want SFC to check a specific file for problems and fix it if it does have them. For example, Here’s the full command for checking and fixing the**user32.dll** file:**SFC /scanfile=c:\\windows\\system32\\user32.dll**                                   |
| /verifyfile | Run this command if you only want to check a particular system file for problems. Even if SFC finds an issue with the file, it will not repair it. For example, Here’s the full command for checking the**user32.dll** file:**SFC /verifyfile=c:\\windows\\system32\\user32.dll** |
| /offbootdir | Run this command to tell the SFC which directory contains a bootable version of Windows. You need to do this every time you use the tool outside of Windows. For example, to select the**E:** drive on your PC, enter**/offbootdir=e:\\**                                         |
| /offwindir  | Run this command to tell the SFC which folder in the directory — the one you specified with the**SFC /offbootdir** command — contains Windows. For example, enter**/offwindir=e:\\windows** to tell the System File Checker that Windows is on the**E:** drive.                   |

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by[creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.

## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-spark-interest-with-style-mixing-tiktoks-genius-techniques-for-insta/"><u>[New] 2024 Approved  Spark Interest with Style  Mixing TikTok's Genius Techniques for Insta</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-maximizing-fb-instream-ad-impact-configuration-techniques-and-metrics-for-2024/"><u>[New] Maximizing FB Instream Ad Impact  Configuration Techniques and Metrics for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-easy-recording-setups-for-lol-enthusiasts-3-ways/"><u>[Updated] Easy Recording Setups for LOL Enthusiasts (3 Ways)</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-best-script-artisans-domain/"><u>2024 Approved  Best Script Artisan's Domain</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-sony-xperia-1-v-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Sony Xperia 1 V Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abruptly-quell-windows-11-interruptions/"><u>Abruptly Quell Windows 11 Interruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-variances-in-remote-and-in-house-windows-setup/"><u>Analyzing Variances in Remote & In-House Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-space-available-for-windows-11-pin-listings/"><u>Boosting Space Available for Windows 11 Pin Listings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-from-frozen-windows-pin-locks/"><u>Breaking Free From Frozen Windows PIN Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/data-defense-on-windows-top-rated-encryption-applications-153-chars/"><u>Data Defense on Windows: Top-Rated Encryption Applications (153 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-win-credits-to-microsoft-logins/"><u>Directing WIN Credits to MICROSOFT LOGINS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-tackling-epic-games-sign-in-on-pc/"><u>Efficiently Tackling Epic Games Sign-In on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-calendar-look-with-outlook-customization-tricks/"><u>Elevate Your Calendar Look with Outlook Customization Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-shutting-down-windows-11-privacy-features/"><u>Guide to Shutting Down Windows 11 Privacy Features</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/how-to-add-a-countdown-timer-in-obs/"><u>How To Add a Countdown Timer in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enhance-windows-11-task-manager-with-a-search-tool/"><u>How to Enhance Windows 11 Task Manager with a Search Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-system-requirements-not-met-watermark-in-windows-11/"><u>How to Remove the System Requirements Not Met Watermark in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-on-apple-iphone-14-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password On Apple iPhone 14</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-nvidia-driver-selection-gameplay-or-studio-focus/"><u>Ideal Nvidia Driver Selection - Gameplay or Studio Focus</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-realme-12-5g-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Realme 12 5G?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-seeking-out-facebooks-streamed-movies-and-shows/"><u>In 2024, Seeking Out Facebook's Streamed Movies & Shows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/including-third-party-storage-on-file-explorer/"><u>Including Third-Party Storage on File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intro-to-digital-art-accessing-microsoft-paint-in-windows-11/"><u>Intro to Digital Art: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/legacy-tech-lifeline-atlasos-revival-plan/"><u>Legacy Tech Lifeline: AtlasOS Revival Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-notepads-visual-transformation-with-dark-themes-windows/"><u>Master Notepad’s Visual Transformation with Dark Themes (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-thumb-button-clicks-in-windows-11/"><u>Mastering Mouse Thumb Button Clicks in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-samsung-dex-connect-galaxy-and-pc-seamlessly/"><u>Mastering Samsung DeX: Connect Galaxy & PC Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-fix-of-xbox-error-code-0x800700e9/"><u>Mastering the Fix of Xbox Error Code: 0X800700E9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-notepad-stability/"><u>Mastering Windows Notepad Stability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-auditory-anomaly-code-0xd36b4-on-windows/"><u>Navigating Through Auditory Anomaly: Code 0Xd36b4 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-interface-clarity-displaying-this-pc-icon/"><u>Optimizing Interface Clarity: Displaying 'This PC' Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unknown-disk-error-in-windows/"><u>Overcoming Unknown Disk Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-keyboard-actions-on-windows-platform/"><u>Personalize Keyboard Actions on Windows Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-task-execution-creating-effective-win-cmds/"><u>Personalize Task Execution: Creating Effective Win Cmds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reduce-chrome-distractions-in-windows-1110/"><u>Reduce Chrome Distractions in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reignite-your-onedrive-login-windows-solutions-needed/"><u>Reignite Your OneDrive Login: Windows Solutions Needed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-airpods-and-windows-compatibility/"><u>Simplified Guide: AirPods & Windows Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-keyboard-wizardry-with-windows-tools/"><u>Speedy Keyboard Wizardry with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-recover-icon-positions-in-windows-10/"><u>Swiftly Recover Icon Positions in Windows 10</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nail-insight-top-picks-for-maximizing-video-visibility-for-2024/"><u>Thumbnail Insight  Top Picks for Maximizing Video Visibility for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-analytical-points-showcasing-pcs-edge-over-macs/"><u>Top 9 Analytical Points Showcasing PC's Edge Over Macs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-causes-behind-usb-attachment-failure-in-virtualbox/"><u>Unraveling the Causes Behind 'USB Attachment Failure' In VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vcplusplus-redistribution-purpose-explored/"><u>VC++ Redistribution Purpose Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/veiled-functionality-for-context-tools-on-pcs/"><u>Veiled Functionality for Context Tools on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-the-lost-bluetooth-9-effective-solutions-to-find-your-connection/"><u>Win 11 and the Lost Bluetooth: 9 Effective Solutions to Find Your Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-audio-test-failure-immediate-action-plan/"><u>Windows Audio Test Failure: Immediate Action Plan</u></a></li>
</ul></div>
