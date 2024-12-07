---
title: Modifying Failed Logon Lockout Period for Win10/11
date: 2024-12-03T20:18:17.956Z
updated: 2024-12-07T01:41:43.525Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Failed Logon Lockout Period for Win10/11
excerpt: This Article Describes Modifying Failed Logon Lockout Period for Win10/11
keywords: Windows Login Cooldown Adjustment,Change Account Unlock Time,Alter Failed Login Interval,Modify Windows Lockout Period,Reset Credential Lockout Time,Update Win10/11 Logon Restriction,Extend Failed Login Wait Period
thumbnail: https://thmb.techidaily.com/052918d3e56b96021eca7b3225588078d8b2ee409e0b799bdcb8f9f006f59b01.jpg
---

## Modifying Failed Logon Lockout Period for Win10/11

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-discover-your-new-favorites-with-our-best-offline-ios-games-list/"><u>[New] In 2024, Discover Your New Favorites with Our Best Offline iOS Games List</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-beginners-guide-video-setup-must-haves/"><u>[Updated] Beginner's Guide Video Setup Must-Haves</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-stream-undoing-simplified-15-actionable-insights-to-retrace-your-broadcast-trail/"><u>[Updated] Stream Undoing Simplified 15 Actionable Insights to Retrace Your Broadcast Trail</u></a></li>
<li><a href="https://extra-information.techidaily.com/10-best-websites-to-download-aesthetic-wallpapers-for-laptop-for-2024/"><u>10 Best Websites to Download Aesthetic Wallpapers for Laptop for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/charting-the-course-of-seafaring-slang/"><u>Charting the Course of Seafaring Slang</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-e8024002e-for-update-issues/"><u>Fixing Error E:8024002E for Update Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unopened-sharing-error-in-windows-1011s-experience/"><u>Fixing Unopened Sharing Error in Windows 10/11'S Experience</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Motorola Moto G13? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-ftdibussys-how-it-challenges-windows-memory-security/"><u>Inside ftdibus.sys: How It Challenges Windows Memory Security</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-pcs-mainteninas-with-folder-reboots-on-windows-11/"><u>Streamline Your PC's Mainteninas with Folder Reboots on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-windows-aesthetics-in-8-easy-steps/"><u>Streamline Your Windows Aesthetics in 8 Easy Steps</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-xiaomi-redmi-k70-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Xiaomi Redmi K70?</u></a></li>
</ul></div>

