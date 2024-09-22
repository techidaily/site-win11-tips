---
title: Disable Unwanted Features to Lower Memory Usage
date: 2024-09-16T19:15:43.294Z
updated: 2024-09-21T16:34:53.344Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Unwanted Features to Lower Memory Usage
excerpt: This Article Describes Disable Unwanted Features to Lower Memory Usage
keywords: Reduce Memory Waste,Disable Extras for Saving,Optimize Memory Use,Cut Unneeded Resource Usage,Minimize System Load,Lower Device RAM Demand,Efficient App Settings
thumbnail: https://thmb.techidaily.com/d0ab1cb7b8b22999ef087a383ed3db769492e1f7dd341f7046ddf8ecb2ad394e.png
---

## Disable Unwanted Features to Lower Memory Usage

 If you’ve kept a close eye on the Task Manager, then you may have noticed the Antimalware Service Executable doing its job. It is a crucial process of Windows Security (previously "Microsoft Defender") and helps keep your system safe from malware. It is pretty common to disable the Antimalware Service Executable because it consumes a large chunk of the system resources.

 On older PCs with limited system resources, the Antimalware Service Executable can severely impact the performance of your system. Read on as we discuss the importance of this service and how you can disable it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Antimalware Service Executable?

 You’re probably familiar with Windows Security (previously Microsoft Defender). Windows Security is a reliable antivirus that comes pre-installed on Windows 10 and 11\. The Antimalware Service Executable (you may find it listed as**MsMpEng.exe** in the**Task Manager**) is a core part of Windows Security.

 The service helps ensure your PC stays protected against any virus, worms, and other malware by continually scanning files and programs on your PC in the background. If the Antimalware Service Executable finds a malicious file or program, it will immediately delete or quarantine the affected files.

## Should You Disable the Antimalware Service Executable?

 Considering how integral the Antimalware Service Executable is to protect your PC, you must be wondering why you should even consider disabling it.

 If you do not have a third-party antivirus installed on your system, then Windows Security is your sole protection against potentially harmful malware. If your PC is left without any third-party antivirus programs installed, the Antimalware Service Executable automatically enables itself and begins safeguarding your PC as part of Windows Security.

 Ideally, you should not turn off the Antimalware Service Executable process. But if you have a reliable third-party antivirus installed, and the Antimalware Service Executable is still consuming a large chunk of your RAM or CPU, then it might make sense to disable it.

## How to Disable the Antimalware Service Executable

 There are a few different ways you can disable the Antimalware Service Executable depending on the circumstances of your system’s performance.

### Method 1: Disable Real-time Protection

 Suppose you find the Antimalware Service Executable process consuming a lot of system resources in certain instances; in that case, you can temporarily disable[real-time](https://www.makeuseof.com/real-time-protection/) malware protection through Windows Security:

1. Head to the**Start** menu, search for**Windows Security** and select the Best match.
2. Navigate to**Virus & threat protection** from the sidebar.
3. Look for**Virus & threat protection settings** , and then click on**Manage settings** option underneath.  
![real time protection windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/real-time-protection.jpg)
4. Disable the**Real-time protection** toggle button by bringing it to the**Off** position.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Real-time protection will be turned back on automatically by Windows Security.

### Method 2: Turn Off Antimalware Service Executable Through Windows Security in the Registry Editor

 For users looking for a more permanent solution to disabling the Antimalware Service Executable, you will have to[disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) from the Registry Editor.

 If you do not have a third-party antivirus installed, disabling Windows Security will leave your system at risk of malicious malware that can damage it.

To disable Antimalware Service Executable from the Registry Editor:

1. Search for**Registry Editor** from the**Start** menu, and launch it.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows Defender** from the sidebar.
3. Right-click on the**Windows Defender** folder and select**New > DWORD (32-bit) Value** .  
![regedit windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/regedit-windows-defender.jpg)
4. Enter**DisableAntiSpyware** in the**Value name** field and**1** in the**Value data** field.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Press**OK** to save your changes and restart your system for the changes to take effect.

## Should You Rely on Windows Security for Windows 10 and 11?

 Many users opt for a dedicated third-party antivirus on Windows 10 or 11, but Windows Security has made significant improvements in the past few years. Not only is Windows Security a complete antivirus package, but it's also free and comes pre-installed on Windows.

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
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-best-8-youtube-marketing-apps-and-solutions/"><u>[Updated] 2024 Approved Best 8 YouTube Marketing Apps & Solutions</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-online-beat-detectors-you-should-try-now-online-and-free/"><u>[Updated] 2024 Approved Online Beat Detectors You Should Try Now [Online & Free]</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-top-30-whatsapp-biographies-for-every-astrology-follower/"><u>2024 Approved Top 30 WhatsApp Biographies for Every Astrology Follower</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-honor-90-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Honor 90 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-teammers-frustrations-quickly/"><u>Ease Teammers' Frustrations, Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-app-youre-trying-to-install-isnt-a-microsoft-verified-app-warning-on-windows/"><u>How to Fix “The App You’re Trying to Install Isn’t a Microsoft-Verified App” Warning on Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-elevate-gaming-on-tv-obs-guide/"><u>In 2024, Elevate Gaming on TV - OBS Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, What are Location Permissions Life360 On Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-toolbar-usage-in-mspcm-for-windows-11/"><u>Mastering Toolbar Usage in MSPCM for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-vmware-boot-failures-with-8-proven-strategies-win11/"><u>Sidestep VMware Boot Failures with 8 Proven Strategies, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-economics-of-windows-11-for-microsoft/"><u>The Economics of Windows 11 for Microsoft</u></a></li>
<li><a href="https://some-tips.techidaily.com/tips-for-smooth-transitioning-from-zoom-to-fb-live-events-for-2024/"><u>Tips for Smooth Transitioning From ZOOM to FB Live Events for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-os-woes-quick-solutions-to-start-photoscape-immediately/"><u>Win OS Woes: Quick Solutions to Start Photoscape Immediately</u></a></li>
</ul></div>

