---
title: "Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks."
date: 2024-08-16T01:52:02.928Z
updated: 2024-08-17T01:52:02.928Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks."
excerpt: "This Article Describes Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks."
keywords: Drone Safety Features,Risk Mitigation Drones,Collision Avoidance Tech,Redundant System Safety,Pre-Flight Check Procedures,Advanced Drone Tech,Flight Operation Security
thumbnail: https://thmb.techidaily.com/3a086eb5f8446de2870210890acaafe476fc2c59adb7aa3e00420e9a95422cb6.jpg
---

## Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks.

 Controlled folder access is a feature of the Windows Security antivirus app on Microsoft desktop platforms. That feature forestalls ransomware by preventing modifications to files in protected folders. Enabling controlled folder access prevents untrusted apps, malware or otherwise, from changing files within protected directories.

 Controlled folder access is an extra security feature in Windows 10 and 11 that some users appreciate. Ransomware isn’t something to be taken lightly, and enabling that feature will keep system and user files extra safe. These are four ways you can enable controlled folder access in Windows.

##  How to Turn On Controlled Folder Access in Windows Security

 The Controlled folder access setting is buried within ransomware protection in the Windows Security app. However, it’s easy to find and turn that option on/off when you know where it is. This is how to turn on the Windows Security’s app Controlled folder access option.

1. To view the Windows Security app, double-click its shield system tray icon.
2. Select Windows Security’s**Virus & threat protection** tab.  
![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manage-ransomware-option.jpg)
3. Click**Manage ransomware protection** to reach the**Controlled folder access** setting.  
![The Controlled folder access option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access.jpg)
4. Now turn on the**Controlled folder access** option to enable that feature.

 Controlled folder access protects your Documents, Videos, Pictures, and Music user folders when enabled. To view the list of protected user directories, click**Protected folder** . You can add more to the list by clicking the**Add protected folder** button, choosing a directory, and clicking**Select Folder** .

![The Add a protected folder button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-a-protected-folder-button.jpg) 

##  How to Turn on Controlled Folder Access With PowerShell

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
##  How to Enable Controlled Folder Access With Group Policy Editor

 If you have Windows 11 Pro or Enterprise edition, you can enable controlled folder access with Group Policy Editor. Group Policy Editor also includes some extra configuration settings for controlled folder access, which is a bonus. This is how to turn on controlled folder access via GPE.

 If you're on Windows Home, the Group Policy Editor won't appear by default. Check out [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) to get around this.

1. Bring up the search tool in Windows and enter**gpedit.msc** there.
2. Select**gpedit.msc** to [bring up the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
3. Click**Computer Configuration** \>**Administrative Templates** inside Group Policy Editor’s left pane.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/computer-configuration-in-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
4. Double-click**Windows Components** to expand it.
5. Click the arrows for expanding**Microsoft Defender Antivirus** and**Microsoft Defender Exploit Guard** .

1. Select**Controlled Folder Access** to view policy settings for that feature.
2. Then double-click**Configure Controlled folder access** to view that setting’s window.  
![The Controlled Folder Access policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-in-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Select the Configure Controlled folder access window’s**Enabled** radio button.
4. Click**Block** on the drop-down menu to select the strictest CFA mode. However, you can also select alternative**Audit Mode** ,**Block disk notification only** , and**Audit disk notification only** options for enabling controlled folder access.  
![The Configure the guard my folders feature drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configure-controlled-folder-access.jpg)
5. Select**Apply** in the Configure Controlled folder access window.
6. Click the Configure Controlled folder access window’s**OK** button.

##  How to Turn on Controlled Folder Access From the Windows Context Menu

 Alternatively, you can create a context menu shortcut for enabling/disabling controlled folder access. Then you’ll be able to access a Turn on Control folder access setting directly from the desktop area of Windows. You can add such a CFA option to the right-click menu by setting up and running a registry script like this:

1. Open Notepad.
2. Then select this script text, and press the**Ctrl** +**C** key combination:  
`Windows Registry Editor Version 5.00  
     
    
 ; Created by: Shawn Brink  
    
 ; Created on: July 19th 2018  
    
 ; Tutorial: https://www.tenforums.com/tutorials/114389-add-turn-off-controlled-folder-access-context-menu-windows-10-a.html  
     
    
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
4. Next, press**Ctrl** +**Shift** +**S** to view Notepad’s "Save as" window.
5. Set the**Save as type** option to**All files** .  
![The All files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/all-files-option.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
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
4. Click**Yes** to erase that key.

##  How to Set Controlled Folder Access Exceptions

 The problem with controlled folder access is that it can stop legitimate apps from accessing required files when they need to. That can be an especially big issue for Windows gaming since untrusted games often can’t save progress with controlled folder access enabled. In-game settings can also reset when that feature is turned on.

 Fortunately, controlled folder access has an exclusion (exception) list for adding trusted apps. It won’t block any trusted apps on that list from modifying files within protected folders. You can add software to the CFA exclusion list as follows:

1. Bring up the**Controlled folder access** setting in Windows Security as covered in steps one to three of the first method above.
2. Click the **Allow an app through Controlled folder access navigation** link.
3. Press the**\+ Add an allowed app** button.  
![The Add an allowed app button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-an-allowed-app.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click**Browse all** **apps** on the menu that appears.  
![The Browse all apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/browse-all-apps-option.jpg)
5. Select the EXE (application) file for a game or other software you want to exclude from controlled folder access.
6. Click**Open** to add the selected game or software.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Enable Controlled Folder Access for Greater Ransomware Protection

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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-conquering-challenges-in-single-source-online-streaming/"><u>[New] 2024 Approved  Conquering Challenges in Single-Source Online Streaming</u></a></li>
<li><a href="https://youtube-data.techidaily.com/apturing-attention-striking-shots-for-youtube-success-for-2024/"><u>[New] Capturing Attention  Striking Shots for YouTube Success for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-instalment-insight-getting-vrecord-running-for-2024/"><u>[New] Instalment Insight  Getting VRecord Running for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unearthing-the-potential-in-magixs-image-sorter/"><u>[New] Unearthing the Potential in MAGIX's Image Sorter</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-movie-magic-adjusting-netflix-speed/"><u>2024 Approved  Mastering Movie Magic  Adjusting Netflix Speed</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-seamless-editing-removing-out-of-place-backgrounds/"><u>2024 Approved  Seamless Editing  Removing Out-of-Place Backgrounds</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/a-detailed-comparison-vsdc-vs-other-recorders-for-2024/"><u>A Detailed Comparison  VSDC vs Other Recorders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-crafting-windows-11-extractable-files/"><u>A Step-by-Step Guide to Crafting Windows 11 Extractable Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-win1011-blue-screen-crash-issue/"><u>Addressing Win10/11 Blue Screen Crash Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-pcs-into-transcoding-hubs-via-tdarr/"><u>Boost Windows PCs Into Transcoding Hubs via Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-code-0x800f0831-the-key-to-smooth-windows/"><u>Decoding Code 0X800F0831: The Key to Smooth Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-infinix-hot-30i-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Infinix Hot 30i.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/foster-robust-windows-application-connections-with-simple-fixes/"><u>Foster Robust Windows Application Connections with Simple Fixes</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-from-nokia-105-classic-by-drfone-android/"><u>How to Bypass FRP from Nokia 105 Classic?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-and-disable-the-windows-key/"><u>How to Enable and Disable the Windows Key</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-8-free-online-video-editors-for-youtube/"><u>In 2024, 8 Free Online Video Editors for YouTube</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-brain-teasers-galore-choose-your-top-escapes/"><u>In 2024, Brain Teasers Galore  Choose Your Top Escapes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-tecno-spark-20-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Tecno Spark 20 Lock Screen Password?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-icloud-on-apple-iphone-14-pro-smoothly-by-drfone-ios/"><u>In 2024, How To Remove iCloud On Apple iPhone 14 Pro Smoothly</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-realme-note-50-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Realme Note 50 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-iphone-7-by-drfone-ios/"><u>In 2024, The Easy Way to Remove an Apple ID from Your MacBook For your iPhone 7</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unlocking-the-code-to-content-creator-commerce-with-carminati-ajay/"><u>In 2024, Unlocking the Code to Content Creator Commerce with Carminati (AJay)</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-the-mystery-of-facebooks-hidden-activities/"><u>In 2024, Unlocking the Mystery of Facebook's Hidden Activities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-augment-folder-context-menus/"><u>Innovative Ways to Augment Folder Context Menus</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/mastering-android-an-assessment-of-premium-voice-recorders-including-free-variants-for-the-year-2023/"><u>Mastering Android An Assessment of Premium Voice Recorders (Including Free Variants) for the Year 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-lag-and-enhance-fps-in-roblox-win-edition/"><u>Minimize Lag & Enhance FPS in Roblox Win Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-access-denied-save-issues-on-windows/"><u>Navigating Through Access Denied Save Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-1110-setup-with-rightful-permissions/"><u>Navigating Windows 11/10 Setup with Rightful Permissions</u></a></li>
<li><a href="https://driver-install.techidaily.com/optimizing-opengl-frame-rates/"><u>Optimizing OpenGL Frame Rates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-update-obstacles-with-these-fixes/"><u>Overcome Update Obstacles with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-functional-headphonesspeakers-in-windows/"><u>Resolving Non-Functional Headphones/Speakers in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-connection-between-windows-11-and-print-devices/"><u>Restoring Connection Between Windows 11 and Print Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-11-admin-details-effectively/"><u>Revamp Your Windows 11 Admin Details Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-emulated-titles-in-playnite/"><u>Seamless Integration of Emulated Titles in Playnite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slick-techniques-for-masking-windows-11-task-view/"><u>Slick Techniques for Masking Windows 11 Task View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-roblox-unrecoverable-errors/"><u>Strategies to Overcome Roblox Unrecoverable Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-divine-interface-capabilities-in-windows-11/"><u>Tap Into Divine Interface Capabilities in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-archival-steganography-in-photos-windows-11/"><u>The Art of Archival Steganography in Photos (Windows 11)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-pros-playbook-mastering-the-art-of-capturing-ps4-gaming/"><u>The Pro's Playbook  Mastering the Art of Capturing PS4 Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unbreakable-passwords-top-four-managers-for-the-new-windows-edition/"><u>Unbreakable Passwords: Top Four Managers for the New Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-speed-minimizing-applications-via-keyboard-shortcuts/"><u>Unleash Speed: Minimizing Applications via Keyboard Shortcuts</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlock-limitless-creativity-with-free-after-effects-samples/"><u>Unlock Limitless Creativity with Free After Effects Samples</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-guide-to-opening-quick-capture-utility/"><u>Windows 11 Guide to Opening Quick Capture Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-out-0x800f0831-windows-troubleshoot-guide/"><u>Zeroing Out 0X800F0831: Windows Troubleshoot Guide</u></a></li>
</ul></div>
