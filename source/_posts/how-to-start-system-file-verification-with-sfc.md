---
title: How to Start System File Verification with SFC
date: 2024-07-12T17:28:43.133Z
updated: 2024-07-13T17:28:43.133Z
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
<li><a href="https://fox-info.techidaily.com/2024-approved-essential-drawing-suites-on-windows-zero-to-high-pricing/"><u>2024 Approved  Essential Drawing Suites on Windows  Zero to High Pricing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-ineffective-windowed-discord-searches/"><u>Solutions for Ineffective Windowed Discord Searches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-smooth-windows-11-display-transitions/"><u>Steps for Smooth Windows 11 Display Transitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-inaccessible-folder-issue-fix-steps-for-windows-based-pcs/"><u>Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-seamlessly-saving-your-screen-premium-choices-on-pc-and-mac-for-2024/"><u>[Updated] Seamlessly Saving Your Screen  Premium Choices on PC & Mac for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-service-setups-for-an-immaculate-windows-11-launch-experience/"><u>Mastering Service Setups for an Immaculate Windows 11 Launch Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-personalized-window-pin-creation/"><u>The Ultimate Guide to Personalized Window PIN Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-fingerprint-scanner-compatibility-problem-in-windows/"><u>Solving Fingerprint Scanner Compatibility Problem in Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-ultimate-tips-adobe-presenter-video-recording/"><u>2024 Approved  Ultimate Tips  Adobe Presenter Video Recording</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-definitive-guide-to-flawless-morphvox-technique-for-2024/"><u>The Definitive Guide to Flawless MorphVOX Technique for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-social-media-connections-instagram-and-tiktok/"><u>[New] Mastering Social Media Connections  Instagram & TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-flaws-with-non-working-ccleaner-in-win1011/"><u>Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-pulse-picking-playlists-hot-tracks-for-viral-youtube-shorts/"><u>In 2024, Pulse-Picking Playlists  Hot Tracks for Viral YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-perplexity-of-non-existent-drive-letters-in-windows-systems/"><u>The Perplexity of Non-Existent Drive Letters in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-taskbar-dynamics-top-6-suggestions-for-windows-11-enhancement/"><u>Reimagining Taskbar Dynamics: Top 6 Suggestions for Windows 11 Enhancement</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unblemished-visuals-buying-high-quality-images/"><u>In 2024, Unblemished Visuals  Buying High-Quality Images</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-cultivating-a-thriving-business-model-with-snapchat-insights/"><u>2024 Approved  Cultivating a Thriving Business Model with Snapchat Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-discord-interface-fixing-a-dormant-overlay/"><u>Reclaim Your Discord Interface: Fixing a Dormant Overlay</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-meizu-21-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Meizu 21.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-wsl-factor-in-the-linux-desktop-landscape/"><u>The WSL Factor in the Linux Desktop Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-reinstalling-microsofts-mspm/"><u>Master the Art: Reinstalling Microsoft's MSPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-windows-iscsi-initiator-a-beginners-guide/"><u>Navigating the Windows iSCSI Initiator: A Beginner's Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/transform-footage-into-stunning-ig-images/"><u>Transform Footage Into Stunning IG Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-barricades-implement-these-7-windows-protections/"><u>Network Barricades: Implement These 7 Windows Protections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-music-librarys-mp3-files-to-windows-audible-cds-with-imgburn/"><u>Streamlining Your Music Library's MP3 Files to Windows' Audible CDs with ImgBurn</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-the-ultimate-pathway-for-redefining-your-tiktok-signature/"><u>[New] In 2024, The Ultimate Pathway for Redefining Your TikTok Signature</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/shotcut-review-is-it-the-best-free-video-editor/"><u>Shotcut Review – Is It The Best Free Video Editor?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-inactive-pc-device-engagement/"><u>Mastery of Inactive PC Device Engagement</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-the-best-of-the-best-free-vob-video-editing-software/"><u>Updated 2024 Approved The Best of the Best Free VOB Video Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-peaceful-sleep-windows-1011-automatic-shutdown/"><u>Securing Peaceful Sleep: Windows 10/11 Automatic Shutdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-iomap64-system-freezes-and-bsods/"><u>Overcoming Windows IOMap64 System Freezes and BSODs</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-unbranded-video-combining-7-best-software-options/"><u>Updated 2024 Approved Unbranded Video Combining 7 Best Software Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-windows-free-software-your-safety-priority-list/"><u>Secure Windows Free Software: Your Safety Priority List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-discord-setup-failures-on-windows-1011/"><u>Mastery Over Discord Setup Failures on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-password-management-on-windows-systems/"><u>Repairing Password Management on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-winning-transforming-your-pc-into-a-powerhouse-for-ps1-gaming/"><u>The Key to Winning: Transforming Your PC Into a Powerhouse for PS1 Gaming</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/avoid-oversaturated-greenscreen-effective-strategies-for-mac-editors-for-2024/"><u>Avoid Oversaturated Greenscreen  Effective Strategies for Mac Editors for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-final-goodbye-to-youtubes-minis-a-step-by-step-process/"><u>[Updated] Final Goodbye to YouTube's Minis  A Step-by-Step Process</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-smooth-operator-top-free-video-stabilizers-reviewed/"><u>Updated In 2024, Smooth Operator Top Free Video Stabilizers Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-control-in-action-modifying-software-size-on-windows-11/"><u>Keyboard Control in Action: Modifying Software Size on Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-concluding-your-digital-footprint-with-linkedins-deactivation-process/"><u>[Updated] Concluding Your Digital Footprint with LinkedIn's Deactivation Process</u></a></li>
</ul></div>
