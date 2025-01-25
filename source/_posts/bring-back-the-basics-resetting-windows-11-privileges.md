---
title: "Bring Back the Basics: Resetting Windows 11 Privileges"
date: 2025-01-17T19:37:17.618Z
updated: 2025-01-24T20:02:02.771Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bring Back the Basics: Resetting Windows 11 Privileges"
excerpt: "This Article Describes Bring Back the Basics: Resetting Windows 11 Privileges"
keywords: Win11 Privilege Reset,Basic Setup W11,W11 Security Settings,Uninstalling W11 Extras,Windows Fundamentals,Simplify Windows W11,Disable Admin Tools W11
thumbnail: https://thmb.techidaily.com/c07f3ef9154ad0c617bd9bd6a2a32146d7b51b27c7deece2dc0396518e1e76ee.jpg
---

## Bring Back the Basics: Resetting Windows 11 Privileges

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-effortless-mp3-conversion-from-youtube-for-mac-users-for-2024/"><u>[New] Effortless MP3 Conversion From YouTube for Mac Users for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-cone-chronicles-a-deep-dive-into-ice-cream-recording-software/"><u>[Updated] Cone Chronicles A Deep Dive Into Ice Cream Recording Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-deactivated-vss-on-systems/"><u>Correcting Deactivated VSS on Systems</u></a></li>
<li><a href="https://win-tutorials.techidaily.com/decoding-different-types-of-pc-hardware-incompatibility-in-windows-environments-expert-analysis-from-yl-software/"><u>Decoding Different Types of PC Hardware Incompatibility in Windows Environments - Expert Analysis From YL Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diy-windows-audio-to-text-application-using-autohotkey-and-whisper-libraries/"><u>DIY Window's Audio to Text Application Using AutoHotkey & Whisper Libraries</u></a></li>
<li><a href="https://android-unlock.techidaily.com/downloading-samfw-frp-tool-30-for-lava-blaze-2-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Lava Blaze 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-reactivate-windows-11-troubleshooters/"><u>Essential Guide to Reactivate Windows 11 Troubleshooters</u></a></li>
<li><a href="https://techtrends.techidaily.com/explore-our-top-picks-best-imessage-gaming-experiences-in-erto2024andamputmsourcenewsletter-targetblank)7-amazing-games-for-your-iphone-chat-this-year(a)/"><u>Explore Our Top Picks: Best iMessage Gaming Experiences in Er_to=2024&amp;utm_source=newsletter Target=_blank>7 Amazing Games for Your iPhone Chat This Year</A></u></a></li>
<li><a href="https://tech-savvy.techidaily.com/geminis-1m-milestone-a-new-era-for-tokens-and-market/"><u>Gemini’s $1M Milestone - A New Era for Tokens and Market</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-enable-printer-connectivity-with-various-gadgets-over-a-local-network/"><u>How to Enable Printer Connectivity with Various Gadgets Over a Local Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-regain-admin-privileges-on-a-pc/"><u>How to Regain Admin Privileges on a PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-uniting-obs-and-zoom-for-professional-streams/"><u>In 2024, Uniting OBS & Zoom for Professional Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revive-windows-obs-studio-launch-issues/"><u>Methods to Revive Windows OBS Studio Launch Issues</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-create-stunning-video-invites-top-apps-for-ios-and-android-for-2024/"><u>New Create Stunning Video Invites Top Apps for iOS and Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-disabled-mobile-hotspot-issue/"><u>Overcoming Windows 11'S Disabled Mobile Hotspot Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-directories-enabling-controlled-access-in-windows-1011/"><u>Securing Directories: Enabling Controlled Access in Windows 10/11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/stunning-video-capture-best-youtube-cameras-reviewed-for-2024/"><u>Stunning Video Capture Best YouTube Cameras Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-execution-identifiers-in-app-management/"><u>Understanding Execution Identifiers in App Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-pc-potential-windows-11-sans-bloatware/"><u>Unleash PC Potential: Windows 11, Sans Bloatware</u></a></li>
</ul></div>

