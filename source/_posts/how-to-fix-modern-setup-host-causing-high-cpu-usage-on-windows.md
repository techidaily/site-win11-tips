---
title: How to Fix Modern Setup Host Causing High CPU Usage on Windows
date: 2024-08-23T07:04:46.100Z
updated: 2024-08-24T07:04:46.100Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Modern Setup Host Causing High CPU Usage on Windows
excerpt: This Article Describes How to Fix Modern Setup Host Causing High CPU Usage on Windows
keywords: Low CPU Usage Windows,Stop High CPU Waste,Reduce Window CPU Overuse,Decrease System CPU Load,Fix Host Cpu Peak,Control Setup Cpu Consumption,Manage Windows Host Cpu
thumbnail: https://thmb.techidaily.com/f0dbd5a21adf0257efb4cfc535a5b1745bbe68be5c6511e0bd704dc50cbfa331.jpg
---

## How to Fix Modern Setup Host Causing High CPU Usage on Windows

 Many things can negatively impact your computer's performance, and this warrants an investigation to get to the bottom of it. Many Windows users usually open Task Manager to see if there's something consuming system resources and causing performance dips. And, if through your investigation, you find that the problem is Modern Setup Host causing high CPU usage, we're going to show you how to fix this.

## What Is Modern Setup Host on Windows?

 Modern Setup Host is a Windows component that runs in the background during a Windows update to ensure that the installation process goes smoothly. After Windows installs the update, Modern Setup Host also aids in making sure that everything is configured correctly to work well with the system, especially if it is a Feature Update. Another thing it does is ensure that Windows is running smoothly in terms of stability and that there aren't any security vulnerabilities.

 As you can see, it is an extremely important process.

## Why Is Modern Setup Host Causing High CPU Usage?

 Many things can alert you that something on your computer is being wasteful with system resources. In the best-case scenario, your computer can become sluggish, and, in the worst-case scenario, it might outright crash. If Modern Setup Host is the culprit behind this, causing high CPU usage, the following could be the reasons why:

* There are corrupt or missing system files on your computer.
* Something is wrong with the Windows Update process.
* There are corrupt or conflicting update files on your computer.
* There's a conflict with a third-party program or application.

 Let's look at how to fix all of these things that can affect Modern Setup Host.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix it Modern Setup Host Causing High CPU Usage

 There are several things you can do to stop Modern Setup Host from causing high CPU usage, and we're going to cover several of them in this section. And if none of them work and the situation gets so bad that you can't operate your PC efficiently, you can consider [resetting your Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/)[Computer](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

### 1\. Run an SFC or DISM Scan

 When your computer has corrupted, damaged, or missing system files, it can affect system components, including Modern Setup Host. This can cause these components to not function properly, leading to high CPU usage. To fix this, you can [repair or replace the affected Windows system files](https://www.makeuseof.com/windows-built-in-repair-tools/) using built-in tools like the SFC and DISM scan.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command.jpg)

 Once you run the scans, restart your computer and check if Modern Setup Host is still causing high CPU usage.

### 2\. Use the Update Troubleshooter

 The Update Troubleshooter is a tool on Windows that can help diagnose and fix common issues related to Windows Updates. And since Modern Setup Host is integral to the Windows Update process, running the troubleshooter can also help fix issues that affect it, including what's making it cause high CPU usage.

 To do that, you can learn [how to run any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/), including the Update Troubleshooter.

### 3\. Delete the Contents of the SoftwareDistribution Folder

 Before Windows installs an update, it will store it in the SoftwareDistribution distribution folder temporarily. So, if one of the update files there is corrupt, it can cause Modern Setup Host to use more resources than it needs to. If you clear this folder, you can potentially solve the issue.

 First, you need to stop the Windows Update service in case it is using the files in the SoftwareDistribution folder. To do that, press **Win + R** to open Windows Run. Type **services.msc** in the text box and then press the **Enter** key to open the Services window.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Find **Windows Update** in the list of services, right-click it, and select **Stop**.

![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once the service stops, go to the SoftwareDistribution folder by [opening the Windows File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and heading to **C: > Windows > SoftwareDistribution**.

![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now, press **Ctrl + A** to select everything inside the folder and press **Shift + Delete**. In the prompt, confirm that you want to clear the folder by clicking on **Yes**.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
### 4\. Try a Clean Boot

 A clean boot can help you rule out third-party programs and services that could conflict with Modern Setup Host. In this mode, Windows will launch with only the essential programs and services it needs to run, allowing you to rule out the culprit. Luckily, [launching Windows in a clean boot state](https://www.makeuseof.com/clean-boot-windows-11/) is easy, and the instructions are the same for both Windows 10 and 11\.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## Stop the Modern Setup Host From Negatively Impacting Your Computer

 Many things can cause high CPU usage on a Windows computer, and one of them is the Modern Setup Host. This process should be able to do its thing rather quickly when everything is in order during a Windows Update. But if there's something affecting the update process, it can stall and cause high CPU usage.

 So, try fixing corrupted or damaged system files, using the Update Troubleshooter, clearing the SoftwareDistrubiton folder, or performing a clean boot. Hopefully, the problem will go away before you have to reset your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-elevate-your-youtube-presence-with-custom-animated-subscription-buttons-in-filmora/"><u>[New] In 2024, Elevate Your YouTube Presence with Custom Animated Subscription Buttons in Filmora</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-ultimate-selection-of-free-youtube-introduction-makers/"><u>[New] Ultimate Selection of Free YouTube Introduction Makers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-the-full-potential-of-iphones-hdr-functions/"><u>[New] Unlocking the Full Potential of iPhone's HDR Functions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-bandicam-simplified-your-comprehensive-guide-to-the-latest/"><u>[Updated] Bandicam Simplified  Your Comprehensive Guide to the Latest</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-best-photo-background-blur-apps-for-iphone-and-android/"><u>2024 Approved  Best Photo Background Blur Apps for iPhone and Android</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-the-fundamentals-of-color-grading-using-luts-in-ae/"><u>2024 Approved  The Fundamentals of Color Grading Using LUTs in AE</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-oppo-a1x-5g-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Oppo A1x 5G PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-and-resolving-zero-x-eight-oh-three-one-f-errors-on-windows/"><u>Demystifying and Resolving Zero X Eight Oh Three One F Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-analysis-of-windows-11s-automated-data-management-system/"><u>Detailed Analysis of Windows 11'S Automated Data Management System</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/economical-floating-space-huge-data-packs-on-a-dime-for-2024/"><u>Economical Floating Space  Huge Data Packs on a Dime for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-to-uninstall-printers-in-win11/"><u>Effective Techniques to Uninstall Printers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-linux-on-wsl-2-proven-windows-enhancements/"><u>Elevate Linux on WSL 2: Proven Windows Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-paste-errors-in-windows-11-software/"><u>Eliminating Paste Errors in Windows 11 Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-to-windows-initialization-points/"><u>Fast Track to Windows' Initialization Points</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-vivo-y77t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-reactivate-hp-printer-status/"><u>How to Reactivate HP Printer Status</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-skys-champions-of-staying-power-top-10-drones/"><u>In 2024, Sky's Champions of Staying Power (Top 10 Drones)</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-poco-m6-pro-4g-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Poco M6 Pro 4G Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-solving-a-driverirqlnotlessorequal-error/"><u>Mastering the Art of Solving 'A DRIVER_IRQL_NOT_LESS_OR_EQUAL' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-taskbar-icon-size-in-win11-a-guide/"><u>Maximizing Taskbar Icon Size in Win11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-limiting-user-permissions-in-windows-10-filesystem/"><u>Method for Limiting User Permissions in Windows 10 Filesystem</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectifying-flipback-displays-with-wins-11/"><u>Rectifying Flipback Displays with Wins 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/reliable-storage-solutions-our-1-to-10-gopro-cases/"><u>Reliable Storage Solutions  Our #1 to #10 GoPro Cases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-failed-login-to-game-pass-service-on-windows-1011/"><u>Reversing Failed Login to Game Pass Service on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-google-maps-installation-for-windows-users/"><u>Seamless Google Maps Installation for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shielding-developer-interfaces-in-windows-11/"><u>Shielding Developer Interfaces in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-uninstall-strategies-personalizing-the-win-1110-menu/"><u>Speedy Uninstall Strategies: Personalizing the Win 11/10 Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-path-failure-in-win10/"><u>Steps to Rectify PATH Failure in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-conflicts-start-peace-opt-for-one-antivirus-in-windows/"><u>Stop Conflicts, Start Peace: Opt for One Antivirus in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-windows-update-notifications/"><u>Stopping Windows Update Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-network-connectivity-windows-error-31-remediation-guide/"><u>Tackling Network Connectivity: Windows Error 31 Remediation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-shutdown-delays-caused-by-unauthorized-windows-apps/"><u>Tackling Shutdown Delays Caused by Unauthorized Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-settings-application-one-user-many-options-in-windows-1011/"><u>Tailored Settings Application: One User, Many Options in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-digital-landscape-with-windows-11-features/"><u>Tailoring Your Digital Landscape with Windows 11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-drive-space-management-the-art-of-utilizing-windows-diskusage-commands/"><u>Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-system-overheats-rms-cpu-solution-guide/"><u>Troubleshooting System Overheats: RM's CPU Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-screen-without-mobile-mode-win-11/"><u>Unlock Full Screen Without Mobile Mode (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-potential-file-type-changes/"><u>Unlocking Windows' Potential: File Type Changes</u></a></li>
<li><a href="https://change-location.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>