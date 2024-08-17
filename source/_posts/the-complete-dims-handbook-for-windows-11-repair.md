---
title: The Complete DIMS Handbook for Windows 11 Repair
date: 2024-08-16T02:29:07.777Z
updated: 2024-08-17T02:29:07.777Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Complete DIMS Handbook for Windows 11 Repair
excerpt: This Article Describes The Complete DIMS Handbook for Windows 11 Repair
keywords: Win11DIMSRepairHandbook,WindowsDIMSRepairGuide,DIMSWin11FixKit,DiMSWindows11Help,RepairDIMSWindows11,DIMSToolkitForWin11,HandbookDIMSWin11Troubleshooting
thumbnail: https://thmb.techidaily.com/ac86b0aa564fee722115c20830e542db073002bfbdd584be2acd66419238b8a6.png
---

## The Complete DIMS Handbook for Windows 11 Repair

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command
![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## Run the DISM RestoreHealth Command to Repair the Windows System Image
![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## Repair Your Windows Installation Using the System File Checker (SFC) Utility
![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-break-free-from-fee-free-youtube-start-at-500plus-subscriber-level/"><u>[New] 2024 Approved  Break Free From Fee-Free Youtube - Start at 500+ Subscriber Level</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-safe-exit-procedures-for-departing-discord-servers/"><u>[New] Safe Exit  Procedures for Departing Discord Servers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-blueprint-for-flawless-srt-construction/"><u>[New] The Ultimate Blueprint for Flawless SRT Construction</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-clear-the-clutter-blurring-backgrounds-for-engaging-yt/"><u>[Updated] 2024 Approved  How to Clear the Clutter  Blurring Backgrounds for Engaging YT</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-inspiring-leadership-the-top-35-recruiter-talks/"><u>[Updated] In 2024, Inspiring Leadership  The Top 35 Recruiter Talks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-step-by-step-building-a-youtube-empire-from-scratch/"><u>[Updated] Step by Step  Building a YouTube Empire From Scratch</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-secret-to-love-in-video-editing-filmoras-best-aspects/"><u>2024 Approved  The Secret to Love in Video Editing  Filmora's Best Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-your-non-operational-windows-11-hotspot/"><u>Activating Your Non-Operational Windows 11 Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-0x8000ffff-in-windows-based-printers/"><u>Conquering Error 0X8000FFFF in Windows-Based Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-the-perfect-christmas-look-in-windows-11/"><u>Craft the Perfect Christmas Look in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-prime-8-video-cutter-tools-on-windows/"><u>Discover the Prime 8 Video Cutter Tools on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-wintoys-a-brief-dive-into-a-formidable-windows-feature/"><u>Discovering WinToys: A Brief Dive Into a Formidable Windows Feature</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-way-to-unlink-wi-fi-on-windows-11/"><u>Efficient Way to Unlink Wi-Fi on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-savings-with-w11-pro-key-access-prime-deals/"><u>Elevate Savings with W11 Pro Key: Access Prime Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-work-with-multiple-displays-in-win11/"><u>Elevate Your Work with Multiple Displays in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-chrome-freeze-and-blank-screens/"><u>Fixing the Chrome Freeze and Blank Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-suppression-of-windows-11-notifications/"><u>Immediate Suppression of Windows 11 Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-frustrations-installation-fixes-for-missing-windows-upgrades/"><u>No More Frustrations! Installation Fixes for Missing Windows Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-irregular-beats-soundcard-irq-solutions/"><u>Quelling Irregular Beats: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-of-lock-screen-delay-on-pcs/"><u>Regaining Control of Lock Screen Delay on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-wobbling-keyboard-arrows-in-windows-environments/"><u>Revive Wobbling Keyboard Arrows in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-dolby-atmos-installation-in-windows-1111/"><u>Seamless Dolby Atmos Installation in Windows 11/11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/skip-the-hassle-find-4-ringtone-sources-here-for-2024/"><u>Skip the Hassle  Find 4 Ringtone Sources Here for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-oneplus-nord-3-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amend-out-of-memory-issues-in-hogwarts-adventures/"><u>Strategies to Amend Out of Memory Issues in Hogwarts Adventures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-connections-how-to-clear-dns-in-steam-settings/"><u>Streamline Connections: How to Clear DNS in Steam Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-s-mode-essential-tips-for-windows-1011/"><u>Transitioning From S Mode: Essential Tips for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11s-operation-elevation-issue-740/"><u>Troubleshooting Windows 11'S Operation Elevation Issue #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11-screen-recording-techniques-combining-audio-and-visual-features-in-snipping-tool-max-156/"><u>Unveiling Windows 11 Screen Recording Techniques: Combining Audio & Visual Features in Snipping Tool (Max 156)</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Realme V30T? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-simplification-recapturing-default-rights/"><u>Windows 11 Simplification: Recapturing Default Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-the-promise-of-next-generation-in-the-upcoming-moment/"><u>Windows 11: The Promise of Next Generation in the Upcoming Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-insight-determining-your-intel-cpus-generation/"><u>Windows Insight: Determining Your Intel CPU's Generation</u></a></li>
</ul></div>
