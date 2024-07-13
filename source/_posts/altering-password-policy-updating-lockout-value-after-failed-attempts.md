---
title: "Altering Password Policy: Updating Lockout Value After Failed Attempts"
date: 2024-07-12T18:04:28.420Z
updated: 2024-07-13T18:04:28.420Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering Password Policy: Updating Lockout Value After Failed Attempts"
excerpt: "This Article Describes Altering Password Policy: Updating Lockout Value After Failed Attempts"
keywords: Password Update Policy,Passwords Lockout Limit,Failed Login Safeguard,Account Security Protocol,Access Control Adjustment,Password Retry Settings,Unauthorized Attempts Response
thumbnail: https://thmb.techidaily.com/728942524bb364987d92cb465ba4b4e140c040cafc9935f89ba444801c2e0013.jpg
---

## Altering Password Policy: Updating Lockout Value After Failed Attempts

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-high-fidelity-portals-to-ps3-gaming-on-pcs/"><u>[New] 2024 Approved  High-Fidelity Portals to Ps3 Gaming on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-the-comprehensible-guide-for-resolving-error-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Beating the Bug: The Comprehensible Guide for Resolving Error 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-wallpaper-a-fresh-look-every-day/"><u>Altering Windows Wallpaper: A Fresh Look Every Day</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-15-pro-passcode-not-working-drfone-by-drfone-ios/"><u>In 2024, How to Fix Apple iPhone 15 Pro Passcode not Working? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-browser-safety-on-windows-11-with-the-implementation-of-defender-aguard/"><u>Boost Browser Safety on Windows 11 with the Implementation of Defender Aguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-windows-11s-autosaverestore-techniques-and-options/"><u>Analyzing Windows 11'S AutoSave/Restore Techniques and Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-organization-in-windows-discover-5-key-folder-insights/"><u>Boost Organization in Windows - Discover 5 Key Folder Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-your-agenda-linking-to-do-to-ifttt/"><u>Automate Your Agenda: Linking To-Do to IFTTT</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/tailor-your-media-auto-scaling-videos-for-instagram-via-macos-for-2024/"><u>Tailor Your Media  Auto-Scaling Videos for Instagram via MacOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginner-friendly-guide-setting-up-the-jdk-on-windows-11/"><u>Beginner-Friendly Guide: Setting Up the JDK on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-operations-efficient-data-alignment-in-win11/"><u>Boost Operations: Efficient Data Alignment in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-win11-notepad-with-genius-mentor/"><u>Augment Win11 Notepad with Genius Mentor</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-8-safe-and-effective-methods-to-unlock-your-iphone-xs-max-without-a-passcode-by-drfone-ios/"><u>In 2024, 8 Safe and Effective Methods to Unlock Your iPhone XS Max Without a Passcode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aid-in-correcting-windows-media-tool-issue-x8007043c/"><u>Aid in Correcting Windows' Media Tool Issue X.8007043C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-not-recognized-issues-in-windows-with-these-fixes/"><u>Banish 'Not Recognized' Issues in Windows with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-windows-protection-integrating-additional-firewall-settings-into-context-menu/"><u>Amplifying Windows Protection: Integrating Additional Firewall Settings Into Context Menu</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-outro-complete-guide-plusbest-makers-and-templates/"><u>In 2024, YouTube Outro Complete Guide [+Best Makers & Templates]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-download-stalls-in-microsoft-environments/"><u>Assisting with uTorrent Download Stalls in Microsoft Environments</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-a-comprehensible-guide-to-instagrams-latest-updates/"><u>In 2024, A Comprehensible Guide to Instagram's Latest Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beneath-the-facade-programs-pause-your-pcs-prowess/"><u>Beneath the Facade, Programs Pause Your PC's Prowess</u></a></li>
<li><a href="https://extra-hints.techidaily.com/immerse-in-ideas-multitasking-activities-for-podcast-fans/"><u>Immerse in Ideas  Multitasking Activities for Podcast Fans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-microsofts-new-taskbar-helper-in-windows-11-streamlines-tasks/"><u>AI Integration: Microsoft's New Taskbar Helper in Windows 11 Streamlines Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-app-size-efficiency/"><u>Assessing Windows App Size Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-development-with-these-wsl-2-secrets/"><u>Boost Your Development with These WSL 2 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-machines-explained-how-they-stand-out/"><u>AI Machines Explained: How They Stand Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-to-windows-webcam-conversion-guide-for-windows-11-users/"><u>Android to Windows Webcam Conversion Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-hello-compatible-scanner-glitch/"><u>Addressing Windows Hello Compatible Scanner Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-copy-pasting-expertise/"><u>Boost Your Typing, Copy-Pasting Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-dynamic-background-anytime/"><u>Adjusting Your Windows Dynamic Background Anytime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11-taskbar-scaling/"><u>Adjusting Windows 11 Taskbar Scaling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminal-backdrop/"><u>Adjusting Windows Terminal Backdrop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-space-for-storage-sluggishness-sets-in/"><u>Blackview: Space for Storage, Sluggishness Sets In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-performance-by-enabling-automatic-file-deletion-in-winos/"><u>Boost System Performance by Enabling Automatic File Deletion in WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-taskbar-size-step-by-step-guide/"><u>Altering Taskbar Size: Step-by-Step Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-xiaomi-redmi-12-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Xiaomi Redmi 12 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-managing-users-via-command-prompt/"><u>Advanced Tips for Managing Users via Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/behind-closed-curtains-of-windows-how-to-open-hidden-self-assessment-tool/"><u>Behind Closed Curtains of Windows: How to Open Hidden Self-Assessment Tool</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/diminishing-sound-quality-in-adobe-rush/"><u>Diminishing Sound Quality in Adobe Rush</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-meizu-21-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Meizu 21 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-apps-with-efficient-internet-fixes/"><u>Boost Your Windows Apps with Efficient Internet Fixes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-bridging-platforms-loop-ready-setups-for-youtube-and-tv/"><u>2024 Approved  Bridging Platforms  Loop-Ready Setups for YouTube and TV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>