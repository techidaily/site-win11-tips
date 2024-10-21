---
title: Setting New Parameters for Login Failure Count in Windows 11 & 11
date: 2024-10-17T03:23:23.717Z
updated: 2024-10-20T18:03:44.072Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting New Parameters for Login Failure Count in Windows 11 & 11
excerpt: This Article Describes Setting New Parameters for Login Failure Count in Windows 11 & 11
keywords: Windows 11 Login Limits,Login Failures Window 11,W11 Login Failure Policy,Windows 11 Error Rate Control,W11 Failed Logins Threshold,Setup Windows 11 Login Limit,Adjusting W11 Login Attempts
thumbnail: https://thmb.techidaily.com/d3b76096f4c9dcaff472cd20aa342807816191e8da2710c62b22806e55635c8b.jpg
---

## Setting New Parameters for Login Failure Count in Windows 11 & 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049388/7443" target="_top" id="2049388">
  <img src="//a.impactradius-go.com/display-ad/7443-2049388" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049388/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938682/19272" target="_top" id="1938682">
  <img src="//a.impactradius-go.com/display-ad/19272-1938682" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938682/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-in-2024-translate-speech-to-text-the-right-way-with-google-translate/"><u>[New] In 2024, Translate Speech to Text the Right Way with Google Translate</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-advanced-tips-for-integrating-markers-in-videography/"><u>[Updated] Advanced Tips for Integrating Markers in Videography</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-ultimate-guide-7-high-ranking-audio-transformation-apps/"><u>[Updated] In 2024, Ultimate Guide 7 High-Ranking Audio Transformation Apps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-master-the-art-of-preserving-your-musical-journey/"><u>[Updated] Master the Art of Preserving Your Musical Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-cant-get-mail-easy-fixes-for-windows-11-users/"><u>Breaking Down 'Can't Get Mail': Easy Fixes for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-11s-operation-elevation-error-740/"><u>Breaking Down Windows 11'S Operation Elevation Error #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-basics-resetting-windows-11-privileges/"><u>Bring Back the Basics: Resetting Windows 11 Privileges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-your-guardianship-quick-fixed-windows-tips/"><u>Bringing Back Your Guardianship: Quick Fixed Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-blocks-for-handbrake-success/"><u>Bypass Windows Blocks for HandBrake Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-expiring-soon-error-on-windows-11-os/"><u>Bypassing 'Expiring Soon' Error on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-chromes-automatic-conversion-to-webp-format-pc-users/"><u>Cease Chrome’s Automatic Conversion to WebP Format PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charming-windows-echoing-winters-joyful-spirit/"><u>Charming Windows: Echoing Winter's Joyful Spirit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-between-intel-unison-and-phone-link-best-wp-app/"><u>Choosing Between Intel Unison & Phone Link: Best WP App?</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/garmin-vivoactive-3-enhance-your-fitness-routine-with-built-in-music-and-smart-connectivity/"><u>Garmin Vivoactive 3: Enhance Your Fitness Routine with Built-In Music and Smart Connectivity</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/how-to-add-emojis-to-discord-for-2024/"><u>How to Add Emojis To Discord for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-best-mac-microphone-software-a-detailed-look-at-the-five-top-picks/"><u>In 2024, Best Mac Microphone Software A Detailed Look at the Five Top Picks</u></a></li>
<li><a href="https://driver-error.techidaily.com/preventing-sm-bus-errors-in-windows-1011-devices/"><u>Preventing SM Bus Errors in Windows 10/11 Devices</u></a></li>
<li><a href="https://fox-direct.techidaily.com/scaling-up-subscriber-numbers-with-savvy-strategies/"><u>Scaling Up Subscriber Numbers with Savvy Strategies</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamlight-solutions-best-for-video-illumination/"><u>Streamlight Solutions Best for Video Illumination</u></a></li>
</ul></div>

