---
title: "Unleashing Normalcy: Windows 11'S Basic User Reset Guide"
date: 2024-08-16T02:13:46.317Z
updated: 2024-08-17T02:13:46.317Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unleashing Normalcy: Windows 11'S Basic User Reset Guide"
excerpt: "This Article Describes Unleashing Normalcy: Windows 11'S Basic User Reset Guide"
keywords: Win11ResetGuide,BasicUserResetWin,NormalizeWinOS,NewWindowsResetTips,WindowsBasicReset,OSNormalizationSteps,ResetWin11ForAllUsers
thumbnail: https://thmb.techidaily.com/5b41f1296863a8cc22d3a2c3dbb979d19c4362b2b1c96fbfb8d71b7193c17bd8.jpg
---

## Unleashing Normalcy: Windows 11'S Basic User Reset Guide

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-comprehensive-fb-messenger-recordings-explained/"><u>[New] In 2024, Comprehensive FB Messenger Recordings Explained</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-customize-your-social-media-screenscape/"><u>[Updated] Customize Your Social Media Screenscape</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-high-res-horizons-in-depth-analysis-of-samsung-ue590-tv/"><u>[Updated] High-Res Horizons  In-Depth Analysis of Samsung UE590 TV</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1716069025282-updated-in-2024-discover-the-best-open-worlds-today/"><u>[Updated] In 2024, Discover the Best Open Worlds Today!</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-level-streaming-tech-innovations-you-need/"><u>2024 Approved  Pro-Level Streaming Tech Innovations You Need</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-disk-distinctions-c-and-d/"><u>A Guide to Understanding Disk Distinctions (C & D)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-inactivity-in-windows-os/"><u>Addressing Taskbar Inactivity in Windows OS</u></a></li>
<li><a href="https://win-blog.techidaily.com/boost-your-gaming-experience-how-to-tackle-blurry-graphics-issues-in-cod-warzone-on-pc/"><u>Boost Your Gaming Experience: How to Tackle Blurry Graphics Issues in COD: Warzone on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-update-obstacles-with-error-code-0x800736cc/"><u>Breaking Through Windows Update Obstacles with Error Code 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-nvidia-geforce-connection-hurdle-in-win-11/"><u>Bypassing the Nvidia GeForce Connection Hurdle in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x0000011b-operation-failure-on-windows-11/"><u>Correcting 0X0000011B Operation Failure on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-mandatory-elements-alert-on-windows-10and11-os/"><u>Counteracting Mandatory Elements Alert on Windows 10&11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-how-clockdate-shows-in-window-11/"><u>Customizing How Clock/Date Shows in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-lan-access-barriers-on-winsminecraft/"><u>Dismantling LAN Access Barriers on WinsMinecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-setup-windows-11-arm-from-an-iso-file-stepwise-approach/"><u>Efficiently Setup Windows 11 ARM From an ISO File Stepwise Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-browser-copy-paste-woes-in-windows/"><u>Essential Fixes for Browser Copy-Paste Woes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-7-prime-free-password-generators-for-pcs/"><u>Explore 7 Prime Free Password Generators for PCs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/explore-the-best-ai-naming-software-for-podcasters/"><u>Explore the Best AI Naming Software for Podcasters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-explorer-3-ways-to-access-directories-on-windows-pcs/"><u>Game Explorer: 3 Ways to Access Directories on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-to-wipe-login-page-contacts/"><u>Guiding You to Wipe Login Page Contacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-into-windows-11s-silent-camera-alert-system/"><u>Hacking Into Windows 11'S Silent Camera Alert System</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-winerror-installation-fault-0xc004f050/"><u>How to Resolve WinError: Installation Fault #0XC004F050</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-poco-c55-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Poco C55 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-samsung-galaxy-z-fold-5-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Samsung Galaxy Z Fold 5 to Mac? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Tecno Pop 8? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-stability-top-photo-tripods-for-iphones-and-androids/"><u>In 2024, Ultimate Stability  Top Photo Tripods for iPhones & Androids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-law-filters-into-your-windows-workflows/"><u>Integrating LAW Filters Into Your Windows Workflows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-windows-open-eliminate-automatic-lock/"><u>Keep Windows Open: Eliminate Automatic Lock</u></a></li>
<li><a href="https://tech-hub.techidaily.com/keep-your-bot-conversations-stealthy-and-secure/"><u>Keep Your Bot Conversations Stealthy & Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-track-of-windows-shots-folders/"><u>Keeping Track of Windows Shots' Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-solving-win-os-device-errors/"><u>Navigating and Solving Win OS Device Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-screen-saver-wait-time/"><u>Optimize Windows Screen Saver Wait Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-screen-unresponsive-error-on-windows-11/"><u>Overcoming 'Screen Unresponsive' Error on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-network-hurdles-correcting-ethernet-problems-under-windows-10-and-7/"><u>Overcoming Network Hurdles: Correcting Ethernet Problems Under Windows 10 & 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-strategies-for-unlocking-store-apps-directory/"><u>Proven Strategies for Unlocking Store Apps Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-faulty-windows-11-recycle-bin-messages/"><u>Purging Faulty Windows 11 Recycle Bin Messages</u></a></li>
<li><a href="https://sound-issues.techidaily.com/realtek-hd-speaker-drivers-wont-open-here-are-the-solutions/"><u>RealTek HD Speaker Drivers Won't Open? Here Are the Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconfiguring-account-lockout-limit-post-failed-sign-in-in-windows-1011/"><u>Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-hogwarts-legacys-memory-shortage-mistake/"><u>Resolving Hogwarts Legacy's Memory Shortage Mistake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-uninstall-failure-windows-1011-access-issue/"><u>Resolving Uninstall Failure: Windows 10/11 Access Issue</u></a></li>
<li><a href="https://vp-tips.techidaily.com/simplify-your-marine-movie-projects-top-7-hacks-for-2024/"><u>Simplify Your Marine Movie Projects  Top 7 Hacks for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/smart-snip-skills-advanced-tips-for-iphone-photo-cropping-for-2024/"><u>Smart Snip Skills  Advanced Tips for iPhone Photo Cropping for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-defender-aguard-on-edge/"><u>Step-by-Step Guide to Windows 11 Defender Aguard on Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-to-preferred-pdf-viewer-on-windows/"><u>Switching to Preferred PDF Viewer on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-preference-portal-your-operating-systems-lair/"><u>The Preference Portal: Your Operating System’s Lair</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/the-ultimate-iphoneipad-video-and-image-archive/"><u>The Ultimate iPhone/iPad Video & Image Archive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-admin-managed-feature-issues-in-windows-11/"><u>Troubleshooting Admin-Managed Feature Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-windows-update-error-0x8024401c-for-windows-10-and-11-users/"><u>Troubleshooting and Fixing Windows Update Error 0X8024401c for Windows 10 & 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-winerror-0x80071a90-in-windows/"><u>Understanding & Resolving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/understanding-missing-screen-flashes/"><u>Understanding Missing Screen Flashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wintoys-unlocking-a-versatile-tool-in-windows-os/"><u>Understanding WinToys: Unlocking a Versatile Tool in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-installation-fix-for-ms-pc-manager-on-xp/"><u>Unlock Installation: Fix for MS PC Manager on XP</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Honor 90 GT? | Dr.fone</u></a></li>
</ul></div>
