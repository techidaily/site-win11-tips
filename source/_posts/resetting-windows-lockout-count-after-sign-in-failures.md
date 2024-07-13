---
title: Resetting Windows Lockout Count After Sign-In Failures
date: 2024-07-12T17:04:57.906Z
updated: 2024-07-13T17:04:57.906Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Windows Lockout Count After Sign-In Failures
excerpt: This Article Describes Resetting Windows Lockout Count After Sign-In Failures
keywords: Reset Windows Password,Unlock Windows Error,Windows Login Failed,Signin Lockout Fix,Account Access Blocked,Regain Windows Entry,Recover Lost Credentials
thumbnail: https://thmb.techidaily.com/33d2c913be55d31e549acb89b4370208c20960b474ce8b9b8af13ad1eeef19a7.jpg
---

## Resetting Windows Lockout Count After Sign-In Failures

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
<li><a href="https://youtube-video-recordings.techidaily.com/new-cutting-edge-guide-to-youtube-video-distribution-via-facebook/"><u>[New] Cutting-Edge Guide to YouTube Video Distribution via Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-control-over-your-pc-in-winos/"><u>Unlock Full Control Over Your PC in WinOS</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-the-tide-restoring-daylight-from-dark-theme/"><u>Turning the Tide: Restoring Daylight From Dark Theme</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-15-youtube-starter-templates-a-guide-to-popularity/"><u>2024 Approved  15 YouTube Starter Templates  A Guide to Popularity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-flawed-windows-safety-features-in-win-11/"><u>Fixing Flawed Windows Safety Features in Win 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-breakdown-of-earnings-how-much-does-a-clicky-make/"><u>[Updated] In 2024, Breakdown of Earnings  How Much Does a Clicky Make?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-navigating-animated-ads-to-skyrocket-facebook-roi-for-2024/"><u>[Updated] Navigating Animated Ads to Skyrocket Facebook ROI for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-entry-into-your-windows-11s-application-arcade/"><u>Effortless Entry Into Your Windows 11'S Application Arcade</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-the-ultimate-guide-to-switch-game-screencasting/"><u>In 2024, The Ultimate Guide to Switch Game Screencasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-the-windows-11-taskbar-teams-chat-removal-will-impact-you/"><u>How the Windows 11 Taskbar Teams Chat Removal Will Impact You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cybersecurity-insight-key-windows-activities-that-could-conceal-threats/"><u>Cybersecurity Insight: Key Windows Activities That Could Conceal Threats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-directx-setup-couldnt-download-the-file-error-on-windows/"><u>How to Fix the “DirectX Setup Couldn’t Download the File” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-license-expiration-alert-on-windows-11/"><u>Addressing 'License Expiration' Alert on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-2023-endless-ears-on-facebook-downloads/"><u>[New] In 2024, 2023  Endless Ears on Facebook Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ascertain-hdd-or-ssd-through-windows-settings/"><u>Ascertain HDD or SSD Through Windows Settings</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-vivo-g2-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Vivo G2? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-improving-windows-11s-trouble-resolution-tools/"><u>Bridging Gaps: Improving Windows 11'S Trouble Resolution Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-the-status-bar-a-guide-to-including-a-weather-icon-in-windows-11/"><u>Customize the Status Bar: A Guide to Including a Weather Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-local-sam-service-error-on-computers/"><u>Fix for Local SAM Service Error on Computers</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-accelerate-vimeo-videos-the-guide-for-2024/"><u>[Updated] Accelerate Vimeo Videos  The Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-window-management-active-periods-not-permanent-disruptions/"><u>Efficient Window Management: Active Periods, Not Permanent Disruptions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-screencapturepro-review-expert-insights-and-comparisons-for-2024/"><u>[New] ScreenCapturePro Review  Expert Insights and Comparisons for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-decode-and-clear-windows-10s-activity-archive/"><u>How to Decode and Clear Windows 10'S Activity Archive</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-comprehensive-guide-to-disconnecting-discord-servers/"><u>[Updated] Comprehensive Guide to Disconnecting Discord Servers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-9-irritating-windows-11-layouts/"><u>Unraveling 9 Irritating Windows 11 Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-cost-free-windows-audio-cleaners/"><u>Top 5 Cost-Free Windows Audio Cleaners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-diskusage-for-in-depth-drive-space-examination/"><u>Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/iconic-inning-cameo-examination-for-2024/"><u>Iconic Inning - Cameo Examination for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unparalleled-selection-of-budget-stock-media-sites/"><u>[New] Unparalleled Selection of Budget Stock Media Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focusing-gpo-application-one-user-approach-for-windows-1111/"><u>Focusing GPO Application: One-User Approach for Windows 11/11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-truth-about-magix-video-pro-xs-performance/"><u>[New] The Truth About Magix Video Pro X's Performance</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-techniques-for-reducing-tempo-in-audio-waves/"><u>New 2024 Approved Techniques for Reducing Tempo in Audio Waves</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-video-editing-mastery-online-tutorials-for-beginners-and-pros/"><u>New In 2024, Video Editing Mastery Online Tutorials for Beginners and Pros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-ai-enhance-windows-11-usability/"><u>How Does AI Enhance Windows 11 Usability?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-snipping-tool-with-a-simple-key-combo-on-win-11/"><u>Activating Snipping Tool with a Simple Key Combo on Win 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-streamline-your-workflow-quick-and-easy-gopro-video-editing-tips/"><u>New 2024 Approved Streamline Your Workflow Quick and Easy GoPro Video Editing Tips</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pathway-to-enlisting-world-class-cinematographers/"><u>2024 Approved  Pathway to Enlisting World-Class Cinematographers</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-revolutionize-your-edits-top-premiere-pro-transition-tools/"><u>Updated Revolutionize Your Edits Top Premiere Pro Transition Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-step-by-step-mobile-thumbnail-creation-for-compelling-youtube-content/"><u>[New] Step by Step Mobile Thumbnail Creation for Compelling YouTube Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-constant-windows-printer-selection/"><u>Guidelines for Constant Windows Printer Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-lowering-windows-acoustic-amplifiers/"><u>Guide to Lowering Windows Acoustic Amplifiers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-creative-composition-selecting-your-favorite-snap-augments/"><u>[New] 2024 Approved  Creative Composition  Selecting Your Favorite Snap Augments</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/you-need-to-know-about-vanishing-shorts-thumbnails-on-youtube-for-2024/"><u>What You Need to Know About Vanishing Shorts Thumbnails on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microphone-blackout-during-powerpoint-video-recording/"><u>Fixing Microphone Blackout During PowerPoint Video Recording</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-from-novice-to-veteran-implementing-roles-in-discord/"><u>[Updated] From Novice to Veteran  Implementing Roles in Discord</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-apex-legends-mastery-exploring-single-platform-potential/"><u>[Updated] 2024 Approved  Apex Legends Mastery  Exploring Single Platform Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-history-on-windows-runs/"><u>Addressing Missing History on Windows Runs</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-itel-a60-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Itel A60 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-process-of-altering-window-11-admin-identity/"><u>Unveiling the Process of Altering Window 11 Admin Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/complete-guide-to-disabling-the-windows-subsystem/"><u>Complete Guide to Disabling the Windows Subsystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-opengl-error-3-nvidia-solutions-win1011/"><u>Eliminating OpenGL Error 3: Nvidia Solutions (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-non-booting-windows-hiberflattening/"><u>Cure for Non-Booting Windows HiberFlattening</u></a></li>
</ul></div>
