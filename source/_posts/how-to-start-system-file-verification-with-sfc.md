---
title: How to Start System File Verification with SFC
date: 2024-08-16T01:38:34.831Z
updated: 2024-08-17T01:38:34.831Z
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
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
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

## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by [creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-first-footage-assessment-breakdown/"><u>[New] In 2024, First Footage Assessment Breakdown</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-mastering-the-art-of-capturing-sims-4-essential-techniques-unveiled/"><u>[Updated] 2024 Approved  Mastering the Art of Capturing Sims 4 – Essential Techniques Unveiled</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-cutting-edge-science-education-through-yt-channels-for-2024/"><u>[Updated] Cutting Edge Science Education Through YT Channels for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-exclusive-sneak-peek-at-apples-finest-facebook-video-extractor-apps/"><u>[Updated] In 2024, Exclusive Sneak Peek at Apple's Finest Facebook Video Extractor Apps</u></a></li>
<li><a href="https://buynow-help.techidaily.com/1723063455954-bikers-vs-zombies-an-exciting-journey-in-days-gone/"><u>Bikers Vs. Zombies - An Exciting Journey in Days Gone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-dns-cache-via-steam-settings/"><u>Clearing Windows DNS Cache via Steam Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compute-disk-space-efficiently-via-powershell-commands/"><u>Compute Disk Space Efficiently via PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-copy-pasting-malfunction/"><u>Corrective Measures for Copy-Pasting Malfunction</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Nokia C300? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-audio-recording-the-windows-11-handbook/"><u>Easy Audio Recording: The Windows 11 Handbook</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/effective-solutions-for-internal-power-malfunction-in-windows-10-devices/"><u>Effective Solutions for Internal Power Malfunction in Windows 10 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-secure-data-movement-in-microsoft-edge-shield-for-w11/"><u>Enabling Secure Data Movement in Microsoft Edge Shield for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-archived-media-madvr-for-windows-enthusiasts/"><u>Enhance Archived Media: MadVR for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-computer-functionality-post-intel-hardware-violation/"><u>Enhancing Computer Functionality Post-Intel Hardware Violation</u></a></li>
<li><a href="https://program-issues.techidaily.com/essential-fixes-for-a-smooth-among-us-voice-chat-experience-on-windows-computers/"><u>Essential Fixes for a Smooth Among Us Voice Chat Experience on Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tactics-to-eliminate-isdonedll-errors/"><u>Expert Tactics to Eliminate ISDone.dll Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disk-read-windows-error-immediately/"><u>Fixing 'Disk Read' Windows Error Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-empty-folder-alerts-for-windows-users/"><u>Fixing Empty Folder Alerts for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-turn-off-microsofts-voice-assistant/"><u>Guide to Turn Off Microsoft's Voice Assistant</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-forbidden-you-dont-have-permission-to-access-on-this-server-error-on-windows/"><u>How to Fix the “Forbidden: You Don’t Have Permission to Access / On This Server” Error on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-seamless-video-text-illusion-with-free-tools/"><u>In 2024, Seamless Video Text Illusion with Free Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-spool-service-relaunch/"><u>Instant Spool Service Relaunch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-logic-how-to-quickly-examine-ethernet-performance/"><u>Latency Logic: How to Quickly Examine Ethernet Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-system-security-turning-on-controlled-access-in-windows-11/"><u>Mastering System Security: Turning On Controlled Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-directory-management-without-renaming-feature-in-win-11/"><u>Mastering the Art of Directory Management without Renaming Feature in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-pin-gallery-space-in-windows-11/"><u>Maximize Your Pin Gallery Space in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-playtime-configuring-amd-card-in-windows-games/"><u>Perfecting Playtime: Configuring AMD Card in Windows Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powerful-scripts-to-detect-pcs-ip-and-mac/"><u>Powerful Scripts to Detect PC's IP and MAC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-lost-steam-connections-on-pc/"><u>Quick Fixes for Lost Steam Connections on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-reds-greens-and-blues-avoiding-windows-color-confusion/"><u>Resolving Reds, Greens & Blues: Avoiding Windows' Color Confusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-sync-path-for-android-plus-windows-duo/"><u>Step-by-Step Sync Path for Android + Windows Duo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-chrome-freeze-in-windows/"><u>Steps to Overcome Chrome Freeze in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-windows-alt-key-problems/"><u>Strategies to Correct Windows ALT Key Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-temporary-file-extraction-in-windows-os/"><u>Streamlining Temporary File Extraction in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-addressing-faulty-or-missing-device-alerts-win1011/"><u>Tips for Addressing Faulty or Missing Device Alerts, Win10/11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-10-budget-friendly-mmorpg-experiences/"><u>Top 10 Budget-Friendly MMORPG Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-20-essential-cmd-tricks-for-beginners/"><u>Top 20 Essential CMD Tricks for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-documents-innovative-text-edits-with-snipt-tool/"><u>Transform Your Documents: Innovative Text Edits with Snipt Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-gaming-mastering-playstation-1-titles-on-win-with-duckstations-tips/"><u>Transform Your Gaming: Mastering PlayStation 1 Titles on WIN with Duckstation's Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-a-faulty-windows-enter-keysystem/"><u>Troubleshooting a Faulty Windows 'Enter' Keysystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-from-thx-spatial-issues/"><u>Unblocking Windows From THX Spatial Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-network-potential-through-dns-on-windows-11/"><u>Unlocking Network Potential Through DNS on Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-mystery-teslas-upcoming-phone-with-speculative-price-points-and-rumored-specifications/"><u>Unveiling the Mystery: Tesla's Upcoming Phone with Speculative Price Points and Rumored Specifications</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unwinding-upside-down-asmr-to-support-zzzs-for-2024/"><u>Unwinding Upside-Down  ASMR to Support Zzz's for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-nas-on-smartphones-and-tablets/"><u>Utilizing NAS on Smartphones and Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1110-resolving-code-xc0000142-failure/"><u>Windows 11/10: Resolving Code XC0000142 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-folder-confluence-techniques-for-users/"><u>Windows Folder Confluence: Techniques for Users</u></a></li>
</ul></div>
