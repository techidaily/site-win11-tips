---
title: Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11
date: 2024-07-12T17:30:09.223Z
updated: 2024-07-13T17:30:09.223Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11
excerpt: This Article Describes Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11
keywords: Windows Login Security,Failed Sign-In Protocols,Account Lockout Settings,Windows 10/11 Safeguards,Limit Unauthorized Access,Sign-In Failure Response,Post-Failure Policy Update
thumbnail: https://thmb.techidaily.com/07cfabd2fe9acb782e30cca8205dc0f557a2c3371dbf02532bc0633c00063d56.jpg
---

## Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11

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
<li><a href="https://win11-tips.techidaily.com/enabling-gestures-for-efficient-browsing-in-edge-win-11-edition/"><u>Enabling Gestures for Efficient Browsing in Edge, Win 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fix-guide-combatting-a-non-active-wsresetexe/"><u>The Ultimate Fix Guide: Combatting a Non-Active WSReset.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-edge-linger-handling-windows-11-background-tasks/"><u>Does Edge Linger? Handling Windows 11 Background Tasks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/shine-above-the-rest-creating-a-distinctive-mark-in-tiktok-for-2024/"><u>Shine Above the Rest  Creating a Distinctive Mark in TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-wi-fi-potential-in-windows-11-with-these-tips/"><u>Unlock Full Wi-Fi Potential in Windows 11 with These Tips</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-edit-youtube-videos-in-final-cut-pro/"><u>[Updated] How to Edit YouTube Videos in Final Cut Pro</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-2024-approved-what-is-an-ai-video-editor/"><u>Updated 2024 Approved What Is an AI Video Editor?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-toggle-smartscreen-filters-in-windows-11/"><u>Steps to Toggle SmartScreen Filters in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/running-smooth-windows-1110-now-has-amd-graphics-drivers/"><u>[RUNNING SMOOTH] Windows 11/10 Now Has AMD Graphics Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-how-to-engage-telnet-securely/"><u>Windows 11: How to Engage Telnet Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-a-convenient-upgrade-notification-toolbar-in-windows-1111/"><u>Adding a Convenient Upgrade Notification Toolbar in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-to-follow-pathway-accessing-wordpad-on-pcs/"><u>Easy-to-Follow Pathway: Accessing WordPad on PCs</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-streamline-content-explore-the-10-best-youtube-trimmer-tools/"><u>In 2024, Streamline Content  Explore the 10 Best YouTube Trimmer Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-unveiling-hidden-functionalities-of-instagrams-question-marker/"><u>[New] 2024 Approved  Unveiling Hidden Functionalities of Instagram’s Question Marker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-printer-settings-in-windows-environment/"><u>Seamless Integration of Printer Settings in Windows Environment</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-all-encompassing-kinetic-review-2023/"><u>[New] All-Encompassing Kinetic Review 2023</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-premier-list-top-free-video-recorder-software-explored/"><u>In 2024, Premier List - Top Free Video Recorder Software Explored</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-7-reliable-video-merging-tools-with-no-watermark-output/"><u>2024 Approved 7 Reliable Video Merging Tools with No Watermark Output</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-blur-free-photography-ranked-10-best-web-editing-tools/"><u>[Updated] Blur-Free Photography  Ranked 10 Best Web Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wisdom-three-routes-to-your-games-data/"><u>Windows Wisdom: Three Routes to Your Games' Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-system-crafting-a-custom-uninstall-menu-for-win/"><u>Simplify Your System: Crafting a Custom Uninstall Menu for Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-speed-status-in-windows-desktop-area/"><u>Effortless Speed Status in Windows Desktop Area</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/professionals-choice-ranking-the-top-9-microphone-apps/"><u>Professional's Choice  Ranking the Top 9 Microphone Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ram-management-for-effective-cross-platform-communication/"><u>Efficient RAM Management for Effective Cross-Platform Communication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-read-only-mode-a-guide-for-windows-users/"><u>Disabling Read-Only Mode: A Guide for Windows Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-nokia-c110-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Nokia C110 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-password-entry-for-instantaneous-win-11-connections/"><u>Bypassing Password Entry for Instantaneous Win 11 Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-digital-life-winning-crypto-apps-ranked-150-chars/"><u>Secure Your Digital Life: Winning Crypto Apps Ranked (150 Chars)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-tailoring-video-content-for-igtv-with-horizontal-footage/"><u>In 2024, Tailoring Video Content for IGTV with Horizontal Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-effective-steps-for-lifelong-disabling-of-windows-defender/"><u>5 Effective Steps for Lifelong Disabling of Windows Defender</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-subtitles-made-simple-top-10-zero-cost-downloaders/"><u>[Updated] Subtitles Made Simple  Top 10 Zero-Cost Downloaders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-eliminating-no-servers-found-in-apex-legends-(156-chars/"><u>Troubleshooting: Eliminating 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/engage-your-phones-dialer-with-ease-windows-11/"><u>Engage Your Phone's Dialer with Ease, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synchronizing-sound-pathways-resolving-paudio-in-winaudacity/"><u>Synchronizing Sound Pathways: Resolving PAudio in WINAudacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-mail-troubleshooting-unraveling-the-zero-x-eight-oh-three-one-f-mystery/"><u>Windows Mail Troubleshooting: Unraveling the Zero X Eight Oh Three One F Mystery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-user-dissatisfaction-with-microsofts-latest-update/"><u>Decoding User Dissatisfaction with Microsoft's Latest Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-system-controls-learn-how-to-use-4-techniques-for-disk-editor-on-win11/"><u>Seamless System Controls: Learn How to Use 4 Techniques for Disk Editor on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-efficiency-5-best-apps-to-create-animated-clock-screen-savers-on-pcs/"><u>Accelerate Efficiency: 5 Best Apps to Create Animated Clock Screen Savers on PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tips-and-tricks-to-tell-if-your-iphone-12-is-unlocked-by-drfone-ios/"><u>Tips And Tricks To Tell if Your iPhone 12 Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-grandmas-old-computer-for-better-use/"><u>Transform Your Grandma’s Old Computer for Better Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-subtle-art-of-windows-11s-user-information-extraction/"><u>The Subtle Art of Windows 11'S User Information Extraction</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-xiaomi-redmi-k70e-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Xiaomi Redmi K70E? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-event-viewer-issues-on-windows-11/"><u>Solving Event Viewer Issues on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-fury-not-frustration-fixing-lag-in-sw-battlefront-2/"><u>Unleash Fury, Not Frustration: Fixing Lag in SW Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-check-your-windows-computers-model-name/"><u>6 Ways to Check Your Windows Computer's Model Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-streamlining-display-with-adjusted-desk-icons/"><u>Title: Streamlining Display with Adjusted Desk Icons</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-the-apple-iphone-8-sim-lock-4-easy-methods-by-drfone-ios/"><u>How To Unlock The Apple iPhone 8 SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-ms-teams-error-80080300-fixes-for-w11-users/"><u>Breaking Down MS Teams Error 80080300: Fixes for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-study-experience-dive-into-asus-vivobook-s-15/"><u>Elevate Your Study Experience: Dive Into ASUS Vivobook S 15</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-navigating-noise-nullification-an-in-depth-user-manual-for-online-auditory-enhancement/"><u>2024 Approved Navigating Noise Nullification An In-Depth User Manual for Online Auditory Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-how-to-reinstall-java-correctly/"><u>Unlocking Windows: How to Reinstall Java Correctly</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/transform-your-videos-into-cinematic-masterpieces-with-fcpx-for-2024/"><u>Transform Your Videos Into Cinematic Masterpieces with FCPX for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-chrome-blackouts/"><u>Taming Windows Chrome Blackouts</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/uick-ascent-to-youtube-affiliates-with-10k-vistas/"><u>[New] Quick Ascent to YouTube Affiliates with 10K Vistas</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-framelock-the-future-of-screen-capturing/"><u>[New] 'Framelock' – The Future of Screen Capturing?</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-elevating-self-presence-expert-guidance-to-duplicating-oneself-on-tiktok/"><u>[Updated] Elevating Self-Presence  Expert Guidance to Duplicating Oneself on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-git-operations-github-desktop-and-windows-11-explained/"><u>Simplifying Git Operations: GitHub Desktop and Windows 11 Explained</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/livestream-launchpad-duel-go-with-xsplit-or-opt-for-obs-in-2024/"><u>Livestream Launchpad Duel  Go with XSplit or Opt for OBS, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-authorization-snags-head-on/"><u>Tackling Windows Authorization Snags Head-On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/calculating-filesize-and-capacity-the-ultimate-powershell-exercise/"><u>Calculating Filesize and Capacity: The Ultimate PowerShell Exercise</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-fb-stream-downloading-on-different-operating-systems/"><u>[New] In 2024, FB Stream Downloading on Different Operating Systems</u></a></li>
</ul></div>
