---
title: Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
date: 2024-08-16T02:15:06.890Z
updated: 2024-08-17T02:15:06.890Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
excerpt: This Article Describes Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
keywords: Windows 11 Login Limits,Win11 Password Failures,Reset Attempt Control,Secure Login Windows 11,Incorrect Logins Management,Windows 11 Access Restrictions,Account Lockout Thresholds
thumbnail: https://thmb.techidaily.com/5137476410d550ff3157a9e8b8c303fc95e61e87d44f30246bb809e8ce4eedda.jpg
---

## Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
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
<li><a href="https://facebook-videos.techidaily.com/new-automatic-youtube-playback-made-simple-for-social-networking-sites-like-facebook-for-2024/"><u>[New] Automatic YouTube Playback Made Simple for Social Networking Sites Like Facebook for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-broadcast-platform-showdown-obs-or-twitch-studio-for-2024/"><u>[New] Broadcast Platform Showdown  OBS or Twitch Studio for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-clear-views-combating-fog-in-gopro-photos-for-2024/"><u>[New] Clear Views  Combating Fog in GoPro Photos for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-improve-browser-performance-fb-vids-chrome/"><u>[New] Improve Browser Performance  FB Vids, Chrome</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-recollect-rivals-mobile-battlegrounds-in-samsungs/"><u>[New] Recollect Rivals  Mobile Battlegrounds in Samsungs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-unlock-device-agnostic-techniques-for-professional-filming-for-2024/"><u>[New] Unlock Device-Agnostic Techniques for Professional Filming for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-free-webm-players/"><u>[Updated] Best Free WebM Players</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-brand-your-youtube-channel-to-get-more-subscribers/"><u>[Updated] In 2024, How to Brand Your YouTube Channel to Get More Subscribers</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-how-to-proficiently-use-screen-share-in-discord-channels/"><u>[Updated] In 2024, How to Proficiently Use Screen Share in Discord Channels</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-leading-intro-apps-for-budding-creators-iphoneandroid/"><u>[Updated] In 2024, Leading Intro Apps for Budding Creators (iPhone/Android)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-essential-manual-to-earning-from-youtube-videos/"><u>[Updated] The Essential Manual to Earning From YouTube Videos</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unleash-creativity-ranked-free-drawing-apps-for-mac/"><u>[Updated] Unleash Creativity  Ranked FREE Drawing Apps for Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-10plus-proven-techniques-for-selecting-the-finest-cricket-broadcasts/"><u>[Updated] Unveiling 10+ Proven Techniques for Selecting the Finest Cricket Broadcasts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hps-visionary-color-display-dissecting-the-z32x-monitor/"><u>2024 Approved  HP’s Visionary Color Display  Dissecting the Z32X Monitor</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-joyous-film-loader-assessment/"><u>2024 Approved  Joyous Film Loader Assessment</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-unique-outro-music-files-at-your-fingertips-free/"><u>2024 Approved  Unique Outro Music Files at Your Fingertips - Free</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-infinix-smart-7-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Infinix Smart 7 to Roku | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-realme-12-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-tecno-spark-20c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-a-reappearing-deleted-file-or-folder-on-windows/"><u>8 Ways to Fix a Reappearing Deleted File or Folder on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-harmony-with-googles-cross-platform-tool/"><u>Achieving Harmony with Google's Cross-Platform Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-fun-integrating-games-into-windows-11-through-google-play/"><u>Android Fun: Integrating Games Into Windows 11 Through Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11s-missing-wi-fi-functionality/"><u>Boosting Windows 11'S Missing Wi-Fi Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-your-pc-health-top-13-tactics-to-restore-windows/"><u>Boosting Your PC Health: Top 13 Tactics to Restore Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-verifying-glass-cases-in-windows-installation/"><u>Break Free From Verifying Glass Cases in Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-11s-spotify-link-barriers/"><u>Breaking Down Windows 11'S Spotify Link Barriers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-into-high-privilege-windows-command-center/"><u>Breaking Into High-Privilege Windows Command Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-code-how-to-reactivate-memory-feature-in-win11/"><u>Breaking the Code: How to Reactivate Memory Feature in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-firewall-gap-enable-chrome-networking-in-windows-os/"><u>Bridge Firewall Gap: Enable Chrome Networking in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-in-windows-11-sticky-notebook-coordination/"><u>Bridging Gaps in Window's 11 Sticky Notebook Coordination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-between-windows-and-photoshop-open-up-delays/"><u>Bridging the Gap Between Windows and PhotoShop Open-Up Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-more-to-the-table-reimagining-windows-11s-widget-framework/"><u>Bringing More to the Table: Reimagining Windows 11'S Widget Framework</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-blackout-blues-efficient-strategies-to-unlock-windows-sites/"><u>Browser Blackout Blues: Efficient Strategies to Unlock Windows Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-download-block-with-opera-tricks/"><u>Bypass Windows Download Block with Opera Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-default-alter-clock-region-on-the-fly/"><u>Bypass Windows' Default: Alter Clock Region On-the-Fly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-access-denied-saving-problems-on-windows/"><u>Bypassing Access Denied Saving Problems on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-audacity-sound-error-in-windows-10-and-11/"><u>Bypassing Audacity Sound Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-microsoft-store-lockdown-on-windows-11/"><u>Bypassing Microsoft Store Lockdown on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-gloom-bringing-back-daylight-in-windows/"><u>Bypassing The Gloom: Bringing Back Daylight in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-not-found-window-error/"><u>Bypassing the Not Found Window Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-user-account-prompts-in-windows/"><u>Bypassing User Account Prompts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-permission-issues-easily/"><u>Bypassing Windows Permission Issues Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-select-or-highlight-text-in-a-pdf-on-windows-heres-how-to-fix-it/"><u>Can't Select or Highlight Text in a PDF on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capture-windows-like-a-pro-snip-tool-vs-prtsc-advantages/"><u>Capture Windows Like a Pro: Snip Tool Vs. PrtSc Advantages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-sound-in-win-11-step-by-step/"><u>Capturing Sound in Win 11 Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-map-navigation-in-new-windows-11/"><u>Character Map Navigation in New Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-map-unlocked-in-windows-11-edition/"><u>Character Map Unlocked in Windows 11 Edition</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-geforce-rtx-ti-drivers-now-compatible-with-win-11-8-and-7-systems/"><u>Get the Latest GeForce RTX 지판 Ti Drivers Now - Compatible with Win 11, 8 & 7 Systems</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-vivo-v30-pro-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Vivo V30 Pro Phones with/without a PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-samsung-galaxy-z-fold-5-device-by-drfone-android/"><u>In 2024, Mastering Android Device Manager The Ultimate Guide to Unlocking Your Samsung Galaxy Z Fold 5 Device</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-maximizing-twitter-budget-efficiency-in-ad-spends/"><u>In 2024, Maximizing Twitter Budget Efficiency in Ad Spends</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unleashing-clarity-the-ultimate-video-enhancer-22-techniques/"><u>In 2024, Unleashing Clarity  The Ultimate Video Enhancer 2.2 Techniques</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-motorola-edge-40-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Motorola Edge 40 Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360477145-reigniting-your-computers-print-functionality-with-effective-wwin-solutions/"><u>Reigniting Your Computer's Print Functionality with Effective WWin Solutions</u></a></li>
<li><a href="https://screen-capture.techidaily.com/seamless-techniques-for-effective-iphone-screen-captures/"><u>Seamless Techniques for Effective Iphone Screen Captures</u></a></li>
<li><a href="https://tech-haven.techidaily.com/simple-steps-converting-dall-e-3s-webp-files-to-pngjpg-format/"><u>Simple Steps: Converting DALL-E 3'S WebP Files to PNG/JPG Format</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-the-best-of-the-best-16-free-movie-makers-no-experience-needed/"><u>Updated 2024 Approved The Best of the Best 16 Free Movie Makers (No Experience Needed)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376942389-windows-gptmimicry-a-costless-local-edition-via-gpt4all/"><u>Windows GPTMimicry: A Costless Local Edition via GPT4All.</u></a></li>
</ul></div>
