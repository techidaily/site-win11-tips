---
title: Adjust Touch Keyboard Default in Windows 11 Pro
date: 2024-08-08T10:56:30.573Z
updated: 2024-08-09T10:56:30.573Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust Touch Keyboard Default in Windows 11 Pro
excerpt: This Article Describes Adjust Touch Keyboard Default in Windows 11 Pro
keywords: Win11 Keyboard Adjust,Default Keyboard Set,Change Touch Keys,Windows Touch Settings,Keyboard Config W11,Pro Windows Keyboard Adj,Update Touch Key Prefs
thumbnail: https://thmb.techidaily.com/44cba3f77a25fb10a15058a95ecd605b31dd154fe2d91aae028e5e688022e444.jpg
---

## Adjust Touch Keyboard Default in Windows 11 Pro

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a [backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-the-power-of-personal-branding-in-making-money-on-snapchat/"><u>[New] 2024 Approved  The Power of Personal Branding in Making Money on Snapchat</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-insta-velocity-strategic-use-of-likes-and-videos-for-growth-for-2024/"><u>[New] Insta Velocity  Strategic Use of Likes & Videos for Growth for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-online-converter-turn-facebook-vids-into-mp3/"><u>[New] Online Converter  Turn Facebook Vids Into MP3</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-should-you-keep-previewing-fb-activity-visible-insights/"><u>[New] Should You Keep Previewing FB Activity Visible? Insights</u></a></li>
<li><a href="https://youtube-web.techidaily.com/he-art-of-youtube-editing-a-compreenasive-guidebook/"><u>[New] The Art of YouTube Editing  A Compreenasive Guidebook</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-screenplay-scribblers-hub/"><u>[New] Top Screenplay Scribblers Hub</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-cut-beyond-youtube-unveiling-the-top-5-video-editor-options-for-2024/"><u>[Updated] Cut Beyond Youtube  Unveiling the Top 5 Video Editor Options for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-elevate-your-zoom-experience-syncing-speakers-and-microphones/"><u>[Updated] Elevate Your Zoom Experience  Syncing Speakers & Microphones</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-enhancing-youtube-content-with-text-overlays/"><u>[Updated] In 2024, Enhancing YouTube Content with Text Overlays</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-tiktok-greats-on-snapchat-screen-time/"><u>[Updated] In 2024, TikTok Greats on Snapchat Screen Time</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-price-point-in-online-advertising/"><u>[Updated] The Price Point in Online Advertising</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-top-virtual-recording-tools-online/"><u>[Updated] Top Virtual Recording Tools Online</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-unwind-in-a-world-of-top-stress-busters/"><u>[Updated] Unwind in a World of Top Stress Busters</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-oppo-find-x7-ultra-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Oppo Find X7 Ultra Activity | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-apple-iphone-12-pro-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your Apple iPhone 12 Pro for Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-steps-to-wipe-your-drives-partitions-in-windows/"><u>4 Easy Steps to Wipe Your Drive's Partitions in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-oppo-a58-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-tecno-spark-20c-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Tecno Spark 20C</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/adding-visual-variety-to-instagram-stories-step-by-step/"><u>Adding Visual Variety to Instagram Stories Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-be-registered-error-a-windows-photos-guide/"><u>Addressing 'Could Not Be Registered' Error: A Windows Photos Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-of-error-80080300-a-guide-to-enhanced-teamwork-on-windows/"><u>Breaking Barriers of Error 80080300: A Guide to Enhanced Teamwork on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-dxgierror-with-device-reattachment/"><u>Combat DXGI_ERROR with Device Reattachment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-and-configuring-your-win11-screensavers/"><u>Crafting and Configuring Your Win11 Screensavers</u></a></li>
<li><a href="https://facebook.techidaily.com/earning-through-connections-social-platforms-income/"><u>Earning Through Connections: Social Platforms' Income</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-regain-onedrive-entry-points-in-windows/"><u>Effortlessly Regain OneDrive Entry Points in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-self-closure-in-windows-os/"><u>Eliminating Self-Closure in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-in-windows-11-notepad/"><u>Enhancing User Experience in Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-the-prospects-why-choose-win11-over-macos/"><u>Examining the Prospects: Why Choose Win11 Over MacOS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/expert-tips-for-enhancing-ppts-with-auditory-content/"><u>Expert Tips for Enhancing PPTs with Auditory Content</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-y36i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-vivo-y27s-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Vivo Y27s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-background-apps-in-windows-11/"><u>How to Disable Background Apps in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-tecno-spark-20-proplus-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-nokia-xr21-by-fonelab-android-recover-video/"><u>How to restore wiped videos on Nokia XR21</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-device-functionality-in-win11-sleep-mode/"><u>How to Revive Device Functionality in Win11 Sleep Mode?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-xr-apples-new-iphone-by-drfone-ios/"><u>How to Unlock Apple iPhone XR, Apples New iPhone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-12plus-5g-phone-without-google-account-by-drfone-android/"><u>How to Unlock Realme 12+ 5G Phone without Google Account?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-free-camera-screen-recorders-deep-dive-review-and-top-alternatives/"><u>In 2024, Free Camera Screen Recorders  Deep Dive Review and Top Alternatives</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-oneplus-11r-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from OnePlus 11R to Another | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-visionarys-manual-selecting-the-most-compelling-4k-displays-today/"><u>In 2024, The Visionary's Manual  Selecting the Most Compelling 4K Displays Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-user-profile-control-with-cmd/"><u>In-Depth Analysis of User Profile Control with CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-power-off-windows-11-when-not-in-use/"><u>Instantly Power Off Windows 11 When Not in Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-data-organization-optimize-your-win11-hdd/"><u>Mastering Data Organization: Optimize Your Win11 HDD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-aligning-sticky-notes-in-w11/"><u>Mastering the Art of Aligning Sticky Notes in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-task-runner-error-code-0x8007000f-in-winos/"><u>Mastery over Task Runner Error Code 0X8007000f in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-unsetting-personalized-search-on-windows-11-os/"><u>Methods for Unsetting Personalized Search on Windows 11 OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/motorola-edgeplus-2023-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Motorola Edge+ (2023) Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-boot-up-a-guide-to-startup-service-management/"><u>Navigate Through Windows Boot-Up: A Guide to Startup Service Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-pc-protection-limiting-multiple-antiviruses/"><u>Optimal PC Protection: Limiting Multiple Antiviruses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-zip-file-errors-a-win-11-remedy-plan/"><u>Overcoming Zip File Errors: A Win 11 Remedy Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-failed-retrieval-error-with-geforce-x/"><u>Quick Fixes for Failed Retrieval Error with GeForce X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11-troubleshooters-for-optimal-performance/"><u>Realigning Windows 11 Troubleshooters for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-overhead-memory-usage-by-malware-detectors/"><u>Reducing Overhead Memory Usage by Malware Detectors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-sudden-device-disconnection-dxgi/"><u>Remedy for Sudden Device Disconnection (DXGI)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-steam-gaming-glory-a-how-to-manual/"><u>Reviving Lost Steam Gaming Glory: A How-To Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-quest-preventing-crashes-on-your-pcs-platform/"><u>Securing Your Quest: Preventing Crashes on Your PC's Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-address-failed-lunar-client-startup-errors/"><u>Solutions to Address Failed Lunar Client Startup Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-windows-issue-file-explorer-failsafe-mode/"><u>Solve Windows Issue: File Explorer Failsafe Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-curb-energy-drain-while-playing-games-on-pc/"><u>Strategies to Curb Energy Drain While Playing Games on PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/surging-through-the-noise-supercharging-telegram-campaigns/"><u>Surging Through the Noise  Supercharging Telegram Campaigns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-for-windows-11s-0x8004def5-glitches/"><u>Swift Solutions for Windows 11'S 0X8004DEF5 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-notes-no-downloads-windows-11-secrets/"><u>Take Notes, No Downloads: Windows 11 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-web-pages-to-desktop-level-with-windows-guide/"><u>Taking Web Pages to Desktop Level with Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-keep-microsoft-teams-from-crashing-win11-win10/"><u>Tips to Keep Microsoft Teams From Crashing Win11, Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-win-11-with-confident-system-setup/"><u>Transitioning to Win 11 with Confident System Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unidentified-devices-on-windows-1011/"><u>Troubleshooting Unidentified Devices on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-using-dark-theme-in-notepad/"><u>Understanding and Using Dark Theme in Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-winexe-creation-from-batch-scripts/"><u>Unveiling WinEXE Creation From Batch Scripts</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Infinix GT 10 Pro? | Dr.fone</u></a></li>
</ul></div>
