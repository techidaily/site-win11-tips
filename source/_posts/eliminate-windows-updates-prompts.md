---
title: Eliminate Windows Updates Prompts
date: 2024-12-19T04:15:23.402Z
updated: 2024-12-21T23:03:22.941Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Windows Updates Prompts
excerpt: This Article Describes Eliminate Windows Updates Prompts
keywords: Stop Update Alerts,Avoid Windows Prompt,Block Update Notifications,Remove Update Reminders,Disable WinUpdates,Quiet Update Warnings,Halt Updater Messages
thumbnail: https://thmb.techidaily.com/ebbfde368b81e7f396fe512ace44b149bef6fef394a1d6fd8cfa20e2c4a0b6c3.jpg
---

## Eliminate Windows Updates Prompts

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-the-pathway-to-delicate-audible-reduction-within-lumafusion/"><u>[New] 2024 Approved The Pathway to Delicate Audible Reduction Within Lumafusion</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-prioritize-these-5-facts-when-tiktoking-on-macos-for-2024/"><u>[New] Prioritize These 5 Facts When TikToking on macOS for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-streamlining-your-gaming-experience-windows-11-edition-for-2024/"><u>[New] Streamlining Your Gaming Experience Windows 11 Edition for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-seamless-music-integration-transform-your-favorite-tunes-into-youtube-content/"><u>[Updated] 2024 Approved Seamless Music Integration Transform Your Favorite Tunes Into YouTube Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-exclusive-fb-picturevid-producer-no-fee/"><u>[Updated] In 2024, Exclusive FB Picture/Vid Producer - No Fee</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphers-to-declutter-implementing-insightful-file-comments/"><u>Deciphers to Declutter: Implementing Insightful File Comments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-way-to-turn-onoff-in-hand-typing-windows/"><u>Easy Way to Turn On/Off In-Hand Typing Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-searcher-that-skips-results/"><u>Fixing Windows 10/11 Searcher That Skips Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-notepad-crashing-on-windows/"><u>How to Fix Notepad Crashing on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Realme V30T? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-the-esc-key-not-working-in-windows-try-these-fixes/"><u>Is the Esc Key Not Working in Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsofts-world-efficient-commands-at-your-fingertips/"><u>Navigating Microsoft's World: Efficient Commands at Your Fingertips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-no-mistakes-essential-errors-to-evade-in-windows-11/"><u>Navigating No Mistakes: Essential Errors to Evade in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-glitches-fixing-ms-store-in-windows-10-and-11/"><u>Overcoming Glitches: Fixing MS Store in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-xp019-error/"><u>Overcoming Windows XP019 Error</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-most-effective-extended-range-routers-our-expert-picks/"><u>The Most Effective Extended-Range Routers – Our Expert Picks</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-ultimate-gif-preservation-toolkit-for-twitters-2024/"><u>The Ultimate GIF Preservation Toolkit for Twitter's 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-best-mts-video-editors-top-picks/"><u>Updated 2024 Approved Best MTS Video Editors Top Picks</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Oppo Find N3? | Dr.fone</u></a></li>
</ul></div>

