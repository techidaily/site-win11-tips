---
title: Customizing Failed Sign In Wait Duration in Windows
date: 2024-12-11T22:25:01.874Z
updated: 2024-12-13T01:46:31.986Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/rom-concept-to-screen-channel-yt-for-pioneering-filmmaking-techniques/"><u>[New] From Concept to Screen Channel YT for Pioneering Filmmaking Techniques</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-techniques-for-accurate-ps3-playback-rendering/"><u>[New] In 2024, Techniques for Accurate PS3 Playback Rendering</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-macs-premier-selection-of-mp4-cutter-software/"><u>[New] Mac's Premier Selection of MP4 Cutter Software</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-explore-the-safest-video-chat-apps-on-both-sides-of-the-market-for-2024/"><u>[Updated] Explore the Safest Video Chat Apps on Both Sides of the Market for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/10-proven-strategies-when-you-cant-get-skype-to-work-correctly/"><u>10 Proven Strategies When You Can't Get Skype to Work Correctly</u></a></li>
<li><a href="https://win-premium.techidaily.com/beste-wege-den-cache-zu-leeren-aktualisierung-mit-windows-11/"><u>Beste Wege, Den Cache Zu Leeren - Aktualisierung Mit Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-run-time-error-windows-app-fix-guide/"><u>Clearing Up 'Run-Time Error': Windows App Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-unreachable-status-of-steam-game-servers-on-desktop-os/"><u>Correcting Unreachable Status of Steam Game Servers on Desktop OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-dysfunctional-print-via-wwin-command-on-windows/"><u>Dealing with Dysfunctional Print via WWin Command on Windows.</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-or-ipad-missing-icons-discover-effective-solutions-now/"><u>IPhone or iPad Missing Icons? Discover Effective Solutions Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-techniques-for-hardware-id-discovery-in-windows-systems/"><u>Key Techniques for Hardware ID Discovery in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-name-update-on-windows-11/"><u>Mastering User Name Update on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-freezing-issues-with-spotify-on-w10w11-oses/"><u>Overcoming Freezing Issues with Spotify on W10/W11 OSes</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premier-digital-discussion-director-for-2024/"><u>Premier Digital Discussion Director for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-inaccessible-nvidia-control-panel-in-win11/"><u>Solutions for Inaccessible Nvidia Control Panel in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-rectifying-domain-services-print-glitches/"><u>Step-by-Step: Rectifying Domain Services Print Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-the-windows-11-desktop-menus-to-fit-your-needs/"><u>Tailoring the Windows 11 Desktop Menus to Fit Your Needs</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-apps-and-online-tools-to-track-samsung-galaxy-f34-5g-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Samsung Galaxy F34 5G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unleash-the-power-of-wireless-charging-with-qi-technology-apple-devotees-take-note-zdnet-insights/"><u>Unleash the Power of Wireless Charging with Qi Technology (Apple Devotees, Take Note!) | ZDNET Insights</u></a></li>
</ul></div>

