---
title: "Overhauling Windows: Revert to Basic User Rights"
date: 2025-02-27T20:49:27.256Z
updated: 2025-03-05T02:50:08.166Z
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

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

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

4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

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
<li><a href="https://extra-skills.techidaily.com/new-screen-size-showdown-the-ultrawide-vs-uhd-4k-dilemma/"><u>[New] Screen Size Showdown The UltraWide Vs UHD 4K Dilemma</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-transforming-old-images-into-snaps-on-snapchat/"><u>[New] Transforming Old Images Into Snaps on Snapchat</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-prime-5-filters-elevating-submerged-cinematography/"><u>[Updated] Prime 5 Filters Elevating Submerged Cinematography</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-iphone-xs-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from iPhone XS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-efficiently-locate-processes-with-win11-task-manager/"><u>How to Efficiently Locate Processes with Win11 Task Manager</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-captivating-videos-start-here-these-7-royalty-free-audios/"><u>In 2024, Captivating Videos Start Here These 7 Royalty-Free Audios</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-cyberlink-screen-recorder-review-and-the-best-alternative/"><u>In 2024, Cyberlink Screen Recorder Review and the Best Alternative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-configuration-of-dns-services-in-windows-11/"><u>Precision Configuration of DNS Services in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-of-your-keys-repair-win10-shortcuts/"><u>Regain Control of Your Keys: Repair WIN10 Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-screen-stutter-on-windows-11-systems/"><u>Resolving Screen Stutter on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shield-your-activity-turn-off-windows-tracking/"><u>Shield Your Activity: Turn Off Windows Tracking</u></a></li>
<li><a href="https://extra-information.techidaily.com/strategizing-success-the-open-door-approach/"><u>Strategizing Success The Open Door Approach</u></a></li>
</ul></div>

