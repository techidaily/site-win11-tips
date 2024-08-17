---
title: "Windows 11 Simplification: Recapturing Default Rights"
date: 2024-08-16T02:14:55.258Z
updated: 2024-08-17T02:14:55.258Z
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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-capturing-perfection-a-deep-dive-into-apeaksofts-technology/"><u>[New] In 2024, Capturing Perfection  A Deep Dive Into Apeaksoft's Technology</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-top-ranked-motors-the-quintessential-guide-to-flight-mastery/"><u>[New] In 2024, Top-Ranked Motors  The Quintessential Guide to Flight Mastery</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-simplifying-display-images-with-screencapture-techniques/"><u>[New] Simplifying Display Images with ScreenCapture Techniques</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-the-art-of-editing-in-garageband/"><u>[Updated] Mastering the Art of Editing in GarageBand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-simplified-techniques-to-winrm-tool/"><u>10 Simplified Techniques to WinRM Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-speedy-techniques-for-windows-control-panel/"><u>11 Speedy Techniques for Window's Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-top-windows-gear-a-comprehensive-review-list/"><u>2024'S Top Windows Gear - A Comprehensive Review List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-to-spot-signs-for-windows-reset/"><u>4 Easy-to-Spot Signs for Windows Reset?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-phased-out-features-in-current-windows-design/"><u>6 Phased-Out Features in Current Windows Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-change-windows-11-administrator-name/"><u>A Comprehensive Guide to Change Windows 11 Administrator Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-chromium-installation-in-windows-11/"><u>A Detailed Walkthrough of Chromium Installation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-restoring-your-windows-11-media-softwares-health/"><u>A Guide to Restoring Your Windows 11 Media Software's Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-towards-improved-security-extending-pins-in-oses/"><u>A Step Towards Improved Security: Extending PINs in OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-alter-program-dimensions-using-pc-keys/"><u>A Step-by-Step Guide to Alter Program Dimensions Using PC Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-bilingual-capabilities-using-windows-shortcuts/"><u>Accelerate Your Bilingual Capabilities Using Windows Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-procedure-for-windows-photo-viewer-in-win11/"><u>Activation Procedure for Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-history-misconfiguration-in-windows/"><u>Addressing File History Misconfiguration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incompatibility-between-windows-and-fingerprint-device/"><u>Addressing Incompatibility Between Windows and Fingerprint Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-old-directx-gaming-via-dxvk-powered-upgrades/"><u>Amplifying Old DirectX Gaming via DXVK-Powered Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-basics-cloning-without-external-help/"><u>Backup Basics: Cloning Without External Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-temp-in-windows-11-systems/"><u>Balancing CPU Temp in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resources-windows-task-management/"><u>Balancing Resources: Windows Task Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-the-media-playback-windows-media-player/"><u>Beginning the Media Playback: Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-alternatives-to-windows-snipping-quick-reliable-capture-techniques/"><u>Best Alternatives to Windows Snipping: Quick, Reliable Capture Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/biometric-permissions-managing-domain-users-in-w11/"><u>Biometric Permissions: Managing Domain Users in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-with-smooth-directx-downloads-and-upgrades/"><u>Boost Your PC with Smooth DirectX Downloads & Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-startup-efficiency-altering-boot-menu-delay/"><u>Boosting Startup Efficiency: Altering Boot Menu Delay</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/craft-a-signature-sound-how-to-modify-voices-for-instagram/"><u>Craft a Signature Sound  How to Modify Voices for Instagram</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-next-gen-apple-watch-ultra-model-2-comprehensive-guide-to-specs-estimated-prices-and-launch-rumors/"><u>Discover the Next-Gen Apple Watch Ultra Model 2 – Comprehensive Guide to Specs, Estimated Prices & Launch Rumors</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723007933090-fix-for-nier-repliecants-crashing-problem-smooth-playtime-now/"><u>Fix for NieR: Repliecant's Crashing Problem - Smooth Playtime Now</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-from-your-apple-iphone-14-pro-max-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID From your Apple iPhone 14 Pro Max without Security Questions?</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-essentials-for-launching-an-engaging-webcam-stream/"><u>In 2024, Essentials for Launching an Engaging Webcam Stream</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfecting-zoom-on-snapchat-for-better-snaps/"><u>In 2024, Perfecting Zoom on Snapchat for Better Snaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363450902-mastering-the-art-of-total-windows-screen-capturing-with-these-4-tips/"><u>Mastering the Art of Total Windows Screen Capturing with These 4 Tips</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/ranked-your-must-have-5-iphones-for-excellent-podcasting-for-2024/"><u>Ranked  Your Must-Have 5 iPhones for Excellent Podcasting for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-troubleshooting-eac-startup-issue-due-to-absent-easy-anti-cheat-software/"><u>Resolved: Troubleshooting EAC Startup Issue Due to Absent Easy Anti-Cheat Software</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-civi-3-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Civi 3 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
</ul></div>
