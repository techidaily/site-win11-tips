---
title: "Sync Success: Starting Windows and Accessing Notepad Quickly"
date: 2024-07-12T17:18:45.698Z
updated: 2024-07-13T17:18:45.698Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sync Success: Starting Windows and Accessing Notepad Quickly"
excerpt: "This Article Describes Sync Success: Starting Windows and Accessing Notepad Quickly"
keywords: Start Windows Fast,Access Notepad Quick,Sync Devices Easy,Quick Device Connect,Speed Up System Start,Faster App Launch,Simplify Windows Use
thumbnail: https://thmb.techidaily.com/5f1d20c9cdc38cb1d77f47c43dee5a5d477e2ff178ada3de9653ceb21ae65a7a.jpg
---

## Sync Success: Starting Windows and Accessing Notepad Quickly

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App ![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

## 4\. Tweak the Registry Editor

 If you're comfortable editing the Windows registry, you can tweak it to open Sticky Notes at startup. This method requires knowledge of how the Registry Editor works and caution when editing it. If done incorrectly, it can cause serious system errors. It's best to [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing anything.

 To open Sticky Notes at startup using the Registry Editor, follow these steps:

1. [Open Windows Search](https://www.makeuseof.com/windows-search-use-guide/).
2. Type **regedit** in the search bar and click on the Registry Editor option.
3. If the UAC dialog appears, click **Yes** to grant access.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\PenWorkspace\Notes
5. Double-click the **LaunchOnNextUserSession** key on the right.  
![Tweak Registry Editor to Open Sticky Notes at Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tweak-registry-editor-to-open-sticky-notes-at-startup.jpg)
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-skills.techidaily.com/in-2024-turbocharged-triumphs-the-leading-10-srt-upgrades-for-os-x-and-windows/"><u>In 2024, Turbocharged Triumphs  The Leading 10 SRT Upgrades for OS X & Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-live-feed-rates-on-task-monitor-win-11/"><u>Improve Live Feed Rates on Task Monitor Win 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-infinix-note-30-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Infinix Note 30 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-windows-disk-read-problems/"><u>Guide to Mend Windows Disk Read Problems</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-roblox-lagging-on-pc-2024/"><u>[SOLVED] Roblox Lagging on PC 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-windows-11-determine-software-harmony/"><u>How Does Windows 11 Determine Software Harmony?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-functionality-reprogramming-fn-keys-on-modern-windows-pcs/"><u>Enhance Functionality: Reprogramming FN Keys on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-curtail-pc-sound-enhancement-effects/"><u>How To Curtail PC Sound Enhancement Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-setup-for-gpt/"><u>Navigating Through Windows Setup for GPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-with-windows-11-preparation/"><u>Elevate Security with Windows 11 Preparation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-same-account-error-in-multiuser-setup/"><u>Eradicating Same Account Error in Multiuser Setup</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-fixing-absence-of-color-on-game-feedback/"><u>[Updated] In 2024, Fixing Absence of Color on Game Feedback</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/orchestrate-instagram-reel-magic-with-music-and-voiceovers-for-2024/"><u>Orchestrate Instagram Reel Magic with Music & Voiceovers for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-head-to-head-comparison-sony-vegas-vs-adobe-premiere-pro-for-video-editors/"><u>Updated In 2024, Head-to-Head Comparison Sony Vegas vs Adobe Premiere Pro for Video Editors</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-facebooks-ultimate-add-ons-for-the-tech-enthusiast-for-2024/"><u>[Updated] Facebook's Ultimate Add-Ons for the Tech Enthusiast for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-a-guide-to-effective-video-marketing/"><u>New 2024 Approved A Guide to Effective Video Marketing</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-vivo-y02t-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Vivo Y02T Hard Reset | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-the-updated-guide-to-video-audio-integration-for-filmmakers/"><u>In 2024, The Updated Guide to Video-Audio Integration for Filmmakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tricks-to-jumpstart-a-nonfunctional-terminal/"><u>Essential Tricks to Jumpstart a Nonfunctional Terminal</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-transfer-photos-and-videos-from-iphone-to-iphone-for-2024/"><u>How to Transfer Photos and Videos From iPhone to iPhone for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/happy-updates-revamp-your-win7-hp-graphics/"><u>Happy Updates! Revamp Your Win7 HP Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-mobile-links-android-and-windows-compatible-tools/"><u>Key Mobile Links: Android & Windows Compatible Tools</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-contacts-after-vivo-v30-has-been-deleted-by-fonelab-android-recover-contacts/"><u>Recover your contacts after Vivo V30 has been deleted.</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-vdsu-screen-reader-report-full-insight-for-2024/"><u>[Updated] VDSU Screen Reader Report  Full Insight for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-honor-v-purse-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Honor V Purse Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-the-wattage-of-your-windows-pc-setup/"><u>Discovering the Wattage of Your Windows PC Setup</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/screen-sharing-made-simple-learn-phonescreen-recording-with-snapchat-for-2024/"><u>Screen Sharing Made Simple  Learn Phonescreen Recording with Snapchat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-hdr-capabilities/"><u>Mastering Windows 11'S HDR Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-overheat-during-intense-play/"><u>Minimizing Overheat During Intense Play</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-leading-the-pack-the-premier-camera-lenses-of-2024-in-order/"><u>[New] Leading the Pack  The Premier Camera Lenses of 2024, in Order</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-system-tray-and-secret-icons-in-win11/"><u>Decoding System Tray & Secret Icons in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-simple-fixes-for-your-non-operational-windows-notepad/"><u>Five Simple Fixes for Your Non-Operational Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-computing-essential-windows-software-to-banish/"><u>Efficient Computing: Essential Windows Software to Banish</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-login-lock-ups-with-rust-and-windows/"><u>Navigating Through Steam Login Lock-Ups with Rust & Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-stolen-iphone-8-in-different-conditionsin-drfone-by-drfone-ios/"><u>How To Unlock Stolen iPhone 8 In Different Conditionsin | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/1715701218203-activating-built-in-screen-recorders-mate-1020-and-p-series-devices-p20-p10/"><u>Activating Built-In Screen Recorders  Mate 10/20 & P-Series Devices (P20, P10).</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-from-apple-iphone-13-mini-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account From Apple iPhone 13 mini?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-x7007043c-in-windows-media-creator/"><u>Eradicating Error X.7007043C in Windows' Media Creator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-cant-stop-your-generic-volume-device-error/"><u>How to Fix the “Windows Can’t Stop Your Generic Volume Device” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-failed-security-codes-in-epic-games-launcher-on-windows-pcs/"><u>Fixes for Failed Security Codes in Epic Games Launcher on Windows PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-a-compreshift-guide-to-creating-profitable-and-engaging-youtube-collaborations/"><u>[Updated] 2024 Approved  A Compreshift Guide to Creating Profitable & Engaging YouTube Collaborations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-interface-error-in-windows-os/"><u>Fixing Steam Interface Error in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-portals-to-nintendo-switch-gaming/"><u>Essential Windows Portals to Nintendo Switch Gaming</u></a></li>
</ul></div>
