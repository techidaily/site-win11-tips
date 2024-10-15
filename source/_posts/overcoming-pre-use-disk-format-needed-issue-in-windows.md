---
title: Overcoming Pre-Use Disk Format Needed Issue in Windows
date: 2024-10-13T16:10:10.849Z
updated: 2024-10-14T17:33:10.460Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Pre-Use Disk Format Needed Issue in Windows
excerpt: This Article Describes Overcoming Pre-Use Disk Format Needed Issue in Windows
keywords: Fix Disk Errors WIN,Resolve Format Issues PC,Unformat Disks Windows,Clear Formatting Problems,Solve Pre-Use Format,Erase Disk Errors Win,Remove Default Disk Settings
thumbnail: https://thmb.techidaily.com/f49bc8cad6beb9dab5f0418b9b2ef89c1f57811a05de89bd7149842bbd8e67a6.jpg
---

## Overcoming Pre-Use Disk Format Needed Issue in Windows

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
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Do a Clean Boot

 Third-party applications and services can interfere with system apps and impede their normal functioning. So,[perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) of your system. It will disable all the third-party services and programs from running at startup. If you are able to access the disk now, repeat the clean boot process while enabling third-party services one by one to isolate the culprit program.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. Change the USB Drive Letter Using Disk Management

 Changing the drive letter could help in resolving the USB drive error on your system and make it accessible. Repeat the following steps to change the drive letter:

1. Press**Win + R** to open the Run dialog box. Type**diskmgmt.msc** and press the enter key.
2. In the Disk Management window, find your USB disk drive and right-click on it.
3. Select the**Change Drive Letter and Paths** option from the context menu.
4. Click on the**Change** button. Then, click on the**arrow** button to expand the drop-down list and select a drive letter from it.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Lastly, click on the**OK** button. Reconfirm your decision and click on the**Yes** button to change the Drive letter.
6. You will see a system notification informing you about the Drive letter change and mounting the drive.
7. Press**Win + E** to open the File Explorer and check whether the USB drive is accessible or not.

### 5\. Scan the Hard Disk Using CHKDSK

 It is possible for the USB disk to contain bad files and sectors; due to which Windows asks you to format it before usage. But you can leverage the inbuilt CHKDSK utility to scan the USB disk for errors and fix them for you. It will scan all the files on the disk and repair the drive. You can either use the[command prompt method or Run CheckDisk](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) using the Properties window in File Explorer.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. After you finish copying the contents of the USB disk, click on the power icon and choose the Power off option to close the Try Ubuntu mode.

### 8\. Try Generic Fixes for Drive Formatting Issues

 If none of those worked, it's time to apply more general fixes before diving into more drastic measures. There are a few different error messages related to storage drive formatting issues that Windows can throw, and all of them share some common fixes.

 As such, check out[how to fix format disk errors on Windows without formatting your drive](<http://How> to Fix Format Disk Errors Without Formatting Your Hard Drive on Windows) for more tips.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 9\. Reset Windows

 If nothing seems to work, and you see the error with every USB disk you try to connect to the system, consider a complete Windows reset. It will remove all your system files and installed apps (though you can choose to keep personal files on the system drive).

 However, before[performing a System Reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try[System Restore](https://www.makeuseof.com/windows-reset-system-restore-difference/) using any available System Restore points. If that fails, and a reset doesn't seem to work, you can[factory reset your Windows computer](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) .

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
<li><a href="https://video-capture.techidaily.com/new-in-2024-best-of-breed-capture-card-for-switch/"><u>[New] In 2024, Best of Breed Capture Card for Switch</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-the-3-step-guide-to-exceptional-gopro-videos/"><u>[New] The 3-Step Guide to Exceptional GoPro Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-snap-a-different-shot-11-best-instagram-tools/"><u>[Updated] 2024 Approved Snap A Different Shot - 11 Best Instagram Tools</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-excellent-collection-advanced-webcam-supports/"><u>[Updated] Excellent Collection Advanced Webcam Supports</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-streamline-your-zoom-meetings-screen-sharing-essentials-for-2024/"><u>[Updated] Streamline Your Zoom Meetings Screen Sharing Essentials for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-there-are-no-startup-items-to-display-in-the-task-manager-error-on-windows/"><u>8 Ways to Fix There Are No Startup Items to Display in the Task Manager Error on Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/m2tff3/"><u>最適な無料ツールでM2TFFファイルの変換方法:上位3つ紹介</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-beginners-guide-to-using-windows-canary/"><u>A Step-by-Step Beginner’s Guide to Using Windows' Canary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pcs-boot-up-with-these-3-ways-in-windows-11/"><u>Accelerate Your PC's Boot-Up with These 3 Ways in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-os-public-ip-command-prompt-tricks/"><u>Accessing OS Public IP: Command Prompt Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-mic-during-screencast-with-powerpoint/"><u>Addressing Missing Mic During Screencast with PowerPoint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-microsofts-new-taskbar-helper-in-windows-11-streamlines-tasks/"><u>AI Integration: Microsoft's New Taskbar Helper in Windows 11 Streamlines Tasks</u></a></li>
<li><a href="https://win-blog.techidaily.com/illuminate-the-gameplay-eradicating-the-darkness-of-fortnites-pc-blackout-problem/"><u>Illuminate the Gameplay: Eradicating the Darkness of Fortnite's PC Blackout Problem</u></a></li>
<li><a href="https://extra-skills.techidaily.com/monetary-aspects-of-shopping-reviews-vlogs-in-2024/"><u>Monetary Aspects of Shopping Reviews Vlogs, In 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/securing-spotlight-uploading-imovie-to-vimeo-successfully/"><u>Securing Spotlight Uploading iMovie to Vimeo Successfully</u></a></li>
</ul></div>

