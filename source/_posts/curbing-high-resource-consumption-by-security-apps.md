---
title: Curbing High-Resource Consumption by Security Apps
date: 2024-10-31T19:03:35.953Z
updated: 2024-11-01T17:17:18.420Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Curbing High-Resource Consumption by Security Apps
excerpt: This Article Describes Curbing High-Resource Consumption by Security Apps
keywords: SecAppEfficiency,ResourceSavingSoftware,EnergyConsumingSecurity,EcoFriendlySecApp,LowResourceSecApp,GreenITSecurity,SustainableCyberDefense
thumbnail: https://thmb.techidaily.com/1a0a225965c2ce4acfd77f7b81b0abb5e4b211b4f6a739d5a50d45eaa5fd443d.jpg
---

## Curbing High-Resource Consumption by Security Apps

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
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2080328/19272" target="_top" id="2080328">
  <img src="//a.impactradius-go.com/display-ad/19272-2080328" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080328/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Press**OK** to save your changes and restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129741/7443" target="_top" id="2129741">
  <img src="//a.impactradius-go.com/display-ad/7443-2129741" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129741/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-in-2024-quick-guide-to-mac-screen-taking-techniques/"><u>[New] In 2024, Quick Guide to MAC Screen Taking Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-broadcasting-showdown-deciding-between-obs-and-twitch-studio/"><u>[Updated] Broadcasting Showdown Deciding Between OBS and Twitch Studio</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-intuitive-guide-how-to-capture-on-vimeo/"><u>2024 Approved Intuitive Guide How to Capture on Vimeo</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-review-for-dji-fpv-goggles/"><u>2024 Approved Review for DJI FPV Goggles</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/comparative-study-single-vs-multi-camera-tech-today-for-2024/"><u>Comparative Study Single Vs. Multi-Camera Tech Today for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-note-30-5g-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Infinix Note 30 5G PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-to-manipulate-software-sizes-using-windows-11s-shortcut-keys/"><u>Learn to Manipulate Software Sizes Using Windows 11'S Shortcut Keys</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723005155597-maplestory-wont-open-here-are-5-effective-solutions-to-get-you-back-on-track/"><u>MapleStory Won't Open? Here Are 5 Effective Solutions to Get You Back on Track</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-dim-windows-11-screens-tips-inside/"><u>Overcoming Dim Windows 11 Screens - Tips Inside!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-ultimate-networking-haven-beyond-vidcon-for-2024/"><u>The Ultimate Networking Haven Beyond VidCon for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-unseen-paths-of-mouse-control-on-win11/"><u>The Unseen Paths of Mouse Control on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-fixes-define-role-of-chkdsk-sfc-dism/"><u>Unraveling Windows Fixes: DEFINE Role of CHKDSK, SFC, DISM</u></a></li>
</ul></div>

