---
title: Customizing Failed Sign In Wait Duration in Windows
date: 2024-08-23T07:00:55.125Z
updated: 2024-08-24T07:00:55.125Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Failed Sign In Wait Duration in Windows
excerpt: This Article Describes Customizing Failed Sign In Wait Duration in Windows
keywords: Shorten Login Time,Failure Delay Adjustment,Extend Sign-In Pause,Reduce Failed Attempts Wait,Personalized Login Pause,Increase Error Recovery Time,Tailor Sign-In Retry Delay
thumbnail: https://thmb.techidaily.com/84772a0e20318a50277b6d80239d31259f3d754cba45388a4148935e78d13735.jpg
---

## Customizing Failed Sign In Wait Duration in Windows

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-boosting-business-top-10-highlight-optimization-hacks/"><u>[New] Boosting Business  Top 10 Highlight Optimization Hacks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-new-to-vector-art-dive-into-basics-forms-and-software/"><u>[New] New to Vector Art? Dive Into Basics, Forms, and Software</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-sonicsoothsayer-listening-inspection-report-for-2024/"><u>[New] SonicSoothsayer  Listening Inspection Report for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-unlock-xps-movie-magic-software-essentials/"><u>[New] Unlock XP's Movie Magic Software Essentials</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-cost-efficient-top-screen-recorder-apps-for-chromeos/"><u>[Updated] 2024 Approved  Cost-Efficient Top Screen Recorder Apps for ChromeOS</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fb-video-downloader-pro-mp4-archive-now-available/"><u>[Updated] FB Video Downloader Pro  MP4 Archive Now Available</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-seamless-transitions-made-simple-screen-record-with-aiseesoft/"><u>[Updated] In 2024, Seamless Transitions Made Simple  Screen Record With Aiseesoft</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-dissecting-a-day-in-the-life-hero5-edition/"><u>2024 Approved  Dissecting a Day in the Life  Hero5 Edition</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premium-audio-alerts-excellent-sites-compilation/"><u>2024 Approved  Premium Audio Alerts  Excellent Sites Compilation</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-securing-memories-a-comprehensive-guide-for-scanning-and-storing-vintage-photos/"><u>2024 Approved  Securing Memories  A Comprehensive Guide for Scanning and Storing Vintage Photos</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-apps-for-perfecting-picture-framing/"><u>Best Apps for Perfecting Picture Framing</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/best-free-introduction-software-for-youtubers/"><u>Best Free Introduction Software for Youtubers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capturing-seconds-at-a-time-the-art-of-phantom-slow-motion-for-2024/"><u>Capturing Seconds at a Time  The Art of Phantom Slow Motion for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-and-its-access-to-timely-information-what-it-means-for-us/"><u>ChatGPT and Its Access to Timely Information: What It Means for Us</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-print-settings-for-windows-11-edge-shield-mode/"><u>Configuring Print Settings for Windows 11 Edge Shield Mode</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/craft-cartoony-snaps-master-snapchats-anime-filters-guide/"><u>Craft Cartoony Snaps  Master Snapchat’s Anime Filters Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-walkthrough-changing-nat-type-in-win11-and-10/"><u>Detailed Walkthrough: Changing NAT Type in Win11 & 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-fixing-event-viewer-problems/"><u>Diagnosing and Fixing Event Viewer Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-workflow-with-process-management-and-aesthetic-overhaul-in-w11/"><u>Elevate Workflow with Process Management & Aesthetic Overhaul in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-chromiums-network-access-over-windows-security-barrier/"><u>Enabling Chromium's Network Access Over Windows Security Barrier</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/essential-camera-techniques-for-novice-filmmakers/"><u>Essential Camera Techniques for Novice Filmmakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-enigma-of-error-0x0000004e-in-win11/"><u>Fixing the Enigma of Error 0X0000004E in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-cc-errors-a-step-by-step-guide/"><u>Fixing Windows 11 CC Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-most-common-anydesk-failures/"><u>Fixing Windows' Most Common AnyDesk Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-portable-software-menu-to-windows-11-and-11/"><u>How to Add a Portable Software Menu to Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-server-stumbled-microsoft-store-error-in-windows-11-and-11/"><u>How to Fix the “Server Stumbled” Microsoft Store Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-optimize-windows-storage-spotting-large-disk-usage/"><u>How to Optimize Windows Storage: Spotting Large Disk Usage</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-infinix-zero-5g-2023-turbo-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Infinix Zero 5G 2023 Turbo Without PUK Codes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-can-you-unlock-iphone-14-pro-max-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>In 2024, Can You Unlock iPhone 14 Pro Max After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-deciphering-the-code-understanding-what-unlisted-on-youtube-means/"><u>In 2024, Deciphering the Code  Understanding What 'Unlisted' On YouTube Means</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-fixing-the-obs-fullscreen-hurdle/"><u>In 2024, Fixing the OBS Fullscreen Hurdle</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-apple-iphone-15-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on Apple iPhone 15</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-from-apple-iphone-14-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID From Apple iPhone 14 without Password?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-art-of-format-transmutation-srt-to-ssa-and-more/"><u>In 2024, The Art of Format Transmutation  SRT to SSA & More</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-oppo-a2-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Oppo A2 Android SIM Unlock APK</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-samsung-galaxy-s23-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Samsung Galaxy S23 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-viewer-payouts-for-video-engagement/"><u>In 2024, Viewer Payouts for Video Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-tips-operating-the-toolbar-in-mspcm-win11/"><u>Key Tips: Operating the Toolbar in MSPCM Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-digital-drawing-embrace-4-essential-updates-to-paint/"><u>Mastering Digital Drawing - Embrace 4 Essential Updates to Paint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-inaccessible-delete-switch-in-windows-11-pins/"><u>Overcoming Inaccessible Delete Switch in Windows 11 PINs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-challenges-for-fbm-connectivity/"><u>Overcoming Windows Challenges for FBM Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-desktop-spaces-optimal-size-in-win11/"><u>Perfecting Desktop Spaces: Optimal Size in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-repairing-frequent-rainmeter-hiccups/"><u>Quick Guide to Repairing Frequent Rainmeter Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-reviving-a-sluggish-windows-11-experience/"><u>Quick Tips: Reviving a Sluggish Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-invalid-pc-name-in-windows-11/"><u>Remedying Invalid PC Name in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-non-working-outlook-automated-filters-in-windows/"><u>Restarting Non-Working Outlook Automated Filters in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-seamless-operation-of-ps-windows-version/"><u>Restoring Seamless Operation of PS Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revival-tactics-restoring-microsoft-store-on-win-11-and-11/"><u>Revival Tactics: Restoring Microsoft Store on Win 11 & 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reviving-your-windows-scanner-a-step-by-step-guide/"><u>Reviving Your Windows Scanner: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-server-stumbled-error-in-windows-11-and-11-store/"><u>Steps to Overcome Server Stumbled Error in Windows 11 & 11 Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reduce-windows-browser-process-count/"><u>Steps to Reduce Windows' Browser Process Count</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-gaming-experience-with-windows-software/"><u>Superior Gaming Experience with Windows Software</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-compact-powerhouse-exploring-the-gameplay-and-savings-of-the-nintendo-switch-lite/"><u>The Compact Powerhouse: Exploring the Gameplay and Savings of the Nintendo Switch Lite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-enhancing-productivity-using-wsl-2/"><u>Top Strategies: Enhancing Productivity Using WSL 2</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ated-free-tools-for-high-res-youtube-cover-extraction/"><u>Top-Rated Free Tools for High-Res YouTube Cover Extraction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workday-top-9-motivations-to-switch-to-windows-outlook/"><u>Transform Your Workday: Top 9 Motivations to Switch to Windows' Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-ordinary-into-exquisite-windows-outlook-calendar-tactics/"><u>Transforming Ordinary Into Exquisite: Windows Outlook Calendar Tactics</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-vivo-y100i-power-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Vivo Y100i Power 5G Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-greyed-out-pin-deletion-command-on-pc/"><u>Unlocking Greyed-Out Pin Deletion Command on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-pc-from-nvidias-geforce-now-error-0xc0f1103f/"><u>Unlocking Windows PC From Nvidia's GeForce Now Error 0Xc0f1103f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-health-5-key-steps-for-device-status-tracking/"><u>Windows 11 Health: 5 Key Steps for Device Status Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-live-streaming-intel-graphics-recording-tips/"><u>Winning at Live Streaming: Intel Graphics Recording Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>