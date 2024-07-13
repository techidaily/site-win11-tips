---
title: Eradicating the OneDrive Symbol From Windows 11 Filesystem
date: 2024-07-12T17:14:55.329Z
updated: 2024-07-13T17:14:55.329Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating the OneDrive Symbol From Windows 11 Filesystem
excerpt: This Article Describes Eradicating the OneDrive Symbol From Windows 11 Filesystem
keywords: Removing OneDrive in Win11,Eliminate OneDrive on PC,Remove OneDrive From File System,Delete OneDrive Windows 11,Ditch OneDrive Filesystem,Exclude OneDrive FS,Eradicate Windows 11 OneDrive
thumbnail: https://thmb.techidaily.com/e66e28dff9a78d29ac6c41d0e2dd487a7c339d734ca57b3143f21e9c629c5f8e.jpg
---

## Eradicating the OneDrive Symbol From Windows 11 Filesystem

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://win11-tips.techidaily.com/steps-to-combat-gaming-induced-laptop-overheating/"><u>Steps to Combat Gaming-Induced Laptop Overheating</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-melody-match-masters-unveiling-the-hottest-tunes-on-web-platforms/"><u>2024 Approved Melody Match Masters Unveiling the Hottest Tunes on Web Platforms</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-tools-focused-uninstall-strategies-for-windows-1011/"><u>Tailored Tools: Focused Uninstall Strategies for Windows 10/11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-nubia-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Nubia Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-browsing-efficiency-on-windows/"><u>Streamlining Browsing Efficiency on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browsing-lightly-identifying-minimal-resource-using-software-across-windowsmacoschromeos/"><u>Browsing Lightly: Identifying Minimal Resource-Using Software Across Windows/macOS/ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-windows-11-in-software-installation-harmony/"><u>The Role of Windows 11 in Software Installation Harmony</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-soundscapes-for-iphone-customization/"><u>[New] Step-by-Step Soundscapes for iPhone Customization</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-edit-on-the-go-best-android-video-editor-apps-for-chromebooks/"><u>New 2024 Approved Edit on the Go Best Android Video Editor Apps for Chromebooks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-high-definition-adventures-winning-with-windows-and-scummvm/"><u>The Ultimate Guide to High Definition Adventures: Winning with Windows & ScummVM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-folder-customization-adding-movecopy-context-functionality/"><u>Windows 11 Folder Customization - Adding Move/Copy Context Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-device-synergy-samsung-dex-for-galaxy-users/"><u>Streamlining Device Synergy: Samsung DeX for Galaxy Users</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-premiere-mac-based-vehicle-sound-unifier/"><u>Updated Premiere Mac-Based Vehicle Sound Unifier</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-or-dfu-mode-on-apple-iphone-7-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery or DFU Mode on Apple iPhone 7 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-software-aid-the-best-windows-apps-that-facilitate-mac-switch/"><u>Crucial Software Aid: The Best Windows Apps That Facilitate MAC Switch</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-step-by-point-process-of-perfect-slow-motion-videos-on-tiktok-for-2024/"><u>[New] Step-By Point Process of Perfect Slow Motion Videos on TikTok for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/scending-with-expertise-mastering-the-art-and-science-of-asmr-production-for-2024/"><u>[New] Ascending with Expertise  Mastering The Art & Science of ASMR Production for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-get-the-most-out-of-the-windows-11-start-menu/"><u>7 Ways to Get the Most Out of the Windows 11 Start Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-impressions-drawing-techniques-for-pc-screens/"><u>Digital Impressions: Drawing Techniques for PC Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ditch-installation-struggles-preparations-before-vbox-on-pc/"><u>Ditch Installation Struggles: Preparations Before VBox on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-measures-for-eradicating-white-screens-in-win1011/"><u>Efficient Measures for Eradicating White Screens in WIN10/11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-maximize-engagement-selective-rank-tracker-utilities-revealed/"><u>In 2024, Maximize Engagement  Selective Rank Tracker Utilities Revealed</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-navigate-through-apples-best-in-class-virtual-reality-games/"><u>[New] In 2024, Navigate Through Apple's Best-in-Class Virtual Reality Games</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-best-practices-to-avoid-sound-in-video-capture/"><u>[New] 2024 Approved  Best Practices to Avoid Sound in Video Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-workspaces-into-a-unified-digital-ecosystem-via-aoemi/"><u>Transforming Windows Workspaces Into a Unified Digital Ecosystem via AOEMi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-analyzing-t-series-youtube-financial-gains/"><u>[New] 2024 Approved  Analyzing T-Series Youtube Financial Gains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-alter-desktop-icons-separation-in-win-oss/"><u>Title: Alter Desktop Icons' Separation in WIN OSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-troubleshooting-windows-1011-file-issues/"><u>Strategies for Troubleshooting Windows 10/11 File Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-deals-bf-black-friday-612-win10-for-life/"><u>Best Deals: BF Black Friday - $6.12 Win10 for Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-reinstating-default-windows-backups/"><u>The Path to Reinstating Default Windows Backups</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-wealthy-digital-creators-for-2024/"><u>Ultra-Wealthy Digital Creators for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-transform-your-footage-a-step-by-step-guide-to-3d-video-effects-on-windows/"><u>Updated 2024 Approved Transform Your Footage A Step-by-Step Guide to 3D Video Effects on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-integrating-cutting-edge-run-commands/"><u>Upgrade Your Windows 11: Integrating Cutting-Edge Run Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-to-new-life-for-your-outdated-computer/"><u>Transition to New Life for Your Outdated Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-future-windows-laptops-top-picks/"><u>The Ultimate Guide to Future Windows Laptops: Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-action-optimize-your-windows-system-against-high-ums-use/"><u>Efficiency in Action: Optimize Your Windows System Against High UMS Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trouble-locating-astra-pilot-help-for-windows-11-pcs/"><u>Trouble Locating Astra Pilot? Help For Windows 11 PCs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-top-strategies-for-efficient-mobizen-screencasting-for-2024/"><u>[New] Top Strategies for Efficient Mobizen Screencasting for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-frozen-opera-downloads-in-windows-sphere/"><u>Unlock Frozen Opera Downloads in Windows Sphere</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-takeaways-from-the-best-ogg-converter/"><u>In 2024, Takeaways From the Best OGG Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-def5-barrier-tips-for-win11s-onedrive-errors/"><u>Breaking Down the DEF5 Barrier: Tips for Win11's OneDrive Errors</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-turn-off-find-my-iphone-se-when-phone-is-broken-by-drfone-ios/"><u>In 2024, How to Turn Off Find My iPhone SE when Phone is Broken?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-ultimate-toolkit-to-counteract-bsod-on-win10/"><u>Your Ultimate Toolkit to Counteract BSOD on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-pinnacle-clarity-to-your-w11-desktop-wallpaper/"><u>Bringing Pinnacle Clarity to Your W11 Desktop Wallpaper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-variability-in-windows-protocols-for-cloud-and-local-reinstallation/"><u>Understanding Variability in Windows Protocols for Cloud and Local Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-dissolving-ms-teams-error-80080300-on-win11-platform/"><u>Deciphering and Dissolving MS Teams Error 80080300 on Win11 Platform</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-s-top-free-divx-video-editors-for-cutting-and-trimming/"><u>In 2024, S Top Free Divx Video Editors for Cutting and Trimming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-a-comprehensive-guide-to-os-settings/"><u>Dive Deep: A Comprehensive Guide to OS Settings</u></a></li>
<li><a href="https://win11.techidaily.com/essential-4-password-guardians-elevating-windows-11-security/"><u>Essential 4 Password Guardians Elevating Windows 11 Security</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-standing-out-with-personalized-tiktok-pfps-for-2024/"><u>[Updated] Standing Out with Personalized TikTok PFPs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-extracting-device-ids-in-windows/"><u>Unleashing the Power: Extracting Device IDs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-missing-5ghz-network-on-windows-11-top-7-solutions/"><u>Troubleshoot Missing 5GHz Network on Windows 11: Top 7 Solutions</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-enhance-your-video-content-how-to-add-subtitles-and-captions-in-final-cut-pro-x-for-2024/"><u>New Enhance Your Video Content How to Add Subtitles and Captions in Final Cut Pro X for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-discover-the-top-vignette-creator-apps-for-iphone-and-android/"><u>2024 Approved Discover the Top Vignette Creator Apps for iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-opening-woes-resolved-fast-fixed-for-windows-11-users/"><u>Chrome Opening Woes Resolved: Fast Fixed for Windows 11 Users</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-make-canva-collages/"><u>How to Make Canva Collages</u></a></li>
</ul></div>
