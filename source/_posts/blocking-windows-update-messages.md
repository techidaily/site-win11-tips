---
title: Blocking Windows Update Messages
date: 2024-08-16T01:08:25.726Z
updated: 2024-08-17T01:08:25.726Z
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

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-a-guide-to-instagram-video-brilliance-with-templates-for-2024/"><u>[New] A Guide to Instagram Video Brilliance with Templates for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-ultimate-tech-gems-best-desktops-revealed/"><u>[New] In 2024, Ultimate Tech Gems - Best Desktops Revealed</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-turn-youtube-clips-into-animated-gifs-step-by-step-guide/"><u>[New] Turn Youtube Clips Into Animated GIFs  Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-master-level-insights-into-crafting-unique-and-memorable-instagram-vids/"><u>[Updated] 2024 Approved  Master Level Insights Into Crafting Unique and Memorable Instagram Vids</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-harnessing-video-magic-channel-creation-wizardry/"><u>[Updated] Harnessing Video Magic  Channel Creation Wizardry</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-ultimate-guide-to-documenting-your-vr-experiences/"><u>[Updated] In 2024, Ultimate Guide to Documenting Your VR Experiences</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-top-vr-game-engines-2023-update/"><u>[Updated] Top VR Game Engines -2023 Update</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-uniting-youtube-videos-a-comprehensive-approach/"><u>[Updated] Uniting YouTube Videos  A Comprehensive Approach</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-screensnap-it-all-high-quality-netflix-on-mac/"><u>2024 Approved  ScreenSnap It All  High-Quality Netflix on Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/assessing-ea-plays-financial-viability/"><u>Assessing EA Play's Financial Viability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curbing-unnecessary-cpu-spikes-tips-and-tricks/"><u>Curbing Unnecessary CPU Spikes: Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-enhanced-ui-in-windows-11/"><u>Discovering Enhanced UI in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-ais-influence-on-the-newest-windows-11-landscape/"><u>Dissecting AI's Influence on the Newest Windows 11 Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/emancipate-chatbots-on-windows-using-freedomgpt/"><u>Emancipate ChatBots on Windows: Using FreedomGPT</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/essential-tips-for-sims-4-video-gaming/"><u>Essential Tips for Sims 4 Video Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exorcising-sound-demons-the-internal-paudio-issue-fix/"><u>Exorcising Sound Demons: The Internal PAudio Issue Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-insights-from-docx-to-pdf-mastery-with-windows-11/"><u>Expert Insights: From Docx to PDF Mastery with Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/framemaster-z-unbeatable-image-quality-at-an-extreme-price/"><u>FrameMaster Z: Unbeatable Image Quality at an Extreme Price</u></a></li>
<li><a href="https://tech-hub.techidaily.com/future-trends-in-generative-ai-and-chatbots-what-innovations-lie-beneath/"><u>Future Trends in Generative AI and Chatbots: What Innovations Lie Beneath?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-activating-user-defined-permissions-in-windows-1011/"><u>Guide to Activating User-Defined Permissions in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-pagefilesys-affect-your-computers-performance-and-safety/"><u>How Does Pagefile.sys Affect Your Computer’s Performance & Safety?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-infinix-hot-40i-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Infinix Hot 40i.</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-track-imei-number-of-honor-play-8t-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Honor Play 8T Through Google Earth?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-samsung-galaxy-z-fold-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-iphone-6s-plus-with-7-methods-drfone-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for iPhone 6s Plus With 7 Methods | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-protecting-privacy-top-10-webcam-covers/"><u>In 2024, Protecting Privacy  Top 10 Webcam Covers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-edge-security-feature-defender-application-guard/"><u>Installing Edge Security Feature: Defender Application Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invoke-smooth-pathways-into-windows-shares/"><u>Invoke Smooth Pathways Into Windows Shares</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/leading-vr-gear-for-drone-operators-for-2024/"><u>Leading VR Gear for Drone Operators for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/lock-your-poco-x6-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Poco X6 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://extra-support.techidaily.com/masterful-descriptions-for-impactful-podcast-intros-for-2024/"><u>Masterful Descriptions for Impactful Podcast Intros for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-updates-decode-error-0xc1900101/"><u>Mastering Windows 11 Updates: Decode Error 0xC1900101</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-eliminating-interrupt-error-on-windows-1011/"><u>Methods for Eliminating INTERRUPT Error on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-pc-new-tricks-staying-current-without-windows-11/"><u>Old PC, New Tricks: Staying Current Without Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unsteady-mouse-icon-windows-tips/"><u>Overcoming Unsteady Mouse Icon: Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seize-savings-unveil-windows-11-pro-key-deals/"><u>Seize Savings: Unveil Windows 11 Pro Key Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-access-errors-in-windows-a-step-by-step-guide/"><u>Solving Access Errors in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directx-update-challenges-on-windows/"><u>Solving DirectX Update Challenges on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-qr-code-scanners-in-windows-environment/"><u>Step-by-Step: QR Code Scanners in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-recover-from-roblox-crashes/"><u>Strategies to Recover From Roblox Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-microsoft-teams-hurdle-80080300-on-win11-systems/"><u>Tackling Microsoft Teams Hurdle #80080300 on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taskmasters-toolkit-best-window-based-productivity-apps-unveiled/"><u>Taskmaster's Toolkit: Best Window-Based Productivity Apps Unveiled</u></a></li>
<li><a href="https://fox-http.techidaily.com/the-insiders-guide-to-leveraging-spotify-ads-effectively-for-2024/"><u>The Insider's Guide to Leveraging Spotify Ads Effectively for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-your-taskbar-with-windows-11-tweaks/"><u>Trim Down Your Taskbar with Windows 11 Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-successful-updates/"><u>Unlocking Windows 11 Successful Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unshackling-windows-11-steps-to-bypass-security-measures/"><u>Unshackling Windows 11: Steps To Bypass Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vintage-vs-modern-atlasos-upgrade/"><u>Vintage VS Modern: AtlasOS Upgrade</u></a></li>
</ul></div>
