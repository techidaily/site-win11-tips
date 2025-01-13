---
title: "Overhauling Windows: Revert to Basic User Rights"
date: 2025-01-10T00:42:57.328Z
updated: 2025-01-12T20:25:14.353Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overhauling Windows: Revert to Basic User Rights"
excerpt: "This Article Describes Overhauling Windows: Revert to Basic User Rights"
keywords: Basic User Privileges,Restore Windows Permissions,Reduce Windows Access,Revert User Rights,Simplify Windows Controls,Ease of Use in Windows,Basic User Setup
thumbnail: https://thmb.techidaily.com/9841b29c6cea5f5f780b6eadf9d0ee4bcbe0f046fdd4bc1a6bbe581309b919ba.jpg
---

## Overhauling Windows: Revert to Basic User Rights

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to[take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then[open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.

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
<li><a href="https://extra-resources.techidaily.com/new-boost-your-cinematography-game-essential-iphone-gear/"><u>[New] Boost Your Cinematography Game Essential iPhone Gear</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-excellent-top-5-apps-for-iphone-auditory-delight/"><u>[New] In 2024, Excellent Top 5 Apps for iPhone Auditory Delight</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-mastering-microphone-modifications-for-vtubers/"><u>[New] Mastering Microphone Modifications for VTubers</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-humor-hacks-simplifying-the-process-of-meme-creation/"><u>[Updated] 2024 Approved Humor Hacks Simplifying the Process of Meme Creation</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-asus-mg28uq-monitor-unpacking-the-ultra-high-resolution-experience/"><u>2024 Approved ASUS MG28UQ Monitor Unpacking the Ultra High-Resolution Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-compromised-windows-defense-in-win-11/"><u>Correcting Compromised Windows Defense in Win 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-ultimate-validity-fingerprint-sensor-software-fast-and-simple-installation/"><u>Download the Ultimate Validity Fingerprint Sensor Software: Fast and Simple Installation!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-linux-setup-not-wsl/"><u>Efficient Linux Setup, Not WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-dialer-feature-win-11/"><u>How to Engage Dialer Feature Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-error-win11s-uptime-failure-code-0x80246007/"><u>How to Reset Error: Win11’s Uptime Failure, Code 0X80246007</u></a></li>
<li><a href="https://screen-capture.techidaily.com/innovative-strategies-for-flawless-screens-in-adobe-captivity/"><u>Innovative Strategies for Flawless Screens in Adobe Captivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-hurdle-opening-windows-folders-via-double-click/"><u>Overcoming the Hurdle: Opening Windows' Folders via Double-Click</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-guide-easy-steps-for-bluetooth-drivers-in-windows-1011/"><u>Quick Guide: Easy Steps for Bluetooth Drivers in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-grades-essential-tips-for-efficient-windows-learning/"><u>Skyrocket Your Grades: Essential Tips for Efficient Windows Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-correction-winoss-parsing-error-0exc00ce556/"><u>Swift Correction: WinOSs Parsing Error 0eXC00CE556</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-choice-selecting-quality-bittorrent-clients/"><u>The Best Choice: Selecting Quality BitTorrent Clients</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-a-non-responsive-corsair-keyboard/"><u>Troubleshooting Guide: Fixing a Non-Responsive Corsair Keyboard</u></a></li>
</ul></div>

