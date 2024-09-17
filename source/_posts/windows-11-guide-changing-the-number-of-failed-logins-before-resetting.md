---
title: "Windows 11 Guide: Changing the Number of Failed Logins Before Resetting"
date: 2024-09-13T02:50:10.027Z
updated: 2024-09-16T22:28:34.584Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Guide: Changing the Number of Failed Logins Before Resetting"
excerpt: "This Article Describes Windows 11 Guide: Changing the Number of Failed Logins Before Resetting"
keywords: Windows 11 Login Failure,Change Login Attempts,Reset User Password,11 PC Security Guide,Failed Login Fix,Lockout Prevention Tricks,Update Passwords Steps
thumbnail: https://thmb.techidaily.com/c7779ebd6615899057fd1d41459b53b981bc532c7ceba807afb11ae201e1d4e5.jpg
---

## Windows 11 Guide: Changing the Number of Failed Logins Before Resetting

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-adjust-default-snapshot-savings-in-mac/"><u>[New] Adjust Default Snapshot Savings in Mac</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-budget-friendly-methods-for-youtube-card-creation/"><u>[Updated] In 2024, Budget-Friendly Methods for YouTube Card Creation</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-fan-count-decline-identify-losses/"><u>[Updated] Instagram Fan Count Decline Identify Losses</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-camera-operational-obs-challenge-won/"><u>2024 Approved Camera Operational OBS Challenge Won</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-tranquility-techniques-managing-in-system-sounds/"><u>2024 Approved Tranquility Techniques Managing In-System Sounds</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-iphone-12-pro-icloud-activation-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing iPhone 12 Pro iCloud Activation Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-initial-display-of-task-manager-in-windows-11/"><u>Customizing Initial Display of Task Manager in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installation-guide-to-dolby-atmos-for-pc-users/"><u>Installation Guide to Dolby Atmos for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-non-functional-microsoft-store-in-windows-11/"><u>Quick Fix for Non-Functional Microsoft Store in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/syncing-scores-youtube-musics-role-in-multimedia-content/"><u>Syncing Scores YouTube Music's Role in Multimedia Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-risks-of-ignoring-windows-11-notification-sounds/"><u>The Hidden Risks of Ignoring Windows 11 Notification Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-desktops-aesthetic-essential-theme-tips-for-win11/"><u>Transforming Your Desktop's Aesthetic: Essential Theme Tips for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-mystery-of-windows-credentials-with-these-top-11-strategies/"><u>Unlock the Mystery of Windows Credentials with These Top 11 Strategies</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115945/19272" target="_top" id="2115945">
  <img src="//a.impactradius-go.com/display-ad/19272-2115945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115945/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

