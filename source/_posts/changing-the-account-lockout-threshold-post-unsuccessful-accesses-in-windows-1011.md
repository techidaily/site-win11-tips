---
title: Changing the Account Lockout Threshold Post Unsuccessful Accesses in Windows 10/11
date: 2024-07-29T08:13:45.100Z
updated: 2024-07-30T08:13:45.100Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing the Account Lockout Threshold Post Unsuccessful Accesses in Windows 10/11
excerpt: This Article Describes Changing the Account Lockout Threshold Post Unsuccessful Accesses in Windows 10/11
keywords: WINDOWS 10 Lockout Adjustment,WINDOWS 10 Login Lockout Policy,Microsoft Windows Account Security,Access Control Threshold Upgrade,Unsuccessful Logins,Enhance Windows Password Lockout,Changing Lockout Delays (Windows)
thumbnail: https://thmb.techidaily.com/a49d5779dbd8d3bcb3bf8423c93f4ef941ba145d1cb34757b006a9b7dc8bcdff.jpeg
---

## Changing the Account Lockout Threshold Post Unsuccessful Accesses in Windows 10/11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-mastering-revenue-on-youtube-shorts/"><u>[New] Mastering Revenue on YouTube Shorts</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-quintessential-5-for-elevated-slow-videos/"><u>[New] Quintessential 5 for Elevated Slow Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-overcoming-technical-hurdles-in-iphone-xs-facial-detection/"><u>[Updated] 2024 Approved  Overcoming Technical Hurdles in iPhone X's Facial Detection</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-elite-nintendo-switch-battle-selection-max-156/"><u>[Updated] In 2024, Elite Nintendo Switch Battle Selection (Max 156)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premium-picks-the-ultimate-gopro-upgrades/"><u>[Updated] Premium Picks  The Ultimate Gopro Upgrades</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-experts-guide-to-recording-mp4-videos/"><u>2024 Approved  Expert's Guide to Recording MP4 Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-art-of-podcast-titling-a-step-by-step-guide/"><u>2024 Approved  The Art of Podcast Titling  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-christmas-ify-your-windows-11/"><u>7 Ways to Christmas-Ify Your Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-customize-windows-11-and-11-with-winbubble/"><u>8 Ways to Customize Windows 11 and 11 With WinBubble</u></a></li>
<li><a href="https://change-location.techidaily.com/achieve-flawless-playback-advanced-mpeg-fixer-for-healing-scratched-damaged-videos/"><u>Achieve Flawless Playback: Advanced MPEG Fixer for Healing Scratched, Damaged Videos</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-call-logs-from-infinix-note-30-by-fonelab-android-recover-call-logs/"><u>Best Android Data Recovery - undelete lost call logs from Infinix Note 30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-pointer-design-in-microsoft-systems/"><u>Customize Pointer Design in Microsoft Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-to-cut-down-system-energy-usage-games/"><u>Efficient Strategies to Cut Down System Energy Usage Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-how-to-disguise-taskbar-on-win-11/"><u>Expert Guide: How to Disguise Taskbar on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-the-no-image-preview-error-in-your-windows-11-environment/"><u>Fix the No Image Preview Error in Your Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-recognized-hdd-problems-in-a-step-by-step-windows-11-process/"><u>Fixing Non-Recognized HDD Problems in a Step-by-Step Windows 11 Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-flushed-to-functional-8-steps-for-desktop-color-correction/"><u>From Flushed to Functional: 8 Steps for Desktop Color Correction</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-tecno-camon-20-premier-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-tutorial-to-bypass-your-lava-yuva-3-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Lava Yuva 3 Face Lock?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-stop-windows-from-launching-spotify/"><u>Guide to Stop Windows From Launching Spotify</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-hyper-v-in-windows-11/"><u>How to Enable Hyper-V in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Oppo K11 5G? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-malfunctioning-your-drivers-with-windows-device-manager-on-windows-11107-by-drivereasy-guide/"><u>How to identify malfunctioning your drivers with Windows Device Manager on Windows 11/10/7</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-oneplus-open-by-fonelab-android-recover-data/"><u>How to recover lost data from OnePlus Open?</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-7-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 7 To Other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-correction-resetting-folders-on-a-ws11-pc/"><u>Immediate Correction: Resetting Folders on a WS11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11-parental-control-measures/"><u>Implementing Windows 11 Parental Control Measures</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-realme-note-50-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Realme Note 50 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-explore-the-peak-tv-service-providers-comparative-insights/"><u>In 2024, Explore the Peak TV Service Providers  Comparative Insights</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Motorola Edge 40 Neo? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-path-profile-picture-dimensions/"><u>In 2024, Path Profile Picture Dimensions</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamline-and-optimize-google-for-podcasters/"><u>In 2024, Streamline & Optimize  Google for Podcasters</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-tweet-to-tune-video-to-audible-file/"><u>In 2024, Tweet-to-Tune  Video to Audible File</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-process-sorting-and-theme-customization-in-windows-11/"><u>In-Depth Analysis: Process Sorting and Theme Customization in Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/leveraging-two-platforms-optimize-your-twitch-and-youtube-presence/"><u>Leveraging Two Platforms  Optimize Your Twitch and YouTube Presence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-your-mouse-cursor-stand-out-on-windows-devices/"><u>Making Your Mouse Cursor Stand Out on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-phone-call-basics-with-intel-unison/"><u>Mastering Windows 11: Phone Call Basics with Intel Unison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-world-of-github-desktop-on-windows-systems/"><u>Navigating the World of GitHub Desktop on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-application-crash-due-to-unhandled-exceptions/"><u>Navigating Through 'Application Crash' Due to Unhandled Exceptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-defenders-antivirus-blockage/"><u>Navigating Through Windows Defender's Antivirus Blockage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-critical-alerts-when-to-reset-windows/"><u>Nine Critical Alerts: When to Reset Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-xbox-stranded-message-quick-solution-for-windows-users/"><u>Overcome Xbox Stranded Message: Quick Solution for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-updater-0x8024a205-issue/"><u>Overcoming Windows Updater 0X8024a205 Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-selectivity-enable-checkbox-file-option-in-win11/"><u>Perfecting Selectivity: Enable Checkbox File Option in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rectifications-quick-tricks-to-prevent-windows-crashes-in-games/"><u>Rapid Rectifications: Quick Tricks to Prevent Windows Crashes in Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reboot-the-process-solving-hidden-logins-on-windows-11/"><u>Reboot the Process: Solving Hidden Logins on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-excess-usage-enhancing-efficiency-for-news-in-windows-1011/"><u>Slash Excess Usage: Enhancing Efficiency for News in Windows 10/11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/step-by-step-guide-to-applying-a-realistic-motion-blur-in-photoshop-for-2024/"><u>Step-by-Step Guide to Applying a Realistic Motion Blur in Photoshop for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-monitoring-integrating-system-resource-data-in-systray/"><u>Streamline Monitoring: Integrating System Resource Data in SysTray</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-high-cpu-usage-in-dropbox-on-windows-pcs/"><u>Tackling High CPU Usage in Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-keyboard-shortcuts-next-to-power-icon/"><u>Tailoring Windows 11: Keyboard Shortcuts Next to Power Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-epic-data-preservation-techniques/"><u>The Essentials of Epic Data Preservation Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-conquering-win-errors/"><u>The Ultimate Guide to Conquering Win Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-disabled-user-sign-in-on-windows/"><u>Troubleshooting Disabled User Sign-In on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-hidden-pin-removal-switch-in-windows-11/"><u>Unlocking Hidden Pin Removal Switch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unshackling-third-party-vendors-from-defender-constraints/"><u>Unshackling Third-Party Vendors From Defender Constraints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-your-pcs-true-wired-capability-through-win11-connectivity-tweaks/"><u>Unveil Your PC’s True Wired Capability Through Win11 Connectivity Tweaks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>