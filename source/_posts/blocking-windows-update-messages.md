---
title: Blocking Windows Update Messages
date: 2025-01-27T06:17:38.666Z
updated: 2025-02-01T05:10:47.990Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-versatile-biz-decks-free-template-and-resource-options/"><u>[New] In 2024, Versatile Biz Decks FREE Template and Resource Options</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-instant-image-perfection-advanced-cropping-guide/"><u>[New] Instant Image Perfection - Advanced Cropping Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-tech-for-everyone-experts-analysis/"><u>[Updated] Tech for Everyone Experts' Analysis</u></a></li>
<li><a href="https://extra-hints.techidaily.com/capture-perfection-at-home-these-are-the-best-5-filming-hacks-for-2024/"><u>Capture Perfection at Home These Are the Best 5 Filming Hacks for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/channeling-success-the-essential-elements-for-profitable-video-trailers-for-2024/"><u>Channeling Success The Essential Elements for Profitable Video Trailers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-mouse-trail-and-size-on-new-windows-os/"><u>Customizing Mouse Trail & Size on New Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directdraw-breakdown-fixes-for-win11-and-beyond/"><u>DirectDraw Breakdown: Fixes for Win11 and Beyond</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-the-newest-nvidia-drivers-compatible-with-windows-1078/"><u>Download the Newest Nvidia Drivers Compatible with Windows 10/7/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/edges-background-behavior-on-modern-windows-11/"><u>Edge's Background Behavior on Modern Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-video-ram-in-windows-11-pro/"><u>Enhancing Video RAM in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-touchpad-feel-with-simple-windows-settings-tweaks/"><u>Improve Touchpad Feel with Simple Windows Settings Tweaks</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-simplifying-image-editing-with-picsarts-background-tool/"><u>In 2024, Simplifying Image Editing with Picsart's Background Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-ntoskrnlexes-heavy-cpu-footprint/"><u>Reducing Ntoskrnl.exe's Heavy CPU Footprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-the-foundation-for-win-11-security-upgrades/"><u>Setting the Foundation for Win 11 Security Upgrades</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-ultimate-gamers-blueprint-expert-tips-for-assembling-a-powerhouse-gaming-pc-on-zdnet/"><u>The Ultimate Gamer's Blueprint: Expert Tips for Assembling a Powerhouse Gaming PC on ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-windows-11-home-settings/"><u>The Ultimate Guide to Windows 11 Home Settings</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-do-you-wish-to-learn-about-some-tools-to-slow-down-a-video-discover-how-to-slow-down-time-lapse-on-iphone-throughout-this-article-for-2024/"><u>Updated Do You Wish to Learn About some Tools to Slow Down a Video? Discover How to Slow Down Time Lapse on iPhone Throughout This Article for 2024</u></a></li>
</ul></div>

