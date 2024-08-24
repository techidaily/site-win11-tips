---
title: "Master Windows Update: Self-Replacing AMD Graphics Drivers"
date: 2024-08-23T07:02:32.140Z
updated: 2024-08-24T07:02:32.140Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Master Windows Update: Self-Replacing AMD Graphics Drivers"
excerpt: "This Article Describes Master Windows Update: Self-Replacing AMD Graphics Drivers"
keywords: AMD Driver Updates,Self-Updating Graphics,Windows Direct GPU Fixes,Patchless GPU Software,Automatic Graphics Update,AMD Drivers Mastery,Live Driver System Rehab
thumbnail: https://thmb.techidaily.com/7deb0baa73b5dfc75fe84cd47c60ae37428dbd6443868bb9392e788fdb87eec8.jpg
---

## Master Windows Update: Self-Replacing AMD Graphics Drivers

 AMD Software Adrenaline Edition on Windows lets you manage your AMD graphics card, game stats, perform driver updates, and more. Sometimes, after an update, it may fail to launch with the error Windows update has replaced your AMD graphics driver.

 The full error reads Windows update may have automatically replaced your AMD graphics driver. This error is due to a conflict between the AMD Software Adrenaline Edition driver and the UWP AMD graphics driver installed by Windows.

 To fix the problem, you’ll need to stop Windows from installing AMD Radeon drivers automatically and perform a manual reinstall. Here’s how to do it.

## Why Does Windows Automatically Replace Your AMD Graphics Drivers?

 By default, the Windows operating system installs the[Microsoft Basic Display Adapter](https://www.makeuseof.com/microsoft-basic-display-adapter-guide/) during the initial setup. It provides display graphics capabilities so that you can set up your new computer and install the necessary drivers.

 This basic display driver lets you configure your discrete graphics with the latest drivers using AMD Software. It also acts as a backup when your discrete GPU driver faults causing[black screen issues on Windows](https://www.makeuseof.com/fix-black-screen-on-windows-10-11/) .

 However, this error occurs when Windows updates install the UWP (Universal Windows Platform) driver for your AMD Radeon GPU. Since two versions of the same driver are installed, when you try to open the AMD Software Adrenaline Edition app it will trigger an error.

 AMD has addressed this issue and provided a quick fix. To fix the error, you'll need to stop Windows from automatically installing the AMD graphics drivers. Then, reinstall the AMD graphics driver using AMD software.

## 1\. Roll Back the AMD Graphics Driver

![amd radeon display adapter driver roll back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-display-adapter-driver-roll-back.jpg)

 An easy way to fix Windows replacing your AMD graphics error is to roll back the AMD graphics driver. A driver rollback removes the current driver and reinstalls the previous version saved on your computer. Fortunately, you can[roll back device drivers using the Windows Device Manager](http://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 In Device Manager, look for and expand the**Display Adapters** section. Here, select the**AMD Radeon (TM) graphics** device and perform a driver rollback. Once done, restart your computer and check for any improvements. If the**Roll Back Driver** option is greyed out, you can't perform a rollback for the selected device.

 Once the error is resolved, you'll need to stop Windows from automatically downloading AMD drivers. If not, you’ll likely encounter the same error after each Windows update.

 You can[stop automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) using device installation settings,**Group Policy Editor** , and the**Windows Registry** . With the device installation settings for automatic driver download set to off, Windows won't download and install AMD graphics drivers automatically.

## 2\. Repair and Reinstall the AMD Software Driver

![amd radeon software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-software-installer.jpg)

 You can reinstall the AMD Software driver using the existing driver. This may fix temporary issues with the driver causing the conflict. Follow these steps to repair and reinstall the AMD graphics driver:

1. Press**Win + E** to open File Explorer and navigate to the following location:  
`C:\AMD\RadeonInstaller\RadeonInstaller\Radeon_Folder_with_verison_name`
2. Next, double-click to run the**Setup.exe** file.  
![run amd setup exe repair graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-amd-setup-exe-repair-graphics-driver.jpg)
3. In the**AMD Radeon Software Installer** dialog, select the driver version to install.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
4. Click**Install** and wait for the driver to install.

 If you encounter an AMD error 195, temporarily[disable Windows Defender Firewall](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and**Real-Time Threat Protection** and try again.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 3\. Reinstall the AMDSoftware Graphics Driver

![amd software adrenaline edition uninstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-software-adrenaline-edition-uninstall.jpg)

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
 If the issue persists, try to remove and reinstall the AMD Software graphics driver. Once uninstalled, you can download the latest driver using the AMD Software.

To uninstall the AMD graphics driver:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click**Installed Apps** .
3. Next, search for**AMD Software** .  
![unisntall amd graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unisntall-adm-graphics-driver.jpg)
4. Click**Uninstall** and then**Uninstall** again to confirm the action.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
5. Select**AMD Radeon Graphics** and click**Uninstall** .

 The AMD Software will start removing the driver from your computer. This process may take some time, and your monitor or display may flicker during the process. If it does, don't fret; it's just Windows getting used to the changes to your display drivers.

 Once done, click on**Finish** and restart your PC.

 When you uninstall a display driver, your secondary monitor can stop working. This will happen if your monitor's HDMI cable is directly connected to the port on your dedicated graphics unit. Your secondary display should work again as you reinstall the graphics driver.

 After the restart, you can[update your AMD Radeon graphics driver](https://www.makeuseof.com/update-amd-radeon-graphics-driver-windows-11/) using AMD Software. Install the driver and restart your PC to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Use a System Restore Point

 A restore point helps you recover your computer when a bad Windows update or driver installation causes the system to malfunction. You can use a restore point to undo the changes without affecting your data and files.

 Unfortunately, using a System Restore point requires you made one in the past. If you haven't made any, now's a good time to get into the habit of making them. Check out[how to make a System Restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) for more information.

To undo the recent changes using a restore point:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** .  
![select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/select-restore-point.jpg)
3. In the**System Restore** dialog, select the**Recommended** **restore** option. If not, select the**Choose a different restore point** option**.**
4. Select a**restore point** and click**Next** .  
![select restore point windows 11 finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-restore-point-windows-11-finish.jpg)
5. Read the description and click**Finish** .
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. System Restore will restart and restore your PC to the state it was in before the date of the selected restore point.

## Fixing the Windows Update May Have Automatically Replaced Your AMD Driver

 This error occurs if multiple versions of the same AMD Radeon graphics driver are installed on your computer. To fix the issue, perform a driver rollback for your AMD Radeon graphics in Device Manager. Once done, change the device installation setting to prevent Windows from automatically installing the OEM driver for your GPU.


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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-many-viewers-equates-to-profit-decoding-youtubes-earnings-formula/"><u>[New] 2024 Approved  How Many Viewers Equates to Profit? Decoding YouTube's Earnings Formula</u></a></li>
<li><a href="https://article-files.techidaily.com/new-2024-approved-superior-pfv-optimization-in-tardy-action/"><u>[New] 2024 Approved  Superior PFV Optimization in Tardy Action</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-captivating-costless-visual-collaboration-games-for-2024/"><u>[New] Captivating Costless Visual Collaboration Games for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-cutting-edge-6-urban-designs-in-mc-for-2024/"><u>[New] Cutting-Edge 6 Urban Designs in MC for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-fast-and-easy-gif-transformation-ultimate-list-of-no-download-services/"><u>[New] Fast and Easy GIF Transformation  Ultimate List of No-Download Services</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-charting-the-course-of-knowledge-best-history-yt-channels-for-students/"><u>[New] In 2024, Charting the Course of Knowledge  Best History YT Channels for Students</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-enhance-pc-listening-experience-install-x-recorder/"><u>[New] In 2024, Enhance PC Listening Experience - Install X-Recorder</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-quick-tip-to-uncover-your-recently-watched-movies-on-fb/"><u>[New] In 2024, Quick Tip to Uncover Your Recently Watched Movies on FB</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-mystery-of-off-facebook-activity-what-to-know-and-do/"><u>[New] The Mystery of Off-Facebook Activity  What to Know & Do</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-beginners-journey-into-advanced-video-coding/"><u>[Updated] 2024 Approved  Beginner's Journey Into Advanced Video Coding</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-validate-your-youtube-profile-a-simple-guide/"><u>[Updated] 2024 Approved  How to Validate Your YouTube Profile? A Simple Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-discovering-chromebooks-best-digital-art-stations-for-2024/"><u>[Updated] Discovering Chromebook's Best Digital Art Stations for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/1716118408180-updated-facebook-videos-vertical-or-horizontal-in-2024/"><u>[Updated] Facebook Videos  Vertical or Horizontal, In 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-effortlessly-access-fb-beats/"><u>[Updated] In 2024, Effortlessly Access FB Beats</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pivot-producer-system/"><u>[Updated] Pivot Producer System</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-reviewing-the-impression-of-high-dynamic-range-on-aurora-tv/"><u>[Updated] Reviewing the Impression of High Dynamic Range on Aurora TV</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitreact-wisdom-a-complete-reference-book-for-2024/"><u>[Updated] TwitReact Wisdom  A Complete Reference Book for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-outwit-facebook-vids-ad-blocking-basics/"><u>2024 Approved  Outwit Facebook Vids  Ad-Blocking Basics</u></a></li>
<li><a href="https://technical-tips.techidaily.com/boost-your-efficiency-with-these-5-amazing-non-rooted-android-clicker-apps/"><u>Boost Your Efficiency with These 5 Amazing Non-Rooted Android Clicker Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clean-slate-clearing-windows-11-activity-record/"><u>Clean Slate: Clearing Windows 11 Activity Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-down-on-time-spent-error-0x800736cc-in-windows-update/"><u>Cutting Down on Time Spent: Error 0X800736CC in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-efficiency-forward-hotkeys-for-fast-clicking/"><u>Drive Efficiency Forward: Hotkeys for Fast Clicking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-command-line-experience-make-terminal-first/"><u>Enhance Command Line Experience: Make Terminal First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-car-tools-for-efficient-windows-use/"><u>Essential Car Tools for Efficient Windows Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fix-guide-for-win1011s-corrupted-bin-errors/"><u>Essential Fix Guide for WIN10/11's Corrupted Bin Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exe-vs-msi-understanding-file-distinctions/"><u>EXE vs MSI: Understanding File Distinctions</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-predictions-annual-increase-projects-avg-laptop-memory-at-118-gb-up-by-12/"><u>Expert Predictions: Annual Increase Projects Avg. Laptop Memory at 11.8 GB - Up by 12%%</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-hide-taskbars-search-in-windows-11/"><u>Expert Tips: Hide Taskbar's Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/full-hd-classics-unlocked-the-perfect-scummvm-techniques-for-windows-users/"><u>Full HD Classics Unlocked: The Perfect ScummVM Techniques for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-when-outlook-fails-to-launch-normally/"><u>Guiding Users When Outlook Fails to Launch Normally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-fixing-a-frozen-control-key-in-win11/"><u>Guiding You Through Fixing a Frozen Control Key in Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-and-replace-outdated-windows-drivers/"><u>How to Find and Replace Outdated Windows Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-outlook-notifications-not-working-on-windows/"><u>How to Fix Outlook Notifications Not Working on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-intensify-your-gaming-view-on-roblox-platforms/"><u>How to Intensify Your Gaming View on Roblox Platforms</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-tecno-pop-7-pro-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Tecno Pop 7 Pro in Minutes | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Realme 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-from-transaction-to-treasure-unlocking-your-facebook-video-archive/"><u>In 2024, From Transaction to Treasure  Unlocking Your Facebook Video Archive</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-successfully-bypass-icloud-activation-lock-from-iphone-8-by-drfone-ios/"><u>In 2024, How to Successfully Bypass iCloud Activation Lock from iPhone 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/journey-into-system32-folder-of-win11/"><u>Journey Into System32 Folder of Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-printer-troubles-reactivating-missing-wwinplusp-on-windows/"><u>Mastering Printer Troubles: Reactivating Missing WWin+P on Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-video-streams-fix-youtube-lag-in-chrome/"><u>Mastering Video Streams: Fix YouTube Lag in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-win-11-edge-security-using-ms-defender-application-guard/"><u>Optimize Win 11 Edge Security Using MS Defender Application Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-icloud-download-challenges-on-pc/"><u>Overcoming iCloud Download Challenges on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/override-standard-user-restrictions-now/"><u>Override Standard User Restrictions Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/override-unmet-system-conditions-indicator-in-win11/"><u>Override Unmet System Conditions Indicator in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-and-style-synergy-the-leading-windows-laptops-of-24/"><u>Power & Style Synergy: The Leading Windows Laptops of '24</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-connections-with-mb-services-in-windows-11/"><u>Re-Establishing Connections with MB Services in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-missing-window-panes-in-windows-11-6-tactics/"><u>Reinstating Missing Window Panes in Windows 11 (6 Tactics)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-stuck-windows-update-problems-now/"><u>Resolving Stuck Windows Update Problems Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-unresolvable-value-errors-in-winos/"><u>Solutions for Unresolvable Value Errors in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-dependencies-using-wpm-effectively/"><u>Streamlining Dependencies: Using WPM Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-qt-initialization-unsuccessful-in-dev-environment/"><u>Tackling Qt Initialization Unsuccessful in Dev Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-10-store-errors-a-quick-guide/"><u>Tackling Windows 10 Store Errors: A Quick Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722028317898-the-ultimate-guide-to-navigating-openais-exclusive-custom-gpt-offerings-today/"><u>The Ultimate Guide to Navigating OpenAI’s Exclusive Custom GPT Offerings Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-supercharging-your-windows/"><u>The Ultimate Guide to Supercharging Your Windows</u></a></li>
<li><a href="https://fox-links.techidaily.com/top-9-platforms-for-unparalleled-gamers-joy/"><u>Top 9 Platforms for Unparalleled Gamers' Joy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-a-non-operational-printer-on-windows-11/"><u>Troubleshoot a Non-Operational Printer on Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-effortlessly-astro-a20-audio-problems-and-fixes/"><u>Troubleshoot Effortlessly: Astro A20 Audio Problems and Fixes</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-and-correcting-rusts-display-errors/"><u>Troubleshooting and Correcting Rust's Display Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-optimal-performance-by-taming-high-cpu-demands/"><u>Unleashing Optimal Performance by Taming High CPU Demands</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unveiling-the-secrets-of-slow-motion-video-production-for-instagram-impact-for-2024/"><u>Unveiling the Secrets of Slow Motion Video Production for Instagram Impact for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-github-desktop-efficiently-on-windows-11-pro/"><u>Utilizing GitHub Desktop Efficiently on Windows 11 Pro</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-to-find-for-2024/"><u>Where to Find for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-team-video-sharing-fixes/"><u>Windows Team Video Sharing Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winerror-0xc0000005-fix-a-step-by-step-guide/"><u>WinError 0Xc0000005 Fix: A Step-by-Step Guide</u></a></li>
</ul></div>
