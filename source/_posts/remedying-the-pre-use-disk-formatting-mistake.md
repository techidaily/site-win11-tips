---
title: Remedying the Pre-Use Disk Formatting Mistake
date: 2024-12-11T22:48:31.689Z
updated: 2024-12-12T17:09:31.462Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Perform a Complete Shutdown

[Microsoft enables Fast Start-up](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) in newer versions of the Windows operating system by default. It hibernates the system and kernel-level processes so your system boots up faster after a shutdown.

 But if the core system services encounter a glitch and stop working properly, you will see the error message every time. So, performing a complete shutdown can help in restarting all core services.

Repeat the following steps:

1. Press**Win + R** to launch the Run command box.
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to open Command Prompt with administrator privileges.
3. Input the following command and press the enter key:**shutdown /s /f /t 0**  
![Perform a Complete Shutdown](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/perform-a-complete-shutdown.jpg)
4. It will take longer than usual for your system to shut down. Power it on again and open File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click on the USB disk and check if you are able to access the files on it.

### 3\. Do a Clean Boot

 Third-party applications and services can interfere with system apps and impede their normal functioning. So,[perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) of your system. It will disable all the third-party services and programs from running at startup. If you are able to access the disk now, repeat the clean boot process while enabling third-party services one by one to isolate the culprit program.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 5\. Scan the Hard Disk Using CHKDSK

 It is possible for the USB disk to contain bad files and sectors; due to which Windows asks you to format it before usage. But you can leverage the inbuilt CHKDSK utility to scan the USB disk for errors and fix them for you. It will scan all the files on the disk and repair the drive. You can either use the[command prompt method or Run CheckDisk](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) using the Properties window in File Explorer.

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-digital-filmmakers-guide-converting-avi-media-to-compact-gif-format-in-filmora/"><u>[New] 2024 Approved Digital Filmmakers' Guide Converting AVI Media to Compact GIF Format in Filmora</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-iphone-photography-simplified-adopt-these-10-easy-rules/"><u>[Updated] IPhone Photography Simplified Adopt These 10 Easy Rules</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-the-art-of-voice-modification-the-ultimate-guide-to-morphvox/"><u>[Updated] Mastering the Art of Voice Modification The Ultimate Guide to MorphVOX</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-scholarly-streams-10-best-ed-tutorials-yt/"><u>[Updated] Scholarly Streams 10 Best Ed Tutorials YT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1-transformer-gratuitement-un-fichier-gif-en-format-m4v-avec-moviesavvy/"><u>1. Transformer Gratuitement Un Fichier GIF en Format M4V Avec MovieSavvy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mpgmkv-movavi/"><u>將MPG電影文件自動轉成MKV - Movavi的無限制線上服務</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cambia-tus-audios-desde-aif-a-m4a-gratuitamente-en-linea-usando-el-innovador-software-de-movavi-para-conversiones-rapidas-y-seguras/"><u>Cambia Tus Audios Desde AIF a M4A Gratuitamente en Línea, Usando El Innovador Software De Movavi Para Conversiones Rápidas Y Seguras.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/change-trp-files-to-mpeg-format-for-free-using-movavis-web-tool/"><u>Change TRP Files to MPEG Format for Free Using Movavi's Web Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comment-transformer-votre-nsv-en-video-mpeg-gratuite-en-ligne-guide-detaille-de-moveave/"><u>Comment Transformer Votre NSV en Vidéo MPEG Gratuite en Ligne - Guide Détaillé De Moveave</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convertir-audios-wav-directamente-al-formato-linea-congratuito-usando-herramientas-de-movavi/"><u>Convertir Audios WAV Directamente Al Formato Línea Congratuito Usando Herramientas De Movavi</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-solution-to-prevent-fortnite-from-exceeding-video-memory-limits/"><u>Effective Solution to Prevent Fortnite From Exceeding Video Memory Limits</u></a></li>
<li><a href="https://driver-download.techidaily.com/guide-to-fetch-and-improve-driver-performance-on-your-xp-pen-graphics-tool/"><u>Guide to Fetch & Improve Driver Performance on Your XP-Pen Graphics Tool</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-riot-games-fixed-the-recurring-connectivity-bug-in-lols-latest-2aster-version/"><u>How Riot Games Fixed the Recurring Connectivity Bug in LoL's Latest 2Aster Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/las-mejores-tacticas-para-escalar-la-claridad-de-tu-fotografia-un-ranking-top-6/"><u>Las Mejores Tácticas Para Escalar La Claridad De Tu Fotografía: Un Ranking Top-6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-modulo-convertitore-gratuito-raf-a-jpeg-online-per-fotografie-di-alta-qualita-e-facile-gestione/"><u>Movavi - Modulo Convertitore Gratuito RAF a JPEG Online per Fotografie Di Alta Qualità E Facile Gestione</u></a></li>
<li><a href="https://extra-hints.techidaily.com/photography-elite-line-up-best-6-4k-dslr-options-reviewed/"><u>Photography Elite Line-Up Best 6 4K DSLR Options Reviewed</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-insiders-guide-to-crafting-perfect-instagram-posts-for-2024/"><u>The Insider's Guide to Crafting Perfect Instagram Posts for 2024</u></a></li>
</ul></div>

