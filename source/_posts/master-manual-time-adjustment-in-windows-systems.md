---
title: Master Manual Time Adjustment in Windows Systems
date: 2024-08-16T02:37:13.917Z
updated: 2024-08-17T02:37:13.917Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Master Manual Time Adjustment in Windows Systems
excerpt: This Article Describes Master Manual Time Adjustment in Windows Systems
keywords: Windows Time Settings,Time Zone Management,System Time Update,PC Date Change Guide,Automatic Time Correction,Time Sync in Windows,Daylight Saving Adjustments
thumbnail: https://thmb.techidaily.com/eb6c43743edfe7719c43f746c3a62c94afe56182a98c24ab59e2903c5366daaa.jpg
---

## Master Manual Time Adjustment in Windows Systems

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

## 1\. Restart Your PC

 The first step when troubleshooting any Windows-related issue is to restart the computer. It seems obvious, but it often solves the problem. Rebooting flushes out cached data that could cause time zone problems. It also resets various temporary services that may prevent Windows from automatically setting the time zone.

 To restart your computer, save all your work and close any running applications. After that, open the Start menu and click **Restart**. Once your computer restarts, check if that fixes the issue.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Turn on Location Services in the Settings

 If restarting your computer didn't fix the issue, check if location services are enabled. Location services allow Windows to automatically detect the time zone and set it accordingly.

 To verify location services, follow these steps:

1. Press **Win + I** to open the Settings window.
2. From the left navigation panel, click **Privacy & security**.
3. Under the **App permissions** section, select **Location**.
4. Make sure the **Location services** option is enabled. If it's not, switch the toggle to turn it on.  
![Enable Location Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-location-services.jpg)

 Now restart your computer and check if Windows can set the time zone automatically.

## 3\. Set the Windows Time Service to Automatic

 If the location services are already enabled, but Windows still can't detect the time zone, the problem may be related to the Windows Time Service. This background service keeps your system clock synchronized with time servers.

 Windows won't detect the time zone if the service is not running. To fix this issue, set Windows Time Service to Automatic.

 Here's how to do that:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **services.msc** in the text box and press **Enter**.
3. Scroll down in the Services window and locate the **Windows Time** service.
4. Right-click the service and select **Properties**.
5. In the Properties window, set the **Startup type** to **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
6. Now check the **Service status**. If it reads **Stopped**, click the **Start** button to start the service.
7. Click **Apply** and **OK** to save the changes.

 Once you've done this, restart your PC and check the time zone settings.

## 4\. Tweak the Registry Editor

 If Windows still fails to detect the time zone or the "Set time zone automatically" option is still grayed out, you may need to tweak your registry. This is a more technical solution and requires registry knowledge. If you're not good at registry editing, skip this step or ask a professional for help.

 Follow these steps to make the changes:

 Modifying the registry incorrectly may cause serious problems. Before making any changes, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

1. Press **Win + S** on your keyboard to open the Windows Search.
2. Type **regedit** in the search bar and press **Enter**.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following directory.  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\tzautoupdate`
5. In the right pane, double-click the **Start** (DWORD) value.  
![Modify Registry to change the Set time zone automatically setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-the-set-time-zone-automatically-setting.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
6. When the Edit DWORD Value window pops up, set the Value data to **3** and click **OK**.
7. After doing this, you must change the location setting. To do this, navigate to the following key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\location`  
 You can also copy and paste the path into the Registry Editor address bar. Now press Enter and this directs you to the Location key.
8. Move to the right pane and double-click the **Value** (REG\_SZ) value.  
![Edit Registry to change the location setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-registry-to-change-the-location-setting.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
9. In the Edit String window, type **Allow** in the **Value data** field and click OK.

 After that, close the Registry Editor and restart your PC. Windows should detect the time zone automatically and set it correctly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Use the Group Policy Editor

 If you're comfortable with registry editing, use the Group Policy Editor instead. However, the tool is only compatible with Windows Pro and Enterprise editions. If you're not a Pro user, [activate the Group Policy for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Right-click on Start and select **Run**.
2. Type **gpedit.msc** in the text field and click **OK**. The Local Group Policy Editor window will open.
3. On the left navigation panel, browse to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Location and Sensors > Windows Location Provider`
4. Go to the right pane and double-click on **Turn off Windows Location Provider**.  
![Turn off Windows Location Provider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/turn-off-windows-location-provider.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
5. In the pop-up window, check the **Not Configured** option.
6. Click **Apply** and **OK** to save the changes.

 Now close the Group Policy Editor and restart your PC. After restarts check if your Windows detects the time zone automatically.

## 6\. Reset the Windows Time Service

 This problem may also occur if the Windows Time Service or time synchronization settings become corrupted. In that case, reset the service to its default settings and see if that helps. Here's how to do it:

1. Click on Start and type **cmd** in the search box.
2. Press **Ctrl + Shift + Enter** on your keyboard simultaneously. This opens the Command Prompt in administrator mode.
3. If the pop-up window appears, click **Yes** to grant permission.
4. In the Command Prompt window, type net **stop w32time** and press **Enter**. Running this command will stop the Windows Time Service.
5. Now, type **w32tm /unregister** in the Command Prompt window and hit **Enter**. This unregisters the service.
6. Next, type **w32tm /register** and press **Enter**. This will re-register the Windows Time Service.
7. After that, type net **start w32time** to restart the Windows Time Service.

 Once done, close the Command Prompt and restart your computer to check if it solves the problem.

## 7\. Try Some Generic Windows Fixes

 There are also generic fixes you can try:

1. **Run the System File Checker tool:**[running System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) scans for corrupted system files and replaces them if necessary.
2. **Perform a Clean Boot:** If that didn't work, [try a Windows clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This determines if third-party applications interfere with Windows Time Service.
3. **Update Windows:** Finally, [update Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to ensure you have all the latest fixes and security patches.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Windows Can Now Automatically Set the Time Zone

 We hope the article helped you resolve timing issues on your Windows computer. It may occur due to missing or corrupted system files or incorrect time zone settings. Make sure to try these solutions and perform a System Restore if the problem persists.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-revolutionize-your-harvest-stardews-top-7-upgrades/"><u>[New] 2024 Approved  Revolutionize Your Harvest  Stardew's Top 7 Upgrades</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-concoct-chuckles-giphy-edition/"><u>[New] Concoct Chuckles - Giphy Edition</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elevate-your-youtube-gaming-content-with-key-freefire-hashtags-for-2024/"><u>[New] Elevate Your YouTube Gaming Content With Key FreeFire Hashtags for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-elite-9-access-privileged-video-downloads/"><u>[New] In 2024, Elite 9 Access  Privileged Video Downloads</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-the-method-for-seamless-volume-dialing-down-in-audacity/"><u>[New] In 2024, The Method for Seamless Volume Dialing Down in Audacity</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-ps3-experience-on-pc-leading-emulators-guide-for-2024/"><u>[New] PS3 Experience on PC  Leading Emulators Guide for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-creative-edge-pushing-boundaries-in-photography/"><u>[Updated] 2024 Approved  The Creative Edge  Pushing Boundaries in Photography</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-crafting-effective-youtube-thumbnails-and-banners-for-2024/"><u>[Updated] Crafting Effective YouTube Thumbnails & Banners for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-bulk-buy-subscribers-cost-effective-growth-strategy/"><u>[Updated] In 2024, Bulk Buy Subscribers  Cost-Effective Growth Strategy</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/"><u>[Updated] In 2024, High-End Downloads  Best 10 Apps for Extracting Vimeo Videos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-securing-successful-video-ventures-through-team-choices/"><u>[Updated] Securing Successful Video Ventures Through Team Choices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-swaying-symbols-dynamic-animation-for-text-effects/"><u>[Updated] Swaying Symbols  Dynamic Animation for Text Effects</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-chroma-spectrum-now-crystal-clear-on-4k/"><u>[Updated] The Ultimate Chroma Spectrum, Now Crystal Clear on 4K</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>3 Ways to Change Location on Facebook Marketplace for Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-photo-preview-boards-in-win-11/"><u>Adjusting Photo Preview Boards in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-introduction-to-windows-exepe-file-formats/"><u>An Introduction to Windows EXE/PE File Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apps-calm-demeanor-hides-computational-challenges-for-windows-users/"><u>Apps' Calm Demeanor Hides Computational Challenges for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-review-pcmac-comparison/"><u>ASUS Zenbook 14 OLED Review: PC/Mac Comparison?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-file-sync-solutions-for-windows-users/"><u>Best File Sync Solutions for Windows Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/building-blocks-for-a-thriving-design-career-for-2024/"><u>Building Blocks for a Thriving Design Career for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/bypass-the-wait-utilize-chatgpt-without-an-account-here-are-5-ways/"><u>Bypass the Wait: Utilize ChatGPT Without an Account Here Are 5 Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-windows-steam-broadcaster-errors/"><u>Combatting Windows Steam Broadcaster Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-failures-qt-platform-support-error-at-launch/"><u>Correcting Failures: 'Qt Platform Support' Error at Launch</u></a></li>
<li><a href="https://article-posts.techidaily.com/craft-your-own-cinematic-magic-making-slow-motion-video-from-photo-apps-for-2024/"><u>Craft Your Own Cinematic Magic  Making Slow Motion Video From Photo Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-approaches-to-adjacent-and-distinct-windows-partition-merging/"><u>Cutting-Edge Approaches to Adjacent and Distinct Windows Partition Merging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-incorrect-parameters-for-winloadlib/"><u>Dealing with Incorrect Parameters for WinLoadLib</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/discover-the-perfect-moment-timing-your-insta-posts/"><u>Discover the Perfect Moment  Timing Your Insta Posts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/dizzy-with-design-mastering-upside-down-imagery/"><u>Dizzy with Design  Mastering Upside Down Imagery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-subnet-tweak-for-experienced-users-win11/"><u>Effortless Subnet Tweak for Experienced Users, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-w11-desktop-customization-essentials/"><u>Effortless W11 Desktop Customization Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-terminal-usage-make-it-primary-choice/"><u>Elevate Your Terminal Usage: Make It Primary Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/envisioning-the-ideal-user-experience-in-windows-11/"><u>Envisioning the Ideal User Experience in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/extract-your-fb-videos-effortlessly-anywhere/"><u>Extract Your FB Videos Effortlessly, Anywhere</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-x50iplus-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Honor X50i+ PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-onedrive-on-a-windows-machine/"><u>How To Unlock Your OneDrive on a Windows Machine</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-elevating-your-instagram-conversations-an-in-depth-guide/"><u>In 2024, Elevating Your Instagram Conversations  An In-Depth Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-learn-how-to-lock-stolen-your-iphone-15-pro-max-properly-drfone-by-drfone-ios/"><u>In 2024, Learn How To Lock Stolen Your iPhone 15 Pro Max Properly | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-storytelling-methodologies-for-the-documentarian/"><u>In 2024, Storytelling Methodologies for the Documentarian</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/keeping-the-memories-efficiently-taking-screenshots-on-xbox-one/"><u>Keeping the Memories  Efficiently Taking Screenshots on Xbox One</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-forward-in-windows-video-management-integrate-tdarrs-distributed-capabilities/"><u>Leap Forward in Windows Video Management: Integrate Tdarr's Distributed Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-windows-files-disabling-read-only-status/"><u>Manipulating Windows Files: Disabling Read-Only Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-directory-management-without-renaming-features-in-windows-11/"><u>Mastering Directory Management without Renaming Features in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-epic-launcher-sign-in-on-pc/"><u>Mastering the Art of Epic Launcher Sign-In on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-lock-personal-pattern-creation-tutorial/"><u>Mastering Window's Lock: Personal Pattern Creation Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restart-printers-automatic-service-in-win/"><u>Methods to Restart Printer's Automatic Service in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiple-routes-for-opening-utilities-on-windows-systems/"><u>Multiple Routes for Opening Utilities on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hazards-of-cheap-windows-key-purchases/"><u>Navigating the Hazards of Cheap Windows Key Purchases</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-simplify-4k-video-post-production-the-top-proxy-video-editing-apps/"><u>New In 2024, Simplify 4K Video Post-Production The Top Proxy Video Editing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-11-search-top-5-expert-methods/"><u>Optimize Your Windows 11 Search: Top 5 Expert Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-discord-launch-and-update-check-with-windows-startup/"><u>Preventing Discord Launch and Update Check with Windows Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-absent-d3dx939dll-on-windows-11/"><u>Remedying Absent D3DX9_39.dll on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-disabled-volume-snapshots/"><u>Restoring Functionality to Disabled Volume Snapshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-error-0xa00f425d-in-windows-camera/"><u>Steps to Eliminate Error 0xA00F425D in Windows Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-by-unrealcefsubprocess-on-systems/"><u>Strategies to Reduce CPU and RAM Overuse by UnrealCEFSubprocess on Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-geforce-now-error-xc0f1103f/"><u>Tackling Windows 11'S GeForce Now Error Xc0f1103f</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-complete-process-of-scheduling-google-meets/"><u>The Complete Process of Scheduling Google Meets</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-launching-maplestory-without-errors/"><u>Troubleshooting Guide: Launching MapleStory Without Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-secrets-of-running-imessage-on-windows/"><u>Uncovering the Secrets of Running iMessage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-approach-to-allocated-ram/"><u>Understanding Windows' Approach to Allocated RAM</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-your-disabled-iphone-11-pro-without-itunes-in-5-ways-by-drfone-ios/"><u>Unlock Your Disabled iPhone 11 Pro Without iTunes in 5 Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-ways-for-swift-epic-game-loading/"><u>Unveiling Windows Ways for Swift Epic Game Loading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-unveiled-major-updates-on-windows-11-vs-10/"><u>Windows Unveiled: Major Updates on Windows 11 Vs. 10</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>