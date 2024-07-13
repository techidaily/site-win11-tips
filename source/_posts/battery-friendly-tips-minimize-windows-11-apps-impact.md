---
title: "Battery-Friendly Tips: Minimize Windows 11 Apps' Impact"
date: 2024-07-12T16:34:11.295Z
updated: 2024-07-13T16:34:11.295Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Battery-Friendly Tips: Minimize Windows 11 Apps' Impact"
excerpt: "This Article Describes Battery-Friendly Tips: Minimize Windows 11 Apps' Impact"
keywords: W11 Power Save,Battery Saver Win,Minimize App Power,Efficient Win11 Usage,Reduce Windows Load,Win11 Energy Tips,App Optimization Windows
thumbnail: https://thmb.techidaily.com/399b71f22f6a0f097f9f941327a817b697b933fa54dbaf37480f689ec0e73886.jpg
---

## Battery-Friendly Tips: Minimize Windows 11 Apps' Impact

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

## 1\. Install Windows Update Hotfix
![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to [manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to [Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

### Disable News and Interests on Windows 11
![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can [disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to [perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to [enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
5. Select**Disabled** and click**Apply** and**OK** to save the changes.  
![turn off news and interest disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled.jpg)
6. Close Group Policy Editor and restart your computer.

 After restarting your computer, the News and Interests feature should no longer appear. Launch the task manager and check for improvements in your PC's CPU and memory usage.

## 4\. Disable News and Interests Using the Registry Editor on Windows 10

 You can disable the feed feature using the Windows Registry if you don't have Group Policy Editor. For this, you'll need to create an EnableFeeds value and set it to 0 to disable it.

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

To disable the news feed feature using Windows Registry:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .  
![registry editor new key Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows.jpg)
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quicker navigation:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Right-click on the**Windows** key in the left pane.
5. Select**New > Key** . Rename the key as**Windows Feeds** .  
![registry editor new key Windows new DWORd value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value.jpg)

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
4. Type**0** in the**Value data** field and click**OK** to save the changes.
5. Close the Registry Editor and restart your computer to apply the changes.

## 5\. Add and Disable EnableFeeds Using PowerShell
![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

## Fix the News and Interests Feature's High Memory Usage on Windows

 Memory leakage is a common cause for the News and Interests high memory usage issue. While a hotfix is available, you'll need to disable the News and Interests widget item to resolve the problem if the issue persists.


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
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-copypaste-anomalies/"><u>Overcoming Windows 11 Copy/Paste Anomalies</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-honor-x50-gt-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Honor X50 GT? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivate-your-windows-11-explore-with-ease/"><u>Reactivate Your Windows 11 Explore with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-android-into-windows-11-select-the-best-6-companion-apps/"><u>Integrating Android Into Windows 11: Select the Best 6 Companion Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-file-explorer-freezes-in-win11-with-these-fixes/"><u>Stop File Explorer Freezes in Win11 With These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-dir-not-empty-error-0x80070091/"><u>Overcoming Windows 11 Dir Not Empty Error (0X80070091)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/dissecting-screencapturex-pros-latest-recording-capabilities-for-2024/"><u>Dissecting ScreenCaptureX Pro's Latest Recording Capabilities for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-easy-cures-for-your-computers-messaging-woes/"><u>Quick & Easy Cures for Your Computer's Messaging Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-non-responsive-windows-services-management-tool/"><u>Navigating the Maze of Non-Responsive Windows Services Management Tool</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-enhancing-visibility-key-steps-in-social-media-video-marketing/"><u>2024 Approved  Enhancing Visibility  Key Steps in Social Media Video Marketing</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Oppo Reno 10 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/easy-steps-on-how-to-create-a-new-apple-id-account-on-apple-iphone-11-by-drfone-ios/"><u>Easy Steps on How To Create a New Apple ID Account On Apple iPhone 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-maximize-engagement-with-facebook-posting-360-degree-photos-on-mobile-for-2024/"><u>[Updated] Maximize Engagement with Facebook  Posting 360-Degree Photos on Mobile for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-poco-m6-pro-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Poco M6 Pro 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-effect-of-eliminating-windows-11-taskbar-chat-on-you/"><u>Understanding the Effect of Eliminating Windows 11 Taskbar Chat on You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-efficient-bluescreenview-use/"><u>Essential Tips for Efficient BlueScreenView Use</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-the-meta-and-omni-spaces/"><u>In 2024, Understanding the Meta and Omni Spaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-no-network-reachable-errors-win/"><u>Eradicating No Network Reachable Errors (WIN)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigning-fast-the-quintessential-wins-performance-aids/"><u>Reigning Fast: The Quintessential Win's Performance Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-camera-apps-error-0xa00f425d-in-windows-11-and-11/"><u>How to Fix the Camera App’s Error 0xA00F425D in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-cr2-conversion-to-jpg-in-windows-environment/"><u>Streamline CR2 Conversion to JPG in Windows Environment</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-the-elite-collection-best-kung-fu-arcade-games/"><u>2024 Approved  The Elite Collection  Best Kung Fu Arcade Games</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-honor-magic-v2-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Honor Magic V2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-10-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-tips-for-sticky-note-backup/"><u>The Essential Tips for Sticky Note Backup</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-10-best-inspirational-movies-that-will-bring-you-hope-and-power/"><u>[New] 10 Best Inspirational Movies That Will Bring You Hope and Power</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/expert-advice-on-converting-high-quality-ipv-files-to-mp4/"><u>Expert Advice on Converting High-Quality IPV Files to MP4</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-vivo-y100i-power-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-from-pixels-to-perfection-a-guide-to-calculating-image-ratios/"><u>New 2024 Approved From Pixels to Perfection A Guide to Calculating Image Ratios</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-pc-vram-with-windows-1011-tips-and-tricks/"><u>Turbocharging PC VRAM with Windows 10/11 Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-audio-software-performance-on-windows-with-error-9999/"><u>Streamlining Audio Software Performance on Windows with Error 9999</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-exclusive-list-20-complimentary-tools-for-fb-ad-producers/"><u>2024 Approved  Exclusive List  20 Complimentary Tools for Fb Ad Producers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-rookie-riches-economical-channels-for-monetization/"><u>[New] In 2024, Rookie Riches  Economical Channels for Monetization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-manual-for-chrome-and-windows-11/"><u>The Ultimate Manual for Chrome and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-malware-discovery-without-software-assistance/"><u>Mastering Malware Discovery without Software Assistance</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-expert-list-superior-gaming-live-options/"><u>[Updated] Expert List  Superior Gaming Live Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-gaming-unbound-android-in-desktop-windows-with-google-play-service/"><u>Experience Gaming Unbound: Android in Desktop Windows with Google Play Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-keys-to-a-cleaner-windows-experience/"><u>Three Keys to a Cleaner Windows Experience</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-premier-ios-choice-best-emulators-of-psp-games-for-2024/"><u>[New] Premier iOS Choice  Best Emulators of PSP Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-post-display-adjustment-in-windows-power-configuration/"><u>Hide Post-Display Adjustment in Windows Power Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-hidden-dangers-on-a-computer-screen/"><u>Navigating Hidden Dangers on a Computer Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-solutions-hiding-zips-within-computer-photos/"><u>Sneaky Storage Solutions: Hiding ZIPs Within Computer Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-chromes-firewallantivirus-denial-error-on-pc/"><u>Resolving Chrome's Firewall/Antivirus Denial Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-email-setup-connecting-your-gmail-to-outlook-windows/"><u>Simplifying Email Setup: Connecting Your Gmail to Outlook Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-elusive-link-finding-missing-launcher/"><u>Re-Establishing Elusive Link: Finding Missing Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-w11w10s-refusal-to-open-folders-after-double-clicks/"><u>Resolving W11/W10's Refusal to Open Folders After Double-Clicks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/harness-the-power-of-instagrams-hidden-features/"><u>Harness the Power of Instagram's Hidden Features</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/top-10-hilarious-and-emotional-instagram-memes-journey/"><u>Top 10 Hilarious & Emotional Instagram Memes Journey</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-correcting-missed-audio-segments-in-obs-recordings/"><u>[Updated] In 2024, Correcting Missed Audio Segments in OBS Recordings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-understanding-zooms-participant-clusters/"><u>[Updated] Understanding Zoom's Participant Clusters</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-best-aspect-ratio-changer-tools-for-video-editing/"><u>New 2024 Approved Best Aspect Ratio Changer Tools for Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mute-your-keyboard-on-a-windows-computer/"><u>How to Mute Your Keyboard on a Windows Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-non-starting-adobe-photoshopping-in-windows-11/"><u>How to Enable Non-Starting Adobe Photoshopping in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-quick-online-mp3-generator-from-fb-videos-2023-updates/"><u>In 2024, Quick Online MP3 Generator From FB Videos, 2023 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-window-display-mastering-alt-tab-order-in-win1110/"><u>Maximizing Window Display: Mastering Alt-Tab Order in Win11/10</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-preserve-tweets-as-visual-delights-with-iosandroid-steps/"><u>[New] Preserve Tweets as Visual Delights with iOS/Android Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-restarting-non-responsive-resource-monitors-in-windows-11/"><u>Strategies for Restarting Non-Responsive Resource Monitors in Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-a-deep-dive-into-video-workflow-enhancement-through-hdri-adoption/"><u>[New] A Deep Dive Into Video Workflow Enhancement Through HDRI Adoption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-your-preferred-soft-install-tool-on-win-devices/"><u>Finding Your Preferred Soft Install Tool on Win Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-end-specs-in-windows-game-capture/"><u>Overcoming Low-End Specs in Windows Game Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pitfalls-of-the-promotional-assessing-risks-with-low-price-auth-codes/"><u>Pitfalls of the Promotional: Assessing Risks with Low-Price Auth Codes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Nokia C02? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-engaging-viewers-on-youtube-gaming-livestreams-for-2024/"><u>[New] Engaging Viewers on YouTube Gaming Livestreams for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reintroducing-versatility-beyond-win-1110s-s-mode/"><u>Reintroducing Versatility Beyond Win 11/10'S S Mode</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-itel-s23plus-drfone-by-drfone-android/"><u>How to Screen Mirroring Itel S23+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resetting-graphics-drivers-on-latest-oses/"><u>Quick Guide to Resetting Graphics Drivers on Latest OSes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-11-pro-drfone-by-drfone-ios/"><u>How to Unlock iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-free-avi-video-combining-tools-no-watermarks-or-trials/"><u>In 2024, Best Free AVI Video Combining Tools No Watermarks or Trials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-vm-mastery-setting-up-linux-vm-in-hyper-v-on-windows/"><u>Multi-VM Mastery: Setting Up Linux VM in Hyper-V on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fundamentals-of-selecting-the-best-win-notebook/"><u>Fundamentals of Selecting the Best Win Notebook</u></a></li>
</ul></div>
