---
title: Getting Plain in Windows 11 Shapes
date: 2024-08-08T11:01:35.145Z
updated: 2024-08-09T11:01:35.145Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Getting Plain in Windows 11 Shapes
excerpt: This Article Describes Getting Plain in Windows 11 Shapes
keywords: Win11_PlainInterface,SimplifiedWindowsUI,Windows11BasicLayout,UnclutteredWindows11,PlainWindowsInterface,SimpleWin11Style,CleanWindowsDesign11
thumbnail: https://thmb.techidaily.com/91b7cfb4d96e2456602f29985eb790b38dbd8c0fc22d4f4a877755c3058adea9.jpg
---

## Getting Plain in Windows 11 Shapes

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-cross-platform-comedy-best-meme-contenders/"><u>[New] 2024 Approved  Cross-Platform Comedy  Best Meme Contenders</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-harvesting-happiness-the-ultimate-list-of-7-14-mods-for-2024/"><u>[New] Harvesting Happiness  The Ultimate List of #7-14 Mods for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-skyrocketing-your-earning-potential-a-vimeo-monetization-guide-for-2024/"><u>[New] Skyrocketing Your Earning Potential  A Vimeo Monetization Guide for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-discover-the-top-30-freefire-hashtags-for-amplifying-video-growth/"><u>[Updated] 2024 Approved  Discover the Top 30 FreeFire Hashtags for Amplifying Video Growth</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-the-ultimate-list-for-first-time-film-makers-35mm-to-pands/"><u>[Updated] 2024 Approved  The Ultimate List for First-Time Film Makers (35Mm to P&S)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-a-comprehensive-guide-to-crop-your-video-for-instagram-for-2024/"><u>[Updated] A Comprehensive Guide to Crop Your Video for Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-comprehensive-youtube-video-editing-with-finalcut-pro-skills-for-2024/"><u>[Updated] Comprehensive YouTube Video Editing with FinalCut Pro Skills for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-affordable-shutterbug-gear-for-dynamic-action-scenes/"><u>[Updated] In 2024, Affordable Shutterbug Gear for Dynamic Action Scenes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-exploring-the-difference-between-ig-reels-and-stories/"><u>[Updated] In 2024, Exploring the Difference Between IG Reels & Stories</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-mastering-media-migration-tiktok-directly-to-fb/"><u>[Updated] In 2024, Mastering Media Migration  TikTok Directly to FB</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-twitch-broadcast-excellence-the-ultimate-5-guide/"><u>[Updated] In 2024, Twitch Broadcast Excellence  The Ultimate 5 Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-the-ultimate-list-of-preferred-mac-snipping-apps-for-2024/"><u>[Updated] The Ultimate List of Preferred Mac Snipping Apps for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-motorola-moto-g13-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Motorola Moto G13 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-ram-cache-and-how-to-purge-it/"><u>Decoding Windows RAM Cache and How to Purge It</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effective-fixes-to-overcome-the-there-was-a-problem-reboot-glitch-on-your-computer/"><u>Effective Fixes to Overcome the 'There Was a Problem' Reboot Glitch on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fix-windows-11-graphics-drivers-reset/"><u>Efficient Fix: Windows 11 Graphics Drivers Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-window-restoration-after-dark-screens/"><u>Effortless Window Restoration After Dark Screens</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enablingdisabling-network-discovery-on-your-pc-a-guide-for-windows-11-users/"><u>Enabling/Disabling Network Discovery on Your PC: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enlightenment-streams-foremost-ed-resources-online-for-2024/"><u>Enlightenment Streams  Foremost Ed Resources Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-fixing-fall-guys-link-failures-windows-wise/"><u>Essential Steps for Fixing Fall Guys Link Failures Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-utilizing-diskusage-on-windows-systems/"><u>Expert Guide to Utilizing DiskUsage on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-experiences-retrieval-failure-on-windows-11-systems/"><u>Fixing GeForce Experience's Retrieval Failure on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-power-of-google-maps-in-your-windows-system/"><u>Harnessing the Power of Google Maps in Your Windows System</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-elevate-your-iphone-photography-dive-into-hdr/"><u>How to Elevate Your iPhone Photography  Dive Into HDR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-outlooks-something-went-wrong-error-on-windows/"><u>How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-the-soft-bricked-vivo-t2-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Vivo T2 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-when-apple-account-locked-from-apple-iphone-11-pro-max-by-drfone-ios/"><u>How to Fix when Apple Account Locked From Apple iPhone 11 Pro Max?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-programs-with-preset-window-sizes-in-windows-11/"><u>How to Open Programs With Preset Window Sizes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reboot-dns-cache-in-windows-11/"><u>How to Reboot DNS Cache in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-gaming-service-failures-on-pcs-and-laptops/"><u>How To Resolve Gaming Service Failures on PCs and Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-save-windows-spotlight-pictures-to-use-as-wallpapers-when-you-want/"><u>How to Save Windows Spotlight Pictures to Use as Wallpapers When You Want</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-a-step-by-step-approach-to-yt-channel-descriptors/"><u>In 2024, A Step-by-Step Approach to YT Channel Descriptors</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/innovative-approaches-to-social-media-video-making/"><u>Innovative Approaches to Social Media Video Making</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-efficiency-into-daily-use-with-win11-icon-additions/"><u>Integrating Efficiency Into Daily Use with Win11 Icon Additions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-video-cutting-solutions-on-your-windows-11-system/"><u>Masterful Video Cutting Solutions on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-device-coexistence-utilize-dex-for-galaxy-on-pc/"><u>Mastery in Device Coexistence: Utilize DeX for Galaxy on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-output-with-windows-streamlined-launcher/"><u>Maximize Output with Windows' Streamlined Launcher</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-g24-power-can-t-play-mp4-video-files-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Motorola G24 Power can't play MP4 video files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-the-8-most-common-mistakes-for-beginners-to-skip/"><u>Navigating Windows 11: The 8 Most Common Mistakes for Beginners to Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-analysis-creating-and-interpreting-data/"><u>Navigating Windows Analysis: Creating & Interpreting Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-win1011-screen-glitches-with-ease/"><u>Quelling WIN10/11 Screen Glitches with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-troubled-windows-11-calendars/"><u>Resetting Techniques for Troubled Windows 11 Calendars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-0xc0000142-in-win7win8/"><u>Resolving Error 0XC0000142 in Win7/Win8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-downloading-and-installing-windows-11-arm-from-iso/"><u>Step by Step: Downloading and Installing Windows 11 ARM From ISO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-overcoming-windows-onedrives-cant-add-now-error/"><u>Step-by-Step Guide: Overcoming Windows OneDrive's 'Can’t Add Now' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-navigation-tips-on-using-narrator-commands/"><u>Streamlining Windows Navigation: Tips on Using Narrator Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-implement-without-obstacles-win11-version-22h2-update/"><u>Tactics to Implement Without Obstacles: Win11 Version 22H2 Update</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-unexpected-suspension-of-chatgpt-in-italy-reasons-and-implications/"><u>The Unexpected Suspension of ChatGPT in Italy - Reasons and Implications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-troubleshooting-tips-to-ease-team-communication-errors-on-w11/"><u>Transformative Troubleshooting Tips to Ease Team Communication Errors on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-operational-amd-radeon-ssp-on-windows/"><u>Troubleshooting Non-Operational AMD Radeon SSP on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-roblox-availability-tackling-windows-settings-issue/"><u>Unblocking Roblox Availability: Tackling Windows Settings Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-maximum-speed-for-your-digital-purchases-at-microsoft/"><u>Unlock Maximum Speed for Your Digital Purchases at Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-laptop-or-desktop-windows-era/"><u>Unveiling Laptop or Desktop Windows Era</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-honor-x50-gt-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Honor X50 GT Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-clean-up-clearing-the-old-protection-data/"><u>Windows Security Clean-Up: Clearing the Old Protection Data</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>