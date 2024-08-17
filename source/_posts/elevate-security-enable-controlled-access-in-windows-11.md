---
title: "Elevate Security: Enable Controlled Access in Windows 11"
date: 2024-08-16T02:46:59.927Z
updated: 2024-08-17T02:46:59.927Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Elevate Security: Enable Controlled Access in Windows 11"
excerpt: "This Article Describes Elevate Security: Enable Controlled Access in Windows 11"
keywords: Secure Windows 11 Entry,Controlled Windows Access,Elevate Win11 Protection,Advanced User Controls Win,Win11 Security Gateway,Enhance Win11 Safety,Stronger Windows Permission
thumbnail: https://thmb.techidaily.com/633f0a6d177df3d7fb477a15a0804c21edff9926ab23c2607a0458a0d217d945.jpeg
---

## Elevate Security: Enable Controlled Access in Windows 11

 Controlled folder access is a feature of the Windows Security antivirus app on Microsoft desktop platforms. That feature forestalls ransomware by preventing modifications to files in protected folders. Enabling controlled folder access prevents untrusted apps, malware or otherwise, from changing files within protected directories.

 Controlled folder access is an extra security feature in Windows 10 and 11 that some users appreciate. Ransomware isn’t something to be taken lightly, and enabling that feature will keep system and user files extra safe. These are four ways you can enable controlled folder access in Windows.

## How to Turn On Controlled Folder Access in Windows Security

 The Controlled folder access setting is buried within ransomware protection in the Windows Security app. However, it’s easy to find and turn that option on/off when you know where it is. This is how to turn on the Windows Security’s app Controlled folder access option.

1. To view the Windows Security app, double-click its shield system tray icon.
2. Select Windows Security’s**Virus & threat protection** tab.  
![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manage-ransomware-option.jpg)
3. Click**Manage ransomware protection** to reach the**Controlled folder access** setting.  
![The Controlled folder access option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access.jpg)
4. Now turn on the**Controlled folder access** option to enable that feature.

 Controlled folder access protects your Documents, Videos, Pictures, and Music user folders when enabled. To view the list of protected user directories, click**Protected folder** . You can add more to the list by clicking the**Add protected folder** button, choosing a directory, and clicking**Select Folder** .

![The Add a protected folder button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-a-protected-folder-button.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## How to Turn on Controlled Folder Access With PowerShell

 Windows PowerShell gives you an alternative method to enable and disable controlled folder access by executing commands. You can turn on controlled folder access with PowerShell as follows:

1. To activate a file search tool, press**Win + S** .
2. Input**PowerShell** within the activated search utility.
3. Open PowerShell in an elevated mode by selecting**Run as administrator** .
4. To enable controlled folder access, input this command text and hit**Enter** :  
`Set-MpPreference -EnableControlledFolderAccess Enabled`  
![The enable controlled folder access command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-controlled-folder-access-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
5. You can disable controlled folder access by executing this command:  
`Set-MpPreference -EnableControlledFolderAccess Disabled`

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable Controlled Folder Access With Group Policy Editor

 If you have Windows 11 Pro or Enterprise edition, you can enable controlled folder access with Group Policy Editor. Group Policy Editor also includes some extra configuration settings for controlled folder access, which is a bonus. This is how to turn on controlled folder access via GPE.

 If you're on Windows Home, the Group Policy Editor won't appear by default. Check out[how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) to get around this.

1. Bring up the search tool in Windows and enter**gpedit.msc** there.
2. Select**gpedit.msc** to[bring up the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
3. Click**Computer Configuration** \>**Administrative Templates** inside Group Policy Editor’s left pane.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/computer-configuration-in-group-policy-editor.jpg)
4. Double-click**Windows Components** to expand it.
5. Click the arrows for expanding**Microsoft Defender Antivirus** and**Microsoft Defender Exploit Guard** .

1. Select**Controlled Folder Access** to view policy settings for that feature.
2. Then double-click**Configure Controlled folder access** to view that setting’s window.  
![The Controlled Folder Access policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-in-group-policy-editor.jpg)
3. Select the Configure Controlled folder access window’s**Enabled** radio button.
4. Click**Block** on the drop-down menu to select the strictest CFA mode. However, you can also select alternative**Audit Mode** ,**Block disk notification only** , and**Audit disk notification only** options for enabling controlled folder access.  
![The Configure the guard my folders feature drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configure-controlled-folder-access.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
5. Select**Apply** in the Configure Controlled folder access window.
6. Click the Configure Controlled folder access window’s**OK** button.

## How to Turn on Controlled Folder Access From the Windows Context Menu

 Alternatively, you can create a context menu shortcut for enabling/disabling controlled folder access. Then you’ll be able to access a Turn on Control folder access setting directly from the desktop area of Windows. You can add such a CFA option to the right-click menu by setting up and running a registry script like this:

1. Open Notepad.
2. Then select this script text, and press the**Ctrl** +**C** key combination:  
`Windows Registry Editor Version 5.00  

 ; Created by: Shawn Brink  

 ; Created on: July 19th 2018  

 ; Tutorial: <https://www.tenforums.com/tutorials/114389-add-turn-off-controlled-folder-access-context-menu-windows-10-a.html>  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess]  

 "HasLUAShield"=""  

 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  

 "MUIVerb"="Turn On or Off Control folder access"  

 "Position"="Bottom"  

 "SubCommands"=""  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\001flyout]  

 "MUIVerb"="Turn on Control folder access"  

 "HasLUAShield"=""  

 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\001flyout\command]  

 @="PowerShell -windowstyle hidden -Command \"Start-Process cmd -ArgumentList '/s,/c,start PowerShell.exe Set-MpPreference -EnableControlledFolderAccess Enabled' -Verb RunAs\""  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\002flyout]  

 "MUIVerb"="Turn off Control folder access"  

 "HasLUAShield"=""  

 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  

 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\002flyout\command]  

 @="PowerShell -windowstyle hidden -Command \"Start-Process cmd -ArgumentList '/s,/c,start PowerShell.exe Set-MpPreference -EnableControlledFolderAccess Disabled' -Verb RunAs\""`
3. Paste that script into Notepad by clicking in that app’s window and pressing**Ctrl** +**V** .  
![The controlled folder access registry script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-registry-script.jpg)
4. Next, press**Ctrl** +**Shift** +**S** to view Notepad’s "Save as" window.
5. Set the**Save as type** option to**All files** .  
![The All files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/all-files-option.jpg)

1. Type**Turn on Control folder access.reg** inside the file name box.
2. Select to save the script to the desktop location.
3. Click**Save** to add the**Turn on Control folder access** registry file to the desktop.
4. Close the Notepad editor, and double-click the**Turn on Control folder access.reg** file on the desktop.  
![The registry script confirmation dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-script-confirmation-dialog.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
5. Select**Yes** to confirm you trust the script.

 Now you can enable controlled folder access from the Windows context menu.

 Right-click any clear area of the desktop and select**Show more options** on Windows' context menu. Move the cursor over the**Turn On or Off Control** **folder access** submenu. Click**Turn on Control folder access** to enable that Windows Security feature.

 If you ever want to remove the controlled folder access context menu option, you can do so by deleting the registry key for it. This is how to delete the key for the**Turn On or Off Control folder access** submenu:

1. Launch the Registry Editor (our guide for[opening the Regedit registry app](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods).
2. Go to this registry key location:  
`HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess`
3. Right-click the Controlled Folder Access key to select**Delete** .  
![The Delete key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-option-for-registry-key.jpg)
4. Click**Yes** to erase that key.

## How to Set Controlled Folder Access Exceptions

 The problem with controlled folder access is that it can stop legitimate apps from accessing required files when they need to. That can be an especially big issue for Windows gaming since untrusted games often can’t save progress with controlled folder access enabled. In-game settings can also reset when that feature is turned on.

 Fortunately, controlled folder access has an exclusion (exception) list for adding trusted apps. It won’t block any trusted apps on that list from modifying files within protected folders. You can add software to the CFA exclusion list as follows:

1. Bring up the**Controlled folder access** setting in Windows Security as covered in steps one to three of the first method above.
2. Click the **Allow an app through Controlled folder access navigation** link.
3. Press the**\+ Add an allowed app** button.  
![The Add an allowed app button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-an-allowed-app.jpg)
4. Click**Browse all** **apps** on the menu that appears.  
![The Browse all apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/browse-all-apps-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select the EXE (application) file for a game or other software you want to exclude from controlled folder access.
6. Click**Open** to add the selected game or software.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Enable Controlled Folder Access for Greater Ransomware Protection

 Turning on controlled folder access in Windows 10 and 11 with the above methods will give files on your PC an extra layer of protection from malware. It makes little difference how you enable that feature, but you can select more configuration options by using Group Policy Editor. Adding controlled folder access context menu settings also gives you a more direct way to toggle that feature on/off as required.

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
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-step-by-step-rewinding-snapchat-videos/"><u>[Updated] In 2024, Step-by-Step  Rewinding Snapchat Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-mastering-clear-webcam-footage-recording-and-editing-tips/"><u>[Updated] Mastering Clear Webcam Footage  Recording & Editing Tips</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-phantasm-captures-action-tech-diary/"><u>[Updated] Phantasm Captures  Action Tech Diary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-disk-distinctions-c-and-d/"><u>A Guide to Understanding Disk Distinctions (C & D)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-inactivity-in-windows-os/"><u>Addressing Taskbar Inactivity in Windows OS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/advanced-users-techniques-for-effective-macscreencasting-for-2024/"><u>Advanced Users Techniques for Effective MacScreencasting for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/amplify-your-wifi-game-with-netgears-advanced-nighthawk-x6s-extender/"><u>Amplify Your WiFi Game with Netgear's Advanced Nighthawk X6S Extender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-update-obstacles-with-error-code-0x800736cc/"><u>Breaking Through Windows Update Obstacles with Error Code 0X800736CC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-your-iphone-14-pro-max-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From your iPhone 14 Pro Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-failed-file-creation-on-11-camera-app/"><u>Bypassing Failed File Creation on 11 Camera App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-valorants-audio-sync-on-microsoft-devices/"><u>Correcting Valorant's Audio Sync on Microsoft Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-how-clockdate-shows-in-window-11/"><u>Customizing How Clock/Date Shows in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-the-haze-9-tips-for-crystal-clear-pc-monitors/"><u>Cutting Through the Haze: 9 Tips for Crystal-Clear PC Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disguised-delayers-innocuous-apps-hindering-pc-speed/"><u>Disguised Delayers: Innocuous Apps Hindering PC Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-lan-access-barriers-on-winsminecraft/"><u>Dismantling LAN Access Barriers on WinsMinecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719366220535-effortless-assistance-for-your-common-windows-complaints/"><u>Effortless Assistance for Your Common Windows Complaints!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-note-clarity-obsidian-canvas-methods/"><u>Enhancing Note Clarity: Obsidian Canvas Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-browser-copy-paste-woes-in-windows/"><u>Essential Fixes for Browser Copy-Paste Woes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-7-prime-free-password-generators-for-pcs/"><u>Explore 7 Prime Free Password Generators for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-uninstallreinstall-issues-for-windows-store/"><u>Fix Uninstall/Reinstall Issues for Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-setting-up-a-taskbar-on-windows-11-tablets/"><u>Guide to Setting Up a Taskbar on Windows 11 Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-to-wipe-login-page-contacts/"><u>Guiding You to Wipe Login Page Contacts</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-tecno-spark-20-pro-by-drfone-android/"><u>How to Bypass FRP from Tecno Spark 20 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-device-access-after-encountering-error-22-in-windows-11/"><u>How to Unlock Device Access After Encountering Error 22 in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-honor-magic-6-pro-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Honor Magic 6 Pro Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streamline-your-content-with-these-20-essential-youtube-hacks/"><u>In 2024, Streamline Your Content with These 20 Essential YouTube Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-windows-open-eliminate-automatic-lock/"><u>Keep Windows Open: Eliminate Automatic Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-track-of-windows-shots-folders/"><u>Keeping Track of Windows Shots' Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-solving-win-os-device-errors/"><u>Navigating and Solving Win OS Device Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-like-a-pro/"><u>Navigating Windows Like a Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-screen-saver-wait-time/"><u>Optimize Windows Screen Saver Wait Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-video-from-mkv-to-mp4-on-windows-pcs/"><u>Optimizing Video: From MKV to MP4 on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-screen-unresponsive-error-on-windows-11/"><u>Overcoming 'Screen Unresponsive' Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-strategies-for-unlocking-store-apps-directory/"><u>Proven Strategies for Unlocking Store Apps Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-faulty-windows-11-recycle-bin-messages/"><u>Purging Faulty Windows 11 Recycle Bin Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-rockalldlldll-disappearance-issue-windows/"><u>Rectifying Rockalldll.dll Disappearance Issue (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-hogwarts-legacys-memory-shortage-mistake/"><u>Resolving Hogwarts Legacy's Memory Shortage Mistake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-uninstall-failure-windows-1011-access-issue/"><u>Resolving Uninstall Failure: Windows 10/11 Access Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-defender-aguard-on-edge/"><u>Step-by-Step Guide to Windows 11 Defender Aguard on Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-to-preferred-pdf-viewer-on-windows/"><u>Switching to Preferred PDF Viewer on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-code-0x80070570-file-corruption-in-windows-11/"><u>Troubleshooting Code 0X80070570 File Corruption in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-winerror-0x80071a90-in-windows/"><u>Understanding & Resolving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wintoys-unlocking-a-versatile-tool-in-windows-os/"><u>Understanding WinToys: Unlocking a Versatile Tool in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unified-tech-experience-windows-pc-and-galaxy-device-flow/"><u>Unified Tech Experience – Windows PC & Galaxy Device Flow</u></a></li>
</ul></div>
