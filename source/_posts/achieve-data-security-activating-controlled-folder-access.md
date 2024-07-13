---
title: "Achieve Data Security: Activating Controlled Folder Access"
date: 2024-07-12T16:42:31.969Z
updated: 2024-07-13T16:42:31.969Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Achieve Data Security: Activating Controlled Folder Access"
excerpt: "This Article Describes Achieve Data Security: Activating Controlled Folder Access"
keywords: Data Security Controls,Secure Folder Access,Protect Data Access,Folder Safety Measures,Controlled Data Sharing,Enhanced File Privacy,Safe Data Management
thumbnail: https://thmb.techidaily.com/747b49f807ccf9f14c19b340ff456a78dd6771beaa7f3b2a1e86afcc1230369a.jpg
---

## Achieve Data Security: Activating Controlled Folder Access

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
<li><a href="https://win11-tips.techidaily.com/dismantling-barriers-to-running-powershell-scripts-in-windows/"><u>Dismantling Barriers to Running PowerShell Scripts in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-comprehensive-exploration-of-vsco-image-processing/"><u>2024 Approved  Comprehensive Exploration of VSCO Image Processing</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-c67-4g-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Realme C67 4G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-masterful-stardew-upgrades-uncovered-the-seven-best/"><u>In 2024, Masterful Stardew Upgrades Uncovered  The Seven Best</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-speed-for-swift-steam-content-delivery/"><u>Enhance PC Speed for Swift Steam Content Delivery</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-top-3d-video-creation-tools-free-and-premium-options/"><u>New 2024 Approved Top 3D Video Creation Tools Free and Premium Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-ahead-with-windows-11-integrating-outlook-preview/"><u>Get Ahead with Windows 11: Integrating Outlook Preview</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-get-going-on-youtube-video-upload-tutorial-in-premiere/"><u>[Updated] In 2024, Get Going on YouTube  Video Upload Tutorial in Premiere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-absence-of-tab-functionality-in-os-x/"><u>Navigating the Absence of Tab Functionality in OS X</u></a></li>
<li><a href="https://extra-resources.techidaily.com/video-freelancers-talent-agreement-form/"><u>Video Freelancers  Talent Agreement Form</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-error-code-0xc00000f-strategies-for-success/"><u>Mastery over Windows Error Code 0Xc00000f: Strategies for Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-upgrade-to-windows-11-22h2-on-unsupported-hardware/"><u>How to Upgrade to Windows 11 22H2 on Unsupported Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-complexities-of-onedrive-errors/"><u>Navigating Through the Complexities of OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-yuzu-fps-on-pc-systems/"><u>Enhancing Yuzu FPS on PC Systems</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/essential-free-laughter-music-collections-for-easy-to-use-film-and-media-projects/"><u>Essential Free Laughter Music Collections for Easy-to-Use Film and Media Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-unlocking-free-speech-transcription-a-triad-of-simple-approaches/"><u>New 2024 Approved Unlocking Free Speech Transcription - A Triad of Simple Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-file-access-failures-in-microsoft-office-outlook/"><u>Correcting File Access Failures in Microsoft Office Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-lock-screen-and-screen-saver-timeout-settings-on-windows/"><u>How to Change the Lock Screen and Screen Saver Timeout Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-loop-of-0xf0831-error-in-win11-os/"><u>Breaking the Loop of 0XF0831 Error in Win11 OS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quicklooker-windows-11s-speedy-photo-viewer/"><u>QuickLooker  Windows 11'S Speedy Photo Viewer</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/streamline-your-mixes-a-curated-list-of-the-top-5-dynamic-audio-ducking-tools-for-producers/"><u>Streamline Your Mixes A Curated List of the Top 5 Dynamic Audio Ducking Tools for Producers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-way-a-guide-to-mapping-drives-on-windows-11/"><u>Navigate Your Way: A Guide to Mapping Drives on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-vivo-y100-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Vivo Y100 Without PUK Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-samsung-galaxy-m14-4g-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Samsung Galaxy M14 4G Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-black-windows-display-with-ease/"><u>Navigate Black Windows Display with Ease</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-channel-expansion-sharing-your-show-across-30-platforms/"><u>2024 Approved  Channel Expansion  Sharing Your Show Across 30 Platforms</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-checklist-before-choosing-youtube-tv/"><u>2024 Approved  The Ultimate Checklist Before Choosing YouTube TV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-remedying-directdraw-disruptions-in-win1011/"><u>Expert Guide: Remedying DirectDraw Disruptions in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-personalized-lock-patterns-on-windows-11/"><u>Mastering Personalized Lock Patterns on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-nokia-130-music-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Nokia 130 Music to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hidden-paths-of-window-menus-on-pc/"><u>Navigating the Hidden Paths of Window Menus on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-invisible-wi-fi-on-windows/"><u>Master the Art of Invisible Wi-Fi on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-implementing-bluescreenview-strategies/"><u>Detailed Guide to Implementing BlueScreenView Strategies</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-compose-cover-videos-for-friends-facebooks-for-2024/"><u>[New] Compose Cover Videos for Friends' Facebooks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-full-system-access-through-cmd-elevation/"><u>Gain Full System Access Through CMD Elevation</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-creme-de-la-creme-of-25-instagram-talents-for-2024/"><u>[New] The Crème De La Crème of 25 Instagram Talents for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-in-depth-assessment-the-dji-quadcopter-model-3/"><u>In 2024, In-Depth Assessment  The DJI Quadcopter Model 3</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-honor-x8b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Honor X8b | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-flush-the-steam-dns-cache-on-windows/"><u>How to Flush the Steam DNS Cache on Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-screen-recording-essentials-and-competitive-analyses/"><u>In 2024, Screen Recording Essentials and Competitive Analyses</u></a></li>
</ul></div>
