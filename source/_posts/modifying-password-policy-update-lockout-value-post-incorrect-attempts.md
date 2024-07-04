---
title: "Modifying Password Policy: Update Lockout Value Post Incorrect Attempts"
date: 2024-06-25T16:53:50.632Z
updated: 2024-06-26T16:53:50.632Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Modifying Password Policy: Update Lockout Value Post Incorrect Attempts"
excerpt: "This Article Describes Modifying Password Policy: Update Lockout Value Post Incorrect Attempts"
keywords: Password Change Guide,Secure Login Methods,Account Security Policies,Preventing Unauthorized Access,Enhancing Password Safety,Reducing Brute Force Risks,Limiting Incorrect Logins
thumbnail: https://thmb.techidaily.com/9f7aaa7e93668c79f588e2bdc07bd0199fd9952e273ede775f53891cdecae42d.jpg
---

## Modifying Password Policy: Update Lockout Value Post Incorrect Attempts

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
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-gaming-service-failures-on-pcs-and-laptops/"><u>How To Resolve Gaming Service Failures on PCs and Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-prose-with-these-5-pc-apps/"><u>Boost Your Prose with These 5 PC Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-outlook-and-gmail-synergy-on-your-pc/"><u>Mastering Outlook & Gmail Synergy on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-system-controls-learn-how-to-use-4-techniques-for-disk-editor-on-win11/"><u>Seamless System Controls: Learn How to Use 4 Techniques for Disk Editor on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-procedure-to-fix-a-disabled-windows-11-hotspot/"><u>Restarting Procedure to Fix a Disabled Windows 11 Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-screen-splitting-problems-in-win-10/"><u>Solutions for Screen Splitting Problems in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-monitor-mastery-personalized-pixelation-per-system-screen/"><u>Multi-Monitor Mastery: Personalized Pixelation per System Screen</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-simple-voice-changer-software-features-guidelines-and-alternatives-for-2024/"><u>Updated Simple Voice Changer Software Features, Guidelines and Alternatives for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/top-10-free-applications-expertly-designed-for-discord-audio-tracking-for-2024/"><u>Top 10 FREE Applications Expertly Designed for Discord Audio Tracking for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-capture-facebook-videos-like-a-pro-select-the-best-firefox-addons-and-downloaders/"><u>[New] 2024 Approved  Capture Facebook Videos Like a Pro  Select the Best Firefox Addons & Downloaders</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-locked-apple-iphone-12-pro-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>Forgot Locked Apple iPhone 12 Pro Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-amplify-your-channels-evading-synthetic-watchers-for-2024/"><u>[New] Amplify Your Channels  Evading Synthetic Watchers for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-melodic-matchmaking-selecting-virtuoso-pieces-to-accompany-wedding-visuals-2024-edition/"><u>New Melodic Matchmaking Selecting Virtuoso Pieces to Accompany Wedding Visuals, 2024 Edition</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-effortlessly-stream-mp3-to-youtube-with-3-key-steps/"><u>[New] Effortlessly Stream  MP3 to YouTube with 3 Key Steps</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlocking-potential-tubebuddy-and-channel-mastery/"><u>2024 Approved  Unlocking Potential  TubeBuddy & Channel Mastery</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-how-to-create-a-diy-green-screen-video-effect-for-2024/"><u>New How to Create a DIY Green Screen Video Effect for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>