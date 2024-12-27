---
title: Method for Altering Reset Counter After Failed Logins
date: 2024-12-23T19:40:53.546Z
updated: 2024-12-27T16:35:23.497Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Method for Altering Reset Counter After Failed Logins
excerpt: This Article Describes Method for Altering Reset Counter After Failed Logins
keywords: Change Reset Counter Login Fail,Modify Failed Logout Count,Increase Lockout Attempts Number,Adjust Failed Logins Retry Limit,Escalate Unsuccessful Login Trials,Recalibrate Login Failure Tally,Extend Reset Attempt Sequence
thumbnail: https://thmb.techidaily.com/a686c6eefaf9c4b50a452c73ac89f7229b66217691cf20f6f81f6b08cd386aeb.jpg
---

## Method for Altering Reset Counter After Failed Logins

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/new-in-2024-unraveling-the-discrepant-nature-of-vr-and-full-sphere-capture/"><u>[New] In 2024, Unraveling the Discrepant Nature of VR and Full Sphere Capture</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-transform-your-igtv-videos-tips-for-impactful-titles-and-summaries/"><u>[New] Transform Your IGTV Videos Tips for Impactful Titles & Summaries</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-innovation-in-minimization-the-finest-selection-of-43-mobile-video-trimming-apps-for-2024/"><u>[Updated] Innovation in Minimization The Finest Selection of 43 Mobile Video Trimming Apps for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-top-10-forgetful-fun-mobile-idle-escapes-for-2024/"><u>[Updated] Top 10 Forgetful Fun Mobile Idle Escapes for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-top-video-platforms-safe-and-streamlined-sme-solutions/"><u>2024 Approved Top Video Platforms Safe & Streamlined SME Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-code-0x800f0831-in-windows-os/"><u>Conquering Error Code 0X800F0831 in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-enhanced-windows-11-configurations/"><u>Discovering Enhanced Windows 11 Configurations</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-xiaomi-redmi-13c-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Xiaomi Redmi 13C in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/enhance-your-online-presence-using-manycam-leading-live-video-production-and-virtually-unlimited-webcams/"><u>Enhance Your Online Presence Using ManyCam: Leading Live Video Production and Virtually Unlimited Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-enhancing-gpo-settings-access-win11-edition/"><u>Expert Tips for Enhancing GPO Settings Access, Win11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-taskbar-disruption/"><u>Overcoming Windows 11 Taskbar Disruption</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-mouseclicklock-functionality-in-win-os/"><u>Simplifying MouseClickLock Functionality in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-ms-store-glitches-on-win-1111-platforms/"><u>Solutions for MS Store Glitches on Win 11/11 Platforms</u></a></li>
<li><a href="https://program-issues.techidaily.com/solve-your-discord-crash-issues-effective-strategies-and-tips/"><u>Solve Your Discord Crash Issues: Effective Strategies and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-erratic-cursor-in-windows-78/"><u>Taming the Erratic Cursor in Windows 7/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-bar-evolution-and-significance-1985-2023/"><u>The Windows Bar: Evolution and Significance (1985-2023)</u></a></li>
</ul></div>

