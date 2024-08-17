---
title: Avoiding Persistent Edge Shortcuts
date: 2024-08-16T01:07:38.615Z
updated: 2024-08-17T01:07:38.615Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoiding Persistent Edge Shortcuts
excerpt: This Article Describes Avoiding Persistent Edge Shortcuts
keywords: Avoid Edge Cutting,No Permanent Edges,Preventing Shortcuts,Stop Edge Shortcuts,Endureless Edges,Eliminate Edge Clues,Eternal Edge-Free
thumbnail: https://thmb.techidaily.com/43e39de2530caaef8af78f1650abc11434992b40c432e7b5caac8bd0f3cdf48f.png
---

## Avoiding Persistent Edge Shortcuts

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Edit Registry Files

 Another way to prevent the Microsoft Edge shortcut from reappearing on your desktop involves editing registry files.

 Making incorrect changes to the registry files can cause serious damage to your system. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

 Even if you are familiar with the registry editor, make sure you follow the steps carefully to [avoid accidentally messing up the Windows registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/).

 Use the following instructions:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft**.
5. Right-click on the **Microsoft** key and select **New > Key**. Name it **EdgeUpdate**.
6. Right-click on the **EdgeUpdate** key and select **New > DWORD (32-bit) Value**. Rename it **CreateDesktopShortcutDefault**.
7. Double-click the newly created DWORD and enter **0** in the Value data field. Then, click **OK**.
8. Within the **EdgeUpdate** key, create another DWORD and name it **RemoveDesktopShortcutDefault**.
9. Double-click the **RemoveDesktopShortcutDefault** DWORD and enter **0** in the Value data field.
10. Click **OK**.  
![EdgeUpdate Key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edgeupdate-key-in-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Modify Group Policy Settings

 If the issue remains even after you edit registry files, you can try modifying the group policy settings.

 The Group Policy Editor is only available in the Professional, Education, or Enterprise editions of Windows. That said, you can [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with a simple workaround.

 Follow these steps to modify Group Policy settings:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter**.
3. Select **Yes** if the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Microsoft Edge**.
5. Double-click the **Allow Microsoft Edge to pre-launch at Windows startup, when the system is idle, and each time Microsoft Edge is closed** policy in the right pane.
6. Select the **Disabled** option.  
![Microsoft Edge pre-launch policy selected in the Local Group Policy Editor Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window.jpg)
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Remove Microsoft Edge as the Default Browser

 Another reason why the Microsoft Edge shortcut may keep showing up on your Windows desktop is if you have set it as the default browser.

 Try [changing the default browser on your Windows PC](https://www.makeuseof.com/windows-11-change-default-browser/) to something other than Microsoft Edge and see if that fixes the issue.

 If you need help picking a reliable browser, you can check out [the best browsers for Windows](https://www.makeuseof.com/windows-11-best-browsers/).

## 5\. Restrict Other Users From Creating Desktop Shortcuts

 If you share your computer with others, someone else may be creating shortcuts for Edge without your permission. If you don't want this to happen, you can use the Group Policy Editor to prevent other users from creating desktop shortcuts.

 Here are the steps for the same:

1. Click the search icon on the taskbar to access the search menu.
2. Type **edit group policy** or **gpedit** in the search box and select the first result that appears.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing desktop icons** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** and then **OK**.  
![Using the Local Group Policy to Prevent Others From Changing Desktop Icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-to-Prevent-Others-From-Changing-Desktop-Icons.jpg)

 And that's about it. Once you make the above changes, the other users won't be able to create, modify, or delete your desktop icons.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 6\. Review Scheduled Tasks

 It is possible that a scheduled task is causing Windows to create a desktop shortcut for Edge repeatedly. To check for this possibility, you need to review tasks in the Task Scheduler app.

 Use these steps to check automated tasks in Task Scheduler:

1. Right-click on the **Start icon** and select **Run** from the menu that appears.
2. Type **taskschd.msc** in the box and press **Enter** to open the Task Scheduler app.
3. Select **Task Scheduler Library** in the left pane to view a list of tasks in the middle pane.
4. Locate and select any Edge-related tasks.
5. Click the **Disable** option in the right pane.  
![An Automated task selected in the Task Scheduler window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Task-Scheduler-Window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-unleash-your-inner-videographer-with-these-4-methods-on-xbox/"><u>[New] 2024 Approved  Unleash Your Inner Videographer with These 4 Methods on Xbox</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-from-simulation-to-reality-jaunt-vrs-journey/"><u>[New] From Simulation to Reality  Jaunt VR's Journey</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-simplifying-screen-views-during-google-meet-chats/"><u>[New] In 2024, Simplifying Screen Views During Google Meet Chats</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-ultimate-list-igtv-masterminds-and-maestros/"><u>[New] The Ultimate List  IGTV Masterminds & Maestros</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-clipmaster-software/"><u>[Updated] ClipMaster Software</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-detailed-analysis-of-youtubes-versus-dailymentions-for-2024/"><u>[Updated] Detailed Analysis of YouTubes Versus DailyMentions for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-notable-creators-superior-insta-highlight-craftsmen-for-2024/"><u>[Updated] Notable Creators  Superior Insta Highlight Craftsmen for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-secrets-of-adobe-cloud-and-alternative-storage-solutions/"><u>[Updated] Unveiling the Secrets of Adobe Cloud & Alternative Storage Solutions</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>10 Best Fake GPS Location Spoofers for Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-top-5-macos-safari-video-conversion-apps/"><u>2024 Approved  Top 5 macOS Safari Video Conversion Apps</u></a></li>
<li><a href="https://tech-haven.techidaily.com/8-innovative-neural-network-solutions-for-the-modern-user/"><u>8 Innovative Neural Network Solutions for the Modern User</u></a></li>
<li><a href="https://buynow-info.techidaily.com/achieving-health-goals-with-the-fitbit-versa-lite-an-insightful-product-review/"><u>Achieving Health Goals with the Fitbit Versa Lite: An Insightful Product Review</u></a></li>
<li><a href="https://extra-hints.techidaily.com/biz-vr-innovations-new-frontiers-in-virtual-workspaces-for-2024/"><u>Biz-VR Innovations  New Frontiers in Virtual Workspaces for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-hyper-v-installation-in-windows-11-home-systems/"><u>Conquering Hyper-V Installation in Windows 11 Home Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-lasting-trash-area-on-your-windows-desktop-space/"><u>Creating a Lasting Trash Area on Your Windows Desktop Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-to-the-core-how-to-fix-win-error-31-in-windows/"><u>Cutting to the Core: How to Fix WIN Error 31 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-essential-services-for-seamless-windows-11-launches/"><u>Enabling Essential Services for Seamless Windows 11 Launches</u></a></li>
<li><a href="https://fox-helps.techidaily.com/enhancing-engagement-onestream-streaming-best-practices/"><u>Enhancing Engagement  OneStream Streaming Best Practices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-disks-understanding-the-c-and-d-narrative/"><u>Examining Disks: Understanding the C & D Narrative</u></a></li>
<li><a href="https://media-tips.techidaily.com/expert-advice-mastering-mov-files-conversion-playback-and-optimal-use/"><u>Expert Advice: Mastering MOV Files - Conversion, Playback & Optimal Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-fortify-your-windows-configuration-interface/"><u>Fix and Fortify Your Windows Configuration Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-problem-when-multiple-apps-claim-same-audio/"><u>Fixing the Problem When Multiple Apps Claim Same Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-dated-devices-to-future-proof-systems-with-app-transfer/"><u>From Dated Devices to Future-Proof Systems with App Transfer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-admin-policy-block-in-windows-software-setup/"><u>How to Bypass 'Admin Policy' Block in Windows Software Setup</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-realme-12-5g-is-unlocked-by-drfone-android/"><u>How To Check if Your Realme 12 5G Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-your-steam-library-auto-synchronize-properly/"><u>How to Make Your Steam Library Auto-Synchronize Properly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-compatibility-checker-in-windows-11/"><u>How to Use the Compatibility Checker in Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Honor Magic Vs 2? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-why-does-instagram-keep-flipping-my-video/"><u>In 2024, Why Does Instagram Keep Flipping My Video?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovation-meets-efficiency-top-6-to-do-list-apps-for-win-11/"><u>Innovation Meets Efficiency - Top 6 To-Do List Apps for Win 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/introducing-windows-xps-media-production-hub-for-2024/"><u>Introducing Windows XP's Media Production Hub for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/large-hard-drives-little-computational-thrill/"><u>Large Hard Drives, Little Computational Thrill</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-windows-calculator-app-less-bright/"><u>Make Windows Calculator App Less Bright</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-interface-woes-top-5-windows-correction-tips/"><u>Mastering Interface Woes: Top 5 Windows Correction Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-unforeseen-system-shuts-in-win11/"><u>Preventing Unforeseen System Shuts in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-a-missing-msvcr110dll-in-windows/"><u>Remedying a Missing msvcr110.dll in Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/resource-scarcity-usable-deficit/"><u>Resource Scarcity: Usable Deficit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-balanced-sound-from-both-sides-of-win-headphones/"><u>Restoring Balanced Sound From Both Sides of WIN Headphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrect-dead-headset-on-your-machine-instantly/"><u>Resurrect Dead Headset on Your Machine, Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-microsoft-words-speech-functionality-on-pc/"><u>Reviving Microsoft Word's Speech Functionality on PC</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-off-view-apps-in-win-1011-the-ultimate-guide-to-6-recovery-methods/"><u>Reviving Off-View Apps in Win 10/11: The Ultimate Guide to 6 Recovery Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-qbittorrent-status-in-windows-woes/"><u>Reviving Your qBittorrent Status in Windows Woes</u></a></li>
<li><a href="https://extra-support.techidaily.com/showcasing-excellence-top-20-anime-openings-for-2024/"><u>Showcasing Excellence  Top 20 Anime Openings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyline-beyond-100mbps-cap-elevating-windows-networks/"><u>Skyline Beyond 100Mbps Cap: Elevating Windows Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stopping-accidental-shortcuts-at-work/"><u>Solutions for Stopping Accidental Shortcuts at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-other-application-happens-with-sound-errors/"><u>Steps to Solve Other Application Happens with Sound Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-trigger-success-in-windows-service-starts/"><u>Strategies to Trigger Success in Windows Service Starts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-system-awakening-alter-boot-timer-for-efficiency/"><u>Swift System Awakening: Alter Boot Timer for Efficiency</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-10-premier-online-church-service-providers/"><u>The 10 Premier Online Church Service Providers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-synergy-of-ai-and-windows-software-development/"><u>The Synergy of AI and Windows Software Development</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-rectify-steam-server-connection-failures-in-windows/"><u>Tips to Rectify Steam Server Connection Failures in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-realme-gt-3-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Realme GT 3 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-notch-portable-power-solution-diving-into-the-omnicharge-omni-review-featuring-20kwh-and-wireless-charging/"><u>Top-Notch Portable Power Solution: Diving Into the Omnicharge Omni ˈReview Featuring 20kWh & Wireless Charging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-pcs-image-processing-potential-with-4-best-viewers/"><u>Unlock Your PC's Image Processing Potential with 4 Best Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-updates-made-simple-resolving-error-0xc1900101/"><u>Win11 Updates Made Simple: Resolving Error 0xC1900101</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-check-up-activation-verification-steps/"><u>Windows 11 Check-Up: Activation Verification Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-users-prefer-cleaner-start-menus/"><u>Windows 11 Users Prefer Cleaner Start Menus</u></a></li>
</ul></div>
