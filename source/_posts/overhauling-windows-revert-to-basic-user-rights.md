---
title: "Overhauling Windows: Revert to Basic User Rights"
date: 2024-12-16T00:30:29.453Z
updated: 2024-12-22T02:27:13.444Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-perfecting-visual-virality-crafting-engaging-square-videos-for-2024/"><u>[New] Perfecting Visual Virality Crafting Engaging Square Videos for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-ace-the-green-screen-scene-with-these-tips/"><u>[Updated] Ace the Green Screen Scene with These Tips</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-copyright-free-online-collections-for-games/"><u>[Updated] Copyright-Free Online Collections for Games</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-revealing-the-top-10-color-enhancers-in-adobes-lightroom/"><u>[Updated] Revealing the Top 10 Color Enhancers in Adobe’s LightRoom</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/demystifying-the-408-http-status-code-why-it-happens-and-how-to-correctly-address-it/"><u>Demystifying the 408 HTTP Status Code: Why It Happens and How to Correctly Address It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dont-skip-the-savings-commit-to-regular-windows-backup/"><u>Don't Skip the Savings: Commit to Regular Windows Backup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-activate-windows-11-with-a-windows-7-key/"><u>How to Activate Windows 11 With a Windows 7 Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-other-application-uses-from-disrupting-sound/"><u>How to Stop 'Other Application Uses' From Disrupting Sound</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-sonic-layers-in-reels-weaving-audio-into-visuals/"><u>In 2024, Sonic Layers in Reels Weaving Audio Into Visuals</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-vive-headset-revolutionizes-virtual-reality-playtime/"><u>In 2024, Vive Headset Revolutionizes Virtual Reality Playtime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-managing-windows-11s-security-mechanisms/"><u>Mastery in Managing Windows 11'S Security Mechanisms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-and-solve-windows-not-found-problem/"><u>Navigate and Solve Windows Not Found Problem</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-edit-videos-like-a-pro-download-splice-for-mac/"><u>New Edit Videos Like a Pro Download Splice for Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rethink-windows-11-the-top-10-best-replacement-software/"><u>Rethink Windows 11: The Top 10 Best Replacement Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-functional-windows-11-anydesk-connection/"><u>Secure Functional Windows 11 AnyDesk Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-the-upcoming-expiry-message-on-w10-and-w11/"><u>Troubleshooting the “Upcoming Expiry” Message on W10 & W11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-unlocking-full-potential-of-your-windows-speakers-three-free-volume-booster-tactics/"><u>Updated In 2024, Unlocking Full Potential of Your Windows Speakers – Three Free Volume Booster Tactics</u></a></li>
<li><a href="https://youtube-web.techidaily.com/zing-jump-cuts-to-amplify-your-vlog-impact/"><u>Utilizing Jump Cuts to Amplify Your Vlog Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-high-resolution-quests-expert-techniques-for-playing-classics-in-hd-on-windows/"><u>Winning at High-Resolution Quests: Expert Techniques for Playing Classics in HD on Windows</u></a></li>
</ul></div>

