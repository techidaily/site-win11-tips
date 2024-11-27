---
title: Personalizing Login Failure Duration in Win 10/11
date: 2024-11-24T16:02:14.980Z
updated: 2024-11-27T17:03:59.475Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Personalizing Login Failure Duration in Win 10/11
excerpt: This Article Describes Personalizing Login Failure Duration in Win 10/11
keywords: Win 10 Login Timeout,Win 10 User Lockout,Windows Logon Delay,Customize PC Lockout,Extend Login Failure,Personalized Lock Out,Duration Set for Login
thumbnail: https://thmb.techidaily.com/5e4f2e08bc06e83ddb45587d928cf61d9245bd50e484b6c6cc6059c7ac856aae.jpg
---

## Personalizing Login Failure Duration in Win 10/11

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-unmatched-mp4-generation-from-facebook-clips/"><u>[New] 2024 Approved Unmatched MP4 Generation From Facebook Clips</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-crafting-classic-cinematography-step-by-step-guide-for-2024/"><u>[Updated] Crafting Classic Cinematography Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-guffaw-generation-generating-7-hilarious-video-moments-online/"><u>[Updated] In 2024, Guffaw Generation Generating 7 Hilarious Video Moments Online</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-sending-direct-tweets-share-photosvideos-on-twitter-without-retweeting/"><u>[Updated] In 2024, Sending Direct Tweets Share Photos/Videos on Twitter without Retweeting</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-picture-by-picture-insta-gallery-for-2024/"><u>[Updated] Picture by Picture Insta Gallery for 2024</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/movavi-mka-to-aac/"><u>無縫移動：如何免費使用Movavi 進行 MKA to AAC 的在線音頻格式轉換</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-and-concise-guide-implementing-intel-wi-fi-and-lan-drivers-in-windows/"><u>Clear and Concise Guide: Implementing Intel Wi-Fi & LAN Drivers in Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-access-chatgpt-within-your-ubuntu-terminal-using-shell-tools/"><u>How to Access ChatGPT Within Your Ubuntu Terminal Using Shell Tools</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-gmail-password-on-gionee-f3-pro-devices-by-drfone-android/"><u>How to Reset Gmail Password on Gionee F3 Pro Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-rapid-rambles-halt-mouse-accel-in-win-11/"><u>No More Rapid Rambles: Halt Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opt-out-of-unwanted-windows-system-updates/"><u>Opt Out of Unwanted Windows System Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-qt-not-found-application-launch-issue/"><u>Resolving Qt Not Found Application Launch Issue</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-complete-manual-for-instagram-selfies-for-2024/"><u>The Complete Manual for Instagram Selfies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timestamp-transformation-top-utilities-for-changing-file-times/"><u>Timestamp Transformation: Top Utilities for Changing File Times</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-zoom-issue-code-1132-fix/"><u>Troubleshooting Windows Zoom Issue: Code 1132 Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-gameplay-secrets-a-beginners-guide-to-diablo/"><u>Unlocking Gameplay Secrets: A Beginner's Guide to Diablo</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    