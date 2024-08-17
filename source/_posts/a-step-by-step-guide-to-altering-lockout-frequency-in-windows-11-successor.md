---
title: A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor
date: 2024-08-16T01:09:29.728Z
updated: 2024-08-17T01:09:29.728Z
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
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-techtrends-screencapture-software-evaluation/"><u>[New] 2024 Approved  TechTrends  ScreenCapture Software Evaluation</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/taying-within-the-limits-key-youtube-policies/"><u>[New] Staying Within the Limits  Key YouTube Policies</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-top-5-web-based-or-extension-voice-changers-for-chromebook/"><u>[New] Top 5 Web-Based or Extension Voice Changers for Chromebook</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-4-ways-to-record-sims-4-gameplay/"><u>[Updated] 4 Ways to Record Sims 4 Gameplay</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-free-6-best-youtube-to-mp3-downloader-for-android/"><u>[Updated] FREE 6 Best YouTube to MP3 Downloader for Android</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-from-archive-to-annotation-turning-zip-into-srt/"><u>[Updated] From Archive to Annotation  Turning ZIP Into SRT</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-best-practices-for-6-trendy-mc-houses/"><u>[Updated] In 2024, Best Practices for 6 Trendy MC Houses</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-vivo-v29-pro-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Vivo V29 Pro FRP Bypass Instantly</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/amplify-your-television-clarity-on-a-budget-in-depth-analysis-of-the-1byone-digital-indoor-tv-antenna/"><u>Amplify Your Television Clarity on a Budget: In-Depth Analysis of the 1BYONE Digital Indoor TV Antenna</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-steams-file-lock-error-and-fixes/"><u>Deciphering Steam’s File Lock Error and Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defeat-fixed-menus-in-windows-your-ultimate-guide/"><u>Defeat Fixed Menus in Windows: Your Ultimate Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradication-of-windows-update-malfunction-error-0x80246007/"><u>Eradication of Windows Update Malfunction: Error 0X80246007</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/essential-software-for-recording-educational-experiences/"><u>Essential Software for Recording Educational Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-tackling-windows-not-found-issue/"><u>Essential Steps: Tackling Windows' Not Found Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-bypass-password-required-alert-on-windows-11/"><u>Guide to Bypass ‘Password Required’ Alert on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-realme-12-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Realme 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-xiaomi-mix-fold-3-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Xiaomi Mix Fold 3 If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-apple-id-verification-code-not-working-from-apple-iphone-6s-by-drfone-ios/"><u>How To Fix Apple ID Verification Code Not Working From Apple iPhone 6s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-package-non-registration-issue-in-windows/"><u>How to Rectify Package Non-Registration Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-10/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 10</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-troubleshoot-itunesfinder-when-it-wont-detect-your-iphone/"><u>How to Troubleshoot iTunes/Finder When It Won't Detect Your iPhone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-civi-3-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi Civi 3 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-smartphone-showcase-the-very-best-for-artistic-endeavors/"><u>In 2024, Smartphone Showcase  The Very Best for Artistic Endeavors</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-xiaomi-redmi-12-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Xiaomi Redmi 12 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/journey-to-stickers-full-tutorial-for-turning-gifs-in-chat-apps-like-discord-and-telegram-for-2024/"><u>Journey to Stickers  Full Tutorial for Turning GIFs in Chat Apps Like Discord and Telegram for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fixes-for-windows-marketplace-error-0x80073cf3/"><u>Mastering Fixes for Windows Marketplace (Error 0X80073CF3)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-controlling-external-hard-drive-access/"><u>Mastering the Art of Controlling External Hard Drive Access</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-art-of-storytelling-video-editing-tips-to-bring-your-home-movies-to-life/"><u>New The Art of Storytelling Video Editing Tips to Bring Your Home Movies to Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-stumbling-block-fixing-the-missing-wwinplusprint-on-pc/"><u>Overcome The Stumbling Block: Fixing the Missing WWin+Print on PC.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-try-connecting-bluetooth-failures-on-windows-11-os/"><u>Overcoming 'Try Connecting' Bluetooth Failures on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pinpointing-valid-logins-amidst-failed-attempts-in-windows/"><u>Pinpointing Valid Logins Amidst Failed Attempts in Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/premium-high-resolution-pics-viewer-quickly-for-2024/"><u>Premium High-Resolution Pics Viewer, Quickly for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-excessive-memory-consumption-in-antivirus-tools/"><u>Reducing Excessive Memory Consumption in Antivirus Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-odbc-interface/"><u>Step-by-Step Guide to Windows ODBC Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-network-prompts-comprehensive-steps-in-windows-os/"><u>Streamlining Network Prompts: Comprehensive Steps in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-characteristics-setting-ai-devices-apart/"><u>The Characteristics Setting AI Devices Apart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-navigating-your-way-through-netconfig/"><u>The Essential Guide to Navigating Your Way Through NetConfig</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-digital-canvases-for-your-win10-artistry/"><u>Top 7 Digital Canvases for Your Win10 Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-utilizing-windows-11s-restore-procedures/"><u>Understanding and Utilizing Windows 11'S Restore Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-package-management-proficiency-wingetui-for-windows-users/"><u>Unlock Package Management Proficiency: WingetUI for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-the-past-adding-trophies-and-awards-to-classic-titles-using-retroarch/"><u>Upgrade the Past - Adding Trophies and Awards to Classic Titles Using Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-a-crossed-out-icon-mean-for-your-files/"><u>What Does a Crossed Out Icon Mean for Your Files?</u></a></li>
</ul></div>
