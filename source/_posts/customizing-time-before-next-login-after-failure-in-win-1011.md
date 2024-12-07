---
title: Customizing Time Before Next Login After Failure in Win 10/11
date: 2024-12-03T16:56:29.665Z
updated: 2024-12-06T16:09:52.899Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Time Before Next Login After Failure in Win 10/11
excerpt: This Article Describes Customizing Time Before Next Login After Failure in Win 10/11
keywords: Windows Login Customization,Timeout Settings Win 10,Win10 Session Limit Adjustment,Login Delay Mechanism Win11,Preventing Repeated Login Failure,User-Defined Login Timelimit,Secure Windows Login Retry Policy
thumbnail: https://thmb.techidaily.com/c44b3c2a949ed90a1a74d6b8f5c0458cbf8a943f8d64ce0fc757b91844bd2888.jpg
---

## Customizing Time Before Next Login After Failure in Win 10/11

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-from-flat-to-fascinating-crafting-depth-in-text-art/"><u>[New] From Flat to Fascinating Crafting Depth in Text Art</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-optimizing-speed-on-vimeo-content/"><u>[New] In 2024, Optimizing Speed on Vimeo Content</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-resurrecting-windows-photo-viewer-a-compreehr-guide-for-win10-users/"><u>[New] In 2024, Resurrecting Windows Photo Viewer - A Compreehr Guide for Win10 Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-revolutionizing-screen-experience-lgs-2023-bp550/"><u>[Updated] Revolutionizing Screen Experience - LG's 2023 BP550</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-simplify-satire-funniest-memes-made-simple/"><u>[Updated] Simplify Satire Funniest Memes Made Simple</u></a></li>
<li><a href="https://driver-download.techidaily.com/brother-hl-3170cdw-driver-installation-fast-and-simple-guide/"><u>Brother HL-3170CDW Driver Installation: Fast and Simple Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhance-your-movie-night-a-step-by-step-tutorial-for-streaming-3d-content-on-fandango-at-home/"><u>Enhance Your Movie Night: A Step-by-Step Tutorial for Streaming 3D Content on Fandango at Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-this-app-is-preventing-windows-from-shutting-down-restarting-or-signing-out-error-on-windows/"><u>How to Fix “This App Is Preventing Windows From Shutting Down, Restarting, or Signing Out” Error on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-livestreaming-leaderboards-which-software-tops-the-chartvmixwirecast/"><u>In 2024, Livestreaming Leaderboards Which Software Tops the Chart—VMix/Wirecast?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-zeroxc000003e-error-in-win1011-application-initiation/"><u>Navigating ZeroXc000003e Error in Win10/11 Application Initiation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pause-in-play-reactivating-computers-sound-system/"><u>Pause in Play? Reactivating Computer's Sound System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-old-computers-switching-away-from-windows/"><u>Refreshing Old Computers: Switching Away From Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-windows-11-calendar-features/"><u>The Ultimate Guide to Windows 11 Calendar Features</u></a></li>
<li><a href="https://article-helps.techidaily.com/transforming-photos-with-easy-online-cropping-steps-for-2024/"><u>Transforming Photos with Easy Online Cropping Steps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-how-ai-transforms-windows-innovations/"><u>Unlocking Potential: How AI Transforms Windows Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-your-windows-11-local-login-without-secure-questions/"><u>Unlocking Your Windows 11 Local Login Without Secure Questions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-methods-enhancing-windows-disk-capacity-without-spending/"><u>Winning Methods: Enhancing Windows Disk Capacity without Spending</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winvpn-error-connection-lost-explained-and-fixed/"><u>WinVPN Error: Connection Lost Explained and Fixed</u></a></li>
</ul></div>

