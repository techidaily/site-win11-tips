---
title: Silencing Windows Update Alerts
date: 2024-10-07T17:50:46.543Z
updated: 2024-10-09T06:31:41.328Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Silencing Windows Update Alerts
excerpt: This Article Describes Silencing Windows Update Alerts
keywords: Stop Windows Update Notifications,Mute Update Alerts WinXP/Win10,Quiet System Updates Windows,Bypass Update Interruptions,Halt Windows Update Alarms,Disable Update Prompts Windows,Prevent Windows Update Alerts
thumbnail: https://thmb.techidaily.com/606be4e6c5a29affde6b0062eb01d7884930a95dd58e84baf4df0ccd1b6b1a9d.jpg
---

## Silencing Windows Update Alerts

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/updated-expert-review-the-ultimate-guide-to-capturing-your-pc-screen/"><u>[Updated] Expert Review The Ultimate Guide to Capturing Your PC Screen</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-a-beginners-guide-to-use-snapseed-photo-editing-features/"><u>2024 Approved A Beginner's Guide to Use Snapseed Photo Editing Features</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/behind-the-filter-ensuring-veritable-instagram-selfies-for-2024/"><u>Behind the Filter Ensuring Veritable Instagram Selfies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fix-guide-for-win1011s-corrupted-bin-errors/"><u>Essential Fix Guide for WIN10/11's Corrupted Bin Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/full-hd-classics-unlocked-the-perfect-scummvm-techniques-for-windows-users/"><u>Full HD Classics Unlocked: The Perfect ScummVM Techniques for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-fixing-a-frozen-control-key-in-win11/"><u>Guiding You Through Fixing a Frozen Control Key in Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-xiaomi-redmi-note-13-pro-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Xiaomi Redmi Note 13 Pro 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/insight-into-the-ascent-navigating-past-the-launch-glitches-successfully/"><u>Insight Into 'The Ascent': Navigating Past the Launch Glitches Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/journey-into-system32-folder-of-win11/"><u>Journey Into System32 Folder of Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-win-11-edge-security-using-ms-defender-application-guard/"><u>Optimize Win 11 Edge Security Using MS Defender Application Guard</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pioneers-in-the-realm-of-vr-viewing-for-2024/"><u>Pioneers in the Realm of VR Viewing for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-definitive-guide-to-ai-watermarking-solutions-revealed-on-zdnet/"><u>The Definitive Guide to AI Watermarking Solutions - Revealed on ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-optimal-performance-by-taming-high-cpu-demands/"><u>Unleashing Optimal Performance by Taming High CPU Demands</u></a></li>
</ul></div>

