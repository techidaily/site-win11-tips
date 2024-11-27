---
title: Modifying Reset Counter for Locked Out Users Post Incorrect Logins
date: 2024-11-21T17:24:26.023Z
updated: 2024-11-27T16:31:22.205Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Reset Counter for Locked Out Users Post Incorrect Logins
excerpt: This Article Describes Modifying Reset Counter for Locked Out Users Post Incorrect Logins
keywords: Reset Pass Attempt Limit,Unlock Account Post-Failure,Reverse Login Cooldowns,Modify Lockout Counter,Correct Logins Restriction Lift,Override Incorrect Password Block,Redefine Lockout Policy
thumbnail: https://thmb.techidaily.com/1c82bb77bafb99b9b6611b5302d1fb010d446c70d3f6bad7daef0045c02e4cb1.png
---

## Modifying Reset Counter for Locked Out Users Post Incorrect Logins

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-tips.techidaily.com/new-ultimate-choice-for-engaging-type-animations/"><u>[New] Ultimate Choice for Engaging Type Animations</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-forget-your-finstas-quickly-iosandroid-advice/"><u>[Updated] 2024 Approved Forget Your Finstas Quickly IOS/Android Advice</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-the-quick-guide-to-capturing-and-storing-twitter-animated-content/"><u>2024 Approved The Quick Guide to Capturing and Storing Twitter Animated Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/covert-drive-strategies-for-ws1110-users/"><u>Covert Drive Strategies for WS11/10 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decreasing-system-overload-reducing-media-impact-on-windows-pcs-resources/"><u>Decreasing System Overload: Reducing Media Impact on Windows PC's Resources</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-vivo-y100-5g-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Vivo Y100 5G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-code-0x8024a205-a-winupdate-solution-guide/"><u>Error Code 0X8024a205: A WinUpdate Solution Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/finding-the-right-pace-whats-ideal-for-your-pc/"><u>Finding the Right Pace: What's Ideal for Your PC?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-misaligned-spatial-sound-on-windows-pcs/"><u>Fixing Misaligned Spatial Sound on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-discord-installation-woes-on-pclaptop/"><u>How to Rectify Discord Installation Woes on PC/Laptop</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-leading-15-no-cost-image-editing-apps-top-picks-of-2023/"><u>In 2024, Leading 15 No-Cost Image Editing Apps - Top Picks of 2023</u></a></li>
<li><a href="https://extra-support.techidaily.com/journey-through-lut-based-color-enhancement-methods-for-2024/"><u>Journey Through LUT-Based Color Enhancement Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-tools-to-convert-videos-seamlessly-on-your-pc-windows/"><u>Top 6 Tools to Convert Videos Seamlessly on Your PC, Windows</u></a></li>
</ul></div>

