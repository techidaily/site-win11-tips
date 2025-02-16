---
title: "Overhauling Windows: Revert to Basic User Rights"
date: 2025-02-13T00:18:04.122Z
updated: 2025-02-16T00:30:09.454Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-top-reddit-threads-ever-the-10-greatest-hits/"><u>[Updated] In 2024, Top Reddit Threads Ever The 10 Greatest Hits</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transforming-digital-art-with-free-versatile-lut-tools/"><u>[Updated] Transforming Digital Art with Free, Versatile LUT Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-0x8007251d-activation-issue-in-windows-os/"><u>Fixing the 0X8007251D Activation Issue in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-managed-settings-failures-due-to-org-policies/"><u>Fixing Windows 11: Managed Settings Failures Due to Org Policies</u></a></li>
<li><a href="https://blog-min.techidaily.com/gratis-online-converteer-mpg-naar-3gp2-met-movavi/"><u>Gratis Online Converteer MPG Naar 3GP2 Met Movavi</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-restart-an-iphone-forcefully-and-switch-to-devices-recovery-environment/"><u>How to Restart an iPhone Forcefully and Switch to Device's Recovery Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-and-solve-apex-legends-crashes-in-win11/"><u>How to Stop and Solve Apex Legends Crashes in Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-infinix-zero-30-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Infinix Zero 30 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/master-the-update-comprehensive-guide-for-xp-pen-pen-tablet-device-drivers-upgrade/"><u>Master the Update: Comprehensive Guide for XP-Pen Pen Tablet Device Drivers Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/paint-your-windows-11-desk-a-simple-guide-to-drawing/"><u>Paint Your Windows 11 Desk - A Simple Guide to Drawing</u></a></li>
<li><a href="https://blog-min.techidaily.com/png-o-jpeg-un-confronto-dettagliato-per-la-qualita-superiore/"><u>PNG O JPEG: Un Confronto Dettagliato per La Qualità Superiore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-obsolete-heat-management-policies-in-win/"><u>Reactivating Obsolete Heat Management Policies in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-0x00709-error-on-pc/"><u>Steps to Rectify 0X00709 Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-patches-without-wi-fi/"><u>Streamlining Windows Patches Without Wi-Fi</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/toms-tech-hub-in-depth-reviews-and-news/"><u>Tom's Tech Hub: In-Depth Reviews and News</u></a></li>
</ul></div>

