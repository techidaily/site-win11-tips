---
title: "Feature: Context Menu Alert for Windows Updates in Win11+11"
date: 2024-08-16T01:22:12.133Z
updated: 2024-08-17T01:22:12.133Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Feature: Context Menu Alert for Windows Updates in Win11+11"
excerpt: "This Article Describes Feature: Context Menu Alert for Windows Updates in Win11+11"
keywords: Win11 Update Notifier,Win11+Update Alert,Contextual Windows Update Alert,Update Notification Win11,Quick Updates Feature,Modern Win11 Alerts,Real-Time Windows Update Info
thumbnail: https://thmb.techidaily.com/08c04182a5370a9894bbb7d5aedb620a94eb3a5d17a6c123fae986b1d0cc282e.jpg
---

## Feature: Context Menu Alert for Windows Updates in Win11+11

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
![The Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/key-option.png)

1. Type **Check for Updates** to be the new key’s name.
2. Right-click the **Check for Updates** key and select **New** on the context menu.
3. Click the **Key** option again.
4. Now input **command** for the new key’s name.
5. Select the **Check for Updates** key, and then right-click a space on the right side of the Registry Editor to select **New > String Value**.  
![The String Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/string-value-option.png)

1. Type **SettingsURI** to be the new string’s name.
2. Double-click **SettingsURI** to open an Edit String window.
3. Type **ms-settings:windowsupdate-action** within the Value data box, and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edit-string-window.png)
4. Right-click the **command** key and select the **New** \> **String Value** options.
5. Enter the string title **DelegateExecute**, and press the **Return** key.  
![The DelegateExecute string for the command key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/delegateexecute_string.png)
6. Double-click the **DelegateExecute** string to bring up its Value data box.
7. Type **{556FF0D6-A1EE-49E5-9FA4-90AE116AD744}** in the Value data text box, and press the **OK** button.
8. Close the Registry Editor’s window.

 Now right-click an area of your Windows 11 desktop and select **Show more options** to bring up the classic context menu. If you’ve edited the registry correctly, that menu will include a **Check for Updates** option. Select that option to open Settings’ **Windows Update** tab. Then you can click the **Check for updates** button on that tab.

![The Check for Updates context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check-for-updates-context-menu-option.png)

 Alternatively, press the **Shift** + **F10** hotkey to bring up the classic context menu without right-clicking the desktop. That keyboard shortcut opens the classic context menu at the top left of the desktop. Then you can select **Check for Updates** from there to bring up the tab shown below.

![The Windows Update tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check_for_updates_button.png)

 This registry trick works much the same on Windows 10\. The only difference is that you won’t need to select **Show more options**. As Windows 10’s desktop context menu is the classic one, it doesn’t include **Show more options**. You can select **Check for Updates** on its primary context menu.

 If you ever want to remove the **Check for Updates** shortcut from the context menu, open the **Shell** key in the Registry Editor again. Then right-click the **Check for Updates** key to select **Delete**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-bend-the-rules-of-livestreaming-on-youtube-without-a-subscriber-hurdle/"><u>[New] Bend the Rules of Livestreaming on YouTube, Without a Subscriber Hurdle</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-covert-videography-the-premier-8-downloader-list/"><u>[New] Covert Videography  The Premier 8 Downloader List</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-the-ultimate-guide-to-delete-social-media-streaming/"><u>[New] In 2024, The Ultimate Guide to Delete Social Media Streaming</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-hidden-dangers-of-high-follower-bloat-avoidance-tactics/"><u>[New] The Hidden Dangers of High-Follower Bloat  Avoidance Tactics</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-effortless-sound-capture-top-5-techniques-for-web-streaming/"><u>[Updated] Effortless Sound Capture  Top 5 Techniques for Web Streaming</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-creating-music-from-videos-instagrams-secret-sauce/"><u>[Updated] In 2024, Creating Music From Videos  Instagram's Secret Sauce</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-google-meet-username-transformation-guide/"><u>[Updated] In 2024, Google Meet Username Transformation Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-quickcapture-hd-software-for-2024/"><u>[Updated] QuickCapture HD Software for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-getting-started-on-discord-a-comprehensive-guide-to-broadcasting/"><u>2024 Approved  Getting Started on Discord  A Comprehensive Guide to Broadcasting</u></a></li>
<li><a href="https://fox-blue.techidaily.com/audio-visual-converters-forum/"><u>Audio Visual Converters Forum</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-webcams-for-zoom-for-2024/"><u>Best Webcams for Zoom for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/controlling-metrics-on-your-windows-11-wifi-networks/"><u>Controlling Metrics on Your Windows 11 Wifi Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/countering-sudden-invisibility-in-win-based-gaming/"><u>Countering Sudden Invisibility in Win-Based Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphraning-the-message-of-crossed-out-icons-on-files/"><u>Deciphraning: The Message of Crossed-Out Icons on Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-removable-drives-in-explorer-interface/"><u>Displaying Removable Drives in Explorer Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-high-contrast-mode-go-to-ease-of-access-settings-and-enable-high-contrast-mode-if-it-improves-visibility/"><u>Enable High Contrast Mode: Go to 'Ease of Access' Settings and Enable High Contrast Mode if It Improves Visibility</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-analysis-of-netgear-orbi-rbs502-mastering-your-homes-outdoor-wi-fi-needs/"><u>Expert Analysis of Netgear Orbi RBS50^2: Mastering Your Home's Outdoor Wi-Fi Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-command-management-in-windows-1011/"><u>Fast-Track Command Management in Windows 10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-paper-to-cloud-preserving-old-family-photographs/"><u>From Paper to Cloud  Preserving Old Family Photographs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-override-microsofts-antivirus-exclusivity-measures/"><u>How to Override Microsoft's Antivirus Exclusivity Measures</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-oppo-a1-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Oppo A1 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-samsung-galaxy-s24-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Samsung Galaxy S24 without App | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-honor-magic-6-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Honor Magic 6 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-methods-to-transfer-from-apple-iphone-6-to-android-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Methods to Transfer from Apple iPhone 6 to Android | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-oppo-a38-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Oppo A38 Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-adding-items-to-win-11-contextual-menu/"><u>Innovative Approaches to Adding Items to Win 11 Contextual Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-guide-streamlining-file-conversions-in-win-11-with-docx/"><u>Innovative Guide: Streamlining File Conversions in Win 11 with Docx</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-tools-aiding-the-laptops-operating-system-swap/"><u>Innovative Tools Aiding the Laptop's Operating System Swap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intuitive-exploration-the-minimalist-approach-to-windows-explorer/"><u>Intuitive Exploration: The Minimalist Approach to Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-settings-in-windows-11-with-minimal-hassle/"><u>Mastering Mouse Settings in Windows 11 with Minimal Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-fix-a-non-reactive-windows-download-folder/"><u>Methods to Fix a Non-Reactive Windows Download Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outsmarting-windows-logon-requirements/"><u>Outsmarting Windows Logon Requirements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-full-screen-problems-in-windows-11-sonics/"><u>Overcoming Full-Screen Problems in Windows 11 Sonics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-spur-up-your-printers-speed/"><u>Quick Fixes to Spur Up Your Printer's Speed</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-oppo-f23-5g-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Oppo F23 5G Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-graphics-drivers-on-windows-11-systems/"><u>Refreshing Graphics Drivers on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-resetting-user-defined-search-in-win11/"><u>Regaining Control: Resetting User-Defined Search in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-windows-backup-configurations/"><u>Regaining Original Windows Backup Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-device-conflicts-no-more-in-use-name-woes/"><u>Resolve Windows Device Conflicts: No More In-Use Name Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-excel-files-unreadable-in-windows-notepad/"><u>Resolve: Excel Files Unreadable in Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-not-enough-resources-for-usb-on-windows/"><u>Resolving “Not Enough Resources” For USB on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shed-heavy-weights-pure-power-windows-11-tiny/"><u>Shed Heavy Weights: Pure Power, Windows 11 Tiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-overcoming-a-blank-login-window-on-win1011/"><u>Solving the Puzzle: Overcoming a Blank Login Window on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-sound-issue-in-audacity-on-windows-1111/"><u>Steps to Resolve Sound Issue in Audacity on Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reinstallation-when-applications-dont-start-on-ms-marketplace/"><u>Strategies for Reinstallation When Applications Don't Start on MS Marketplace</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-budget-wifi-champion-unpacking-features-and-performance-of-the-tp-link-archer-c9/"><u>The Budget WiFi Champion: Unpacking Features and Performance of the TP-Link Archer C9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-leading-windows-brightness-management-apps-and-utilities/"><u>The Leading Windows Brightness Management Apps & Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-computere-clock-display-top-5-windows-screensaver-apps-for-dynamic-visuals/"><u>Transform Your Computer’e Clock Display: Top 5 Windows Screensaver Apps for Dynamic Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-and-restoring-itunes-on-windows-devices/"><u>Unfreezing and Restoring iTunes on Windows Devices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unleash-potential-strategies-for-skyrocketing-your-fb-profile-status-for-2024/"><u>Unleash Potential  Strategies for Skyrocketing Your FB Profile Status for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-insight-using-the-lookup-tool-for-window-crashes/"><u>Unlocking Insight: Using the Lookup Tool for Window Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-error-0x80070522-in-windows-restore-client-access-rights/"><u>Unpacking Error 0X80070522 in Windows: Restore Client Access Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-your-pcs-onedrive-mysteries-solutions-here/"><u>Unraveling Your PC's OneDrive Mysteries: Solutions Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-monitoring-network-traffic-on-windows-11/"><u>Unveiling the Secrets of Monitoring Network Traffic on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-protocol-concealing-firewall-areas/"><u>Window’s Security Protocol: Concealing Firewall Areas</u></a></li>
</ul></div>
