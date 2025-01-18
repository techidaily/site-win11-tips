---
title: "Defaults Defined: User Permission Reset Guide for Win11"
date: 2025-01-12T16:46:53.114Z
updated: 2025-01-18T17:51:16.663Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Defaults Defined: User Permission Reset Guide for Win11"
excerpt: "This Article Describes Defaults Defined: User Permission Reset Guide for Win11"
keywords: Permissions Reset Guide,Win11 User Settings,Default Permissions Restore,User Rights Reset Win,Win11 Permission Fix,Resetting Win11 Privacy,Manage Windows 11 Defaults
thumbnail: https://thmb.techidaily.com/bed3a8fbbe4c6c5bbdded3f73edc2505580ffc686720a91de941d4b85521ee34.jpg
---

## Defaults Defined: User Permission Reset Guide for Win11

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-premier-choices-8-linux-editing-tools/"><u>[Updated] 2024 Approved Premier Choices 8 Linux Editing Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-countdown-configuration-for-obs-users-a-compreenas-guide/"><u>[Updated] Countdown Configuration for OBS Users A Compreenas Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/behind-the-photo-instagram-selfie-credibility-explored-for-2024/"><u>Behind the Photo Instagram Selfie Credibility Explored for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-air-on-steam-login-woes-with-rust-and-windows-coding/"><u>Clearing the Air on Steam Login Woes with Rust & Windows Coding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directx-management-downloading-and-updating-made-simple/"><u>DirectX Management: Downloading & Updating Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-printmanagement-module-missing-on-pcs/"><u>Fixing 'PrintManagement' Module Missing on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-the-command-line-tab-in-windows-11s-task-manager/"><u>How to Add the Command Line Tab in Windows 11'S Task Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-device-not-detected-problem-fixing-error-code-24-on-windows-os/"><u>How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210258133-9786077132615-la-oracion-en-la-psicoterapia/"><u>La oración en la psicoterapia | Free Book</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionize-your-gpt-interaction-top-9-addons-revealed/"><u>Revolutionize Your GPT Interaction – Top 9 Addons Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-expunging-windows-search-graphics/"><u>Techniques for Expunging Windows Search Graphics</u></a></li>
</ul></div>

