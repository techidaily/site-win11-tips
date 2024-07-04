---
title: A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
date: 2024-07-03T12:50:31.061Z
updated: 2024-07-04T12:50:31.061Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
excerpt: This Article Describes A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
keywords: Window's Lockout Tweaks,Lockout Modification Guide,PC Security Settings,Increase Lockout Time,User Account Access Control,Windows Adjustments Quick,Manage Lockout Frequency
thumbnail: https://thmb.techidaily.com/bab37a5357094e09dd42f37d3cc78e25fe907bbcf4a7b3121bebc119dc83e730.jpg
---

## A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor

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
<li><a href="https://win11-tips.techidaily.com/bridging-network-gaps-win-10-and-11-written-for-telnet-users/"><u>Bridging Network Gaps: Win 10 & 11' Written for Telnet Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disappearing-badge-icons/"><u>Addressing Disappearing Badge Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sign-out-failures-from-non-standard-windows-applications/"><u>Resolving Sign-Out Failures From Non-Standard Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-seamless-multilingual-input-adjusting-keyboard-layout-in-windows-11/"><u>Achieve Seamless Multilingual Input: Adjusting Keyboard Layout in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-data-exchange-safeguarding-files-across-ws11w10/"><u>Silent Data Exchange: Safeguarding Files Across WS11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-command-prompt-integrating-folders-into-context-menu/"><u>Elevate Your Command Prompt: Integrating Folders Into Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disguised-delayers-innocuous-apps-hindering-pc-speed/"><u>Disguised Delayers: Innocuous Apps Hindering PC Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-blank-screens-on-system-ignition/"><u>Addressing Blank Screens on System Ignition</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-essential-zoom-techniques-for-chromebook-proficiency/"><u>[Updated] In 2024, Essential Zoom Techniques for Chromebook Proficiency</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/top-aspect-ratio-conversion-tools-on-the-web-for-2024/"><u>Top Aspect Ratio Conversion Tools on the Web for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-oppo-f23-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-thumbnails-that-attract-techniques-for-youtube-image-resizing/"><u>[New] In 2024, Thumbnails That Attract  Techniques for YouTube Image Resizing</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On ZTE Nubia Flip 5G? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-itel-a05s-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Itel A05s | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-xiaomi-redmi-note-13-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-crafting-moments-of-happiness-animated-filters-on-your-phone/"><u>[New] In 2024, Crafting Moments of Happiness  Animated Filters on Your Phone</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-5-mobile-photo-editing-iphone-x87-background-switch-for-2024/"><u>Ultimate 5 Mobile Photo Editing  IPhone X/8/7 Background Switch for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>