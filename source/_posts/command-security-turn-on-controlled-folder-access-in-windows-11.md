---
title: "Command Security: Turn on Controlled Folder Access in Windows 11"
date: 2024-08-23T07:00:23.575Z
updated: 2024-08-24T07:00:23.575Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Security: Turn on Controlled Folder Access in Windows 11"
excerpt: "This Article Describes Command Security: Turn on Controlled Folder Access in Windows 11"
keywords: Controlled Folder Access,Secure Windows 11,Folder Security Settings,Turn On Access Control,Enhance Data Protection,Windows 11 Safeguards,Commanding Security Tools
thumbnail: https://thmb.techidaily.com/c834e1885a4b3f3f1ee7dd2c9fc2dd5ec6f5c9eaec19dd6a1d5eb489c36a841d.jpg
---

## Command Security: Turn on Controlled Folder Access in Windows 11

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click**Block** on the drop-down menu to select the strictest CFA mode. However, you can also select alternative**Audit Mode** ,**Block disk notification only** , and**Audit disk notification only** options for enabling controlled folder access.  
![The Configure the guard my folders feature drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configure-controlled-folder-access.jpg)
5. Select**Apply** in the Configure Controlled folder access window.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

1. Launch the Registry Editor (our guide for[opening the Regedit registry app](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods).
2. Go to this registry key location:  
`HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess`
3. Right-click the Controlled Folder Access key to select**Delete** .  
![The Delete key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-option-for-registry-key.jpg)
4. Click**Yes** to erase that key.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
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
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-upload-youtube-shorts-video-from-computer-and-mobile-for-2024/"><u>[Updated] How to Upload YouTube Shorts Video From Computer and Mobile for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-3d-photography-duel-samsung-vs-lg-edition/"><u>[Updated] The 3D Photography Duel  Samsung VS LG Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/13-fun-games-to-improve-your-creative-design-skills/"><u>13 Fun Games to Improve Your Creative Design Skills</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-free-high-quality-srt-translation-services-1-8/"><u>2024 Approved  Free, High-Quality SRT Translation Services – #1-#8</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-industrial-giants-taking-flight-heavy-duty-drones/"><u>2024 Approved  Industrial Giants Taking Flight  Heavy-Duty Drones</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-instagram-follower-deletion-identification/"><u>2024 Approved  Instagram Follower Deletion Identification</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-iphones-high-dynamic-range-photography-demystified/"><u>2024 Approved  IPhone's High-Dynamic Range Photography Demystified</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-photography-and-videography-leading-tech-on-the-market/"><u>2024 Approved  Photography & Videography  Leading Tech on the Market</u></a></li>
<li><a href="https://extra-information.techidaily.com/bring-your-video-to-life-with-cropping-adding-and-tweaking-audio-in-canva/"><u>Bring Your Video to Life with Cropping, Adding, & Tweaking Audio in Canva</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decreasing-processor-load-while-engaged-in-virtual-battles/"><u>Decreasing Processor Load While Engaged in Virtual Battles</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-remedies-when-windows-explorer-frequently-fails-uncover-secrets/"><u>Effective Remedies When Windows Explorer Frequently Fails - Uncover Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-conversion-techniques-from-docx-to-pdf-on-windows-11/"><u>Efficient Conversion Techniques From Docx to PDF on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-ui-context-menu-with-disk-space-insight-tool/"><u>Enhancing Windows UI: Context Menu with Disk Space Insight Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enrich-windows-11-notepad-through-synergistic-tech/"><u>Enrich Windows 11 Notepad Through Synergistic Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-top-displayed-calculator-on-pcs/"><u>Ensuring Top-Displayed Calculator on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-edits-for-enhanced-user-control-in-win11/"><u>Essential Edits for Enhanced User Control in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-resolving-windows-camera-issues/"><u>Essential Steps for Resolving Windows Camera Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/fix-how-to-enable-your-gpu-for-cyberpunk-2077-on-windows-11/"><u>Fix: How to Enable Your GPU for Cyberpunk 2077 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-windows-auditory-service-auto-restart-feature/"><u>How to Enable Windows Auditory Service Auto-Restart Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-page-not-rendered-in-ms-marketplace/"><u>How to Rectify Page Not Rendered in MS Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-microsoft-defender-blocking-third-party-antivirus-software-on-windows/"><u>How to Stop Microsoft Defender Blocking Third-Party Antivirus Software on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-mp3s-into-audio-cds-with-imgburn-on-windows/"><u>How to Turn Your Mp3s Into Audio CDs With ImgBurn on Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-a2-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Xiaomi Redmi A2 Phone with Broken Screen</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Watch Hulu Outside US On Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-upgrade-for-ancient-computers-running-windows-11-using-to-go-and-rufus/"><u>Instant Upgrade for Ancient Computers: Running Windows 11 Using To Go & Rufus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/loudness-levelers-essential-apps-for-taking-windows-audio-above-100/"><u>Loudness Levelers: Essential Apps for Taking Windows' Audio Above 100%%</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterbatch-execution-automation-via-task-scheduler/"><u>Masterbatch Execution: Automation via Task Scheduler</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-what-should-be-considered-to-choose-a-nice-gopro-for-vlogging/"><u>New 2024 Approved What Should Be Considered to Choose A Nice GoPro for Vlogging?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opera-installer-stuck-downloading-on-windows-try-these-fixes/"><u>Opera Installer Stuck Downloading on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-this-non-adobe-windows-errors/"><u>Overcoming 'This Non-Adobe' Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-display-in-windows-11/"><u>Overcoming Missing Display in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-effective-fixes-to-windows-onedrive-problems/"><u>Quick and Effective Fixes to Windows OneDrive Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-fetching-ip-and-mac-addresses-windows-wise/"><u>Quick Guide: Fetching IP & MAC Addresses, Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regular-maintenance-rebuilding-win-icon-cache/"><u>Regular Maintenance: Rebuilding Win Icon Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieve-your-wingman-copilot-in-ws11s-struggle/"><u>Retrieve Your Wingman (Copilot) In WS11's Struggle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-unlocking-telnet-on-wins-os-x/"><u>Step-by-Step Guide: Unlocking Telnet on Wins OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-autonomous-restarts-win11-strategy/"><u>Stop Autonomous Restarts: Win11 Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-screech-start-scroll-mouse-adjustment-guide/"><u>Stop Screech, Start Scroll: Mouse Adjustment Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-file-transfers-on-win11-pcs-1/"><u>Strategies to Improve File Transfers on WIN11 PCs (1)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-techniques-to-alter-files-on-your-win-os/"><u>Tailored Techniques to Alter Files on Your Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-dusk-drawers-of-microsoft-paint/"><u>The Dusk Drawers of Microsoft Paint</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-solution-fixing-zlibdll-could-not-be-loaded/"><u>The Ultimate Solution: Fixing 'zlib.dll Could Not Be Loaded'</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transform-your-communications-with-openais-fine-tuned-gpt-tools/"><u>Transform Your Communications with OpenAI's Fine-Tuned GPT Tools</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/transition-tactics-your-youtube-videos-on-instagram/"><u>Transition Tactics  Your YouTube Videos on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-empty-directory-error-code-x80070091/"><u>Troubleshooting Windows' Empty Directory Error Code X80070091</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-captcha-on-steam-for-successful-logins/"><u>Unblocking CAPTCHA on Steam for Successful Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-lan-world-play-windows-mc-solutions/"><u>Unleashing LAN World Play: Windows MC Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-displays-potential-with-these-simple-steps/"><u>Unlock Your Display's Potential with These Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-insights-what-patch-wxx-brings-to-windows-11/"><u>Upgrade Insights: What Patch W.x.x Brings to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-drawing-delights-the-ultimate-7-app-guide/"><u>Win10 Drawing Delights: The Ultimate 7 App Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/yule-time-share-windows-games-through-ms-store/"><u>Yule Time: Share Windows Games Through MS Store</u></a></li>
</ul></div>
