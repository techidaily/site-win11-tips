---
title: Resetting Windows Lockout Count After Sign-In Failures
date: 2024-06-25T16:36:48.421Z
updated: 2024-06-26T16:36:48.421Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Windows Lockout Count After Sign-In Failures
excerpt: This Article Describes Resetting Windows Lockout Count After Sign-In Failures
keywords: Reset Windows Password,Unlock Windows Error,Windows Login Failed,Signin Lockout Fix,Account Access Blocked,Regain Windows Entry,Recover Lost Credentials
thumbnail: https://thmb.techidaily.com/33d2c913be55d31e549acb89b4370208c20960b474ce8b9b8af13ad1eeef19a7.jpg
---

## Resetting Windows Lockout Count After Sign-In Failures

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
<li><a href="https://win11-tips.techidaily.com/past-keys-to-future-launches-utilizing-windows-7-for-windows-11-bootup/"><u>Past Keys to Future Launches: Utilizing Windows 7 for Windows 11 Bootup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-start-screen-links-in-win11s-options/"><u>Adjusting Start Screen Links in Win11's Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpening-up-discord-response-time-on-windows-devices/"><u>Sharpening Up Discord Response Time on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-resolution-at-your-fingertips-top-10-tools/"><u>Error Resolution at Your Fingertips: Top 10 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-discord-launch-and-update-check-with-windows-startup/"><u>Preventing Discord Launch and Update Check with Windows Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-unresponsive-wired-gaming-accessories/"><u>Cure for Unresponsive Wired Gaming Accessories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-window-tricks-to-unlock-facebook-chats/"><u>Winning Window Tricks to Unlock Facebook Chats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-valorants-audio-sync-on-microsoft-devices/"><u>Correcting Valorant's Audio Sync on Microsoft Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-mold-reinventing-yourself-with-a-new-username-in-windows-11/"><u>Breaking the Mold: Reinventing Yourself with a New UserName in Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-15-innovative-cutting-edge-software-options-replacing-obs/"><u>[New] 2024 Approved  15 Innovative, Cutting-Edge Software Options Replacing OBS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-influencer-secrets-making-your-vids-hits-hard/"><u>[New] In 2024, Influencer Secrets  Making Your Vids Hits Hard</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-xiaomi-redmi-note-13-pro-5g-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Xiaomi Redmi Note 13 Pro 5G Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-infinix-note-30i-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Infinix Note 30i? | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-step-into-personal-branding-with-a-new-tiktok-look/"><u>[Updated] 2024 Approved  Step Into Personal Branding with a New TikTok Look</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-enhance-your-tv-experience-mastering-fb-live-and-roku/"><u>[New] Enhance Your TV Experience  Mastering FB Live and Roku</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/the-gamers-playbook-4-essential-steps-for-recording-games/"><u>The Gamer's Playbook  4 Essential Steps for Recording Games</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-embedding-youtube-playlists-step-by-step-guide/"><u>[Updated] 2024 Approved  Embedding YouTube Playlists  Step-by-Step Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-best-choice-high-definition-screen-capturing-apps/"><u>The Best Choice  High-Definition Screen Capturing Apps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>