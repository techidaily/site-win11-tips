---
title: "Optimizing Account Security: Changing Reset Counter After Failed Logins"
date: 2024-06-25T16:18:48.193Z
updated: 2024-06-26T16:18:48.193Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Account Security: Changing Reset Counter After Failed Logins"
excerpt: "This Article Describes Optimizing Account Security: Changing Reset Counter After Failed Logins"
keywords: Secure Passwords Update,Prevent Reset Abuse,Improve Login Safety,Strengthen Access Controls,Enhance Account Protection,Reduce Failed Attempt Risks,Optimize Security Measures
thumbnail: https://thmb.techidaily.com/6a82b15c3b5908dade20c57e5528354889aa2d43fb699583edd3d2db4662000a.jpg
---

## Optimizing Account Security: Changing Reset Counter After Failed Logins

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
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-adding-emoji-15-to-win11-setup/"><u>Navigate with Style: Adding Emoji 15 to Win11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-workflow-with-aero-shake-w11-tech/"><u>Optimizing Your Workflow with Aero Shake W11 Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-understanding-its-windows-purpose/"><u>What Is Pagefile.sys? Understanding Its Windows Purpose</u></a></li>
<li><a href="https://win11-tips.techidaily.com/journey-through-time-exploring-windows-11s-archives/"><u>Journey Through Time: Exploring Windows 11’S Archives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-usb-health-in-windows-a-troubleshooting-checklist/"><u>Restoring USB Health in Windows: A Troubleshooting Checklist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/paperless-pages-winning-window-based-notepad-substitutes/"><u>Paperless Pages: Winning Window-Based Notepad Substitutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-strategies-windows-voice-logging/"><u>Step-by-Step Strategies: Windows Voice Logging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-recovery-on-windows-11-pro/"><u>Streamlining Data Recovery on Windows 11 Pro</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/5-most-effective-methods-to-unlock-iphone-13-mini-in-lost-mode-drfone-by-drfone-ios/"><u>5 Most Effective Methods to Unlock iPhone 13 mini in Lost Mode | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-windows-8-flv-editor-a-user-friendly-video-editing-solution/"><u>Updated Windows 8 FLV Editor A User-Friendly Video Editing Solution</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crafting-shocking-news-titles-expert-for-2024/"><u>Crafting Shocking News Titles Expert for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-palette-perfection-a-guide-to-grading-filmmaking/"><u>2024 Approved  Palette Perfection  A Guide to Grading Filmmaking</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-earn-on-youtube-beginners-path-to-profitability/"><u>[New] In 2024, Earn on YouTube  Beginner's Path to Profitability</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-overcoming-screen-blackouts-in-recording-tools/"><u>[New] Overcoming Screen Blackouts in Recording Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-make-every-frame-count-a-list-of-the-hottest-50-video-reducing-apps-for-your-phone/"><u>In 2024, Make Every Frame Count  A List of the Hottest 50 Video-Reducing Apps for Your Phone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-ultimate-guide-to-high-definition-hd-youtube-and-fb-videos/"><u>[New] 2024 Approved  The Ultimate Guide to High Definition (HD) YouTube & FB Videos</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-honor-70-lite-5g-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Honor 70 Lite 5G</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>