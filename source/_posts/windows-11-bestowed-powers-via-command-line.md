---
title: "Windows 11: Bestowed Powers via Command Line"
date: 2024-08-23T06:58:36.385Z
updated: 2024-08-24T06:58:36.385Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Bestowed Powers via Command Line"
excerpt: "This Article Describes Windows 11: Bestowed Powers via Command Line"
keywords: Windows 11 CLI,PowerCmdWin11,Win11CommandOpt,Windows 11 CmdLimits,Win11PowerOptions,CMDWin11Enhancements,CLIWindowsUpgrade
thumbnail: https://thmb.techidaily.com/5a612b69f151ee0b6ea165a5e0a8368a6294f13aca50623658d8bbb7241b81d0.jpg
---

## Windows 11: Bestowed Powers via Command Line

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

## How to Add God Mode to the Context Menu by Manually Editing the Registry

 You can add God Mode to Windows 11’s desktop context menu by manually tweaking the registry. The tweaking required is relatively simple to apply and involves adding a couple of new registry entries to the Shell key. Follow these steps to manually add God Mode to Windows 11’s context menu:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Click in the address bar at the top of Registry Editor to delete the current key location.
3. Input this Shell key path in the address bar and hit **Enter**:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Right-click on **Shell** in Registry Editor’s navigation sidebar to select **New** and **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/new-key-options.jpg)
5. Type **God Mode** in the key’s text box.

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.
4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.
5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/waying-scripts-an-introduction-to-bouncy-text-animations/"><u>[New] Swaying Scripts  An Introduction to Bouncy Text Animations</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-your-gateway-to-classic-games-best-in-class-5gb-advance-emulators-compatible-with-pcs-for-2024/"><u>[New] Your Gateway to Classic Games  Best-in-Class 5GB Advance Emulators Compatible with PCs for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-top-rated-screen-recorders-on-windows-and-macos-unveiled/"><u>[Updated] 2024 Approved  Top-Rated Screen Recorders on Windows & macOS Unveiled</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-capture-your-best-moments-top-8-mirrorless-cameras-for-you/"><u>[Updated] Capture Your Best Moments  Top 8 Mirrorless Cameras For You</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-establishing-a-unique-code-for-your-tiktok-presence/"><u>[Updated] In 2024, Establishing a Unique Code for Your TikTok Presence</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-unpacking-tunefab-written-review-on-latest-tech-for-screen-recording/"><u>[Updated] In 2024, Unpacking Tunefab' Written Review on Latest Tech for Screen Recording</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-polaroid-cubeplus-action-camera-review/"><u>[Updated] Polaroid Cube+ Action Camera Review</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>10 Best Fake GPS Location Spoofers for Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-tips-for-crafting-an-engaging-fb-timeline-memory/"><u>2024 Approved  Tips for Crafting an Engaging FB Timeline Memory</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-with-people-virtually-the-power-of-facebook-twitter-instagram-and-youtube/"><u>Connecting with People Virtually: The Power of Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtail-extra-audio-boost-in-windows/"><u>Curtail Extra Audio Boost in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/decreasing-decibents-deliberately-logic-pros-volume-techniques/"><u>Decreasing Decibents Deliberately  Logic Pro's Volume Techniques</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/effective-solutions-to-resolve-windows-1n-hypervisor-bsod-issues-tips-and-tricks-for-users/"><u>Effective Solutions to Resolve Windows 1N Hypervisor BSoD Issues: Tips and Tricks for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-workflow-with-process-management-and-aesthetic-overhaul-in-w11/"><u>Elevate Workflow with Process Management & Aesthetic Overhaul in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-geforce-nows-xc0f1103f-hitch-in-windows-11/"><u>Eliminate GeForce Now's Xc0f1103f Hitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-chromiums-network-access-over-windows-security-barrier/"><u>Enabling Chromium's Network Access Over Windows Security Barrier</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-to-correct-error-code-0xc00aturate-issues-in-black-ops-cold-war-gameplay/"><u>Expert Advice to Correct Error Code 0Xc00aturate Issues in Black Ops: Cold War Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/express-guide-to-determine-windows-11-gpu-variant/"><u>Express Guide to Determine Windows 11 GPU Variant</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-the-most-out-of-windows-backup-features/"><u>Get the Most Out of Windows Backup Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-portable-software-menu-to-windows-11-and-11/"><u>How to Add a Portable Software Menu to Windows 11 & 11</u></a></li>
<li><a href="https://article-posts.techidaily.com/how-to-control-your-airpods-connection-and-stop-auto-pairing-with-different-iphonesipados/"><u>How to Control Your AirPods' Connection and Stop Auto-Pairing with Different iPhones/iPadOS</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-motorola-edge-2023-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Motorola Edge 2023 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Tecno Camon 20 Premier 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-screen-flickering-and-flashing-on-windows-10-and-11/"><u>How to Fix Screen Flickering and Flashing on Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-optimize-windows-storage-spotting-large-disk-usage/"><u>How to Optimize Windows Storage: Spotting Large Disk Usage</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-oneplus-nord-n30-5g-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of OnePlus Nord N30 5G on Mac?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-samsung-galaxy-m14-4g-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Samsung Galaxy M14 4G</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-oppo-reno-10-pro-5g-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Oppo Reno 10 Pro 5G</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-turning-off-two-factor-authentication-on-iphone-xs-5-tips-you-must-know-by-drfone-ios/"><u>In 2024, Turning Off Two Factor Authentication On iPhone XS? 5 Tips You Must Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-11-ways-to-open-control-panel/"><u>Master Your Machine: 11 Ways to Open Control Panel</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/mp4mpeg-audio-extraction-tool/"><u>MP4/MPEG Audio Extraction Tool</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-through-gopro-models-and-specifications/"><u>Navigating Through GoPro Models & Specifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-win-11-experience-game-changing-advice-for-the-winning-side/"><u>Optimizing Your Win 11 Experience: Game-Changing Advice for the Winning Side</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-secure-authentication-problems-with-the-epic-launcher/"><u>Overcoming Secure Authentication Problems with the Epic Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bing-chat-integration-in-windows-11/"><u>Quick Guide to Bing Chat Integration in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-outlook-responses-a-windows-fix-guide/"><u>Quick Outlook Responses: A Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-reviving-a-sluggish-windows-11-experience/"><u>Quick Tips: Reviving a Sluggish Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revival-tactics-restoring-microsoft-store-on-win-11-and-11/"><u>Revival Tactics: Restoring Microsoft Store on Win 11 & 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/screensnap-it-all-high-quality-netflix-on-mac/"><u>ScreenSnap It All  High-Quality Netflix on Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-syncopation-combining-dropbox-and-googledrive-driveletters/"><u>Simplifying Syncopation: Combining Dropbox and GoogleDrive DriveLetters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-setups-mastering-the-invisible-menu-features/"><u>Stealthy Setups: Mastering the Invisible Menu Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reduce-windows-browser-process-count/"><u>Steps to Reduce Windows' Browser Process Count</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-fingerprint-scanner-unsupported-problems/"><u>Steps to Resolve 'Fingerprint Scanner Unsupported' Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-commence-quickly-open-windows-and-sticky-notes/"><u>Streamlined Commence: Quickly Open Windows and Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-qr-code-processes-with-windows-os/"><u>Streamlining QR Code Processes with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-real-deal-on-applecareplus-does-the-extra-security-make-financial-sense/"><u>The Real Deal on AppleCare+ – Does the Extra Security Make Financial Sense?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-automated-file-deletion-on-windows/"><u>The Ultimate Guide to Automated File Deletion on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timeless-traits-windows-11s-retained-7-classic-characteristics/"><u>Timeless Traits: Windows 11'S Retained 7 Classic Characteristics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-enhancing-productivity-using-wsl-2/"><u>Top Strategies: Enhancing Productivity Using WSL 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-to-emulate-macos-the-top-5-approaches/"><u>Transforming Windows to Emulate macOS: The Top 5 Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-modern-standby-a-critical-analysis/"><u>Unveiling Modern Standby: A Critical Analysis</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-intel-drivers-for-windows-when-and-how/"><u>Update Intel Drivers for Windows (When And How)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgraded-performance-ahead-steps-to-amplify-virtual-memory-in-windows-11/"><u>Upgraded Performance Ahead: Steps to Amplify Virtual Memory in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-should-i-do-if-i-cant-upgrade-my-pc-to-windows-11/"><u>What Should I Do If I Can't Upgrade My PC to Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-if-windows-wont-show-notification-badges-on-taskbar-icons/"><u>What to Do if Windows Won’t Show Notification Badges on Taskbar Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-warning-signs-is-a-restart-needed/"><u>Windows Warning Signs: Is a Restart Needed?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-live-streaming-intel-graphics-recording-tips/"><u>Winning at Live Streaming: Intel Graphics Recording Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>