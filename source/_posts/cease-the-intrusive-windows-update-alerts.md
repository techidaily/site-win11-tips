---
title: Cease the Intrusive Windows Update Alerts
date: 2024-07-29T08:14:56.410Z
updated: 2024-07-30T08:14:56.410Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cease the Intrusive Windows Update Alerts
excerpt: This Article Describes Cease the Intrusive Windows Update Alerts
keywords: Stop Update Notifications,End Update Interruptions,Silence Update Prompts,Prevent Update Alerts,Halt Windows Updates,Mute Update Messages,Block Update Warnings
thumbnail: https://thmb.techidaily.com/e90a41374ab8bcea029035e600ef5fff009cee16ec9e8eead9f3969598aefde0.jpg
---

## Cease the Intrusive Windows Update Alerts

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-data.techidaily.com/xpert-smartphone-photo-and-film-capture-iphoneandroid-comparison/"><u>[New] Expert Smartphone Photo & Film Capture  IPhone/Android Comparison</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-lone-listeners-conundrum-cure-method-for-2024/"><u>[New] Lone Listener's Conundrum  Cure Method for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-steps-to-successful-remote-podcasting-for-2024/"><u>[New] Steps to Successful Remote Podcasting for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-five-full-frame-cameras-for-uhd-capture/"><u>[Updated] Best Five Full Frame Cameras for UHD Capture</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-comprehensive-update-best-android-apps-for-downloading-facebook-videos/"><u>[Updated] Comprehensive Update  Best Android Apps for Downloading Facebook Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-choose-the-best-free-introduction-maker-for-2024/"><u>[Updated] How to Choose the Best Free Introduction Maker for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-basic-tactics-to-archive-webcam-chats/"><u>[Updated] In 2024, Basic Tactics to Archive Webcam Chats</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-keep-and-store-your-linkedin-videos-with-these-high-quality-downloader-apps/"><u>[Updated] Keep and Store Your LinkedIn Videos with These High-Quality Downloader Apps</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-tailor-made-youtube-url-strategies-an-easier-approach/"><u>[Updated] Tailor-Made YouTube URL Strategies  An Easier Approach</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unleash-your-creative-vision-a-guide-to-android-editors/"><u>[Updated] Unleash Your Creative Vision  A Guide to Android Editors</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-unveiling-the-secrets-of-live-broadcasting-on-instagram-through-obs-for-2024/"><u>[Updated] Unveiling the Secrets of Live Broadcasting on Instagram Through OBS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-display-settings-in-windows-11/"><u>10 Ways to Open the Display Settings in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-strategies-for-seamless-sound-transitions-in-adobe-premiere/"><u>2024 Approved  Expert Strategies for Seamless Sound Transitions in Adobe Premiere</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-from-novice-to-expert-free-lut-techniques-for-color-grading/"><u>2024 Approved  From Novice to Expert  Free LUT Techniques for Color Grading</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-create-an-affordable-customizable-virtual-reality-gear/"><u>2024 Approved  How to Create an Affordable, Customizable Virtual Reality Gear</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tricks-to-correct-your-pcs-pink-screen-misstep/"><u>5 Tricks to Correct Your PC's Pink Screen Misstep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-steps-to-tame-the-gpu-hungry-desktop-window-manager/"><u>7 Steps to Tame the GPU-Hungry Desktop Window Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-for-switching-from-pin-to-passwords-in-windows-11-user-interface/"><u>A Guide for Switching From PIN to Passwords in Windows 11 User Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-recognizing-and-addressing-uninstalled-disk-issue-win-11-style/"><u>A Practical Guide to Recognizing & Addressing 'Uninstalled Disk' Issue, Win 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-windows-in-minutes-with-handy-shorthand/"><u>Ace Windows in Minutes with Handy Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-mastery-accessing-windows-admin-settings/"><u>Achieving Mastery: Accessing Windows Admin Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-themed-settings-for-education-on-windows-11/"><u>Activating Themed Settings for Education on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-privileges-and-permissions-panel/"><u>Activating Windows 11 Privileges and Permissions Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-digital-imagery-to-your-desktop/"><u>Adding Digital Imagery to Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-volume-shadow-copy-on-pcs/"><u>Addressing Disabled Volume Shadow Copy on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-domain-services-printer-errors-win11-tips-and-tricks/"><u>Addressing Domain Services Printer Errors: Win11 Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-pages-in-the-explorer-bar/"><u>Addressing Empty Pages in the Explorer Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inaccessible-values-in-windows-applications/"><u>Addressing Inaccessible Values in Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-touch-keyboard-default-in-windows-11-pro/"><u>Adjust Touch Keyboard Default in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-password-policy-updating-lockout-value-after-failed-attempts/"><u>Altering Password Policy: Updating Lockout Value After Failed Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-gaming-experience-optimize-amd-graphics-on-pc/"><u>Amplify Gaming Experience: Optimize AMD Graphics on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-ram-with-advanced-virtual-memory-settings/"><u>Amplifying RAM with Advanced Virtual Memory Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-impact-of-audio-device-isolation/"><u>Analyzing the Impact of Audio Device Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artists-rejoice-best-windows-11-drawing-apps/"><u>Artists Rejoice: Best Windows 11 Drawing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-discord-updates-and-autostart-on-windows-10/"><u>Avoid Discord Updates & Autostart on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719315730924-avoid-frustration-fixing-the-missing-print-feature-on-windows/"><u>Avoid Frustration: Fixing the Missing Print Feature on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-wows-endless-loop-fix-error-132-in-win-editions/"><u>Avoid WoW's Endless Loop: Fix Error 132 in Win Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-pc-to-god-like-powers-with-windows-11/"><u>Awaken Your PC to God-Like Powers with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-fixing-irq-for-clear-audio/"><u>Balancing Act: Fixing IRQ for Clear Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-security-and-usability-user-access-levels-on-windows/"><u>Balancing Security & Usability: User Access Levels on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-browser-safety-on-windows-11-with-the-implementation-of-defender-aguard/"><u>Boost Browser Safety on Windows 11 with the Implementation of Defender Aguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-using-powertoys-copy-pasting-features/"><u>Boost Efficiency: Using PowerToys' Copy-Pasting Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-speed-typing-aids-unleashed/"><u>Boost Your Speed: Typing Aids Unleashed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-usability-of-legacy-systems-for-seniors/"><u>Boosting Usability of Legacy Systems for Seniors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/disseminating-tweeted-videos-on-the-worlds-biggest-social-site/"><u>Disseminating Tweeted Videos on the World's Biggest Social Site</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380036891-dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/export-live-webcam-video-through-vlc/"><u>Export Live Webcam Video Through VLC</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-oppo-reno-10-proplus-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Oppo Reno 10 Pro+ 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-harness-the-power-of-insights-a-curated-list-of-instagram-performance-trackers/"><u>In 2024, Harness the Power of Insights  A Curated List of Instagram Performance Trackers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-smiles-snorts-and-sighs-top-10-ig-meme-communities-of-the-decade/"><u>In 2024, Smiles, Snorts & Sighs  Top 10 IG Meme Communities of the Decade</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-solutions-to-spy-on-apple-iphone-14-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-ios/"><u>In 2024, Solutions to Spy on Apple iPhone 14 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unveiling-secrets-to-extending-reach-with-youtube-lists/"><u>In 2024, Unveiling Secrets to Extending Reach with YouTube Lists</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-unveiling-the-best-strategies-how-to-boost-engagement-and-growth-on-youtube/"><u>In 2024, Unveiling the Best Strategies  How to Boost Engagement and Growth on YouTube</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-tecno-spark-20-pro-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Tecno Spark 20 Pro – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306931208-opening-troubled-chrome-remediation-tips-for-win11-users-here/"><u>Opening Troubled Chrome: Remediation Tips for Win11 Users Here.</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/precise-guide-to-navigating-adobe-cloud-then-comparing-other-methods-for-2024/"><u>Precise Guide to Navigating Adobe Cloud, Then Comparing Other Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719228801666-streamline-help-process-for-windows-snags/"><u>Streamline Help Process for Windows Snags</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/superior-free-reproduction-tools-for-switch-games/"><u>Superior Free Reproduction Tools for Switch Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719343275245-tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today!</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-4-fastest-lenovo-record-methods-for-2024/"><u>The 4 Fastest Lenovo Record Methods for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/timing-the-perfect-capture-and-labeling-for-2024/"><u>Timing the Perfect Capture and Labeling for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341599288-windows-chatbot-simulation-localize-for-free-with-gpt4all/"><u>Windows ChatBot Simulation: Localize for Free with GPT4All</u></a></li>
</ul></div>
