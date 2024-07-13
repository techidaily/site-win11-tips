---
title: How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11
date: 2024-07-12T16:59:26.487Z
updated: 2024-07-13T16:59:26.487Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11
excerpt: This Article Describes How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11
keywords: Windows Lockout Management,Extend Lockout Time,Change Login Delay,Reset Failed Logon Timer,Adjust Windows Security Duration,Increase Lockout Interval,Modify Login Lockout Time
thumbnail: https://thmb.techidaily.com/8979e8080587e2a8dc2c43407031e5a8747618e7ac4eca2f3b40cffb1bdf15c9.jpg
---

## How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11

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

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/navigate-through-clipchamps-windows-11-install-troubles/"><u>Navigate Through ClipChamp's Windows 11 Install Troubles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-removing-signature-rejection-on-pcs/"><u>Strategies for Removing Signature Rejection on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recommended-procedures-for-dying-wireless-controller/"><u>Recommended Procedures for Dying Wireless Controller</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/embrace-the-future-facebook-video-autoplay/"><u>Embrace the Future  Facebook Video Autoplay</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-maximizing-your-steam-experience-with-a-switch-pro-controller/"><u>[New] Maximizing Your Steam Experience with a Switch Pro Controller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-tasks-with-these-8-best-rated-window-pomodoros/"><u>Streamline Your Tasks With These 8 Best-Rated Window Pomodoros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-missing-mcuicnt-file-execution-issue-on-windows/"><u>Tackling Missing McUICnt File Execution Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-clear-desktop-instructions-for-windows-recycle-bin-auto-empty/"><u>Master Clear Desktop: Instructions for Windows Recycle Bin Auto-Empty</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-top-15-windows-10-recording-applications-reviewed/"><u>[Updated] In 2024, Top 15 Windows 10 Recording Applications Reviewed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-youtube-captioning-for-clearer-communication/"><u>In 2024, YouTube Captioning for Clearer Communication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-file-operations-in-powershell-and-command-prompt/"><u>Optimizing File Operations in PowerShell & Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-record-windows-uac-notifications/"><u>Quick Steps to Record Windows UAC Notifications</u></a></li>
<li><a href="https://some-skills.techidaily.com/streamlined-method-acquire-free-secure-version-of-vlc-on-mac-for-2024/"><u>Streamlined Method  Acquire Free, Secure Version of VLC on MAC for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-definitive-top-ten-nintendo-switch-combat-apps-max-156/"><u>[New] In 2024, Definitive Top Ten Nintendo Switch Combat Apps (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snip-and-sketch-vs-prtsc-which-screen-capture-wins/"><u>Snip & Sketch Vs. PrtSc: Which Screen Capture Wins?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-program-harmony-in-os-with-win-pct-wisdom/"><u>Master Program Harmony in OS with Win-PCT Wisdom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cleanup-automating-deletion-of-files-in-windows/"><u>Quick Cleanup: Automating Deletion of Files in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-comprehensive-analysis-hero4-black-overview/"><u>[Updated] Comprehensive Analysis  Hero4 Black Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-books-8-effective-studying-tips-on-windows/"><u>Mastering the Books: 8 Effective Studying Tips on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-search-for-program-install-spots-on-pc/"><u>Mastering the Search for Program Install Spots on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-undetermined-value-messages-on-windows/"><u>Solutions for 'Undetermined' Value Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speak-write-and-transform-an-intuitive-guide-to-text-generation-with-windows-whisper/"><u>Speak, Write and Transform: An Intuitive Guide to Text Generation with Windows Whisper</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-expert-recommended-free-video-splitters-top-5-list/"><u>In 2024, Expert-Recommended Free Video Splitters Top 5 List</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-editors-dream-machine-top-portable-video-edits-tools-for-2024/"><u>[New] Editor's Dream Machine  Top Portable Video Edits Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-administrator-security-configs/"><u>Steps to Tackle Windows Administrator Security Configs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-instagram-utilizing-search-to-expand-your-filters/"><u>[New] Mastering Instagram  Utilizing Search to Expand Your Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-successfully-locating-policy-management-tools/"><u>Steps to Successfully Locating Policy Management Tools</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/tutorial-uploading-youtube-to-instagram-stories-effortlessly/"><u>Tutorial  Uploading YouTube to Instagram Stories Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-your-computers-print-command-conundrum-with-effective-tips/"><u>Solving Your Computer's Print Command Conundrum with Effective Tips.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-ai-feature-on-windows-11-microsofts-taskbar-assistant-revolutionizes-productivity/"><u>New AI Feature on Windows 11: Microsoft's Taskbar Assistant Revolutionizes Productivity</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-honor-magic-v2-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Honor Magic V2 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-oneplus-nord-n30-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do OnePlus Nord N30 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-simplified-guide-to-iphone-screen-adjustment/"><u>In 2024, Simplified Guide to iPhone Screen Adjustment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-utorrent-install-issues-on-a-windows-laptop/"><u>Navigating uTorrent Install Issues on a Windows Laptop</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-choosing-vocal-change-software-for-2024/"><u>The Ultimate Guide to Choosing Vocal Change Software for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-the-ultimate-guide-capturing-your-ps4-experience/"><u>2024 Approved  The Ultimate Guide  Capturing Your PS4 Experience</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/boosting-video-success-tips-from-top-50plus-quotes-on-tiktok-for-2024/"><u>Boosting Video Success  Tips From Top 50+ Quotes on TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opera-installer-lockdown-try-these-window-tips/"><u>Opera Installer Lockdown? Try These Window Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-administrative-controls-on-windows-defense-measures/"><u>Reversing Administrative Controls on Windows Defense Measures</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-video-selfie-mastery-tips-from-top-youtubers/"><u>2024 Approved  Video Selfie Mastery  Tips From Top YouTubers</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-steps-to-avoid-automatic-podcast-suggestions-on-spotify/"><u>In 2024, Steps to Avoid Automatic Podcast Suggestions on Spotify</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-video-editing-for-beginners-a-microsoft-guide-for-windows-users/"><u>New 2024 Approved Video Editing for Beginners A Microsoft Guide for Windows Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-techniques-for-designing-attractive-vlog-narratives/"><u>[New] Innovative Techniques for Designing Attractive Vlog Narratives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-greyed-out-waste-bin-icon-in-win11/"><u>Restoring Greyed Out Waste Bin Icon in Win11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Apple iPhone 12 mini | Dr.fone</u></a></li>
</ul></div>
