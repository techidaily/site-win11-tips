---
title: "Alteration of Login Failure Counter: Windows 11 User Guide"
date: 2024-08-08T10:54:58.326Z
updated: 2024-08-09T10:54:58.326Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Alteration of Login Failure Counter: Windows 11 User Guide"
excerpt: "This Article Describes Alteration of Login Failure Counter: Windows 11 User Guide"
keywords: Win11 Login Troubleshooting,11 PC Login Fix Guide,11 User Error Logout Help,Correcting Login Failures in Windows 11,Enhancing Login Success Rate Windows 11,Resetting Failed Logins on Win11,Overcoming 11 Login Issues Guide
thumbnail: https://thmb.techidaily.com/6c7b51dcfdae2a8da726c75853a324eb9a3939b33880d7b4a364119150ff2caf.jpg
---

## Alteration of Login Failure Counter: Windows 11 User Guide

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-instagram-utilizing-search-to-expand-your-filters/"><u>[New] 2024 Approved  Mastering Instagram  Utilizing Search to Expand Your Filters</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-enhancing-comments-with-emojis-on-youtube/"><u>[New] In 2024, Enhancing Comments with Emojis on YouTube</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/everaging-creator-funding-in-youtube-shorts-for-2024/"><u>[New] Leveraging Creator Funding in YouTube Shorts for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-mastering-access-the-journey-through-free-visual-resources/"><u>[New] Mastering Access  The Journey Through Free Visual Resources</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-perfecting-music-in-instagram-videos-and-stories/"><u>[New] Perfecting Music in Instagram Videos & Stories</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-discover-facebooks-latest-transformations/"><u>[Updated] 2024 Approved  Discover Facebook's Latest Transformations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-harmonizing-highlights-how-to-embed-songs-on-instagram-stories/"><u>[Updated] 2024 Approved  Harmonizing Highlights  How to Embed Songs on Instagram Stories</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-5-ways-to-record-webinar-for-free-for-2024/"><u>[Updated] 5 Ways to Record Webinar for Free for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-stand-out-and-thrive-strategies-for-staff-recognition-at-vimeo/"><u>[Updated] In 2024, Stand Out and Thrive  Strategies for Staff Recognition at Vimeo</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-to-the-best-10-affordable-online-channels-for-graphic-design/"><u>[Updated] Navigating to the Best 10 Affordable Online Channels for Graphic Design</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-screenshots-to-art-the-8-best-photo-collage-tools/"><u>2024 Approved  From Screenshots to Art  The 8 Best Photo Collage Tools</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-harmonize-body-and-mind-through-these-top-10-yogis-videos/"><u>2024 Approved  Harmonize Body and Mind Through These Top 10 Yogis' Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-iphone-shutterbugs-tips-for-better-images/"><u>2024 Approved  IPhone Shutterbugs  Tips for Better Images</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-complete-playbook-for-broadcasting-spherical-content-on-youtube/"><u>2024 Approved  The Complete Playbook for Broadcasting Spherical Content on Youtube</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-full-time-employees-guide-to-video-content-success/"><u>2024 Approved  The Full-Time Employee's Guide to Video Content Success</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/6-ways-to-make-chatgpt-your-perfect-dungeon-master-assistant/"><u>6 Ways to Make ChatGPT Your Perfect Dungeon Master Assistant</u></a></li>
<li><a href="https://tech-haven.techidaily.com/artificial-intelligence-reimagining-daily-homemaking/"><u>Artificial Intelligence: Reimagining Daily Homemaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-net-runtime-requirement-hurdle/"><u>Avoiding Windows' .NET Runtime Requirement Hurdle</u></a></li>
<li><a href="https://facebook.techidaily.com/buzz-in-online-sphere-deciphering-vague-publicity/"><u>Buzz in Online Sphere: Deciphering Vague Publicity</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/celebrity-fleeting-frame-study/"><u>Celebrity Fleeting Frame Study</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-unresponsive-wired-gaming-accessories/"><u>Cure for Unresponsive Wired Gaming Accessories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-overcoming-steam-auth-problems-with-rust-on-windows/"><u>Detailed Guide to Overcoming Steam Auth Problems with Rust on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-6-computer-utilization-monitors-on-pcs/"><u>Discover the Top 6 Computer Utilization Monitors on PCs</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-oneplus-nord-3-5g-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your OnePlus Nord 3 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-alteration-of-nat-types-in-windows-operating-systems/"><u>Effective Alteration of NAT Types in Windows Operating Systems</u></a></li>
<li><a href="https://fox-access.techidaily.com/enhance-every-shot-with-free-top-image-boosters/"><u>Enhance Every Shot with Free, Top Image Boosters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-persistence-of-user-defined-volume-mixer/"><u>Ensuring Persistence of User-Defined Volume Mixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-3-innovative-ways-for-windows-hardware-id-access/"><u>Exploring 3 Innovative Ways for Windows Hardware ID Access</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-simple-to-stunning-infusing-life-into-text-on-instagram/"><u>From Simple to Stunning  Infusing Life Into Text on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gearing-up-with-best-laptops-from-ifa-2023/"><u>Gearing Up with Best Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cleanse-your-computer-of-previous-security-audits/"><u>How to Cleanse Your Computer of Previous Security Audits</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-oneplus-ace-3-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change OnePlus Ace 3 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-samsung-galaxy-a05-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Samsung Galaxy A05</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-windows-patch-identification/"><u>Insights Into Window's Patch Identification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-internal-error-in-windows-11-remote/"><u>Mastering the Art of Fixing Internal Error in Windows 11 Remote</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win1011-recycle-bin-repair-strategies/"><u>Mastering WIN10/11 Recycle Bin Repair Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-ease-to-windows-11s-security-management/"><u>Navigate with Ease to Windows 11’S Security Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-mspcm-interface-on-windows-11-easily/"><u>Navigating the MSPCM Interface on Windows 11 Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-limited-access-install-troubleshooting-on-win-1110/"><u>Navigating Through Limited Access Install Troubleshooting on Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-connectivity-woes-in-w11/"><u>Navigating Through Steam Connectivity Woes in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-screen-guide-to-windows-11-gpus/"><u>Optimize Your Screen: Guide to Windows 11 GPUs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-inactivity-in-new-os-sleep-mode/"><u>Overcoming Device Inactivity in New OS Sleep Mode</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/quick-tips-for-transcribing-audio-to-text-using-microsoft-word/"><u>Quick Tips for Transcribing Audio to Text Using Microsoft Word</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11s-file-order-preferences/"><u>Realigning Windows 11'S File Order Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-file-explorer-on-stable-windows-11/"><u>Regain Control Over File Explorer on Stable Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-over-windows-snipping-commands/"><u>Regaining Control Over Windows' Snipping Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-missing-dxgidll-streamline-your-win11/"><u>Reinstate Missing Dxgi.dll, Streamline Your Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-the-backbone-softwaredistribution-and-catroot2-on-ws11/"><u>Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-itunes-operational-status-on-your-pc/"><u>Restoring iTunes Operational Status on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stuck-lock-screen-delay-on-pcs/"><u>Solutions for Stuck Lock Screen Delay on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-connection-attempted-bluetooth-hiccup-on-pcs/"><u>Solving 'Connection Attempted' Bluetooth Hiccup on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-walkthrough-switching-nat-type-on-wins-10-and-11/"><u>Step-By-Step Walkthrough: Switching NAT Type on Wins 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-dxgierrordevicehunk-on-windows-11/"><u>Steps to Tackle DXGI_ERROR_DEVICE_HUNK on Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/syncing-songs-safely-with-insta-rules-for-2024/"><u>Syncing Songs Safely with Insta Rules for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-permanent-trash-setup-for-efficient-file-disposal-on-pcs/"><u>Tailored Permanent Trash Setup for Efficient File Disposal on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-future-of-windows-interface-winbubbles-8-innovations/"><u>The Future of Windows Interface: WinBubble's 8 Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-error-0xc00d36b4-sound-fixes/"><u>Unraveling Windows Error 0XC00D36B4: Sound Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-wipe-old-windows-protection-markers-from-microsofts-record/"><u>Ways to Wipe Old Windows Protection Markers From Microsoft's Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-wintoys-a-short-guide-to-a-powerful-windows-tool/"><u>What Is Wintoys? A Short Guide to a Powerful Windows Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-lsass-component-resolution-a-user-friendly-guide/"><u>Win LSass Component Resolution: A User-Friendly Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-accessing-screen-capture-utility-quickly/"><u>Windows 11: Accessing Screen Capture Utility Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-unwanted-scroll-events/"><u>Winning Against Unwanted Scroll Events</u></a></li>
</ul></div>
