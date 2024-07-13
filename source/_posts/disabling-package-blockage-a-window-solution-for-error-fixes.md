---
title: "Disabling Package Blockage: A Window Solution for Error Fixes"
date: 2024-07-12T17:03:26.292Z
updated: 2024-07-13T17:03:26.292Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Disabling Package Blockage: A Window Solution for Error Fixes"
excerpt: "This Article Describes Disabling Package Blockage: A Window Solution for Error Fixes"
keywords: Fix Packaging Errors,Window Repair Tips,Unblock Package Issues,Windows Solutions,Clear Error Blockages,Package Disabling Guide,Windows Maintenance Help
thumbnail: https://thmb.techidaily.com/88b9d1a1839e87bc852a7b88397e12987972348fa38a161adde19f109b06aa2c.jpg
---

## Disabling Package Blockage: A Window Solution for Error Fixes

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by [opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to [opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://win11-tips.techidaily.com/intro-to-digital-art-accessing-microsoft-paint-in-windows-11/"><u>Intro to Digital Art: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-to-combat-windows-1011-error-740/"><u>Swift Strategies to Combat Windows 10/11 Error 740</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-top-10-emerging-youtube-channels-to-spark-motivation/"><u>[New] In 2024, Top 10 Emerging YouTube Channels to Spark Motivation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-upgrade-hurdle-top-7-deterrents-to-windows-11-switching/"><u>The Upgrade Hurdle: Top 7 Deterrents to Windows 11 Switching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resurrect-lost-keyboard-erase-functionality/"><u>How to Resurrect Lost Keyboard Erase Functionality</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-optimal-ram-assignment-for-superior-minecraft-gaming-for-2024/"><u>[Updated] Optimal Ram Assignment for Superior Minecraft Gaming for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-realme-narzo-n55-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Realme Narzo N55 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-portable-executable-an-overview/"><u>Windows' Portable Executable: An Overview</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/videopie-interpretation-platform/"><u>VideoPie Interpretation Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-techniques-to-resolve-error-code-3-on-gl-drivers/"><u>Expert Techniques to Resolve Error Code 3 on GL Drivers</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-15-best-android-emulator-mac-and-pc/"><u>[New] 15 Best Android Emulator (Mac and PC)</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-a-full-review-for-itools-virtual-location-and-top-5-alternatives-for-apple-iphone-14-pro-maxipad-drfone-by-drfone-virtual-ios/"><u>In 2024, A Full Review for iTools Virtual Location and Top 5 Alternatives For Apple iPhone 14 Pro Max/iPad | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/legacy-tech-lifeline-atlasos-revival-plan/"><u>Legacy Tech Lifeline: AtlasOS Revival Plan</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/mastering-instagram-boosting-post-engagement-strategies-for-2024/"><u>Mastering Instagram  Boosting Post Engagement Strategies for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-trim-and-cut-avi-files-like-a-pro-top-tools-for-every-platform-windows-mac-android-iphone-online/"><u>New 2024 Approved Trim and Cut AVI Files Like a Pro Top Tools for Every Platform Windows, MAC, Android, iPhone, Online</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-professional-recording-hacks-to-amplify-video-quality/"><u>[New] Professional Recording Hacks to Amplify Video Quality</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-5-pinterest-video-clips-download-for-no-cost/"><u>[Updated] Best 5 Pinterest Video Clips, Download for No Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-space-available-for-windows-11-pin-listings/"><u>Boosting Space Available for Windows 11 Pin Listings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-shopping-microsoft-store-error-0x80072f30-cure/"><u>Simplify Your Shopping: Microsoft Store Error 0X80072F30 Cure</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-top-10-premium-free-audio-streaming-apps-ios-and-android-edition/"><u>New 2024 Approved Top 10 Premium-Free Audio Streaming Apps IOS & Android Edition</u></a></li>
<li><a href="https://howto.techidaily.com/lava-blaze-2-pro-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Lava Blaze 2 Pro Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-calendar-look-with-outlook-customization-tricks/"><u>Elevate Your Calendar Look with Outlook Customization Tricks</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-flawless-coexistence-of-linktree-and-tiktok-biographies/"><u>2024 Approved  Flawless Coexistence of Linktree and TikTok Biographies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-the-restricted-world-of-windows-11/"><u>Delving Into the Restricted World of Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/oppo-a2-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo A2 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-win-credits-to-microsoft-logins/"><u>Directing WIN Credits to MICROSOFT LOGINS</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-creating-dynamic-chat-spaces-on-whatsapp-for-2024/"><u>[New] Creating Dynamic Chat Spaces on WhatsApp for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-unsignatured-drivers-on-modern-windows/"><u>Tricks for Unsignatured Drivers on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-notepads-visual-transformation-with-dark-themes-windows/"><u>Master Notepad’s Visual Transformation with Dark Themes (Windows)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-who-are-the-biggest-watchers-top-amazon-series-liked-by-twitter-2023/"><u>[New] Who Are the Biggest Watchers? Top Amazon Series Liked by Twitter, 2023</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-quality-iphone-filmmaking-top-8-tips/"><u>The Ultimate Guide to Quality iPhone Filmmaking (Top 8 Tips)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-11s-full-potential-through-taskbar-utilization/"><u>Unleash Windows 11'S Full Potential Through Taskbar Utilization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-sid-exploration-a-comprehensible-guidebook/"><u>Windows 11 SID Exploration: A Comprehensible Guidebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enhance-windows-11-task-manager-with-a-search-tool/"><u>How to Enhance Windows 11 Task Manager with a Search Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/data-defense-on-windows-top-rated-encryption-applications-153-chars/"><u>Data Defense on Windows: Top-Rated Encryption Applications (153 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-tutorial-for-turning-on-windows-11s-quick-start/"><u>Step-by-Step Tutorial for Turning On Windows 11'S Quick Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-shutting-down-windows-11-privacy-features/"><u>Guide to Shutting Down Windows 11 Privacy Features</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-realme-c53-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Realme C53 Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-hacks-bypassing-windows-account-verification/"><u>Advanced Hacks: Bypassing Windows Account Verification</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-stolen-apple-iphone-14-pro-max-in-different-conditionsin-drfone-by-drfone-ios/"><u>In 2024, How To Unlock Stolen Apple iPhone 14 Pro Max In Different Conditionsin | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-make-excel-2010-hyperlinks-working-by-stellar-guide/"><u>Easy Steps to Make Excel 2010 Hyperlinks Working</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-itel-p55-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Itel P55 Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-elevate-your-photo-game-top-5-android-photo-editors-ranked/"><u>[Updated] In 2024, Elevate Your Photo Game  Top 5 Android Photo Editors Ranked</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-moviemaster-for-macos/"><u>2024 Approved MovieMaster for macOS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-top-8-metaverse-headsets-and-glasses-to-dive-into-metaverse-for-2024/"><u>[Updated] Top 8 Metaverse Headsets and Glasses to Dive Into Metaverse for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-chrome-stuck-in-w11-quick-fixes/"><u>Troubleshooting: Chrome Stuck in W11? Quick Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-to-configuring-pc-manager/"><u>Unveiling the Secrets to Configuring PC Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-control-of-windows-read-only-constraints/"><u>Taking Control of Windows Read-Only Constraints</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-editprime-vision/"><u>[Updated] 2024 Approved  EditPrime Vision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-from-frozen-windows-pin-locks/"><u>Breaking Free From Frozen Windows PIN Locks</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-elevate-viewing-experience-enable-av1-on-youtube/"><u>In 2024, Elevate Viewing Experience – Enable AV1 on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-screen-snag-reviewed-in-depth-analysis/"><u>2024 Approved  Screen Snag Reviewed  In-Depth Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-the-ultimate-alternatives-to-native-software/"><u>Win 11: The Ultimate Alternatives to Native Software</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-itel-a60-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Itel A60 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-system-requirements-not-met-watermark-in-windows-11/"><u>How to Remove the System Requirements Not Met Watermark in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-fix-java-non-installation-in-windows/"><u>Approaches to Fix Java Non-Installation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/including-third-party-storage-on-file-explorer/"><u>Including Third-Party Storage on File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-secrets-to-discovering-window-settings/"><u>15 Secrets to Discovering Window Settings</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-mastering-fcpx-tips-and-tricks-for-overcoming-common-obstacles/"><u>Updated Mastering FCPX Tips and Tricks for Overcoming Common Obstacles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-full-disk-notification-in-windows/"><u>How To Prevent Full Disk Notification in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abruptly-quell-windows-11-interruptions/"><u>Abruptly Quell Windows 11 Interruptions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-sns-hdr-pro-analysis-worth-its-weight-in-gold/"><u>[New] SNS HDR Pro Analysis  Worth Its Weight in Gold?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-variances-in-remote-and-in-house-windows-setup/"><u>Analyzing Variances in Remote & In-House Windows Setup</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-samsung-galaxy-f15-5g-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Samsung Galaxy F15 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lost-in-5ghz-revive-your-connection-with-these-fixes-for-windows-11/"><u>Lost in 5GHz? Revive Your Connection with These Fixes for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-nvidia-driver-selection-gameplay-or-studio-focus/"><u>Ideal Nvidia Driver Selection - Gameplay or Studio Focus</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-how-to-do-masking-in-after-effects-alternative-provided/"><u>2024 Approved How to Do Masking in After Effects Alternative Provided</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-tackling-epic-games-sign-in-on-pc/"><u>Efficiently Tackling Epic Games Sign-In on PC</u></a></li>
</ul></div>
