---
title: Understanding CHKDSK, SFC Vs. DISM in OS Maintenance
date: 2024-06-25T16:54:15.176Z
updated: 2024-06-26T16:54:15.176Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding CHKDSK, SFC Vs. DISM in OS Maintenance
excerpt: This Article Describes Understanding CHKDSK, SFC Vs. DISM in OS Maintenance
keywords: Chkdsk Basics,SFC Overview,Disk Check Pro,Fixed Sys Image,System File Repair,DISM Tools Guide,OS Maintenance Tech
thumbnail: https://thmb.techidaily.com/42a3217d9873863c48091846f5f8a9e9b9b6456440b499628df593e7d229a025.jpg
---

## Understanding CHKDSK, SFC Vs. DISM in OS Maintenance

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

## What Is SFC Scannow and When Should You Use It?

 Whereas CHKDSK finds and fixes errors in the file system of your hard drive, **SFC (System File Checker)** specifically scans and repairs Windows system files. If it detects a file has been corrupted or modified, SFC automatically replaces that file with the correct version.

 Knowing when to use SFC is usually more obvious than with CHKDSK, which depends on the hunch that your hard drive isn't behaving correctly. If Windows programs are crashing, you're getting error messages about missing DLL files, or you're experiencing the dreaded Blue Screen of Death, then it's definitely time to run SFC.

[Open an elevated Command Prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), then type the following command and press **Enter** to execute:

`sfc /scannow`

 SFC will perform a full scan of your system and repair and replace any files that are damaged or missing using versions from the Windows component store (read the next section on DISM for more information on this and how SFC and DISM work can work together). The scan can take some time, but make sure you leave the Command Prompt window open until it's complete.

 If you only want to scan but not repair corrupted system files, type:

`sfc /verifyonly command`

 Once SFC has finished scanning, you'll see one of three messages:

* **Windows Resource Protection did not find any integrity violations.** This means that whatever's causing your PC problems isn't related to a system file.
* **Windows Resource Protection found corrupt files and successfully repaired them.** This should hopefully mean that your problems have been solved.
* **Windows Resource Protection found corrupt files but was unable to fix some of them.** This means that system files are to blame, but SFC can't replace them. Try running the tool again in Safe Mode. If you still get the same result, don't despair: it's time to use DISM.

![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)

## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-6-excellent-tools-for-controlling-windows-screen-luminosity/"><u>Unveiling the 6 Excellent Tools for Controlling Windows Screen Luminosity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-0xc0000001-on-windows-os/"><u>Steps to Solve 0XC0000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-upgrade-efficiency-over-entertainment/"><u>Windows 11 Upgrade: Efficiency Over Entertainment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-windows-hello-recognition-work-again/"><u>Making Windows Hello Recognition Work Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepad-woes-on-pc-7-steps-to-reopen-the-favorite-text-editor/"><u>Notepad Woes on PC: 7 Steps to Reopen the Favorite Text Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-autoshrink-mechanism/"><u>Taming Window's Autoshrink Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-high-cpu-usage-by-windows-ums-for-vanguard-users/"><u>Unraveling High CPU Usage by Windows’ UMS for Vanguard Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-workings-of-windows-odbc-tools/"><u>Insight Into the Workings of Windows ODBC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-identify-non-recognized-usb-devices-on-win-11/"><u>Steps to Identify Non-Recognized USB Devices on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-techniques-to-resolve-error-code-3-on-gl-drivers/"><u>Expert Techniques to Resolve Error Code 3 on GL Drivers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-subtitle-tactics-for-instagrams-video-feed/"><u>[Updated] In 2024, Subtitle Tactics for Instagram's Video Feed</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-android-music-integration-a-guide-to-social-media-playlists/"><u>[New] In 2024, Android Music Integration  A Guide to Social Media Playlists</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-top-animals-in-play-essential-android-titles-reviewed-for-2024/"><u>[Updated] Top Animals in Play  Essential Android Titles Reviewed for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-a-step-by-step-guide-to-easy-video-cuts-on-windows-phones/"><u>In 2024, A Step-by-Step Guide to Easy Video Cuts on Windows Phones</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-mastering-nikon-footage-a-step-by-step-guide-to-video-editing/"><u>New 2024 Approved Mastering Nikon Footage A Step-by-Step Guide to Video Editing</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-nokia-c110-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-flavor-journeys-tiktoks-cross-country-dishes/"><u>2024 Approved  Flavor Journeys  TikTok's Cross-Country Dishes</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/understanding-drones-their-functionality-explored/"><u>Understanding Drones  Their Functionality Explored</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-step-by-step-to-split-clips-in-vlc/"><u>In 2024, Step by Step to Split Clips in VLC</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-top-5-microphones-compatible-with-macos/"><u>[Updated] In 2024, Top 5 Microphones Compatible with MacOS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>