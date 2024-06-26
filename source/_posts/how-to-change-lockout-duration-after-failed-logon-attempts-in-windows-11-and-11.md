---
title: How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11
date: 2024-06-25T16:32:03.632Z
updated: 2024-06-26T16:32:03.632Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/elevate-your-command-prompt-integrating-folders-into-context-menu/"><u>Elevate Your Command Prompt: Integrating Folders Into Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-terminal-for-quake-environment/"><u>Accessing Windows Terminal for Quake Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-guide-to-superior-windows-search-without-ls/"><u>In-Depth Guide to Superior Windows Search without LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-auto-lock-and-screensaver-interval/"><u>Personalize Auto-Lock & Screensaver Interval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reenergizing-your-dead-wireless-hotspot-in-windows-11/"><u>Reenergizing Your Dead Wireless Hotspot in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-faulty-resource-monitors-on-windows-11/"><u>Resetting Techniques for Faulty Resource Monitors on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-non-active-vss-service-states/"><u>Restoring Non-Active VSS Service States</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-buzz-mastering-voice-recorder-shortcuts-in-windows-11/"><u>Beating the Buzz: Mastering Voice Recorder Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-state-of-the-art-ai-windows-edition/"><u>Running State-of-the-Art AI: Windows Edition</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-oppo-find-n3-flip-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Oppo Find N3 Flip Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/boosting-stability-and-speed-more-ram-for-minecraft/"><u>Boosting Stability & Speed  More RAM for Minecraft</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-evaluationcast-breakdown/"><u>[New] EvaluationCast Breakdown</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-an-android-users-journey-to-flawless-audio-visual-integration-for-2024/"><u>New An Android Users Journey to Flawless Audio-Visual Integration for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-beyond-standard-views-a-detailed-look-at-the-z32x-model/"><u>[New] Beyond Standard Views  A Detailed Look at the Z32X Model</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-sonic-treasure-trove-the-8-best-websites-to-explore-a-world-of-high-quality-gratis-audio-enhancements/"><u>Updated In 2024, Sonic Treasure Trove The 8 Best Websites to Explore a World of High-Quality, Gratis Audio Enhancements</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Xiaomi Civi 3? | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-guide-to-make-timelapse-video-with-imovie-for-2024/"><u>New Guide to Make Timelapse Video with iMovie for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/advanced-voice-communication-technology-for-gamers-interaction-for-2024/"><u>Advanced Voice Communication Technology for Gamers Interaction for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-revitalizing-urban-areas-with-environmental-vision-and-purpose/"><u>[Updated] 2024 Approved  Revitalizing Urban Areas with Environmental Vision and Purpose</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>