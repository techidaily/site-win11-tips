---
title: "Alteration of Login Failure Counter: Windows 11 User Guide"
date: 2025-01-30T01:54:58.264Z
updated: 2025-02-01T14:52:26.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Alteration of Login Failure Counter: Windows 11 User Guide"
excerpt: "This Article Describes Alteration of Login Failure Counter: Windows 11 User Guide"
keywords: Win11 Login Troubleshooting,11 PC Login Fix Guide,11 User Error Logout Help,Correcting Login Failures in Windows 11,Enhancing Login Success Rate Windows 11,Resetting Failed Logins on Win11,Overcoming 11 Login Issues Guide
thumbnail: https://thmb.techidaily.com/6c7b51dcfdae2a8da726c75853a324eb9a3939b33880d7b4a364119150ff2caf.jpg
---

## Alteration of Login Failure Counter: Windows 11 User Guide

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-glue.techidaily.com/new-in-2024-unleashing-full-potential-of-zoom-with-chromebook/"><u>[New] In 2024, Unleashing Full Potential of Zoom with Chromebook</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-flash-and-fly-gaming-top-10-speedy-apps-on-desktopmobile/"><u>[Updated] Flash & Fly Gaming Top 10 Speedy Apps on Desktop/Mobile</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-harmonizing-images-essential-tutorials-for-color-mastery/"><u>[Updated] In 2024, Harmonizing Images Essential Tutorials for Color Mastery</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-next-level-3d-watching-ultimate-guide-to-blu-ray-players/"><u>[Updated] Next-Level 3D Watching Ultimate Guide to Blu-Ray Players</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-frozen-media-app-on-your-windows-11-system/"><u>Cure Frozen Media App on Your Windows 11 System</u></a></li>
<li><a href="https://driver-install.techidaily.com/direct-driver-update-via-ddu-2024-insights/"><u>Direct Driver Update via DDU - 2024 Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-display-dreams-tailoring-each-monitors-visual-experience-in-win-1011/"><u>Dual Display Dreams: Tailoring Each Monitor's Visual Experience in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-solve-voice-chat-failures-in-valorant-pc/"><u>Essential Tips to Solve Voice Chat Failures in Valorant (PC)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-itel-a60-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Itel A60 to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-restoring-the-dormant-wsreset-on-your-pc/"><u>Methods for Restoring the Dormant WSReset on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-tips-to-optimize-fps-in-csgo-matches/"><u>Pro Tips to Optimize FPS in CS:GO Matches</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-correcting-failed-java-setup-in-windows/"><u>Techniques for Correcting Failed Java Setup in Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-of-digital-connectivity-unveiling-facebook-twitter-instagram-youtube/"><u>The Big Four of Digital Connectivity: Unveiling Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-essential-tips-resolving-issues-in-systems-power-on-self-test-post/"><u>Troubleshooting Essential Tips: Resolving Issues in System's Power-On Self Test (POST)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-n-lineup-analyzed-optimal-selections/"><u>Windows N Lineup Analyzed: Optimal Selections</u></a></li>
</ul></div>

