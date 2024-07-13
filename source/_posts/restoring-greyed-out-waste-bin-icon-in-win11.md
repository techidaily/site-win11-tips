---
title: Restoring Greyed Out Waste Bin Icon in Win11
date: 2024-07-12T17:40:28.552Z
updated: 2024-07-13T17:40:28.552Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Greyed Out Waste Bin Icon in Win11
excerpt: This Article Describes Restoring Greyed Out Waste Bin Icon in Win11
keywords: Fix Waste Bin Icon Issue,Reset Grayed Icon Windows,Clear Grayed Icon Win11,Restore Bin Icons Win10/Win11,Repair Icon Glitches Windows,Ungray Waste Bins Win11,Reverse Greyed Out Bin Icon
thumbnail: https://thmb.techidaily.com/b0e6c7278d6ccf548c998db09b6cda475848470d5c9c7b34bcb8ab2c73be290c.jpg
---

## Restoring Greyed Out Waste Bin Icon in Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/5-alternative-techniques-for-temporarily-haltin-windows-11-safety/"><u>5 Alternative Techniques for Temporarily Haltin Windows 11 Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-and-using-components-settings/"><u>A Guide to Understanding and Using Components Settings</u></a></li>
<li><a href="https://fox-info.techidaily.com/crescendo-to-calmness-premier-asmr-artists/"><u>Crescendo to Calmness  Premier ASMR Artists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-digital-imagery-to-your-desktop/"><u>Adding Digital Imagery to Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-low-memory-alerts-for-vmware-hosts/"><u>Addressing Low Memory Alerts for VmWare Hosts</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Vivo Y27 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-data-safety-with-controlled-folder-access-feature/"><u>Activate Data Safety with Controlled Folder Access Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327147890-secrets-to-perfect-full-screen-snipping-with-windows-toolkit/"><u>Secrets to Perfect Full-Screen Snipping with Windows' Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-indicators-when-a-pc-needs-a-clean-slate/"><u>7 Indicators: When a PC Needs a Clean Slate</u></a></li>
<li><a href="https://extra-information.techidaily.com/comparative-study-of-premium-video-services/"><u>Comparative Study of Premium Video Services</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-effortless-capture-procedure-guiding-you-through-macos-screen-record/"><u>In 2024, Effortless Capture Procedure  Guiding You Through macOS Screen Record</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-ultimate-guide-to-glitch-video-editors-top-picks-for-windows-mac-and-web/"><u>2024 Approved The Ultimate Guide to Glitch Video Editors Top Picks for Windows, Mac, and Web</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pcs-boot-up-with-these-3-ways-in-windows-11/"><u>Accelerate Your PC's Boot-Up with These 3 Ways in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-mastering-windows-11s-search-functionality/"><u>A Quick Guide to Mastering Windows 11'S Search Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-getting-jdk-rolled-out-in-windows-11-dev-environment/"><u>A Guide to Getting JDK Rolled Out in Windows 11 Dev Environment</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/a-compreehensive-guide-to-youtube-thumbnail-creation-mac-for-2024/"><u>A Compreehensive Guide to YouTube Thumbnail Creation (Mac) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-remedies-to-clear-windows-setup-stuck-on-validation-error/"><u>9 Remedies to Clear Windows Setup Stuck on Validation Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-make-the-windows-terminal-your-default-terminal-app/"><u>3 Ways to Make the Windows Terminal Your Default Terminal App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-ancient-windows-to-seniors-needs/"><u>Adapting Ancient Windows to Seniors' Needs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Oppo A78 5G? | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-poco-m6-5g-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Poco M6 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-savvy-scribblers-selection-the-top-compiler-of-twitter-animation/"><u>[New] Savvy Scribbler's Selection - The Top Compiler of Twitter Animation</u></a></li>
<li><a href="https://extra-hints.techidaily.com/cutting-edge-video-production-windows-11s-moviemaker-toolkit/"><u>Cutting-Edge Video Production  Windows 11'S Moviemaker Toolkit</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-beat-breakers-crafting-compelling-video-music-scores/"><u>[New] 2024 Approved  Beat Breakers  Crafting Compelling Video Music Scores</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359374237-combat-window-settings-malfunctions-now/"><u>Combat Window Settings Malfunctions Now!</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-setting-up-a-sports-channel-from-scratch-mac-style/"><u>[New] Setting up a Sports Channel From Scratch, Mac-Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-iomap64-bsod-with-easy-steps-for-windows-users/"><u>Addressing IOMap64 BSoD with Easy Steps for Windows Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-art-of-aural-storytelling-on-instagram-reels/"><u>[Updated] In 2024, The Art of Aural Storytelling on Instagram Reels</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-mastering-media-migration-tiktok-directly-to-fb/"><u>[Updated] 2024 Approved  Mastering Media Migration  TikTok Directly to FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-through-to-windows-11-security-control-screen/"><u>A Step-by-Step Through to Windows 11 Security Control Screen</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-unbranded-desktop-recording-suite-cost-zero-for-2024/"><u>[Updated] Unbranded Desktop Recording Suite (Cost  Zero) for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/ultimate-affordable-game-controllers-under-100-for-2024/"><u>Ultimate Affordable Game Controllers Under $100 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327449344-bargain-hunters-rejoice-key-lovers-snag-best-prices-for-lifetime-windows-11/"><u>Bargain Hunters Rejoice: Key Lovers Snag Best Prices for Lifetime Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-undo-error-x80780119-on-windows-images/"><u>Actions to Undo Error X80780119 on Windows Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenas-for-conquering-windows-10-bsod-woes/"><u>A Compreenas for Conquering Windows 10 BSOD Woes</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/step-by-step-path-to-smm-victory-for-2024/"><u>Step-by-Step Path to SMM Victory for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-way-to-fix-the-virus-and-threat-protection-engine-unavailable-issue-in-windows-defender/"><u>5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-install-net-now-demands-from-apps/"><u>Addressing Install .NET Now Demands From Apps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/ultimate-tech-gear-best-win-11-webcam-recorders/"><u>Ultimate Tech Gear  Best Win 11 Webcam Recorders</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-reversing-tiktok-videos-101-master-the-technique-with-this-ultimate-guide-for-2024/"><u>Updated Reversing TikTok Videos 101 Master the Technique with This Ultimate Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-slowness-in-windows-discord-interface/"><u>Addressing Slowness in Windows Discord Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-fn-key-operations-in-the-latest-windows-os/"><u>Adapting FN Key Operations in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-restart-and-shutdown-disruptions-from-windows-faulty-apps/"><u>Addressing Restart and Shutdown Disruptions From Windows Faulty Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-altering-lockout-frequency-in-windows-11-successor/"><u>A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-enabling-uninstalled-features-in-win10win11/"><u>7 Strategies for Enabling Uninstalled Features in Win10/Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-crafting-dynamic-duo-videos-on-macos-sierra/"><u>[Updated] Crafting Dynamic Duo Videos on macOS Sierra</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-epiceditor-hub-innovative-pc-cutting-with-tunes/"><u>In 2024, EpicEditor Hub  Innovative PC Cutting with Tunes</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-visual-language-in-tiktok-a-complete-overview/"><u>[Updated] In 2024, Visual Language in TikTok  A Complete Overview</u></a></li>
</ul></div>
