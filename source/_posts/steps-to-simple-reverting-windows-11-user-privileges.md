---
title: "Steps to Simple: Reverting Windows 11 User Privileges"
date: 2024-10-25T16:25:23.964Z
updated: 2024-11-01T17:41:48.524Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Steps to Simple: Reverting Windows 11 User Privileges"
excerpt: "This Article Describes Steps to Simple: Reverting Windows 11 User Privileges"
keywords: Win11 Privilege Reversion,Revoking Windows Rights,Simplified User Control,Limit Windows Access,Modify User Perms,Secure PC Privileges,Restrict Admin Powers
thumbnail: https://thmb.techidaily.com/6d09665be2a2fe83c31f111bbc0153ce5984e036a76c36457898ede132e8d028.jpg
---

## Steps to Simple: Reverting Windows 11 User Privileges

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151855/7443" target="_top" id="2151855">
  <img src="//a.impactradius-go.com/display-ad/7443-2151855" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151855/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-in-game-capture-clarified/"><u>[New] 2024 Approved In-Game Capture Clarified</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-simplified-journey-for-metaverse-personas/"><u>[New] The Ultimate Simplified Journey for Metaverse Personas</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-essential-tools-for-adding-framing-to-digital-pictures-2023-edition/"><u>[Updated] Essential Tools for Adding Framing to Digital Pictures - 2023 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-the-msvcr110dll-absence-a-fix-guide/"><u>Combatting the Msvcr110.dll Absence: A Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-your-windows-background-file-location-on-pc/"><u>Discover Your Window's Background File Location on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-severe-javascript-failures-within-discord-win-edition/"><u>Expert Fixes for Severe JavaScript Failures Within Discord WIN Edition</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-itel-a70-easily-by-drfone-android/"><u>How To Unlock a Itel A70 Easily?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-stuck-gifs-in-discord-windows-edition/"><u>Mastering the Art of Fixing Stuck GIFs in Discord Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-skills-and-speed-up-valorant-tips-for-top-performance/"><u>Sharpen Skills & Speed Up: Valorant Tips for Top Performance</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-dos-and-donts-of-interacting-with-youtube-viewers/"><u>The Do's and Don'ts of Interacting with YouTube Viewers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Oppo Find X7? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/tout-savoir-pour-transformer-votre-audio-m4a-en-wav-avec-lassistance-de-movavi-convertisseur/"><u>Tout Savoir Pour Transformer Votre Audio M4A en WAV Avec L'assistance De Movavi Convertisseur</u></a></li>
</ul></div>

