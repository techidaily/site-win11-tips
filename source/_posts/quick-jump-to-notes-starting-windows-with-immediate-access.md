---
title: "Quick Jump to Notes: Starting Windows with Immediate Access"
date: 2024-07-12T17:18:34.458Z
updated: 2024-07-13T17:18:34.458Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Jump to Notes: Starting Windows with Immediate Access"
excerpt: "This Article Describes Quick Jump to Notes: Starting Windows with Immediate Access"
keywords: Quick Note Start,Windows Fast Launch,Immediate Access Jump,Notepad Open Instantly,Speedy Note Hub,Direct Window Entry,Swift Notes Launcher
thumbnail: https://thmb.techidaily.com/32b091bb5633d3a9c4c2a4da4b60ec3b4374fdb769db4d47d5b0ac420926fc16.jpg
---

## Quick Jump to Notes: Starting Windows with Immediate Access

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
<li><a href="https://smart-video-creator.techidaily.com/in-2024-hidden-gems-top-rated-mac-apps-for-speech-to-text-conversion-no-cost-no-hassle/"><u>In 2024, Hidden Gems Top-Rated Mac Apps for Speech to Text Conversion (No Cost, No Hassle)</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-how-to-make-an-animation-with-7-steps-for-2024/"><u>Updated How to Make an Animation With 7 Steps for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-inside-polarrs-magic-box-the-ultimate-digital-image-enhancer/"><u>In 2024, Inside Polarr's Magic Box  The Ultimate Digital Image Enhancer</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-vidgrabmaster-mobilepc-app-downloads-for-2024/"><u>[New] VidGrabMaster  Mobile/PC App Downloads for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/obs-animated-alternatives/"><u>OBS Animated Alternatives</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-infinix-note-30i-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Infinix Note 30i without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-no-write-saves-winos/"><u>A Step-by-Step Guide to Fixing No Write Saves, WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-preparing-your-pc-before-win-upgrade/"><u>A Step-by-Step Guide to Preparing Your PC Before Win Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-make-the-windows-terminal-your-default-terminal-app/"><u>3 Ways to Make the Windows Terminal Your Default Terminal App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-strategies-for-optimizing-windows-11s-bar/"><u>5 Key Strategies for Optimizing Windows 11'S Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-network-configurations-in-win11/"><u>Accessing Network Configurations in Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-incorporating-multimedia-in-school-curricula/"><u>2024 Approved  Incorporating Multimedia in School Curricula</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-adjustments-to-reestablish-wi-fi-connectivity-in-windows-10-systems/"><u>5 Key Adjustments to Reestablish Wi-Fi Connectivity in Windows 10 Systems</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-x6-phone-without-pin-by-drfone-android/"><u>How to Unlock Poco X6 Phone without PIN</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-free-and-fantastic-the-best-avi-video-editors/"><u>New In 2024, Free and Fantastic The Best AVI Video Editors</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-simplifying-complications-in-youtube-shorts/"><u>In 2024, Simplifying Complications in YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-networked-resources-in-explorers-sidebar/"><u>Adding Networked Resources in Explorer's Sidebar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-repairing-onedrive-on-windows-11/"><u>A Step-by-Step Approach to Repairing OneDrive on Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/top-rated-free-video-storage-sites-for-online-sharing/"><u>Top-Rated Free Video Storage Sites for Online Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ad-free-thinking-ad-free-win-11-start/"><u>Ad-Free Thinking, Ad-Free Win 11 Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-excessive-tiworkerexe-cpu-usage-issue/"><u>Addressing Excessive TiWorker.exe CPU Usage Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-deciphering-windows-11s-registry/"><u>A Comprehensive Guide to Deciphering Windows 11'S Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tactics-to-prevent-c-drive-from-running-dry-in-windows/"><u>5 Tactics to Prevent C: Drive From Running Dry in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-setup-5-key-tools-to-turbocharge-windows/"><u>Accelerate Your Setup: 5 Key Tools to Turbocharge Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-top-picks-for-integrating-frame-elements-with-images-for-2024/"><u>[Updated] Top Picks for Integrating Frame Elements with Images for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-innovative-windows-tricks-for-program-launching/"><u>6 Innovative Windows Tricks for Program Launching</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-optimizing-stardew-valley-fun-a-list-of-the-top-7-mods/"><u>[New] 2024 Approved  Optimizing Stardew Valley Fun  A List of the Top 7 Mods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-errors-missing-dll-mfc71u-in-os/"><u>Addressing Errors: Missing DLL – Mfc71u in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-and-configure-powershell-execution-policies-securely/"><u>Activate & Configure PowerShell Execution Policies Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-crucial-strategies-to-salvage-a-frozen-windows-service-panel/"><u>7 Crucial Strategies to Salvage a Frozen Windows Service Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-seven-windows-workarounds-for-web-site-woes/"><u>Access Denied? Seven Windows Workarounds for Web Site Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-secrets-the-fastest-ways-to-uncover-windows-11s-credential-manager/"><u>Accessing Secrets: The Fastest Ways to Uncover Windows 11'S Credential Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-the-speaker-in-microsofts-new-era/"><u>Activating the Speaker in Microsoft's New Era</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-hevc-h-265-content-on-motorola-moto-g-stylus-2023-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Can’t view HEVC H.265 content on Motorola Moto G Stylus (2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-in-windows-vm-hosting-platforms/"><u>Addressing Insufficient RAM in Windows VM Hosting Platforms</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-realme-narzo-60x-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Realme Narzo 60x 5GFRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-rotate-images-on-a-windows-11-pc/"><u>6 Ways to Rotate Images on a Windows 11 PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-master-sound-capture-on-your-macos-device-via-audacity/"><u>In 2024, Master Sound Capture on Your MacOS Device via Audacity</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-absentee-tab-button-on-your-pc/"><u>Addressing the Absentee Tab Button on Your PC</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-silencing-the-sharp-methods-for-banishing-excessive-hiss-in-music-production-for-2024/"><u>Updated Silencing the Sharp Methods for Banishing Excessive Hiss in Music Production for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-system-blocked-issue-on-your-windows-machine/"><u>Addressing the System Blocked Issue on Your Windows Machine</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-find-out-what-keyframe-interval-is-why-it-is-important-and-to-change-its-value-on-obs-studio-with-simple-and-easy-to-follow-instructions/"><u>Updated Find Out What Keyframe Interval Is, Why It Is Important, and to Change Its Value on OBS Studio with Simple and Easy-to-Follow Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-workflow-efficient-redo-keys-on-windows/"><u>Ace Your Workflow: Efficient Redo Keys on Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-superior-on-screen-moment-documentation/"><u>[Updated] In 2024, Superior On-Screen Moment Documentation</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-why-apple-account-disabled-from-your-apple-iphone-13-how-to-fix-by-drfone-ios/"><u>In 2024, Why Apple Account Disabled From your Apple iPhone 13? How to Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-data-safety-with-controlled-folder-access-feature/"><u>Activate Data Safety with Controlled Folder Access Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-a-windows-device-thats-stuck-in-dark-mode/"><u>5 Ways to Fix a Windows Device That's Stuck in Dark Mode</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-mp4-video-metadata-management-tools-top-picks/"><u>2024 Approved MP4 Video Metadata Management Tools Top Picks</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-coexisting-screen-data-gathering/"><u>[New] 2024 Approved  Coexisting Screen Data Gathering</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-androids-video-reversion-secrets-unveiled/"><u>2024 Approved  Android's Video Reversion Secrets Unveiled</u></a></li>
</ul></div>
