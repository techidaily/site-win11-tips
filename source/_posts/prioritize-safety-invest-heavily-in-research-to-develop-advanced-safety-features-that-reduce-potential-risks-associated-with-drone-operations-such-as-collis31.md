---
title: "Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks."
date: 2024-06-25T16:45:43.116Z
updated: 2024-06-26T16:45:43.116Z
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

##  How to Enable Controlled Folder Access With Group Policy Editor

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
4. Click**Yes** to erase that key.

##  How to Set Controlled Folder Access Exceptions

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
<li><a href="https://win11-tips.techidaily.com/8-fixes-for-no-server-found-on-apex-legends-tips-and-tricks-(156-chars/"><u>8 Fixes for 'No Server Found' On Apex Legends: Tips and Tricks (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangling-stacked-icons-on-operating-system-ui/"><u>Disentangling Stacked Icons on Operating System UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-selectivity-enable-checkbox-file-option-in-win11/"><u>Perfecting Selectivity: Enable Checkbox File Option in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-discord-install-failure/"><u>Overcoming Windows 11 Discord Install Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-smart-color-settings-in-windows-11-programs/"><u>Enable Smart Color Settings in Windows 11 Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purple-pandemonium-restore-your-pcs-color-calibration/"><u>Purple Pandemonium? Restore Your PC's Color Calibration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-tablet-navigation-a-guide-to-windows-11s-taskbar/"><u>Optimizing Tablet Navigation: A Guide to Windows 11'S Taskbar</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-the-complete-handbook-to-adding-auditory-elements-to-ae-projects-revised/"><u>Updated 2024 Approved The Complete Handbook to Adding Auditory Elements to AE Projects, Revised</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-find-my-friends-work-on-itel-p55t-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Itel P55T | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/avoiding-simulated-reality-ills-strategies-and-tips-for-2024/"><u>Avoiding Simulated Reality Ills  Strategies and Tips for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-must-have-iphone-apps-the-complete-roundup/"><u>2024 Approved Must-Have iPhone Apps The Complete Roundup</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/snort-spree-twitters-funniest-humor-chronicles/"><u>Snort Spree  Twitter’s Funniest Humor Chronicles</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-your-apple-iphone-6-plus-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>In 2024, How to Unlock Your Apple iPhone 6 Plus Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-beat-breakers-the-premier-list-of-todays-chart-toppers-and-their-signatures-online/"><u>Updated Beat Breakers The Premier List of Todays Chart-Toppers and Their Signatures Online</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-vidmore-screen-recorder-how-to-use-it/"><u>2024 Approved  Vidmore Screen Recorder - How to Use It</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/must-have-top-skins-themes-and-backgrounds-for-laptops-for-2024/"><u>Must-Have  Top Skins, Themes & Backgrounds for Laptops for 2024</u></a></li>
</ul></div>
