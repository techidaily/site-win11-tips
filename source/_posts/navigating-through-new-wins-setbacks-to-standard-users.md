---
title: "Navigating Through New Wins: Setbacks to Standard Users"
date: 2024-12-18T04:05:41.004Z
updated: 2024-12-22T04:56:59.454Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Through New Wins: Setbacks to Standard Users"
excerpt: "This Article Describes Navigating Through New Wins: Setbacks to Standard Users"
keywords: Win Navigation Tips,Dealing with Setbacks,User Experience Challenges,Navigational Strategies,Overcoming New Hurdles,Standard Users' Adaptation,Enhancing User Routines
thumbnail: https://thmb.techidaily.com/757021be603bb0b62889fcb3393264ba25afdf3ad53016173b55a4a0650b3071.jpg
---

## Navigating Through New Wins: Setbacks to Standard Users

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-crafting-the-future-workplace-with-vr-technology/"><u>[New] Crafting the Future Workplace with VR Technology</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-editscreen-pro-windows-8-for-2024/"><u>[New] EditScreen Pro Windows 8 for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/44cm44kk44oz44k544k44kw44op44og44oq44o844or5yuv55s744gu44oa44km44oz44ot44o844oj5pa55rov77ya44oi44od44ox77ys44og44kv44ol44od44kv44cn/"><u>「インスタグラムリール動画のダウンロード方法：トップ２テクニック」</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-audiovisual-format-fusion-srt-to-ttml-and-ssa-mastery/"><u>2024 Approved Audiovisual Format Fusion SRT to TTML & SSA Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-fixes-for-the-common-spotify-errors-on-win11/"><u>Easy Fixes for the Common Spotify Errors on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reintroduce-blocked-app-in-os/"><u>How to Reintroduce Blocked App in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-oversaturated-color-from-laptop-display/"><u>How to Remove Oversaturated Color From Laptop Display</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-instagrams-unusual-video-display-the-explanation/"><u>In 2024, Instagram's Unusual Video Display The Explanation</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-spoofing-life360-how-to-do-it-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>In 2024, Spoofing Life360 How to Do it on Nokia C300? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-tackling-windows-steam-restrictions/"><u>Mastery in Tackling Windows' Steam Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-data-storage-utilizing-diskusage-command-proficiency/"><u>Mastery Over Data Storage: Utilizing DiskUsage Command Proficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-help-desk-center/"><u>Quick Guide: Unlocking Windows' Help Desk Center</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-motorola-moto-e13-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Motorola Moto E13</u></a></li>
<li><a href="https://driver-install.techidaily.com/the-ultimate-guide-to-reinstalling-printer-drivers/"><u>The Ultimate Guide to Reinstalling Printer Drivers</u></a></li>
<li><a href="https://youtube-web.techidaily.com/years-unexpected-cinematic-gems/"><u>This Year's Unexpected Cinematic Gems</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-ranking-nintendo-switch-gear-and-peripherals/"><u>Top-Ranking Nintendo Switch Gear and Peripherals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-code-xc0f1103f-with-geforce-now/"><u>Troubleshooting Error Code Xc0f1103f with GeForce Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/user-perspective-on-common-issues-with-windows-11/"><u>User Perspective on Common Issues with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-arm-setup-from-iso-file-to-operational-system/"><u>Windows 11 ARM Setup: From ISO File to Operational System</u></a></li>
</ul></div>

