---
title: Manipulating Login Retry Wait Timepost-Failed Attempts
date: 2024-08-16T01:48:56.581Z
updated: 2024-08-17T01:48:56.581Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Manipulating Login Retry Wait Timepost-Failed Attempts
excerpt: This Article Describes Manipulating Login Retry Wait Timepost-Failed Attempts
keywords: Login Retry Limits,Failed Attempt Logins,Reboot Login Delay,Account Lockout Strategy,Post-Failure Wait Time,Throttle Login Retries,Manage Failed Login Pause
thumbnail: https://thmb.techidaily.com/9f7aaa7e93668c79f588e2bdc07bd0199fd9952e273ede775f53891cdecae42d.jpg
---

## Manipulating Login Retry Wait Timepost-Failed Attempts

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-crafting-the-perfect-youtube-channel-url-a-quick-guide/"><u>[New] 2024 Approved  Crafting the Perfect YouTube Channel Url  A Quick Guide</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-step-by-step-guide-to-master-gratuitous-timer-software/"><u>[New] 2024 Approved  Step-by-Step Guide to Master Gratuitous Timer Software</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-beat-matching-visuals-and-audio-on-facebook-platform/"><u>[New] Beat-Matching Visuals & Audio on Facebook Platform</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-enhance-your-gopro-footage-top-5-sd-cards-hero-8-7-for-2024/"><u>[New] Enhance Your GoPro Footage  Top 5 SD Cards (Hero 8, 7) for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-expert-level-recording-app-clean-and-clear-for-2024/"><u>[New] Expert-Level Recording App - Clean and Clear for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-cut-to-the-chase-boosting-your-instagram-with-content/"><u>[Updated] 2024 Approved  Cut to the Chase - Boosting Your Instagram with Content</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-enhancing-video-appeal-20-premium-thumbnail-fonts/"><u>[Updated] 2024 Approved  Enhancing Video Appeal  20 Premium Thumbnail Fonts</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-explore-the-most-economical-video-conference-software-best-10-recommendations-for-business-and-education/"><u>[Updated] 2024 Approved  Explore the Most Economical Video Conference Software  Best 10 Recommendations for Business & Education</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-exploring-the-context-and-importance-of-pfp-on-tiktok/"><u>[Updated] 2024 Approved  Exploring the Context and Importance of PFP on TikTok</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-clearview-studio-windows-1011-edition-for-2024/"><u>[Updated] ClearView Studio  Windows 10/11 Edition for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-unseen-viewers-route-navigating-instagram-stories-with-anonymous-viewing/"><u>[Updated] In 2024, The Unseen Viewer's Route  Navigating Instagram Stories with Anonymous Viewing</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-learn-everything-about-3d-lut-creator-and-mobile-app/"><u>[Updated] Learn Everything About 3D LUT Creator & Mobile App</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-the-emoticon-experts-guide-to-capturing-and-preserving-twitters-gif-images/"><u>2024 Approved  The Emoticon Expert’s Guide to Capturing and Preserving Twitter's GIF Images</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-understanding-netflixs-multi-stream-technology-a-quick-guide/"><u>2024 Approved  Understanding Netflix's Multi-Stream Technology  A Quick Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlocking-nearby-nuggets-your-essential-locale-lens-for-a-smoother-journey/"><u>2024 Approved  Unlocking Nearby Nuggets  Your Essential Locale Lens for a Smoother Journey</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/5-techniques-for-capturing-win10-games-for-2024/"><u>5 Techniques for Capturing Win10 Games for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-gionee-f3-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-novel-way-to-manage-galaxy-devices-with-windows-11/"><u>A Novel Way to Manage Galaxy Devices with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/budget-beware-top-7-hazards-with-sub-standard-windows-licenses/"><u>Budget Beware: Top 7 Hazards with Sub-Standard Windows Licenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-lookup-resurrecting-w11-file-explorer/"><u>Classic Lookup: Resurrecting W11 File Explorer</u></a></li>
<li><a href="https://games-able.techidaily.com/clean-slate-deleting-ps5-login-details/"><u>Clean Slate: Deleting PS5 Login Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-erroneous-onedrive-tags-in-windows-file-system/"><u>Correcting Erroneous OneDrive Tags in Windows File System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-file-thumbnail-absence-in-version-11/"><u>Correcting Windows File Thumbnail Absence in Version 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-service-failure-error-1053/"><u>Correcting Windows Service Failure Error 1053</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diy-disk-clone-mastery-for-pc-enthusiasts/"><u>DIY Disk Clone Mastery for PC Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-image-perfection-with-windows-photos-app/"><u>Effortless Image Perfection with Windows Photos App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-desktop-with-these-8-innovative-personalization-steps-from-bubbleui/"><u>Elevate Your Desktop with These 8 Innovative Personalization Steps From BubbleUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-focus-amidst-windows-11s-multitask-features/"><u>Enhancing Focus Amidst Windows 11'S Multitask Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-for-microsoft-pc-manager-on-w11/"><u>Essential Guide for Microsoft PC Manager on W11</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-realme-note-50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-switching-on-or-off-the-registry-editor/"><u>Guide: Switching on or Off the Registry Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-onedrives-cant-add-your-folder-right-now-error-on-windows/"><u>How to Fix OneDrive's Can’t Add Your Folder Right Now Error on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-optimize-viewing-experience-on-netflix-platforms/"><u>How to Optimize Viewing Experience on Netflix Platforms</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-stop-steam-from-continuously-crashing-in-seconds/"><u>How to Stop Steam From Continuously Crashing in Seconds</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-tecno-phantom-v-fold-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to Tecno Phantom V Fold Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/how-to-use-loilo-game-recorder/"><u>How to Use LoiLo Game Recorder</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-tecno-spark-20-proplus-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Tecno Spark 20 Pro+ FRP Bypass With Best Methods</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-se-2020-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone SE (2020) With an Apple Watch & What to Do if It Doesnt Work | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagram-reels-strategy-for-instant-success/"><u>Instagram Reels Strategy for Instant Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-items-into-windows-11-taskbar/"><u>Integrating Items Into Windows 11 Taskbar</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/macs-premier-mkv-player-picks/"><u>Mac's Premier MKV Player Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-websites-windows-programs-a-tutorial/"><u>Making Websites Windows Programs: A Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-browser-resource-usage-winmacchromeos-comparison/"><u>Minimizing Browser Resource Usage: Win/Mac/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373411881-navigate-and-solve-frozen-shift-problems/"><u>Navigate and Solve Frozen Shift Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-workflow-with-aero-shake-w11-tech/"><u>Optimizing Your Workflow with Aero Shake W11 Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-outlooks-error-0x80040610-in-windows-systems/"><u>Overcoming Outlook's Error 0X80040610 in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-power-indicators-ensure-a-full-charge-with-windows-11-alerts/"><u>Proactive Power Indicators: Ensure a Full Charge with Windows 11 Alerts</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reclaim-your-channel-from-dark-screens-on-twitch/"><u>Reclaim Your Channel From Dark Screens on Twitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-audible-acuity-ending-echo-of-empty-spaces/"><u>Regain Audible Acuity: Ending Echo of Empty Spaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-complications-caused-by-latest-windows-updates/"><u>Resolving Complications Caused by Latest Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-virtualboxs-usb-failure-message-a-step-by-step-guide-for-windows-users/"><u>Resolving VirtualBox's USB Failure Message: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11-pin-access-issues/"><u>Resolving Windows 11 PIN Access Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-program-functionality-with-ease/"><u>Restoring Windows Program Functionality with Ease</u></a></li>
<li><a href="https://technical-tips.techidaily.com/retro-reels-revealed-discovering-10-iconic-films-from-the-fabulous-80s-era/"><u>Retro Reels Revealed: Discovering 10 Iconic Films From the Fabulous '80S Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-experience-implementing-appxappxbundle-files-from-store/"><u>Seamless Experience: Implementing Appx/Appxbundle Files From Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-slacks-missing-notifications-issue-in-win-11/"><u>Solving Slack's Missing Notifications Issue in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-easing-through-administrative-denial-of-installers/"><u>Strategies for Easing Through Administrative Denial of Installers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-expiring-notifications-on-win11/"><u>Strategies to Prevent Expiring Notifications on Win11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/streamlining-your-web-experience-by-deploying-ai-agents-via-agentgpt-in-chromefirefox/"><u>Streamlining Your Web Experience by Deploying AI Agents via AgentGPT in Chrome/Firefox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-cached-data-for-optimal-performance/"><u>Taming Window’s Cached Data for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-talk-the-key-to-a-visible-mouse-indicator-in-windows-os/"><u>Tech Talk: The Key to a Visible Mouse Indicator in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-defenders-error-0x80004004/"><u>Troubleshooting Defender's Error 0X80004004</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-deskanywhere-failures-in-windows-11/"><u>Troubleshooting DeskAnywhere Failures in WIndows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncompromised-security-in-windows-app-downloads/"><u>Uncompromised Security in Windows App Downloads</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/understanding-igs-evolution-reels-vs-stories/"><u>Understanding IG's Evolution  Reels vs Stories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-stuck-photoshopping-in-windows-11-versions-2023/"><u>Unfreezing Stuck Photoshopping in Windows 11, Versions 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-true-power-of-windows-screen-capture-toolkit/"><u>Unleash the True Power of Windows' Screen Capture Toolkit.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-power-of-ping-windows-application-essentials/"><u>Unveiling the Power of Ping: Windows Application Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winservicesexe-explained-troubleshooting-guide/"><u>WinServices.exe Explained: Troubleshooting Guide</u></a></li>
</ul></div>
