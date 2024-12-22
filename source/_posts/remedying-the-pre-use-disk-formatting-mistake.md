---
title: Remedying the Pre-Use Disk Formatting Mistake
date: 2024-12-15T06:29:32.460Z
updated: 2024-12-21T18:00:52.016Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying the Pre-Use Disk Formatting Mistake
excerpt: This Article Describes Remedying the Pre-Use Disk Formatting Mistake
keywords: Fixing Disk Format Errors,Preventing Early Disk Errors,Avoiding Disk Initialization Issues,Correction of First-Use Disk Formatting,Eradicating Initial Disk Problems,Remedying Disk Setup Mistakes,Solving Disk Format Before Use
thumbnail: https://thmb.techidaily.com/4701af21fbd3236ee27b5d0a75fe2af600bece4b4b8021497e0ee7ed3f0b2671.jpg
---

## Remedying the Pre-Use Disk Formatting Mistake

 We use external flash drives and hard disks on a regular basis for file transfer and sharing. While cloud sharing is gaining popularity, physical disk sharing is still best suited for large or personal files. You can connect multiple USB devices on your system at the same time and move data from one drive to others.

 But some users encounter the "You Need To Format The Disk In Drive before you can use it" error. It forces you to format the disk before you can use it. However, it isn’t a sensible option if you have important files on the disk. We will list multiple methods using which you can reassess your disk drive. Let’s begin.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are the Reasons Behind the Error Message?

 You can see the “Format Disk in drive” message due to one or more of the following reasons:

1. The USB drive or the port is malfunctioning.
2. The device drivers of the disk are corrupt or outdated.
3. Malware is preventing access to the disk.
4. Core system files have gone missing or corrupt.
5. A third-party app is conflicting with system apps and services.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Methods to Fix the “You Need to Format the Disk in Drive Before You Can Use It” Error

 Try out the following methods to fix the disk error message and save your data stored on it:

###

### 1\. Check the USB Drive

 If connecting the USB drive to any USB port on your system produces the same error, then unplug it. Connect it to another computer and check if it shows up in Device Manager and you can access the file contents without any issues. If it works, create a copy of all your data on that system for backup purposes.

### 2\. Perform a Complete Shutdown

[Microsoft enables Fast Start-up](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) in newer versions of the Windows operating system by default. It hibernates the system and kernel-level processes so your system boots up faster after a shutdown.

 But if the core system services encounter a glitch and stop working properly, you will see the error message every time. So, performing a complete shutdown can help in restarting all core services.

Repeat the following steps:

1. Press**Win + R** to launch the Run command box.
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to open Command Prompt with administrator privileges.
3. Input the following command and press the enter key:**shutdown /s /f /t 0**  
![Perform a Complete Shutdown](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/perform-a-complete-shutdown.jpg)
4. It will take longer than usual for your system to shut down. Power it on again and open File Explorer.

5. Click on the USB disk and check if you are able to access the files on it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Do a Clean Boot

 Third-party applications and services can interfere with system apps and impede their normal functioning. So,[perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) of your system. It will disable all the third-party services and programs from running at startup. If you are able to access the disk now, repeat the clean boot process while enabling third-party services one by one to isolate the culprit program.

### 4\. Change the USB Drive Letter Using Disk Management

 Changing the drive letter could help in resolving the USB drive error on your system and make it accessible. Repeat the following steps to change the drive letter:

1. Press**Win + R** to open the Run dialog box. Type**diskmgmt.msc** and press the enter key.
2. In the Disk Management window, find your USB disk drive and right-click on it.
3. Select the**Change Drive Letter and Paths** option from the context menu.
4. Click on the**Change** button. Then, click on the**arrow** button to expand the drop-down list and select a drive letter from it.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Lastly, click on the**OK** button. Reconfirm your decision and click on the**Yes** button to change the Drive letter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. You will see a system notification informing you about the Drive letter change and mounting the drive.
7. Press**Win + E** to open the File Explorer and check whether the USB drive is accessible or not.

### 5\. Scan the Hard Disk Using CHKDSK

 It is possible for the USB disk to contain bad files and sectors; due to which Windows asks you to format it before usage. But you can leverage the inbuilt CHKDSK utility to scan the USB disk for errors and fix them for you. It will scan all the files on the disk and repair the drive. You can either use the[command prompt method or Run CheckDisk](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) using the Properties window in File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 6\. Run an SFC and DISM Scan

 If the check disk doesn’t do any good, and you still have the error, it is possible that your system files are missing or corrupt.[Start with an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to check and replace any corrupt system files. Follow that up with a[DISM scan to fix the Windows installation image](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . Make sure you have an active internet connection to run the DISM scan without any issues.

### 7\. Use a Linux Installation Media to Access the USB Disk Drive

 This method is more of a workaround to not lose your data. If you don’t have a second system nearby, you can[create a Linux installation media](https://www.makeuseof.com/tag/install-ubuntu-computer-using-usb-flash-drive/) and use the Try Ubuntu mode to mount and access the contents of the USB disk. It will save the effort of searching for another computer, and you can successfully create a backup of the USB disk.

 To access the USB disk using Linux installation media repeat the following steps:

1. Plug the Linux installation media into your system.
2. Press the**Esc** key and power on your system to enter the boot devices menu. Select the Linux installation media and boot it up.
3. In the Grub menu, select the**Try or install Ubuntu** option. Wait for the setup Window to launch and then click on the**Try Ubuntu** option.
4. Go to the left-hand side menu and click on the**Files** app.  
![Use a Linux Installation Media to Access the USB Disk Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/use-a-linux-installation-media-to-access-the-usb-disk-drive.jpg)
5. Click on the USB disk name in the navigation pane to open it. Now, you can copy these files to another location on your hard drive or an external hard disk.
6. After you finish copying the contents of the USB disk, click on the power icon and choose the Power off option to close the Try Ubuntu mode.

### 8\. Try Generic Fixes for Drive Formatting Issues

 If none of those worked, it's time to apply more general fixes before diving into more drastic measures. There are a few different error messages related to storage drive formatting issues that Windows can throw, and all of them share some common fixes.

 As such, check out[how to fix format disk errors on Windows without formatting your drive](<http://How> to Fix Format Disk Errors Without Formatting Your Hard Drive on Windows) for more tips.

### 9\. Reset Windows

 If nothing seems to work, and you see the error with every USB disk you try to connect to the system, consider a complete Windows reset. It will remove all your system files and installed apps (though you can choose to keep personal files on the system drive).

 However, before[performing a System Reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try[System Restore](https://www.makeuseof.com/windows-reset-system-restore-difference/) using any available System Restore points. If that fails, and a reset doesn't seem to work, you can[factory reset your Windows computer](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Access USB Disk Contents Without Formatting

 It is a bad idea to click on the Format button when File Explorer prompts you to do it to access the USB disk. Firstly, try to check the hardware malfunctions and salvage the data on the USB disk. You can use another system or create a Linux installation media to access files on the USB disk.

 If SFC and DISM fail to repair the system, and you still see the error with every USB disk you connect to your system, reset your Windows computer.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-the-experts-guide-to-xbox-one-screen-captures/"><u>[New] In 2024, The Expert's Guide to Xbox One Screen Captures</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-compact-obs-setup-for-underpriced-pcs/"><u>[Updated] Compact OBS Setup for Underpriced PCs</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-mobile-apps-for-top-notch-introduction-videos-on-iosandroid-for-2024/"><u>[Updated] Mobile Apps for Top-Notch Introduction Videos on iOS/Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-login-attempt-wait-time-for-windows-os/"><u>Customizing Login Attempt Wait Time for Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-stranded-alert-on-xbox-in-windows-a-step-by-step-guide/"><u>Fixing 'Stranded' Alert on Xbox in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Oppo A78 5G? | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/how-to-enable-and-use-dvd-playback-feature-on-the-xbox-one-gaming-system/"><u>How to Enable and Use DVD Playback Feature on the Xbox One Gaming System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-stale-group-policies-on-windows-machines/"><u>Quick Fixes for Stale Group Policies on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-solving-semaphore-timeout-in-windows-1110/"><u>Quick Guide: Solving Semaphore Timeout in Windows 11/10</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/top-strategies-for-ensuring-maximum-productivity-of-your-computer-insights-by-yl-software/"><u>Top Strategies for Ensuring Maximum Productivity of Your Computer - Insights by YL Software</u></a></li>
<li><a href="https://hardware-help.techidaily.com/top-rated-webcams-for-live-broadcasts-comprehensive-reviews-by-tech-pros-zdnet/"><u>Top-Rated Webcams for Live Broadcasts : Comprehensive Reviews by Tech Pros - ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-optimal-display-performance-on-win1011/"><u>Unlock Optimal Display Performance on WIN10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-voice-recorders-quick-access-with-shortcuts-guide/"><u>Windows 11 Voice Recorders: Quick Access with Shortcuts Guide</u></a></li>
</ul></div>

