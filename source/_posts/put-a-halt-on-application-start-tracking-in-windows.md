---
title: Put a Halt on Application Start-Tracking in Windows
date: 2024-07-29T08:09:01.245Z
updated: 2024-07-30T08:09:01.245Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Put a Halt on Application Start-Tracking in Windows
excerpt: This Article Describes Put a Halt on Application Start-Tracking in Windows
keywords: Stop App Tracking Windows,End App Start Monitoring,Cease Window Tracker Use,Disable Windows Tracking,Halt Application Logging,Block Windows Start-Tracking,Prevent App Start Monitoring
thumbnail: https://thmb.techidaily.com/97bc8f701c5a50640871957d35ec4f8e16308c84bcc3926e5048675a7dfb62d5.png
---

## Put a Halt on Application Start-Tracking in Windows

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-finding-free-music-a-producers-handbook/"><u>[New] 2024 Approved  Finding Free Music  A Producer's Handbook</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-leveraging-live-tweets-strategies-unveiled/"><u>[New] 2024 Approved  Leveraging Live Tweets  Strategies Unveiled</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-break-free-the-chuckles-ranking-20-hilarious-fb-detention-scenes/"><u>[New] In 2024, Break Free the Chuckles  Ranking 20 Hilarious FB Detention Scenes</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-ultimate-guide-new-camera-recording-tech-overview/"><u>[New] In 2024, Ultimate Guide  New Camera Recording Tech Overview</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-unlock-your-screen-androids-premier-free-recorder-tools/"><u>[Updated] 2024 Approved  Unlock Your Screen  Android's Premier Free Recorder Tools</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-from-spectator-to-participant-joining-on-tiktok-live-for-2024/"><u>[Updated] From Spectator to Participant  Joining on TikTok Live for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premium-combo-exclusive-afx-design-tools/"><u>[Updated] Premium Combo  Exclusive AFX Design Tools</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-master-the-art-of-gaming-best-monitors-and-tvs-for-xbox-series-x/"><u>2024 Approved  Master the Art of Gaming  Best Monitors & TVs For Xbox Series X</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-top-audio-respeeders-fast-fix-for-pace-modification/"><u>2024 Approved  Top Audio Respeeders  Fast-Fix for Pace Modification</u></a></li>
<li><a href="https://screen-capture.techidaily.com/6-ways-to-record-mov-files-on-windows-10-for-2024/"><u>6 Ways to Record .mov Files on Windows 10 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-tackle-error-0x800700e1-on-windows-11-devices/"><u>Approaches to Tackle Error 0X800700E1 on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-and-gpu-for-smooth-online-engagement/"><u>Balancing CPU and GPU for Smooth Online Engagement</u></a></li>
<li><a href="https://extra-hints.techidaily.com/breakthrough-14-text-animation-samples-for-2024/"><u>Breakthrough 14 Text Animation Samples for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/closed-folder-fixes-for-w11w10-double-click-malfunction/"><u>Closed Folder Fixes for W11/W10 Double-Click Malfunction</u></a></li>
<li><a href="https://screen-recording.techidaily.com/enhancing-streaming-quality-using-obs-plus-zoom-for-2024/"><u>Enhancing Streaming Quality Using OBS + Zoom for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-on-keeping-windows-11s-notifications-alive/"><u>Essential Insights on Keeping Windows 11'S Notifications Alive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-gptclone-at-home-for-free-on-windows/"><u>Experience GPTClone at Home for FREE on Windows!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-dangers-of-keygen-malware-symptoms-and-removal-strategies/"><u>Exploring the Dangers of Keygen Malware: Symptoms & Removal Strategies</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-from-apple-iphone-12-pro-by-drfone-ios/"><u>How to Fix Locked Apple ID from Apple iPhone 12 Pro</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-nokia-c300-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Nokia C300</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-analyzing-the-core-disparities-between-metaverse-and-multiplemetaverse/"><u>In 2024, Analyzing the Core Disparities Between Metaverse and MultipleMetaverse</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigate-the-art-of-film-with-xps-easy-tools/"><u>In 2024, Navigate the Art of Film with XP's Easy Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-infinix-zero-5g-2023-turbo-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Infinix Zero 5G 2023 Turbo Screen | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-xiaomi-redmi-12-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Xiaomi Redmi 12 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-nubia-z50s-pro-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Nubia Z50S Pro Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-xiaomi-redmi-k70es-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Xiaomi Redmi K70Es Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-windows-11s-disguised-search-action/"><u>Initiating Windows 11'S Disguised Search Action</u></a></li>
<li><a href="https://extra-information.techidaily.com/inspire-chuckles-designing-memes-on-kapwing/"><u>Inspire Chuckles – Designing Memes on Kapwing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-mouse-movement-how-to-stop-acceleration/"><u>Master Your Mouse Movement: How to Stop Acceleration</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-the-art-of-purchasing-drones-insider-advice-for-2024/"><u>Mastering the Art of Purchasing Drones  Insider Advice for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-free-fright-fest-top-websites-harvesting-spooky-sound-samples/"><u>New 2024 Approved Free Fright Fest Top Websites Harvesting Spooky Sound Samples</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-detection-hurdles-for-controllers-on-steam/"><u>Overcoming Detection Hurdles for Controllers on Steam</u></a></li>
<li><a href="https://fix-guide.techidaily.com/poco-c50-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Poco C50 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-tips-stacking-windows-sticky-notes-high/"><u>Pro Tips: Stacking Windows Sticky Notes High</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-battery-alert-strategies-for-win-users/"><u>Proactive Battery Alert Strategies for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-restoration-techniques-to-reactivate-virus-protection-in-windows/"><u>Quick Restoration Techniques to Reactivate Virus Protection in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-backup-routine-for-nvidia-panel-configurations/"><u>Re-Establishing Backup Routine for Nvidia Panel Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-synapse-functionality-with-razer-devices-on-windows/"><u>Restoring Synapse Functionality with Razer Devices on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-cyber-voyage-checking-stable-connections-on-pc/"><u>Securing Your Cyber Voyage: Checking Stable Connections on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-top-tier-nvidia-drivers-focusing-on-purpose/"><u>Selecting Top-Tier Nvidia Drivers - Focusing on Purpose</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-windows-on-steam-deck-made-simple/"><u>Setting Up Windows on Steam Deck Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lowering-cpu-intensity-in-gaming-windows/"><u>Solutions for Lowering CPU Intensity in Gaming Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-errors-in-win1011-0x8007045d/"><u>Solving Common Errors in Win10/11 - 0X8007045D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-intelligent-assistant-protocol-on-windows/"><u>Stopping Intelligent Assistant Protocol on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-audio-tracking-on-windows-powered-screencasts/"><u>Strategies for Audio Tracking on Windows-Powered Screencasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-workflow-programmatic-shortcuts-in-winos/"><u>Streamline Workflow: Programmatic Shortcuts in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-your-schedule-how-to-reset-windows-time-service/"><u>Sync Your Schedule: How to Reset Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unanticipated-error-messages-in-wins-secure/"><u>Tackling Unanticipated Error Messages in WINS Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-most-reliable-brightness-tools-for-windows-multi-display-users/"><u>The 6 Most Reliable Brightness Tools For Windows Multi-Display Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tech-companion-asus-vivobook-s-15-review/"><u>The Ultimate Tech Companion: Asus Vivobook S 15 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-xbox-game-pass-error-0x000-on-windows-11-systems/"><u>Understanding and Correcting Xbox Game Pass Error 0X000_ on Windows 11 Systems</u></a></li>
</ul></div>
