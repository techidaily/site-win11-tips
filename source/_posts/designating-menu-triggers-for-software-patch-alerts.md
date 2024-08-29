---
title: Designating Menu Triggers for Software Patch Alerts
date: 2024-08-28T01:11:06.652Z
updated: 2024-08-29T01:11:06.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Designating Menu Triggers for Software Patch Alerts
excerpt: This Article Describes Designating Menu Triggers for Software Patch Alerts
keywords: Menu Trigger Warnings,Patch Alert Cues,Menu Patch Notifications,Software Update Signals,Alert Menus Designation,Triggers for Patch Updates,Notifying Menu Actions
thumbnail: https://thmb.techidaily.com/a9e60c359d76678f8aad5193db4d1713b6255faff22e113abbe3abedfe2cc94d.jpeg
---

## Designating Menu Triggers for Software Patch Alerts

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-mobile-creativity-boost-identifying-the-best-video-editing-tools/"><u>[New] 2024 Approved  Mobile Creativity Boost  Identifying the Best Video Editing Tools</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-6-must-visit-destinations-for-top-notch-youtube-branding-elements-for-2024/"><u>[New] 6 Must-Visit Destinations For Top-Notch YouTube Branding Elements for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-a-duel-of-viewers-google-cardboard-vs-samsung-vr/"><u>[New] A Duel of Viewers  Google Cardboard Vs. Samsung VR</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-practical-steps-to-enhance-videos-with-device-based-filtering/"><u>[New] Practical Steps to Enhance Videos with Device-Based Filtering</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-timing-duration-for-a-20mb-high-definition-video-for-2024/"><u>[New] Timing Duration for a 20Mb High-Definition Video for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-comprehensive-techniques-to-improve-mp4-soundtracks-using-srt-2024s-best-practices/"><u>[Updated] Comprehensive Techniques to Improve MP4 Soundtracks Using SRT (2024'S Best Practices)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-breaking-the-internet-hashtag-wisdom-for-short-films/"><u>[Updated] In 2024, Breaking the Internet  Hashtag Wisdom for Short Films</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-easyshadecleanse-professionally-crafted-erase-software/"><u>[Updated] In 2024, EasyShadeCleanse  Professionally Crafted Erase Software</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-kinemasters-guide-to-fluid-film-segments/"><u>[Updated] Kinemaster's Guide to Fluid Film Segments</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-w10-ultimate-screen-replay-suite/"><u>[Updated] W10 Ultimate Screen Replay Suite</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-how-to-securely-archive-calls-on-facebook-messenger/"><u>2024 Approved  How to Securely Archive Calls on Facebook Messenger</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-meet-mycam-cam-the-home-video-revolution-unfolding/"><u>2024 Approved  Meet MyCam Cam  The Home Video Revolution Unfolding</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-ogle-player-powerful-pixel-perfect-media/"><u>2024 Approved  Ogle Player  Powerful, Pixel-Perfect Media</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-free-hilarious-memetic-art/"><u>2024 Approved  The Ultimate Guide to Free, Hilarious Memetic Art</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deactivating-random-openings-of-file-explorer/"><u>Deactivating Random Openings of File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-computer-chronology-windows-edition/"><u>Deciphering Computer Chronology - Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-duo-dynamics-syncing-your-mobile-and-computer/"><u>Digital Duo Dynamics: Syncing Your Mobile & Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enlightening-on-high-fidelity-window-images/"><u>Enlightening on High-Fidelity Window Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-temperature-tracker-guide/"><u>Essential Windows Temperature Tracker Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-your-windows-ssd-with-win-plus-ssfresh-techniques/"><u>Fast-Track Your Windows SSD with Win + SSFresh Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-now-glitch-xc0f1103f-in-win-1011-oses/"><u>Fixing GeForce Now Glitch XC0F1103F in Win 10/11 OSes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/fusionchannel-best-live-and-on-demand-tv-experience-2024/"><u>FusionChannel  Best Live & On-Demand TV Experience, 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-default-search-window-action-windows-11-guide/"><u>Halt Default Search Window Action, Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-regain-superuser-status-in-windows-terminal/"><u>How to Regain Superuser Status in Windows Terminal</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-tecno-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Tecno Phone that is Locked?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immerse-yourself-in-a-three-dimensional-audio-world-on-windows-11/"><u>Immerse Yourself in a Three-Dimensional Audio World on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-breakdown-of-youtubes-shorts-initiative/"><u>In 2024, The Breakdown of YouTube's Shorts Initiative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intels-unison-and-microsofts-phone-link-for-wp-which-is-better/"><u>Intel's Unison and Microsoft's Phone Link for WP: Which Is Better?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-removing-epic-games-from-w11/"><u>Mastering the Art of Removing Epic Games From W11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-windows-11-unlocking-access-to-your-file-sharing-and-backup-options/"><u>Mastering Windows 11: Unlocking Access to Your File Sharing and Backup Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opting-out-of-built-in-pc-graphics-on-windows-os/"><u>Opting Out of Built-In PC Graphics on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/push-beyond-the-limits-yuzu-emulator-speed/"><u>Push Beyond the Limits: Yuzu Emulator Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-the-shortcomings-of-discord-search-on-windows-devices/"><u>Rectifying the Shortcomings of Discord Search on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-your-computers-print-functionality-with-effective-wwin-solutions/"><u>Reigniting Your Computer's Print Functionality with Effective WWin Solutions.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-nvidia-display-issue-in-control-panel/"><u>Resolving Nvidia Display Issue in Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-scanning-condensed-viewing-for-file-finder/"><u>Simplified Scanning: Condensed Viewing for File Finder</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-note-30-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Note 30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-restore-non-functional-network-in-win-os/"><u>Solutions to Restore Non-Functional Network in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-ease-through-the-waiting-gpsvc/"><u>Strategies to Ease Through the Waiting GPSVC</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/the-ultimate-filter-guide-to-superior-zoom-quality-for-2024/"><u>The Ultimate Filter Guide to Superior Zoom Quality for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-repairing-iomap64-syscall-issues-on-windows-devices/"><u>Tips for Repairing IOMap64 SysCall Issues on Windows Devices</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-made-easy-fix-your-apex-legends-not-loading-in-minutes/"><u>Troubleshooting Made Easy: Fix Your 'Apex Legends Not Loading' In Minutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-generic-volume-control-fix-guide/"><u>Unblocking Windows Generic Volume Control: Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-password-power-mastering-the-11-methods-for-credential-management-on-win11/"><u>Unleash Password Power: Mastering the 11 Methods for Credential Management on Win11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unveiling-the-game-changing-power-of-the-apple-macbook-pro-with-m1-chip-2020-edition/"><u>Unveiling the Game-Changing Power of the Apple MacBook Pro with M1 Chip, 2020 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-steps-to-engage-wordpad-in-win-os/"><u>Unveiling the Steps to Engage WordPad in Win OS</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/vtech-kidizoom-duo-camera-review/"><u>VTech Kidizoom Duo Camera Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10-fix-overcoming-null-audio-device-problems/"><u>Win 10 Fix: Overcoming Null Audio Device Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-local-device-naming-problems-on-windows-pcs/"><u>Winning Over Local Device Naming Problems on Windows PCs</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>