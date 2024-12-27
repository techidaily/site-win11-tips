---
title: Stop Windows From Prompting for Updates
date: 2024-12-21T16:36:19.652Z
updated: 2024-12-27T21:50:37.441Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Prompting for Updates
excerpt: This Article Describes Stop Windows From Prompting for Updates
keywords: Stop Update Prompts -,Avoid Windows Update Alerts -,Prevent Windows Update Requests -,No More Update Prompts on Windows -,Block Windows Update Interruption -,Defer Windows Update Notifications -,Disable Windows Update Warnings -
thumbnail: https://thmb.techidaily.com/bb00ebc3d89d1362ca9b186657d254b37c10a245e721f7dc9d791e4530e6a65b.jpeg
---

## Stop Windows From Prompting for Updates

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://video-screen-grab.techidaily.com/new-capture-save-and-share-mastering-playstation-4-recordings/"><u>[New] Capture, Save & Share Mastering PlayStation 4 Recordings</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-high-speed-windows-photoviewer/"><u>[New] High-Speed Windows Photoviewer</u></a></li>
<li><a href="https://youtube-web.techidaily.com/riple-tactic-tracker-how-to-scrutinize-your-subscriber-earnings-on-googles-platform-youtube-for-2024/"><u>[New] Triple Tactic Tracker How to Scrutinize Your Subscriber Earnings on Google's Platform, YouTube for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-vdq-quickscreen-recorder-report-in-depth-analysis/"><u>[Updated] VDQ QuickScreen Recorder Report In-Depth Analysis</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/digging-into-the-data-top-10-twitvideos-for-2024/"><u>Digging Into the Data Top 10 TwitVideos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extended-support-for-windows-11-version-22h2-announced/"><u>Extended Support for Windows 11 Version 22H2 Announced</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-newcomer-to-pro-classic-diablo-techniques/"><u>From Newcomer to Pro: Classic Diablo Techniques</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-asgard-unleashed-echoes-of-ragnarok/"><u>In 2024, Asgard Unleashed Echoes of Ragnarök</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-the-security-questions-of-your-apple-id-from-your-iphone-15-plus-by-drfone-ios/"><u>In 2024, How To Reset the Security Questions of Your Apple ID From Your iPhone 15 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insider-take-unveiling-key-upgrades-in-feb-update/"><u>Insider Take: Unveiling Key Upgrades in FEB Update</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/la-strategie-de-clonage-dordinateurs-sans-problemes-guide-complet-pour-un-reseau-identique/"><u>La Stratégie De Clonage D'Ordinateurs Sans Problèmes: Guide Complet Pour Un Réseau Identique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-windows-shortcuts-for-uwp-apps/"><u>Mastering the Art of Windows Shortcuts for UWP Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-csgo-playthrough-speed-with-these-tips/"><u>Maximize CSGO Playthrough Speed with These Tips</u></a></li>
<li><a href="https://buynow-help.techidaily.com/maximizing-your-viewing-experience-with-the-affordable-hisense-50h8f-4k-tv-expert-review/"><u>Maximizing Your Viewing Experience with the Affordable Hisense 50H8F 4K TV - Expert Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win-11-recycle-bin-crashes-and-issues/"><u>Overcoming Win 11 Recycle Bin Crashes & Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-window-11-themes-with-advanced-registry-techniques/"><u>Unlocking Window 11 Themes with Advanced Registry Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-alternative-approaches-to-open-your-apps/"><u>Windows 10: Alternative Approaches to Open Your Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1725286111250-dvd/"><u>ゲオレンタルDVDの安全なバックアップ手順:信頼できるソフトウェア使い方ガイド</u></a></li>
</ul></div>

