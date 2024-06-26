---
title: Decrease Overhead Memory Use by Antivirus Programs
date: 2024-06-25T16:40:56.416Z
updated: 2024-06-26T16:40:56.416Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decrease Overhead Memory Use by Antivirus Programs
excerpt: This Article Describes Decrease Overhead Memory Use by Antivirus Programs
keywords: Reduce AV Memory Usage,Low-Memory Antivirus Optimization,Minimize Antivirus RAM Footprint,Decrease Antivirus Overhead,Cut VPN Memory Consumption,Optimize Antivir Memory Usage,Efficient AV Program Resource Use
thumbnail: https://thmb.techidaily.com/4f90c1408653d67bc404a72c2dca3d3d52e3a294965755306154ed4cda4187a3.png
---

## Decrease Overhead Memory Use by Antivirus Programs

 If you’ve kept a close eye on the Task Manager, then you may have noticed the Antimalware Service Executable doing its job. It is a crucial process of Windows Security (previously "Microsoft Defender") and helps keep your system safe from malware. It is pretty common to disable the Antimalware Service Executable because it consumes a large chunk of the system resources.

 On older PCs with limited system resources, the Antimalware Service Executable can severely impact the performance of your system. Read on as we discuss the importance of this service and how you can disable it.

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

 Suppose you find the Antimalware Service Executable process consuming a lot of system resources in certain instances; in that case, you can temporarily disable [real-time](https://www.makeuseof.com/real-time-protection/) malware protection through Windows Security:

1. Head to the**Start** menu, search for**Windows Security** and select the Best match.
2. Navigate to**Virus & threat protection** from the sidebar.
3. Look for**Virus & threat protection settings** , and then click on**Manage settings** option underneath.  
![real time protection windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/real-time-protection.jpg)
4. Disable the**Real-time protection** toggle button by bringing it to the**Off** position.

 Real-time protection will be turned back on automatically by Windows Security.

### Method 2: Turn Off Antimalware Service Executable Through Windows Security in the Registry Editor

 For users looking for a more permanent solution to disabling the Antimalware Service Executable, you will have to [disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) from the Registry Editor.

 If you do not have a third-party antivirus installed, disabling Windows Security will leave your system at risk of malicious malware that can damage it.

To disable Antimalware Service Executable from the Registry Editor:

1. Search for**Registry Editor** from the**Start** menu, and launch it.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows Defender** from the sidebar.
3. Right-click on the**Windows Defender** folder and select**New > DWORD (32-bit) Value** .  
![regedit windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/regedit-windows-defender.jpg)
4. Enter**DisableAntiSpyware** in the**Value name** field and**1** in the**Value data** field.
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
<li><a href="https://win11-tips.techidaily.com/counteracting-shutdownrestart-blockage-due-to-deceptive-apps-in-windows/"><u>Counteracting Shutdown/Restart Blockage Due to Deceptive Apps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-removal-of-win11s-official-store/"><u>Exclusive Removal of Win11's Official Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-wipe-old-windows-protection-markers-from-microsofts-record/"><u>Ways to Wipe Old Windows Protection Markers From Microsoft's Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-view-and-clear-the-windows-10-activity-history/"><u>How to View and Clear the Windows 10 Activity History</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-add-ons-for-disk-image-duality-on-pc/"><u>Avoiding Add-Ons for Disk Image Duality on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modern-standby-uncovering-its-defects-and-criticisms/"><u>Modern Standby: Uncovering Its Defects and Criticisms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-edge-always-active-on-windows-11-guide/"><u>Is Edge Always Active on Windows 11? Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-server-issues-fixes-and-tips-for-apex-on-windows-(156-chars/"><u>Overcoming 'No Server' Issues: Fixes and Tips for Apex on Windows (<156 Chars)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-top-10-trending-tweets-capturing-momentum/"><u>[New] Top 10 Trending Tweets Capturing Momentum</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-photoshops-jiggle-minimizing-effective-or-overstated/"><u>[Updated] Photoshop's Jiggle Minimizing - Effective or Overstated?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2023-how-to-find-videos-on-facebook-in-2024/"><u>[New] 2023 | How to Find Videos on Facebook, In 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/premier-screen-capture-apps-for-windows-free-1-5-listing/"><u>Premier Screen Capture Apps for Windows Free  #1-5 Listing</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-best-apps-to-create-engaging-video-invitations-on-your-smartphone/"><u>Updated In 2024, Best Apps to Create Engaging Video Invitations on Your Smartphone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-cryptic-snapshots-advanced-concealed-image-recording-on-snapchat/"><u>[New] In 2024, Cryptic SnapShots  Advanced Concealed Image Recording on Snapchat</u></a></li>
<li><a href="https://extra-support.techidaily.com/pioneering-haptic-interface-an-in-depth-guide-for-2024/"><u>Pioneering Haptic Interface  An In-Depth Guide for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-itel-a60-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Itel A60 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-your-motorola-moto-g34-5g-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Motorola Moto G34 5G Lock Screen Password</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-finding-clarity-in-colors-top-5-4k-monitors-showcased/"><u>[New] In 2024, Finding Clarity in Colors  Top 5 4K Monitors Showcased</u></a></li>
</ul></div>
