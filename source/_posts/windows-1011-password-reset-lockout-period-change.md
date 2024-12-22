---
title: Windows 10/11 Password Reset Lockout Period Change
date: 2024-12-21T00:39:44.268Z
updated: 2024-12-21T19:11:35.332Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows 10/11 Password Reset Lockout Period Change
excerpt: This Article Describes Windows 10/11 Password Reset Lockout Period Change
keywords: Windows Password Change,10/11 Lockout Period Update,Windows Login Lockout,Reset Windows Passwords,Windows Security Settings,Change Window Password Lock,Windows 10/11 Account Access Control
thumbnail: https://thmb.techidaily.com/d37006e5965cff133da2576b0b3455692491cf1f8c58029bf90db9237f948dc9.jpg
---

## Windows 10/11 Password Reset Lockout Period Change

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-unlocking-views-youtube-thumbnail-dimension-strategies/"><u>[New] 2024 Approved Unlocking Views YouTube Thumbnail Dimension Strategies</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-effortless-film-logging-how-to-use-devices-like-pros/"><u>[Updated] Effortless Film Logging How to Use Devices Like Pros</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-how-to-add-friends-on-discord/"><u>[Updated] In 2024, How to Add Friends on Discord</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/canon-pro-100-driver-download-and-installation-for-windows-users-hassle-free-setup/"><u>Canon PRO 100 Driver Download & Installation for Windows Users - Hassle-Free Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commence-the-telling-in-windows-11-ecosystem/"><u>Commence the Telling in Windows 11 Ecosystem</u></a></li>
<li><a href="https://tech-hub.techidaily.com/complete-overhaul-of-your-smartwatch-a-detailed-apple-watch-reset-process-insights/"><u>Complete Overhaul of Your Smartwatch: A Detailed Apple Watch Reset Process (Insights )</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demolishing-the-empty-directory-problem-windows-0x80070091-hurdle/"><u>Demolishing the Empty Directory Problem: Windows' 0X80070091 Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-conventional-to-cutting-edge-the-shift-in-os-features/"><u>From Conventional to Cutting-Edge: The Shift in OS Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-pubg-battlegrounds-not-saving-settings-in-windows-1110/"><u>How to Fix PUBG: Battlegrounds Not Saving Settings in Windows 11/10</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-nokia-g42-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Nokia G42 5G FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-elevated-access-in-windows-11-settings/"><u>Integrating Elevated Access in Windows 11 Settings</u></a></li>
<li><a href="https://printer-issues.techidaily.com/make-windows-11-printer-work-again/"><u>Make Windows 11 Printer Work Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-failed-device-pairings-in-windows-11/"><u>Quick Fix for Failed Device Pairings in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-errors-rejuvenating-windows-11s-troubleshooting-tools/"><u>Resolving Errors: Rejuvenating Windows 11'S Troubleshooting Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-grayed-out-memory-management-in-win11/"><u>Reviving Grayed-Out Memory Management in Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-your-drive-mercedes-benz-embraces-ai-with-innovative-chatgpt-voice-control-system/"><u>Revolutionize Your Drive - Mercedes-Benz Embraces AI with Innovative ChatGPT Voice Control System</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-resolving-voicemod-issues/"><u>Ultimate Guide: Resolving Voicemod Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-key-aspects-before-purchasing-a-win-notebook/"><u>Understanding Key Aspects Before Purchasing a Win Notebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixer-tackling-inaccessible-networks-on-windows-11-os/"><u>Winfixer: Tackling Inaccessible Networks on Windows 11 OS</u></a></li>
</ul></div>

