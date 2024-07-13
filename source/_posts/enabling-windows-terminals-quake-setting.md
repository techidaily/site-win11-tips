---
title: Enabling Windows Terminal's Quake Setting
date: 2024-07-12T16:49:11.830Z
updated: 2024-07-13T16:49:11.830Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Windows Terminal's Quake Setting
excerpt: This Article Describes Enabling Windows Terminal's Quake Setting
keywords: Quake Settings Window,Enable Terminal Mode,Windows Quake Control,Terminals Game Configuration,Quake Option Windows,Terminal Performance Tuning,Windows Terminal Adjustments
thumbnail: https://thmb.techidaily.com/80c97e26a42ec85426e926d8a619570205ae66ef3c841d342bad4a1013bf8d86.jpg
---

## Enabling Windows Terminal's Quake Setting

 The Windows Terminal is a Microsoft app used for working in command-line tools like PowerShell, Command Prompt, and WSL. It includes several useful features, including Quake Mode. And if you regularly need to enter command lines, Quake Mode is an efficient way to do it.

Here's how to enable and use Quake mode in Windows Terminal.

## What Is Quake Mode, and Why Should You Use It?

 Windows Terminal is a fast and efficient way to make using command-line tools easier. You can download it from the Microsoft Store.

![multiple tabs in the windows terminal app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/window-terminal-app.jpg)

 The key features of Windows Terminal include multiple tabs, panes, and a GPU-accelerated text rendering engine. There are also custom themes, styles, and configurations. And, of course, Quake mode which was added in version 1.9.

 When enabled, Quake mode lets you quickly open a new terminal instance from within any app. The terminal window opens from the top of the screen and fills the full-screen width. You can then hide the terminal window, keeping it ready to be opened whenever you need it.

 The name Quake mode refers to the similar-looking terminal window you could open in the iD Software game, Quake.

 If you don't know what Quake is, why not check out some [classic PC FPS games?](https://www.makeuseof.com/tag/play-classic-shooters-on-modern-computer/) Great fun, even if you have a modern PC.

## How to Open Windows Terminal in Quake Mode

There are two ways to open the Windows Terminal in Quake mode.

 The first is to press**Win + R** to open the**Run dialog** . In the text field, type**wt -w \_quake** . Make sure you include the spaces after the t and before the underscore.

 You can also open the Windows Terminal app in the normal way. You can find it in the main Start Menu apps list if you are new to the app. With the app open in standard mode, press**Win + \`** (the grave accent button below Esc on the keyboard).

![The windows terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-terminal-quake.jpg)

 If you want the command-line tool to be run as an administrator, you will need to use the second method. Learn how to open [Windows PowerShell or Command Prompt as an administrator](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

## Hiding and Restoring the Terminal Window

 The idea of the Quake mode is to give the ability to have a terminal window always available. Even when in a full-screen app or if you can't click a terminal shortcut in the Taskbar.

 Once the Windows Terminal is in Quake mode, you can hide it by pressing**Win + \`** . It remains active but is hidden off-screen.

To reveal the window again, press the same keyboard shortcut.

 The Quake mode terminal window stretches the entire width of the screen. By default, it will fill about half the height of the screen. Unfortunately, you can't change the width, but you can click and drag the bottom edge of the panel to make it less intrusive.

## Closing the Quake Mode Terminal Window

 As mentioned, the**Windows Key + \`** shortcut doesn't close the terminal window; it only hides it. Even closing the original Windows Terminal window won't remove the Quake mode window.

 When the Quake mode terminal window is on-screen, a terminal icon will appear in the Taskbar. You can hover over this icon and click the**X** on the peek preview window.

![The peek window for the Windows Terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/closing-quake-mode-window.jpg)

 If you don't see a peek preview, you can right-click on the terminal icon in the Taskbar and select**Close Window** .

 If the [Windows Taskbar is not working](https://www.makeuseof.com/tag/5-steps-fix-windows-10-taskbar-issues/) for some reason, these options won't be available. Instead, you can close the Quake mode terminal window by typing**EXIT** in the terminal and pressing**Return** .

## Start Windows Terminal in Quake Mode at Logon

 You can set the Terminal to open at logon in the PowerShell settings. But even if you have previously used Quake mode, the terminal will start in a normal window. You can get around this by creating a modified shortcut in shell:startup.

1. Type**Run** into Windows Search and open the Run Dialog.
2. Open the startup items folder by typing**shell:startup** , then click**Ok** .  
![creating a shortcut to quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/auto-open-quake-mode.jpg)
3. Right-click anywhere in the folder and select**New > Shortcut** .
4. For the location of the item, type:**wt.exe -w \_quake** . Click**Next** .  
![shortcut to automatically open quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/quake-mode-shortcut.jpg)
5. Give the shortcut a name you will recognize, such as**Terminal Quake** . Then click**Finish** .

 The next time you log on to Windows, the terminal will open automatically in Quake Mode. You can then use it, or press the**Windows + \`** shortcut to minimize it.

 If you have [disabled app execution aliases](https://www.makeuseof.com/app-execution-aliases-guide/) , you will have to type or browse to the full path for the Windows Terminal. So instead of typing**wt.exe -w \_quake** , enter **C:\\Users\\\[username\]\\AppData\\Local\\Microsoft\\WindowssApps\\wt.exe -w \_quake** .

## Using the Windows Terminal's Quake Mode

 The Windows Terminal is a great way to work in command-line apps such as PowerShell and Windows Subsystem for Linux. Being able to run it in Quake mode means that you always have access to the terminal you need, no matter what you do on your PC.


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
<li><a href="https://win11-tips.techidaily.com/rectifying-overlapping-app-symbols-on-pc-screen/"><u>Rectifying Overlapping App Symbols on PC Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-not-responding-problem-for-spotify-software/"><u>Resolving the Not Responding Problem for Spotify Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-cheat-sheet-for-ms-project-keys/"><u>The Ultimate Cheat Sheet for MS Project Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-school-explorer-revival-strategies/"><u>Old-School Explorer Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-peak-performance-taming-vanguards-cpu-power-draw-in-windows/"><u>Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-delete-tiktok-watermarks-with-the-best-online-tools/"><u>2024 Approved Delete TikTok Watermarks with the Best Online Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-your-path-upgrading-outdated-windows-driver-tech/"><u>Clear Your Path: Upgrading Outdated Windows Driver Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-glitches-to-achieve-uninterrupted-gameplay-win-11/"><u>Overcoming Steam Glitches to Achieve Uninterrupted Gameplay Win 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/must-have-windows-11-video-editing-apps-list/"><u>Must-Have Windows 11 Video Editing Apps List</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-samsung-galaxy-a23-5g-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Samsung Galaxy A23 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-the-must-have-msistore-tools/"><u>Unlock Potential: The Must-Have MSIStore Tools</u></a></li>
<li><a href="https://extra-hints.techidaily.com/audit-your-finances-establishing-podcast-expenses/"><u>Audit Your Finances  Establishing Podcast Expenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-path-to-w11-audio-recording/"><u>Beginner's Path to W11 Audio Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-windows-11-desktop-menu-layout/"><u>Personalizing Your Windows 11 Desktop Menu Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-1011-photography-setup/"><u>Streamlining Windows 10/11 Photography Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-problematic-java-setup-on-windows-pcs/"><u>Unblocking Problematic Java Setup on Windows PCs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-pinnacle-of-new-zooids-in-panzoids/"><u>2024 Approved  The Pinnacle of New Zooids in Panzoids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-app-crash-common-issues-and-fixes/"><u>Resolving Windows App Crash: Common Issues & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-protocol-port-vulnerability-check-for-windows/"><u>Network Protocol Port Vulnerability Check for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-boosting-virtualbox-version-70-on-windows-11/"><u>Step-by-Step Guide: Boosting VirtualBox Version 7.0 on Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-inside-the-world-of-superior-screen-recording-with-recmeister/"><u>[Updated] 2024 Approved  Inside the World of Superior Screen Recording with Recmeister</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-unleash-your-ugc-making-memes-and-marks-on-fb/"><u>[Updated] In 2024, Unleash Your UGC  Making Memes and Marks on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-switching-back-the-windows-11-search-icons/"><u>Steps for Switching Back the Windows 11 Search Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-windows-notifications-for-essential-only/"><u>Adjust Windows Notifications for Essential Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-it-admin-access-restricted-on-windows/"><u>Resolving 'IT Admin Access Restricted' On Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/compelling-alternatives-to-obs-for-video-capture-for-2024/"><u>Compelling Alternatives to OBS for Video Capture for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-surprising-alerts-in-windows-security/"><u>Troubleshooting Surprising Alerts in Windows Security</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-samsung-galaxy-a05s-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Samsung Galaxy A05s Location Settings | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-uncompromised-audio-with-ffmpegs-extraction-features/"><u>2024 Approved  Uncompromised Audio with FFmpeg's Extraction Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovery-of-missing-widgets-and-icons-on-windows-11/"><u>Recovery of Missing Widgets and Icons on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-put-a-windows-computer-to-sleep/"><u>9 Ways to Put a Windows Computer to Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-elusive-windows-search-responses/"><u>Recovering Elusive Windows Search Responses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-steam-downloads-stopping-unexpected-declines/"><u>Speed up Steam Downloads: Stopping Unexpected Declines</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-truecapture-pro-for-windows-users/"><u>[New] In 2024, TrueCapture Pro for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-order-7-methods-for-windows-users-disrupted-google-drive/"><u>Restore Order: 7 Methods for Windows Users, Disrupted Google Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-taskbar-absence-during-full-screen-mode/"><u>Tackling Taskbar Absence During Full-Screen Mode</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-relevance-of-authenticity-in-insta-video-selfies-for-2024/"><u>[New] The Relevance of Authenticity in Insta Video Selfies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-overcoming-windows-run-time-errors/"><u>Unraveling the Mystery: Overcoming Windows 'Run-Time Errors'</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/captivating-audiences-with-thrilling-unboxing-vids-for-2024/"><u>Captivating Audiences with Thrilling Unboxing Vids for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-via-cli-registry-edition/"><u>Advanced Windows Customization via CLI: Registry Edition</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-the-ultimate-guide-to-online-video-editing-on-chromebook/"><u>New In 2024, The Ultimate Guide to Online Video Editing on Chromebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reveal-hidden-configurations-unearth-missing-controls-in-win11/"><u>Reveal Hidden Configurations: Unearth Missing Controls in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-mysteries-inside-its-registry-files/"><u>Unraveling Windows 11'S Mysteries: Inside Its Registry Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-gaming-picking-the-perfect-install-drive/"><u>Streamlined Gaming: Picking the Perfect Install Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-cleansing-windows-arp-cache/"><u>Understanding and Cleansing Windows ARP Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-intelligent-interface-ais-role-in-windows-evolution/"><u>The Intelligent Interface: AI's Role in Windows Evolution</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-how-to-animate-image-on-scroll-and-text-on-scroll-for-2024/"><u>New How to Animate Image on Scroll and Text on Scroll for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-0x80072f8f-0x20000-error-on-pcs/"><u>Resolving 0X80072f8f-0x20000 Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-intrusions-top-7-windows-safeguarding-methods/"><u>Preventing Intrusions: Top 7 Windows Safeguarding Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-pathway-for-purchasing-adobe-from-microsoft/"><u>Seamless Pathway for Purchasing Adobe From Microsoft</u></a></li>
</ul></div>
