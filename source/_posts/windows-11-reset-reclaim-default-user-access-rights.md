---
title: "Windows 11 Reset: Reclaim Default User Access Rights"
date: 2024-12-24T18:15:00.374Z
updated: 2024-12-27T18:59:48.025Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Reset: Reclaim Default User Access Rights"
excerpt: "This Article Describes Windows 11 Reset: Reclaim Default User Access Rights"
keywords: Windows 11 Restart,Reinstall Windows,Default Account,User Access Control,Regain Privileges,Reset PC,Microsoft Update
thumbnail: https://thmb.techidaily.com/2dc71f07a766ca604beda3fe20bd5fd81321c87e0ac1f0a29af15d53f14e15af.jpg
---

## Windows 11 Reset: Reclaim Default User Access Rights

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-the-pathway-to-online-success-building-a-new-youtube-channel/"><u>[New] 2024 Approved The Pathway to Online Success Building a New YouTube Channel</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-emotional-engagement-top-kindred-android-3ds-alternatives/"><u>[Updated] 2024 Approved Emotional Engagement Top Kindred Android 3DS Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curbing-superfluous-windows-services/"><u>Curbing Superfluous Windows Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-for-deciphering-windows-11-error-messages/"><u>Effective Strategies for Deciphering Windows 11 Error Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-concealed-search-sentry-within-windows-11-taskbar/"><u>Enabling Concealed Search Sentry Within Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstating-steam-game-icons/"><u>Guide to Reinstating Steam Game Icons</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-exclusive-list-top-sandbox-experiences/"><u>In 2024, Exclusive List Top Sandbox Experiences</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-nubia-red-magic-8s-proplus-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Nubia Red Magic 8S Pro+ to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failed-cloud-operations-onedrive/"><u>Navigating Through Failed Cloud Operations (OneDrive)</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-adobe-premiere-pro-essentials-6-time-saving-tips-for-better-video-edits/"><u>New In 2024, Adobe Premiere Pro Essentials 6 Time-Saving Tips for Better Video Edits</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/retrieving-unintentionally-removed-files-from-your-iphone-using-stellar-tools/"><u>Retrieving Unintentionally Removed Files From Your iPhone Using Stellar Tools</u></a></li>
<li><a href="https://fox-direct.techidaily.com/silent-swings-managing-volume-effortlessly-in-garageband/"><u>Silent Swings Managing Volume Effortlessly in Garageband</u></a></li>
<li><a href="https://fox-metric.techidaily.com/step-by-step-guide-finding-and-configuring-your-network-preferences-via-windows-control-panel-yl-computing/"><u>Step-by-Step Guide: Finding & Configuring Your Network Preferences via Windows Control Panel - YL Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-smooth-steam-access-resolving-timeout-issues-via-rustwindows/"><u>Unlocking Smooth Steam Access: Resolving Timeout Issues via Rust/Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-ahead-a-new-era-with-ai/"><u>Windows 11 Ahead: A New Era with AI</u></a></li>
</ul></div>

