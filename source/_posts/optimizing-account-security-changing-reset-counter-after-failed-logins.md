---
title: "Optimizing Account Security: Changing Reset Counter After Failed Logins"
date: 2024-08-16T02:22:46.832Z
updated: 2024-08-17T02:22:46.832Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Account Security: Changing Reset Counter After Failed Logins"
excerpt: "This Article Describes Optimizing Account Security: Changing Reset Counter After Failed Logins"
keywords: Secure Passwords Update,Prevent Reset Abuse,Improve Login Safety,Strengthen Access Controls,Enhance Account Protection,Reduce Failed Attempt Risks,Optimize Security Measures
thumbnail: https://thmb.techidaily.com/6a82b15c3b5908dade20c57e5528354889aa2d43fb699583edd3d2db4662000a.jpg
---

## Optimizing Account Security: Changing Reset Counter After Failed Logins

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/nhance-your-music-library-top-6-free-ios-apps-for-audio-conversion/"><u>[New] Enhance Your Music Library  Top 6 Free iOS Apps for Audio Conversion</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-the-invisible-recorder-how-to-save-online-music-streams/"><u>[New] In 2024, The Invisible Recorder  How to Save Online Music Streams</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-total-domination-a-ranking-of-the-7-best-war-based-titans-for-2024/"><u>[New] Total Domination  A Ranking of the 7 Best War-Based Titans for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-first-contact-with-freight-elevating-the-opening-moment/"><u>[Updated] First Contact with Freight  Elevating the Opening Moment</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-navigating-network-settings-in-mixer-macos-for-2024/"><u>[Updated] Navigating Network Settings in Mixer macOS for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-superfast-fb-downloader-mp4-files-in-minutes/"><u>[Updated] SuperFast FB Downloader  MP4 Files in Minutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-fixes-for-fbm-not-working-here/"><u>10 Essential Fixes for FBM Not Working Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-tactics-for-control-panel-entry/"><u>10 Essential Tactics for Control Panel Entry</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-oneplus-11r-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-tips-to-fix-windows-system-restore/"><u>13 Tips to Fix Windows System Restore</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-aligning-objectives-brands-and-youtube-collaborative-moves/"><u>2024 Approved  Aligning Objectives  Brands and YouTube Collaborative Moves</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-blur-proof-iphones-achieving-flawless-budget-friendly-edits/"><u>2024 Approved  Blur-Proof iPhones  Achieving Flawless, Budget-Friendly Edits</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-elevating-experience-with-the-right-music-for-vids/"><u>2024 Approved  Elevating Experience with the Right Music for Vids</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-inside-look-top-10-screenshot-tools-on-macos-platform/"><u>2024 Approved  Inside Look  Top 10 Screenshot Tools on macOS Platform</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-obspluszoom-creating-a-flawless-production-workflow/"><u>2024 Approved  OBS+Zoom  Creating a Flawless Production Workflow</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-podcast-summary-genius-guidance-and-examples/"><u>2024 Approved  Podcast Summary Genius  Guidance & Examples</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-fabric-of-future-cutting-edge-vr-technology/"><u>2024 Approved  The Fabric of Future  Cutting-Edge VR Technology</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-top-11-best-dji-phantom-4-accessories-to-buy/"><u>2024 Approved  Top 11 Best DJI Phantom 4 Accessories to Buy</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-unveiling-the-best-strategies-how-to-boost-engagement-and-growth-on-youtube/"><u>2024 Approved  Unveiling the Best Strategies  How to Boost Engagement and Growth on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-disable-usb-selective-suspend-in-windows-11/"><u>3 Quick Ways to Disable USB Selective Suspend in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-10-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-make-windows-look-like-macos/"><u>5 Ways to Make Windows Look Like macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-checksum-error-in-winrar/"><u>6 Ways to Fix the Checksum Error in WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-potential-exciting-enhancements-from-w11-22h2-moment/"><u>7 Potential Exciting Enhancements From W11 22H2 Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-slick-techniques-to-launch-iis-manager/"><u>8 Slick Techniques to Launch IIS Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-cookie-cutter-guide-to-revamping-your-pc-with-a-fresh-os/"><u>A Compre Cookie-Cutter Guide to Revamping Your PC with a Fresh OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-preparing-your-pc-before-win-upgrade/"><u>A Step-by-Step Guide to Preparing Your PC Before Win Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-operations-using-windows-task-scheduler/"><u>Accelerate System Operations Using Windows Task Scheduler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-network-configurations-in-win11/"><u>Accessing Network Configurations in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-and-configure-powershell-execution-policies-securely/"><u>Activate & Configure PowerShell Execution Policies Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-nighttime-display-in-notepad-windows-11-edition/"><u>Activating Nighttime Display in Notepad Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-service-did-not-respond-issue-in-windows/"><u>Addressing Service Did Not Respond Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-called-fails-on-windows-1011/"><u>Addressing System Called Fails on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjustment-assistants-best-windows-utilities-for-date-tweaking/"><u>Adjustment Assistants: Best Windows Utilities for Date Tweaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-assistants-impact-on-windows-11-experience/"><u>AI Assistant's Impact on Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aligning-chrome-and-system-time-windows-sync-tips/"><u>Aligning Chrome and System Time (Windows Sync Tips)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplified-audio-top-4-applications-to-surpass-windows-100-threshold/"><u>Amplified Audio: Top 4 Applications to Surpass Windows’ 100%% Threshold</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-outputs-with-savvy-techniques/"><u>Amplify Windows 11 Outputs with Savvy Techniques</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-agni-2-5g-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from Agni 2 5G</u></a></li>
<li><a href="https://article-posts.techidaily.com/androids-secret-weapon-for-stunning-time-lagged-footage/"><u>Android's Secret Weapon for Stunning Time-Lagged Footage</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-samsung-galaxy-a34-5g-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Samsung Galaxy A34 5G? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificial-intelligence-windows-future-trailblazer/"><u>Artificial Intelligence: Windows' Future Trailblazer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-space-allocation-in-windows-applications/"><u>Assessing Space Allocation in Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automated-awareness-quick-open-of-windows-and-sticky-notebooks/"><u>Automated Awareness: Quick Open of Windows and Sticky Notebooks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-wifi-network-deletion-in-win-11/"><u>Automating Wifi Network Deletion in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-trouble-fixing-corrupted-recycle-bin-on-win1011/"><u>Avoid the Trouble: Fixing Corrupted Recycle Bin on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-a-marooned-experience-with-xbox-in-windows-11/"><u>Avoiding a Marooned Experience with Xbox in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-elusive-obs-recording-glitches-on-windows-operating-system/"><u>Beating Elusive OBS Recording Glitches on Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-fixing-frequent-apex-legends-crashes-on-windows-11/"><u>Beating the Bug: Fixing Frequent Apex Legends Crashes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-efficient-w11-microphone-use/"><u>Beginner's Guide: Efficient W11 Microphone Use</u></a></li>
<li><a href="https://tech-revival.techidaily.com/best-practices-for-exporting-and-backing-up-your-chat-data-with-chatgpt/"><u>Best Practices for Exporting and Backing Up Your Chat Data with ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-kept-secrets-eclectic-windows-11-styles/"><u>Best-Kept Secrets: Eclectic Windows 11 Styles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlocker-free-windows-4-effective-security-measures/"><u>BitLocker-Free Windows: 4 Effective Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprint-to-rule-winos-apps-browsers/"><u>Blueprint to Rule WinOS Apps, Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-code-development-top-wls-2-methods-on-latest-oses/"><u>Boost Your Code Development: Top WLS 2 Methods on Latest OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-performance-with-advanced-virtual-memory-management-techniques/"><u>Boosting System Performance with Advanced Virtual Memory Management Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719348732386-cant-capture-sound-in-obs-on-win-11-solve-it-now/"><u>Can't Capture Sound in OBS on Win 11? Solve It Now!</u></a></li>
<li><a href="https://extra-information.techidaily.com/capture-creativity-speedy-drawing-techniques-for-windows-photo-editor/"><u>Capture Creativity  Speedy Drawing Techniques for Windows Photo Editor</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/digital-nightmare-drawer/"><u>Digital Nightmare Drawer</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-poco-m6-5gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Poco M6 5Gwith/without a PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-itel-frp-by-drfone-android/"><u>How Can We Bypass Itel FRP?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-8-plus-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 8 Plus To Other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-annual-reveal-best-free-luts-with-direct-access-links/"><u>In 2024, Annual Reveal - Best FREE LUTs with Direct Access Links</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-decoding-music-copyright-rules-in-the-world-of-instagram/"><u>In 2024, Decoding Music Copyright Rules in the World of Instagram</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-investigating-whether-sns-hdr-offers-superior-ux/"><u>In 2024, Investigating Whether SNS HDR Offers Superior UX</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-streamlining-the-recording-process-in-virtual-gatherings/"><u>In 2024, Streamlining the Recording Process in Virtual Gatherings</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-your-channels-potential-the-cost-analysis/"><u>In 2024, Unlocking Your Channel's Potential  The Cost Analysis</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/learn-and-master-io-screen-recording-today-for-2024/"><u>Learn and Master IO Screen Recording Today for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/1723063547995-multicast-addresses-are-identified-by-the-prefix-ff008/"><u>Multicast Addresses Are Identified by the Prefix FF00::/8.</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-views-hourlys-youtube-hit-list/"><u>Rapid Views  Hourly's YouTube Hit List</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-list-of-20-magic-words-for-marketing/"><u>The Ultimate List of 20 Magic Words for Marketing</u></a></li>
<li><a href="https://driver-install.techidaily.com/tp-links-usb-wi-fi-driver-fast-download-for-pc-users/"><u>TP Link's USB Wi-Fi Driver: Fast Download for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266023156-zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution.</u></a></li>
</ul></div>
