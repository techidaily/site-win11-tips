---
title: Step-by-Step Guide to Activate Folder Restrictions in Windows
date: 2024-08-16T02:27:02.659Z
updated: 2024-08-17T02:27:02.659Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide to Activate Folder Restrictions in Windows
excerpt: This Article Describes Step-by-Step Guide to Activate Folder Restrictions in Windows
keywords: Windows Folder Control,Enable Protection,Restricting Folders,Secure Windows Paths,Folder Permission Guide,Activate Folder Lock,Manage Windows Safety
thumbnail: https://thmb.techidaily.com/919428e7eabfca4b711aa4a4cd51f4e93cb7908e27ba9c3d55f238a99b357fbb.jpg
---

## Step-by-Step Guide to Activate Folder Restrictions in Windows

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

## How to Turn on Controlled Folder Access With PowerShell

 Windows PowerShell gives you an alternative method to enable and disable controlled folder access by executing commands. You can turn on controlled folder access with PowerShell as follows:

1. To activate a file search tool, press**Win + S** .
2. Input**PowerShell** within the activated search utility.
3. Open PowerShell in an elevated mode by selecting**Run as administrator** .
4. To enable controlled folder access, input this command text and hit**Enter** :  
`Set-MpPreference -EnableControlledFolderAccess Enabled`  
![The enable controlled folder access command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-controlled-folder-access-command.jpg)
5. You can disable controlled folder access by executing this command:  
`Set-MpPreference -EnableControlledFolderAccess Disabled`

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## How to Enable Controlled Folder Access With Group Policy Editor

 If you have Windows 11 Pro or Enterprise edition, you can enable controlled folder access with Group Policy Editor. Group Policy Editor also includes some extra configuration settings for controlled folder access, which is a bonus. This is how to turn on controlled folder access via GPE.

 If you're on Windows Home, the Group Policy Editor won't appear by default. Check out [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) to get around this.

1. Bring up the search tool in Windows and enter**gpedit.msc** there.
2. Select**gpedit.msc** to [bring up the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
3. Click**Computer Configuration** \>**Administrative Templates** inside Group Policy Editor’s left pane.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/computer-configuration-in-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
4. Double-click**Windows Components** to expand it.
5. Click the arrows for expanding**Microsoft Defender Antivirus** and**Microsoft Defender Exploit Guard** .

1. Select**Controlled Folder Access** to view policy settings for that feature.
2. Then double-click**Configure Controlled folder access** to view that setting’s window.  
![The Controlled Folder Access policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-in-group-policy-editor.jpg)
3. Select the Configure Controlled folder access window’s**Enabled** radio button.
4. Click**Block** on the drop-down menu to select the strictest CFA mode. However, you can also select alternative**Audit Mode** ,**Block disk notification only** , and**Audit disk notification only** options for enabling controlled folder access.  
![The Configure the guard my folders feature drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configure-controlled-folder-access.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
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
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
4. Next, press**Ctrl** +**Shift** +**S** to view Notepad’s "Save as" window.
5. Set the**Save as type** option to**All files** .  
![The All files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/all-files-option.jpg)

1. Type**Turn on Control folder access.reg** inside the file name box.
2. Select to save the script to the desktop location.
3. Click**Save** to add the**Turn on Control folder access** registry file to the desktop.
4. Close the Notepad editor, and double-click the**Turn on Control folder access.reg** file on the desktop.  
![The registry script confirmation dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-script-confirmation-dialog.jpg)
5. Select**Yes** to confirm you trust the script.

 Now you can enable controlled folder access from the Windows context menu.

 Right-click any clear area of the desktop and select**Show more options** on Windows' context menu. Move the cursor over the**Turn On or Off Control** **folder access** submenu. Click**Turn on Control folder access** to enable that Windows Security feature.

 If you ever want to remove the controlled folder access context menu option, you can do so by deleting the registry key for it. This is how to delete the key for the**Turn On or Off Control folder access** submenu:

1. Launch the Registry Editor (our guide for [opening the Regedit registry app](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods).
2. Go to this registry key location:  
`HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess`
3. Right-click the Controlled Folder Access key to select**Delete** .  
![The Delete key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-option-for-registry-key.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
4. Click**Yes** to erase that key.

## How to Set Controlled Folder Access Exceptions

 The problem with controlled folder access is that it can stop legitimate apps from accessing required files when they need to. That can be an especially big issue for Windows gaming since untrusted games often can’t save progress with controlled folder access enabled. In-game settings can also reset when that feature is turned on.

 Fortunately, controlled folder access has an exclusion (exception) list for adding trusted apps. It won’t block any trusted apps on that list from modifying files within protected folders. You can add software to the CFA exclusion list as follows:

1. Bring up the**Controlled folder access** setting in Windows Security as covered in steps one to three of the first method above.
2. Click the **Allow an app through Controlled folder access navigation** link.
3. Press the**\+ Add an allowed app** button.  
![The Add an allowed app button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-an-allowed-app.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
4. Click**Browse all** **apps** on the menu that appears.  
![The Browse all apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/browse-all-apps-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select the EXE (application) file for a game or other software you want to exclude from controlled folder access.
6. Click**Open** to add the selected game or software.

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
<li><a href="https://extra-skills.techidaily.com/updated-non-google-augmented-reality-visual-aids/"><u>[Updated] Non-Google Augmented Reality Visual Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-the-control-panel-on-windows/"><u>11 Ways to Open the Control Panel on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-copy-file-and-folder-paths-in-windows-11/"><u>6 Ways to Copy File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/a-compreayers-guide-to-smooth-and-clear-xbox-screen-recordings-for-2024/"><u>A Compreayer’s Guide to Smooth and Clear Xbox Screen Recordings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-beginning-navigating-3-reset-routes/"><u>A Fresh Windows Beginning: Navigating 3 Reset Routes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-eliminate-hardware-detection-faults/"><u>A Quick Guide to Eliminate Hardware Detection Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-management-with-seamless-multi-folder-crafting-on-windows-pcs/"><u>Accelerate File Management with Seamless Multi-Folder Crafting on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-access-boosting-morning-routine-and-note-openings/"><u>Accelerated Access: Boosting Morning Routine & Note Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-recently-used-windows-with-ease/"><u>Accessing Recently Used Windows with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-clipchamp-integration-windows-11-setup-solved/"><u>Achieve ClipChamp Integration: Windows 11 Setup Solved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-performance-with-powertoys-win11/"><u>Achieving Optimal Performance with PowerToys (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-directx-update-problems-in-windows-os/"><u>Addressing DirectX Update Problems in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-installation-privilege-issue-on-win-1011/"><u>Addressing Insufficient Installation Privilege Issue on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-icon-glitches-in-win-108/"><u>Addressing Taskbar Icon Glitches in Win 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tactics-for-superior-windows-navigation-eliminating-ls/"><u>Advanced Tactics for Superior Windows Navigation: Eliminating LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amend-f-key-malfunctions-restore-control-in-windows-11/"><u>Amend: F Key Malfunctions - Restore Control in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/antivirus-alert-7-significant-windows-functions-under-scrutiny/"><u>Antivirus Alert: 7 Significant Windows Functions Under Scrutiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-some-websites-not-opening-in-any-browser-on-windows-7-ways-to-fix-it/"><u>Are Some Websites Not Opening in Any Browser on Windows? 7 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-deadlock-in-windows-desktop-menu-navigation/"><u>Avoiding Deadlock in Windows Desktop Menu Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-high-temperature-troubleshooting-tips-w11/"><u>Avoiding High-Temperature Troubleshooting Tips: W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-termination-messages-in-roblox-games/"><u>Avoiding Unwanted Termination Messages in Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windowed-app-movement-windows-task-managing-tips/"><u>Avoiding Windowed App Movement: Windows Task Managing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11-lock-screen-effortlessly/"><u>Avoiding Windows 11 Lock Screen Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-black-glare-from-window-8-displays/"><u>Banishing the Black Glare From Window 8 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-video-transformers-from-the-world-of-windows/"><u>Best Video Transformers From the World of Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-code-ai-reshaping-windows-tech-landscape/"><u>Beyond Code: AI Reshaping Windows Tech Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-setting-up-automatic-deletions-in-win11/"><u>Boost Productivity: Setting Up Automatic Deletions in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-management-via-cmd/"><u>Boost Your System Management via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-on-windows-11-top-seven-tweaks-for-game-enthusiasts/"><u>Boosting Performance on Windows 11: Top Seven Tweaks for Game Enthusiasts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cant-print-your-pdf-these-simple-tips-will-help-you-succeed/"><u>Can't Print Your PDF? These Simple Tips Will Help You Succeed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363006980-discover-solutions-for-programs-that-dont-work-on-vistawindows-7/"><u>Discover Solutions for Programs that Don't Work on Vista/Windows 7</u></a></li>
<li><a href="https://buynow-info.techidaily.com/experience-247-wellness-monitoring-with-garmin-venu-your-ultimate-activity-tracker/"><u>Experience 24/7 Wellness Monitoring with Garmin Venu: Your Ultimate Activity Tracker</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-solve-the-minecraft-is-outdated-message-by-updating-graphics-card-driver/"><u>How to Solve the 'Minecraft Is Outdated' Message by Updating Graphics Card Driver</u></a></li>
<li><a href="https://win-solutions.techidaily.com/immortals-of-heroes-fenyx-rising-release-date-confirmed-issue-resolved/"><u>Immortals of Heroes: Fenyx Rising Release Date Confirmed - Issue Resolved</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-itel-p55-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Itel P55</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-honor-magic5-ultimate-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Honor Magic5 Ultimate to New Android? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfecting-cinematography-using-luts-for-polished-colors/"><u>In 2024, Perfecting Cinematography  Using Luts for Polished Colors</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-hp-laserjet-p1nsiiii-m399a-driver-downloads-and-updates-for-windows-pcs/"><u>Latest HP LaserJet P1nsiiii M399a Driver Downloads & Updates for Windows PCs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/picture-perfect-creating-screenshots-in-windows/"><u>Picture Perfect  Creating Screenshots in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722889361116-winxp-haldll-not-found-heres-your-step-by-step-fix/"><u>WinXP Hal.dll Not Found? Here's Your Step-by-Step Fix!</u></a></li>
</ul></div>
