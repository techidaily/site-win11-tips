---
title: "Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments"
date: 2024-08-08T10:58:48.230Z
updated: 2024-08-09T10:58:48.230Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments"
excerpt: "This Article Describes Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments"
keywords: Word Text Attachment Guide,Avoid Editing Attachments,Text-Only Doc Settings,Word No Edit Attachments,Office Products Preview,Save Original Opened Files,Word Setup for Copy Paste
thumbnail: https://thmb.techidaily.com/07fa8cadb13240ad4114bdffce36c4f17cee86cd9ffa9ec58a8ecda669ea9207.jpg
---

## Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.


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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-selecting-the-perfect-wedding-countdown-clock-for-android-and-ios-devices/"><u>[New] 2024 Approved  Selecting the Perfect Wedding Countdown Clock for Android & iOS Devices</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-behind-the-glamour-10-honest-insights-into-reels-for-2024/"><u>[New] Behind the Glamour  10 Honest Insights Into Reels for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-effortless-film-logging-how-to-use-devices-like-pros-for-2024/"><u>[New] Effortless Film Logging  How to Use Devices Like Pros for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovative-approaches-to-background-blanketing-in-affinity-photo/"><u>[New] Innovative Approaches to Background Blanketing in Affinity Photo</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-latest-android-selection-ranked-top-10-apps-for-saving-facebook-videos/"><u>[New] Latest Android Selection  Ranked Top 10 Apps for Saving Facebook Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-powerful-films-for-purpose-and-positivity/"><u>[New] Powerful Films for Purpose and Positivity</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-prime-10-youtube-historians-top-picks-for-learning/"><u>[New] Prime 10  YouTube Historians’ Top Picks for Learning</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-secure-and-detailed-best-ways-to-document-fb-call-footage-for-2024/"><u>[New] Secure & Detailed  Best Ways to Document FB Call Footage for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-step-by-step-guide-to-compliant-twitter-media-posts/"><u>[New] Step-by-Step Guide to Compliant Twitter Media Posts</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-top-10-trending-videos-on-twitter-for-2024/"><u>[New] Top 10 Trending Videos on Twitter for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-top-ranked-mobile-melody-design-experts-for-2024/"><u>[New] Top-Ranked  Mobile Melody Design Experts for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-unveiling-social-screens-share-your-monitor-on-fb-live-for-2024/"><u>[New] Unveiling Social Screens  Share Your Monitor on FB Live for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-aspect-ratio-preferences-on-facebook-vids-for-2024/"><u>[Updated] Aspect Ratio Preferences on Facebook Vids for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-software-a-gamers-livestream-compendium/"><u>[Updated] Best Software  A Gamers' Livestream Compendium</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-commanding-youtube-realm-through-strategic-creator-studio-utilization-for-2024/"><u>[Updated] Commanding YouTube Realm Through Strategic Creator Studio Utilization for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-engaging-excellence-best-story-filter-compilation-for-2024/"><u>[Updated] Engaging Excellence  Best Story Filter Compilation for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-expert-take-on-camstudios-recorder-efficacy-for-2024/"><u>[Updated] Expert Take on CamStudio's Recorder Efficacy for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-front-seat-recreation-10-non-athletic-delights/"><u>[Updated] Front Seat Recreation  10 Non-Athletic Delights</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-effortless-exchange-idevice-images-and-videos/"><u>[Updated] In 2024, Effortless Exchange  IDevice Images & Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-prime-panzoid-layout-libraries-for-2024/"><u>[Updated] Prime Panzoid Layout Libraries for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-ultimate-voyage-guide-from-novice-to-esteemed-travel-blogger/"><u>[Updated] The Ultimate Voyage Guide  From Novice to Esteemed Travel Blogger</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-10-best-free-video-conferencing-services-with-screen-sharing/"><u>2024 Approved  10 Best Free Video Conferencing Services with Screen Sharing</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-content-composer-arena/"><u>2024 Approved  Content Composer Arena</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-is-consumer-feedback-compensated-in-vlogs/"><u>2024 Approved  Is Consumer Feedback Compensated in Vlogs?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-paving-the-way-to-success-with-innovative-medical-ads/"><u>2024 Approved  Paving the Way to Success with Innovative Medical Ads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-critical-tweaks-to-reactivate-firewall/"><u>4 Critical Tweaks to Reactivate Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-a-windows-device-thats-stuck-in-dark-mode/"><u>5 Ways to Fix a Windows Device That's Stuck in Dark Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simple-guide-to-windows-11-home-interface-activation/"><u>A Simple Guide to Windows 11 Home Interface Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-power-up-window-10-and-11-with-keybinds/"><u>Accelerate Tasks: Power-Up Window 10 and 11 with Keybinds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-outlook-preview-via-windows-11-os/"><u>Accessing Outlook Preview via Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimum-ssd-speed-on-windows-via-ssdfresh/"><u>Achieve Optimum SSD Speed on Windows via SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-excellence-perfecting-your-consoles-gamepad-functionality/"><u>Achieving Excellence: Perfecting Your Console's Gamepad Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-widget-bar-features/"><u>Activating Windows 11 Widget Bar Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-access-dilemnas-on-windows-os/"><u>Addressing File Access Dilemnas on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-extraction-failure-fix-for-error-1152-in-win/"><u>Addressing File Extraction Failure: Fix for Error 1152 in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-in-windows-vm-hosting-platforms/"><u>Addressing Insufficient RAM in Windows VM Hosting Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lossed-graphics-support-in-overwatch-2/"><u>Addressing Lossed Graphics Support in Overwatch 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-interface-dll-failure-on-pc/"><u>Addressing Steam Interface Dll Failure on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-unresponsive-task-issue-in-windows-os/"><u>Addressing the 'Unresponsive Task' Issue in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-reset-account-lockouts-after-failed-logins-in-windows-11/"><u>Adjusting Reset Account Lockouts After Failed Logins in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-task-management-adding-cli-toolbar-in-win11-taskmgr/"><u>Advanced Task Management: Adding CLI Toolbar in Win11 TaskMgr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-in-powertoys-for-file-security/"><u>Advanced Techniques in PowerToys for File Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advice-when-windows-doesnt-recognize-powershell-commands/"><u>Advice When Windows Doesn't Recognize PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alteration-of-login-failure-counter-windows-11-user-guide/"><u>Alteration of Login Failure Counter: Windows 11 User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-user-frustrations-in-windows-11-transition/"><u>Analyzing User Frustrations in Windows 11 Transition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-computer-speakers-not-working-how-to-fix-having-no-sound/"><u>Are Your Computer Speakers Not Working? How to Fix Having No Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-s15-oled-experience-merging-chic-and-versatile-features/"><u>Asus S15 OLED Experience: Merging Chic & Versatile Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-drivers-guide-for-a-fresh-windows-experience/"><u>Audio Drivers' Guide for a Fresh Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-excessive-cpu-demand-by-windows-extender/"><u>Avoiding Excessive CPU Demand by Windows Extender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-nvidia-writes-of-error-3-in-win1011/"><u>Avoiding NVIDIA' Writes of Error 3 in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bandwidth-breakdown-4-ways-to-measure-your-ethernets-pace/"><u>Bandwidth Breakdown: 4 Ways to Measure Your Ethernet's Pace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-delay-in-sw-top-tips-to-speed-up-your-bf2-gameplay/"><u>Beat Delay in SW: Top Tips to Speed Up Your BF2 Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-windows-media-player-activation-process/"><u>Beginning Windows Media Player Activation Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-apps-to-skyrocket-your-windows-workflow-and-efficiency/"><u>Best Apps to Skyrocket Your Windows Workflow & Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-tools-for-mp4-and-mov-clips/"><u>Best Windows Tools for MP4 and MOV Clips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bigger-better-barely-noticed-by-mini-pcs-users/"><u>Bigger, Better Barely Noticed by Mini PCs' Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-terminal-as-favorite-app/"><u>Boost Productivity with Terminal as Favorite App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-development-with-these-wsl-2-secrets/"><u>Boost Your Development with These WSL 2 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-print-output-speedy-windows-printer-tips/"><u>Boosting Print Output: Speedy WIndows Printer Tips</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-motorola-moto-g84-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Motorola Moto G84 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://extra-tips.techidaily.com/explore-the-latest-in-picsart-a-comprehensive-guide-and-review/"><u>Explore the Latest in PicsArt - A Comprehensive Guide and Review</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/full-screen-issue-windowed-display-on-monitor-with-win11/"><u>Full-Screen Issue: Windowed Display on Monitor with Win11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/google-wireless-nest-doorbell-battery-version-detailed-assessment-and-review/"><u>Google Wireless Nest Doorbell (Battery Version) - Detailed Assessment & Review</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>How to Simulate GPS Movement in AR games On Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-find-and-buy-premium-youtube-ringtone-videos-easily/"><u>In 2024, Find & Buy Premium YouTube Ringtone Videos Easily</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-merge-videos-without-watermarks-top-5-tools/"><u>New Merge Videos Without Watermarks Top 5 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292218138-quicker-downloads-for-battlenet-games-win-pcs-now/"><u>Quicker Downloads for Battle.net Games, Win PCs Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719317772933-reconcile-your-win-plus-print-discrepinasions-with-effective-solutions/"><u>Reconcile Your Win + Print Discrepinasions with Effective Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719349707624-resurrect-your-xbox-on-a-slow-pc-steps-to-take/"><u>Resurrect Your Xbox on a Slow PC: Steps to Take!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722171151494-unveiling-the-advancements-in-googles-bard-ai-via-palm-2-explore-7-features/"><u>Unveiling the Advancements in Google's Bard AI via PaLM 2 - Explore 7 Features</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-10-free-avi-merger-tools-to-combine-avi-videos-effortlessly-for-2024/"><u>Updated 10 Free AVI Merger Tools to Combine AVI Videos Effortlessly for 2024</u></a></li>
</ul></div>
