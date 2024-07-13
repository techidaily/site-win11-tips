---
title: "Accelerated Access: Boosting Morning Routine & Note Openings"
date: 2024-07-12T17:50:53.111Z
updated: 2024-07-13T17:50:53.111Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accelerated Access: Boosting Morning Routine & Note Openings"
excerpt: "This Article Describes Accelerated Access: Boosting Morning Routine & Note Openings"
keywords: Fast Morning Start,Quick Note Opener,Accelerate Mornings,Speedy Notebook,Rapid Access Notes,Hastened Routine,Swift Opening Books
thumbnail: https://thmb.techidaily.com/d8fc0a6dc40b2c266ea46ef0e0946f6a6f2bfc24fdd8c197f755ef2d88428204.jpg
---

## Accelerated Access: Boosting Morning Routine & Note Openings

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
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
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
<li><a href="https://win11-tips.techidaily.com/mastery-over-flawed-icons-and-menu-items-on-win-1011/"><u>Mastery Over Flawed Icons and Menu Items on Win 10/11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-capture-record-and-share-the-essence-of-spring-screens/"><u>[Updated] In 2024, Capture, Record, and Share - The Essence of Spring Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-system-operations-via-terminal-commands/"><u>Streamlining System Operations via Terminal Commands</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-obtaining-customized-animation-emojis-on-discord-without-a-premium-account/"><u>2024 Approved  Obtaining Customized Animation Emojis on Discord Without a Premium Account</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-expertly-selected-8-recording-software/"><u>[New] In 2024, Expertly Selected 8 Recording Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastery-in-monitors-selecting-top-4k-panels-for-video-editors-for-2024/"><u>Mastery in Monitors  Selecting Top 4K Panels for Video Editors for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-ordering-with-these-7-photo-apps/"><u>Seamless File Ordering with These 7 Photo Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-screen-organization-multi-window-mastery-with-win1110/"><u>Simplified Screen Organization: Multi-Window Mastery with Win11/10</u></a></li>
<li><a href="https://video-capture.techidaily.com/step-by-step-recording-on-discord/"><u>Step-by-Step  Recording on Discord</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-mac-video-editing-software-top-vsdc-alternatives/"><u>Updated In 2024, Mac Video Editing Software Top VSDC Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-11-remedy-six-steps-to-resurrect-lost-panes/"><u>The Ultimate Windows 11 Remedy: Six Steps to Resurrect Lost Panes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-how-to-alter-file-extensions-on-windows/"><u>Step by Step: How to Alter File Extensions on Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-navigating-video-uploads-on-social-platforms/"><u>[Updated] 2024 Approved  Navigating Video Uploads on Social Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-stranded-xbox-on-win11-quick-troubleshooting-guide/"><u>Solving Stranded Xbox on Win11: Quick Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-tech-game-with-these-top-7-windows-tips/"><u>Skyrocket Your Tech Game with These Top 7 Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-win-11-adjusting-proxy-preferences/"><u>Navigating Win 11: Adjusting Proxy Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-travelled-titles-tamed-the-power-of-retroarcs-visual-shapers/"><u>Time-Travelled Titles Tamed: The Power of RetroArc's Visual Shapers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-outdated-systems-why-not-windows/"><u>Rejuvenate Outdated Systems: Why Not Windows?</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-green-grounds-a-selection-of-free-downloadable-videography-sets/"><u>2024 Approved  Green Grounds  A Selection of Free, Downloadable Videography Sets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-control-over-typing-with-these-9-fixes-for-broken-keyboard-commands-on-windows-pc/"><u>Reclaiming Control over Typing with These 9 Fixes for Broken Keyboard Commands on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-image-previews-top-4-win-friendly-viewers/"><u>Perfecting Image Previews: Top 4 Win-Friendly Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-display-configurations-on-nvidia/"><u>Overcoming Missing Display Configurations on Nvidia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-failed-signal-for-windows-steam-link/"><u>Reviving Failed Signal for Windows Steam Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-remote-connection-issues/"><u>Mastering Windows Remote Connection Issues</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-cherished-holiday-hits-our-top-10-family-friendly-films/"><u>In 2024, Cherished Holiday Hits  Our Top 10 Family-Friendly Films</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rehabilitating-the-non-deletable-character-in-microsoft-os/"><u>Rehabilitating the Non-Deletable Character in Microsoft OS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-kodi-remote-x-wmps-easy-alternative/"><u>In 2024, Kodi Remote X  WMP's Easy Alternative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microphone-issues-live-recording-fixes-in-obs-w11/"><u>Troubleshooting Microphone Issues: Live Recording Fixes in OBS, W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obsolete-windows-aesthetics-gone-for-good/"><u>Obsolete Windows Aesthetics, Gone for Good</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-power-of-placement-comments-in-windows-explorer/"><u>Unveiling the Power of Placement Comments in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-compression-errors-a-guide-to-fixed-zip-files-in-windows-11/"><u>Overcoming Compression Errors: A Guide to Fixed ZIP Files in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-capture-the-thrill-essential-recording-tips-for-overwatch-for-2024/"><u>[New] Capture the Thrill  Essential Recording Tips for Overwatch for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-discover-the-leading-10-audio-streamers/"><u>In 2024, Discover the Leading 10 Audio Streamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-windows-experience-with-customized-fn-keys-settings/"><u>Tailor Your Windows Experience with Customized FN Keys Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-windows-potential-get-the-outlook-preview-installed/"><u>Unveil Windows' Potential: Get the Outlook Preview Installed</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-master-photographers-tale-assembly-tool-for-2024/"><u>[New] Master Photographer's Tale Assembly Tool for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-the-elite-circle-top-gamers-on-tiktok/"><u>2024 Approved  The Elite Circle  Top Gamers on TikTok</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-fb-messenger-call-history-management-made-easy-for-2024/"><u>[New] FB Messenger Call History Management Made Easy for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-learn-selective-picture-clarity-reduction/"><u>[New] Learn Selective Picture Clarity Reduction</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-10-ultimate-simulators-for-androids-gb-games/"><u>[New] 2024 Approved  10 Ultimate Simulators for Android's GB Games</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>How to Share Location in Messenger On Apple iPhone XS Max? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-explore-sub4sub-safely-with-our-step-by-step-guide/"><u>[New] Explore Sub4sub Safely with Our Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-setting-up-seamless-auto-play-for-fb-content/"><u>[Updated] 2024 Approved  Setting Up Seamless Auto-Play for FB Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-unresponsive-delete-button-issue-on-pcs/"><u>Solving Unresponsive Delete Button Issue on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-windows-headset-mic-functionality/"><u>Restore Your Windows Headset Mic Functionality</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-innovative-broadcast-strategies-live-on-instagram-using-obs-software-for-2024/"><u>[Updated] Innovative Broadcast Strategies  Live on Instagram Using OBS Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-managing-wins-ram-cache/"><u>Understanding and Managing Win's RAM Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-ms-teams-error-80080300-on-windows-11-a-guide/"><u>Resolving MS Teams Error 80080300 on Windows 11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-diablo-secrets-basic-techniques/"><u>Unlocking Diablo Secrets: Basic Techniques</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-mental-agility-triumphs-in-premier-escape-venues/"><u>[Updated] Mental Agility Triumphs in Premier Escape Venues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-the-steps-msoffice-installation-on-windows-11/"><u>Simplifying the Steps: MSOffice Installation on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retro-game-revival-elevating-experiences-by-adding-achievements-using-retroarch/"><u>Retro Game Revival: Elevating Experiences by Adding Achievements Using Retroarch</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-sony-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Sony Phone Network-Ready</u></a></li>
</ul></div>
