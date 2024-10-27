---
title: How to Change Lockout Duration After Failed Logon Attempts in Windows 10 and 11
date: 2024-10-23T16:18:54.763Z
updated: 2024-10-26T16:18:10.026Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Change Lockout Duration After Failed Logon Attempts in Windows 10 and 11
excerpt: This Article Describes How to Change Lockout Duration After Failed Logon Attempts in Windows 10 and 11
keywords: Windows Login Lockout Time,Extend Lockout Period Win10,Delay Lockout Windows 11,Reset Account Lockout Windows,Increase Logon Lockout Duration,Prolong Windows Failed Login Lock,Adjust Windows Lockout Interval
thumbnail: https://thmb.techidaily.com/b3b1cb7d8c5c52c25843bc952abd6a00ab0cd811cafc15697aa0c13fd607a950.jpg
---

## How to Change Lockout Duration After Failed Logon Attempts in Windows 10 and 11

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
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111965/7443" target="_top" id="2111965">
  <img src="//a.impactradius-go.com/display-ad/7443-2111965" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111965/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144289/7443" target="_top" id="2144289">
  <img src="//a.impactradius-go.com/display-ad/7443-2144289" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144289/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082521/7443" target="_top" id="2082521">
  <img src="//a.impactradius-go.com/display-ad/7443-2082521" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082521/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-x-audio-studio-pro-for-computer-users/"><u>[New] 2024 Approved X-Audio Studio Pro for Computer Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-multitask-media-with-ease-expertly-using-netflixs-picture-in-picture-feature/"><u>[New] Master Multitask Media with Ease Expertly Using Netflix’s Picture-In-Picture Feature</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-capturing-more-with-less-lgs-360-camera-redefined-and-reviewed-for-2024/"><u>[Updated] Capturing More with Less - LG's 360 Camera Redefined & Reviewed for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-ensuring-smooth-transition-livestreaming-old-videos-on-fb/"><u>[Updated] In 2024, Ensuring Smooth Transition Livestreaming Old Videos on FB</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-the-challenge-of-svchostexe-netsvcs-strategies-to-curtail-its-significant-impact-on-internet-usage/"><u>Addressing the Challenge of svchost.exe (NETsvcs): Strategies to Curtail Its Significant Impact on Internet Usage</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-samsung-galaxy-f14-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Samsung Galaxy F14 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-oneplus-12r-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/local-groups-local-power-admin-techniques-for-win1110-homes/"><u>Local Groups, Local Power: Admin Techniques for Win11/10 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-geforce-experience-error-x0001-in-windows-os/"><u>Overcoming GeForce Experience Error X0001 in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-access-methods-for-windows-control-panel/"><u>Quick Access Methods for Windows Control Panel</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211048300-quick-fix-guide-to-fast-league-of-legends-downloading-say-goodbye-to-delays/"><u>Quick-Fix Guide to Fast League of Legends Downloading: Say Goodbye to Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-printer-availability-on-windows-11/"><u>Strategies for Printer Availability on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tech-usage-leveraging-windows-widgets/"><u>Streamlining Tech Usage: Leveraging Windows Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-hogwarts-games-ram-overflow-issue/"><u>Troubleshooting Hogwarts Game's RAM Overflow Issue</u></a></li>
</ul></div>

