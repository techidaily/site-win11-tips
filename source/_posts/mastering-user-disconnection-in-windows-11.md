---
title: Mastering User Disconnection in Windows 11
date: 2024-07-12T16:46:10.217Z
updated: 2024-07-13T16:46:10.217Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering User Disconnection in Windows 11
excerpt: This Article Describes Mastering User Disconnection in Windows 11
keywords: Win11 Disconnect Mastery,Windows Severe Logout,UX Dropouts Control,Network Severance Guide,Sign-Out Efficiency Tips,Login Failure Solutions,User Detachment Techniques
thumbnail: https://thmb.techidaily.com/485101ae8f555e145174a15eda6071c25617b2b00c96089d339b8e4537366b75.jpg
---

## Mastering User Disconnection in Windows 11

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/windows-setup-guide-for-steam-deck-owners/"><u>Windows Setup Guide for Steam Deck Owners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-productivity-integrating-flow-launcher-into-daily-routine/"><u>Amplify Productivity: Integrating Flow Launcher Into Daily Routine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-system-editor-access-control-on-windows-11/"><u>Techniques for System Editor Access Control on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-high-dpi-displays-a-windows-guide/"><u>Dealing with High DPI Displays: A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-files-in-flux-top-6-methods-to-extract-and-duplicate-windows-11-folder-trails/"><u>Finding Files in Flux: Top 6 Methods to Extract and Duplicate Windows 11 Folder Trails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-system-exploration-in-win11-6-keyways-to-duplicating-file-and-folder-paths/"><u>File System Exploration in Win11: 6 Keyways to Duplicating File and Folder Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restore-deleted-run-logs/"><u>Methods to Restore Deleted Run Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-essential-7-strategies-in-windows-11-38/"><u>Maximizing Efficiency: Essential 7 Strategies in Windows 11 (38)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-to-access-mspaint-in-windows-11/"><u>Discovering How to Access MSPaint in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-can-we-unlock-our-honor-play-8t-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Honor Play 8T Phone Screen?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-from-creative-visionaries-to-paid-influencers-the-instagram-route/"><u>[New] 2024 Approved  From Creative Visionaries to Paid Influencers  The Instagram Route</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-users-should-anticipate-sudo/"><u>Why Windows Users Should Anticipate Sudo</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-20-timeless-anime-themes-making-a-mark-on-tiktok/"><u>[Updated] 2024 Approved  20 Timeless Anime Themes Making a Mark on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx939-dll-in-win11/"><u>Addressing Missing D3DX9_39 DLL in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-dilemran-of-winscripterrors/"><u>Deciphering the Dilemran of WinScriptErrors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-compatibility-challenges-with-intel-gpu/"><u>Guiding Users Through Compatibility Challenges with Intel GPU</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268439990-chrome-freeze-no-more-top-solutions-for-windows-11-users/"><u>Chrome Freeze No More: Top Solutions for Windows 11 Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-caps-lock-and-numeric-status-on-taskbar-tray-of-win11/"><u>Displaying Caps Lock & Numeric Status on Taskbar Tray of Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-efficiently-extract-onedrive-from-windows-explorer/"><u>How To Efficiently Extract OneDrive From Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-access-to-registry-tools-in-win11/"><u>How to Manage Access to Registry Tools in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-recording-basics-for-newcomers-on-win-11/"><u>Audio Recording Basics for Newcomers on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-versatile-applications-top-10-ways-to-use-powertoys/"><u>Explore Versatile Applications: Top 10 Ways to Use PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphered-defense-dont-shift-too-suddenly/"><u>Deciphered Defense? Don't Shift Too Suddenly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-management-adding-this-pc-to-windows-desktop/"><u>Window Management: Adding 'This PC' To Windows Desktop</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-home-sweet-habitat-6-basic-mc-dwellings-demystified/"><u>2024 Approved  Home Sweet Habitat  6 Basic MC Dwellings Demystified</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harnessing-the-power-of-burst-mode-for-dynamic-videos/"><u>[Updated] Harnessing the Power of Burst Mode for Dynamic Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-startup-the-comprehensive-guidebook/"><u>Master Your Windows Startup: The Comprehensive Guidebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-manual-timezone-setting-in-microsoft-os/"><u>Troubleshoot Manual Timezone Setting in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-your-onedrive-to-a-desired-spot-on-win10/"><u>Transitioning Your OneDrive to a Desired Spot on Win10</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-from-the-iphone-15-plus-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock From the iPhone 15 Plus Without Previous Owner?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Motorola Moto G23? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-navigating-youtubes-subtitle-system-download-with-ease-using-3-methods/"><u>[Updated] Navigating YouTube's Subtitle System  Download with Ease Using 3 Methods</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/recording-rivals-meet-in-2024/"><u>Recording Rivals, Meet, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-primes-textual-missteps-on-windows-11-desktops/"><u>Correct Prime's Textual Missteps on Windows 11 Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-automation-for-batch-files/"><u>Mastering Windows Automation for Batch Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-cant-access-mail-alert-on-windows-11s-mail-app/"><u>Unveiling Fixes for Can't Access Mail Alert on Windows 11'S Mail App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-full-use-of-the-control-key-in-windows-11/"><u>Enabling Full Use of the Control Key in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-linux-into-your-windows-desktop-world/"><u>Integrating Linux Into Your Windows Desktop World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-hardware-ids-retrieval-methods/"><u>Mastering Windows Hardware IDs Retrieval Methods</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-immediate-audience-monitoring-tools/"><u>[Updated] Immediate Audience Monitoring Tools</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-cutting-edge-pc-editing-techniques-enhancing-your-youtube-presence/"><u>[Updated] 2024 Approved  Cutting-Edge PC Editing Techniques  Enhancing Your YouTube Presence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-unsolicited-opens-in-ms-store-on-windows-10/"><u>Halt Unsolicited Opens in MS Store on Windows 10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/iview-harmony-ios-and-macos-slideshow-tool-for-2024/"><u>IView Harmony  IOS & macOS Slideshow Tool for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-high-quality-win11-screen-capture-pro-for-2024/"><u>[New] High-Quality Win11 Screen Capture Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-time-intensive-gpsvc-hangs/"><u>Eliminating Time-Intensive GPSVC Hangs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-hypervisorerror-blue-screen-on-windows-10-and-11/"><u>5 Ways to Fix the HYPERVISOR_ERROR Blue Screen on Windows 10 & 11</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-y100i-power-5g-by-fonelab-android-recover-music/"><u>Undelete lost music from Y100i Power 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-calculator-opening-method/"><u>Mastering Windows 11 Calculator Opening Method</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-optimal-choices-top-5-tiktok-to-gif-conversion-programs/"><u>In 2024, Optimal Choices  Top 5 TikTok-to-GIF Conversion Programs</u></a></li>
</ul></div>
