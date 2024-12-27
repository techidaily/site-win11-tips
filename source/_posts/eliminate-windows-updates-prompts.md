---
title: Eliminate Windows Updates Prompts
date: 2024-12-21T17:50:14.438Z
updated: 2024-12-27T19:40:18.008Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-in-2024-a-guide-to-the-best-headsets-and-goggles-in-metaverse/"><u>[New] In 2024, A Guide to the Best Headsets and Goggles in Metaverse</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-apowersoft-masterclass-top-pc-screen-recorder-analysis/"><u>[New] In 2024, Apowersoft Masterclass Top PC Screen Recorder Analysis</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-digital-text-generator-for-videos/"><u>[Updated] 2024 Approved Digital Text Generator for Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-exploring-apowersofts-pc-screen-snap-recorder/"><u>[Updated] 2024 Approved Exploring Apowersoft's PC Screen Snap Recorder</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-countdown-in-forward-the-counterintuitive-playlist-method-for-2024/"><u>[Updated] Countdown in Forward The Counterintuitive Playlist Method for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-4-methods-to-record-gameplay-on-xbox-one/"><u>[Updated] In 2024, 4 Methods to Record Gameplay on Xbox One</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-developer-skills-github-desktop-on-win-11/"><u>Empower Your Developer Skills: Github Desktop on Win 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-itel-p40plus-get-deleted-pictures-back-with-ease-and-safety-by-fonelab-android-recover-pictures/"><u>How to Itel P40+ Get Deleted Pictures Back with Ease and Safety?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-gaining-ground-on-the-groundswell-of-online-viewers/"><u>In 2024, Gaining Ground on the Groundswell of Online Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-ip-and-mac-extraction-in-windows-with-powershell/"><u>Mastering IP & MAC Extraction in Windows with PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-tactics-fixing-blank-login-on-windows-11/"><u>Precision Tactics: Fixing Blank Login on Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-enterprises-pioneering-the-future-of-the-metaverse-insights-from-zdnet/"><u>Top Enterprises Pioneering the Future of the Metaverse: Insights From ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-wi-fi-issues-in-windows-11-a-pocket-guide-with-8-solutions/"><u>Troubleshoot Wi-Fi Issues in Windows 11: A Pocket Guide with 8 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-print-management-with-windows-11s-tools-max-56-chars/"><u>Winning at Print Management with Windows 11'S Tools (Max 56 Chars)</u></a></li>
</ul></div>

