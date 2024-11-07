---
title: Too Much Memory Used by Antivirus? How to Manage
date: 2024-11-05T04:27:20.209Z
updated: 2024-11-06T20:10:11.779Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144285/7443" target="_top" id="2144285">
  <img src="//a.impactradius-go.com/display-ad/7443-2144285" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144285/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Should You Disable the Antimalware Service Executable?

 Considering how integral the Antimalware Service Executable is to protect your PC, you must be wondering why you should even consider disabling it.

 If you do not have a third-party antivirus installed on your system, then Windows Security is your sole protection against potentially harmful malware. If your PC is left without any third-party antivirus programs installed, the Antimalware Service Executable automatically enables itself and begins safeguarding your PC as part of Windows Security.

 Ideally, you should not turn off the Antimalware Service Executable process. But if you have a reliable third-party antivirus installed, and the Antimalware Service Executable is still consuming a large chunk of your RAM or CPU, then it might make sense to disable it.

## How to Disable the Antimalware Service Executable

 There are a few different ways you can disable the Antimalware Service Executable depending on the circumstances of your system’s performance.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416">
  <img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Method 1: Disable Real-time Protection

 Suppose you find the Antimalware Service Executable process consuming a lot of system resources in certain instances; in that case, you can temporarily disable[real-time](https://www.makeuseof.com/real-time-protection/) malware protection through Windows Security:

1. Head to the**Start** menu, search for**Windows Security** and select the Best match.
2. Navigate to**Virus & threat protection** from the sidebar.
3. Look for**Virus & threat protection settings** , and then click on**Manage settings** option underneath.  
![real time protection windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/real-time-protection.jpg)
4. Disable the**Real-time protection** toggle button by bringing it to the**Off** position.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
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
5. Press**OK** to save your changes and restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-access.techidaily.com/new-elevate-your-creations-the-7-most-innovative-nft-generators/"><u>[New] Elevate Your Creations - The 7 Most Innovative NFT Generators</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-the-art-of-perfect-video-quality-in-zoom-sessions/"><u>[Updated] 2024 Approved The Art of Perfect Video Quality in Zoom Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-script-mishaps-a-comprehensive-fix-list-for-windows/"><u>Conquer Script Mishaps: A Comprehensive Fix List for Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/crafting-impressive-videos-with-the-best-methods-for-obs-studio/"><u>Crafting Impressive Videos with the Best Methods for OBS Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-techniques-generating-sfx-archives-on-win11/"><u>Cutting Edge Techniques: Generating SFX Archives on Win11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-on-apple-iphone-8-by-drfone-ios/"><u>How to Bypass iCloud Lock on Apple iPhone 8</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-samsung-galaxy-z-fold-5-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Samsung Galaxy Z Fold 5 online without jailbreak</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-oppo-reno-9a-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Oppo Reno 9A?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-tecno-pop-7-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Tecno Pop 7 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-10-audio-transformation-apps-for-next-level-vtuber-performance/"><u>In 2024, Top 10 Audio Transformation Apps for Next-Level VTuber Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-radeon-performance-windows-11-driver-guide/"><u>Maximizing Radeon Performance: Windows 11 Driver Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-repair-protocol-for-error-code-x800704cf/"><u>Microsoft Store Repair Protocol for Error Code X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-microsoft-outlook-problems-in-windows/"><u>Navigating the Maze of Microsoft Outlook Problems in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-stop-default-path-problems-in-windows/"><u>Quick Fix: Stop 'Default Path' Problems in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-optimize-ram-allocation-in-windows-operating-system/"><u>Tips to Optimize RAM Allocation in Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-down-on-typos-reverse-silence-on-your-spacebar/"><u>Turning Down on Typos: Reverse Silence on Your Spacebar</u></a></li>
<li><a href="https://extra-tips.techidaily.com/why-testimonial-videos-boost-brand-credibility/"><u>Why Testimonial Videos Boost Brand Credibility</u></a></li>
</ul></div>

