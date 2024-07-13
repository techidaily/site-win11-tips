---
title: Blocking Windows Update Messages
date: 2024-07-12T17:59:50.078Z
updated: 2024-07-13T17:59:50.078Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Blocking Windows Update Messages
excerpt: This Article Describes Blocking Windows Update Messages
keywords: Uninstall Updates Blocker,Disable Update Notifications,Stop Windows Update Alerts,Manage Update Warnings,Halt Update System Messages,Prevent Update Disturbances,Curtail Windows Update Vibes
thumbnail: https://thmb.techidaily.com/078ec5c6b19df307c3d053f03815c7d21ecece8ed3226ebe1d118a70909568e6.jpg
---

## Blocking Windows Update Messages

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://facebook-video-footage.techidaily.com/top-5-ultimate-camera-and-video-recording-apps-iphoneandroid-edition-for-2024/"><u>Top 5 Ultimate Camera & Video Recording Apps  IPhone/Android Edition for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-collection-of-10-inspirational-movies/"><u>In 2024, The Ultimate Collection of 10 Inspirational Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-extended-storage-mediocre-execution/"><u>Blackview MiniPC: Extended Storage, Mediocre Execution</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/echoing-quietness-a-guide-to-purifying-your-podcasts-from-high-frequency-humming/"><u>Echoing Quietness A Guide to Purifying Your Podcasts From High-Frequency Humming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-setup-service-operation-levels/"><u>Adjusting Windows Setup Service Operation Levels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-changing-windows-date-and-time-accurately/"><u>Avoid Changing Windows Date & Time Accurately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-virtualization-turning-on-hyper-v-for-win-11/"><u>Boosting Virtualization: Turning On Hyper-V for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-game-breaking-disconnections-fall-guys-windows-fixes/"><u>Avoid Game-Breaking Disconnections: Fall Guys Windows Fixes</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-ultimate-guide-to-trimming-videos-online-with-kapwing/"><u>Updated In 2024, The Ultimate Guide to Trimming Videos Online with Kapwing</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-poco-c55-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Poco C55? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-outwit-youtube-visitors-tips-to-evade-automated-audiences/"><u>[Updated] Outwit YouTube Visitors  Tips to Evade Automated Audiences</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-a-full-review-of-splice-video-editing-app-for-2024/"><u>New A Full Review of Splice Video Editing App for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-disasterous-dism-error-0x800f082f-on-windows/"><u>Banishing Disasterous DISM: Error 0X800F082F on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-essential-guide-for-diy-gif-makers-youtube-to-visual-storytelling/"><u>2024 Approved  The Essential Guide for DIY GIF Makers  YouTube to Visual Storytelling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-sync-and-conquer-to-dot-and-ifttt/"><u>Automate, Sync, and Conquer: To-Dot & IFTTT</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-locating-authentic-monster-audio-layers/"><u>2024 Approved Locating Authentic Monster Audio Layers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-samsung-galaxy-m14-4g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Samsung Galaxy M14 4G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-top-picks-for-zero-price-mp3-fusion-technology-for-2024/"><u>New Top Picks for Zero-Price MP3 Fusion Technology for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-mastering-gaming-the-8-best-sound-effects-available-without-a-price-tag/"><u>2024 Approved Mastering Gaming The 8 Best Sound Effects Available Without a Price Tag</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-windows-cab-and-its-functionality/"><u>An In-Depth Look at Windows CAB and Its Functionality</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-the-ultimate-resource-for-adding-dynamic-gifs-to-discord-conversations/"><u>2024 Approved  The Ultimate Resource for Adding Dynamic GIFs to Discord Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bluescreenview-unpacked-practical-applications/"><u>BlueScreenView Unpacked: Practical Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-cameras-failed-recordings/"><u>Addressing Windows Camera's Failed Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-sensitivity-on-modern-windows-devices/"><u>Balancing Sensitivity on Modern Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unintended-read-only-file-states-in-windows-11/"><u>Avoiding Unintended Read-Only File States in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-capturewin-the-hassle-free-screen-recorder/"><u>[Updated] 2024 Approved  CaptureWin  The Hassle-Free Screen Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-ux3405-review-is-this-the-macbook-of-windows/"><u>ASUS Zenbook 14 OLED (UX3405) Review: Is This the MacBook of Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-could-not-create-window-mmc-snapshot-issues/"><u>Avoiding 'Could Not Create' Window MMC Snapshot Issues</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unlocking-visual-treasures-without-cost/"><u>[Updated] Unlocking Visual Treasures Without Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-history-welcome-new-hues-on-windows/"><u>Banish History, Welcome New Hues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-mastering-windows-11-efficiency/"><u>Boost Your System: Mastering Windows 11 Efficiency</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-discord-customization-essentials-selecting-eye-catching-flag-designs/"><u>[New] In 2024, Discord Customization Essentials  Selecting Eye-Catching Flag Designs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-vanishing-bluetooth-clients-on-pc/"><u>Addressing Vanishing Bluetooth Clients on PC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unparalleled-snapchat-experience-top-editing-tools-on-smartphones-for-2024/"><u>[Updated] Unparalleled Snapchat Experience  Top Editing Tools on Smartphones for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-ignite-your-networking-join-the-1k-club-on-instagram-regularly/"><u>2024 Approved  Ignite Your Networking  Join the 1K Club on Instagram Regularly</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-a-step-by-step-guide-to-youtube-to-igtv-conversion/"><u>In 2024, A Step-by-Step Guide to YouTube to IGTV Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-errors-secure-your-onedrive-login-on-windows/"><u>Avoiding Errors: Secure Your OneDrive Login on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-augmented-reality-stickers-by-google-unveiled-and-compared/"><u>In 2024, Augmented Reality Stickers by Google Unveiled and Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-pc-launches-activating-fast-startup-feature/"><u>Boosting PC Launches: Activating Fast Startup Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-fun-integrating-games-into-windows-11-through-google-play/"><u>Android Fun: Integrating Games Into Windows 11 Through Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-task-management-adding-cli-toolbar-in-win11-taskmgr/"><u>Advanced Task Management: Adding CLI Toolbar in Win11 TaskMgr</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-evolving-tactics-for-crafting-immersive-mukbang-sessions/"><u>2024 Approved  Evolving Tactics for Crafting Immersive Mukbang Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-android-app-integration-on-windows-11-systems/"><u>Best Android App Integration on Windows 11 Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-x100-pro-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Vivo X100 Pro Phone without Any Data Loss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-fixing-frequent-apex-legends-crashes-on-windows-11/"><u>Beating the Bug: Fixing Frequent Apex Legends Crashes on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-beyond-inshot-essential-laptop-editing-tools/"><u>2024 Approved  Beyond Inshot  Essential Laptop Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-abrupt-termination-of-wow-error-132-on-win11/"><u>Banishing The Abrupt Termination of WoW (Error 132) on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-synergy-with-windows-os-paving-a-futuristic-path/"><u>AI Synergy with Windows OS: Paving a Futuristic Path</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-selective-image-blurring-techniques/"><u>Mastering Selective Image Blurring Techniques</u></a></li>
</ul></div>
