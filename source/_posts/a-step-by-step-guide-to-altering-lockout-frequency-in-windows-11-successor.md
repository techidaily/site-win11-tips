---
title: A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
date: 2024-07-12T17:58:42.262Z
updated: 2024-07-13T17:58:42.262Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
excerpt: This Article Describes A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
keywords: Window's Lockout Tweaks,Lockout Modification Guide,PC Security Settings,Increase Lockout Time,User Account Access Control,Windows Adjustments Quick,Manage Lockout Frequency
thumbnail: https://thmb.techidaily.com/bab37a5357094e09dd42f37d3cc78e25fe907bbcf4a7b3121bebc119dc83e730.jpg
---

## A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/what-does-s-mode-imply-in-windows-11-upgrade/"><u>What Does 'S Mode' Imply in Windows 11 Upgrade?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-power-enable-the-outlook-preview-app/"><u>Unlock Windows' Power: Enable the Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-most-reliable-brightness-tools-for-windows-multi-display-users/"><u>The 6 Most Reliable Brightness Tools For Windows Multi-Display Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhindered-wi-fi-on-your-desktop-9-strategies-for-win11-users/"><u>Unhindered Wi-Fi on Your Desktop: 9 Strategies for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-workflow-programmatic-shortcuts-in-winos/"><u>Streamline Workflow: Programmatic Shortcuts in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-straightforward-steps-to-engage-repair-tool/"><u>10 Straightforward Steps to Engage Repair Tool</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-bring-your-videos-to-life-border-magic-on-ig/"><u>[New] In 2024, Bring Your Videos to Life  Border Magic on IG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-private-data-from-apple-iphone-7-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Private Data From Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-top-10-scholarly-channels-on-youtube-for-history-aficionados/"><u>[New] 2024 Approved  Top 10 Scholarly Channels on Youtube for History Aficionados</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tech-companion-asus-vivobook-s-15-review/"><u>The Ultimate Tech Companion: Asus Vivobook S 15 Review</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unified-content-designation-system-for-tech-applications/"><u>Unified Content Designation System for Tech Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-to-windows-birthplace-points/"><u>Trailblazing to Windows' Birthplace Points</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-the-ultimate-guide-to-splice-video-editing-capabilities-and-more/"><u>Updated 2024 Approved The Ultimate Guide to Splice Video Editing Capabilities and More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-safest-and-cutest-toy-drones-for-children/"><u>In 2024, Safest and Cutest Toy Drones for Children</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-ace-your-youtube-livestreams-mastering-broadcast-techniques-using-wirecast/"><u>[New] Ace Your Youtube Livestreams  Mastering Broadcast Techniques Using WireCast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-top-5-grievances-from-windows-11-users/"><u>Unveiling the Top 5 Grievances From Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-your-schedule-how-to-reset-windows-time-service/"><u>Sync Your Schedule: How to Reset Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-changing-app-size-using-pc-keys-on-windows-11/"><u>Tips for Changing App Size Using PC Keys on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steer-clear-of-stuck-arrows-in-windows/"><u>Steer Clear of Stuck Arrows in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-xbox-game-pass-error-0x000-on-windows-11-systems/"><u>Understanding and Correcting Xbox Game Pass Error 0X000_ on Windows 11 Systems</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-subtitle-edit-mac-alternative-find-your-new-go-to-subtitle-editor/"><u>2024 Approved Subtitle Edit Mac Alternative Find Your New Go-To Subtitle Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-seamlessly-reorganize-video-playlists-on-yt-for-2024/"><u>[Updated] How to Seamlessly Reorganize Video Playlists on YT for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-free-audio-magic-at-your-fingertips-the-essential-top-10-sound-blending-software/"><u>Updated Free Audio Magic at Your Fingertips The Essential Top 10 Sound Blending Software</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-unlock-the-power-of-voice-best-free-mac-speech-recognition-software-for-2024/"><u>New Unlock the Power of Voice Best Free Mac Speech Recognition Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-setup-a-closer-look/"><u>Windows 11 Setup: A Closer Look</u></a></li>
<li><a href="https://some-skills.techidaily.com/textual-tricks-for-tickling-funny-bones-for-2024/"><u>Textual Tricks for Tickling Funny Bones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unanticipated-error-messages-in-wins-secure/"><u>Tackling Unanticipated Error Messages in WINS Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-dilemma-obs-not-opening-on-windows/"><u>Resolving the Dilemma: OBS Not Opening on Windows</u></a></li>
</ul></div>
