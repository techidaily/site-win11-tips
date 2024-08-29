---
title: Modifying Reset Counter for Locked Out Users Post Incorrect Logins
date: 2024-08-28T01:16:15.625Z
updated: 2024-08-29T01:16:15.625Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Reset Counter for Locked Out Users Post Incorrect Logins
excerpt: This Article Describes Modifying Reset Counter for Locked Out Users Post Incorrect Logins
keywords: Reset Pass Attempt Limit,Unlock Account Post-Failure,Reverse Login Cooldowns,Modify Lockout Counter,Correct Logins Restriction Lift,Override Incorrect Password Block,Redefine Lockout Policy
thumbnail: https://thmb.techidaily.com/1c82bb77bafb99b9b6611b5302d1fb010d446c70d3f6bad7daef0045c02e4cb1.png
---

## Modifying Reset Counter for Locked Out Users Post Incorrect Logins

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-thrifty-aetherspace-vault-massive-files-affordably/"><u>[New] 2024 Approved  Thrifty Aetherspace Vault  Massive Files Affordably</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/nveiling-the-world-through-your-lens-how-to-become-a-professional-travel-vlogger-for-2024/"><u>[New] Unveiling the World Through Your Lens  How To Become A Professional Travel Vlogger for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-cutting-edge-tips-for-low-cost-youtube-sessions/"><u>[Updated] In 2024, Cutting-Edge Tips for Low-Cost YouTube Sessions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-getting-ahead-with-professional-itunes-capture-methods/"><u>[Updated] In 2024, Getting Ahead with Professional iTunes Capture Methods</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-insta-meets-tiktok-connectors-handbook-for-2024/"><u>[Updated] Insta Meets TikTok  Connector's Handbook for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-outperforming-vimeo-with-these-superior-alternatives/"><u>2024 Approved  Outperforming Vimeo with These Superior Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/data-synchronization-merging-in-win1011-systems/"><u>Data Synchronization: Merging in WIN10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-rdp-error-codes-in-modern-windows-systems/"><u>Decoding RDP Error Codes in Modern Windows Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/easy-to-follow-plan-for-5-effective-windows-11-audio-techniques/"><u>Easy-to-Follow Plan for 5 Effective Windows 11 Audio Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-requires-elevation-error-in-windows-11-devices/"><u>Eliminating the Requires Elevation Error in Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-admin-command-execution-without-hurdles/"><u>Ensuring Admin Command Execution Without Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-homescreen-activation-in-windows-11/"><u>Guide to Homescreen Activation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-game-bars-pc-doesnt-meet-hardware-requirements-for-captures-error-in-windows/"><u>How to Fix Game Bar’s “PC Doesn't Meet Hardware Requirements for Captures” Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-perform-common-windows-actions-with-shortcuts/"><u>How to Perform Common Windows Actions With Shortcuts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Honor 90 Lite? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-step-by-step-guide-to-professional-youtube-live-broadcast-with-wirecast/"><u>In 2024, Step-by-Step Guide to Professional YouTube Live Broadcast with WireCast</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-virtual-battlegrounds-top-7-fps-showdowns/"><u>In 2024, Virtual Battlegrounds  Top 7 FPS Showdowns</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Oppo A79 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-search-for-integrity-how-to-filter-out-fake-windows-apps/"><u>In Search for Integrity: How to Filter Out Fake Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11-integrating-advanced-run-command/"><u>Maximizing Windows 11: Integrating Advanced Run Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-speeds-in-windows-edge-win10win11/"><u>Overcoming Low Speeds in Windows Edge (Win10/Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-wireless-network-detection-on-windows-11/"><u>Reigniting Wireless Network Detection on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-your-pcs-overwatch-2-lossed-graphic-error/"><u>Resolving Your PC’s Overwatch 2 Lossed Graphic Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-integrate-onedrive-and-microsoft-id/"><u>Streamline Your Workflow: Integrate OneDrive & Microsoft ID</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-win-10-and-11-networks-with-telnet-easily/"><u>Tailoring Win 10 & 11 Networks with Telnet Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-better-sighting-of-tasks-on-windows-desktops/"><u>Techniques for Better Sighting of Tasks on Windows Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-windows-user-manual-for-speech-to-text-conversion/"><u>The Complete Window's User Manual for Speech-to-Text Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-maximize-laptop-lifespan-power-management-basics/"><u>Tips: Maximize Laptop Lifespan - Power Management Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-deletion-keys-in-windows/"><u>Troubleshooting Non-Functional Deletion Keys in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unlocking-youtube-success-elite-video-tagging-secrets/"><u>Unlocking YouTube Success  Elite Video Tagging Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-complexities-of-microsofts-error-0x80040610/"><u>Unraveling the Complexities of Microsoft's Error 0X80040610</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-system-accessibility-context-menu-enhancement-in-win1011/"><u>Upgrade System Accessibility: Context Menu Enhancement in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-active-windows-sound-services/"><u>Winning Back Active Windows Sound Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-lossed-rendering-support-in-overwatch-2/"><u>Winning Back Lossed Rendering Support in Overwatch 2</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>