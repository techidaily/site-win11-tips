---
title: Too Much Memory Used by Antivirus? How to Manage
date: 2024-10-27T18:04:03.982Z
updated: 2024-11-01T19:50:17.098Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Too Much Memory Used by Antivirus? How to Manage
excerpt: This Article Describes Too Much Memory Used by Antivirus? How to Manage
keywords: Antivirus Memory Usage,Manage Virus Memory,High Memory Alerts,Optimize AV Memory,Reduce Antivirus Load,Efficient Memory Use,Control Security Memory
thumbnail: https://thmb.techidaily.com/38a7a5c0a5123e7708eb11aa967d228491b39460885352e6b8c3f7846969574b.jpg
---

## Too Much Memory Used by Antivirus? How to Manage

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable the Antimalware Service Executable

 There are a few different ways you can disable the Antimalware Service Executable depending on the circumstances of your system’s performance.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Method 1: Disable Real-time Protection

 Suppose you find the Antimalware Service Executable process consuming a lot of system resources in certain instances; in that case, you can temporarily disable[real-time](https://www.makeuseof.com/real-time-protection/) malware protection through Windows Security:

1. Head to the**Start** menu, search for**Windows Security** and select the Best match.
2. Navigate to**Virus & threat protection** from the sidebar.
3. Look for**Virus & threat protection settings** , and then click on**Manage settings** option underneath.  
![real time protection windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/real-time-protection.jpg)
4. Disable the**Real-time protection** toggle button by bringing it to the**Off** position.

 Real-time protection will be turned back on automatically by Windows Security.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Method 2: Turn Off Antimalware Service Executable Through Windows Security in the Registry Editor

 For users looking for a more permanent solution to disabling the Antimalware Service Executable, you will have to[disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) from the Registry Editor.

 If you do not have a third-party antivirus installed, disabling Windows Security will leave your system at risk of malicious malware that can damage it.

To disable Antimalware Service Executable from the Registry Editor:

1. Search for**Registry Editor** from the**Start** menu, and launch it.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows Defender** from the sidebar.
3. Right-click on the**Windows Defender** folder and select**New > DWORD (32-bit) Value** .  
![regedit windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/regedit-windows-defender.jpg)
4. Enter**DisableAntiSpyware** in the**Value name** field and**1** in the**Value data** field.
5. Press**OK** to save your changes and restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://video-screen-grab.techidaily.com/new-elite-race-games-collection-guide/"><u>[New] Elite Race Games Collection Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-pioneering-screen-capture-methods-with-adobe-captivity-unveiled/"><u>[New] Pioneering Screen Capture Methods with Adobe Captivity Unveiled</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-cost-effective-filmmaking-5-top-free-video-tools/"><u>2024 Approved Cost-Effective Filmmaking 5 Top Free Video Tools</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-evaluation-of-the-elegoo-saturn-4-ultra-revolutionizing-resin-3d-printers/"><u>Comprehensive Evaluation of the Elegoo Saturn 4 Ultra - Revolutionizing Resin 3D Printers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-samsung-galaxy-a14-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Samsung Galaxy A14 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-how-to-effortlessly-access-and-apply-instagrams-best-filters/"><u>In 2024, How to Effortlessly Access and Apply Instagram's Best Filters</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-samsung-galaxy-a23-5g-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Samsung Galaxy A23 5G? | Dr.fone</u></a></li>
<li><a href="https://media-tips.techidaily.com/increment-in-monthly-costs-for-popular-streaming-services-disneyplus-espnplus-and-hulus-new-pricing-plan/"><u>Increment in Monthly Costs for Popular Streaming Services: Disney+, ESPN+, and Hulu's New Pricing Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-management-in-windows-11-without-rename-options/"><u>Mastering File Management in Windows 11 without Rename Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-weather-icons-styling-windows-11s-system-tray/"><u>Mastering Weather Icons: Styling Windows 11'S System Tray</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-steam-library-read-only-errors-on-pcs-with-win-11/"><u>Rectifying Steam Library Read-Only Errors on PCs with Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-voice-chat-via-xbox-mic-on-windows-11-screens/"><u>Securing Voice Chat via Xbox Mic on Windows 11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-purging-protection-history-in-modern-windows-oses/"><u>Strategies for Purging Protection History in Modern Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-disallowed-user-access-on-your-win-pc/"><u>Troubleshooting Disallowed User Access on Your Win PC</u></a></li>
</ul></div>

