---
title: Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11
date: 2024-06-25T16:58:31.338Z
updated: 2024-06-26T16:58:31.338Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11
excerpt: This Article Describes Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11
keywords: Windows Login Security,Failed Sign-In Protocols,Account Lockout Settings,Windows 10/11 Safeguards,Limit Unauthorized Access,Sign-In Failure Response,Post-Failure Policy Update
thumbnail: https://thmb.techidaily.com/07cfabd2fe9acb782e30cca8205dc0f557a2c3371dbf02532bc0633c00063d56.jpg
---

## Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11

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
<li><a href="https://win11-tips.techidaily.com/safeguard-files-when-maximizing-space-in-windows/"><u>Safeguard Files When Maximizing Space in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-using-netstat-in-windows-11/"><u>A Comprehensive Tutorial: Using Netstat in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-themes-for-enhanced-terminal-views/"><u>Innovative Themes for Enhanced Terminal Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-x7007043c-in-windows-media-creator/"><u>Eradicating Error X.7007043C in Windows' Media Creator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-pc-performance-insider-tips-on-wintools/"><u>Elevate PC Performance: Insider Tips on WinTools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/github-desktop-essentials-for-effective-windows-git-control/"><u>GitHub Desktop Essentials for Effective Windows Git Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-search-with-image-cleanse/"><u>Simplifying Windows Search with Image Cleanse</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-vivo-y100t-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Vivo Y100t? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-realme-c33-2023-frp-by-drfone-android/"><u>Full Guide to Bypass Realme C33 2023 FRP</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-creating-high-impact-yt-cover-images/"><u>[New] In 2024, Creating High-Impact YT Cover Images</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-above-and-beyond-selecting-premium-software-for-drone-filmmaking/"><u>2024 Approved  Above & Beyond  Selecting Premium Software for Drone Filmmaking</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-identifying-the-best-cloud-service-allies-of-2024/"><u>[New] Identifying the Best Cloud Service Allies of 2024</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-samsung-galaxy-s24-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-mastering-audio-manipulation-speed-and-pitch-adjustments-in-adobe-rush/"><u>Updated In 2024, Mastering Audio Manipulation Speed and Pitch Adjustments in Adobe Rush</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-chromes-multi-screen-magic-pip-tutorial/"><u>2024 Approved  Chrome's Multi-Screen Magic  PIP Tutorial</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>