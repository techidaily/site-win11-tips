---
title: Adjusting Reset Account Lockouts After Failed Logins in Windows 11
date: 2025-01-17T23:24:20.292Z
updated: 2025-01-24T17:34:44.310Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Reset Account Lockouts After Failed Logins in Windows 11
excerpt: This Article Describes Adjusting Reset Account Lockouts After Failed Logins in Windows 11
keywords: Window 11 Account Unlock,Login Failure Fix,Reset Passwords W11,Clear Account Lockout,ByPass Password Error,Windows Logins Recovery,Safe Login Restart
thumbnail: https://thmb.techidaily.com/79f38eb573cc99e5f54bf7180a8b2f400aa646add73d8ccbbc068b9cd2192911.jpg
---

## Adjusting Reset Account Lockouts After Failed Logins in Windows 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

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
<li><a href="https://win11-tips.techidaily.com/dissecting-the-process-of-windows-11s-automated-backups/"><u>Dissecting the Process of Windows 11'S Automated Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-mkv-to-mp4-conversion-tutorial-windows/"><u>Efficient MKV to MP4 Conversion Tutorial (Windows)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/fcps-premier-selection-the-top-10-editing-plugins/"><u>FCP's Premier Selection The Top 10 Editing Plugins</u></a></li>
<li><a href="https://tech-revival.techidaily.com/harnessing-artificial-intelligence-in-bing-comprehensive-guide-to-empowered-android-browsing/"><u>Harnessing Artificial Intelligence in Bing: Comprehensive Guide to Empowered Android Browsing</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-vivo-y17s-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Vivo Y17s Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-exploring-the-mystery-of-the-blue-video-symbol-on-fb-messages/"><u>In 2024, Exploring the Mystery of the Blue Video Symbol on FB Messages</u></a></li>
<li><a href="https://win-premium.techidaily.com/online-cr2-movavi/"><u>Online CR2 티비프로 자이로 바꾸기 - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-successfully-deploy-store-bought-programs/"><u>Steps to Successfully Deploy Store-Bought Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-savvy-reestablishing-server-link-with-7-fixes-for-obs-studio/"><u>Sync Savvy: Reestablishing Server Link with 7 Fixes for OBS Studio</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-10-fascinating-facts-about-emojis-that-will-surprise-you/"><u>Top 10 Fascinating Facts About Emojis That Will Surprise You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-overcoming-create-failed-issue-in-windows/"><u>Understanding and Overcoming Create Failed Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-index-configuration/"><u>Understanding Windows Index Configuration</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-vivo-y02t-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Vivo Y02T? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-xiaomi-redmi-note-12-pro-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Xiaomi Redmi Note 12 Pro 5G? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>

