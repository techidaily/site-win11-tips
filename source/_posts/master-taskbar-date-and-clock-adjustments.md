---
title: Master Taskbar Date & Clock Adjustments
date: 2024-08-23T07:03:42.051Z
updated: 2024-08-24T07:03:42.051Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Master Taskbar Date & Clock Adjustments
excerpt: This Article Describes Master Taskbar Date & Clock Adjustments
keywords: Taskbar Time Controls,Clock Display Change,Set Windows Date,Date Bar Settings,Clock Update Method,Adjust Timer Widget,Customize Taskbar Info
thumbnail: https://thmb.techidaily.com/3186e4df3cd85f5548d507c683f3aba596cb59805e7e3afa70cfb9fc8a32b29d.jpg
---

## Master Taskbar Date & Clock Adjustments

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://article-posts.techidaily.com/new-in-2024-secrets-of-windows-10-effortless-media-importation-methods/"><u>[New] In 2024, Secrets of Windows 10  Effortless Media Importation Methods</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-masterful-transitioning-8-leading-convertors-for-sub-and-srt/"><u>[New] Masterful Transitioning  8 Leading Convertors for Sub and SRT</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-mobile-cinema-app-assessment-review/"><u>[Updated] In 2024, Mobile Cinema App Assessment Review</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-optimal-sound-systems-under-100-for-immersive-gameplay/"><u>[Updated] In 2024, Optimal Sound Systems Under $100 for Immersive Gameplay</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-employment-and-video-content-creation/"><u>[Updated] Navigating Employment and Video Content Creation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-step-by-step-seamlessly-upgrading-to-macos-11-big-sur/"><u>[Updated] Step-by-Step  Seamlessly Upgrading to macOS 11 Big Sur</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-essential-guide-to-metaverse-brand-strategies/"><u>2024 Approved  The Essential Guide to Metaverse Brand Strategies</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-transforming-ideas-into-impactful-scenes-through-dialogue/"><u>2024 Approved  Transforming Ideas Into Impactful Scenes Through Dialogue</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-infinix-zero-5g-2023-turbo-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Infinix Zero 5G 2023 Turbo</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-buddies-games-top-metagame-escapades/"><u>Best Buddies Games  Top Metagame Escapades</u></a></li>
<li><a href="https://extra-hints.techidaily.com/capture-the-moment-iphone-xs-revolutionary-camera-for-2024/"><u>Capture the Moment  IPhone X's Revolutionary Camera for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clean-slate-clearing-windows-11-activity-record/"><u>Clean Slate: Clearing Windows 11 Activity Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-black-windows-rdp-connection-issue/"><u>Correcting Black Windows RDP Connection Issue</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/creality-unveils-release-schedule-and-price-points-for-the-powerhouse-k1c-3d-printer-with-detailed-specifications/"><u>Creality Unveils Release Schedule & Price Points for the Powerhouse K1C 3D Printer with Detailed Specifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-down-on-time-spent-error-0x800736cc-in-windows-update/"><u>Cutting Down on Time Spent: Error 0X800736CC in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-os-emulation-strategies-in-virtual-environment/"><u>Cutting-Edge OS Emulation Strategies in Virtual Environment</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/easy-steps-to-free-online-and-offline-animation-for-2024/"><u>Easy Steps to Free Online & Offline Animation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-command-line-experience-make-terminal-first/"><u>Enhance Command Line Experience: Make Terminal First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-wake-up-speed-tweaking-boot-menu-wait-timer/"><u>Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-car-tools-for-efficient-windows-use/"><u>Essential Car Tools for Efficient Windows Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/faster-steam-content-downloading-for-windows-users/"><u>Faster Steam Content Downloading for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-fixing-a-frozen-control-key-in-win11/"><u>Guiding You Through Fixing a Frozen Control Key in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-outlook-notifications-not-working-on-windows/"><u>How to Fix Outlook Notifications Not Working on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-s23plus-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy S23+ to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-gionee-f3-pro-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Gionee F3 Pro to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-xiaomi-redmi-note-12-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Xiaomi Redmi Note 12 5G FRP</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-itel-s23plus-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Itel S23+ IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-your-heat-in-check-with-these-gamers-laptop-care-guidelines/"><u>Keep Your Heat in Check with These Gamer's Laptop Care Guidelines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-windows-11-search-strategies-for-enhanced-efficiency/"><u>Masterful Windows 11 Search Strategies for Enhanced Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-printer-troubles-reactivating-missing-wwinplusp-on-windows/"><u>Mastering Printer Troubles: Reactivating Missing WWin+P on Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-video-streams-fix-youtube-lag-in-chrome/"><u>Mastering Video Streams: Fix YouTube Lag in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-recovering-lost-settings-from-nvidia-control-center/"><u>Methods for Recovering Lost Settings From NVidia Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-icloud-download-challenges-on-pc/"><u>Overcoming iCloud Download Challenges on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-challenge-of-a-nonfunctional-coprocessor-module-for-windows-10-users-solutions-unveiled/"><u>Overcoming the Challenge of a Nonfunctional Coprocessor Module for Windows 10 Users – Solutions Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/override-unmet-system-conditions-indicator-in-win11/"><u>Override Unmet System Conditions Indicator in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-missing-window-panes-in-windows-11-6-tactics/"><u>Reinstating Missing Window Panes in Windows 11 (6 Tactics)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steam-not-online-quick-fixes-for-windows-users/"><u>Steam Not Online? Quick Fixes for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-dependencies-using-wpm-effectively/"><u>Streamlining Dependencies: Using WPM Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-qt-initialization-unsuccessful-in-dev-environment/"><u>Tackling Qt Initialization Unsuccessful in Dev Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-10-store-errors-a-quick-guide/"><u>Tackling Windows 10 Store Errors: A Quick Guide</u></a></li>
<li><a href="https://some-tips.techidaily.com/ultimate-guide-to-android-photo-fixes-for-2024/"><u>Ultimate Guide to Android Photo Fixes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-optimal-performance-by-taming-high-cpu-demands/"><u>Unleashing Optimal Performance by Taming High CPU Demands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-win11-potential-with-devhome-exploration/"><u>Unlocking Win11 Potential with DevHome Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-dont-retrofit-old-pcs-without-windows/"><u>Update, Don't Retrofit: Old PCs without Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-computers-clock-display-top-5-dynamic-windows-clock-screensavers-using-these-apps/"><u>Upgrade Your Computer’s Clock Display: Top 5 Dynamic Windows Clock Screensavers Using These Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-github-desktop-efficiently-on-windows-11-pro/"><u>Utilizing GitHub Desktop Efficiently on Windows 11 Pro</u></a></li>
</ul></div>
