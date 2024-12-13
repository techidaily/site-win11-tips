---
title: Customizing Login Attempt Wait Time for Windows OS
date: 2024-12-06T20:05:17.437Z
updated: 2024-12-12T17:52:44.253Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Login Attempt Wait Time for Windows OS
excerpt: This Article Describes Customizing Login Attempt Wait Time for Windows OS
keywords: WinLoginDelay,CustomWaitOS,UserLoginPause,OSAuthTimeAdj,SecureLoginWindows,WindowsLoginCustomize,AdaptiveLoginRate
thumbnail: https://thmb.techidaily.com/91d880ab7920ac263b2bbc42f64c84854115542d15d4b0d06e6a3ab502cdbe2d.jpg
---

## Customizing Login Attempt Wait Time for Windows OS

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-in-2024-essential-steps-for-diminishing-audio-intensity-in-lumafusion/"><u>[New] In 2024, Essential Steps for Diminishing Audio Intensity in Lumafusion</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-navigating-gopro-lens-distortion-in-post-production/"><u>[Updated] 2024 Approved Navigating GoPro Lens Distortion in Post-Production</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-step-by-step-guide-to-crafting-youtube-splitscreen-content/"><u>[Updated] In 2024, Step-by-Step Guide to Crafting YouTube Splitscreen Content</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209845687-9781936470679-dreams/"><u>Dreams | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-0x8007251d-activation-issue-in-windows-os/"><u>Fixing the 0X8007251D Activation Issue in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-managed-settings-failures-due-to-org-policies/"><u>Fixing Windows 11: Managed Settings Failures Due to Org Policies</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-and-solve-apex-legends-crashes-in-win11/"><u>How to Stop and Solve Apex Legends Crashes in Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-3-easy-youtube-audio-extraction-methods-free-and-secure/"><u>In 2024, 3 Easy YouTube Audio Extraction Methods Free & Secure</u></a></li>
<li><a href="https://driver-install.techidaily.com/protected-logitech-camera-upgrade/"><u>Protected Logitech Camera Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-patches-without-wi-fi/"><u>Streamlining Windows Patches Without Wi-Fi</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-pc-gaming-issues-fix-crashes/"><u>Troubleshooting PC Gaming Issues: Fix Crashes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    