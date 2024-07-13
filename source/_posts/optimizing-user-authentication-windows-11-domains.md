---
title: "Optimizing User Authentication: Windows 11, Domains"
date: 2024-07-12T17:44:31.114Z
updated: 2024-07-13T17:44:31.114Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing User Authentication: Windows 11, Domains"
excerpt: "This Article Describes Optimizing User Authentication: Windows 11, Domains"
keywords: Win11 Auth Optimize,Domain Authentication,Secure Login Windows,Access Control Windows 11,Identity Verification PC,User Credentials Management,Security Windows Protocols
thumbnail: https://thmb.techidaily.com/85be9153d8c81024583588a94ed9e00fc880777ac2a8c7cff5efd5d21044d91c.jpg
---

## Optimizing User Authentication: Windows 11, Domains

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/achieve-smooth-operator-install-in-windows-realm/"><u>Achieve Smooth Operator Install in Windows Realm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-msresourceappnametext-glitch-win11-style/"><u>Fixing 'MsResource:AppName/Text Glitch', Win11 Style</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-iphone-13-mini-could-not-be-activatedreached-issue-by-drfone-ios/"><u>How To Fix iPhone 13 mini Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-registry-tweaks-in-windows-terminal/"><u>The Ultimate Guide to Registry Tweaks in Windows Terminal</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-verizon-apple-iphone-6-by-drfone-ios/"><u>In 2024, How to Unlock Verizon Apple iPhone 6</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-nokia-150-2023-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Nokia 150 (2023) for Parents | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-explorer-tooltips-with-auto-update-notifications/"><u>Amplifying Explorer Tooltips with Auto-Update Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secrets-to-swiftly-concluding-a-troubled-update-process/"><u>5 Secrets to Swiftly Concluding a Troubled Update Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-pcs-touch-interface-a-user-friendly-tutorial/"><u>Tailoring Your PC’s Touch Interface: A User-Friendly Tutorial</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-top-picks-essential-products-every-entrepreneur-must-own/"><u>In 2024, Top Picks  Essential Products Every Entrepreneur Must Own</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-top-10-free-youtube-channels-for-exceptional-art-creation/"><u>2024 Approved  Top 10 FREE YouTube Channels for Exceptional Art Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-stuck-scrollbar-and-freezing-pages-in-microsoft-excel-on-windows/"><u>Stop Stuck Scrollbar & Freezing Pages in Microsoft Excel on Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-vimeos-video-segments-the-chapter-creation-handbook/"><u>[New] In 2024, Vimeo's Video Segments  The Chapter Creation Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-drivers-make-sure-your-graphics-card-drivers-are-up-to-date-for-optimal-performance/"><u>Update Drivers: Make Sure Your Graphics Card Drivers Are up to Date for Optimal Performance</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/ranking-the-best-top-6-tools-for-fb-lite-video-downloading-2023-for-2024/"><u>Ranking the Best  Top 6 Tools for FB Lite Video Downloading, 2023 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-hello-5-ways-to-tackle-fingerprint-problems/"><u>Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-tips-and-solutions-for-common-vlc-issues-on-mac/"><u>Top Tips & Solutions for Common VLC Issues on Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-compliance-with-insider-editions/"><u>Ensuring Compliance with Insider Editions</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/understanding-youtubes-legal-framework-vs-cc-for-2024/"><u>Understanding YouTube's Legal Framework Vs. CC for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-samsung-galaxy-a14-5g-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Samsung Galaxy A14 5G IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-xiaomi-13t-pro-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Xiaomi 13T Pro Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-experience-running-task-manager-as-admin-on-win11/"><u>Elevate Your Computer Experience: Running Task Manager as Admin on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-ignoring-restricted-feature-on-windows-software/"><u>Tips for Ignoring Restricted Feature on Windows Software</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-bringing-heartwarmth-to-the-winter-5-snug-cinematographic-tips/"><u>[New] In 2024, Bringing Heartwarmth to the Winter  5 Snug Cinematographic Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-apex-of-atmospheric-analysis-windows-11s-top-weather-apps/"><u>The Apex of Atmospheric Analysis: Windows 11'S Top Weather Apps</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-from-sony-xperia-10-v-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Sony Xperia 10 V Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-run-windows-media-player/"><u>Easy Steps to Run Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-hidden-disk-space-with-windows-1011s-deletion-automation/"><u>Unlock Hidden Disk Space with Windows 10/11'S Deletion Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-desktop-portable-tools-in-win11-menu/"><u>Streamline Your Desktop: Portable Tools in Win11 Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-resource-building-shortcuts-for-microsofts-uwp-apps-in-windows-11/"><u>The Ultimate Resource: Building Shortcuts for Microsoft's UWP Apps in Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-survive-and-thrive-top-8-zombie-game-experiences/"><u>In 2024, Survive and Thrive  Top 8 Zombie Game Experiences</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/10-most-popular-tiktok-food-trends-for-2024/"><u>10 Most Popular Tiktok Food Trends for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-how-to-make-viral-buzz-on-facebook-for-2024/"><u>[Updated] How to Make Viral Buzz on Facebook for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-xiaomi-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Xiaomi</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-wmv-splitter-software-free-and-easy-to-use/"><u>Best WMV Splitter Software Free and Easy to Use</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-realme-gt-5-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Realme GT 5?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-mistakes-to-sidestep-on-your-first-day-with-windows-11/"><u>Crucial Mistakes to Sidestep on Your First Day with Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/the-complete-cheatsheet-to-make-a-collage-for-2024/"><u>The Complete Cheatsheet to Make a Collage for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-mechanics-behind-failed-usb-attachment-in-virtualbox/"><u>Decoding the Mechanics Behind Failed USB Attachment in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lsassexe-component-not-found-error-in-windows/"><u>Addressing lsass.exe Component Not Found Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/becoming-a-storage-strategy-expert-with-windows-diskusage-commands-mastery/"><u>Becoming a Storage Strategy Expert with Windows' DiskUsage Commands Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-customizing-fn-key-functions/"><u>Win 10/11: Customizing Fn Key Functions</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-step-by-step-incorporating-new-fonts-into-after-effects/"><u>In 2024, Step-by-Step  Incorporating New Fonts Into After Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-convert-cr2-images-to-windows-friendly-jpg-format/"><u>Swiftly Convert CR2 Images to Windows-Friendly JPG Format</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-digital-leaders-the-top-10-online-video-recorder-apps/"><u>2024 Approved  Digital Leaders  The Top 10 Online Video Recorder Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-correcting-installer-mishaps-a-win11-blueprint/"><u>Unraveling & Correcting Installer Mishaps: A Win11 Blueprint</u></a></li>
</ul></div>
