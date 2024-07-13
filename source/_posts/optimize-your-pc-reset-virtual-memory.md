---
title: "Optimize Your PC: Reset Virtual Memory"
date: 2024-07-12T16:54:27.189Z
updated: 2024-07-13T16:54:27.189Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Your PC: Reset Virtual Memory"
excerpt: "This Article Describes Optimize Your PC: Reset Virtual Memory"
keywords: PC Memory Optimization,Virtual Mem Reset Guide,Enhance System Speed,RAM Efficiency Tips,Increase PC Performance,Adjust Virtual RAM,Boost Computer Speed
thumbnail: https://thmb.techidaily.com/e8d9fb9f5398f4a792320d2b13c1a57276ee28fb817fc4d294eae20885dd4758.jpg
---

## Optimize Your PC: Reset Virtual Memory

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


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
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-prevent-freezing-of-streamed-videos-in-chrome/"><u>[Updated] 2024 Approved  Prevent Freezing of Streamed Videos in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-command-over-disabled-menu-functions/"><u>Regaining Command over Disabled Menu Functions</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-auditory-aesthetics-for-slides-infusing-your-ppt-with-tunes/"><u>In 2024, Auditory Aesthetics for Slides  Infusing Your PPT with Tunes</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-social-media-riches-joining-the-elite-of-tiktok-creators-for-2024/"><u>[New] Social Media Riches  Joining the Elite of TikTok Creators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-volume-control-fix-guide/"><u>Windows 10/11 Volume Control Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-state-of-the-art-ai-windows-edition/"><u>Running State-of-the-Art AI: Windows Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-redefining-realities-practical-vr-uses/"><u>2024 Approved  Redefining Realities  Practical VR Uses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-by-unrealcefsubprocess-on-systems/"><u>Strategies to Reduce CPU and RAM Overuse by UnrealCEFSubprocess on Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masteringdarkmodesettingforwindowstexteditor/"><u>MasteringDarkModeSettingForWindowsTextEditor</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-achieving-cinematic-quality-through-aspect-ratio-choices/"><u>In 2024, Achieving Cinematic Quality Through Aspect Ratio Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-account-security-changing-reset-counter-after-failed-logins/"><u>Optimizing Account Security: Changing Reset Counter After Failed Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-secrets-of-running-imessage-on-windows/"><u>Uncovering the Secrets of Running iMessage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-keyways-to-activate-telnet-on-windows-11-pcs/"><u>3 Keyways to Activate Telnet on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-ways-for-swift-epic-game-loading/"><u>Unveiling Windows Ways for Swift Epic Game Loading</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-mastering-desktopmobile-screen-sharing-in-google-meet/"><u>[Updated] 2024 Approved  Mastering Desktop/Mobile Screen Sharing in Google Meet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-error-0xa00f425d-in-windows-camera/"><u>Steps to Eliminate Error 0xA00F425D in Windows Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-11-search-top-5-expert-methods/"><u>Optimize Your Windows 11 Search: Top 5 Expert Methods</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-cant-get-mail-errors-windows-11-edition/"><u>Strategies to Overcome Can’t Get Mail Errors, Windows 11 Edition</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-establishing-whatsapp-meeting-rooms-efficiently/"><u>2024 Approved  Establishing WhatsApp Meeting Rooms Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-tools-for-microsoft-enthusiasts/"><u>Top 8 Cross-Platform Tools for Microsoft Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-windows-files-disabling-read-only-status/"><u>Manipulating Windows Files: Disabling Read-Only Status</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-this-pc-cant-run-post-windows-11-setup/"><u>Rectifying 'This PC Can't Run' Post-Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-downloading-errors-in-microsoft-store/"><u>Addressing Downloading Errors in Microsoft Store</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/fix-apple-iphone-6-plus-stuck-on-data-transfer-verified-solution-drfone-by-drfone-transfer-from-ios/"><u>Fix Apple iPhone 6 Plus Stuck on Data Transfer Verified Solution! | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-tracking-payment-for-consumer-feedback-vlogs-for-2024/"><u>[Updated] Tracking Payment for Consumer Feedback Vlogs for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-a-compreayers-guide-to-capturing-console-games-on-a-computer/"><u>[New] 2024 Approved  A Compreayer's Guide to Capturing Console Games on a Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hazards-of-cheap-windows-key-purchases/"><u>Navigating the Hazards of Cheap Windows Key Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-ignoring-soon-expiring-licenses-alerts-in-windows/"><u>Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows</u></a></li>
<li><a href="https://fox-blue.techidaily.com/effortlessly-faster-fb-videos-a-comprehensive-tools-repository-for-2024/"><u>Effortlessly Faster FB Videos  A Comprehensive Tools Repository for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-navigating-new-media-the-marketers-top-10-ig-editing-platforms/"><u>In 2024, Navigating New Media  The Marketer's Top 10 IG Editing Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-internal-errors-quickly-with-windows-rdp-connections/"><u>Resolving Internal Errors Quickly with Windows RDP Connections</u></a></li>
<li><a href="https://extra-skills.techidaily.com/lumafusion-tips-for-subtle-sound-reduction-for-2024/"><u>Lumafusion Tips for Subtle Sound Reduction for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-history-hiccup-quick-fixes-in-3-steps/"><u>Windows History Hiccup - Quick Fixes in 3 Steps</u></a></li>
<li><a href="https://video-capture.techidaily.com/discover-the-hits-top-tracks-on-spotify-for-2024/"><u>Discover the Hits  Top Tracks on Spotify for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-zoomed-details-for-team-collaboration-on-ms-teams/"><u>[New] Navigating Zoomed Details for Team Collaboration on MS Teams</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-rank-your-download-preferences-with-our-top-5-list/"><u>[Updated] Rank Your Download Preferences with Our Top 5 List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-error-0x0000004e-in-windows-devices/"><u>Navigating Error 0X0000004E in Windows Devices</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/crafting-impactful-content-on-tiktok-with-these-best-quotes/"><u>Crafting Impactful Content on TikTok with These Best Quotes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-organization-in-windows-11/"><u>Simplifying File Organization in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-reactivating-ms-store-apps-in-windows-11/"><u>Regaining Access: Reactivating MS Store Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiple-routes-for-opening-utilities-on-windows-systems/"><u>Multiple Routes for Opening Utilities on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-discord-launch-and-update-check-with-windows-startup/"><u>Preventing Discord Launch and Update Check with Windows Startup</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-winning-strategies-and-hashtags-for-youtubes-best-freefirers/"><u>2024 Approved  Winning Strategies & Hashtags for YouTube's Best FreeFirers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-approach-to-allocated-ram/"><u>Understanding Windows' Approach to Allocated RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-windows-11-potential-via-powertoys-install/"><u>Unleashing Windows 11 Potential via PowerToys Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-epic-launcher-sign-in-on-pc/"><u>Mastering the Art of Epic Launcher Sign-In on PC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-15-plus-without-passcode-drfone-by-drfone-ios/"><u>How to Unlock iPhone 15 Plus Without Passcode? | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-snap-smart-the-best-iphone-and-android-apps-for-photo-stickers/"><u>2024 Approved  Snap Smart - The Best iPhone and Android Apps for Photo Stickers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-flex-your-viewing-muscles-handling-multiple-youtube-videos-for-2024/"><u>[Updated] Flex Your Viewing Muscles  Handling Multiple YouTube Videos for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-art-of-gameye-immersive-video-recording/"><u>[New] The Art of GamEye  Immersive Video Recording</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-mobile-video-editing-made-easy-top-10-free-green-screen-apps/"><u>Updated Mobile Video Editing Made Easy Top 10 Free Green Screen Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remediation-steps-for-windows-sandboxs-hypervisor-not-found/"><u>Remediation Steps for Windows Sandbox's Hypervisor Not Found</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-breaking-down-the-barriers-effective-rtmp-streaming-in-premiere/"><u>2024 Approved  Breaking Down the Barriers  Effective RTMP Streaming in Premiere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-taskbar-icon-anomalies/"><u>Rectifying Taskbar Icon Anomalies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-what-do-podcast-producers-really-make/"><u>[New] In 2024, What Do Podcast Producers Really Make?</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/tricks-to-convert-video-to-mp3-without-losing-quality/"><u>Tricks to Convert Video to MP3 without Losing Quality</u></a></li>
</ul></div>
