---
title: How to Reset All User Permissions to Default in Windows 11
date: 2024-12-21T01:33:14.187Z
updated: 2024-12-22T09:04:23.413Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset All User Permissions to Default in Windows 11
excerpt: This Article Describes How to Reset All User Permissions to Default in Windows 11
keywords: Windows 11 Reset Permisions,Reset User Rights,Win11 Default Perms,Change Windows 11 Perms,User Permissions Reset Win,Default User Settings in Win11,Altering Windows Perms Guide
thumbnail: https://thmb.techidaily.com/98bd5c521103adb9f2f398b8ea114e1ff33040cece118b77c428c885565f6981.jpg
---

## How to Reset All User Permissions to Default in Windows 11

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/new-ios-compatible-psp-games-the-five-finest-for-2024/"><u>[New] IOS Compatible PSP Games The Five Finest for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-fusion-functionality-combining-watch-mac-access/"><u>[Updated] Fusion Functionality Combining Watch, Mac Access</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-the-art-of-haul-videography-pre-and-post-editing-processes/"><u>[Updated] In 2024, The Art of Haul Videography Pre and Post Editing Processes</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-mp3-converter-convert-mpeg-audio-files-to-aac-m4a-format/"><u>Free MP3 Converter: Convert MPEG Audio Files to AAC M4A Format</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-se-2022-to-samsung-galaxy-s20-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone SE (2022) to Samsung Galaxy S20? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-asus-rog-phone-8-pro-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Asus ROG Phone 8 Pro via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-processor-age-detection-a-windows-users-guide-8-methods/"><u>Intel Processor Age Detection: A Windows User’s Guide (8 Methods)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/optimizing-your-experience-viewing-facebook-live-effectively-for-2024/"><u>Optimizing Your Experience Viewing Facebook Live Effectively for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/overcoming-common-challenges-tips-to-correctly-address-steamvr-error-the-unique-approach-of-the-green-belt-in-lean-thinking/"><u>Overcoming Common Challenges: Tips to Correctly Address SteamVR Error The Unique Approach of the 'Green Belt' In Lean Thinking</u></a></li>
<li><a href="https://sound-issues.techidaily.com/restore-audio-to-your-mute-mac-with-these-effective-fixes-and-tips/"><u>Restore Audio to Your Mute Mac with These Effective Fixes and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-recognizing-missing-hdd-in-os/"><u>Steps for Recognizing Missing HDD in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-overscan-on-windows-full-screen-perfection-guide/"><u>Trim Overscan on Windows: Full-Screen Perfection Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-pc-from-the-grips-of-error-code-22-in-windows-11/"><u>Unlock Your PC From the Grips of Error Code 22 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unifying-device-use-for-effortless-stickies/"><u>Windows 11: Unifying Device Use for Effortless Stickies</u></a></li>
</ul></div>

