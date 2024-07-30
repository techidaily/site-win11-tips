---
title: Break Free From Default Settings on Windows Firewall
date: 2024-07-29T08:11:55.626Z
updated: 2024-07-30T08:11:55.626Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Break Free From Default Settings on Windows Firewall
excerpt: This Article Describes Break Free From Default Settings on Windows Firewall
keywords: Firewall Basics,Customize WinFirewall,Opt Out Defaults,Firewall Security,Advanced Firewall Control,Disable Default Rules,Enhance Firewall Settings
thumbnail: https://thmb.techidaily.com/9e9b99a6d9a89547d11f6e0d3b7ad397a8c45980a1b807a51ada942660956a43.jpg
---

## Break Free From Default Settings on Windows Firewall

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Windows PowerShell

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-elevate-your-video-visibility-ethically-one-million-in-views-for-2024/"><u>[New] Elevate Your Video Visibility Ethically  One Million in Views for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-hone-your-skills-how-to-seamlessly-post-videos-to-instagram-via-desktop-for-2024/"><u>[New] Hone Your Skills  How to Seamlessly Post Videos to Instagram via Desktop for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-comprehensive-users-manual-on-using-ez-grabber/"><u>[New] In 2024, The Comprehensive User's Manual on Using EZ Grabber</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-access-top-shorter-video-downloads-for-free-online-for-2024/"><u>[Updated] Access Top Shorter Video Downloads for FREE Online for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-best-picks-the-leading-10-online-resources-for-vimeo-video-download-for-2024/"><u>[Updated] Best Picks  The Leading 10 Online Resources for Vimeo Video Download for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-binge-worthy-viral-video-roundup-on-tiktok/"><u>[Updated] Binge-Worthy  Viral Video Roundup on TikTok</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-a-beginners-path-to-compiling-a-youtube-playlist/"><u>[Updated] In 2024, A Beginner's Path to Compiling a YouTube Playlist</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-timeless-treasures-the-premier-compiler-and-preserver-for-tweeter-visuals/"><u>[Updated] In 2024, Timeless Treasures  The Premier Compiler & Preserver for Tweeter Visuals</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-novices-nook-the-easiest-mc-dwellings-explored-for-2024/"><u>[Updated] Novice's Nook  The Easiest MC Dwellings Explored for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-sequel-of-seconds-measuring-20mb-footage/"><u>[Updated] Sequel of Seconds  Measuring 20MB Footage</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-slow-motion-footage-gopro-hero-10-tips/"><u>2024 Approved  Mastering Slow-Motion Footage  GoPro Hero 10 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-open-disk-management-in-windows-10-and-11/"><u>4 Ways to Open Disk Management in Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-windows-update-error-0x800f080a/"><u>6 Ways to Fix the Windows Update Error 0X800f080a</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-insights-on-staying-with-older-windows-editions/"><u>7 Insights on Staying with Older Windows Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-pathways-to-revitalize-a-dying-windows-services-console/"><u>7 Pathways to Revitalize a Dying Windows Services Console</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-optional-features-not-installing-on-windows-10-and-11/"><u>7 Ways to Fix Optional Features Not Installing on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-running-imessage-on-windows/"><u>A Comprehensive Guide to Running iMessage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-dive-into-modern-standby-and-its-problematic-aspects/"><u>A Dive Into Modern Standby and Its Problematic Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-resolving-rd-session-errors-win10win11/"><u>A Guide to Resolving RD Session Errors Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-microsofts-bluetooth-app/"><u>A Step-by-Step Guide to Using Microsoft's Bluetooth App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-winning-strategy-for-moving-software-into-the-future-of-windows-11/"><u>A Winning Strategy for Moving Software Into the Future of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-app-opening-top-5-windows-11-tips/"><u>Accelerate App Opening: Top 5 Windows 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-startup-manipulating-boot-timeout-on-windows-11/"><u>Accelerate Startup: Manipulating Boot Timeout on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-valorant-setup-with-these-tips/"><u>Accelerate Your Valorant Setup with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-awareness-custom-notification-for-win11-users/"><u>Accelerating Battery Awareness: Custom Notification for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-index-view-options/"><u>Accessing Windows Index View Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-window-11-search-game-essential-tips-to-know/"><u>Ace Your Window 11 Search Game: Essential Tips to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-notepad-display-from-light-to-dark-in-win-11-version/"><u>Adapting Notepad Display: From Light to Dark in Win 11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-pre-ultimate-computers-to-seniors-needs/"><u>Adapting Pre-Ultimate Computers to Seniors' Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-common-failures-when-importing-iphones-to-windows/"><u>Addressing Common Failures When Importing iPhones to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-a00f4289-for-windows-11-webcam/"><u>Addressing Error Code A00F4289 for Windows 11 Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-hang-error-dxgierrordevicehunk-on-windows/"><u>Addressing the HANG Error: DXGI_ERROR_DEVICE_HUNK on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-cameras-failed-recordings/"><u>Addressing Windows Camera's Failed Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11s-default-silent-camera-alert-setting/"><u>Altering Windows 11'S Default Silent Camera Alert Setting</u></a></li>
<li><a href="https://activate-lock.techidaily.com/apple-iphone-12-icloud-activation-lock-bypass-by-drfone-ios/"><u>Apple iPhone 12 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360526951-arcade-mode-for-window-users-key-fixes-ahead/"><u>Arcade Mode for Window Users: Key Fixes Ahead</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-windows-apps-struggling-to-connect-to-the-internet-try-these-fixes/"><u>Are Your Windows Apps Struggling to Connect to the Internet? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audacity-sound-error-step-by-step-windows-fix-guide/"><u>Audacity Sound Error: Step-by-Step Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-your-agenda-linking-to-do-to-ifttt/"><u>Automate Your Agenda: Linking To-Do to IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-pitfalls-with-win11-captions/"><u>Avoiding Common Pitfalls with Win11 Captions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-pitfalls-of-mysterious-obs-studio-recordings/"><u>Avoiding the Pitfalls of Mysterious OBS Studio Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-zoom-failures-immediate-resolution-for-error-1132/"><u>Avoiding Zoom Failures - Immediate Resolution for Error 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bargain-alert-key-enthusiasts-snag-612lifetime-windows-11-deal-today-only/"><u>Bargain Alert: Key Enthusiasts Snag $6.12/Lifetime Windows 11 Deal Today Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-fps-measurement-software-for-windows-11-users/"><u>Best FPS Measurement Software for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-worlds-the-best-6-android-apps-for-an-advanced-window-11-experience/"><u>Blend Worlds: The Best 6 Android Apps for an Advanced Window 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-windows-innovations-into-linux/"><u>Blending Windows Innovations Into Linux</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-workflow-experts-choice-for-the-top-8-windows-pomodoros/"><u>Boost Workflow: Expert's Choice for the Top 8 Windows Pomodoros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-browser-performance-fix-youtube-delays/"><u>Boosting Browser Performance: Fix YouTube Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278644350-briefly-explain-what-cultural-relativism-means-in-your-own-words/"><u>Briefly Explain What Cultural Relativism Means in Your Own Words</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/crop-like-a-pro-mastering-video-editing-with-avidemux-for-2024/"><u>Crop Like a Pro Mastering Video Editing with Avidemux for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/cut-the-redundancy-a-step-by-step-to-adding-times-in-your-videos/"><u>Cut the Redundancy  A Step-by-Step to Adding Times in Your Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explore-free-options-10-leading-mac-artists-preferences-for-2024/"><u>Explore Free Options  10 Leading Mac Artists' Preferences for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-poco-c50-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Poco C50 If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-tecno-camon-20-pro-5g-devices-by-drfone-android/"><u>How to Reset Gmail Password on Tecno Camon 20 Pro 5G Devices</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-c33-2023-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Realme C33 2023 Phone without Any Data Loss</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-vivo-y78plus-t1-editionwithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Vivo Y78+ (T1) Editionwith/without a PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-oppo-reno-8t-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Oppo Reno 8T to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-realme-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Realme 11 5G? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-navigating-the-hidden-paths-of-tiktok-unshrouding-techniques/"><u>In 2024, Navigating the Hidden Paths of TikTok  Unshrouding Techniques</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Vivo Y02T? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-seamlessly-combining-iphone-videos-and-images/"><u>In 2024, Seamlessly Combining IPhone Videos and Images</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-unveiling-the-secrets-to-a-flawless-fb-live-session/"><u>In 2024, Unveiling the Secrets to a Flawless FB Live Session</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/kinemaster-app-for-android-complete-review-2023-for-2024/"><u>KineMaster App for Android - Complete Review 2023 for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-ai-script-generator-virbo-guide/"><u>New In 2024, AI Script Generator | Virbo Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719383487316-overcoming-windows-obstacles-simple-effective-solutions/"><u>Overcoming Windows Obstacles: Simple, Effective Solutions!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unlock-the-potential-of-your-camera-creating-stunning-slow-motion-videos-for-instagram-for-2024/"><u>Unlock the Potential of Your Camera  Creating Stunning Slow-Motion Videos for Instagram for 2024</u></a></li>
</ul></div>
