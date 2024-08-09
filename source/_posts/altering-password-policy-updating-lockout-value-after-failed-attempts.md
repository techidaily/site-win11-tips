---
title: "Altering Password Policy: Updating Lockout Value After Failed Attempts"
date: 2024-08-08T10:57:11.274Z
updated: 2024-08-09T10:57:11.274Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering Password Policy: Updating Lockout Value After Failed Attempts"
excerpt: "This Article Describes Altering Password Policy: Updating Lockout Value After Failed Attempts"
keywords: Password Update Policy,Passwords Lockout Limit,Failed Login Safeguard,Account Security Protocol,Access Control Adjustment,Password Retry Settings,Unauthorized Attempts Response
thumbnail: https://thmb.techidaily.com/728942524bb364987d92cb465ba4b4e140c040cafc9935f89ba444801c2e0013.jpg
---

## Altering Password Policy: Updating Lockout Value After Failed Attempts

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-accelerating-the-playback-of-instagram-videos-tips/"><u>[New] In 2024, Accelerating the Playback of Instagram Videos (Tips)</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-essence-of-time-stretching-detailed-review-of-slomo-2e1924/"><u>[New] The Essence of Time Stretching  Detailed Review of SloMo, 2E1924</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-guide-clearing-up-youtube-watchlater-stored-list/"><u>[Updated] Guide  Clearing Up YouTube Watchlater Stored List</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-radio-dramaturgys-finest-works/"><u>[Updated] Radio Dramaturgy's Finest Works</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-apeak-recording-assessment-top-software-showdown/"><u>2024 Approved  Apeak Recording Assessment  Top Software Showdown</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-mac-users-path-to-professional-audio-with-audacity/"><u>2024 Approved  Mac Users' Path to Professional Audio with Audacity</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-unlocking-audio-excellence-in-ios-settings/"><u>2024 Approved  Unlocking Audio Excellence in iOS Settings</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveiling-secrets-to-amazing-photo-collages/"><u>2024 Approved  Unveiling Secrets to Amazing Photo Collages</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-poco-f5-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Poco F5 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sticky-context-menus-in-windows-11-edition/"><u>Addressing Sticky Context Menus in Windows 11 Edition</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/best-instagram-highlights-covers-apps-for-iphone-and-android/"><u>Best Instagram Highlights Covers Apps for iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitfort-fractured-stay-the-course-before-change/"><u>BitFort Fractured: Stay the Course Before Change</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-bandwidth-methods-for-assessing-your-networks-velocity/"><u>Boost Bandwidth: Methods for Assessing Your Network's Velocity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-molds-changing-the-winadmin-access-paradigm/"><u>Breaking Molds: Changing the WinAdmin Access Paradigm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-audio-amplification-feature/"><u>Cease Windows Audio Amplification Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compelling-case-for-continuing-with-windows-10-win10/"><u>Compelling Case for Continuing with Windows 10 (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confronting-memory-write-issues-in-windows/"><u>Confronting 'Memory Write' Issues in Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/content-connoisseurs-guide-outperforming-ai-writing-tools/"><u>Content Connoisseurs Guide: Outperforming AI Writing Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cutting-edge-plot-architects-domain/"><u>Cutting-Edge Plot Architects Domain</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-route-to-recent-windows-documents/"><u>Direct Route to Recent Windows Documents</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/efficient-methods-for-sharing-powerful-ppt-in-google-meet-sessions-for-2024/"><u>Efficient Methods for Sharing Powerful PPT in Google Meet Sessions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-printer-disconnection-in-windows-10-and-11-systems/"><u>Fast Track Printer Disconnection in Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-non-admin-account-permissions-in-windows/"><u>Fine-Tuning Non-Admin Account Permissions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-access-the-high-level-command-prompt-in-w11-os/"><u>How to Access the High-Level Command Prompt in W11 OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-printer-setup-error-driver-not-detected-by-os/"><u>HP Printer Setup Error: Driver Not Detected by OS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-redmi-a2-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi Redmi A2 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-selective-alarm-tones-optimal-websites-list/"><u>In 2024, Selective Alarm Tones  Optimal Websites List</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-vivo-v27-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-navigation-turn-off-acceleration-windows-1011/"><u>Mastering Mouse Navigation: Turn Off Acceleration Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-to-your-pcs-health-report-efficiently/"><u>Navigate to Your PC’s Health Report Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-startup-folder-in-windows-os-quickly/"><u>Navigating to Startup Folder in Windows OS Quickly</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-achieving-superior-sound-in-mp4-videos-a-comprehensive-guide/"><u>New Achieving Superior Sound in MP4 Videos A Comprehensive Guide</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-cadence-in-coding-envisioning-the-leading-luminaries-amongst-ai-music-architects/"><u>New In 2024, Cadence in Coding Envisioning the Leading Luminaries Amongst AI Music Architects</u></a></li>
<li><a href="https://extra-support.techidaily.com/premier-transcription-tools-for-silent-input-for-2024/"><u>Premier Transcription Tools for Silent Input for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pure-potential-upgrade-with-minimalist-win11/"><u>Pure Potential: Upgrade with Minimalist Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-outlook-fails-in-windows-systems/"><u>Resolve Outlook Fails in Windows Systems</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/rising-stars-in-digital-domain/"><u>Rising Stars in Digital Domain</u></a></li>
<li><a href="https://data-wizards.techidaily.com/snap-salvage-digital-camera-image-retrieval/"><u>Snap Salvage: Digital Camera Image Retrieval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reactivate-apps-hindered-by-qt-plugin-issue/"><u>Steps to Reactivate Apps Hindered by Qt Plugin Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-anomalies-dealing-with-anydesk-issues-in-windows/"><u>Streamlining Anomalies: Dealing with AnyDesk Issues in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-audio-alchemists-handbook-creating-custom-auditory-alerts-on-android-phones-for-2024/"><u>The Audio Alchemist's Handbook  Creating Custom Auditory Alerts on Android Phones for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-gateway-how-to-enter-os-settings/"><u>The Gateway: How to Enter OS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-wmp-failures/"><u>Understanding & Correcting WMP Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unplugging-problems-addressing-frequent-ps4-disconnection-in-pc/"><u>Unplugging Problems: Addressing Frequent PS4 Disconnection in PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mysteries-of-microsofts-copilot-key-in-windows-11/"><u>Unveiling the Mysteries of Microsoft's Copilot Key in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/web-accessibility-in-the-absence-of-built-in-browser/"><u>Web Accessibility in the Absence of Built-In Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-gaming-experience-boosted-by-solving-directdraw-errors/"><u>Windows 11 & 11 Gaming Experience Boosted by Solving DirectDraw Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-customization-top-20-settings-for-enhanced-performance/"><u>Windows 11 Customization: Top 20 Settings for Enhanced Performance</u></a></li>
</ul></div>
