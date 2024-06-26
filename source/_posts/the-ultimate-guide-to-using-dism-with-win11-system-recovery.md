---
title: The Ultimate Guide to Using Dism with Win11 System Recovery
date: 2024-06-25T17:11:12.957Z
updated: 2024-06-26T17:11:12.957Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Using Dism with Win11 System Recovery
excerpt: This Article Describes The Ultimate Guide to Using Dism with Win11 System Recovery
keywords: Dism Win11,Win11 System Recovery,System Repair Dism,Win10 Rescue Tools,Win11 Dism Guide,System Restore Win11,Dism Utility Windows 11
thumbnail: https://thmb.techidaily.com/be42a9800526c31b5bfdef3ed18cce59bd7b3192524b647f6f87b51df7e044d8.png
---

## The Ultimate Guide to Using Dism with Win11 System Recovery

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command ![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

## Run the DISM RestoreHealth Command to Repair the Windows System Image ![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

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
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility ![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070522-resolving-client-permissions-issue-on-windows-systems/"><u>Overcoming 0X80070522: Resolving Client Permissions Issue on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-affected-windows-netflix-functions/"><u>Restarting Affected Windows Netflix Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-split-display-frustrations-in-windows/"><u>Overcoming Split Display Frustrations in WIndows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-sandbox-no-hypervisor-was-found-0xc0351000-error/"><u>How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-systems-graphics-with-windows-11-tips/"><u>Revive Your System's Graphics with Windows 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-multi-screen-setup-on-windows-11/"><u>Mastering Multi-Screen Setup on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-youtube-videos-a-chrome-fix-guide/"><u>Streamlining YouTube Videos: A Chrome Fix Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-hitting-the-high-score-in-ps4-game-capture-mastery/"><u>2024 Approved  Hitting the High Score in PS4 Game Capture Mastery</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-viral-jokes-whos-winning-on-the-meme-front/"><u>[New] 2024 Approved  Viral Jokes  Who's Winning on the Meme Front?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-hide-or-highlight-best-video-blur-apps-for-mobile-phones/"><u>Updated In 2024, Hide or Highlight Best Video Blur Apps for Mobile Phones</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-navigating-the-social-sphere-of-tiktok-lives-for-2024/"><u>[Updated] Navigating the Social Sphere of TikTok Lives for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-guide-to-huawei-p10-performance-metrics/"><u>[New] The Ultimate Guide to Huawei P10 Performance Metrics</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-the-pantheon-of-popularity-instagrams-top-25-icons/"><u>[New] In 2024, The Pantheon of Popularity  Instagram's Top 25 Icons</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-se-2022-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone SE (2022) Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-samsung-galaxy-z-fold-5-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Samsung Galaxy Z Fold 5 Location on Skout | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>