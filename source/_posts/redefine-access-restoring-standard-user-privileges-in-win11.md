---
title: "Redefine Access: Restoring Standard User Privileges in Win11"
date: 2024-07-12T17:26:48.924Z
updated: 2024-07-13T17:26:48.924Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Redefine Access: Restoring Standard User Privileges in Win11"
excerpt: "This Article Describes Redefine Access: Restoring Standard User Privileges in Win11"
keywords: Win11 Privacy,Standard User Controls,Redefining Security,Win11 Rights Management,Access Recovery,User Privilege Restoration,Enhanced PC Security
thumbnail: https://thmb.techidaily.com/f9dfa57d80070d52083269f7e54688cbc55bc603dffea5c52daaecde9ad2614f.jpg
---

## Redefine Access: Restoring Standard User Privileges in Win11

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
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-passcode-from-iphone-11-pro-complete-guide-drfone-by-drfone-ios/"><u>In 2024, How To Remove Passcode From iPhone 11 Pro? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-obstacles-for-secure-memory-settings-in-new-windows-11/"><u>Clearing Obstacles for Secure Memory Settings in New Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insiders-look-at-windows-boot-configuration-management/"><u>Insider's Look at Windows Boot Configuration Management</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-oppo-reno-9a-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Oppo Reno 9A? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-honor-x8b-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Honor X8b.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trimming-down-excessive-cpu-usage-in-windows-hosts/"><u>Trimming Down Excessive CPU Usage in Windows Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-error-0x80131500-on-microsoft-shop/"><u>Unlocking Error #0X80131500 on Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-camera-saving-errors/"><u>Guiding Through Windows Camera Saving Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-disconnects-and-fixes-javascript-issues-in-discord-win-11/"><u>Mastering Disconnects & Fixes: JavaScript Issues in Discord Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-storyteller-a-step-by-step-guide/"><u>Launching Windows 11'S Storyteller: A Step-by-Step Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-vidvault-seamless-techniques-for-securing-tweeted-videos/"><u>[Updated] VidVault  Seamless Techniques for Securing Tweeted Videos</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unraveling-visual-clarity-for-the-new-digital-age/"><u>[New] Unraveling Visual Clarity for the New Digital Age</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-split-screen-video-editing-made-easy-free-online-and-offline-solutions/"><u>In 2024, Split Screen Video Editing Made Easy Free Online and Offline Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-resolution-of-windows-error-1132-in-zoom/"><u>Master the Resolution of Window's Error 1132 in Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-closed-folder-issues-in-winxpxo11-on-double-click/"><u>How to Tackle Closed Folder Issues in WinXP/XO11 on Double-Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-lsassexe-unable-to-locate-error-simple-steps/"><u>Fixing 'lsass.exe' Unable to Locate Error - Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-drag-recover-lost-functionality-fast/"><u>Win11 Drag: Recover Lost Functionality Fast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-techniques-to-accelerate-steam-downloads-on-windows/"><u>Master Techniques to Accelerate Steam Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-command-center-for-app-and-browser-authority/"><u>Windows Command Center for App and Browser Authority</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-java-development-kit-setup-in-windows-11/"><u>Essential Steps to Java Development Kit Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-keyboard-commands-to-sharpen-your-3d-skills/"><u>Essential Keyboard Commands to Sharpen Your 3D Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-microsofts-phone-link-application-functionality/"><u>Decoding Microsoft's Phone Link Application Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-directories-a-breeze-with-win11-essentials/"><u>Making Directories a Breeze with Win11 Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-deletion-in-windows-11-115-chars/"><u>Mastering Software Deletion in Windows 11 (115 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-fixes-for-non-responsive-backlight-on-windows-pcs/"><u>Five Fixes for Non-Responsive Backlight on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-search-enhancements-in-windows-11-file-explorer/"><u>Visual Search Enhancements in Windows 11 File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-cleaning-for-a-functional-windows-11-space/"><u>Effortless Cleaning for a Functional Windows 11 Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-admin-restrictions-on-windows-safety-settings/"><u>Bypassing Admin Restrictions on Windows Safety Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-your-onedrive-save-point-on-windows-10/"><u>Altering Your OneDrive Save Point on Windows 10</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-mastering-lip-sync-explore-top-apps-for-dynamic-videos/"><u>Updated 2024 Approved Mastering Lip Sync Explore Top Apps for Dynamic Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-crumpled-to-curated-your-step-by-step-process-of-transforming-faded-print-photographs-into-digital-originals/"><u>In 2024, From Crumpled to Curated  Your Step-by-Step Process of Transforming Faded Print Photographs Into Digital Originals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-open-disk-management-in-windows-11-and-11/"><u>4 Ways to Open Disk Management in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-windows-applications-without-admin-rights/"><u>How to Manage Windows Applications Without Admin Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-clicking-away-how-to-instantly-load-apk-files-on-windows-11/"><u>Double-Clicking Away: How to Instantly Load APK Files on Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-mirroring-magic-how-to-flip-a-video-clip-in-final-cut-pro/"><u>Updated Mirroring Magic How to Flip a Video Clip in Final Cut Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-store-clearing-error-code-x80072f30/"><u>Troubleshoot Windows Store: Clearing Error Code X80072F30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-auto-time-zone-switches-in-microsofts-operating-system/"><u>Bypassing Auto Time Zone Switches in Microsoft's Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-tips-for-a-win11-masterpiece/"><u>Transform Your Desktop: Tips for a Win11 Masterpiece</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-windows-background-save-spot-in-11/"><u>How to Find Window's Background Save Spot in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-telnet-on-windows-11-systems/"><u>Unlocking Telnet on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fn-key-techniques-for-efficient-windows-use/"><u>Fn Key Techniques for Efficient Windows Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/dissecting-freelens-studio-a-user-perspective/"><u>Dissecting Freelens Studio  A User Perspective</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-your-worldwide-address-through-cmd-windows/"><u>Unmasking Your Worldwide Address Through CMD, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-build-custom-text-transcription-software-on-windows-with-whisper/"><u>How to Build Custom Text Transcription Software on Windows with Whisper</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-technological-splendor-m1-pro-vs-m1-max/"><u>[Updated] Exploring the Technological Splendor  M1 Pro Vs. M1 Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-method-for-heic-to-jpeg-conversion/"><u>Windows Method for Heic to Jpeg Conversion</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-accelerate-lost-snap-content-find/"><u>[New] 2024 Approved  Accelerate Lost Snap Content Find</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-uniform-iptv-system-utilization/"><u>2024 Approved  Uniform IPTV System Utilization</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-cutting-edge-5-home-movie-maker/"><u>[Updated] In 2024, Cutting-Edge 5 Home Movie Maker</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-vivo-y36-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Vivo Y36 without App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-windows-file-not-found-error/"><u>Methods to Overcome Windows 'File Not Found' Error</u></a></li>
</ul></div>
