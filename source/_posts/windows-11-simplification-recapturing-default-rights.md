---
title: "Windows 11 Simplification: Recapturing Default Rights"
date: 2024-06-25T16:26:20.305Z
updated: 2024-06-26T16:26:20.305Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Simplification: Recapturing Default Rights"
excerpt: "This Article Describes Windows 11 Simplification: Recapturing Default Rights"
keywords: Windows 11 Ease,Win11 Defaults,Simplify Win11,Retrieve Win11,Win11 Rights,Easy Win11 Setup,Restore Win11 Basics
thumbnail: https://thmb.techidaily.com/99663f80a681577ef6d172804500e3555c286bc17d7a19ae0d763067c374fc29.jpg
---

## Windows 11 Simplification: Recapturing Default Rights

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

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
<li><a href="https://win11-tips.techidaily.com/simplifying-git-operations-github-desktop-and-windows-11-explained/"><u>Simplifying Git Operations: GitHub Desktop and Windows 11 Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-disabled-troubleshooters-in-modern-windows/"><u>Resolving Disabled Troubleshooters in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disguised-delayers-innocuous-apps-hindering-pc-speed/"><u>Disguised Delayers: Innocuous Apps Hindering PC Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-management-adding-this-pc-to-windows-desktop/"><u>Window Management: Adding 'This PC' To Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-insufficient-access-during-uninstall/"><u>Steps to Overcome Insufficient Access During Uninstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-smart-adjustments-color-control-in-win11-apps/"><u>Enabling Smart Adjustments: Color Control in Win11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-local-security-not-functioning-warning/"><u>Immediate Actions for 'Local Security Not Functioning' Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-to-know-your-characters-on-windows-11/"><u>Get to Know Your Characters on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-workshop-generating-and-deciphering-system-insights/"><u>The Windows Workshop: Generating & Deciphering System Insights</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-master-the-art-of-cutting-a-video-editors-handbook-for-instagram/"><u>2024 Approved  Master the Art of Cutting  A Video Editor's Handbook for Instagram</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-vivo-t2-5g-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Vivo T2 5G Back to Operation | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-shutterbug-secrets-iphone-night-photography/"><u>[New] 2024 Approved  Shutterbug Secrets  IPhone Night Photography</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-10-apps-to-boost-audio-velocity/"><u>[Updated] Ultimate 10 Apps to Boost Audio Velocity</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-18-tips-for-free-online-event-streaming-techniques/"><u>In 2024, 18 Tips for Free Online Event Streaming Techniques</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-vivo-s17-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-expert-techniques-for-effective-social-sharing-via-pins/"><u>[Updated] 2024 Approved  Expert Techniques for Effective Social Sharing via Pins</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-iphone-8-plus-could-not-be-activatedreached-issue-by-drfone-ios/"><u>In 2024, How To Fix iPhone 8 Plus Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-diy-dynamics-unlock-creative-animation-potential/"><u>[Updated] In 2024, DIY Dynamics  Unlock Creative Animation Potential</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-smaller-is-better-top-drone-brands-reviewed/"><u>[Updated] Smaller Is Better  Top Drone Brands Reviewed</u></a></li>
</ul></div>
