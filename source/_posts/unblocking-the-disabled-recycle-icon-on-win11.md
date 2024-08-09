---
title: Unblocking the Disabled Recycle Icon on Win11
date: 2024-08-08T11:03:00.473Z
updated: 2024-08-09T11:03:00.473Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unblocking the Disabled Recycle Icon on Win11
excerpt: This Article Describes Unblocking the Disabled Recycle Icon on Win11
keywords: Fix Recycle Bin Error WIN11,Unblock Icon on Windows 11,Clear Recycle Icon Issue WIN11,Resolve Recycle Bin Disabled WIN11,Enable Recycle Icon WIN11,Restore Recycle Icons in Win11,Fix Disabled Recycle Bin on Windows 11
thumbnail: https://thmb.techidaily.com/ddfdfc8e69381106d1b66c2809b663a8f7e41d96d0a4215acf2250fc3083c5a7.jpg
---

## Unblocking the Disabled Recycle Icon on Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-broadcast-perfection-recommended-tech-and-apps-for-youtubers/"><u>[New] 2024 Approved  Broadcast Perfection  Recommended Tech and Apps for YouTubers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-captivating-your-network-streamlining-content-via-wirecast-to-facebook/"><u>[New] 2024 Approved  Captivating Your Network  Streamlining Content via Wirecast to Facebook</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-masterclass-in-effortless-video-acquisition/"><u>[New] 2024 Approved  Masterclass in Effortless Video Acquisition</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-capturing-action-choosing-from-5-leading-game-stream-webcams/"><u>[New] In 2024, Capturing Action  Choosing From 5 Leading Game Stream Webcams</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagrams-visual-rhythm-mastering-the-slow-motion-balance-for-2024/"><u>[New] Instagram's Visual Rhythm  Mastering the Slow-Motion Balance for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-mastering-real-time-video-conversations-with-whatsapp-web-on-pcs/"><u>[Updated] 2024 Approved  Mastering Real-Time Video Conversations with WhatsApp Web on PCs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ending-grey-shades-in-live-stream-translations-for-2024/"><u>[Updated] Ending Grey Shades in Live Stream Translations for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-cutting-edge-taggification-top-7-affordable-online-extractors-for-youtube/"><u>[Updated] In 2024, Cutting-Edge Taggification  Top 7 Affordable Online Extractors for YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-establishing-baseline-metrics-for-igtv-effectiveness/"><u>[Updated] In 2024, Establishing Baseline Metrics for IGTV Effectiveness</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-craft-digital-laughter-kapwing-meme-maker/"><u>2024 Approved  Craft Digital Laughter – Kapwing Meme Maker</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-upcoming-vr-masterpieces-top-5-new-titles-for-playstation-vr-enthusiasts/"><u>2024 Approved  Upcoming VR Masterpieces  Top 5 New Titles for PlayStation VR Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-steps-to-wipe-your-drives-partitions-in-windows/"><u>4 Easy Steps to Wipe Your Drive's Partitions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-be-registered-error-a-windows-photos-guide/"><u>Addressing 'Could Not Be Registered' Error: A Windows Photos Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-dxgierror-with-device-reattachment/"><u>Combat DXGI_ERROR with Device Reattachment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-and-configuring-your-win11-screensavers/"><u>Crafting and Configuring Your Win11 Screensavers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/directordocks-overview-detailed-reviews/"><u>DirectorDocks Overview – Detailed Reviews</u></a></li>
<li><a href="https://network-issues.techidaily.com/discover-unseen-display-options-in-windows-11/"><u>Discover Unseen Display Options in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-regain-onedrive-entry-points-in-windows/"><u>Effortlessly Regain OneDrive Entry Points in Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/eliminating-problems-samsung-ssd-and-windows-synergy/"><u>Eliminating Problems: Samsung SSD and Windows Synergy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-self-closure-in-windows-os/"><u>Eliminating Self-Closure in Windows OS</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/enhance-your-gameplay-latest-gtx-1660-ti-graphics-driver-update/"><u>Enhance Your Gameplay: Latest GTX 1660 Ti Graphics Driver Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-in-windows-11-notepad/"><u>Enhancing User Experience in Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-the-prospects-why-choose-win11-over-macos/"><u>Examining the Prospects: Why Choose Win11 Over MacOS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-12-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on 12</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-oppo-reno-10-5g-is-unlocked-by-drfone-android/"><u>How To Check if Your Oppo Reno 10 5G Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-background-apps-in-windows-11/"><u>How to Disable Background Apps in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-6-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 6 without iTunes? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-restore-a-bricked-poco-m6-pro-4g-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Poco M6 Pro 4G Back to Operation | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-device-functionality-in-win11-sleep-mode/"><u>How to Revive Device Functionality in Win11 Sleep Mode?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/igfx-stopped-successfully-rebooted/"><u>IGFX Stopped, Successfully Rebooted</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-localizing-your-content-adding-subtitles-to-igtv/"><u>In 2024, Localizing Your Content  Adding Subtitles to IGTV</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-v29-pro-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Vivo V29 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-user-profile-control-with-cmd/"><u>In-Depth Analysis of User Profile Control with CMD</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/incorporating-youtubes-creative-commons-in-video-making/"><u>Incorporating YouTube's Creative Commons in Video Making</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-power-off-windows-11-when-not-in-use/"><u>Instantly Power Off Windows 11 When Not in Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-data-organization-optimize-your-win11-hdd/"><u>Mastering Data Organization: Optimize Your Win11 HDD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-task-runner-error-code-0x8007000f-in-winos/"><u>Mastery over Task Runner Error Code 0X8007000f in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-unsetting-personalized-search-on-windows-11-os/"><u>Methods for Unsetting Personalized Search on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-boot-up-a-guide-to-startup-service-management/"><u>Navigate Through Windows Boot-Up: A Guide to Startup Service Management</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/next-level-video-top-webcam-filters-for-flawless-broadcasts/"><u>Next Level Video  Top Webcam Filters for Flawless Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-zip-file-errors-a-win-11-remedy-plan/"><u>Overcoming Zip File Errors: A Win 11 Remedy Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-failed-retrieval-error-with-geforce-x/"><u>Quick Fixes for Failed Retrieval Error with GeForce X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11-troubleshooters-for-optimal-performance/"><u>Realigning Windows 11 Troubleshooters for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-overhead-memory-usage-by-malware-detectors/"><u>Reducing Overhead Memory Usage by Malware Detectors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-sudden-device-disconnection-dxgi/"><u>Remedy for Sudden Device Disconnection (DXGI)</u></a></li>
<li><a href="https://driver-download.techidaily.com/resolving-bluetray-errors-in-windows-10-a-comprehensive-guide/"><u>Resolving BlueTray Errors in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-steam-gaming-glory-a-how-to-manual/"><u>Reviving Lost Steam Gaming Glory: A How-To Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-address-failed-lunar-client-startup-errors/"><u>Solutions to Address Failed Lunar Client Startup Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-windows-issue-file-explorer-failsafe-mode/"><u>Solve Windows Issue: File Explorer Failsafe Mode</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-how-to-install-missing-drivers-for-your-device-on-windows-10-8-and-7/"><u>Solved: How to Install Missing Driver(s) for Your Device on Windows 10, 8 & 7</u></a></li>
<li><a href="https://buynow-info.techidaily.com/stay-charged-on-the-go-the-premier-selection-of-portable-laptop-batteries/"><u>Stay Charged on the Go: The Premier Selection of Portable Laptop Batteries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-curb-energy-drain-while-playing-games-on-pc/"><u>Strategies to Curb Energy Drain While Playing Games on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-for-windows-11s-0x8004def5-glitches/"><u>Swift Solutions for Windows 11'S 0X8004DEF5 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-notes-no-downloads-windows-11-secrets/"><u>Take Notes, No Downloads: Windows 11 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-keep-microsoft-teams-from-crashing-win11-win10/"><u>Tips to Keep Microsoft Teams From Crashing Win11, Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-win-11-with-confident-system-setup/"><u>Transitioning to Win 11 with Confident System Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unidentified-devices-on-windows-1011/"><u>Troubleshooting Unidentified Devices on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-using-dark-theme-in-notepad/"><u>Understanding and Using Dark Theme in Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-winexe-creation-from-batch-scripts/"><u>Unveiling WinEXE Creation From Batch Scripts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>