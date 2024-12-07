---
title: Personalizing Login Failure Duration in Win 10/11
date: 2024-12-01T18:56:46.610Z
updated: 2024-12-07T02:17:56.476Z
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

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-explore-best-selections-for-youtube-ringtone-downloads/"><u>[Updated] 2024 Approved Explore Best Selections for YouTube Ringtone Downloads</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-video-splitting-expertise-best-recorder-verdict/"><u>[Updated] In 2024, Video Splitting Expertise Best Recorder Verdict</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-peeling-back-layers-what-hides-beneath-each-snapchat-emoji-for-2024/"><u>[Updated] Peeling Back Layers What Hides Beneath Each Snapchat Emoji for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-virtual-cache-step-by-step-guide-w11/"><u>Clear Virtual Cache: Step by Step Guide W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-task-management-on-windows-11/"><u>Elevate Task Management on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-roblox-error-262-in-minutes/"><u>Eliminate Roblox Error 262 in Minutes!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-auto-color-customization-for-windows-11-software/"><u>Enable Auto-Color Customization for Windows 11 Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escalating-valorant-speed-on-slow-windows-systems/"><u>Escalating Valorant Speed on Slow Windows Systems</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/heimvision-a80s-sunrise-alarm-clock-revealed-enjoy-mornings-with-advanced-light-tech/"><u>HeimVision A80S Sunrise Alarm Clock Revealed: Enjoy Mornings with Advanced Light Tech</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-apps-from-lenovo-thinkphone-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Apps from Lenovo ThinkPhone to Another | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-y55s-5g-2023-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Vivo Y55s 5G (2023) Phone Without Password?</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-stepwise-journey-becoming-a-pro-with-audacity-for-recording/"><u>In 2024, Stepwise Journey Becoming a Pro with Audacity for Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-11-error-code-geforce-x0001/"><u>Mending Windows 11 Error Code: GeForce X0001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/procedures-to-reset-frozen-resource-monitors-in-windows-11/"><u>Procedures to Reset Frozen Resource Monitors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-folder-security-on-windows-10-with-group-policies/"><u>Setting Up Folder Security on Windows 10 with Group Policies</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-reviews-on-memory-processors-and-more-at-tome-hardware-hub/"><u>Top Reviews on Memory, Processors, and More at Tom'e Hardware Hub</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Infinix Note 30 VIP | Dr.fone</u></a></li>
</ul></div>

