---
title: A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
date: 2025-01-25T13:23:31.065Z
updated: 2025-02-01T00:00:31.135Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
excerpt: This Article Describes A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
keywords: Window's Lockout Tweaks,Lockout Modification Guide,PC Security Settings,Increase Lockout Time,User Account Access Control,Windows Adjustments Quick,Manage Lockout Frequency
thumbnail: https://thmb.techidaily.com/bab37a5357094e09dd42f37d3cc78e25fe907bbcf4a7b3121bebc119dc83e730.jpg
---

## A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-get-it-right-the-first-time-instagrams-video-sizing-guide-for-2024/"><u>[New] Get It Right the First Time Instagram's Video Sizing Guide for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-best-camcorder-tech-for-shooting-sports/"><u>[New] In 2024, Best Camcorder Tech for Shooting Sports</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-streamline-your-youtube-experience-manage-video-comments/"><u>[Updated] 2024 Approved Streamline Your YouTube Experience Manage Video Comments</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-swap-periscopes-lens-innovative-video-platforms-for-smartphones/"><u>2024 Approved Swap Periscope's Lens Innovative Video Platforms for Smartphones</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/tive-approach-to-swiftly-eliminate-video-comments/"><u>Effective Approach to Swiftly Eliminate Video Comments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-save-configuration-flaw-pubg-on-windows/"><u>Fixing the Save Configuration Flaw: PUBG on Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-vivo-y36i-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Vivo Y36i</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-resolve-crashing-errors-when-playing-monster-hunter-rise/"><u>How to Resolve Crashing Errors When Playing Monster Hunter Rise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ifa-showcase-cutting-edge-laptops-of-2023/"><u>IFA Showcase: Cutting-Edge Laptops of 2023</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-converting-videos-with-impact-sdr-to-hdr-your-essential-guide/"><u>In 2024, Converting Videos with Impact SDR to HDR - Your Essential Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-honor-x9b-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Honor X9b FRP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-temperature-safety-mechanisms/"><u>Navigating Windows' Temperature Safety Mechanisms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscovering-the-missing-tab-button-on-your-laptop/"><u>Rediscovering the Missing Tab Button on Your Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipit-stumbles-9-techniques-to-overcome-obstructions/"><u>SnipIt Stumbles? 9 Techniques to Overcome Obstructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-update-problem-error-code-0x800f0845/"><u>Solving Windows Update Problem - Error Code: 0X800f0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-solving-system-call-fails-in-windows-1011/"><u>Strategies for Solving 'System Call Fails' In Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-vintage-video-games-adding-trophies-via-retroarch/"><u>The Art of Vintage Video Games - Adding Trophies via Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-comprehensive-walkthrough-of-microsoft-works-in-w11/"><u>The Comprehensive Walkthrough of Microsoft Works in W11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ultimate-list-of-airtag-peripherals-expert-opinions-and-ratings-zdnet/"><u>Ultimate List of AirTag Peripherals : Expert Opinions and Ratings | ZDNet</u></a></li>
</ul></div>

