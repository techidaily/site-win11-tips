---
title: Activate Data Safety with Controlled Folder Access Feature
date: 2024-08-16T01:09:45.570Z
updated: 2024-08-17T01:09:45.570Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate Data Safety with Controlled Folder Access Feature
excerpt: This Article Describes Activate Data Safety with Controlled Folder Access Feature
keywords: Data Safeguard,Secure Data,Safe Files,Access Control,File Protection,Secure Storage,Security Locks
thumbnail: https://thmb.techidaily.com/b855ebe51b5189358ef7af65d06591503136d0471619c6e6540592a14f8eb424.jpg
---

## Activate Data Safety with Controlled Folder Access Feature

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
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
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
4. Double-click**Windows Components** to expand it.
5. Click the arrows for expanding**Microsoft Defender Antivirus** and**Microsoft Defender Exploit Guard** .

1. Select**Controlled Folder Access** to view policy settings for that feature.
2. Then double-click**Configure Controlled folder access** to view that setting’s window.  
![The Controlled Folder Access policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-in-group-policy-editor.jpg)
3. Select the Configure Controlled folder access window’s**Enabled** radio button.
4. Click**Block** on the drop-down menu to select the strictest CFA mode. However, you can also select alternative**Audit Mode** ,**Block disk notification only** , and**Audit disk notification only** options for enabling controlled folder access.  
![The Configure the guard my folders feature drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configure-controlled-folder-access.jpg)
5. Select**Apply** in the Configure Controlled folder access window.
6. Click the Configure Controlled folder access window’s**OK** button.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
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
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Next, press**Ctrl** +**Shift** +**S** to view Notepad’s "Save as" window.
5. Set the**Save as type** option to**All files** .  
![The All files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/all-files-option.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

1. Type**Turn on Control folder access.reg** inside the file name box.
2. Select to save the script to the desktop location.
3. Click**Save** to add the**Turn on Control folder access** registry file to the desktop.
4. Close the Notepad editor, and double-click the**Turn on Control folder access.reg** file on the desktop.  
![The registry script confirmation dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-script-confirmation-dialog.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
5. Select the EXE (application) file for a game or other software you want to exclude from controlled folder access.
6. Click**Open** to add the selected game or software.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-tweeting-videos-to-tweenish-animations-for-no-fee/"><u>[New] 2024 Approved  Tweeting Videos to Tweenish Animations for No Fee</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-photographic-albums-with-soundscape-features/"><u>[New] Photographic Albums with Soundscape Features</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/rime-video-to-text-technology-now-in-2024/"><u>[New] Prime Video-to-Text Technology, Now, In 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unlocking-youtube-success-with-the-right-networking-choice/"><u>[New] Unlocking YouTube Success with the Right Networking Choice</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-pushing-creative-boundaries-the-power-of-magix-vpx/"><u>[Updated] 2024 Approved  Pushing Creative Boundaries  The Power of Magix VPX</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-master-the-art-of-professional-webcam-filming-for-2024/"><u>[Updated] Master the Art of Professional Webcam Filming for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-fascinating-world-of-stock-pictures-and-meme-lore/"><u>[Updated] The Fascinating World of Stock Pictures & Meme Lore</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/10-most-efficient-applications-for-total-iphone-data-deletion/"><u>10 Most Efficient Applications for Total iPhone Data Deletion</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-mastering-video-recording-camstudios-total-package/"><u>2024 Approved  Mastering Video Recording  CamStudio's Total Package</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-process-of-eliminating-security-record-in-windows/"><u>Decoding the Process of Eliminating Security Record in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/echoes-of-the-past-utilizing-windows-7-product-key-for-windows-11/"><u>Echoes of the Past: Utilizing Windows 7 Product Key for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-windows-security-bypassing-faulty-pins-easily/"><u>Enhance Windows Security: Bypassing Faulty PINs Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-sticky-notes-dont-get-lost/"><u>Ensuring Sticky Notes Don't Get Lost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-virtualbox-v70-installation-for-windows-11-users/"><u>Essential Guide: VirtualBox v7.0 Installation for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-routes-to-windows-recovery-toolkit/"><u>Essential Routes to Windows Recovery Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-to-overcome-remote-connection-errors-on-windows/"><u>Fixes to Overcome Remote Connection Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-grips-with-windows-11s-audio-settings-quickly/"><u>Getting to Grips with Windows 11'S Audio Settings Quickly</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Xiaomi Redmi K70 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-dodge-repeated-network-logon-error-messages-on-windows/"><u>How to Dodge Repeated Network Logon Error Messages on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-11-official-method-to-unlock-your-apple-iphone-11-by-drfone-ios/"><u>How To Unlock Apple iPhone 11 Official Method to Unlock Your Apple iPhone 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-stalled-excel-workflow-on-windows-devices/"><u>Jumpstart Stalled Excel Workflow on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-saved-gamer-tactics-with-launcher-backups/"><u>Mastering Saved Gamer Tactics with Launcher Backups</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/microsoft-windows-bluetooth-drivers-free-downloads-and-latest-updates-for-windows-10-11-8-and-7/"><u>Microsoft Windows Bluetooth Drivers: Free Downloads and Latest Updates for Windows 10, 11, 8, & 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-shadows-add-stealthy-menu-in-win11/"><u>Navigating the Shadows: Add Stealthy Menu in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-chrome-freeze-crash-and-blackout/"><u>Overcoming Chrome Freeze, Crash, and Blackout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-hurdles-of-windows-11s-search-functionality/"><u>Overcoming the Hurdles of Windows 11'S Search Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-overloaded-system-by-controlling-processes/"><u>Resolving Overloaded System by Controlling Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-performance-the-most-unnecessary-windows-applications/"><u>Sharpen Performance: The Most Unnecessary Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-chrome-blackout-on-a-pc/"><u>Solving Chrome Blackout on a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-w11w10-bluetooth-pin-verification-failures/"><u>Strategies to Solve W11/W10 Bluetooth PIN Verification Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-benefits-in-maintaining-your-win-11-notification-signals/"><u>The Hidden Benefits in Maintaining Your Win 11 Notification Signals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-retro-arc-of-gaming-shading-techniques-for-ancient-artifacts/"><u>The Retro Arc of Gaming: Shading Techniques for Ancient Artifacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-guide-to-fast-clickers/"><u>The Ultimate Windows Guide to Fast Clickers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-8-3d-websites-with-stunning-gold-text-visuals/"><u>Top 8 3D Websites with Stunning Gold Text Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-imminent-windows-licensing-warning/"><u>Troubleshooting Imminent Windows Licensing Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-exe-files-on-your-pc-no-more-issues/"><u>Unlock EXE Files on Your PC, No More Issues!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-dormant-pane-panes-ultimate-guide-to-win11/"><u>Unlocking Dormant Pane Panes: Ultimate Guide to Win11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-inside-clubhouse-dissecting-its-core-ethos-features-and-significance-in-the-modern-era/"><u>Updated Inside Clubhouse Dissecting Its Core Ethos, Features, and Significance in the Modern Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-key-beware-the-subtle-dangers-of-discounts/"><u>Windows Key Beware: The Subtle Dangers of Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-renewal-methods-for-driver-replacement-and-update/"><u>Windows Renewal: Methods for Driver Replacement and Update</u></a></li>
</ul></div>
