---
title: Quick Fix for Non-Functional Microsoft Store in Windows 11
date: 2024-09-11T01:28:04.320Z
updated: 2024-09-12T01:28:04.320Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fix for Non-Functional Microsoft Store in Windows 11
excerpt: This Article Describes Quick Fix for Non-Functional Microsoft Store in Windows 11
keywords: Windows 11 Store Issue,Microsoft Store Repair,Fixing Microsoft Store,Functioning MS Store,Quick Microsoft Fix,Restore MS Store,Stop Non-Functional Store
thumbnail: https://thmb.techidaily.com/600ab240c6c8b1ad864f3c8d1c4daad9b77c19a5afa889dc63fba4f50be8c27e.jpg
---

## Quick Fix for Non-Functional Microsoft Store in Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-broadcasting-fb-movies-on-whatsapp/"><u>[New] 2024 Approved Broadcasting FB Movies on WhatsApp</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-crystalstream-hd-converter-software-suite/"><u>[New] 2024 Approved CrystalStream HD Converter Software Suite</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-prime-voice-recorders-for-online-use/"><u>[New] 2024 Approved Prime Voice Recorders for Online Use</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-the-pros-approach-to-optimizing-zoom-settings/"><u>[New] In 2024, The Pro's Approach to Optimizing Zoom Settings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-imageinspector-plus-detailed-windowsmac-screenshots-for-2024/"><u>[Updated] ImageInspector Plus Detailed Windows/Mac Screenshots for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-premier-alternatives-to-youtubes-top-5-video-editors/"><u>[Updated] Premier Alternatives to YouTube's Top 5 Video Editors</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-building-blocks-of-virtual-experience-terminology/"><u>2024 Approved Building Blocks of Virtual Experience Terminology</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-securing-premium-image-on-zoom-via-strategic-filters/"><u>2024 Approved Securing Premium Image on Zoom via Strategic Filters</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-strategic-tips-to-enhance-your-gmeet-ppt-presentations-on-mobilelaptop/"><u>2024 Approved Strategic Tips to Enhance Your GMeet PPT Presentations on Mobile/Laptop</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-play-mkv-movies-on-redmi-12-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Can I play MKV movies on Redmi 12 5G?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparable-digital-painting-and-sketching-for-pc-users/"><u>Comparable Digital Painting & Sketching for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-how-windows-approves-deleted-items/"><u>Customizing How Windows Approves Deleted Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-windows-11s-sticky-note-barrier/"><u>Cutting Through Windows 11'S Sticky Note Barrier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decision-guide-choosing-a-superior-windows-coder/"><u>Decision Guide: Choosing a Superior Windows Coder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-detect-pcs-network-settings-in-windows-ps/"><u>Efficiently Detect PC's Network Settings in Windows PS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-with-extended-pins-on-win1011/"><u>Elevate Security with Extended PINs on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-task-management-skills-in-windows-11-through-run-upgrade/"><u>Elevate Your Task Management Skills in Windows 11 Through Run Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-windows-experience-through-keys-and-discounts/"><u>Elevating Your Windows Experience Through Keys and Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-time-management-on-pc-choose-from-these-5-best-tools-to-create-customized-clock-screen-savers/"><u>Enhance Time Management on PC: Choose From These 5 Best Tools to Create Customized Clock Screen Savers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-for-resolving-windows-upgrade-frustrations/"><u>Essential Techniques for Resolving Windows Upgrade Frustrations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-experience-failure-in-windows-11-and-11-systems/"><u>Fixing GeForce Experience Failure in Windows 11 & 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-defeating-the-2erious-case-of-miracast-not-working-on-your-gadget/"><u>Guide to Defeating the 2Erious Case of Miracast Not Working on Your Gadget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-windows-errors-when-displays-dont-boot-up/"><u>Handling Windows Errors: When Displays Don't Boot Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-copy-and-paste-in-application-guard-for-edge-in-windows-11/"><u>How to Enable Copy and Paste in Application Guard for Edge in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-shadowplay-failure-to-record-in-windows-easy-guide/"><u>How to Fix ShadowPlay Failure to Record in Windows - Easy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-windows-automatically-empty-the-recycle-bin/"><u>How to Make Windows Automatically Empty the Recycle Bin</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-vivo-s17t-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Vivo S17t to Apple TV | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-comparing-the-best-updated-review-of-gopro-and-yi-action-cams/"><u>In 2024, Comparing the Best Updated Review of GoPro and Yi Action Cams</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-honor-70-lite-5g-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Honor 70 Lite 5G Devices</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-my-spouse-from-spying-on-my-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Stop My Spouse from Spying on My Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-c12-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Nokia C12 Phone without Any Data Loss</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/lenovo-x220-drivers-fast-and-easy-guide-to-update-your-system/"><u>Lenovo X220 Drivers - Fast and Easy Guide to Update Your System</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722973013030-lexar-usb-connection-made-simple-instant-driver-download/"><u>Lexar USB Connection Made Simple: Instant Driver Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-space-available-for-pin-listings/"><u>Maximizing Space Available for Pin Listings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-disconnected-remotes-in-windows-operating-system/"><u>Mending Disconnected Remotes in Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-high-cpu-drain-from-dropbox-a-guide-for-windows-users/"><u>Minimizing High CPU Drain From Dropbox: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-aoemi-for-concurrent-file-sync-on-multiple-windows-devices/"><u>Navigating AOEMi for Concurrent File Sync on Multiple Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-deletion-warning-options/"><u>Navigating Through Windows' Deletion Warning Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-9-windows-11-sounds-settings-with-ease-and-speed/"><u>Open 9 Windows 11 Sounds Settings with Ease and Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-tools-for-notetakers-and-pc-slates-alike/"><u>Optimal Tools for Notetakers & PC Slates Alike</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-vivo-s17e-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Vivo S17e.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-guide-to-overcoming-windows-errors/"><u>Precision Guide to Overcoming Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reshape-the-start-page-in-task-manager-windows-11/"><u>Reshape the Start Page in Task Manager (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-workflows-nircmds-win-shortcut-guide/"><u>Simplified Workflows: NirCmd's Win Shortcut Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-with-wintoys-your-quick-reference-manual/"><u>Simplifying Windows With WinToys: Your Quick Reference Manual</u></a></li>
<li><a href="https://extra-support.techidaily.com/standout-reddit-content-an-exclusive-look-at-top-10-threads-for-2024/"><u>Standout Reddit Content An Exclusive Look at Top 10 Threads for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-into-the-future-with-chatgpt-activating-browser-plugin-integration-in-the-new-beta-mode/"><u>Step Into the Future with ChatGPT: Activating Browser, Plugin Integration in the New Beta Mode</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-fix-eliminating-xlivedll-not-found-error-in-your-system-a-users-handbook/"><u>Step-by-Step Fix: Eliminating Xlive.dll Not Found Error in Your System – A User’s Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepping-up-security-edges-camera-and-mic-guidance/"><u>Stepping Up Security: Edge's Camera & Mic Guidance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/success-strategies-fixing-driver-not-supported-issue-in-win11/"><u>Success Strategies: Fixing Driver Not Supported Issue in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-interface-task-manager-on-win11/"><u>Tailor-Made Interface: Task Manager on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-20-critical-command-prompt-commands/"><u>The Ultimate Guide to 20 Critical Command Prompt Commands</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-ultimate-guide-to-ppt-capture-excellence/"><u>The Ultimate Guide to PPT Capture Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-conquer-usb-device-failures-windows-edition/"><u>Tips to Conquer USB Device Failures: Windows Edition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/toolwiz-visual-mastery-a-comprehensive-review-for-2024/"><u>Toolwiz Visual Mastery - A Comprehensive Review for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-notes-visually-a-guide-to-obsidian-canvas/"><u>Transform Your Notes Visually: A Guide to Obsidian Canvas</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-for-when-you-encounter-a-missing-user32dll-file/"><u>Troubleshooting Tips for When You Encounter a Missing User32.dll File</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-windows-application-run-time-errors/"><u>Understanding and Fixing Windows Application Run-Time Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualization-mastery-clearing-images-of-extraneous-elements/"><u>Visualization Mastery: Clearing Images of Extraneous Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-past-and-future-unearthing-7-time-honed-elements-in-11/"><u>Windows Past and Future: Unearthing 7 Time-Honed Elements in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-startup-configurations-simplified-guidebook/"><u>Windows Startup Configurations Simplified Guidebook</u></a></li>
</ul></div>




