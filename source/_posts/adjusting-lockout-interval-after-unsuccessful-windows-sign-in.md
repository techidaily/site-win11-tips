---
title: Adjusting Lockout Interval After Unsuccessful Windows Sign In
date: 2025-01-24T19:51:57.616Z
updated: 2025-01-31T18:20:35.622Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Lockout Interval After Unsuccessful Windows Sign In
excerpt: This Article Describes Adjusting Lockout Interval After Unsuccessful Windows Sign In
keywords: Lockout Management,Password Reset Protocols,Unsuccessful Login Handling,Windows Security Settings,Account Lock Recovery,Sign In Failure Adjustment,Access Issue Resolution
thumbnail: https://thmb.techidaily.com/fbcf05b0c32ba329cf6957ae3248e625c39ba58c1a53bbe9519d95b22a1c1295.jpg
---

## Adjusting Lockout Interval After Unsuccessful Windows Sign In

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/reakdown-of-earnings-how-much-does-a-clicky-make-in-2024/"><u>[New] Breakdown of Earnings How Much Does a Clicky Make, In 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-mastering-screencast-with-ezvide-maker-tool/"><u>[Updated] 2024 Approved Mastering Screencast with EZvide Maker Tool</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-quick-tips-for-uploading-content-on-twitter/"><u>[Updated] 2024 Approved Quick Tips for Uploading Content on Twitter</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hidden-gems-in-graphic-design-basics/"><u>2024 Approved Hidden Gems in Graphic Design Basics</u></a></li>
<li><a href="https://article-tips.techidaily.com/gaming-harmonies-archive-legal-free-to-access-for-2024/"><u>Gaming Harmonies Archive Legal, Free to Access for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-vivo-x100-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Vivo X100 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premium-performance-in-a-package-that-pleases-your-pocket/"><u>In 2024, Premium Performance in a Package That Pleases Your Pocket</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210192643-9781642796179-moneyfulness/"><u>Moneyfulness | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-failed-installation-process-for-apps-from-microsoft-store/"><u>Reinstating Failed Installation Process for Apps From Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-heat-build-up-in-games-on-your-laptop/"><u>Strategies to Prevent Heat Build-Up in Games on Your Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-nvidias-geforce-error-x0001-on-windows/"><u>Strategies to Solve Nvidia's GeForce Error X0001 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-image-adjustment-on-your-pc-with-these-win-11-tips/"><u>Streamline Image Adjustment on Your PC with These Win 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-icons-placement/"><u>The Essential Guide to Icons Placement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-error-correction-resolving-0x80070003-update-issue-in-windows/"><u>Win Error Correction: Resolving 0X80070003 Update Issue in Windows</u></a></li>
</ul></div>

