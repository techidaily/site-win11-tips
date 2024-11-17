---
title: "Reclaiming Control: Revoking Advanced Users on Windows 11"
date: 2024-11-14T20:34:33.168Z
updated: 2024-11-17T17:49:55.865Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reclaiming Control: Revoking Advanced Users on Windows 11"
excerpt: "This Article Describes Reclaiming Control: Revoking Advanced Users on Windows 11"
keywords: Win11 User Restrictions,Advanced Access Revoke,Windows 11 Limits,Gain PC Control,Disable Pro Users,Secure Win11 Settings,Control Windows Advance
thumbnail: https://thmb.techidaily.com/e9e9b7ca60047014bff6bb18f8c482a86a228fe45f3ba370acbb24c0cc43ac69.jpg
---

## Reclaiming Control: Revoking Advanced Users on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluetties.sjv.io/c/5597632/2141687/17094" target="_top" id="2141687">
  <img src="//a.impactradius-go.com/display-ad/17094-2141687" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141687/17094" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144298/7443" target="_top" id="2144298">
  <img src="//a.impactradius-go.com/display-ad/7443-2144298" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144298/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-hints.techidaily.com/2024-approved-a-complete-breakdown-lg-bp350-monitors-specifications-and-reviews/"><u>2024 Approved A Complete Breakdown LG BP350 Monitor's Specifications and Reviews</u></a></li>
<li><a href="https://blog-min.techidaily.com/8-ways-to-transfer-photos-from-vivo-s18-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>8 Ways to Transfer Photos from Vivo S18 to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/bass-management-demystified-discovering-its-role-and-functionality-in-audio-systems/"><u>Bass Management Demystified: Discovering Its Role and Functionality in Audio Systems</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/complete-setup-blueprint-for-wm6/"><u>Complete Setup Blueprint for WM6</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/eloquentaiartisan-the-ai-empowered-editor/"><u>EloquentAIArtisan The AI-Empowered Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-overcoming-microsoft-store-crashes-0x80073d26-fix/"><u>Guide to Overcoming Microsoft Store Crashes: 0X80073D26 Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/relocating-qbittorrent-on-windows-a-comprehensive-instructional-walkthrough/"><u>Relocating qBittorrent on Windows: A Comprehensive Instructional Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-the-reset-account-lockout-after-incorrect-passwords-on-windows-11/"><u>Revamping the Reset Account Lockout After Incorrect Passwords on Windows 11</u></a></li>
<li><a href="https://win-docs.techidaily.com/top-6-essential-digital-cooperation-apps-for-remote-work-success/"><u>Top 6 Essential Digital Cooperation Apps for Remote Work Success</u></a></li>
<li><a href="https://fox-blue.techidaily.com/top-tier-gaming-live-broadcast-tools-for-2024/"><u>Top-Tier Gaming Live Broadcast Tools for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-box-office-hype-films/"><u>Ultimate Box Office Hype Films</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-frozen-windows-run-logs/"><u>Unfreezing Frozen Windows Run Logs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-honor-90-gt-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Honor 90 GT Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-truth-how-to-detect-your-hard-drivessd-status-in-windows/"><u>Unveiling the Truth: How to Detect Your Hard Drive/SSD Status in Windows</u></a></li>
</ul></div>

