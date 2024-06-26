---
title: Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
date: 2024-06-25T16:24:40.613Z
updated: 2024-06-26T16:24:40.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
excerpt: This Article Describes Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
keywords: Windows 11 Login Limits,Win11 Password Failures,Reset Attempt Control,Secure Login Windows 11,Incorrect Logins Management,Windows 11 Access Restrictions,Account Lockout Thresholds
thumbnail: https://thmb.techidaily.com/5137476410d550ff3157a9e8b8c303fc95e61e87d44f30246bb809e8ce4eedda.jpg
---

## Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

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

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-x7007043c-in-windows-media-creator/"><u>Eradicating Error X.7007043C in Windows' Media Creator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failure-to-install-win11s-v22h2-update/"><u>Navigating Through Failure to Install Win11's V22H2 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-data-exchange-safeguarding-files-across-ws11w10/"><u>Silent Data Exchange: Safeguarding Files Across WS11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-with-windows-11-safe-boot-tips/"><u>Troubleshoot With Windows 11 Safe Boot Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-typing-solutions-for-windows-pcs-7-must-dos/"><u>Speedy Typing Solutions for Windows PCs (#7 Must-Dos)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-your-monitor-memorable-saving-windows-spotlight-photos-as-walls/"><u>Making Your Monitor Memorable: Saving Windows Spotlight Photos as Walls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-overheat-during-intense-play/"><u>Minimizing Overheat During Intense Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-chrome-clock-error-ahead-or-behind-windows-edition/"><u>Adjusting Chrome Clock Error: Ahead or Behind? (Windows Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-windows-navigator-placement-of-this-pc-icons/"><u>Customizing Windows Navigator: Placement of 'This PC' Icons</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-elevating-engagement-with-expert-level-niche-creators/"><u>[New] In 2024, Elevating Engagement with Expert-Level Niche Creators</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-oneplus-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your OnePlus Phone? Unlock It Now</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-comprehensive-handbook-for-recording-calls/"><u>[New] The Comprehensive Handbook for Recording Calls</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premier-live-basketball-experience-at-home/"><u>[Updated] Premier Live Basketball Experience at Home</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/reviving-cut-off-livestreams-solving-facebook-streaming-hiccups/"><u>Reviving Cut-Off Livestreams  Solving Facebook Streaming Hiccups</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-cooldown-chart-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-2024-approved-how-to-make-your-memoji-talk-get-creative-with-your-messaging/"><u>Updated 2024 Approved How To Make Your Memoji Talk? Get Creative With Your Messaging</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-infinix-hot-40i-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Infinix Hot 40i Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-auto-translate-youtube-videos-into-different-languages-for-2024/"><u>Updated Auto Translate YouTube Videos Into Different Languages for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-enhance-your-video-impact-with-slow-motion-on-ig/"><u>[New] 2024 Approved  Enhance Your Video Impact with Slow Motion on IG</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>