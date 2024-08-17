---
title: Revamping the Reset Account Lockout After Incorrect Passwords on Windows 11
date: 2024-08-16T02:35:39.568Z
updated: 2024-08-17T02:35:39.568Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revamping the Reset Account Lockout After Incorrect Passwords on Windows 11
excerpt: This Article Describes Revamping the Reset Account Lockout After Incorrect Passwords on Windows 11
keywords: Windows 11 Account Lock,Password Reset Guide,Win11 Reset Failed,Correct Passwords Help,Lockout Fix in Windows 11,Unlock Windows PC,Safe Reset Password Tips
thumbnail: https://thmb.techidaily.com/57a07625ab9c873f1b8816cfe4ef02cf1a6f9bda4b7acdd0899c793b0d810b70.jpg
---

## Revamping the Reset Account Lockout After Incorrect Passwords on Windows 11

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-discover-two-hands-on-approaches-to-personalize-snapchat-audio/"><u>[New] 2024 Approved  Discover Two Hands-On Approaches to Personalize Snapchat Audio</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-navigating-complex-projects-on-magix-video-pro-x/"><u>[New] 2024 Approved  Navigating Complex Projects on Magix Video Pro X</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-accurate-mac-photography-mastery-of-five-proven-snapshot-ways/"><u>[New] In 2024, Accurate Mac Photography  Mastery of Five Proven Snapshot Ways</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-efficient-tweet-strategy-embrace-aspect-ratio-specifications/"><u>[Updated] Efficient Tweet Strategy  Embrace Aspect Ratio Specifications</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-elevate-skype-call-audio-excellence/"><u>[Updated] In 2024, Elevate Skype Call Audio Excellence</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-navigating-video-uploads-and-enhancements-in-instagram/"><u>[Updated] Navigating Video Uploads and Enhancements in Instagram</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-guide-how-to-record-and-save-youtube-videos-without-spending-a-penny/"><u>[Updated] The Ultimate Guide  How To Record and Save YouTube Videos without Spending a Penny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-steps-for-efficient-access-to-windows-connections-tool/"><u>10 Key Steps for Efficient Access to Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-tips-for-restoring-fbm-functionality-on-desktop/"><u>10 Key Tips for Restoring FBM Functionality on Desktop</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-kinemaster-essentials-a-guide-to-flawless-movements/"><u>2024 Approved  Kinemaster Essentials  A Guide to Flawless Movements</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-unveiling-horizon-based-approaches-to-post-on-igtv/"><u>2024 Approved  Unveiling Horizon-Based Approaches to Post on IGTV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-innovations-to-transform-your-windows-11-setup/"><u>6 Android Innovations to Transform Your Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-crucial-strategies-to-salvage-a-frozen-windows-service-panel/"><u>7 Crucial Strategies to Salvage a Frozen Windows Service Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-windows-narrators-legacy-keyboard-shortcuts/"><u>A Complete Guide to Windows Narrator's Legacy Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-cortana-data-retrieval-for-windows-users/"><u>A Complete Walkthrough: Cortana Data Retrieval for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-fix-13-solutions-for-windows-system-repair/"><u>A Quick Fix: 13 Solutions for Windows System Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-browsing-activate-filters-with-checkbox-on-win11/"><u>Accelerate File Browsing: Activate Filters with Checkbox on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-loading-device-drivers-in-windows-11/"><u>Addressing Non-Loading Device Drivers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-slowness-in-windows-discord-interface/"><u>Addressing Slowness in Windows Discord Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-timeout-issue-windows-1110-semaphore-error-0x80070079/"><u>Addressing Timeout Issue - Windows 11/10 Semaphore Error 0X80070079</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-dynamic-background-anytime/"><u>Adjusting Your Windows Dynamic Background Anytime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-managing-users-via-command-prompt/"><u>Advanced Tips for Managing Users via Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-winservicesexe-and-its-errors/"><u>An In-Depth Look at Winservices.exe and Its Errors</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/assemble-comic-memes-with-giphy-for-2024/"><u>Assemble Comic Memes with Giphy for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-your-windows-11-activation-status/"><u>Assessing Your Windows 11 Activation Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-desktop-interactivity-the-widget-approach-in-win-11/"><u>Augmenting Desktop Interactivity: The Widget Approach in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-visual-clutter-inside-windows-search/"><u>Avoiding Visual Clutter Inside Windows Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-100-quagmire-with-these-simple-solutions/"><u>Beat the 100%% Quagmire with These Simple Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-trick-swiftly-access-sticky-notes-post-boot-windows/"><u>Beginner's Trick: Swiftly Access Sticky Notes Post-Boot Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-11-videoscripting-software-round-up/"><u>Best Windows 11 Videoscripting Software Round-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-power-visibility-customizing-full-charge-alerts-for-win11/"><u>Boost Power Visibility: Customizing Full Charge Alerts for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-health-through-interactive-device-tracking/"><u>Boost System Health Through Interactive Device Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-the-ultimate-guide-to-wpm-in-windows-11/"><u>Boost Your Workflow: The Ultimate Guide to WPM in Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/essential-techniques-for-writing-irresistible-vlog-narratives/"><u>Essential Techniques for Writing Irresistible Vlog Narratives</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-windows-werfaultexe-app-crash-issues/"><u>How to Resolve Windows WerFault.exe App Crash Issues</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-from-iphone-12-pro-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code From iPhone 12 Pro</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-samsung-galaxy-z-flip-5-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Samsung Galaxy Z Flip 5 Phone that is Locked?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Motorola Moto G14? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-xiaomi-mix-fold-3-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Xiaomi Mix Fold 3 Phone Pattern Lock</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-what-is-an-ai-video-generator/"><u>In 2024, What Is an AI Video Generator?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-davinci-resolve-scopes-have-undergone-significant-improvements-find-out-how-to-use-these-scopes-and-improve-your-video-editing-skills-for-2024/"><u>New DaVinci Resolve Scopes Have Undergone Significant Improvements. Find Out How to Use These Scopes and Improve Your Video Editing Skills for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255690388-pro-tips-to-improve-your-snip-and-sketch-screenshot-experience/"><u>Pro Tips to Improve Your Snip & Sketch Screenshot Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381156661-reactive-keys-reclaiming-shift-on-win/"><u>Reactive Keys: Reclaiming Shift on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292309532-revolutionize-incompatibility-on-windows-without-tools/"><u>Revolutionize Incompatibility on Windows without Tools!</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-13plus-accessible-no-cost-audio-engineering-applications-for-all-platforms/"><u>Updated 2024 Approved 13+ Accessible No-Cost Audio Engineering Applications for All Platforms</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>Which is the Best Fake GPS Joystick App On Apple iPhone 11 Pro? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>