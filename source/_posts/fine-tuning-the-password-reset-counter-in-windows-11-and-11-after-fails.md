---
title: Fine-Tuning the Password Reset Counter in Windows 11 and 11 After Fails
date: 2024-12-24T19:53:47.097Z
updated: 2024-12-27T20:58:02.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fine-Tuning the Password Reset Counter in Windows 11 and 11 After Fails
excerpt: This Article Describes Fine-Tuning the Password Reset Counter in Windows 11 and 11 After Fails
keywords: Win11 PassResetOptimize,Windows 11 FixPasswordFail,ResetCounterEnhanceWin,OptimizingPassFixWindows,PasswordResetImproveWin,FailCounterTweakWin11,FineTuneWin11PasswordResets
thumbnail: https://thmb.techidaily.com/aca28fbc907b3b2134a063785955f99d7ee87845f83996484c29a6f763ca253a.jpg
---

## Fine-Tuning the Password Reset Counter in Windows 11 and 11 After Fails

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-access.techidaily.com/updated-in-2024-what-are-the-disadvantages-of-vr/"><u>[Updated] In 2024, What Are the Disadvantages of VR?</u></a></li>
<li><a href="https://apple-account.techidaily.com/a-step-by-step-guide-to-finding-your-apple-id-on-your-iphone-12-mini-by-drfone-ios/"><u>A Step-by-Step Guide to Finding Your Apple ID On Your iPhone 12 mini</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-incorrect-estimated-time-remaining-indicator-in-win-11/"><u>Fixing Incorrect Estimated Time Remaining Indicator in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-started-windows-canary-channel-overview/"><u>Getting Started: Windows Canary Channel Overview</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-motorola-moto-g23-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Motorola Moto G23 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-itel-p40-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Itel P40?</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Vivo Y100? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-browser-glitches-7-solutions-for-firefox-crash-in-windows/"><u>Mastering Browser Glitches: 7 Solutions for Firefox Crash in Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-poetry-with-chatgpt-a-guide/"><u>Mastering the Art of Poetry with ChatGPT: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-new-laptop-go-3-cpu-assessment-strengthening-weaknesses/"><u>Microsoft's New Laptop Go 3 CPU Assessment: Strengthening Weaknesses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicken-task-manager-live-data-refresh-in-windows-11/"><u>Quicken Task Manager Live Data Refresh in Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/savvy-spending-secrets-for-xbox-series-gaming/"><u>Savvy Spending Secrets for Xbox Series Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seek-out-your-windows-backdrop-file-in-win11/"><u>Seek Out Your Window's Backdrop File in Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-streaming-your-phones-videos-to-amazon-fire-tv/"><u>Step-by-Step Guide: Streaming Your Phone's Videos to Amazon Fire TV</u></a></li>
<li><a href="https://driver-download.techidaily.com/successfully-addressing-window-based-challenges-for-samsung-printer-users-a-comprehhavemore-detailed-look-at-driver-issues-and-their-solutions/"><u>Successfully Addressing Window-Based Challenges for Samsung Printer Users: A Comprehhavemore Detailed Look at Driver Issues and Their Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-google-play-setup-on-windows-11/"><u>Tutorial: Google Play Setup on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-meaning-behind-windows-folders-x-marked/"><u>Unlocking: The Meaning Behind Windows Folders X-Marked</u></a></li>
</ul></div>

