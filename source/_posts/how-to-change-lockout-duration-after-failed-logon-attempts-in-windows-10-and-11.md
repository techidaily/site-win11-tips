---
title: How to Change Lockout Duration After Failed Logon Attempts in Windows 10 and 11
date: 2024-10-20T03:37:12.109Z
updated: 2024-10-20T19:10:24.270Z
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
<a href="https://appsumo.8odi.net/c/5597632/2049387/7443" target="_top" id="2049387">
  <img src="//a.impactradius-go.com/display-ad/7443-2049387" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049387/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482">
  <img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-gotorhythms-top-pick-for-hearing-westerosi-songs/"><u>[New] GoToRhythms Top Pick for Hearing Westerosi Songs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-kidstoons-pro-deep-dive-year-2024/"><u>[New] KidsToons Pro Deep Dive - Year 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-optimal-method-for-integrating-gopro-footage-into-360-degree-films/"><u>[Updated] Optimal Method for Integrating GoPro Footage Into 360-Degree Films</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-unlock-potential-top-free-video-opener-hacks-for-2024/"><u>[Updated] Unlock Potential Top Free Video Opener Hacks for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-apple-iphone-11-pro-icloud-activation-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing Apple iPhone 11 Pro iCloud Activation Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-obstructed-calendarmail-access-on-w11/"><u>How to Overcome Obstructed Calendar/Mail Access on W11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Pause Life360 Location Sharing For Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x800704b3-on-your-win1011-machine/"><u>Overcoming Error 0X800704B3 on Your Win10/11 Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-recyclebin-icon-in-windows-11/"><u>Reviving Dormant Recyclebin Icon in Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/simple-steps-converting-apng-files-into-easy-to-use-gifs/"><u>Simple Steps: Converting APNG Files Into Easy-to-Use GIFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snippet-savvy-crafting-custom-keybinds-for-speed-and-precision-in-win11/"><u>Snippet Savvy: Crafting Custom Keybinds for Speed & Precision in Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-roadblock-ahead-teredo-fails-to-secure-spot-on-competitive-list/"><u>The Roadblock Ahead: Teredo Fails to Secure Spot on Competitive List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-elusive-results-in-your-windows-1011-search/"><u>Uncovering Elusive Results in Your Windows 10/11 Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-runtime-broker-a-key-to-optimized-pc-operations/"><u>Understanding Runtime Broker: A Key to Optimized PC Operations</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    