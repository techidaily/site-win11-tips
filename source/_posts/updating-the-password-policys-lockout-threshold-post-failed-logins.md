---
title: Updating the Password Policy's Lockout Threshold Post-Failed Logins
date: 2024-11-04T01:32:50.977Z
updated: 2024-11-06T19:41:06.600Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Updating the Password Policy's Lockout Threshold Post-Failed Logins
excerpt: This Article Describes Updating the Password Policy's Lockout Threshold Post-Failed Logins
keywords: Passwords Update Policy,Login Failure Lockout,Security Thresholds Adjust,Preventing Brute Force Attacks,Account Safety Enhancement,Logout Limits Improvement,Password Reset Protocols
thumbnail: https://thmb.techidaily.com/e87b3408f54a53f91c9308647e5fc7c06d24ab266fe9e1d96c042582b4eeaa37.jpg
---

## Updating the Password Policy's Lockout Threshold Post-Failed Logins

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
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-effortless-setup-of-streamlabs-for-mac-users-via-obs/"><u>[New] 2024 Approved Effortless Setup of Streamlabs for Mac Users via OBS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-free-music-unlocked-the-ultimate-library-for-videographers/"><u>[Updated] 2024 Approved Free Music Unlocked The Ultimate Library for Videographers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-unseen-viewers-route-navigating-instagram-stories-with-anonymous-viewing-for-2024/"><u>[Updated] The Unseen Viewer's Route Navigating Instagram Stories with Anonymous Viewing for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transformative-tactics-for-impeccable-hue-correction/"><u>[Updated] Transformative Tactics for Impeccable Hue Correction</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-stumble-upon-these-hidden-meme-page-treasures/"><u>2024 Approved Stumble Upon These Hidden Meme Page Treasures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disconnected-voice-commands-on-microsoft-written-by-jessica-haines/"><u>Fixing Disconnected Voice Commands on Microsoft' Written by Jessica Haines</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-often-can-creators-expect-to-be-paid-by-youtube/"><u>How Often Can Creators Expect to Be Paid by YouTube?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enabledisable-windows-11-search-lights/"><u>How to Enable/Disable Windows 11 Search Lights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/laptop-lag-elevate-connectivity-to-iphone-standards/"><u>Laptop Lag? Elevate Connectivity to iPhone Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-lsa-problem-in-windows-os/"><u>Mending LSA Problem in Windows OS</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/1728474387297-outlook/"><u>Outlook連絡先データの外部記憶装置への完全なバックアップ手順</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-through-office-workflows-with-keyboard-shortcuts/"><u>Power Through Office Workflows with Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-microsoft-windowed-google-nearby-share-glitch/"><u>Quick FIX: Microsoft Windowed Google Nearby Share Glitch</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-entrypointnotfound-in-fortnite-a-comprehensive-guide/"><u>Resolving 'EntryPointNotFound' In Fortnite: A Comprehensive Guide</u></a></li>
<li><a href="https://solve-popular.techidaily.com/unlocking-vmdk-a-comprehensive-guide-on-opening-disk-images-with-vmware-and-virtualbox/"><u>Unlocking VMDK: A Comprehensive Guide on Opening Disk Images with VMWare & VirtualBox</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    