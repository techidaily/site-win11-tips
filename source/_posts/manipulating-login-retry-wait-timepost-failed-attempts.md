---
title: Manipulating Login Retry Wait Timepost-Failed Attempts
date: 2024-07-12T17:18:26.891Z
updated: 2024-07-13T17:18:26.891Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Manipulating Login Retry Wait Timepost-Failed Attempts
excerpt: This Article Describes Manipulating Login Retry Wait Timepost-Failed Attempts
keywords: Login Retry Limits,Failed Attempt Logins,Reboot Login Delay,Account Lockout Strategy,Post-Failure Wait Time,Throttle Login Retries,Manage Failed Login Pause
thumbnail: https://thmb.techidaily.com/9f7aaa7e93668c79f588e2bdc07bd0199fd9952e273ede775f53891cdecae42d.jpg
---

## Manipulating Login Retry Wait Timepost-Failed Attempts

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
<li><a href="https://win11-tips.techidaily.com/a-quick-walkthrough-to-unveil-ms-paint-windows-11/"><u>A Quick Walkthrough to Unveil MS Paint, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-settings-to-tweak-on-a-new-windows-11-install/"><u>8 Settings to Tweak on a New Windows 11 Install</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/itop-review-necessary-for-quality-recordings/"><u>ITop Review  Necessary for Quality Recordings?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719346952101-chatgpt-lite-free-self-hosted-windows-edition-with-gpt4all/"><u>ChatGPT Lite: Free Self-Hosted Windows Edition with GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-open-the-file-history-in-windows-11/"><u>8 Ways to Open the File History in Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-essential-mp3-labeling-tools-the-five-must-have-online-editors/"><u>New In 2024, Essential MP3 Labeling Tools The Five Must-Have Online Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-phantom-noise-fixing-inactive-notifications-from-phone-link/"><u>Addressing Phantom Noise: Fixing Inactive Notifications From Phone Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719258280599-jump-over-the-endless-update-hurdle-quick-fixes-now/"><u>Jump Over The Endless Update Hurdle: Quick Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-windows-11s-core-deciphering-its-registry/"><u>A Deep Dive Into Windows 11'S Core: Deciphering Its Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-easy-tips-for-memo-making-in-windows/"><u>7 Easy Tips for Memo-Making in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-xiaomi-redmi-note-13-pro-5g-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Xiaomi Redmi Note 13 Pro 5G Phone? Unlock It Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreran-guide-to-windows-11-widget-toolbar-usage/"><u>A Compreran Guide to Windows 11 Widget Toolbar Usage</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/social-media-strategists-guide-top-10-ig-video-editing-apps/"><u>Social Media Strategists' Guide  Top 10 IG Video Editing Apps</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-video-blogging-essentials-choosing-the-best-cameras-and-lenses/"><u>In 2024, Video Blogging Essentials  Choosing the Best Cameras and Lenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376942389-windows-gptmimicry-a-costless-local-edition-via-gpt4all/"><u>Windows GPTMimicry: A Costless Local Edition via GPT4All.</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-truth-behind-your-instagram-selfie/"><u>2024 Approved  The Truth Behind Your Instagram Selfie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373613156-unlock-windows-xp-potential-without-the-compatibility-tool/"><u>Unlock Windows XP Potential Without the Compatibility Tool.</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-educational-animation-made-easy-top-10-software-for-2024/"><u>Updated Educational Animation Made Easy Top 10 Software for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premium-gopro-editing-applications-on-smartphones-for-2024/"><u>Premium GoPro Editing Applications on Smartphones for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-secure-and-upgrade-your-video-conferences-top-10-recorder-choices/"><u>[New] In 2024, Secure and Upgrade Your Video Conferences - Top 10 Recorder Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-crash-code-0xc0000142-in-win11win7/"><u>Addressing Crash Code 0XC0000142 in WIN11/Win7</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/explore-the-sonic-depiction-of-a-bell-peal-for-2024/"><u>Explore the Sonic Depiction of a Bell Peal for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-crafting-visual-narratives-effective-titling/"><u>[Updated] Crafting Visual Narratives  Effective Titling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719331271081-dual-virus-scanners-think-twice-windows/"><u>Dual Virus Scanners? Think Twice, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-discords-non-display-errors-on-pc/"><u>Addressing Discord's Non-Display Errors on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-pre-ultimate-computers-to-seniors-needs/"><u>Adapting Pre-Ultimate Computers to Seniors' Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-deceptive-virus-notifications-on-windows-chrome/"><u>Addressing Deceptive Virus Notifications on Windows Chrome</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/optimize-video-publishing-timing-for-maximum-views-for-2024/"><u>Optimize Video Publishing Timing for Maximum Views for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-probing-program-hideouts-in-windows/"><u>A Practical Approach to Probing Program Hideouts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-rectifying-windows-display-defects/"><u>7 Strategies for Rectifying Windows Display Defects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-window-11-search-game-essential-tips-to-know/"><u>Ace Your Window 11 Search Game: Essential Tips to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-open-disk-management-in-windows-10-and-11/"><u>4 Ways to Open Disk Management in Windows 10 and 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-comprehensive-12-video-live-viewing-platform/"><u>2024 Approved  Comprehensive 12-Video Live Viewing Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-with-file-history-backup-on-windows/"><u>Addressing Error with File History Backup on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-hyper-v-enablement-in-win11/"><u>A Comprehensive Guide to Hyper-V Enablement in Win11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-navigating-gmail-and-zoom-for-productive-video-collaboration/"><u>2024 Approved  Navigating Gmail and Zoom for Productive Video Collaboration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360526951-arcade-mode-for-window-users-key-fixes-ahead/"><u>Arcade Mode for Window Users: Key Fixes Ahead</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-restoring-essential-features-of-photo-viewer-on-win11/"><u>A Quick Guide to Restoring Essential Features of Photo Viewer on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376441397-why-arent-window-11-thumbnail-images-displayed-solutions-available/"><u>Why Aren't Window 11 Thumbnail Images Displayed? Solutions Available</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Oppo Reno 10 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-reno-11f-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo Reno 11F 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/macs-screen-capture-champions-the-premier-tools-evaluation-for-2024/"><u>Mac's Screen Capture Champions  The Premier Tools Evaluation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-windows-11-and-parallels-confluence-in-macos/"><u>Achieving Windows 11 and Parallels Confluence in MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-cease-chromes-unintended-tabs/"><u>A Step-By-Step Guide to Cease Chrome's Unintended Tabs</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-sony-vegas-transforms-ordinary-footage-into-youtube-stardom/"><u>[New] How Sony Vegas Transforms Ordinary Footage Into YouTube Stardom</u></a></li>
</ul></div>
