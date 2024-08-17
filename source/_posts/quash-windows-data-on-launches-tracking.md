---
title: Quash Windows Data on Launches Tracking
date: 2024-08-16T02:28:50.468Z
updated: 2024-08-17T02:28:50.468Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quash Windows Data on Launches Tracking
excerpt: This Article Describes Quash Windows Data on Launches Tracking
keywords: Quiet Tracking Data,Stop Windows Surveillance,End Windows Privacy Intrusion,Disable Windows Tracking,Halt Windows Monitoring,Eliminate Window's Data Collection,Prevent Launches on Windows Tracking
thumbnail: https://thmb.techidaily.com/8b607e0e604394629b363ae69329923c5b752c9a4c4af741aef58011df0d7554.jpg
---

## Quash Windows Data on Launches Tracking

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-the-future-of-development-understanding-the-impact-of-next-gen-frameworks/"><u>[New] 2024 Approved  The Future of Development  Understanding the Impact of Next-Gen Frameworks</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-what-drives-youtubes-content-creator-hub/"><u>[New] 2024 Approved  What Drives YouTube's Content Creator Hub?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/levate-your-profit-with-these-top-10-simplified-youtube-business-channels/"><u>[New] Elevate Your Profit with These Top 10 Simplified YouTube Business Channels</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-emphasize-eye-catcher-excise-background-in-photo-editing/"><u>[New] In 2024, Emphasize Eye-Catcher  Excise Background in Photo Editing</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-switching-onoff-comment-functionality-on-youtube/"><u>[New] Switching On/Off Comment Functionality on YouTube</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-vsco-photo-workflow-analysis/"><u>[New] The Ultimate VSCO Photo Workflow Analysis</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-essential-audio-techniques-capturing-clear-sound/"><u>[Updated] 2024 Approved  Essential Audio Techniques  Capturing Clear Sound</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-the-beginners-guide-to-pioneering-minecraft-recordings-on-mac/"><u>[Updated] 2024 Approved  The Beginner's Guide to Pioneering Minecraft Recordings on Mac</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-optimize-youtube-submissions-for-extended-films-for-2024/"><u>[Updated] How to Optimize YouTube Submissions for Extended Films for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-elevate-visibility-comprehensive-guide-to-video-marketing-titles/"><u>[Updated] In 2024, Elevate Visibility  Comprehensive Guide to Video Marketing Titles</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-leading-edge-applications-surpassing-traditional-fbx-file-capture/"><u>[Updated] In 2024, Leading-Edge Applications Surpassing Traditional FBX File Capture</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-top-5-time-lapse-screen-recorder-for-2024/"><u>[Updated] Top 5 Time-Lapse Screen Recorder for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/10-top-ai-tools-to-invent-unique-podcast-names-online/"><u>10 Top AI Tools to Invent Unique Podcast Names Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-photo-preview-boards-in-win-11/"><u>Adjusting Photo Preview Boards in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-introduction-to-windows-exepe-file-formats/"><u>An Introduction to Windows EXE/PE File Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apps-calm-demeanor-hides-computational-challenges-for-windows-users/"><u>Apps' Calm Demeanor Hides Computational Challenges for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-review-pcmac-comparison/"><u>ASUS Zenbook 14 OLED Review: PC/Mac Comparison?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-file-sync-solutions-for-windows-users/"><u>Best File Sync Solutions for Windows Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/boost-windows-graphical-output-with-latest-intel-driver-update/"><u>Boost Windows' Graphical Output with Latest Intel Driver Update</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-microsofts-zero-error-on-windows-11/"><u>Bypassing Microsoft's Zero-Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-and-siri-perfecting-iphone-conversations/"><u>ChatGPT and Siri: Perfecting iPhone Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-windows-steam-broadcaster-errors/"><u>Combatting Windows Steam Broadcaster Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-failures-qt-platform-support-error-at-launch/"><u>Correcting Failures: 'Qt Platform Support' Error at Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-approaches-to-adjacent-and-distinct-windows-partition-merging/"><u>Cutting-Edge Approaches to Adjacent and Distinct Windows Partition Merging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-incorrect-parameters-for-winloadlib/"><u>Dealing with Incorrect Parameters for WinLoadLib</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-subnet-tweak-for-experienced-users-win11/"><u>Effortless Subnet Tweak for Experienced Users, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-w11-desktop-customization-essentials/"><u>Effortless W11 Desktop Customization Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-terminal-usage-make-it-primary-choice/"><u>Elevate Your Terminal Usage: Make It Primary Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/envisioning-the-ideal-user-experience-in-windows-11/"><u>Envisioning the Ideal User Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-11s-error-diagnostic-solutions/"><u>Exploiting Windows 11'S Error Diagnostic Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hidden-options-mastery-of-lost-control-configurations/"><u>Explore Hidden Options: Mastery of Lost Control Configurations</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/french-novel-selections-top-picks-for-new-language-learners/"><u>French Novel Selections: Top Picks for New Language Learners</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-vivo-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Vivo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-the-focus-wallpaper-icon-on-windows-11/"><u>How to Clear the Focus Wallpaper Icon on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-mdm-from-iphone-11-pro-by-drfone-ios-unlock-ios-unlock/"><u>How to Remove MDM from iPhone 11 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-onedrive-on-a-windows-machine/"><u>How To Unlock Your OneDrive on a Windows Machine</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-13-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 13? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-best-lava-frp-bypass-guide-by-drfone-android/"><u>In 2024, Best Lava FRP Bypass Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-poco-m6-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Poco M6 5G Phones with/without a PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-vivo-y27s-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Vivo Y27s Phones with/without a PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-launching-at-optimal-times-a-podcast-guide/"><u>In 2024, Launching at Optimal Times  A Podcast Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-logitechs-elite-4k-webcam-exhaustive-features-and-usability/"><u>In 2024, Logitech’s Elite 4K Webcam  Exhaustive Features & Usability</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-seamless-social-integration-twitter-and-facebook-connections/"><u>In 2024, Seamless Social Integration  Twitter & Facebook Connections</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-the-complete-ginger-island-in-stardew/"><u>In 2024, The Complete Ginger Island in Stardew</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-apk-deployment-for-win-11-users/"><u>Instant APK Deployment for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-yourphoneexe-malware-insights-on-windows-87/"><u>Is YourPhone.exe Malware? Insights on Windows 8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-forward-in-windows-video-management-integrate-tdarrs-distributed-capabilities/"><u>Leap Forward in Windows Video Management: Integrate Tdarr's Distributed Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-windows-files-disabling-read-only-status/"><u>Manipulating Windows Files: Disabling Read-Only Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-directory-management-without-renaming-features-in-windows-11/"><u>Mastering Directory Management without Renaming Features in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-epic-launcher-sign-in-on-pc/"><u>Mastering the Art of Epic Launcher Sign-In on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restart-printers-automatic-service-in-win/"><u>Methods to Restart Printer's Automatic Service in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiple-routes-for-opening-utilities-on-windows-systems/"><u>Multiple Routes for Opening Utilities on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hazards-of-cheap-windows-key-purchases/"><u>Navigating the Hazards of Cheap Windows Key Purchases</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-check-out-the-article-to-add-subtitles-to-final-cut-pro-via-the-simple-step-by-step-tutorial-also-the-steps-are-similar-for-adding-caption/"><u>New 2024 Approved Check Out the Article to Add Subtitles to Final Cut Pro via the Simple Step-by-Step Tutorial! Also, the Steps Are Similar for Adding Captions in FCPX</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-top-3d-animation-software-for-mobile-devices-free-to-download/"><u>New 2024 Approved Top 3D Animation Software for Mobile Devices (Free to Download)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-11-search-top-5-expert-methods/"><u>Optimize Your Windows 11 Search: Top 5 Expert Methods</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-nokia-150-2023-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from Nokia 150 (2023)</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-apple-iphone-7-and-browser-drfone-by-drfone-virtual-ios/"><u>Prevent Cross-Site Tracking on Apple iPhone 7 and Browser | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-discord-launch-and-update-check-with-windows-startup/"><u>Preventing Discord Launch and Update Check with Windows Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-absent-d3dx939dll-on-windows-11/"><u>Remedying Absent D3DX9_39.dll on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-disabled-volume-snapshots/"><u>Restoring Functionality to Disabled Volume Snapshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-error-0xa00f425d-in-windows-camera/"><u>Steps to Eliminate Error 0xA00F425D in Windows Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-by-unrealcefsubprocess-on-systems/"><u>Strategies to Reduce CPU and RAM Overuse by UnrealCEFSubprocess on Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-geforce-now-error-xc0f1103f/"><u>Tackling Windows 11'S GeForce Now Error Xc0f1103f</u></a></li>
<li><a href="https://win-blog.techidaily.com/the-repetitive-nature-of-its-resource-management-and-building-systems-limited-long-term-engagement-without-significant-content-updates-or-game-mechanic-chan567/"><u>The Repetitive Nature of Its Resource Management and Building Systems Limited Long-Term Engagement without Significant Content Updates or Game Mechanic Changes.</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-samsung-galaxy-s23-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-secrets-of-running-imessage-on-windows/"><u>Uncovering the Secrets of Running iMessage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-approach-to-allocated-ram/"><u>Understanding Windows' Approach to Allocated RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-ways-for-swift-epic-game-loading/"><u>Unveiling Windows Ways for Swift Epic Game Loading</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-unchaining-the-cadence-online-methods-for-detecting-and-isolating-musics-pulse/"><u>Updated In 2024, Unchaining the Cadence Online Methods for Detecting and Isolating Musics Pulse</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-infinix-gt-10-pro-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Infinix GT 10 Pro? Here is How | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-unveiled-major-updates-on-windows-11-vs-10/"><u>Windows Unveiled: Major Updates on Windows 11 Vs. 10</u></a></li>
</ul></div>
