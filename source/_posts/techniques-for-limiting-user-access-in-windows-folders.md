---
title: Techniques for Limiting User Access in Windows Folders
date: 2024-09-11T01:26:46.358Z
updated: 2024-09-12T01:26:46.358Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Limiting User Access in Windows Folders
excerpt: This Article Describes Techniques for Limiting User Access in Windows Folders
keywords: Windows Security Limit,Folder Permission Control,Access Restriction Methods,User Privilege Management,Windows Folder Safeguarding,Security Settings Reduction,Intrusion Prevention in Windows
thumbnail: https://thmb.techidaily.com/11bd493dd0576b5128c521759756af9ef0469248903e298828d7682c78b82237.jpg
---

## Techniques for Limiting User Access in Windows Folders

 Controlled folder access is a feature of the Windows Security antivirus app on Microsoft desktop platforms. That feature forestalls ransomware by preventing modifications to files in protected folders. Enabling controlled folder access prevents untrusted apps, malware or otherwise, from changing files within protected directories.

 Controlled folder access is an extra security feature in Windows 10 and 11 that some users appreciate. Ransomware isn’t something to be taken lightly, and enabling that feature will keep system and user files extra safe. These are four ways you can enable controlled folder access in Windows.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



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
<a href="https://appsumo.8odi.net/c/5597632/2118324/7443" target="_top" id="2118324">
  <img src="//a.impactradius-go.com/display-ad/7443-2118324" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118324/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
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




<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




`Set-MpPreference -EnableControlledFolderAccess Disabled`

## How to Enable Controlled Folder Access With Group Policy Editor

 If you have Windows 11 Pro or Enterprise edition, you can enable controlled folder access with Group Policy Editor. Group Policy Editor also includes some extra configuration settings for controlled folder access, which is a bonus. This is how to turn on controlled folder access via GPE.

 If you're on Windows Home, the Group Policy Editor won't appear by default. Check out[how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) to get around this.

1. Bring up the search tool in Windows and enter**gpedit.msc** there.
2. Select**gpedit.msc** to[bring up the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
3. Click**Computer Configuration** \>**Administrative Templates** inside Group Policy Editor’s left pane.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/computer-configuration-in-group-policy-editor.jpg)
4. Double-click**Windows Components** to expand it.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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
<a href="https://aligracehair.sjv.io/c/5597632/2115926/19272" target="_top" id="2115926">
  <img src="//a.impactradius-go.com/display-ad/19272-2115926" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115926/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
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

1. Launch the Registry Editor (our guide for[opening the Regedit registry app](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods).
2. Go to this registry key location:  
`HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess`
3. Right-click the Controlled Folder Access key to select**Delete** .  
![The Delete key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-option-for-registry-key.jpg)
4. Click**Yes** to erase that key.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Set Controlled Folder Access Exceptions

 The problem with controlled folder access is that it can stop legitimate apps from accessing required files when they need to. That can be an especially big issue for Windows gaming since untrusted games often can’t save progress with controlled folder access enabled. In-game settings can also reset when that feature is turned on.

 Fortunately, controlled folder access has an exclusion (exception) list for adding trusted apps. It won’t block any trusted apps on that list from modifying files within protected folders. You can add software to the CFA exclusion list as follows:

1. Bring up the**Controlled folder access** setting in Windows Security as covered in steps one to three of the first method above.
2. Click the **Allow an app through Controlled folder access navigation** link.
3. Press the**\+ Add an allowed app** button.  
![The Add an allowed app button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-an-allowed-app.jpg)
4. Click**Browse all** **apps** on the menu that appears.  




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![The Browse all apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/browse-all-apps-option.jpg)
5. Select the EXE (application) file for a game or other software you want to exclude from controlled folder access.
6. Click**Open** to add the selected game or software.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-turn-mundane-games-into-epic-scenes/"><u>[New] 2024 Approved How to Turn Mundane Games Into Epic Scenes</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-ending-echoes-reconnecting-audio-to-obs/"><u>[New] In 2024, Ending Echoes Reconnecting Audio to OBS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-enhanced-joy-in-switchs-hd-gameplay-through-cards/"><u>[New] In 2024, Enhanced Joy in Switch's HD Gameplay Through Cards</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-instaphoto-tips-for-seamless-sharing/"><u>[New] InstaPhoto Tips for Seamless Sharing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unveiling-instagram-insights-a-deep-dive-into-data-trends-for-2024/"><u>[New] Unveiling Instagram Insights A Deep Dive Into Data Trends for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-seamless-incorporation-of-text-overlays-for-vimeo-films/"><u>[Updated] Seamless Incorporation of Text Overlays for Vimeo Films</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-advance-explored-in-metasig-space/"><u>ChatGPT Advance Explored in Metasig Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-print-sharing-woes-on-windows-11/"><u>Clearing Up Print Sharing Woes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-unsuccessful-windows-update-error-0x8024800c/"><u>Correcting Unsuccessful Windows Update (Error 0X8024800C)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detect-and-prevent-cyber-risks-without-antivirus-help/"><u>Detect and Prevent Cyber Risks Without Antivirus Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-disconnected-application-problems-in-win10/"><u>Eliminating Disconnected Application Problems in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-prominent-positioning-of-sticky-notes-in-win-11/"><u>Ensuring Prominent Positioning of Sticky Notes in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-google-chromes-filesync-on-your-pc-win/"><u>Expert Advice for Google Chrome's Filesync on Your PC, WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-efficiency-microsofts-bluetooth-linked-app/"><u>Exploring the Efficiency: Microsoft's Bluetooth-Linked App</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-inactive-lock-screen-countdown-in-windows-os/"><u>Fixing Inactive Lock Screen Countdown in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cleanse-your-saved-wi-fi-list-in-win-11/"><u>How to Cleanse Your Saved Wi-Fi List in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-your-deactivated-key-on-win11/"><u>How to Reactivate Your Deactivated Key on Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-elevating-your-vlogs-with-high-quality-editing-premiere-pro-style/"><u>In 2024, Elevating Your Vlogs with High-Quality Editing - Premiere Pro Style</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-lava-blaze-2-pro-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Lava Blaze 2 Pro FRP Locks</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-many-attempts-to-unlock-iphone-13-pro-by-drfone-ios/"><u>In 2024, How Many Attempts To Unlock iPhone 13 Pro</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-google-chrome-from-tracking-your-location-on-realme-v30-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Google Chrome from Tracking Your Location On Realme V30? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-key-picks-the-best-6-online-communities-for-enterprise-expansion/"><u>In 2024, Key Picks The Best 6 Online Communities for Enterprise Expansion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-startup-configurations/"><u>Mastering Windows Startup Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-internal-server-errors-windows-1011-tips/"><u>Overcoming Internal Server Errors: Windows 10/11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unsupported-boots-in-windows-the-5-essential-fixes/"><u>Overcoming Unsupported Boots in Windows: The 5 Essential Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-troubleshoot-steps-to-resurrect-xbox-app/"><u>Quick Troubleshoot Steps to Resurrect Xbox App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-normal-operations-fixing-windows-enter-key-issues/"><u>Reinstating Normal Operations: Fixing Windows Enter Key Issues</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721468374007-rotation-locked-learn-how-to-activate-landscape-on-your-ios-gadget/"><u>Rotation Locked? Learn How to Activate Landscape on Your iOS Gadget!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-windows-effortlessly-with-these-free-generators/"><u>Safeguard Windows Effortlessly with These Free Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-minimizing-minecraft-crashes-in-windows/"><u>Solutions for Minimizing Minecraft Crashes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-battlenet-access-in-windows-1011-operating-system/"><u>Streamlining Battle.net Access in Windows 10/11 Operating System</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-complete-guide-to-creating-memorable-youtube-outros-for-2024/"><u>The Complete Guide to Creating Memorable YouTube Outros for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/the-stagnation-of-ideas-in-contemporary-vr-for-2024/"><u>The Stagnation of Ideas in Contemporary VR for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/virtual-vintage-the-dosbox-x-guide-to-classic-pc-gaming/"><u>Virtual Vintage: The DOSBox-X Guide to Classic PC Gaming</u></a></li>
</ul></div>




