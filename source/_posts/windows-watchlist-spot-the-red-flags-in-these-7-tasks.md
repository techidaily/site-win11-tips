---
title: "Windows Watchlist: Spot the Red Flags in These 7 Tasks"
date: 2024-08-16T01:32:03.649Z
updated: 2024-08-17T01:32:03.649Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Watchlist: Spot the Red Flags in These 7 Tasks"
excerpt: "This Article Describes Windows Watchlist: Spot the Red Flags in These 7 Tasks"
keywords: Red Flag Tasks Windows,Watchlist Windows Tips,Identify Risks Windows,Spotting Security Vulnerabilities,Windows Task Alerts,Detecting Threats in Windows,Recognizing Unsafe Windows Actions
thumbnail: https://thmb.techidaily.com/c4e970c61c745a22a93f179d1f650cdbb34448ec2a9158efa033c2403816542e.jpg
---

## Windows Watchlist: Spot the Red Flags in These 7 Tasks

 Processes are an unavoidable part of Windows, and it is not unusual to see dozens or hundreds of them in Task Manager. Each process is a program or part of a program that is running. Unfortunately, malware creators know this and are known to hide malicious software behind the names of legitimate processes.

 Here are some of the most commonly hijacked or duplicated processes, along with where they should be located and how to spot a malicious version.

## 1\. Svchost.exe

 The Service Host, or svchost.exe, is a shared-service process. It allows various other Windows services to share processes. This helps to reduce resource usage, making the system more efficient. You will almost certainly see more than one instance of Svchost.exe in Task Manager, but this is normal. If one or more of these files are compromised by malware, you may notice a distinct reduction in performance.

![the svchost process in task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/svchost-process.jpg)

 The legitimate Svchost files should be found in**C:\\Windows\\System32** . If you suspect it has been hijacked, check**C:\\Windows\\Temp** . If you see svchost.exe here, it could be a malicious file. Scan the file with your antivirus software, and quarantine it if necessary.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Explorer.exe

 Explorer.exe is responsible for the graphical shell. Without it, you would have no Taskbar, Start Menu, File Manager, or even the Desktop. Therefore, it is an essential part of Windows and cannot be disabled.

 Several viruses can use the Explorer.exe filename to hide behind, including trojan.w32.ZAPCHAST. The legitimate file will be in**C:\\Windows** . If you find it in**System32** , you should definitely check it with your antivirus software.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Winlogon.exe

 The Winlogon.exe process is an essential part of the Windows OS. It handles things like loading the user profile during login and locking the computer when the screensaver runs. Unfortunately, because it handles security elements, Windows Logon and the winlogon.exe process are common targets for threats.

 Several Trojan viruses, including Vundo, can be hidden within or disguised as winlogon.exe. The usual location of the Winlogon.exe file is**C:\\Windows\\System32** . If you find it in**C:\\Windows\\WinSecurity** , it could be malicious. One good indication that the process has been hijacked is unusually high memory use.

 Viruses and malware don't just hide behind Windows processes. Here are some [other ways malware can go undetected and hide on your computer](https://www.makeuseof.com/can-malware-go-undetected-how-viruses-hide-from-you/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Csrss.exe

 The Client/Server Run-Time Subsystem, or Csrss.exe, is an essential Windows process. Although it is not as widely used in modern Windows versions, it is still required by the system and cannot be disabled.

![The csrss process file in folder location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/csrss-process.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 The Nimda.E virus has been known to mimic the Csrss.exe process, although that is not the only potential threat. The legitimate file should be located in the**System32** or**SysWOW64** folders. Right-click on the Csrss.exe process in Task Manager and choose**Open File Location** . If it is located anywhere else, it is likely to be a malicious file.

## 5\. Lsass.exe

 lsass.exe is an essential process responsible for the security policy on Windows. It verifies the login name and password, among other security procedures. It is unlikely that the process will be hijacked. If it isn't running correctly, you will usually be automatically logged out of your computer. But viruses are known to use the filename to hide.

 Look for the Lsass.exe file in**C:\\Windows\\System32** . This is the only place you should find it. If you see it in another location, such as**C:\\Windows\\system** or**C:\\Program Files** , act with suspicion and scan the file with your antivirus.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Services.exe

 The Services.exe process is responsible for starting and stopping various essential Windows services. Like the other Windows processes in this list, viruses and malware target it because it allows them to hide in plain sight.

 If the file is hijacked, you may notice problems during the startup and shutdown of your PC. Look for the real Services.exe file in the**System32** folder. If it is located anywhere else, such as in**C:\\Windows\\ConnectionStatus** , the file could be a virus.

 The processes mentioned here are essential to the smooth running of Windows. But not all are, and many non-essential [processes can even be closed to help with performance](https://www.makeuseof.com/windows-processes-end-safely-performance/) .

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 7\. Spoolsv.exe

 The Windows Print Spooler Service, or Spoolsv.exe, is an important part of the printing interface. It runs in the background, waiting to manage things like the print queue when required. The process is not dependent on having a printer connected, so you shouldn't be surprised to see it in Task Manager.

![The spooler process in task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/spooler-process.jpg)

 Perhaps because Spoolsv.exe is easily overlooked, a virus can take the name to make itself seem legitimate. The true spools file can be found in**C:\\Windows\\System32** . The fake file will often appear in**C:\\Windows** , or in a user profile folder.

## How Do You Check if a Process Is Legitimate?

 The Task Manager is your friend when looking for suspicious activity. Infected processes will often behave erratically, consuming more CPU power and memory than is usual. But that isn't always the case, so here are some other ways to check a process is legitimate.

 Most of the essential processes listed here should only appear in the System32 folder. You can easily check the location of a suspicious file in the Task Manager. Right-click on the process and select**Open File Location** . Check the path of the folder that opens to ensure the file is in the correct place.

 Another way to tell if a file is legitimate is to check the size. Most of the .exe files of these essential processes will be under 200kb. Right-click on the process name in Task Manager, select**Properties** and look at the size. If it seems unusually large, take a closer look to determine if it is safe.

 You can also [check the certificate of the EXE file](https://www.makeuseof.com/windows-tell-if-exe-file-is-safe/) . An authentic file will have a security certificate issued by Microsoft. If you see anything else, it is likely to be malicious.

 The final thing to do is scan suspect files with an up-to-date antivirus scanner. Quarantine and remove any files that are flagged as infected. Fortunately, modern versions of Windows come with Microsoft Defender built-in, so learn [how to scan a single file or folder with Microsoft Defender](https://www.makeuseof.com/microsoft-defender-scan-file-folder/) to check any suspicious files you find.

## The Windows Processes That Might Be Hiding a Virus

 Part of keeping your Windows PC safe from malware and viruses is knowing where they hide. Sometimes a malicious file will behave oddly, using too much CPU and memory. But not always. So spotting a suspicious file in other ways is a useful skill.


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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-navigate-to-the-premier-android-tools-for-ps2-games/"><u>[New] In 2024, Navigate to the Premier Android Tools for PS2 Games</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-unlocking-the-secrets-of-instagrams-trending-reels/"><u>[Updated] 2024 Approved  Unlocking the Secrets of Instagram's Trending Reels</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-how-to-relive-facebooks-yesteryears-instructions-for-digital-devices/"><u>[Updated] In 2024, How to Relive Facebook's Yesteryears - Instructions for Digital Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-audio-visual-synchronization-for-streams/"><u>2024 Approved  Mastering Audio-Visual Synchronization for Streams</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-mastering-headline-economy-utilizing-slug-lines-smartly/"><u>2024 Approved  Mastering Headline Economy  Utilizing Slug Lines Smartly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-warning-indicators-that-call-for-a-full-reboot/"><u>5 Warning Indicators That Call For a Full Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-office-365-issue-code-30015-26/"><u>Correcting Office 365 Issue: Code 30015-26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disable-default-settings-keep-your-usb-running-on-windows-11/"><u>Disable Default Settings - Keep Your USB Running on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-webp-visualization-with-these-excellent-tools/"><u>Enhance WebP Visualization with These Excellent Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-digital-desktop-with-engaging-time-themed-screensavers-using-these-5-tools/"><u>Enhance Your Digital Desktop with Engaging Time-Themed Screensavers Using These 5 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-finest-windows-11-drawers-here/"><u>Explore the Finest Windows 11 Drawers Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-move-and-copy-to-folder-context-menu-options-in-windows-11-and-11/"><u>How to Add a Move and Copy to Folder Context Menu Options in Windows 11 & 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/how-to-amplify-your-online-presence-with-google-meets-aesthetic-tools-for-2024/"><u>How to Amplify Your Online Presence with Google Meet's Aesthetic Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-bluetooth-pin-verification-hitch-on-win11w10-pcs/"><u>How To Fix Bluetooth PIN Verification Hitch on Win11/W10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-increase-the-performance-of-android-studio-on-windows/"><u>How to Increase the Performance of Android Studio on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-asus-rog-phone-8-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Asus ROG Phone 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-unopened-sharing-error-on-w10w11/"><u>How to Rectify Unopened Sharing Error on W10/W11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-magic-6-pro-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Magic 6 Pro using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/impact-analysis-removal-of-windows-11-taskbars-chatting-function/"><u>Impact Analysis: Removal of Windows 11 Taskbar's Chatting Function</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-oppo-find-x6-pro-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Oppo Find X6 Pro to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-chorus-chronicles-new-speaker-insights/"><u>In 2024, Chorus Chronicles  New Speaker Insights</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-honor-100-pro-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Honor 100 Pro? Try These Fixes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-tecno-pova-5-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Tecno Pova 5 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-professional-streaming-the-premier-6-zoom-webcam-picks/"><u>In 2024, Professional Streaming  The Premier #6 Zoom Webcam Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-how-to-optimize-windows-11-settings/"><u>Master Your Machine: How to Optimize Windows 11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-classic-diablo-a-beginners-guide/"><u>Mastering Classic Diablo: A Beginner's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-uninstall-quickly-in-windows-11/"><u>Navigating to Uninstall Quickly in Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcome-icloud-connection-issues-with-these-proven-fixes/"><u>Overcome iCloud Connection Issues with These Proven Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-signed-file-barrier-for-system-upgrades/"><u>Overcoming Non-Signed File Barrier for System Upgrades</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pioneering-websites-for-modern-letterforms/"><u>Pioneering Websites for Modern Letterforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-languages-change-navigating-hotkeys-in-windows-11-and-11-pro/"><u>Quick Languages Change: Navigating Hotkeys in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successful-drive-fix-amd-detection-driver-for-windows-10/"><u>Successful Drive Fix: AMD Detection Driver for Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-up-with-microsoft-sql-on-malwarebytes-after-disconnect/"><u>Syncing Up with Microsoft SQL on Malwarebytes After Disconnect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-mystery-of-win11s-disconnected-5g-wi-fi/"><u>Tackling the Mystery of Win11's Disconnected 5G Wi-Fi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-synchronized-note-taking-in-windows-11/"><u>The Art of Synchronized Note-Taking in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-policy-editor-in-windows-11/"><u>Unlock the Full Potential of Policy Editor in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-system-details-locate-windows-ip-and-mac-via-powershell/"><u>Unveiling System Details: Locate Windows' IP and MAC via Powershell</u></a></li>
</ul></div>
