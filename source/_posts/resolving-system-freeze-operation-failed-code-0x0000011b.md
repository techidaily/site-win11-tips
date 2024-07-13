---
title: "Resolving System Freeze: Operation Failed Code 0X0000011B"
date: 2024-07-12T17:09:10.650Z
updated: 2024-07-13T17:09:10.650Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving System Freeze: Operation Failed Code 0X0000011B"
excerpt: "This Article Describes Resolving System Freeze: Operation Failed Code 0X0000011B"
keywords: Fix System Freeze Error,Unfreeze OS Crash,Resolve Code 0X0000011B,Stop Operation Failed,ZeroXOS Fix Guide,System Halt Recovery,Error X011B Solution
thumbnail: https://thmb.techidaily.com/5ab9533fc8b349be19f63e7cbad029dfd19e210f57907497c693bf48b201e0ff.jpg
---

## Resolving System Freeze: Operation Failed Code 0X0000011B

 A new security patch released by Microsoft may have caused printers shared over the network to malfunction, resulting in the operation failed 0x0000011B error. The error has primarily affected Windows 10 21H1 build running computers. However, you may also experience it on Windows 11 systems.

 You can fix the error by installing the latest patch for the bug in the Windows update section. If not, here are other troubleshooting steps to fix the error and get your printer working again.

 Note that all the fixes must be applied to the host system that has the printer connected to it.

## 1\. Restart the Print Spooler Service

 A common troubleshooting step to fix issues with your printer is to restart the print spooler service. It is an essential service that handles the print job between your computer and printer. If the [print spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) , you can manually start it from the Services snap-in. Here’s how to do it.

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Service** snap-in, locate the**Print Spooler** service.  
![print spooler service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-properties.jpg)
4. Next, right-click on the service and select**Properties** .  
![print spooler service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-startup-type-automatic.jpg)
5. In the**Properties** dialog, open the**General** tab.  
![restart print spooler service 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-print-spooler-service-1.jpg)
6. Click the**Startup type** drop-down and set it to**Automatic** .
7. Click**Apply** and**OK** to save the changes.
8. Right-click on**Print** **Spooler** again and click**Restart** .
9. Once the Print Spooler service is up and running, create a new print job and check for any improvements.

## 2\. Install All the Pending Windows Updates
![check windows 10 updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-windows-10-updates.jpg)

 If it’s a widespread issue, you’ll likely receive a bug fix via Windows update. So, begin with checking if a new Windows update is available. These are often small hotfixes released to fix widespread issues.

To check and install Windows updates:

1. Press**Win + I** to open the**Settings** app.
2. In the left pane, open the**Windows Update** tab. Open**Update & Security** on Windows 10.
3. Click on**Check for updates** . Windows will look for pending updates and list them here.
4. Click on**Download & install** to install the updates.
5. Once installed, restart your PC and check for any improvements.

## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to [add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

1. Press**Win + I** to open**Settings** .
2. Next, click on**Devices** and then open the**Printers & scanners** tab.
3. Next, click on**Add a printer or scanner** . Windows will scan for available printers.  
![the printer that i want isnt listed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-printer-that-i-want-isnt-listed.jpg)
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)

1. Under**Choose a printer por** t, select**Create a new port.**  
![create new port local port add printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-port-local-port-add-printer.jpg)
2. Click the drop-down for**Type of port** and select**Local Port.**
3. Click**Next** .  
![enter port name printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enter-port-name-printer.jpg)
4. Type your network printer file path and the network printer name in the**Enter a port name** field. You can use the username or the IP address for the computer name and then the printer name you want to share.
5. Click**OK** to save the printer.

1. Next, select your printer manufacturer from the list to install the printer driver.
2. Next, select the correct printer driver under the**Printers** column.
3. Click**Next** .
4. Choose a name for your printer driver and click**Install** .
5. Click**Next** and wait for the installation to complete.

 Your newly added printer will now appear under**Device and Printer** in**Control Panel** and the**Settings** app. Give a new print job to see if the error is resolved.

## 4\. Disable the CVE-2021-1678 Registry Fix

 The problematic security update included a security fix to patch the Printer Spooler Spoofing vulnerability dubbed CVE-2021-1678\. However, the new changes seem to have triggered the 0x0000011B operation failed error.

 To fix the error without uninstalling the security update, you’ll need to create a new registry entry to disable the feature. Here’s how to do it.

 Note that modifying your Windows Registry involves risk. We recommend you [back up your Windows registry](http://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a system restore](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

Next, follow these steps to disable CVE-2021-1678 mitigation:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor.
3. In Registry Editor, navigate to the following location. Copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print`
4. Next, right-click on**Print > New > DWORD (32-bit) Value.**  
![create new dword 32 bit value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-dword-32-bit-value-registry-editor.jpg)
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  
![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
8. Close**Registry Editor** and restart your PC to apply the changes.
9. After the restart, try to use your shared printer and check if the error is resolved.

## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
3. Next, click on**Programs** .  
![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

## Fixing the 0x0000011b Printing Error on Windows

 This error has largely affected Windows 10 computers. To fix the issue, try to install all the pending Windows updates that may include a hotfix. You can also add the printer manually to a local port or edit the registry entry to disable the problematic setting. If nothing works, uninstalling the security update may be the last resort. However, doing so can put your computer at risk of print spooler spoofing vulnerability.

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
<li><a href="https://youtube-videos.techidaily.com/rising-stars-in-digital-domain/"><u>Rising Stars in Digital Domain</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-efficient-workflow-multi-screen-settings-in-win11/"><u>Achieve Efficient Workflow: Multi-Screen Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-directory-alert-in-windows-11/"><u>Addressing Empty Directory Alert in Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/what-wikipedia-wont-tell-you-about-character-rigging-for-2024/"><u>What Wikipedia Wont Tell You About Character Rigging for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lossed-graphics-support-in-overwatch-2/"><u>Addressing Lossed Graphics Support in Overwatch 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-gameplay-9-tricks-to-end-wwe-2k23-freezes-in-windows/"><u>Accelerate Gameplay: 9 Tricks to End WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-newcomers-path-in-the-world-of-original-diablo/"><u>A Newcomer's Path in the World of Original Diablo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719310221725-tame-frozen-windows-handbraked-beast/"><u>Tame Frozen Windows-Handbraked Beast!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessible-beginnings-on-windows-for-first-timers/"><u>Accessible Beginnings on Windows for First-Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719348732386-cant-capture-sound-in-obs-on-win-11-solve-it-now/"><u>Can't Capture Sound in OBS on Win 11? Solve It Now!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-creating-immersive-experiences-with-quality-video-voice-over/"><u>[Updated] 2024 Approved  Creating Immersive Experiences with Quality Video Voice Over</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-keyboard-shortcuts-to-access-windows-ease-of-access/"><u>5 Keyboard Shortcuts to Access Windows Ease of Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sudden-screen-blackouts-in-winsteam/"><u>Addressing Sudden Screen Blackouts in WinSteam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-enhance-and-immerse-in-atmos-on-windows/"><u>A Complete Guide to Enhance and Immerse in Atmos on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inaccessible-values-in-windows-applications/"><u>Addressing Inaccessible Values in Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719356387702-stuck-google-chrome-on-win11-try-these-immediate-actions/"><u>Stuck Google Chrome on Win11? Try These Immediate Actions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719347202341-unveiling-the-full-potential-of-windows-snip-and-sketch-capabilities/"><u>Unveiling the Full Potential of Windows' Snip and Sketch Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-resolving-steam-setup-problems-win11-edition/"><u>A Practical Guide to Resolving Steam Setup Problems, Win11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-eliminate-hardware-detection-faults/"><u>A Quick Guide to Eliminate Hardware Detection Faults</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-the-update-to-sonys-premium-blu-ray-player/"><u>In 2024, Unveiling the Update to Sony’s Premium Blu-Ray Player</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-samsung-galaxy-xcover-6-pro-tactical-edition-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Samsung Galaxy XCover 6 Pro Tactical Edition Phone Pattern Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-turn-filter-keys-on-or-off-on-windows/"><u>4 Ways to Turn Filter Keys On or Off on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-file-transfer-times-in-battlenet-gaming/"><u>Accelerating File Transfer Times in Battle.net Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-routes-to-activate-telnet-in-windows-11-os/"><u>3 Routes to Activate Telnet in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-day-windows-productivity-software-that-works-wonders/"><u>Ace Your Day: Windows Productivity Software That Works Wonders</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-optimized-motion-the-creme-de-la-liste-of-srt-upgrades-for-pc-and-mac/"><u>2024 Approved  Optimized Motion  The Crème De La Liste of SRT Upgrades for PC and Mac</u></a></li>
<li><a href="https://extra-resources.techidaily.com/time-warp-techniques-harnessing-classic-80s-visual-flair-in-videos/"><u>Time Warp Techniques  Harnessing Classic 80S Visual Flair in Videos</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-from-concept-to-creation-making-a-dynamic-podcast-teaser/"><u>[New] In 2024, From Concept to Creation  Making a Dynamic Podcast Teaser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-outlook-preview-via-windows-11-os/"><u>Accessing Outlook Preview via Windows 11 OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-mastering-the-art-of-instagrams-musical-emoji-use/"><u>[Updated] In 2024, Mastering the Art of Instagram's Musical Emoji Use</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/looking-for-a-free-video-editor-to-edit-videos-on-mac-imovie-by-apple-is-a-great-choice-but-is-it-the-best-video-editor-or-is-there-a-better-alternative-ava/"><u>Looking for a Free Video Editor to Edit Videos on Mac? IMovie by Apple Is a Great Choice? But Is It the Best Video Editor or Is There a Better Alternative Available? Check Out Our iMovie Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-copy-file-and-folder-paths-in-windows-11/"><u>6 Ways to Copy File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-managing-windows-11-default-applications/"><u>A Comprehensible Guide to Managing Windows 11 Default Applications</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-best-practices-in-youtube-keyword-selection/"><u>2024 Approved  Best Practices in YouTube Keyword Selection</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-ps5xbox-x-visuals-the-top-5-game-tvs-for-2024/"><u>[Updated] PS5/Xbox X Visuals  The Top 5 Game TVs for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-screen-spectrum-your-gateway-to-gameplay/"><u>In 2024, Screen Spectrum  Your Gateway to Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-precise-walkthrough-for-windows-update-resetting/"><u>A Precise Walkthrough for Windows Update Resetting</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-deleting-youtube-content-a-step-by-step-guide-for-2024/"><u>[Updated] Deleting YouTube Content  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-written-guide-to-creating-a-trident-widget-grid-on-win11/"><u>A Compre Written Guide to Creating a Trident Widget Grid on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-mfc71udll-missing-issue-in-windows/"><u>Addressing Mfc71u.dll Missing Issue in Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/surrender-to-serenity-top-10-game-guides-for-2024/"><u>Surrender to Serenity  Top 10 Game Guides for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-surface-laptop-studio-2s-creative-edge/"><u>A Deep Dive Into Surface Laptop Studio 2’S Creative Edge</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-picks-superior-cloud-space-solutions/"><u>[New] Top Picks  Superior Cloud Space Solutions</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-dns-performance-via-reset/"><u>Achieving Optimal DNS Performance via Reset</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-meizu-21-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-steps-to-tame-the-gpu-hungry-desktop-window-manager/"><u>7 Steps to Tame the GPU-Hungry Desktop Window Manager</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-immortalize-memories-prime-online-tools-for-photo-framing/"><u>2024 Approved  Immortalize Memories  Prime Online Tools for Photo Framing</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-iphone-12-pro-without-passcode-or-face-id-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock iPhone 12 Pro without Passcode or Face ID</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-windows-solid-state-drive-power-of-fresh/"><u>Accelerate Your Windows' Solid State Drive - Power of Fresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719274715388-how-to-organize-your-notes-visually-with-obsidian-canvas/"><u>How to Organize Your Notes Visually with Obsidian Canvas</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/crafting-captivating-reels-musical-integration-strategies-for-2024/"><u>Crafting Captivating Reels  Musical Integration Strategies for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-noise-nullification-made-simple-a-complete-look-at-noise-reduction-in-adobe-premiere-pro/"><u>New Noise Nullification Made Simple A Complete Look at Noise Reduction in Adobe Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-running-imessage-on-windows/"><u>A Comprehensive Guide to Running iMessage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319213526-essential-tips-for-a-working-winshift/"><u>Essential Tips for a Working WinShift.</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-swift-solutions-moving-iphone-pictures-and-videos/"><u>2024 Approved  Swift Solutions  Moving iPhone Pictures & Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-detecting-bots-amongst-your-brands-facebook-supporters/"><u>[Updated] Detecting Bots Amongst Your Brand's Facebook Supporters</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-pioneering-online-techniques-for-vhs-image-refinement/"><u>[Updated] 2024 Approved  Pioneering Online Techniques for VHS Image Refinement</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-elevate-video-clarity-with-expert-tips-for-youtube-editors-for-2024/"><u>[Updated] Elevate Video Clarity with Expert Tips for YouTube Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719258042287-reclaiming-chrome-in-w11-easy-to-follow-remediation-tips/"><u>Reclaiming Chrome in W11 - Easy-to-Follow Remediation Tips</u></a></li>
</ul></div>
