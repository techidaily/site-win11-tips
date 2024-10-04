---
title: Disabling Windows Update Messages Completely
date: 2024-10-01T21:19:26.734Z
updated: 2024-10-03T23:51:15.224Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Windows Update Messages Completely
excerpt: This Article Describes Disabling Windows Update Messages Completely
keywords: Stop Windows Update Notifications,Halt UWP Updates,Eliminate Update Alerts PC,Disable Win Update Prompts,Block Windows Update Messages,Quieten System Upgrade Alarms,Eradicate Update Notifications
thumbnail: https://thmb.techidaily.com/65c45785d0c2f42e9363c89b2d70455197811e6750d98eb4741caabcbcd92e96.png
---

## Disabling Windows Update Messages Completely

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
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-ace-in-the-halls-boosting-youtube-traffic/"><u>[Updated] 2024 Approved Ace in the Halls Boosting YouTube Traffic</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-innovate-your-tiktok-storytelling-with-effects/"><u>[Updated] Innovate Your TikTok Storytelling with Effects</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-prevent-ai-driven-youtube-video-selections/"><u>2024 Approved Prevent AI-Driven YouTube Video Selections</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-realtimevid-recorder-overview/"><u>2024 Approved RealTimeVid Recorder Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-sign-out-disruption-addressing-software-conflict-on-windows-systems/"><u>Eliminating Sign Out Disruption: Addressing Software Conflict on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-zero-error-hypervisor-not-found-in-sandbox-mode/"><u>How to Rectify Zero Error: Hypervisor Not Found in Sandbox Mode</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-oneplus-ace-3-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your OnePlus Ace 3 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722998973631-join-the-pantheon-play-ascendingly-thrilling-god-of-war-fps-on-pc-platforms/"><u>Join the Pantheon: Play Ascendingly Thrilling God of War FPS on PC Platforms!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-wingets-potency-with-these-fixes-for-w11/"><u>Restore Winget's Potency with These Fixes for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-self-restarting-behavior-in-windows-11-os/"><u>Stopping Self-Restarting Behavior in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-4-windows-apps-for-webp-image-inspectors/"><u>Top 4 Windows Apps for WebP Image Inspectors</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/top-entry-level-gaming-edit-suite-reviews/"><u>Top Entry-Level Gaming Edit Suite Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-facebook-messenger-glitches-on-windows-desktop/"><u>Troubleshoot: Facebook Messenger Glitches on Windows Desktop</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlock-rumors-and-insights-into-google-tvs-impending-debut-price-forecasts-launch-dates-and-hardware-info-revealed/"><u>Unlock Rumors and Insights Into Google TV's Impending Debut - Price Forecasts, Launch Dates, and Hardware Info Revealed</u></a></li>
</ul></div>

