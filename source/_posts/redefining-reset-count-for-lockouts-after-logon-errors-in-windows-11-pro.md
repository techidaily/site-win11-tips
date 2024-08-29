---
title: Redefining Reset Count for Lockouts After Logon Errors in Windows 11 Pro
date: 2024-08-28T01:13:45.991Z
updated: 2024-08-29T01:13:45.991Z
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
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-capturing-creativity-android-photography-guide/"><u>[New] Capturing Creativity  Android Photography Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-ideal-chat-and-meetup-tools-for-large-groups-for-2024/"><u>[New] Ideal Chat & Meetup Tools for Large Groups for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-decoding-tiktoks-profile-picture-phenomenon/"><u>[New] In 2024, Decoding TikTok's Profile Picture Phenomenon</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-tailoring-your-archive-strategy-on-instagram-for-2024/"><u>[New] Tailoring Your Archive Strategy on Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-user-testimonials-ios-vs-android-youtube-watching-habits/"><u>[New] User Testimonials  IOS vs Android YouTube Watching Habits</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-essential-first-steps-for-mastering-insta-chat-rooms/"><u>[Updated] In 2024, Essential First Steps for Mastering Insta Chat Rooms</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-making-a-mark-with-effective-youtube-channel-graphics/"><u>[Updated] Making a Mark with Effective YouTube Channel Graphics</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-mastering-instagram-top-borders-and-frames-for-perfect-photos-for-2024/"><u>[Updated] Mastering Instagram  Top Borders & Frames for Perfect Photos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-access-denied-saves-on-your-computer-windows/"><u>Clearing Up Access Denied Saves on Your Computer Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-setup-activating-telnet-on-modern-windows/"><u>Effortless Setup: Activating Telnet on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-usb-persistence-in-windows-11-three-steps/"><u>Enabling USB Persistence in Windows 11 - Three Steps</u></a></li>
<li><a href="https://program-issues.techidaily.com/enhance-cod-black-ops-4-performance-fixing-lag-spikes-and-improving-fps/"><u>Enhance COD Black Ops 4 Performance – Fixing Lag Spikes and Improving FPS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-journey-preventing-system-crash-during-dwarven-adventure/"><u>Ensuring Smooth Journey: Preventing System Crash During Dwarven Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-installing-the-outlook-preview-app/"><u>Essential Steps: Installing the Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-less-known-windows-11-custom-styles/"><u>Explore Less-Known Windows 11 Custom Styles</u></a></li>
<li><a href="https://some-guidance.techidaily.com/fixed-why-wont-my-laptop-speakers-work-and-what-to-do-about-it/"><u>Fixed! Why Won't My Laptop Speakers Work and What To Do About It</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/hasten-haste-in-videos-with-top-apps-android/"><u>Hasten Haste in Videos with Top Apps, Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-local-users-and-groups-management-in-windows-11-and-10-home/"><u>How to Enable Local Users and Groups Management in Windows 11 and 10 Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-windows-from-immediate-bios-access/"><u>How to Prevent Windows From Immediate BIOS Access</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-iphone-images-jpg-png-straightforward-conversion-guide/"><u>In 2024, IPhone Images (JPG, PNG) - Straightforward Conversion Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-windows-10-users-guide-to-microphones/"><u>In 2024, The Windows 10 User's Guide to Microphones</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-lava-blaze-2-pro-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Lava Blaze 2 Pro Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-imaging-made-sharp-again-essential-techniques-to-eliminate-blur/"><u>IPhone Imaging Made Sharp Again: Essential Techniques to Eliminate Blur</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-performance-resolving-windows-11-stuttering/"><u>Jumpstart Performance: Resolving Windows 11 Stuttering</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-ms-paint-on-windows-11-quick-guide/"><u>Launching MS Paint on Windows 11: Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-errors-interpreting-bsod-with-code-0x0e00000b/"><u>Mastering Windows Errors: Interpreting BSOD with Code 0X0e00000b</u></a></li>
<li><a href="https://extra-support.techidaily.com/mediamagic-8-edition-for-2024/"><u>MediaMagic 8 Edition for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/optimize-site-traffic-with-cookiebots-cutting-edge-tracking-solutions/"><u>Optimize Site Traffic with Cookiebot's Cutting-Edge Tracking Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-windows-11-challenge-instal-clipchamp-effortlessly/"><u>Overcome the Windows 11 Challenge: Instal ClipChamp Effortlessly</u></a></li>
<li><a href="https://fox-access.techidaily.com/peaceful-playback-practices-for-pcos-users-for-2024/"><u>Peaceful Playback Practices for PC/OS Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-in-compression-rectifying-checksum-errors-with-winrar/"><u>Precision in Compression: Rectifying Checksum Errors with WinRAR</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/precision-medicine-is-an-emerging-field-that-uses-genetic-information-to-tailor-treatments-for-cad-offering-more-effective-management-for-those-with-a-high-1/"><u>Precision Medicine Is an Emerging Field that Uses Genetic Information to Tailor Treatments for CAD, Offering More Effective Management for Those with a High Genetic Risk</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-system-call-failed-on-windows-1011/"><u>Quick Fixes: System Call Failed on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tricks-for-fixed-windows-11-power-issue/"><u>Quick Tricks for Fixed Windows 11 Power Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-responsive-brighness-fn-key-on-windows-11/"><u>Resolving Non-Responsive Brighness Fn Key on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-silent-acer-expert-tips-on-restoring-computer-speakers/"><u>Revive Your Silent Acer: Expert Tips on Restoring Computer Speakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-dolby-atmos-in-win-1011-systems/"><u>Setting Up Dolby Atmos in Win 10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-android-gaming-on-pc-win-11s-role-via-play/"><u>Simplifying Android Gaming on PC: Win 11'S Role via Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-solutions-zip-archives-in-image-files-win11/"><u>Sneaky Storage Solutions: ZIP Archives in Image Files (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-input-typingaids-secret/"><u>Speeding Up Input: TypingAid's Secret</u></a></li>
<li><a href="https://hardware-help.techidaily.com/speedy-downloads-thrustmaster-t150-driver-software-for-instant-setup/"><u>Speedy Downloads: Thrustmaster T150 Driver Software for Instant Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/square-up-your-windows-interface/"><u>Square Up Your Windows Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-hypervisor-errors-with-these-5-strategies/"><u>Stop HYPERVISOR Errors with These 5 Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-workflows-integrating-android-into-w11-ecosystem/"><u>Streamlining Workflows: Integrating Android Into W11 Ecosystem</u></a></li>
<li><a href="https://extra-information.techidaily.com/superior-sound-swap-technology-the-top-free-option-for-valorant-gamers/"><u>Superior Sound Swap Technology  The Top Free Option for Valorant Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-new-frontier-for-windows-ventures-past-11/"><u>The New Frontier for Windows: Ventures Past 11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-pioneer-bdr-xs06-portability-without-compromise-on-performance-in-high-quality-dvd-burning/"><u>The Pioneer BDR-XS06 - Portability Without Compromise on Performance in High-Quality DVD Burning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-the-intel-unison-app-that-wont-work-in-win11/"><u>Troubleshooting the Intel Unison App that Won't Work in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-your-pc-ramp-up-valorant-downloads-on-windows/"><u>Turbocharge Your PC: Ramp Up Valorant Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-your-journey-fixing-failed-discord-installation-on-pc/"><u>Unblocking Your Journey: Fixing Failed Discord Installation on PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/understanding-vr-headsets-an-overview/"><u>Understanding VR Headsets  An Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-online-life-securing-windows-network/"><u>Uninterrupted Online Life: Securing Windows Network</u></a></li>
<li><a href="https://win-amazing.techidaily.com/updated-hp-laserjet-pro-mfp-m428fdw-driver-for-modern-windows-systems-including-windows-11107/"><u>Updated HP LaserJet Pro MFP M428fdw Driver for Modern Windows Systems Including Windows 11/10/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-and-powershell-understanding-their-unique-features/"><u>Windows Terminal and PowerShell: Understanding Their Unique Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winpasswords-the-leading-7-gratis-generation-apps/"><u>WinPasswords: The Leading 7 Gratis Generation Apps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>