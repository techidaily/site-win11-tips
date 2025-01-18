---
title: How to Fine-Tune Account Lockout Counter After Failed Logins on Windows 11 OS
date: 2025-01-16T17:14:22.722Z
updated: 2025-01-18T17:19:10.901Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fine-Tune Account Lockout Counter After Failed Logins on Windows 11 OS
excerpt: This Article Describes How to Fine-Tune Account Lockout Counter After Failed Logins on Windows 11 OS
keywords: Windows 11 Login Lockout Adjustment,Optimize Windows Account Security,Fine-Tune Windows 11 Lockouts,Manage Failed Logins Windows 11,Reduce Windows Lockout Attempts,Secure Windows 11 Login Policy,Customize Windows Counter Lockouts
thumbnail: https://thmb.techidaily.com/6631d02aad6297e4d6f700e032b5f1a6df7f0a4821dff69d11f95fe1acb0191f.jpg
---

## How to Fine-Tune Account Lockout Counter After Failed Logins on Windows 11 OS

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/new-favourites-revealed-top-20-anime-melodies-for-2024/"><u>[New] Favourites Revealed Top 20 Anime Melodies for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-memory-map-maker/"><u>[New] Memory Map Maker</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-soloists-journey-personal-growth-and-success-on-youtube-for-musicians/"><u>[New] The Soloist's Journey Personal Growth and Success on YouTube for Musicians</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-essential-skills-for-efficient-teamsnap-photo-taking/"><u>[Updated] In 2024, Essential Skills for Efficient TeamSnap Photo Taking</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-ultimate-guide-to-choosing-a-screen-recorder-tool/"><u>2024 Approved Ultimate Guide to Choosing a Screen Recorder Tool</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211261270-9798887637884-at-your-core/"><u>At Your Core | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-paudio-conundrum-windows-10-and-11s-audio-dilemma/"><u>Deciphering PAudio Conundrum: Windows 10 & 11'S Audio Dilemma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-overcome-settings-loss-after-system-shutdown/"><u>Guide to Overcome Settings Loss After System Shutdown</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-v29e-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Vivo V29e Phone with Broken Screen</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-push-boundaries-with-unique-split-screen-videos-for-youtube/"><u>In 2024, Push Boundaries with Unique Split-Screen Videos for YouTube</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-transition-addressing-7-common-hurdles-of-digital-twin-technology-in-businesses-zdnet/"><u>Mastering the Transition: Addressing 7 Common Hurdles of Digital Twin Technology in Businesses | ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-pcs-potential-onedrive-fails-remedied/"><u>Mastering Your PC's Potential: OneDrive Fails Remedied</u></a></li>
<li><a href="https://win11-tips.techidaily.com/paint-your-thoughts-clearly-mastering-note-taking-with-obsidian/"><u>Paint Your Thoughts Clearly - Mastering Note-Taking with Obsidian</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-correcting-disk-readwrite-issues/"><u>Preventing and Correcting Disk Read/Write Issues</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-cortana-activation-in-windows-11/"><u>Preventing Cortana Activation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-automatic-voice-feature-in-ms-word/"><u>Restoring Automatic Voice Feature in MS Word</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shut-down-specification-failure-sticker-in-os/"><u>Shut Down Specification Failure Sticker in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-preserve-windows-system-time-settings/"><u>Strategies to Preserve Windows System Time Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-methods-to-use-telnet-in-windows-11/"><u>Three Methods to Use Telnet in Windows 11</u></a></li>
</ul></div>

