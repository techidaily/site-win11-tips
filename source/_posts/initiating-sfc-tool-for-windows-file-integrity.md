---
title: Initiating SFC Tool for Windows File Integrity
date: 2024-10-29T19:47:46.827Z
updated: 2024-11-01T17:10:49.508Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Initiating SFC Tool for Windows File Integrity
excerpt: This Article Describes Initiating SFC Tool for Windows File Integrity
keywords: Windows SFC Integrity Check,File Integrity Verification Windows,SFC Scan in Windows OS,Secure File Tools Windows,Windows File Security Tool,Protect Files with SFC Windows,Enhancing Windows File Integrity
thumbnail: https://thmb.techidaily.com/b65bf539ad3bc7b67798ef76b0171c5880f30454ab3ea8bd7a6f0e0d486378c6.jpg
---

## Initiating SFC Tool for Windows File Integrity

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105882/7443" target="_top" id="2105882">
  <img src="//a.impactradius-go.com/display-ad/7443-2105882" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105882/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2016129/19272" target="_top" id="2016129">
  <img src="//a.impactradius-go.com/display-ad/19272-2016129" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016129/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-invaluable-resource-for-zero-cost-video-and-photo-providers/"><u>[New] 2024 Approved Invaluable Resource for Zero-Cost Video and Photo Providers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-add-narration-and-voiceovers-to-your-video/"><u>[New] How to Add Narration and Voiceovers to Your Video</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://win-tips.techidaily.com/asus-vivobookasusf910/"><u>ASUS Vivobookのリカバリモードでシステム復元手順：ASUS回復キーF9使用【ウィンドゥ10】</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-red-x-symbols-in-computer-file-systems/"><u>Demystifying Red “X” Symbols in Computer File Systems</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-updated-drivers-for-amd-rx-6700-xt-on-windows-11-10-and-7-platforms/"><u>Download Updated Drivers for AMD RX ‌6700 XT on Windows 11, 10 and 7 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-a-head-start-at-gameplay-with-winning-tactics-fc-style/"><u>Get a Head Start at Gameplay with Winning Tactics, FC Style</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ghostly-replay-techniques-for-editors/"><u>Ghostly Replay Techniques for Editors</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-error-code-0x800705b4-fixes-for-seamless-windows-11-updates/"><u>Mastering Error Code 0X800705b4 Fixes for Seamless Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-next-leap-after-cortana/"><u>Microsoft's Next Leap After Cortana</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-your-non-responsive-windows-digital-scribe/"><u>Reigniting Your Non-Responsive Windows Digital Scribe</u></a></li>
<li><a href="https://extra-tips.techidaily.com/simplify-screenplay-to-film-use-windows-movie-maker-win11/"><u>Simplify Screenplay to Film Use Windows Movie Maker (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-try-connection-bluetooth-misfire/"><u>Swift Solution to 'Try Connection' Bluetooth Misfire</u></a></li>
</ul></div>

