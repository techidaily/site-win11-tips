---
title: Elevate Controls in Windows 11'S UI Amenities
date: 2024-08-08T11:05:22.212Z
updated: 2024-08-09T11:05:22.212Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Elevate Controls in Windows 11'S UI Amenities
excerpt: This Article Describes Elevate Controls in Windows 11'S UI Amenities
keywords: WinUI Elevation,UI Enhancements,Windows 11 UI,Control Features,Interface Improvement,User Experience (UX) Upgrade,Modern Windows Amenities
thumbnail: https://thmb.techidaily.com/7e858d7102e5ef6f6137f0acdeeba112d7b0daf0c9e0dad5ba4b3979a33bb860.jpg
---

## Elevate Controls in Windows 11'S UI Amenities

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
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
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

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-bridging-the-visibility-gap-for-online-media/"><u>[New] 2024 Approved  Bridging the Visibility Gap for Online Media</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-snapchat-enhancing-images-and-videos/"><u>[New] Mastering Snapchat  Enhancing Images & Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-modify-mac-screen-shot-storage-path/"><u>[Updated] 2024 Approved  Modify Mac Screen Shot Storage Path</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1716068821354-updated-in-2024-best-free-android-capture-app-zero-ads/"><u>[Updated] In 2024, Best Free Android Capture App, Zero Ads!</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-integrating-clips-flawlessly-using-blend-modes-for-2024/"><u>[Updated] Integrating Clips Flawlessly Using Blend Modes for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-strategies-for-capturing-high-quality-periscope-broadcasts/"><u>[Updated] Strategies for Capturing High-Quality Periscope Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-fix-strategies-for-your-windows-resolution-dilemmas/"><u>10 Fix Strategies for Your Windows Resolution Dilemmas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-remote-desktop-connection-tool-in-windows-11/"><u>10 Ways to Open the Remote Desktop Connection Tool in Windows 11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-assessing-daily-video-consumption-in-gb-units/"><u>2024 Approved  Assessing Daily Video Consumption in GB Units</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-navigating-through-instagram-video-hiccups/"><u>2024 Approved  Navigating Through Instagram Video Hiccups</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-t-series-youtube-revenue-an-overview/"><u>2024 Approved  T-Series YouTube Revenue  An Overview</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-the-enhanced-samsung-k850u-experience/"><u>2024 Approved  Unveiling the Enhanced Samsung K850U Experience</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-realme-note-50-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Realme Note 50 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-critical-tweaks-to-reactivate-firewall/"><u>4 Critical Tweaks to Reactivate Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-window-updates-that-left-old-traits-behind/"><u>6 Window Updates That Left Old Traits Behind</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-a-missing-bluetooth-option-in-windows-11/"><u>9 Ways to Fix a Missing Bluetooth Option in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-complete-guide-to-oem-unlocking-on-samsung-galaxy-a15-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenas-for-conquering-windows-10-bsod-woes/"><u>A Compreenas for Conquering Windows 10 BSOD Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simple-guide-to-windows-11-home-interface-activation/"><u>A Simple Guide to Windows 11 Home Interface Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-power-up-window-10-and-11-with-keybinds/"><u>Accelerate Tasks: Power-Up Window 10 and 11 with Keybinds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-day-windows-productivity-software-that-works-wonders/"><u>Ace Your Day: Windows Productivity Software That Works Wonders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-way-through-windows-with-mouseclicklock-techniques/"><u>Ace Your Way Through Windows with MouseClickLock Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-balanced-screen-viewing-a-step-by-step-guide-to-90-degree-rotation/"><u>Achieving Balanced Screen Viewing: A Step-by-Step Guide to 90-Degree Rotation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-excellence-perfecting-your-consoles-gamepad-functionality/"><u>Achieving Excellence: Perfecting Your Console's Gamepad Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-the-speaker-in-microsofts-new-era/"><u>Activating the Speaker in Microsoft's New Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-resolving-msvcr110dll-lack/"><u>Addressing and Resolving MSVCR110.dll Lack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-discords-non-display-errors-on-pc/"><u>Addressing Discord's Non-Display Errors on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-access-dilemnas-on-windows-os/"><u>Addressing File Access Dilemnas on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inconsistent-thx-sound-on-pcs/"><u>Addressing Inconsistent THX Sound on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-inaccessibility-of-roblox-due-to-user-settings-in-windows/"><u>Addressing the Inaccessibility of Roblox Due to User Settings in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-isdonedll-issue-on-w11-and-11x-systems/"><u>Addressing the ISDone.dll Issue on W11 & 11X Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-update-problem-windows-11-error-code-0x800f0922/"><u>Addressing Update Problem: Windows 11 Error Code 0X800f0922</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-wsl-registration-failure-error-x80370102-fix-guide/"><u>Addressing WSL Registration Failure - Error X80370102 Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-lockout-interval-after-unsuccessful-windows-sign-in/"><u>Adjusting Lockout Interval After Unsuccessful Windows Sign In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-taskbar-size-step-by-step-guide/"><u>Altering Taskbar Size: Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/avoid-common-mistakes-expert-advice-on-choosing-the-best-selfie-stick/"><u>Avoid Common Mistakes: Expert Advice on Choosing the Best Selfie Stick</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-pitfalls-in-ad-ds-printer-issues-windows-1011/"><u>Avoiding Common Pitfalls in AD DS Printer Issues, Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-errors-secure-your-onedrive-login-on-windows/"><u>Avoiding Errors: Secure Your OneDrive Login on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-system-conquering-power-save-errors/"><u>Awaken Your System: Conquering Power Save Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-not-recognized-issues-in-windows-with-these-fixes/"><u>Banish 'Not Recognized' Issues in Windows with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-win11-blue-screen-quick-fixes-for-your-pc-top-11/"><u>Banish Win11 Blue Screen: Quick Fixes for Your PC (Top 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-windows-media-player-activation-process/"><u>Beginning Windows Media Player Activation Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bigger-better-barely-noticed-by-mini-pcs-users/"><u>Bigger, Better Barely Noticed by Mini PCs' Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-windows-excellence-into-macos-benefits/"><u>Blending Windows Excellence Into macOS Benefits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blue-screen-errors-finding-their-windows-footprint/"><u>Blue Screen Errors: Finding Their Windows Footprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-easy-group-policy-navigation-in-win11/"><u>Boost Productivity with Easy Group Policy Navigation in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-keystrokes-speed-top-tips-to-decrease-delay-on-windows/"><u>Boost Your Keystrokes' Speed: Top Tips to Decrease Delay on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-print-output-speedy-windows-printer-tips/"><u>Boosting Print Output: Speedy WIndows Printer Tips</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-a-viral-hit-10-best-music-video-producers-for-2024/"><u>Create a Viral Hit 10 Best Music Video Producers for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-and-the-metaverse-an-in-depth-analysis/"><u>Facebook & The Metaverse: An In-Depth Analysis</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-oppo-reno-8t-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Oppo Reno 8T? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-everything-from-apple-iphone-14-plus-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer Everything from Apple iPhone 14 Plus to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-use-special-features-virtual-location-on-poco-x5-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Poco X5? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-oneplus-12-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On OnePlus 12? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-essential-gamer-perks-lowest-priced-monitors-and-keyboards/"><u>In 2024, Essential Gamer Perks  Lowest Priced Monitors & Keyboards</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-sony-xperia-5-v-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Sony Xperia 5 V Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-future-of-cloud-storages-top-picks-to-consider/"><u>In 2024, The Future of Cloud Storages  Top Picks to Consider</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/is-this-a-pigeon-meme-generator/"><u>Is This a Pigeon Meme Generator</u></a></li>
<li><a href="https://extra-skills.techidaily.com/key-top-5-agile-camcorders-for-adventure-selections-for-2024/"><u>Key Top 5 Agile Camcorders for Adventure Selections for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-the-virtual-cityscape-cyberpunk-2077s-smoothed-fps-experience/"><u>Mastering the Virtual Cityscape: Cyberpunk 2077'S Smoothed FPS Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292218138-quicker-downloads-for-battlenet-games-win-pcs-now/"><u>Quicker Downloads for Battle.net Games, Win PCs Now!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/scheduling-zoom-conferences-for-android-users-for-2024/"><u>Scheduling Zoom Conferences for Android Users for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitcast-audible-and-mp4-edition/"><u>TwitCast  Audible & MP4 Edition</u></a></li>
<li><a href="https://extra-tips.techidaily.com/youtube-tunes-integration-with-visual-content/"><u>YouTube Tunes Integration with Visual Content</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>