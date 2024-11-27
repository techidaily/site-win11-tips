---
title: Redefining Reset Count for Lockouts After Logon Errors in Windows 11 Pro
date: 2024-11-20T16:17:36.349Z
updated: 2024-11-27T17:45:34.182Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redefining Reset Count for Lockouts After Logon Errors in Windows 11 Pro
excerpt: This Article Describes Redefining Reset Count for Lockouts After Logon Errors in Windows 11 Pro
keywords: Windows 11 Login Reckoning,Redesigned Lockout Count,Pro Windows Reset Counter,11 PC Lockout Errors,Logon Failure Management,Windows Lockout Policy,New Error Reset Strategy
thumbnail: https://thmb.techidaily.com/d1af8070250ed0fc44c0eb3bb732f040d9be0391dec23043dea2f82d9170e773.jpg
---

## Redefining Reset Count for Lockouts After Logon Errors in Windows 11 Pro

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-creative-couture-top-trendy-filters-on-ig/"><u>[Updated] 2024 Approved Creative Couture Top Trendy Filters on IG</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-leading-sites-for-extracting-text-aesthetics-packs/"><u>[Updated] 2024 Approved Leading Sites for Extracting Text Aesthetics Packs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-snapchats-hidden-content-finding-and-restoring-photos/"><u>[Updated] 2024 Approved Snapchat's Hidden Content Finding and Restoring Photos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/accessing-and-archiving-your-facebook-status-vids/"><u>Accessing and Archiving Your Facebook Status Vids</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/complete-guide-for-macos-sierra-patches-and-plug-ins-for-2024/"><u>Complete Guide for macOS Sierra Patches and Plug-Ins for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-streamline-network-performance-with-dns-cleanse/"><u>Guide to Streamline Network Performance with DNS Cleanse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-load-steamuidll-error-in-steam-for-windows/"><u>How to Fix the “Failed to Load steamui.dll” Error in Steam for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-problem-of-unreachable-nvidia-cp/"><u>How to Fix the Problem of Unreachable Nvidia CP</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-samsung-galaxy-a14-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Samsung Galaxy A14 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-index-modification/"><u>Mastering Windows Index Modification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-sound-barrier-audacitys-portaudio-in-wos/"><u>Mending the Sound Barrier: Audacity's PortAudio in WOS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/rapidity-reshaping-for-professional-mp4s-for-2024/"><u>Rapidity Reshaping for Professional MP4s for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-eliminating-power-save-for-usbs-in-windows-11/"><u>Stay Connected - Eliminating Power Save for USBs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quest-for-sid-knowledge-decoding-in-windows-11/"><u>The Quest for SID Knowledge: Decoding in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-turning-off-stealth-mode-windows-tasks/"><u>Tips for Turning Off Stealth Mode Windows Tasks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-vivo-y27-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Vivo Y27 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://media-tips.techidaily.com/unlocking-the-secrets-of-spotifys-overlooked-jam-session-functionality/"><u>Unlocking the Secrets of Spotify's Overlooked Jam Session Functionality</u></a></li>
</ul></div>

