---
title: "Feature: Context Menu Alert for Windows Updates in Win11+11"
date: 2024-07-12T17:45:20.412Z
updated: 2024-07-13T17:45:20.412Z
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

## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

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
<li><a href="https://ai-video-editing.techidaily.com/1713951643172-unravel-the-creative-potential-of-adobe-after-effects-for-precise-motion-synchronization-learn-how-to-use-track-matte-and-tracking-with-a-simple-alternative/"><u>Unravel the Creative Potential of Adobe After Effects for Precise Motion Synchronization. Learn How to Use Track Matte and Tracking with a Simple Alternative for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-iphone-image-import-something-went-wrong-error-in-windows-10-and-11/"><u>How to Fix the iPhone Image Import “Something Went Wrong” Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-pc-performance-insider-tips-on-wintools/"><u>Elevate PC Performance: Insider Tips on WinTools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-webvidrecorder-download-fb-content-easily/"><u>In 2024, WebVidRecorder  Download FB Content Easily</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/trouble-with-iphone-6-plus-swipe-up-try-these-11-solutions-by-drfone-ios/"><u>Trouble with iPhone 6 Plus Swipe-Up? Try These 11 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-share-cant-be-opened-issues-in-geforce/"><u>Eliminating Share Can't Be Opened Issues in GeForce</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/quick-start-capturing-high-quality-mov-videos-on-windows-11/"><u>Quick Start  Capturing High-Quality MOV Videos on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oneplus-nord-n30-se-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from OnePlus Nord N30 SE to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-office-activation-error/"><u>Resolving Microsoft Office Activation Error</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-unleash-your-creativity-top-10-free-video-editors-for-mp4-files/"><u>2024 Approved Unleash Your Creativity Top 10 Free Video Editors for MP4 Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-management-navigating-taskbar-with-windows-hotkeys/"><u>Effortless Management: Navigating Taskbar with Windows Hotkeys</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-oppo-a1-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Oppo A1 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-older-systems-healthy-with-win10-improvements/"><u>Keep Older Systems Healthy with Win10 Improvements</u></a></li>
<li><a href="https://discord-videos.techidaily.com/perfect-your-discord-voices-avoiding-background-noise-with-voicemod/"><u>Perfect Your Discord Voices  Avoiding Background Noise with VoiceMod</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-policy-shift-for-trumps-page/"><u>Facebook Policy Shift for Trump's Page</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-network-issues-on-windows-11-a-comprehensible-approach/"><u>Overcoming Network Issues on Windows 11 - A Comprehensible Approach</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-finding-serenity-in-animated-worlds-top-youtube-picks-for-2024/"><u>[New] Finding Serenity in Animated Worlds  Top YouTube Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-remedy-guide-eight-tactics/"><u>Essential Windows Remedy Guide - Eight Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vac-rejection-in-steam-windows-gameplay/"><u>Overcoming VAC Rejection in Steam Windows Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-improve-windows-taskmanager-through-cli-integration/"><u>How to Improve Windows TaskManager Through CLI Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-powerpoint-print-errors-with-9-effective-methods/"><u>Overcoming Common PowerPoint Print Errors with 9 Effective Methods</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-xiaomi-13-ultra-by-fonelab-android-recover-data/"><u>Recover lost data from Xiaomi 13 Ultra</u></a></li>
<li><a href="https://extra-hints.techidaily.com/smooth-strategy-perfecting-your-instagram-grid/"><u>Smooth Strategy  Perfecting Your Instagram Grid</u></a></li>
<li><a href="https://techidaily.com/is-your-motorola-moto-g34-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Motorola Moto G34 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-mastering-video-trimming-for-maximum-instagram-impact-mac/"><u>[Updated] In 2024, Mastering Video Trimming for Maximum Instagram Impact (Mac)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-windows-notes-prominent/"><u>Keeping Your Windows Notes Prominent</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-result-visibility-for-windows-1011s-search/"><u>Enhancing Result Visibility for Windows 10/11'S Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-fingerprint-recognition-in-windows-11/"><u>Integrating Fingerprint Recognition in Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/advanced-desktop-tools-to-screen-capture-discord/"><u>Advanced Desktop Tools to Screen-Capture Discord</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-a-comprehensive-guide-to-snapchats-highlight-system/"><u>[Updated] A Comprehensive Guide to Snapchat's Highlight System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-windows-storage-the-top-free-volume-boosters-list/"><u>Enhance Your Windows Storage: The Top Free Volume Boosters List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-ps4-remote-link-eliminating-random-drops-in-connection/"><u>Secure Your PS4 Remote Link: Eliminating Random Drops in Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-difficulty-of-error-0x000-in-xbox-game-pass-windows-edition/"><u>Overcoming the Difficulty of Error 0X000_ in Xbox Game Pass Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-pcs-visual-fidelity-with-updated-radeon-drivers-windows-edition/"><u>Elevating Your PC's Visual Fidelity with Updated Radeon Drivers, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-linkage-airpods-and-windows-harmony/"><u>Master the Linkage: AirPods & Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-jump-to-notes-starting-windows-with-immediate-access/"><u>Quick Jump to Notes: Starting Windows with Immediate Access</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-exploring-the-best-vocal-transformation-options-for-gamers/"><u>In 2024, Exploring the Best Vocal Transformation Options for Gamers</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/non-edge-processes-lurking-in-task-manager/"><u>Non-Edge Processes Lurking in Task Manager</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-tiktok-to-twitter-sharing-videos/"><u>In 2024, TikTok to Twitter  Sharing Videos</u></a></li>
<li><a href="https://unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-zte-blade-a73-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your ZTE Blade A73 5G</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oppo-a79-5g-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Oppo A79 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-error-0x80131500-on-microsoft-store/"><u>Disabling Error 0X80131500 on Microsoft Store</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-mastering-your-sound-on-the-go-best-ios-apps-for-editing-2023-edition/"><u>Updated Mastering Your Sound on the Go Best iOS Apps for Editing, 2023 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-an-exception-breakpoint-has-been-reached-error-on-windows/"><u>How to Fix the “An Exception Breakpoint Has Been Reached” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-removal-of-win11s-official-store/"><u>Exclusive Removal of Win11's Official Store</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/a-beginners-guide-to-using-siri-in-your-tiktok-videos/"><u>A Beginner's Guide to Using Siri in Your TikTok Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-insta-wealth-tactics-for-transforming-passion-projects-into-paid-opportunities/"><u>[New] Insta-Wealth  Tactics for Transforming Passion Projects Into Paid Opportunities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-silencing-the-defender-firewall-in-win11/"><u>Guide to Silencing the Defender Firewall in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-login-retry-wait-timepost-failed-attempts/"><u>Manipulating Login Retry Wait Timepost-Failed Attempts</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-standard-youtube-licenses-versus-cc/"><u>[Updated] Standard Youtube Licenses Versus CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-secure-your-childrens-online-world-windows-11/"><u>Guidelines to Secure Your Children’s Online World: Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-performance-essential-strategies-with-windows-11/"><u>Skyrocket Your Performance: Essential Strategies with Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/vr-real-world-impacts/"><u>VR Real-World Impacts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-eliminate-your-streaming-darkness-on-youtube-for-2024/"><u>[Updated] Eliminate Your Streaming Darkness on YouTube for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-instagram-stop-motion-tutorial-bring-your-posts-to-life/"><u>Updated In 2024, Instagram Stop Motion Tutorial Bring Your Posts to Life</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-elevate-your-content-game-with-professional-facebook-slideshow-techniques-for-2024/"><u>[Updated] Elevate Your Content Game with Professional Facebook Slideshow Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/engage-with-windows-11s-screen-snip-functionality/"><u>Engage with Windows 11'S Screen Snip Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-stalled-outlook-alerts-for-new-messages/"><u>Reviving Stalled Outlook Alerts for New Messages</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/tiktok-video-aspect-ratios/"><u>TikTok Video Aspect Ratios</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-android-and-iphones-leading-tools-for-enhanced-fb-likes/"><u>[Updated] In 2024, Android & iPhone's Leading Tools for Enhanced FB Likes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-essentials-of-youtubes-cc-license-for-filmakers-for-2024/"><u>The Essentials of YouTube's CC License for Filmakers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-collectors-delight-exclusive-black-friday-price-drop-on-essential-windows-11/"><u>Key Collectors' Delight – Exclusive Black Friday Price Drop on Essential Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-steam-disk-write-error-on-windows/"><u>How to Fix the Steam Disk Write Error on Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-navigating-music-licens-written-by-john-doe/"><u>2024 Approved  Navigating Music Licens Written by John Doe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/group-free-enhance-windows-11-taskbar-ease/"><u>Group-Free: Enhance Windows 11 Taskbar Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chocolatey-vs-wm-top-tools-for-windows-software-downloads/"><u>Chocolatey vs WM: Top Tools for Windows Software Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-search-with-image-cleanse/"><u>Simplifying Windows Search with Image Cleanse</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-guidelines-for-compelling-visual-fb-marketing/"><u>[New] In 2024, Guidelines for Compelling Visual FB Marketing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-your-course-in-windows-preload-land/"><u>Charting Your Course in Windows Preload Land</u></a></li>
</ul></div>
