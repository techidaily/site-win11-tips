---
title: Launching SFC Verification for Windows Files
date: 2024-08-28T01:10:32.368Z
updated: 2024-08-29T01:10:32.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Launching SFC Verification for Windows Files
excerpt: This Article Describes Launching SFC Verification for Windows Files
keywords: Windows File SFC Check,Windows SFC Verify,SFC Scan Windows,SFC Test Windows Files,Verify Windows Integrity,SFC Compliance for Windows,Windows Security Audit
thumbnail: https://thmb.techidaily.com/a29b3ac6ca9f187aecdc1d4dbdad5d59450793de0cab9f35e7f80c9b2a8a933d.png
---

## Launching SFC Verification for Windows Files

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

## What Happens After I Run the System File Checker?

 After the System File Checker completes its scan, it will display a message in the Command Prompt window with the results.

 If your system files are okay, you’ll see a message that says "Windows Resource Protection did not find any integrity violations." If SFC found and fixed all problematic files, the message will read "Windows Resource Protection found corrupt files and successfully repaired them."

![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
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

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-unlock-hidden-instagram-story-views/"><u>[New] 2024 Approved  Unlock Hidden Instagram Story Views</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-best-free-high-quality-streaming-tools-for-webm-video-files/"><u>[New] Best Free, High-Quality Streaming Tools for WebM Video Files</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-how-video-testimonials-shape-perception-and-trust-for-2024/"><u>[New] How Video Testimonials Shape Perception and Trust for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-achieving-excellence-in-work-and-online-content/"><u>[New] In 2024, Achieving Excellence in Work and Online Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-high-paying-creator-status-on-youtube/"><u>[Updated] In 2024, High-Paying Creator Status on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commanding-your-computer-to-rest-when-not-in-use/"><u>Commanding Your Computer to Rest When Not In Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/connectivity-through-time-leveraging-windows-7-for-windows-11-activation/"><u>Connectivity Through Time: Leveraging Windows 7 for Windows 11 Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-false-listings-of-devices-in-windows-error-logs/"><u>Correcting False Listings of Devices in Windows Error Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-error-messages-with-windows-11-and-ms/"><u>Deciphering Error Messages with Windows 11 and MS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-risks-of-keygen-virus-and-windows-security-measures/"><u>Decoding the Risks of Keygen Virus & Windows Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-to-the-heart-of-recent-windows-use/"><u>Direct to the Heart of Recent Windows Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-into-windows-sound-system-architecture/"><u>Diving Into Windows' Sound System Architecture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-privilege-based-errors-in-system-installation/"><u>Easing Privilege-Based Errors in System Installation</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/effortless-techniques-for-streamlined-ipad-video-recording/"><u>Effortless Techniques for Streamlined iPad Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-reading-experience-in-windows-11-notepad/"><u>Elevate Reading Experience in Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-creativity-with-these-8-premium-video-cutters-for-windows/"><u>Enhance Creativity with These 8 Premium Video Cutters for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-unleash-virtualization-power-win11/"><u>Essential Steps to Unleash Virtualization Power Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-masking-language-indicator-on-win11/"><u>Expert Guide to Masking Language Indicator on Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-no-device-found-error-on-your-computer-a-step-by-step-guide/"><u>Fixing 'No Device Found' Error on Your Computer - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-precursor-pcs-to-progressive-windows-11-platforms/"><u>From Precursor PCs to Progressive Windows 11 Platforms</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-12-without-passcode-drfone-by-drfone-ios/"><u>How to Unlock iPhone 12 Without Passcode? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-breeze-through-snapchat-two-techniques-for-dynamic-lenses/"><u>In 2024, Breeze Through Snapchat  Two Techniques for Dynamic Lenses</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-the-fading-technique-on-soundtracks-in-audacity/"><u>In 2024, Mastering the Fading Technique on Soundtracks in Audacity</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-experts-approach-to-inserting-subtitlescc-on-youtube-videos/"><u>In 2024, The Expert's Approach to Inserting Subtitles/CC on YouTube Videos</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-vivo-t2-pro-5g-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Vivo T2 Pro 5G Device</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-thermaltake-massive-tm-laptop-cooler-assessment-features-vs-cost/"><u>In-Depth Thermaltake Massive TM Laptop Cooler Assessment - Features Vs. Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-win-plus-p-not-working-on-windows-heres-how-to-fix-it/"><u>Is Win + P Not Working on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-phones-as-windows-microphones/"><u>Leveraging Phones as Windows Microphones</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-art-of-windows-11-driver-updates-with-revouninstaller/"><u>Master the Art of Windows 11 Driver Updates with RevoUninstaller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-windows-update-self-replacing-amd-graphics-drivers/"><u>Master Windows Update: Self-Replacing AMD Graphics Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-compression-techniques-for-disk-optimization/"><u>Mastering File Compression Techniques for Disk Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/naming-conventions-editing-windows-11-user-folders/"><u>Naming Conventions: Editing Windows 11 User Folders</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-zoom-meetings-on-windows-10-for-2024/"><u>Navigating Zoom Meetings on Windows 10 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/on-premise-self-hosted-gpt-the-windows-path-via-gpt4all/"><u>On-Premise, Self-Hosted GPT: The Windows Path via GPT4All.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-installer-efficiency/"><u>Optimizing Windows Installer Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-hurdles-in-accessing-network-router/"><u>Overcoming Hurdles in Accessing Network Router</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professional-procrastination-buster-top-windows-productivity-hacks/"><u>Professional Procrastination Buster: Top Windows Productivity Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-a-seamless-search-experience-in-windows-11-tm/"><u>Re-Establishing a Seamless Search Experience in Windows 11 TM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-edge-browser-setting-up-microsofts-defender-application-guard-in-win-11/"><u>Secure Edge Browser: Setting up Microsoft's Defender Application Guard in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-stop-non-data-transfer-from-usb-ports-on-pc/"><u>Solutions to Stop Non-Data Transfer From USB Ports on PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-coredll-cannot-be-found-problem-a-step-by-step-guide/"><u>Solving the 'Core.dll Cannot Be Found' Problem: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/srt-to-txt-mastery-the-2023-guide-for-rapid-changeover-for-2024/"><u>SRT to TXT Mastery  The 2023 Guide for Rapid Changeover for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-entry-into-windows-startup-hub/"><u>Stepwise Entry Into Windows Startup Hub</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-ultimate-alternative-review-to-sharex/"><u>The Ultimate Alternative Review to ShareX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-the-self-opens-issue-with-msdnstore/"><u>Troubleshooting the Self-Opens Issue with MSDN/Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-files-in-windows-no-more-read-only-limit/"><u>Unlocking Files in Windows: No More Read-Only Limit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-issues-from-a-recent-windows-system-upgrade/"><u>Unraveling Issues From a Recent Windows System Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-window-icon-location-techniques/"><u>Unveiling Window Icon Location Techniques</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-countdown-made-easy-a-3-step-guide-for-fcpx-users/"><u>Updated 2024 Approved Countdown Made Easy A 3-Step Guide for FCPX Users</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrade-sound-precision-fresh-scarlett-6i6-driver-guide/"><u>Upgrade Sound Precision: Fresh Scarlett 6I6 Driver Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-efficiency-boost-crafting-uwp-app-shortcuts/"><u>Windows 11 Efficiency Boost: Crafting UWP App Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-harmony-restored-5-solutions-to-glitches/"><u>Windows Harmony Restored: 5 Solutions to Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-game-restoring-ps4-input-link-to-stability-on-computer/"><u>Winning Back Your Game: Restoring PS4 Input Link to Stability on Computer</u></a></li>
</ul></div>
