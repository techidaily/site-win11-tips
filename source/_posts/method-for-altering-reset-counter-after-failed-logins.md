---
title: Method for Altering Reset Counter After Failed Logins
date: 2024-08-16T02:38:39.292Z
updated: 2024-08-17T02:38:39.292Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Method for Altering Reset Counter After Failed Logins
excerpt: This Article Describes Method for Altering Reset Counter After Failed Logins
keywords: Change Reset Counter Login Fail,Modify Failed Logout Count,Increase Lockout Attempts Number,Adjust Failed Logins Retry Limit,Escalate Unsuccessful Login Trials,Recalibrate Login Failure Tally,Extend Reset Attempt Sequence
thumbnail: https://thmb.techidaily.com/a686c6eefaf9c4b50a452c73ac89f7229b66217691cf20f6f81f6b08cd386aeb.jpg
---

## Method for Altering Reset Counter After Failed Logins

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
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-average-profit-per-million-youtube-viewers/"><u>[New] 2024 Approved  Average Profit per Million YouTube Viewers</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-pinpointing-your-place-in-youtubes-varied-landscapes/"><u>[New] 2024 Approved  Pinpointing Your Place in YouTube's Varied Landscapes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-simplified-guide-to-iphone-display-recordings/"><u>[New] 2024 Approved  Simplified Guide to IPhone Display Recordings</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-dive-deep-into-tiktoks-voiceover-realm-for-2024/"><u>[New] Dive Deep Into TikTok's Voiceover Realm for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-ideal-video-capture-apps-for-educators-for-2024/"><u>[New] Ideal Video Capture Apps for Educators for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-designing-your-perfect-tiktok-outro/"><u>[New] In 2024, Designing Your Perfect TikTok Outro</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-popcorn-projections-thorough-review-of-film-snack-recorder-for-2024/"><u>[New] Popcorn Projections  Thorough Review of Film Snack Recorder for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-inserting-dates-in-digital-pictures/"><u>[New] Step-by-Step  Inserting Dates in Digital Pictures</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximizing-revenue-how-to-monetize-youtube-channel-on-mobile/"><u>[Updated] Maximizing Revenue  How to Monetize YouTube Channel on Mobile</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-skys-best-hd-pics-top-website-guide/"><u>[Updated] Sky's Best HD Pics  Top Website Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-step-by-step-audacity-audio-recording-on-macos-for-2024/"><u>[Updated] Step-by-Step  Audacity Audio Recording on MacOS for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-snip-save-and-share-high-quality-tamil-ringtones-easily/"><u>2024 Approved  How to Snip, Save and Share High-Quality Tamil Ringtones Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-net-runtime-requirement-hurdle/"><u>Avoiding Windows' .NET Runtime Requirement Hurdle</u></a></li>
<li><a href="https://facebook.techidaily.com/bridging-the-gap-between-media-and-authors-with-facebooks-5-million-financing/"><u>Bridging the Gap Between Media and Authors with Facebook's $5 Million Financing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-unresponsive-wired-gaming-accessories/"><u>Cure for Unresponsive Wired Gaming Accessories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-overcoming-steam-auth-problems-with-rust-on-windows/"><u>Detailed Guide to Overcoming Steam Auth Problems with Rust on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-6-computer-utilization-monitors-on-pcs/"><u>Discover the Top 6 Computer Utilization Monitors on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-alteration-of-nat-types-in-windows-operating-systems/"><u>Effective Alteration of NAT Types in Windows Operating Systems</u></a></li>
<li><a href="https://driver-install.techidaily.com/efficiency-unleashed-startech-drives-fix-for-winxp-11-os/"><u>Efficiency Unleashed: StarTech Drives Fix for WINXP-11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-persistence-of-user-defined-volume-mixer/"><u>Ensuring Persistence of User-Defined Volume Mixer</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-18-cameras-for-high-quality-online-sharing/"><u>Essential 18 Cameras for High-Quality Online Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-3-innovative-ways-for-windows-hardware-id-access/"><u>Exploring 3 Innovative Ways for Windows Hardware ID Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gearing-up-with-best-laptops-from-ifa-2023/"><u>Gearing Up with Best Laptops From IFA 2023</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-samsung-galaxy-xcover-7-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Samsung Galaxy XCover 7 Phone | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/harnessing-advanced-conversation-integrate-nvidias-rtx-chatbot-into-your-pc-experience/"><u>Harnessing Advanced Conversation: Integrate NVIDIA's RTX Chatbot Into Your PC Experience</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-honor-90-pro-by-fonelab-android-recover-video/"><u>How to restore wiped videos on Honor 90 Pro</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-realme-gt-3-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Realme GT 3 for Free? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-effortlessly-enhance-your-tiktok-aesthetic-guide-inside/"><u>In 2024, Effortlessly Enhance Your TikTok Aesthetic  Guide Inside</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-elevate-video-aesthetics-to-meet-instagram-standards/"><u>In 2024, Elevate Video Aesthetics to Meet Instagram Standards</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-from-free-posts-to-fiscal-success-fb-pages-profit-playbook/"><u>In 2024, From Free Posts to Fiscal Success  FB Pages Profit Playbook</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-can-i-unlock-my-apple-iphone-11-pro-after-forgetting-my-pin-code-drfone-by-drfone-ios/"><u>In 2024, How Can I Unlock My Apple iPhone 11 Pro After Forgetting my PIN Code? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-xiaomi-redmi-note-13-proplus-5g-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Xiaomi Redmi Note 13 Pro+ 5G online without jailbreak</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-soundsnatcher-recorder-software-overview/"><u>In 2024, SoundSnatcher Recorder Software Overview</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-zoom-video-transcoding-3-proven-success-techniques/"><u>In 2024, Zoom Video Transcoding  3 Proven Success Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-windows-patch-identification/"><u>Insights Into Window's Patch Identification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-internal-error-in-windows-11-remote/"><u>Mastering the Art of Fixing Internal Error in Windows 11 Remote</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win1011-recycle-bin-repair-strategies/"><u>Mastering WIN10/11 Recycle Bin Repair Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-ease-to-windows-11s-security-management/"><u>Navigate with Ease to Windows 11’S Security Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-mspcm-interface-on-windows-11-easily/"><u>Navigating the MSPCM Interface on Windows 11 Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-limited-access-install-troubleshooting-on-win-1110/"><u>Navigating Through Limited Access Install Troubleshooting on Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-connectivity-woes-in-w11/"><u>Navigating Through Steam Connectivity Woes in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-screen-guide-to-windows-11-gpus/"><u>Optimize Your Screen: Guide to Windows 11 GPUs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-inactivity-in-new-os-sleep-mode/"><u>Overcoming Device Inactivity in New OS Sleep Mode</u></a></li>
<li><a href="https://vp-tips.techidaily.com/pro-tips-chromebooks-finest-pencil-based-software-for-2024/"><u>Pro Tips  Chromebook's Finest Pencil-Based Software for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/prolific-productions-top-10-text-techniques-to-captivate-viewers/"><u>Prolific Productions  Top 10 Text Techniques to Captivate Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11s-file-order-preferences/"><u>Realigning Windows 11'S File Order Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-file-explorer-on-stable-windows-11/"><u>Regain Control Over File Explorer on Stable Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-over-windows-snipping-commands/"><u>Regaining Control Over Windows' Snipping Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-missing-dxgidll-streamline-your-win11/"><u>Reinstate Missing Dxgi.dll, Streamline Your Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-the-backbone-softwaredistribution-and-catroot2-on-ws11/"><u>Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-itunes-operational-status-on-your-pc/"><u>Restoring iTunes Operational Status on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stuck-lock-screen-delay-on-pcs/"><u>Solutions for Stuck Lock Screen Delay on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-walkthrough-switching-nat-type-on-wins-10-and-11/"><u>Step-By-Step Walkthrough: Switching NAT Type on Wins 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-dxgierrordevicehunk-on-windows-11/"><u>Steps to Tackle DXGI_ERROR_DEVICE_HUNK on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-permanent-trash-setup-for-efficient-file-disposal-on-pcs/"><u>Tailored Permanent Trash Setup for Efficient File Disposal on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-future-of-windows-interface-winbubbles-8-innovations/"><u>The Future of Windows Interface: WinBubble's 8 Innovations</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-10-explanations-for-auto-dimming-display-on-iphones/"><u>Top 10 Explanations for Auto-Dimming Display on iPhones</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-manfrotto-befree-aluminum-tripod-unmatched-quality/"><u>Ultimate Manfrotto Befree Aluminum Tripod: Unmatched Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-error-0xc00d36b4-sound-fixes/"><u>Unraveling Windows Error 0XC00D36B4: Sound Fixes</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveiling-ace-video-capturers-guide/"><u>Unveiling Ace Video Capturers Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-wipe-old-windows-protection-markers-from-microsofts-record/"><u>Ways to Wipe Old Windows Protection Markers From Microsoft's Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-wintoys-a-short-guide-to-a-powerful-windows-tool/"><u>What Is Wintoys? A Short Guide to a Powerful Windows Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-lsass-component-resolution-a-user-friendly-guide/"><u>Win LSass Component Resolution: A User-Friendly Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-accessing-screen-capture-utility-quickly/"><u>Windows 11: Accessing Screen Capture Utility Quickly</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>