---
title: Manipulating Login Retry Wait Timepost-Failed Attempts
date: 2024-06-25T16:48:22.741Z
updated: 2024-06-26T16:48:22.741Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-clearing-windowss-prior-passcode/"><u>Winning Back Access: Clearing “Windows's Prior Passcode”</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-how-to-clear-steams-dns-cache/"><u>Understanding How to Clear Steam's DNS Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-specific-error-403-in-roblox-space/"><u>Resolving Windows-Specific Error 403 in Roblox Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-offline-windows-enhancements/"><u>Navigating Offline Windows Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-wintoys-a-short-guide-to-a-powerful-windows-tool/"><u>What Is Wintoys? A Short Guide to a Powerful Windows Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-complications-caused-by-latest-windows-updates/"><u>Resolving Complications Caused by Latest Windows Updates</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-setting-up-your-social-media-presence-with-twitter/"><u>In 2024, Setting Up Your Social Media Presence with Twitter</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-tomtoms-advanced-adventure-cameras-review-2023-edition/"><u>[Updated] 2024 Approved  TomTom’s Advanced Adventure Cameras Review - 2023 Edition</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-crossing-thresholds-in-ctas-anticipating-fb-ad-shifts/"><u>[New] 2024 Approved  Crossing Thresholds in CTAs  Anticipating FB Ad Shifts</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-make-your-own-dvds-a-guide-to-top-video-editing-tools/"><u>In 2024, Make Your Own DVDs A Guide to Top Video Editing Tools</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-reviewing-yuneecs-powerful-typhoon-aerodrone/"><u>[Updated] Reviewing Yuneec's Powerful Typhoon AeroDrone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-lava-blaze-2-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Lava Blaze 2 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-pave-your-path-to-popularity-secure-1000-fansmonth-on-instagram/"><u>[New] In 2024, Pave Your Path to Popularity  Secure 1,000 Fans/Month on Instagram</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-beginners-bonanza-affordable-profitable-channel-options/"><u>[Updated] Beginner's Bonanza  Affordable, Profitable Channel Options</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>