---
title: Personalizing Failure Lockout Period on Sign In Errors
date: 2024-06-25T16:52:59.888Z
updated: 2024-06-26T16:52:59.888Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Personalizing Failure Lockout Period on Sign In Errors
excerpt: This Article Describes Personalizing Failure Lockout Period on Sign In Errors
keywords: Personalized Lockout Period,Custom Failure Lockout,Individual Sign-In Error,Tailored Access Denied,User Account Lockout,Error Handling Timeframe,Specific Login Delay
thumbnail: https://thmb.techidaily.com/d6f225de23330f252c6d5195ffc58e836dfeb5e08b530725208b4f5fec9ae8dd.JPG
---

## Personalizing Failure Lockout Period on Sign In Errors

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
<li><a href="https://win11-tips.techidaily.com/top-5-cost-free-windows-audio-cleaners/"><u>Top 5 Cost-Free Windows Audio Cleaners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-enhanced-functionality-with-ai-for-windows-11-users/"><u>Unveiling Enhanced Functionality with AI for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-new-os-build-a-focused-and-effective-windows-11-boot-drive-in-three-ways/"><u>Conquer the New OS – Build a Focused and Effective Windows 11 Boot Drive in Three Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-yuzu-game-performance-in-windows/"><u>Boosting Yuzu Game Performance in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-pursuit-of-purposeful-downloads-from-windows-store/"><u>In Pursuit of Purposeful Downloads From Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-windows-1011-climate-choices/"><u>Exclusive Windows 10/11 Climate Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mute-your-keyboard-on-a-windows-computer/"><u>How to Mute Your Keyboard on a Windows Computer</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-leveraging-powerpoints-automatic-transcription-feature/"><u>[Updated] Leveraging PowerPoint’s Automatic Transcription Feature</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-eclectic-mix-modern-emotional-tracks-on-the-horizon/"><u>Updated Eclectic Mix Modern Emotional Tracks on the Horizon</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/maximizing-vids-for-cash-comparing-dm-and-yo-strategies/"><u>Maximizing Vids for Cash  Comparing Dm & Yo Strategies</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/debut-video-capture-review-for-2024/"><u>Debut Video Capture Review for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/delete-gmail-account-withwithout-password-on-lava-yuva-2-pro-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Lava Yuva 2 Pro</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-xiaomi-redmi-a2plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Xiaomi Redmi A2+ | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-10-top-notch-ad-free-crystal-clear-tiktok-downloads/"><u>[New] In 2024, 10 Top-Notch  Ad-Free, Crystal Clear TikTok Downloads</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-deciphering-sharex-comparisons-and-replacements/"><u>[New] Deciphering ShareX  Comparisons & Replacements</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>