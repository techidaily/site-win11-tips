---
title: "Vigilance in Action: Key Windows Tasks to Scrutinize for Infection"
date: 2024-10-07T21:44:14.425Z
updated: 2024-10-08T20:01:20.814Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Vigilance in Action: Key Windows Tasks to Scrutinize for Infection"
excerpt: "This Article Describes Vigilance in Action: Key Windows Tasks to Scrutinize for Infection"
keywords: Vigilant Scanning,Key Task Check,Window Security,Infection Alert,Action Prevention,Risky Windows,Secure Computing
thumbnail: https://thmb.techidaily.com/f84b2c3b2f643243e9c367a28e725ddd1d16800a678efc068af4239160ee06bb.jpg
---

## Vigilance in Action: Key Windows Tasks to Scrutinize for Infection

 Processes are an unavoidable part of Windows, and it is not unusual to see dozens or hundreds of them in Task Manager. Each process is a program or part of a program that is running. Unfortunately, malware creators know this and are known to hide malicious software behind the names of legitimate processes.

 Here are some of the most commonly hijacked or duplicated processes, along with where they should be located and how to spot a malicious version.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Svchost.exe

 The Service Host, or svchost.exe, is a shared-service process. It allows various other Windows services to share processes. This helps to reduce resource usage, making the system more efficient. You will almost certainly see more than one instance of Svchost.exe in Task Manager, but this is normal. If one or more of these files are compromised by malware, you may notice a distinct reduction in performance.

![the svchost process in task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/svchost-process.jpg)

 The legitimate Svchost files should be found in**C:\\Windows\\System32** . If you suspect it has been hijacked, check**C:\\Windows\\Temp** . If you see svchost.exe here, it could be a malicious file. Scan the file with your antivirus software, and quarantine it if necessary.

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Explorer.exe

 Explorer.exe is responsible for the graphical shell. Without it, you would have no Taskbar, Start Menu, File Manager, or even the Desktop. Therefore, it is an essential part of Windows and cannot be disabled.

 Several viruses can use the Explorer.exe filename to hide behind, including trojan.w32.ZAPCHAST. The legitimate file will be in**C:\\Windows** . If you find it in**System32** , you should definitely check it with your antivirus software.

## 3\. Winlogon.exe

 The Winlogon.exe process is an essential part of the Windows OS. It handles things like loading the user profile during login and locking the computer when the screensaver runs. Unfortunately, because it handles security elements, Windows Logon and the winlogon.exe process are common targets for threats.

 Several Trojan viruses, including Vundo, can be hidden within or disguised as winlogon.exe. The usual location of the Winlogon.exe file is**C:\\Windows\\System32** . If you find it in**C:\\Windows\\WinSecurity** , it could be malicious. One good indication that the process has been hijacked is unusually high memory use.

 Viruses and malware don't just hide behind Windows processes. Here are some[other ways malware can go undetected and hide on your computer](https://www.makeuseof.com/can-malware-go-undetected-how-viruses-hide-from-you/) .

## 4\. Csrss.exe

 The Client/Server Run-Time Subsystem, or Csrss.exe, is an essential Windows process. Although it is not as widely used in modern Windows versions, it is still required by the system and cannot be disabled.

![The csrss process file in folder location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/csrss-process.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049388/7443" target="_top" id="2049388">
  <img src="//a.impactradius-go.com/display-ad/7443-2049388" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049388/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Nimda.E virus has been known to mimic the Csrss.exe process, although that is not the only potential threat. The legitimate file should be located in the**System32** or**SysWOW64** folders. Right-click on the Csrss.exe process in Task Manager and choose**Open File Location** . If it is located anywhere else, it is likely to be a malicious file.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Lsass.exe

 lsass.exe is an essential process responsible for the security policy on Windows. It verifies the login name and password, among other security procedures. It is unlikely that the process will be hijacked. If it isn't running correctly, you will usually be automatically logged out of your computer. But viruses are known to use the filename to hide.

 Look for the Lsass.exe file in**C:\\Windows\\System32** . This is the only place you should find it. If you see it in another location, such as**C:\\Windows\\system** or**C:\\Program Files** , act with suspicion and scan the file with your antivirus.

## 6\. Services.exe

 The Services.exe process is responsible for starting and stopping various essential Windows services. Like the other Windows processes in this list, viruses and malware target it because it allows them to hide in plain sight.

 If the file is hijacked, you may notice problems during the startup and shutdown of your PC. Look for the real Services.exe file in the**System32** folder. If it is located anywhere else, such as in**C:\\Windows\\ConnectionStatus** , the file could be a virus.

 The processes mentioned here are essential to the smooth running of Windows. But not all are, and many non-essential[processes can even be closed to help with performance](https://www.makeuseof.com/windows-processes-end-safely-performance/) .

## 7\. Spoolsv.exe

 The Windows Print Spooler Service, or Spoolsv.exe, is an important part of the printing interface. It runs in the background, waiting to manage things like the print queue when required. The process is not dependent on having a printer connected, so you shouldn't be surprised to see it in Task Manager.

![The spooler process in task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/spooler-process.jpg)

 Perhaps because Spoolsv.exe is easily overlooked, a virus can take the name to make itself seem legitimate. The true spools file can be found in**C:\\Windows\\System32** . The fake file will often appear in**C:\\Windows** , or in a user profile folder.

## How Do You Check if a Process Is Legitimate?

 The Task Manager is your friend when looking for suspicious activity. Infected processes will often behave erratically, consuming more CPU power and memory than is usual. But that isn't always the case, so here are some other ways to check a process is legitimate.

 Most of the essential processes listed here should only appear in the System32 folder. You can easily check the location of a suspicious file in the Task Manager. Right-click on the process and select**Open File Location** . Check the path of the folder that opens to ensure the file is in the correct place.

 Another way to tell if a file is legitimate is to check the size. Most of the .exe files of these essential processes will be under 200kb. Right-click on the process name in Task Manager, select**Properties** and look at the size. If it seems unusually large, take a closer look to determine if it is safe.

 You can also[check the certificate of the EXE file](https://www.makeuseof.com/windows-tell-if-exe-file-is-safe/) . An authentic file will have a security certificate issued by Microsoft. If you see anything else, it is likely to be malicious.

 The final thing to do is scan suspect files with an up-to-date antivirus scanner. Quarantine and remove any files that are flagged as infected. Fortunately, modern versions of Windows come with Microsoft Defender built-in, so learn[how to scan a single file or folder with Microsoft Defender](https://www.makeuseof.com/microsoft-defender-scan-file-folder/) to check any suspicious files you find.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-unraveling-tiktoks-veiled-prohibitive-measures/"><u>[New] 2024 Approved Unraveling TikTok's Veiled Prohibitive Measures</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-top-2023-ps3-emulators-for-enhanced-gaming-for-2024/"><u>[Updated] Top 2023 Ps3 Emulators for Enhanced Gaming for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-seamless-multilingual-input-adjusting-keyboard-layout-in-windows-11/"><u>Achieve Seamless Multilingual Input: Adjusting Keyboard Layout in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-online-conversion-change-bmp-images-to-tiff-format-with-ease/"><u>Free Online Conversion: Change BMP Images to TIFF Format with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstalling-microsoft-store-apps-on-windows-10-and-11/"><u>Guide to Reinstalling Microsoft Store Apps on Windows 10 & 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-on-your-apple-iphone-13-pro-max-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card on Your Apple iPhone 13 Pro Max Apple ID and Apple Pay</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Xiaomi Redmi Note 12 4G? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-unveil-tiktoks-most-effective-typefaces-for-video-growth-this-year/"><u>In 2024, Unveil TikTok's Most Effective Typefaces for Video Growth This Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sticky-notes-display-on-win-11/"><u>Mastering the Art of Sticky Notes Display on Win 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/melodicmeasurement-reaction-to-tunes-for-2024/"><u>MelodicMeasurement Reaction to Tunes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-keyboard-errors-for-functional-shortcuts-in-windows-11/"><u>Resolve: Keyboard Errors for Functional Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-ceasing-random-windows-key-activation/"><u>Strategies for Ceasing Random Windows Key Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-devices-on-the-frontline-top-5-ways-to-confirm-availability/"><u>Windows 11 Devices on the Frontline: Top 5 Ways to Confirm Availability</u></a></li>
</ul></div>

