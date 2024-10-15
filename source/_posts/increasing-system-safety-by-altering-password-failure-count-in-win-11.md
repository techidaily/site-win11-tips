---
title: Increasing System Safety by Altering Password Failure Count in Win 11
date: 2024-10-08T19:37:05.166Z
updated: 2024-10-15T00:38:21.079Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Increasing System Safety by Altering Password Failure Count in Win 11
excerpt: This Article Describes Increasing System Safety by Altering Password Failure Count in Win 11
keywords: Win 11 Security Boost,Password Change Impact,Reduce Login Attempts,Enhance OS Safety,System Failure Limit,Secure Win 11 Passwords,Optimize Safe Access
thumbnail: https://thmb.techidaily.com/243178c138d6204ad2bbeb47ec4cfcdba020958c11cab04cb22d5f5327eef01b.jpg
---

## Increasing System Safety by Altering Password Failure Count in Win 11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123736/7443" target="_top" id="2123736">
  <img src="//a.impactradius-go.com/display-ad/7443-2123736" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123736/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/n-2024-master-the-art-of-streaming-pick-from-the-leading-6-cost-free-and-on-demand-short-video-downloads/"><u>[New] In 2024, Master the Art of Streaming Pick From the Leading 6 Cost-Free & On-Demand Short Video Downloads</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-ultimate-recording-gear-for-social-media-stars/"><u>[New] In 2024, Ultimate Recording Gear for Social Media Stars</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-perfecting-proportions-understanding-youtube-video-sizes/"><u>[Updated] In 2024, Perfecting Proportions Understanding YouTube Video Sizes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-full-review-of-cutspace-suite-with-visualfx-tools-2023-for-2024/"><u>A Full Review of CutSpace Suite with VisualFX Tools, 2023 for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/back-astock-exchange-traded-fund-etf-veubatsan-overview/"><u>Back Astock Exchange Traded Fund (ETF) - VEU/BATS:An Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-confusion-a-guide-to-reinstalling-store-software/"><u>Clearing Up Confusion: A Guide to Reinstalling Store Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-tap-for-apks-a-user-friendly-guide-in-win-11/"><u>Double-Tap for APKs: A User-Friendly Guide in Win 11</u></a></li>
<li><a href="https://data-wizards.techidaily.com/excellent-visual-repair-service-praises-aplenty/"><u>Excellent Visual Repair Service, Praises Aplenty</u></a></li>
<li><a href="https://tech-haven.techidaily.com/experience-cutting-edge-ai-for-free-with-our-in-depth-copilot-tutorial-on-gpt-cu4-turbo-mastery/"><u>Experience Cutting-Edge AI for FREE with Our In-Depth Copilot Tutorial on GPT-Cu4 Turbo Mastery</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fastest-phone-apps-for-faster-audio-streaming-for-2024/"><u>Fastest Phone Apps for Faster Audio Streaming for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-admin-level-execution-woes/"><u>Guiding Users Through Admin-Level Execution Woes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-infinix-note-30-vip-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Infinix Note 30 VIP Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsoft-works-with-windows-11-easy/"><u>Integrating Microsoft Works with Windows 11 Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-safety-sticky-notes-edition/"><u>Mastering File Safety: Sticky Notes Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-o365-sync-issues-a-quick-guide-to-fixing-errors/"><u>Win 11 and O365 Sync Issues: A Quick Guide to Fixing Errors</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    