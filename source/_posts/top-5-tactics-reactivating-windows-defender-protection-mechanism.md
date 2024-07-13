---
title: "Top 5 Tactics: Reactivating Windows Defender Protection Mechanism"
date: 2024-07-12T16:38:10.190Z
updated: 2024-07-13T16:38:10.190Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Top 5 Tactics: Reactivating Windows Defender Protection Mechanism"
excerpt: "This Article Describes Top 5 Tactics: Reactivating Windows Defender Protection Mechanism"
keywords: WinDefend Reactivity Tips,Reviving WinDefend Safeguard,React Defender Protection Fixes,Enhancing Windows Defender,Boosting Defender Security,WinDefend Renewal Strategies,Elevating WinDefend Protocols
thumbnail: https://thmb.techidaily.com/246d0000b4a8f8f8e29a0c282b538c53c7dcabe9e936ddda4c95b0a712854944.jpg
---

## Top 5 Tactics: Reactivating Windows Defender Protection Mechanism

 Windows Defender is a crucial built-in antivirus software that helps protect your computer from various types of malware and security threats. However, users might encounter a common issue where the Virus & threat protection feature in Windows Defender displays an error message saying "Engine Unavailable" which prevents it from scanning for viruses and leaving your system vulnerable.

 In this article, we will explore the solutions that can help fix this issue and restore the full functionality of this important security feature.

## Why Is the Engine Unavailable in Windows Defender?

 The Virus & Threat Protection engine typically becomes unavailable after a Windows Defender update fails to install in the system. This can happen due to a number of reasons, and we have listed the most common ones below:

* **The r** **elevant services are disabled** \- the essential services required to install the Windows Defender updates might be disabled, preventing the system from updating it.
* **Windows Security's files are corrupt** \- there can be an issue with the Windows Security utility itself. A temporary bug or a corruption error might have infected it, causing it to act up.
* **Conflicting software** \- software offering similar functionalities could be conflicting with Windows Defender and its relevant procedures.
* **Corrupted Windows files or malware** \- the critical system files might be corrupt, which is affecting the update functionality of Windows. Your system might also be infected with malware.

 Regardless of what might be leading to the problem, the solutions we have listed below are sure to help you get the Virus & Threat Protection engine up and running for good. We suggest that before you proceed, restart your computer and retry installing the update. In some cases, a temporary system glitch can lead to the problem and a simple reboot can clear it.

## 1\. Restart the Security Center Service

 The Security Center service in Windows is responsible for managing security-related services, including Windows Defender. If the service is not functioning properly, it can prevent you from updating the Defender or using it at all

 Fortunately, service issues are easy to resolve. Most of the time, restarting the service can get it running properly again.

Here is how you can restart the Security Center Service:

1. Press the**Win + R** keys together to open Run.
2. Type "services.ms" in Run and press**Enter** .
3. In the following dialog, scroll down to locate the Security Center service and right-click on it.
4. Choose**Properties** from the context menu.  
![Launch the properties of Security Center service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-center-properties.jpg)
5. Now, click on the**Stop** button, wait for a few seconds, and click**Start** .
6. Expand the dropdown for Startup type and choose**Automatic** .
7. Click**Apply** \>**OK** to save the changes and then close the Services utility.

 You can now retry installing the Defender update and check if restarting the service fixed the issue.

## 2\. Edit the Relevant Registry Keys

 You can also enable the Windows Defender services using the Registry Editor. In this method, we will disable the DisableAntiSpyware and DisableAntiVirus values. Then, we will delete any corrupt Registry entries that malware may have introduced in the system.

 However, before we proceed, we recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Once that is done, proceed with the steps below:

1. Press the**Win + R** keys together to open Run.
2. Type "regedit" in the text field of Run and press**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`HKEY_LOCAL_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender`
5. Move to the right pane and locate the**DisableAntiSpyware** value.

1. Double-click on it and under Value data, type**0** .  
![Change the value data to 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disableantispyware-key.jpg)
2. Do the same with the**DisableAntiVirus** value in the same window.
3. After this, navigate to the following location in the Registry Editor:  
`HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`
4. Here, right-click on the MSASCui.exe, MpCmdRun.exe, and MsMpEng.exe values one by one and choose**Delete** .  
![Delete the Registry entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-the-key.jpg)
5. Finally, close the Registry Editor and restart your computer. Upon reboot check if the issue is resolved.

## 3\. Manually Install the Update

 If the system cannot install the Windows Defender update automatically, you can also manually install it.

 This can be done by heading over to the [Microsoft security updates](https://www.microsoft.com/en-us/wdsi/defenderupdates) page and finding the required update in the "manually download the update" section. You can then select the appropriate version based on your system and install it.

 You can also use the Powershell utility to install the update manually. We have discussed the [different methods of manually updating Windows Defender](https://www.makeuseof.com/microsoft-defender-manually-update/) , so be sure to check it out.

## 4\. Reset Windows Security

 As we mentioned earlier, there can be an issue with Windows Security itself. This problem can be resolved by resetting the utility, which will clear all of its settings and configurations, restoring the default state.

Here is how you can reset the Windows Security app:

1. Press the**Win + S** keys together to open the Windows Search utility.
2. Type Powershell in the search bar and click on**Run as administrator** .
3. In the Powershell window, type the command mentioned below and hit**Enter** .  
`Get-AppxPackage Microsoft.SecHealthUI -AllUsers | Reset-AppxPackage`  
![Command to Reset Windows Security in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Command-to-Reset-Windows-Security-.jpg)
4. Once the command is executed, exit Powershell and check if the issue is resolved.

## 5\. Remove Any Conflicting Software

 In case you have a third party installed on the system, it might be interfering with the processes of Windows Defender, preventing it from updating or functioning properly.

 If this applies to you, we recommend temporarily disabling the security program or uninstalling it. You can do this using the Control Panel or the Settings app. We have a detailed guide that discusses [how to remove programs in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) that you can refer to if you need help.

 If you can successfully update Windows Defender after removing the third-party software, then it implies that the program was indeed the culprit. In this case, you can switch to a better third-party alternative. Here are some [best free antivirus programs](https://www.makeuseof.com/tag/ten-best-antivirus-programs/) that you can consider installing.

## Get Windows Defender Up and Running Again

 Issues with the Windows Defender can be frustrating and expose your system to security threats. Hopefully, the solutions we have described above will help you fix the engine unavailable problem and use the security program to its full potential. If the problem occurs repeatedly in the future, you can report the issue to the official Microsoft support team and switch to a third-party solution until an official fix is released.


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
<li><a href="https://desktop-recording.techidaily.com/updated-zooming-in-on-podcast-quality-an-ultimate-video-recording-guidebook-for-2024/"><u>[Updated] Zooming In on Podcast Quality  An Ultimate Video Recording Guidebook for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-beginning-navigating-3-reset-routes/"><u>A Fresh Windows Beginning: Navigating 3 Reset Routes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-legitimate-strategies-to-amass-over-a-million-youtube-views/"><u>[New] Legitimate Strategies to Amass Over a Million YouTube Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessible-beginnings-on-windows-for-first-timers/"><u>Accessible Beginnings on Windows for First-Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-dns-performance-via-reset/"><u>Achieving Optimal DNS Performance via Reset</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-counterclockwise-playback-in-instagram-videos/"><u>In 2024, Counterclockwise Playback in Instagram Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Vivo G2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-newcomers-path-in-the-world-of-original-diablo/"><u>A Newcomer's Path in the World of Original Diablo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accurate-atmospheres-expert-picks-of-windows-11s-weather-apps/"><u>Accurate Atmospheres: Expert Picks of Windows 11'S Weather Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-free-up-local-drive-space-without-deleting-files-on-windows-11/"><u>8 Ways to Free Up Local Drive Space Without Deleting Files on Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-experts-gopro-buyers-companion/"><u>2024 Approved  The Expert's Gopro Buyer’s Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719258042287-reclaiming-chrome-in-w11-easy-to-follow-remediation-tips/"><u>Reclaiming Chrome in W11 - Easy-to-Follow Remediation Tips</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-what-phone-is-compatible-with-gear-vr-2023-update/"><u>[New] What Phone Is Compatible with Gear VR? -2023 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-mfc71udll-missing-issue-in-windows/"><u>Addressing Mfc71u.dll Missing Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-enhance-and-immerse-in-atmos-on-windows/"><u>A Complete Guide to Enhance and Immerse in Atmos on Windows</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-ensure-lasting-tiktok-videos-proper-saving-on-phones/"><u>[Updated] In 2024, Ensure Lasting TikTok Videos  Proper Saving on Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lossed-graphics-support-in-overwatch-2/"><u>Addressing Lossed Graphics Support in Overwatch 2</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-guide-to-adding-audio-to-microsoft-presentations/"><u>[New] The Ultimate Guide to Adding Audio to Microsoft Presentations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-on-windows-1011s-audio-upgrade/"><u>A Comprehensive Tutorial on Windows 10/11'S Audio Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-keyboard-shortcuts-to-access-windows-ease-of-access/"><u>5 Keyboard Shortcuts to Access Windows Ease of Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-low-quality-steam-streams/"><u>Addressing Low Quality Steam Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-file-transfer-times-in-battlenet-gaming/"><u>Accelerating File Transfer Times in Battle.net Gaming</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Google Pixel 7a? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-deciphering-how-to-spot-your-video-enthusiasts/"><u>[Updated] In 2024, Deciphering How to Spot Your Video Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719356387702-stuck-google-chrome-on-win11-try-these-immediate-actions/"><u>Stuck Google Chrome on Win11? Try These Immediate Actions</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-tecno-pova-5-pro-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Tecno Pova 5 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-how-to-create-animated-facebook-ads-with-high-roi/"><u>[New] 2024 Approved  How to Create Animated Facebook Ads With High ROI?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-steps-to-tame-the-gpu-hungry-desktop-window-manager/"><u>7 Steps to Tame the GPU-Hungry Desktop Window Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-insights-on-staying-with-older-windows-editions/"><u>7 Insights on Staying with Older Windows Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719348732386-cant-capture-sound-in-obs-on-win-11-solve-it-now/"><u>Can't Capture Sound in OBS on Win 11? Solve It Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719310221725-tame-frozen-windows-handbraked-beast/"><u>Tame Frozen Windows-Handbraked Beast!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-the-best-podcast-host-options/"><u>In 2024, Navigating the Best Podcast Host Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719362383486-enhance-full-screen-screenshot-success-in-windows-snip-and-sketch-tool/"><u>Enhance Full-Screen Screenshot Success in Windows' Snip & Sketch Tool.</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-fast-track-to-zooming-proficiency/"><u>In 2024, The Fast Track to Zooming Proficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306648168-fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now!</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-cartoon-fundamentals-how-to-learn-cartoon-characters-sketch-quickly/"><u>Updated In 2024, Cartoon Fundamentals How to Learn Cartoon Characters Sketch Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-eliminate-hardware-detection-faults/"><u>A Quick Guide to Eliminate Hardware Detection Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-precise-walkthrough-for-windows-update-resetting/"><u>A Precise Walkthrough for Windows Update Resetting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sudden-screen-blackouts-in-winsteam/"><u>Addressing Sudden Screen Blackouts in WinSteam</u></a></li>
<li><a href="https://vp-tips.techidaily.com/visualize-and-create-with-top-7-innovative-animation-suites-for-2024/"><u>Visualize & Create with Top 7 Innovative Animation Suites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-turn-filter-keys-on-or-off-on-windows/"><u>4 Ways to Turn Filter Keys On or Off on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-routes-to-activate-telnet-in-windows-11-os/"><u>3 Routes to Activate Telnet in Windows 11 OS</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-screen-streaming-showdown-whos-the-champion-obs-or-shadowgl/"><u>[New] 2024 Approved  Screen Streaming Showdown  Who's the Champion? OBS or ShadowGL?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-directory-alert-in-windows-11/"><u>Addressing Empty Directory Alert in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-step-by-step-solution-for-non-shown-shorts-thumbnails-on-youtube/"><u>In 2024, Step-by-Step Solution for Non-Shown Shorts Thumbnails on YouTube</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/cutting-edge-video-editing-mastering-green-screen-integration-for-2024/"><u>Cutting Edge Video Editing  Mastering Green Screen Integration for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-resolving-steam-setup-problems-win11-edition/"><u>A Practical Guide to Resolving Steam Setup Problems, Win11 Edition</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-mastering-wax-a-step-by-step-guide-to-editing-videos-for-free/"><u>Updated In 2024, Mastering Wax A Step-by-Step Guide to Editing Videos for Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719274715388-how-to-organize-your-notes-visually-with-obsidian-canvas/"><u>How to Organize Your Notes Visually with Obsidian Canvas</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/masterful-tiktok-makeovers-swap-video-backdrop-in-easy-steps/"><u>Masterful TikTok Makeovers  Swap Video Backdrop in Easy Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatenighttimedisplaynotepadwin/"><u>ActivateNighttimeDisplayNotepadWin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-written-guide-to-creating-a-trident-widget-grid-on-win11/"><u>A Compre Written Guide to Creating a Trident Widget Grid on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inaccessible-values-in-windows-applications/"><u>Addressing Inaccessible Values in Windows Applications</u></a></li>
<li><a href="https://extra-resources.techidaily.com/high-quality-streaming-showdown-whos-your-favorite-vmixwirecast/"><u>High-Quality Streaming Showdown  Who's Your Favorite, VMix/Wirecast?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-the-ultimate-guide-to-video-metadata-editing-on-mac-8-top-picks-for-2024/"><u>Updated The Ultimate Guide to Video Metadata Editing on Mac 8 Top Picks for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-essential-techniques-for-silencing-background-sounds-off-and-online-solutions/"><u>New Essential Techniques for Silencing Background Sounds Off- and Online Solutions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/youtube-tricks-for-enhancing-screen-real-estate/"><u>YouTube Tricks for Enhancing Screen Real Estate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-surface-laptop-studio-2s-creative-edge/"><u>A Deep Dive Into Surface Laptop Studio 2’S Creative Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-copy-file-and-folder-paths-in-windows-11/"><u>6 Ways to Copy File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-gameplay-9-tricks-to-end-wwe-2k23-freezes-in-windows/"><u>Accelerate Gameplay: 9 Tricks to End WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-best-background-music-remover-to-help-you-remove-background-music/"><u>Updated In 2024, Best Background Music Remover to Help You Remove Background Music</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-running-imessage-on-windows/"><u>A Comprehensive Guide to Running iMessage on Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-cross-platform-guide-extracting-facebook-video-content/"><u>[Updated] In 2024, Cross-Platform Guide  Extracting Facebook Video Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-day-windows-productivity-software-that-works-wonders/"><u>Ace Your Day: Windows Productivity Software That Works Wonders</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-screen-refreshing-issue-in-dell-pc/"><u>[Fixed]: Screen Refreshing Issue in Dell PC</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-advanced-vr-tech-for-drone-enthusiasts/"><u>2024 Approved  Advanced VR Tech for Drone Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-efficient-workflow-multi-screen-settings-in-win11/"><u>Achieve Efficient Workflow: Multi-Screen Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unbeatable-summer-movie-list-10-familial-classics/"><u>Unbeatable Summer Movie List  10 Familial Classics</u></a></li>
</ul></div>
