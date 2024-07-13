---
title: Adjusting Reset Counter After Failed Logins on Windows 10/11
date: 2024-07-12T18:03:22.318Z
updated: 2024-07-13T18:03:22.318Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Reset Counter After Failed Logins on Windows 10/11
excerpt: This Article Describes Adjusting Reset Counter After Failed Logins on Windows 10/11
keywords: Windows Login Troubleshooting,Counter Reset Guide (Windows),Successful Login Attempts,Reset Failed Logins Fix,Prevent Unauthorized Access,Secure User Credentials,Update Lockout Count
thumbnail: https://thmb.techidaily.com/5dd2f6cde3d323e673a6ae6de82e04690c6752ca51d81e51c29c7b758bb18642.jpg
---

## Adjusting Reset Counter After Failed Logins on Windows 10/11

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
<li><a href="https://screen-capture.techidaily.com/updated-freely-capture-perfection-the-leading-10-high-quality-recorders/"><u>[Updated] Freely Capture Perfection  The Leading 10 High-Quality Recorders</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-explore-the-difference-basic-plus-and-pro-in-vimeo-services-for-2024/"><u>[Updated] Explore The Difference  Basic, Plus & Pro in Vimeo Services for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-worst-javascript-failures-while-using-discord-in-win-oses/"><u>Avoiding the Worst JavaScript Failures While Using Discord in Win OSes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/how-to-add-custom-youtube-shorts-thumbnails-with-ease-in-2024/"><u>How to Add Custom YouTube Shorts Thumbnails with Ease, In 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resource-allocation-for-ntoskrnlexe/"><u>Balancing Resource Allocation for Ntoskrnl.exe</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-expert-tips-migrating-twitch-videos-to-youtube/"><u>In 2024, Expert Tips  Migrating Twitch Videos to YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-100-quagmire-with-these-simple-solutions/"><u>Beat the 100%% Quagmire with These Simple Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-pc-safety-change-your-windows-11-password/"><u>Boost PC Safety: Change Your Windows 11 Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-deadlock-in-windows-desktop-menu-navigation/"><u>Avoiding Deadlock in Windows Desktop Menu Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bargain-hunters-rejoice-key-lovers-snag-best-prices-for-lifetime-windows-11/"><u>Bargain Hunters Rejoice: Key Lovers Snag Best Prices for Lifetime Windows 11!</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-in-game-recording-a-comprehensive-review/"><u>[New] In 2024, In-Game Recording  A Comprehensive Review</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-social-media-savvy-turning-friends-into-customers-and-coins-for-2024/"><u>[New] Social Media Savvy  Turning Friends Into Customers and Coins for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/quick-playlist-streaming-your-mp3-music-library-online/"><u>Quick Playlist  Streaming Your MP3 Music Library Online</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/2024-approved-wealthy-web-showrunners/"><u>2024 Approved  Wealthy Web Showrunners</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-mastery-of-tiktok-perfecting-videos-from-your-pctablet/"><u>In 2024, Mastery of TikTok  Perfecting Videos From Your PC/Tablet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blank-screenshare-reconnecting-windows-microphone-to-google-meet/"><u>Blank Screenshare: Reconnecting Windows Microphone to Google Meet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-pitfalls-of-roblox-error-262/"><u>Avoiding Common Pitfalls of Roblox Error 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-pitfalls-of-mysterious-obs-studio-recordings/"><u>Avoiding the Pitfalls of Mysterious OBS Studio Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-net-speed-win-pc-download-acceleration-tips/"><u>Boosting Net Speed: Win-PC Download Acceleration Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advance-your-wallet-harness-w11-pro-offers-wisely/"><u>Advance Your Wallet: Harness W11 Pro Offers Wisely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-address-roblox-glitches/"><u>Approaches to Address Roblox Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alt-tab-techniques-efficiently-arrange-your-open-windows-win1110/"><u>Alt-Tab Techniques: Efficiently Arrange Your Open Windows (Win11/10)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-samsung-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Samsung Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-crashes-in-the-epic-launcher-for-win-users/"><u>Avoidance of Crashes in the Epic Launcher for Win Users</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-digital-decision-making-choosing-the-best-cropping-tool-for-2024/"><u>[Updated] Digital Decision Making  Choosing the Best Cropping Tool for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-connectivity-boost-for-windows-11-webcams/"><u>Android Connectivity Boost for Windows 11 Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-storage-efficiency-in-windows-11/"><u>Boosting Storage Efficiency in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-integrating-new-folders-into-windows-11-menu/"><u>Boosting Efficiency: Integrating New Folders Into Windows 11 Menu</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-next-level-content-creation-tools-post-vimeo/"><u>In 2024, Next-Level Content Creation Tools, Post-Vimeo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-disruptions-securing-winnet-for-peace-of-mind/"><u>Avoid Disruptions: Securing WinNet for Peace of Mind</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-top-10-free-surveillance-software-options-for-2024/"><u>New Top 10 Free Surveillance Software Options for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-zte-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock ZTE Phone without Any Data Loss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automated-password-inclusion-in-windows-file-management/"><u>Automated Password Inclusion in Windows File Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-pc-to-god-like-powers-with-windows-11/"><u>Awaken Your PC to God-Like Powers with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-copilot-arrives-on-windows-11-transforming-user-interaction/"><u>AI Copilot Arrives on Windows 11, Transforming User Interaction</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/concurrent-display-registration/"><u>Concurrent Display Registration</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-itel-s23plus-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Itel S23+ Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-webcam-integration-on-windows-11-pcs/"><u>Android Webcam Integration on Windows 11 PCs</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-windows-10-video-trimmer-top-picks-for-free-and-easy-editing/"><u>New 2024 Approved Windows 10 Video Trimmer Top Picks for Free and Easy Editing</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/navigating-the-m1-space-apples-lightest-or-heaviest-model-in-2024/"><u>Navigating the M1 Space  Apple's Lightest or Heaviest Model, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprint-to-rule-winos-apps-browsers/"><u>Blueprint to Rule WinOS Apps, Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boltgun-playtime-maximized-overcoming-computer-delays-in-warhammer-40k/"><u>Boltgun Playtime Maximized: Overcoming Computer Delays in Warhammer 40K</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-oneplus-nord-n30-5g-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on OnePlus Nord N30 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-health-through-interactive-device-tracking/"><u>Boost System Health Through Interactive Device Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-processing-closure-for-busy-windows-users/"><u>Batch-Processing Closure for Busy Windows Users</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-infinix-note-30-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Infinix Note 30 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-smooth-operations-for-11-windows-errors/"><u>Beat the Blues: Smooth Operations for 11 Windows Errors</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-guiding-you-through-youtubes-view-limitations/"><u>[New] In 2024, Guiding You Through YouTube's View Limitations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-spacious-and-slow-a-bittersweet-blend/"><u>Blackview: Spacious and Slow - A Bittersweet Blend</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-productivity-with-wordpad-embedding-commands-into-context-menus/"><u>Boosting Productivity with WordPad: Embedding Commands Into Context Menus</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/2024-approved-how-to-translate-tiktok-videos-all-you-want-to-know/"><u>2024 Approved How to Translate TikTok Videos? All You Want to Know</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-troubleshooting-error-connecting-to-the-apple-id-server-from-apple-iphone-15-plus-by-drfone-ios/"><u>In 2024, Troubleshooting Error Connecting to the Apple ID Server From Apple iPhone 15 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-real-time-performance-of-win-11-task-manager/"><u>Adjusting Real-Time Performance of Win 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-premature-edge-activation-in-w11/"><u>Avoid Premature Edge Activation in W11</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-oppo-a79-5g-frp-by-drfone-android/"><u>How Can We Bypass Oppo A79 5G FRP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-windows-store-crash-code-error-0x80072efd/"><u>Banishing Windows Store Crash Code: Error 0X80072EFD</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-culinary-crossroads-global-flavors-unleashed/"><u>In 2024, Culinary Crossroads  Global Flavors Unleashed</u></a></li>
<li><a href="https://android-unlock.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-motorola-moto-g73-5g-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Motorola Moto G73 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automatic-file-disposal-in-windows-11/"><u>Boost Efficiency with Automatic File Disposal in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-words-settings-for-consistent-openness-of-email-attachments-as-text/"><u>Adjust Word's Settings for Consistent Openness of Email Attachments as Text</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-professional-level-communication-on-skype/"><u>[Updated] 2024 Approved  Professional-Level Communication on Skype</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-cross-platform-calendar-coordination-zoom-to-your-devices/"><u>[Updated] Cross-Platform Calendar Coordination  Zoom to Your Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-winning-factors-9-pc-features-that-trump-macs/"><u>Analyzing the Winning Factors: 9 PC Features That Trump Macs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-insights-into-integrating-disjoint-windows-partitions/"><u>Advanced Insights Into Integrating Disjoint Windows Partitions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>