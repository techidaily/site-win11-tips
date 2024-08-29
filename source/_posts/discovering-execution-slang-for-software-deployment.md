---
title: Discovering Execution Slang for Software Deployment
date: 2024-08-28T01:16:46.974Z
updated: 2024-08-29T01:16:46.974Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Discovering Execution Slang for Software Deployment
excerpt: This Article Describes Discovering Execution Slang for Software Deployment
keywords: SoftDeploymentSlang,DevOpsJargon,AppReleaseTerms,CodeExecLanguage,DevWorkflowLingo,SoftwarePhraseology,ExecutionTalkSoftware
thumbnail: https://thmb.techidaily.com/1f78d2fb13516bc942d880b1ed451501538b368f9a6b178eea0c04126c8f2280.jpg
---

## Discovering Execution Slang for Software Deployment

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-capture-peak-performance-high-end-webcams-for-quality-live-streams-on-twitch/"><u>[New] 2024 Approved  Capture Peak Performance  High-End Webcams for Quality Live Streams on Twitch</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-an-intro-to-macs-5-leading-snipping-software-choices-for-2024/"><u>[New] An Intro to Mac's 5 Leading Snipping Software Choices for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-online-tools-select-your-new-photo-background/"><u>[New] Leading Online Tools  Select Your New Photo Background</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-next-level-game-monitoring-software-beyond-the-fbx-standard-for-2024/"><u>[New] Next Level Game Monitoring Software Beyond the FBX Standard for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-pixicapture-studio-winos-series/"><u>[New] PixiCapture Studio WinOS Series</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-capture-your-conversations-top-rated-free-and-paid-techniques-windowsmac/"><u>[Updated] 2024 Approved  Capture Your Conversations  Top-Rated Free and Paid Techniques (Windows/Mac)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-a-comprehensive-guide-to-smoothly-flip-movies-in-vlc-for-2024/"><u>[Updated] A Comprehensive Guide to Smoothly Flip Movies in VLC for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-cutting-edge-mini-drones-for-the-savvy-buyer/"><u>[Updated] Cutting-Edge Mini Drones for the Savvy Buyer</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-easy-alteration-rotate-film-frames-with-vlc-for-2024/"><u>[Updated] Easy Alteration  Rotate Film Frames with VLC for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-cultivating-cash-by-critiquing-consumer-commodities-online/"><u>[Updated] In 2024, Cultivating Cash by Critiquing Consumer Commodities Online</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-frontline-contenders-top-7-action-fps-games/"><u>[Updated] In 2024, Frontline Contenders  Top 7 Action FPS Games</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-instant-record-and-commentary-assistive-software/"><u>[Updated] In 2024, Instant Record & Commentary Assistive Software</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-mastering-angular-adjustments-in-vlc-player/"><u>[Updated] Mastering Angular Adjustments in VLC Player</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-savvy-soccer-snatching-how-to-record-and-cut-cheap/"><u>[Updated] Savvy Soccer Snatching  How to Record and Cut Cheap</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-streamline-your-path-to-youtubes-srt-files/"><u>2024 Approved  Streamline Your Path to YouTube's SRT Files</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-finest-5-android-image-boosters/"><u>2024 Approved  The Finest 5 Android Image Boosters</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/5-most-effective-methods-to-unlock-apple-iphone-14-in-lost-mode-drfone-by-drfone-ios/"><u>5 Most Effective Methods to Unlock Apple iPhone 14 in Lost Mode | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cleansing-local-disks-in-win11-preserving-your-files-max-156-chars/"><u>Cleansing Local Disks in Win11: Preserving Your Files (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-executable-and-linker-format-pe/"><u>Demystifying Windows Executable & Linker Format (PE)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-team-tools-without-the-burden/"><u>Efficient Team Tools Without the Burden</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-productivity-optimize-windows-tiling/"><u>Elevate Productivity: Optimize Windows Tiling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-window-11s-camera-app-crash-afc-error-code/"><u>Eliminating Window 11'S Camera APP Crash: AFC Error Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-reversing-problems-from-a-recent-windows-update/"><u>Expert Advice: Reversing Problems From a Recent Windows Update</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/expert-analysis-of-hitman-series-finale-game-three-unveiled/"><u>Expert Analysis of Hitman Series Finale, Game Three Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-expertise-accessing-tabs-with-ease-windows-11/"><u>File Expertise: Accessing Tabs with Ease (Windows 11)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixed-issue-with-installing-printer/"><u>Fixed Issue with Installing Printer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-awful-crash-in-chrome-browser-on-pc/"><u>Fixing Awful Crash in Chrome Browser on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-dark-display-issue-in-halo-infinite-simple-strategies-that-work/"><u>Fixing the Dark Display Issue in Halo Infinite: Simple Strategies That Work</u></a></li>
<li><a href="https://youtube-help.techidaily.com/from-freezing-points-to-inviting-landscapes-for-2024/"><u>From Freezing Points to Inviting Landscapes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gaming-mastery-on-windows-11-top-strategies-for-peak-performance-and-fun/"><u>Gaming Mastery on Windows 11: Top Strategies for Peak Performance and Fun</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/guidance-to-fix-iphone-autofocus-problems-immediately/"><u>Guidance to Fix iPhone Autofocus Problems Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-turn-onoff-windows-11-highlight-effect/"><u>Guide to Turn On/Off Windows 11 Highlight Effect</u></a></li>
<li><a href="https://techidaily.com/hard-reset-oppo-a38-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Oppo A38 in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-unable-to-connect-to-ea-servers-error-on-windows/"><u>How to Fix the “Unable to Connect to EA Servers” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-load-drivers-without-sie-compliance-on-pcs/"><u>How to Load Drivers Without SIE Compliance on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-chromium-from-spontaneously-launching-tabs/"><u>How to Prevent Chromium From Spontaneously Launching Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-inadvertent-windows-key-activation/"><u>How to Prevent Inadvertent Windows Key Activation</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-poco-m6-5g-by-fonelab-android-recover-video/"><u>How to recover old videos from your Poco M6 5G</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-screen-lock-pin-on-vivo-v29-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Vivo V29 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unstick-scrollbar-fix-for-excel-on-pc/"><u>How to Unstick Scrollbar: Fix for Excel on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-file-access-in-geforce-experience/"><u>Improving File Access in GeForce Experience</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-live-stream-perfection-ranking-the-best-recorder-gadgets-in-tech/"><u>In 2024, Live Stream Perfection  Ranking the Best Recorder Gadgets in Tech</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-step-up-your-game-mastering-the-art-of-capturing-playthroughs/"><u>In 2024, Step Up Your Game  Mastering the Art of Capturing Playthroughs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/inside-look-at-samsung-unpacked-2025-all-upcoming-devices-rumors-and-breakthrough-tech-news-covered/"><u>Inside Look at Samsung Unpacked 2025 - All Upcoming Devices, Rumors, and Breakthrough Tech News Covered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/linguistic-harmony-installing-fonts-for-all-windows-users/"><u>Linguistic Harmony: Installing Fonts for All Windows Users</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/navigating-the-world-of-wireless-with-linksys-velop-a-top-tier-router-assessment/"><u>Navigating the World of Wireless with Linksys Velop: A Top-Tier Router Assessment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11s-task-manager-for-process-control-and-theme-personalization/"><u>Navigating Windows 11'S Task Manager for Process Control and Theme Personalization</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-video-editing-essentials-how-to-split-clips-in-windows-live-movie-maker-updated/"><u>New 2024 Approved Video Editing Essentials How to Split Clips in Windows Live Movie Maker (Updated)</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-what-is-talking-avatar-in-2024/"><u>New What Is Talking Avatar, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obscure-your-wi-fi-networks-on-windows-pc/"><u>Obscure Your Wi-Fi Networks on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-tcpip-port-detection-techniques-on-windows-systems/"><u>Open TCP/IP Port Detection Techniques on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-upgrade-rejected-error-messages/"><u>Overcoming Windows Upgrade Rejected Error Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powershell-techniques-to-track-down-win-ipmac-info/"><u>PowerShell Techniques to Track Down Win IP/MAC Info</u></a></li>
<li><a href="https://win11-tips.techidaily.com/puzzled-by-snipits-shutdown-9-recovery-methods-unveiled/"><u>Puzzled by SnipIt's Shutdown? 9 Recovery Methods Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-enhance-pointer-features-in-windows-11/"><u>Quick Fixes to Enhance Pointer Features in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-messenger-magic-on-windows-devices/"><u>Reigniting Messenger Magic on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-unresponsive-keys-in-windows-computer-setup/"><u>Repairing Unresponsive Keys in Windows Computer Setup</u></a></li>
<li><a href="https://win-able.techidaily.com/resolved-how-to-enable-graphics-processing-unit-gpu-in-call-of-duty-warzone-on-windows-10/"><u>Resolved: How to Enable Graphics Processing Unit (GPU) in Call of Duty: Warzone on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-low-performance-pcs-overcoming-intel-hd-graphics-issues/"><u>Resolving Low-Performance PCs: Overcoming Intel HD Graphics Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revise-your-context-menu-get-rid-of-show-more-entry/"><u>Revise Your Context Menu: Get Rid of Show More Entry</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ringsong-blueprint-guide-for-turning-tamil-tracks-into-notifications/"><u>RingSong Blueprint  Guide for Turning Tamil Tracks Into Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rotate-like-a-pro-6-easy-steps-for-windows-photos/"><u>Rotate Like a Pro: 6 Easy Steps for Windows Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-onedrive-and-microsoft-account-connection-guide/"><u>Seamless OneDrive & Microsoft Account Connection Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-hiding-personal-info-on-windows-login/"><u>Securely Hiding Personal Info on Windows Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-opening-win-11s-call-center/"><u>Steps for Opening Win 11'S Call Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-geforce-experience-from-failing-windows-guide/"><u>Stop GeForce Experience From Failing: Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-darkened-screens-while-gaming-on-win/"><u>Strategies to Prevent Darkened Screens While Gaming on WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-o365-cloud-synchronization-hiccups-windows/"><u>Tackling O365 Cloud Synchronization Hiccups (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-windows-ambiance-installing-from-the-ms-store/"><u>Transitioning Windows Ambiance: Installing From The MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-file-disappearance-top-8-methods/"><u>Troubleshooting File Disappearance: Top 8 Methods</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-fixing-update-issues-with-the-minecraft-java-edition-launcher/"><u>Troubleshooting: Fixing Update Issues with the Minecraft Java Edition Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-power-to-change-file-formats/"><u>Unlocking Windows' Power to Change File Formats</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unraveling-the-best-free-srt-translators-your-essential-guidebook/"><u>Unraveling the Best Free SRT Translators  Your Essential Guidebook</u></a></li>
</ul></div>
