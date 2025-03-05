---
title: Unraveling the Mystery of 0X80072f8f on PCs
date: 2025-02-28T18:58:29.348Z
updated: 2025-03-04T17:16:07.974Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling the Mystery of 0X80072f8f on PCs
excerpt: This Article Describes Unraveling the Mystery of 0X80072f8f on PCs
keywords: XP Error Code Fix,Debug 0X80072F8F Windows,Fatal OS Error Resolution,ZeroX Error Diagnosis PC,Fixing 0X Error on Computer,Solve Windows Error 72F,Eliminating XP Crash Code
thumbnail: https://thmb.techidaily.com/1327be62e2a36c04a123df979f8639b0dac23eaf84d67c3864e5678ef96194e7.jpg
---

## Unraveling the Mystery of 0X80072f8f on PCs

 The Windows Media Creation Tool prepares installation media for upgrading your PC or creating a USB drive to perform a clean Windows installation. It is the perfect tool to make sure you are using the latest Windows version and is quite easy to use.

 However, there are times when users can run into errors while using the Media Creation Tool. One such error is the error code 0x80072f8f – 0x20000, which appears when users attempt to launch the MediaCreationTool.exe file.

 Below, you will find several effective troubleshooting methods that will help you fix this issue in no time.

## 1\. Run the Media Creation Tool as an Administrator

 Certain programs and processes on Windows operating system need administrative privileges to perform their jobs properly. If they are not allowed these extra permissions, you are likely to run into error codes such as this one.

 So, the first thing that you need to do if you encounter the error code 0x80072f8f - 0x20000 upon attempting to use the Media Creation Tool is to launch the file as an administrator. If insufficient permissions are causing the problem, this should fix it without you having to go through any of the complex troubleshooting methods.

Follow these steps to run the file as administrator:

1. Right-click on the targeted file and select**Run as administrator** from the context menu.  
![Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/run-as-administrator-1.jpg)
2. Click**Yes** in the confirmation prompt and check if the file runs without any issues now.  
![Yes button in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/user-account-control-yes.jpg)

 If the error persists, it indicates that there is another cause behind it. In that case, proceed with the next method.

## 2\. Use a Different USB Port

 Often, faulty ports cause issues during the creation of the installation media. There are [several ways to test if the USB port is faulty](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) . You can begin by switching to another port and checking if the USB works fine there.

 You can also try using the same USB on another device and see if it works fine there.

## 3\. Modify the Windows Registry

 Making some changes in the Windows Registry to allow Media Creation Tool to run smoothly is another potential fix that you can try.

 Windows Registry is an administrative-level, powerful utility that stores information about the programs and processes of your operating system. The information here is stored as keys and values. You can modify the relevant keys/values to customize the processes of your system, which is exactly what we are going to do in this method.

 However, before you proceed with this method, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will help you restore the current state of your system in case anything goes wrong during the process.

When you have created a backup, follow these steps.

1. Press**Win** +**R** to open a Run dialog.
2. Type**regedit** in Run and click**Enter** .  
![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/regedit.jpg)
3. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\Auto Update`
4. Right-click in an empty area in the right pane and select**New** \>**DWORD (32-bit) Value** from the context menu.  
![New DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/auto-update-new-dword.jpg)
5. Name this value as**AllowOSUpgrade** .  
![AllowOSUpgrade value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/allow-os-upgrade.jpg)
6. Double-click on**AllowOSUpgrade** and type**1** under Value data.  
![Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/allow-os-upgrade-value-data.jpg)
7. Hit**OK** and close the Registry Editor.

 You can now restart your PC and upon reboot, check if the Media Creation Tool works fine.

## 4\. Delete the Content of the Software Distribution Folder

 Another solution that worked for users was deleting the contents of the Software Distribution folder. This folder contains temporary files that might be interfering with the process of the Media Creation Tool.

 If this scenario is applicable, deleting the contents of the Software Distribution folder by following the steps below should do the trick for you.

1. Launch File Explorer and navigate to the location below:  
`C:\Windows\SoftwareDistribution\Download`  
![Software Distribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/software-distribution-download.jpg)
2. Select all the contents of the Download folder and right-click on them.
3. Click on the**bin icon** in the context menu to delete them.  
![Delete icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/delete-download.jpg)
4. Once you delete the files, type**cmd** in the search area of the taskbar and select**Run as administrator** .
5. Type the following command in the Command Prompt window and hit**Enter** .  
`wuauclt.exe /updatenow`  
![wuauclt.exe command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/wuauclt-exe-updatenow.jpg)
6. Then, restart your PC and try launching Media Creation Tool again.

## 5\. Enable Relevant Services

 Programs and processes on the Windows operating system require relevant services to be functioning to work. If any of the relevant services are disabled or corrupt, the program will fail to function.

 For instance, the Windows Update process requires the Windows Update service to run. If the settings of this service are not configured properly, you will fail to install the latest updates.

 Similarly, Media Creation Tool is related to the following services, and they should be working fine for you to use it:

* Windows Update
* Background Intelligent Transfer Service
* Server
* Workstation
* TCP/IP NetBIOS Helper
* IKE and AuthIP IPsec Keying Modules

 In this method, we will make sure that these services are configured accurately, and we will be using the Windows Update service to demonstrate the steps.

1. Open a Run dialog by pressing**Win** +**R keys** .
2. Type**services.msc** in the dialog and hit**Enter** . This should launch Windows Services.
3. In the following window, right-click on the**Windows Update** service and choose**Properties** from the context menu.
4. ![Windows update service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/services-windows-update-properties.jpg)
5. In the Properties dialog, change the Startup type to**Automatic** .  
![Startup type as automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/startup-type-automatic.jpg)
6. If the service is stopped, click on the**Start button** and select**Apply** \>**OK** to save the changes.  
![Start button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/start-service-status.jpg)
7. Repeat the same steps for the rest of the above-mentioned services.

 Once done, check if you can run the Media Creation Tool without any issues now.

## 8\. Perform a Clean Boot

 The issue can also arise due to a driver or software conflict within the system. To check if this is the case, you can perform a clean boot to launch the system with a minimal set of drivers and startup programs. If the issue does not appear in this mode, then it implies that a background process or driver is indeed causing the problem. You can then take necessary steps to remove it from the system.

Here is how you can perform a clean boot in Windows:

1. Press the Win + R keys together to open Run.
2. Type msconfig in the text field of Run and click Enter.
3. In the System Configuration window, head over to the**Services** tab and checkmark the box for**Hide all Microsoft services** .  
![Hide all Microsoft services option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-hide-all-msservices.jpg)
4. Click on the**Disable all button** .
5. Now, navigate to the**Startup** tab and click on**Open Task Manager** .  
![Open the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/startup-open-task-manager.jpg)
6. In the Startup tab, right-click on all the items and choose**Disable** .  
![Click on the Disable button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disable-program.jpg)
7. Once done, close the Task Manager and go back to the System Configuration window.
8. Click**Apply** \>**OK** to save the changes.
9. Finally, restart your computer.

 If the error code 0x80072f8f - 0x20000 is not present after a clean boot, it suggests that the issue was caused by a software or driver conflict. If this situation is applicable, you can either manually remove the recently installed software that you think might be leading to the issue, or [perform a system restore](https://www.makeuseof.com/tag/windows-system-restore-works/) to return to an older functioning state of the system.

## 7\. Disable Your Antivirus

 If you are using a third-party antivirus in Windows, there is a chance that it is blocking the process of Media Creation Tool because of a false alarm. To check if this is the case, you can disable or uninstall your antivirus and then run the Media Creation Tool.

 If the antivirus program is the culprit, then we recommend switching to another similar service for better performance.

## Media Creation Tool Error, Now Resolved

 Media Creation Tool is undoubtedly one of the most useful and easy-to-use tools offered by Microsoft for Windows. The troubleshooting methods listed above will hopefully allow you to use it without any issues. If the error appears again, you can reach out to the official Microsoft support team and report the problem to them. Hopefully, they will be able to identify the exact cause of the issue and suggest you a fix accordingly.

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
<li><a href="https://fox-http.techidaily.com/updated-navigating-the-nuances-zooming-in-on-roblox-for-2024/"><u>[Updated] Navigating the Nuances Zooming In on Roblox for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-simple-methods-for-capturing-online-stations-a-guide-by-movavi/"><u>10 Simple Methods for Capturing Online Stations: A Guide by Movavi</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-unhindered-movie-enjoyment-no-cost-video-player-pcmac/"><u>2024 Approved Unhindered Movie Enjoyment - No Cost VIDEO Player (PC/Mac)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726222500223-mkvgif-movavi/"><u>費用不要なMKVからGIFへの自動変換 - Movaviを利用して簡単に</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-the-right-video-editor-for-your-chromebook-the-ultimate-guide-to-top-9-options/"><u>Choosing the Right Video Editor for Your Chromebook: The Ultimate Guide to Top 9 Options</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/critical-card-detection-failure/"><u>Critical: Card Detection Failure</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-installation-of-the-new-nvidia-geforce-rtx-3070-graphics-drivers-for-pcs-running-windows-11-or-10/"><u>Free Installation of the New NVIDIA GeForce RTX 3070 Graphics Drivers for PCs Running Windows 11 or 10</u></a></li>
<li><a href="https://win-lab.techidaily.com/guide-complet-depanner-lerreur-de-non-initialisation-du-tpm-dans-windows-n-et-les-solutions-pour-y-compris/"><u>Guide Complet : Dépanner L’Erreur De Non Initialisation Du TPM Dans Windows N Et Les Solutions Pour Y Compris</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unify-your-cloud-storage-onedrive-plus-microsoft-service/"><u>How to Unify Your Cloud Storage: OneDrive + Microsoft Service</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-essential-mac-6-video-grabber-apps/"><u>In 2024, Essential Mac 6 Video Grabber Apps</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-streamline-your-soundtrack-with-these-playlist-tips-for-youtube/"><u>In 2024, Streamline Your Soundtrack with These Playlist Tips for YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-methods-for-flawless-mp4-conversion-from-mkv-without-compromising-video-integrity/"><u>Top 10 Methods for Flawless MP4 Conversion From MKV Without Compromising Video Integrity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-16-livres-gravadores-de-video-mais-eficientes-para-o-ano-de-2024/"><u>Top 16 Livres Gravadores De Vídeo Mais Eficientes Para O Ano De 2024</u></a></li>
</ul></div>

