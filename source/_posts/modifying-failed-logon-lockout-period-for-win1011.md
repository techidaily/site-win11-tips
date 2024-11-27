---
title: Modifying Failed Logon Lockout Period for Win10/11
date: 2024-11-25T17:13:41.784Z
updated: 2024-11-27T17:08:35.702Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Failed Logon Lockout Period for Win10/11
excerpt: This Article Describes Modifying Failed Logon Lockout Period for Win10/11
keywords: Windows Login Cooldown Adjustment,Change Account Unlock Time,Alter Failed Login Interval,Modify Windows Lockout Period,Reset Credential Lockout Time,Update Win10/11 Logon Restriction,Extend Failed Login Wait Period
thumbnail: https://thmb.techidaily.com/052918d3e56b96021eca7b3225588078d8b2ee409e0b799bdcb8f9f006f59b01.jpg
---

## Modifying Failed Logon Lockout Period for Win10/11

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-sound-fidelity-preservation-computer-sounds-and-dialogue-for-2024/"><u>[New] Sound Fidelity Preservation Computer Sounds & Dialogue for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-the-seamless-guide-to-saving-gifs-on-iphonesandroids/"><u>[Updated] 2024 Approved The Seamless Guide to Saving GIFs on iPhones/Androids</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-transform-your-visual-content-on-instagram-using-these-6-tools/"><u>[Updated] 2024 Approved Transform Your Visual Content on Instagram Using These 6 Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-comprehensive-examination-razer-kiyo-cam/"><u>[Updated] Comprehensive Examination Razer Kiyo Cam</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-unlocking-popularity-a-comprehensive-list-of-instagrams-top-25-tags-for-2024/"><u>[Updated] Unlocking Popularity A Comprehensive List of Instagram's Top 25 Tags for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unmute-silent-windows-volume/"><u>How to Unmute Silent Windows Volume</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intensify-visual-power-with-graphics-upgrade-for-app-guard-edge/"><u>Intensify Visual Power with Graphics Upgrade for App Guard Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-multi-vm-environments-linux-inside-hyper-v-on-windows/"><u>Navigating Multi-VM Environments: Linux Inside Hyper-V on Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/review-all-round-performance-and-features-of-the-garmin-gpsmap-64st-gps-unit/"><u>Review: All-Round Performance and Features of the Garmin GPSMAP 64St GPS Unit</u></a></li>
<li><a href="https://buynow-info.techidaily.com/revolutionizing-android-with-the-latest-google-pixel-4xl-unveiled-in-our-expert-review/"><u>Revolutionizing Android with the Latest Google Pixel 4XL Unveiled in Our Expert Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-docker-operations-within-wsl-2-environment/"><u>Streamlining Docker Operations Within WSL 2 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-mystery-fixing-recording-mishaps-with-obs-studio/"><u>Tackling the Mystery: Fixing Recording Mishaps with OBS Studio</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-guide-to-using-google-maps-on-your-iphone-a-review/"><u>The Ultimate Guide to Using Google Maps on Your iPhone - A Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-5-zero-dollar-pc-sound-filters/"><u>Winning 5 Zero-Dollar PC Sound Filters</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    