---
title: Tailoring Account Lockout Interval Post Unsuccessful Logins, Win 11 Pro
date: 2024-10-26T17:35:15.626Z
updated: 2024-11-01T18:06:34.104Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Account Lockout Interval Post Unsuccessful Logins, Win 11 Pro
excerpt: This Article Describes Tailoring Account Lockout Interval Post Unsuccessful Logins, Win 11 Pro
keywords: Windows 11 Login Lock,Win11 Password Reset,Account Security Win11,Secure Win11 Lockout,Unlock Failed Logins Win,Optimize Win11 Login Safe,Enhance Win11 Access Control
thumbnail: https://thmb.techidaily.com/14598feaeb4d0e61d08a761998cd6976c067dba5c944d538d367654e5b9adad2.jpg
---

## Tailoring Account Lockout Interval Post Unsuccessful Logins, Win 11 Pro

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
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036481/19272" target="_top" id="2036481">
  <img src="//a.impactradius-go.com/display-ad/19272-2036481" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036481/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148774/18498" target="_top" id="2148774">
  <img src="//a.impactradius-go.com/display-ad/18498-2148774" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148774/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-skills.techidaily.com/new-substitutes-to-winmovie-making-software/"><u>[New] Substitutes to WinMovie Making Software</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-tapping-into-trends-your-guide-to-impactful-instagram-tags/"><u>[New] Tapping Into Trends Your Guide to Impactful Instagram Tags</u></a></li>
<li><a href="https://unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-tecno-camon-20-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Tecno Camon 20</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-power-of-online-interactions-on-facebook-twitter-instagram-and-youtube/"><u>Exploring the Power of Online Interactions on Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/how-to-make-slow-motion-videos-on-instagram-reels-step-by-step/"><u>How to Make Slow Motion Videos on Instagram Reels [Step by Step]</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-top-student-vids-essential-histories-channel-list/"><u>In 2024, Top Student Vids Essential Histories Channel List</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-wave-warriors-gear-the-best-cams-for-surfing/"><u>In 2024, Wave Warriors Gear The Best Cams for Surfing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slashing-system-strain-taming-the-user-mode-service-of-vanguard-in-windows/"><u>Slashing System Strain: Taming the User-Mode Service of Vanguard in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/startup-for-windows-11s-speedy-repair-tool/"><u>Startup for Windows 11’S Speedy Repair Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-non-responsive-ccleaner-on-windows-1011/"><u>Steps to Address Non-Responsive CCleaner on Windows 10/11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/sustained-engagement-determining-the-ideal-frequency-for-your-youtube-channel-for-2024/"><u>Sustained Engagement Determining the Ideal Frequency for Your YouTube Channel for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-non-functioning-performance-monitor/"><u>Troubleshooting Windows: Non-Functioning Performance Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-hidden-secrets-of-print-settings-in-win11-max-50-chars/"><u>Unlock the Hidden Secrets of Print Settings in Win11 (Max 50 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-phones-a-future-of-flexibility-and-ease/"><u>Windows 11 & Phones: A Future of Flexibility & Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-net-windows-update-techniques/"><u>Zero-Net Windows Update Techniques</u></a></li>
</ul></div>

