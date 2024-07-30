---
title: Bringing Back Original Settings to Windows 11 Touch Panel
date: 2024-07-29T08:13:37.998Z
updated: 2024-07-30T08:13:37.998Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bringing Back Original Settings to Windows 11 Touch Panel
excerpt: This Article Describes Bringing Back Original Settings to Windows 11 Touch Panel
keywords: Win11 Original Panels,Revive Windows Tiles,Nostalgic Window Settings,Redesign W11 Display,Restore Windows Touch Panel,Classic Windows UI Update,Echoed Windows Features
thumbnail: https://thmb.techidaily.com/cb769af3708fc15b594c9ede31a115d7b902d54d4fbcec56dcebaeb9d186f784.jpg
---

## Bringing Back Original Settings to Windows 11 Touch Panel

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to[create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a[backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## 2\. Run a Batch File to Reset the Touch Keyboard's Default Open Position

 Resetting the default opening position of your touch keyboard can be done quickly and easily by running a batch file. This method is especially useful if you prefer to automate the reset process instead of manually tweaking the registry editor. Here is how to do it.

 To get started, you first need to open the Notepad application. For this, you can type "Notepad" in either Windows Search or the Run dialog box and press**Enter** .

 Once you're in Notepad, copy and paste the following code into it:

`@echo off  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeXPositionOnScreen /F  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeYPositionOnScreen /F  
taskkill /f /im explorer.exe  
start explorer.exe`

 Now click**File** in the upper-left corner and select**Save As** from the menu list.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Resetting the Default Position of the Touch Keyboard

 If you're using a Windows touchscreen device, typing with a touch keyboard can be easy. However, you might have noticed an inconvenience where the keyboard opens in an awkward position.

 This can make typing on specific keys difficult, especially if you're used to accessing the keyboard from a certain spot. To fix this issue, refer to this guide on resetting the default open position of your touch keyboard.


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
<li><a href="https://facebook-videos.techidaily.com/new-how-to-maximize-revenue-the-secret-of-fb-animation-campaigns/"><u>[New] How to Maximize Revenue  The Secret of FB Animation Campaigns</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-io-screen-recorder-user-manual-overview/"><u>[New] In 2024, IO Screen Recorder User Manual Overview</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-step-by-step-strategy-for-profiting-from-every-youtube-short-video/"><u>[New] Step-by-Step Strategy for Profiting From Every YouTube Short Video</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-streamlining-media-transfer-twitter-content-on-snapchat-for-2024/"><u>[New] Streamlining Media Transfer  Twitter Content on Snapchat for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-perfect-your-asmr-recordings-with-these-mic-choices/"><u>[Updated] In 2024, Perfect Your ASMR Recordings with These Mic Choices</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-your-guide-to-free-non-networked-android-games/"><u>[Updated] In 2024, Your Guide to Free, Non-Networked Android Games</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-bass-brilliance-new-device-overview/"><u>2024 Approved  Bass Brilliance  New Device Overview</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-integrating-external-websites-into-instagrams-ecosystem/"><u>2024 Approved  Integrating External Websites Into Instagram's Ecosystem</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-simple-guide-turning-favorite-tiktok-beats-into-cellphone-signals/"><u>2024 Approved  Simple Guide  Turning Favorite TikTok Beats Into Cellphone Signals</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-troubleshooting-the-windows-camera-app/"><u>A Complete Guide to Troubleshooting the Windows Camera App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-and-utilizing-widgets-in-windows-11/"><u>Accessing and Utilizing Widgets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-assault-fixing-lags-for-pc-warriors/"><u>Ace Your Assault: Fixing Lags for PC Warriors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-as-a-windows-vr-device/"><u>Adapting Oculus Quest 2 as a Windows VR Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-side-by-side-error-corrective-techniques-for-win10/"><u>Addressing Side-by-Side Error: Corrective Techniques for Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-desktop-icon-chaos-in-windows/"><u>Avoid Desktop Icon Chaos in Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bios-update-error-22-settled/"><u>BIOS Update: Error 22 Settled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-experience-our-criteria-for-best-free-drivers/"><u>Boost Your Windows Experience: Our Criteria for Best Free Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-boot-routine-secrets/"><u>Breaking Down Windows Boot Routine Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brilliant-obsidian-structure-for-clear-notes/"><u>Brilliant Obsidian Structure for Clear Notes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/capturing-perfect-sounds-our-top-6-recommendations-for-livestreamers-for-2024/"><u>Capturing Perfect Sounds  Our Top 6 Recommendations for Livestreamers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-microsoft-office-error-0x80041015-a-fix-guide/"><u>Conquering Microsoft Office Error 0X80041015: A Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-your-perfect-reading-experience-notepad-customization-in-windows-11/"><u>Creating Your Perfect Reading Experience: Notepad Customization in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-obscured-network-visibility-in-windows/"><u>Curing Obscured Network Visibility in Windows</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-itools-virtual-location-not-work-on-apple-iphone-seipad-drfone-by-drfone-virtual-ios/"><u>Does iTools virtual location not work On Apple iPhone SE/iPad? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-breakdown-windows-saver-dynamics/"><u>Expert Breakdown: Windows Saver Dynamics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-java-vm-not-found-issue-on-windows-devices/"><u>Fixing Java VM Not Found Issue on Windows Devices</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-oneplus-11r-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on OnePlus 11R 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/growth-in-the-grove-top-7-stardew-valley-addons-for-2024/"><u>Growth in the Grove  Top 7 Stardew Valley Addons for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Infinix Hot 40 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-deal-with-imminent-license-expiry-on-your-pc/"><u>How to Deal with Imminent License Expiry on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-unrealcefsubprocess-high-cpu-and-ram-usage-on-windows/"><u>How to Fix the UnrealCEFSubprocess High CPU and RAM Usage on Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-x50-phone-without-pin-by-drfone-android/"><u>How to Unlock Honor X50 Phone without PIN</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-tecno-pova-5-pro-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-samsung-galaxy-f54-5g-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Samsung Galaxy F54 5G without App | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-accelerate-your-contents-view-count-1kplus-in-time/"><u>In 2024, Accelerate Your Content's View Count  1K+ in Time</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-vivo-t2-5g-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Vivo T2 5G Without PUK Codes</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-the-screen-recorders-journey-a-deep-dive-into-the-best-tools/"><u>In 2024, The Screen Recorder's Journey  A Deep Dive Into the Best Tools</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-samsung-galaxy-z-flip-5-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Samsung Galaxy Z Flip 5 Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-machine-prepared-to-run-newest-windows-os/"><u>Is Your Machine Prepared to Run Newest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterpiece-ahead-initiating-mspaint-windows-11-style/"><u>Masterpiece Ahead: Initiating MSPaint, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-cursor-visibility-on-win-11-a-guide/"><u>Maximizing Cursor Visibility on Win 11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-visibility-unveiling-windows-11s-system-tray-and-hidden-items/"><u>Maximizing Visibility: Unveiling Windows 11'S System Tray & Hidden Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/momentum-builds-with-windows-11s-upcoming-feature-unveil/"><u>Momentum Builds with Windows 11’S Upcoming Feature Unveil</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-shift-whats-updated-in-windows-11/"><u>Navigating the Shift: What's Updated in Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fixed-bluetooth-pairing-error-in-win-os/"><u>Quick Guide to Fixed: Bluetooth Pairing Error in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-ignoring-license-expires-messages-in-win11/"><u>Quick Tips: Ignoring ‘License Expires’ Messages in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-the-windows-indexer-a-quick-guide/"><u>Restarting the Windows Indexer: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-the-hidden-search-bar-in-win11s-task-manager/"><u>Revealing the Hidden Search Bar in Win11's Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-workflow-why-the-latest-windows-outlook-matters/"><u>Revolutionize Your Workflow: Why the Latest Windows' Outlook Matters</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-m34-5g-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy M34 5G Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-turning-onoff-secure-boot-in-virtualbox/"><u>Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-starting-spotify-by-default/"><u>Stop Windows From Starting Spotify by Default</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-virtual-disk-error-handling-in-windows-systems/"><u>Streamlining Virtual Disk Error Handling in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-performance-replacing-aged-technology/"><u>Streamlining Windows Performance: Replacing Aged Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-your-snaps-with-these-6-steps-for-windows-11-users/"><u>Swivel Your Snaps with These 6 Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-dolby-atmos-installation-in-windows/"><u>The Essential Checklist for Dolby Atmos Installation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-cutting-the-fat-in-windows-11/"><u>The Ultimate Guide to Cutting the Fat in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-library-accessibility-on-win-11-pcs/"><u>Troubleshooting Steam Library Accessibility on Win 11 PCs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-audio-compilations-for-video-production-for-2024/"><u>Ultimate Audio Compilations for Video Production for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-difference-between-time-lapse-and-hyperlapse-for-2024/"><u>Updated Difference Between Time Lapse and Hyperlapse for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-design-your-own-unique-pin-pattern/"><u>Windows 10/11 Hack: Design Your Own Unique Pin Pattern</u></a></li>
<li><a href="https://extra-hints.techidaily.com/your-journey-to-flawless-video-subtitling-essential-digital-aids-listed/"><u>Your Journey to Flawless Video Subtitling  Essential Digital Aids Listed</u></a></li>
</ul></div>
