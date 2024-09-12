---
title: Step-by-Step Process for Running SFC on Windows PCs
date: 2024-09-11T01:20:47.252Z
updated: 2024-09-12T01:20:47.252Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Process for Running SFC on Windows PCs
excerpt: This Article Describes Step-by-Step Process for Running SFC on Windows PCs
keywords: Run SFC Command Windows,Execute System File Check,Windows SFC Verification,Perform SFC Scan Windows,SFC Diagnostic Tool PCs,Fix System Files Windows,System File Integrity Check Windows
thumbnail: https://thmb.techidaily.com/fc45e4935b2783be1c5dc416a8cddc7dff02a0dd6e0a55facead0cef258b81de.jpg
---

## Step-by-Step Process for Running SFC on Windows PCs

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





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."





<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2123472/16836" target="_top" id="2123472">
  <img src="//a.impactradius-go.com/display-ad/16836-2123472" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123472/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by[creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123469/16836" target="_top" id="2123469">
  <img src="//a.impactradius-go.com/display-ad/16836-2123469" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123469/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-craft-a-richer-user-experience-in-windows-photos-with-music-and-aesthetic-filters/"><u>[New] 2024 Approved Craft a Richer User Experience in Windows Photos with Music and Aesthetic Filters</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-from-novice-to-proficient-the-path-with-zoom-webinars/"><u>[New] From Novice to Proficient The Path with Zoom Webinars</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-gear-up-for-greatness-choosing-webcams-for-youtube-excellence-for-2024/"><u>[New] Gear Up for Greatness Choosing Webcams for YouTube Excellence for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-screen-recorder-showdown-features-and-prices-compared-for-2024/"><u>[New] Screen Recorder Showdown Features and Prices Compared for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-securely-shutting-down-your-instagram-presence-forever/"><u>[Updated] Securely Shutting Down Your Instagram Presence Forever</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-unleashing-the-power-of-whiteboards-on-zoom-platforms-across-multiple-devices/"><u>[Updated] Unleashing the Power of Whiteboards on Zoom Platforms Across Multiple Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-windows-error-code-0xc00000f/"><u>Decoding and Correcting Windows Error Code: 0Xc00000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-your-dormant-data-windows-storage-visualization-tactics/"><u>Discover Your Dormant Data: Windows Storage Visualization Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-fix-disk-read-error-in-windows/"><u>Essential Guide to Fix Disk Read Error in Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/experience-unforgettable-co-op-gameplay-in-dying-light-an-intense-first-person-survival-adventure/"><u>Experience Unforgettable Co-Op Gameplay in Dying Light - An Intense First-Person Survival Adventure</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-take-on-huawei-p20-pro-outstanding-camera-capabilities-in-an-excellent-device/"><u>Expert Take on Huawei P20 Pro: Outstanding Camera Capabilities in an Excellent Device</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-poco-f5-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-familiar-with-your-mouse-guide-to-windows-11-propets/"><u>Get Familiar with Your Mouse: Guide to Windows 11 Propets</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-m34-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy M34 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-world-of-warcrafts-fatal-exception-error-132-in-windows-1011/"><u>How to Fix World of Warcraft’s Fatal Exception Error 132 in Windows 10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-itel-a60s-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on Itel A60s</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-tecno-spark-10c-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Tecno Spark 10C Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-the-0x80071a90-windows-problem/"><u>How to Solve the 0X80071a90 Windows Problem</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-decipher-the-best-video-tracker-tools-for-high-impact-results/"><u>In 2024, Decipher the Best Video Tracker Tools for High-Impact Results</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-iphone-7-plus-by-drfone-ios/"><u>In 2024, The Easy Way to Remove an Apple ID from Your MacBook For your iPhone 7 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/internet-inequity-fix-your-windows-slowdown-now/"><u>Internet Inequity: Fix Your Windows Slowdown Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-insider-beta-features-hidden/"><u>Keeping Insider Beta Features Hidden</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-device-awareness-in-power-mode-slumber/"><u>Leveraging Device Awareness in Power Mode Slumber</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-techniques-distinguishing-between-storage-disks-on-windows/"><u>Masterful Techniques: Distinguishing Between Storage Disks on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-periscope-a-comprehensive-tutorial/"><u>Mastering Periscope A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-anomaly-zero-error-correction-guide/"><u>Microsoft Store Anomaly: Zero-Error Correction Guide</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-2024-approved-voice-translation-english-to-bangla-online-and-offline-apps/"><u>New 2024 Approved Voice Translation English to Bangla Online and Offline Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-peeky-tabs-strategies-for-edge-on-w11/"><u>No Peeky Tabs: Strategies for Edge on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-to-the-next-level-with-collective-folder-formation/"><u>Propel Productivity to the Next Level with Collective Folder Formation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-file-images-in-windows-11-the-how-to-guide/"><u>Reinstating File Images in Windows 11 – The How-To Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-grayed-out-secure-boot-on-windows-bios-settings/"><u>Restoring Grayed-Out Secure Boot on Windows BIOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-the-driver-verifier-application-on-windows-11/"><u>Starting the Driver Verifier Application on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-recover-non-identified-wireless-networks-in-win11/"><u>Strategies to Recover Non-Identified Wireless Networks in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-unearth-windows-policy-rules/"><u>Strategies to Unearth Windows Policy Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switch-off-windows-record-of-launches/"><u>Switch Off Windows Record of Launches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-cursor-for-a-unique-visual-identity/"><u>Tailoring Your Cursor for a Unique Visual Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-imperative-of-routine-windows-file-protection/"><u>The Imperative of Routine Windows File Protection</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/things-you-must-know-for-screen-mirroring-apple-iphone-xr-drfone-by-drfone-ios/"><u>Things You Must Know for Screen Mirroring Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-application-switching-aids-mac-to-windows-migration-made-easy/"><u>Top 5 Application Switching Aids: Mac-to-Windows Migration Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-failed-ms-pc-manager-install-on-windows/"><u>Troubleshoot: Failed MS PC Manager Install on Windows?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-on-iphone-12-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide on iPhone 12 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-with-dolby-atmos-audio/"><u>Upgrade Your Windows 11 with Dolby Atmos Audio</u></a></li>
</ul></div>
