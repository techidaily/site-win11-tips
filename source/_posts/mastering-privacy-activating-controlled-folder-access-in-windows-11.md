---
title: "Mastering Privacy: Activating Controlled Folder Access in Windows 11"
date: 2024-08-16T02:17:38.625Z
updated: 2024-08-17T02:17:38.625Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Privacy: Activating Controlled Folder Access in Windows 11"
excerpt: "This Article Describes Mastering Privacy: Activating Controlled Folder Access in Windows 11"
keywords: Win11 Privacy Controls,Controlled Folder Access,Secure Data Access,Windows Privacy Settings,Digital Content Protection,Restricted File Sharing,Advanced Security Options
thumbnail: https://thmb.techidaily.com/95c7607cc85834758f594e36f86b8274633568f32ba37267dd79e6e802f121e2.png
---

## Mastering Privacy: Activating Controlled Folder Access in Windows 11

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

## How to Enable Controlled Folder Access With Group Policy Editor

 If you have Windows 11 Pro or Enterprise edition, you can enable controlled folder access with Group Policy Editor. Group Policy Editor also includes some extra configuration settings for controlled folder access, which is a bonus. This is how to turn on controlled folder access via GPE.

 If you're on Windows Home, the Group Policy Editor won't appear by default. Check out [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) to get around this.

1. Bring up the search tool in Windows and enter**gpedit.msc** there.
2. Select**gpedit.msc** to [bring up the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
3. Click**Computer Configuration** \>**Administrative Templates** inside Group Policy Editor’s left pane.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/computer-configuration-in-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select**Apply** in the Configure Controlled folder access window.
6. Click the Configure Controlled folder access window’s**OK** button.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
4. Click**Yes** to erase that key.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
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
<li><a href="https://fox-helps.techidaily.com/new-future-shooting-gear-ideal-cameras-musical-videography-for-2024/"><u>[New] Future Shooting Gear  Ideal Cameras Musical Videography for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-master-your-snapchats-the-top-6-editing-apps-for-both-devices-for-2024/"><u>[New] Master Your Snapchats  The Top 6 Editing Apps for Both Devices for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-crafting-visual-narratives-with-premium-text-tools-in-ae/"><u>[Updated] 2024 Approved  Crafting Visual Narratives with Premium Text Tools in AE</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-the-quick-zoomers-guide-to-clearer-instagram-narratives/"><u>[Updated] 2024 Approved  The Quick-Zoomer's Guide to Clearer Instagram Narratives</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-flippant-entry-and-exit-tips/"><u>[Updated] Flippant Entry & Exit Tips</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-step-by-step-strategy-for-unearthing-secret-youtube-videos/"><u>[Updated] In 2024, Step-by-Step Strategy for Unearthing Secret YouTube Videos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-your-guide-to-the-hottest-screen-free-android-gaming-apps/"><u>[Updated] In 2024, Your Guide to the Hottest Screen-Free Android Gaming Apps</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-symphonic-streams-exclusive-sites-for-downloadable-tones/"><u>[Updated] Symphonic Streams  Exclusive Sites for Downloadable Tones</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-methodical-path-to-discovering-hidden-youtube-footage/"><u>[Updated] The Methodical Path to Discovering Hidden YouTube Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-routines-to-pause-windows-and-office-software-updates/"><u>4 Routines to Pause Windows & Office Software Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oppo-reno-10-proplus-5g-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Oppo Reno 10 Pro+ 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://data-wizards.techidaily.com/clean-cinematography-uncompromised-quality/"><u>Clean Cinematography, Uncompromised Quality</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/combatting-freezing-while-watching-videos-post-upgrade/"><u>Combatting Freezing While Watching Videos Post-Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-right-video-coding-technique-for-win-os-users/"><u>Deciphering the Right Video Coding Technique for Win OS Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dims-masterclass-restoring-and-repairing-win11-images/"><u>DIMS Masterclass: Restoring and Repairing Win11 Images</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/discover-the-sleek-sony-lx310bt-bluetooth-player/"><u>Discover the Sleek Sony LX310BT Bluetooth Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-update-error-code-0x8024800c/"><u>Fixing Windows Update Error Code 0X8024800C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-terminal-restart-on-win11/"><u>Guiding Users Through Terminal Restart on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-install-msixbundle-and-appxappxbundle-files-from-the-microsoft-store/"><u>How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/iosandroid-sync-with-windows-server-files/"><u>IOS/Android: Sync with Windows Server Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-folder-access-inserting-into-windows-11-context-menu/"><u>Mastering Folder Access: Inserting Into Window's 11 Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-installation-of-google-play-in-w11/"><u>Mastering the Installation of Google Play in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-errors-how-to-fix-unopenable-packages/"><u>Navigating Windows Errors: How to Fix Unopenable Packages</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oneplus-nord-ce-3-5g-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>OnePlus Nord CE 3 5G Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-reviving-non-functioning-reading-aloud-in-word-2016plus/"><u>Quick Guide to Reviving Non-Functioning Reading Aloud in Word 2016+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-reset-windows-paperwork-service/"><u>Quick Reset Windows' Paperwork Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-steam-symbols-on-pc/"><u>Resetting Steam Symbols on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/separate-your-online-storage-onedrive-and-microsoft-ids/"><u>Separate Your Online Storage: OneDrive & Microsoft IDs</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-honor-90-lite-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Honor 90 Lite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-procedure-for-gpu-detection-in-windows-11/"><u>Speedy Procedure for GPU Detection in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-copy-pasting-issues-across-chrome-edge-and-firefox-on-win/"><u>Troubleshooting Copy-Pasting Issues Across Chrome, Edge, & Firefox on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-wows-fatal-issue-in-windows-1111/"><u>Troubleshooting WoW's Fatal Issue in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-best-practices-for-ping-commands/"><u>Understanding Windows: Best Practices for Ping Commands</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-perpetual-inactivity-in-windows-11s-defender-feature/"><u>Unlocking Perpetual Inactivity in Windows 11'S Defender Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-bypassing-tpm-with-rufus/"><u>Unlocking Windows 11: Bypassing TPM with Rufus</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-audio-time-travel-discovering-leading-audio-reverser-technology/"><u>Updated 2024 Approved Audio Time Travel Discovering Leading Audio Reverser Technology</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-perfect-your-playlist-a-compilation-of-elite-mp3-enhancement-services/"><u>Updated 2024 Approved Perfect Your Playlist A Compilation of Elite MP3 Enhancement Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-tips-to-safeguard-sticky-notes-on-pc/"><u>Winning Tips to Safeguard Sticky Notes on PC</u></a></li>
</ul></div>
