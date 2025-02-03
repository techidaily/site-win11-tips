---
title: "Overhauling Windows: Revert to Basic User Rights"
date: 2025-01-31T12:24:23.246Z
updated: 2025-02-01T11:55:22.851Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-a-compreehensive-guide-to-youtube-thumbnail-creation-mac/"><u>[New] 2024 Approved A Compreehensive Guide to YouTube Thumbnail Creation (Mac)</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-from-zero-to-hero-downloading-and-setting-up-obs-for-macos/"><u>[New] 2024 Approved From Zero to Hero Downloading and Setting up OBS for macOS</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-the-entrepreneurs-lifeline-critical-items-every-startup-needs-right-now/"><u>[New] 2024 Approved The Entrepreneur's Lifeline Critical Items Every Startup Needs Right Now</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1724766461936-dvd-vrdvd/"><u>無料でDVD-VR/DVDビデオを動画にする：複数選び自由なコンバータプログラム案内！</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-oneplus-ace-2v-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on OnePlus Ace 2V? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/beyond-the-buzzwords-the-leading-edits-without-vimeo/"><u>Beyond the Buzzwords The Leading Edits Without Vimeo</u></a></li>
<li><a href="https://extra-tips.techidaily.com/darktable-feature-deep-dive-tutorial/"><u>Darktable Feature Deep Dive Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disarming-windows-11-security-error-messages-quickly/"><u>Disarming Windows 11 Security Error Messages Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-opposite-worlds-to-one-android-pc-harmony-plan/"><u>From Opposite Worlds to One: Android-PC Harmony Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-recycle-bin-error-in-win1011/"><u>How to Eradicate Recycle Bin Error in WIN10/11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-become-a-facetime-pro-skype-call-basics-for-mobile-users/"><u>In 2024, Become a Facetime Pro Skype Call Basics for Mobile Users</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-from-scratch-to-screen-video-editing-with-youtube-and-others/"><u>In 2024, From Scratch to Screen Video Editing with YouTube & Others</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-stalled-wsreset-utility-in-windows-systems/"><u>Reigniting Stalled WSReset Utility in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-multiple-instances-problem-in-windows/"><u>Tackling 'Multiple Instances' Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-trustworthy-win-friendly-downloads/"><u>The Ultimate List of Trustworthy Win-Friendly Downloads</u></a></li>
</ul></div>

