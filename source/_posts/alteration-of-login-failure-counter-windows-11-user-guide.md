---
title: "Alteration of Login Failure Counter: Windows 11 User Guide"
date: 2024-07-12T18:07:04.797Z
updated: 2024-07-13T18:07:04.797Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Alteration of Login Failure Counter: Windows 11 User Guide"
excerpt: "This Article Describes Alteration of Login Failure Counter: Windows 11 User Guide"
keywords: Win11 Login Troubleshooting,11 PC Login Fix Guide,11 User Error Logout Help,Correcting Login Failures in Windows 11,Enhancing Login Success Rate Windows 11,Resetting Failed Logins on Win11,Overcoming 11 Login Issues Guide
thumbnail: https://thmb.techidaily.com/6c7b51dcfdae2a8da726c75853a324eb9a3939b33880d7b4a364119150ff2caf.jpg
---

## Alteration of Login Failure Counter: Windows 11 User Guide

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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-chromium-os-built-in-video-capturer/"><u>[New] In 2024, Chromium OS Built-In Video Capturer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-and-reset-windows-11s-touch-keyboard-layout/"><u>Adjust and Reset Windows 11'S Touch Keyboard Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-errors-essential-tips-for-first-time-windows-11-users/"><u>Avoiding Common Errors: Essential Tips for First-Time Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11-lock-screen-effortlessly/"><u>Avoiding Windows 11 Lock Screen Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automated-folder-pairings-in-new-windows-os/"><u>Boost Efficiency with Automated Folder Pairings in New Windows OS</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-screen-recorder-showcase-apowersofts-place-in-the-market/"><u>[New] In 2024, Screen Recorder Showcase  Apowersoft's Place in the Market</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edge-safety-implement-windows-11-defender-application-guard/"><u>Boosting Edge Safety: Implement Windows 11 Defender Application Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bidding-farewell-to-ads-in-the-win-11-startup/"><u>Bidding Farewell to Ads in the Win 11 Startup</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/engage-and-inspire-viewers-animated-subscribers-in-filmora-explained/"><u>Engage and Inspire Viewers - Animated Subscribers in Filmora Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-on-windows-11-top-seven-tweaks-for-game-enthusiasts/"><u>Boosting Performance on Windows 11: Top Seven Tweaks for Game Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-not-stopping-generic-audio-issue/"><u>Addressing 'Windows Not Stopping Generic Audio' Issue</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-framefixer-analysis-all-inclusive-report/"><u>[New] FrameFixer Analysis – All-Inclusive Report</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-control-display-settings-for-windows-11-users/"><u>Advanced Control: Display Settings for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-with-smooth-directx-downloads-and-upgrades/"><u>Boost Your PC with Smooth DirectX Downloads & Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-experts-strategy-for-managing-component-services-in-w11/"><u>An Expert's Strategy for Managing Component Services in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-display-drivers-that-dont-launch-in-windows-10/"><u>Avoiding Display Drivers That Don’t Launch in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-old-directx-gaming-via-dxvk-powered-upgrades/"><u>Amplifying Old DirectX Gaming via DXVK-Powered Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-hurdles-with-these-three-steps-to-activate-telnet-on-wins/"><u>Avoid Hurdles with These Three Steps to Activate Telnet on Wins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-customized-windows-cmd-tricks-and-tips/"><u>Boost Productivity: Customized Windows Cmd Tricks and Tips</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-top-picks-user-friendly-software-for-new-game-recorders-and-editors/"><u>[Updated] In 2024, Top Picks  User-Friendly Software for New Game Recorders & Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/a-step-by-step-igtv-translation-guide/"><u>A Step-By-Step IGTV Translation Guide</u></a></li>
<li><a href="https://discord-videos.techidaily.com/incorporating-leadership-in-your-discord-network/"><u>Incorporating Leadership in Your Discord Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adopt-a-streamlined-approach-to-input-customization/"><u>Adopt a Streamlined Approach to Input Customization</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-melodypulse-recorder-downloads-guide/"><u>[Updated] In 2024, Melodypulse Recorder Downloads Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-windows-apps-struggling-to-connect-to-the-internet-try-these-fixes/"><u>Are Your Windows Apps Struggling to Connect to the Internet? Try These Fixes</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-oppo-find-x6-pro-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Oppo Find X6 Pro Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-directional-audio-with-windows-earbuds/"><u>Balancing Directional Audio with Windows Earbuds</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-compiling-a-database-of-realistic-dog-sounds-for-media-use/"><u>Updated Compiling a Database of Realistic Dog Sounds for Media Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-blank-spaces-on-your-screen-icons-revival-guide/"><u>Avoid Blank Spaces on Your Screen: Icons Revival Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-write-access-denial-errors-in-windows-11-system/"><u>Addressing Write Access Denial Errors in Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-eluding-windows-11-explorer-errors/"><u>Best Practices for Eluding Windows 11 Explorer Errors</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/gently-reducing-sound-levels-in-operating-systems/"><u>Gently Reducing Sound Levels in Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-a-guide-to-setting-up-hyper-v-on-win-11-home/"><u>Boost Your PC: A Guide to Setting Up Hyper-V on Win 11 Home</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>