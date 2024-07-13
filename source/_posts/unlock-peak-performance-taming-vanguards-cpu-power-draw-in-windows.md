---
title: "Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows"
date: 2024-07-12T17:11:34.530Z
updated: 2024-07-13T17:11:34.530Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows"
excerpt: "This Article Describes Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows"
keywords: Unlock Peak Performance,Vanguard CPU Management,Reducing Power Draw,High-Performance PC Optimization,Windows CPU Efficiency Tips,Limiting Vanguard's Consumption,Enhancing System Speed
thumbnail: https://thmb.techidaily.com/77d3e1b90c90a1223bd94c398f31bb9940ba742ed134b8bf4a5fe9e955fed55f.jpg
---

## Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows

 Is the "Vanguard user-mode service" process consuming too much of your CPU resources when playing Valorant? This indicates that Riot Vanguard, an anti-cheat software that prevents unfair gameplay in Valorant, isn't working as it should. High CPU usage can cause lag and stutter in Valorant, completely ruining its performance.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

## 1\. Apply Some Preliminary Checks

 Start de-stressing your CPU by taking the following basic steps, as they may reduce resource usage immediately:

* Restart Valorant or any other game that spikes the Vanguard user-mode service's CPU consumption.
* Whitelist Vanguard from Windows Defender (see [how to allow apps through the Microsoft firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/)) and the antivirus software you use to ensure your security suites don't cause Vanguard to consume more CPU resources than necessary.
* Be sure to turn off any cheat software you're using to manipulate Valorant or any other Riot Games game.
* Use the Task Manager to filter the processes consuming the most CPU resources by descending order to determine if Vanguard overstresses the CPU the most. If another process turns out to be more burdensome, turn it off.

 If none of the above checks fixes the problem, apply the remaining fixes.

## 2\. Disable and Restart Valorant and Vanguard Processes

 First off, ensure that a temporary glitch hasn't fueled the high CPU usage by the Vanguard user-mode service process. The easiest way to rule out this possibility is to close Valorant, turn off the Vanguard services, and restart them.

 To disable them, right-click the Windows **Start** button and open the **Task Manager**. Here, locate the Vanguard and Valorant-related processes, right-click on each process, and select **End task**.

![Disable Vanguard-Related Processes From Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-disable-vanguard-related-processes-from-windows-task-manager.jpg)

 Once these processes are disabled, give Valorant a fresh start, which will automatically restart Vanguard. If restarting the processes doesn't make a difference and the process continues to overstretch the CPU, move on to the next step.

## 3\. Make the Vanguard User-Mode Service Process a Low Priority

 Windows allows users to limit the CPU resource usage of processes in two different ways. The first is to change the priority of the process, and the second is to turn on the efficiency mode. Using either of these methods limits the allocation of CPU resources to less essential processes, limiting their CPU usage.

 To change the priority of Vanguard-related processes, go to the **Details** tab, right-click on the **vgc.exe** or any other process, and select **Low** from the **Set Priority** menu.

![Change the Priority of the Vanguard User Mode Service Process in the Set Priority Menu in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-set-the-vanguard-user-mode-service-process-a-low-priority-in-the-set-priority-menu-in-windows-task-manager.jpg)

 If you choose the latter option to control CPU resource consumption, right-click on the same process and choose **Efficiency mode**.

![Enable the Efficiency Mode of Vgc in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-go-to-efficiency-mode-of-vgc-in-windows-task-manage.jpg)

## 4\. Change the Processor Affinity

 The processor affinity setting in Task Manager allows you to limit the number of processors a process can use. Using this setting, you can instruct the process to use only a few processors while leaving others free. In general, the fewer processors a process is permitted to use, the lower its overall resource consumption will be.

 In light of that, changing the processor affinity for the Vanguard process may resolve the issue at hand. To do that, right-click the **vgc.exe** or any other process you want to change the affinity for, then click **Set affinity**.

![Click on Set Affinity Option of Vgc exe in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/5-click-on-set-affinity-option-of-vgc-exe-in-windows-task-manager.jpg)

 Here, uncheck the boxes besides most of the **CPUs** and keep only a few of them checked.

![Disable Unnecessary CPUs From Processor Affinity Settings in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-disable-unnecessary-cpus-from-processor-affinity-settings-in-windows-task-manager.jpg)

## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.
4. After that, restart the service by clicking on the **Start** button again.  
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  
![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

## 6\. Disable Third-Party Overlays

 Riot Vanguard is an anti-cheat program. It prevents cheating and bans users who attempt to hack into the game. It does this by detecting unauthorized changes made to the game files and settings using third-party cheat software.

 As reported by some users, using the in-game overlays can also spike CPU resource usage for the Vanguard user-mode service process. Turning off the third-party overlays resulted in a reduction in resource consumption for those users.

 Therefore, if you're using any third-party app to enable in-game overlay, especially Discord, turn it off. Hopefully, this will reduce CPU usage.

![Check the Assigned Hotkey Under Toggle Overlay Lock in the Discord's Game Overlay Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/7-check-the-assigned-hotkey-under-toggle-overlay-lock-in-the-discord-s-game-overlay-settings.jpg)

## 7\. Move Valorant to a Different Drive

 Installing Valorant on the same drive as your operating system has been reported to cause problems. If you've also installed the game on the same drive where your OS resides, it's possible that Windows security could be hindering Vanguard's activity, making it consume more resources.

 To ensure that's not the case, you should move Valorant to a different drive. Not sure how to do that? Refer to our guide on [how to move the installed apps and programs in Windows 10 or 11.](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/)

## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

## Don't Let Vanguard Overstress Your CPU

 The consumption of excessive CPU resources by a single process can affect the game's performance and degrade the overall system performance. Hopefully, you now better understand what causes the CPU spike for the Vanguard user-mode service process and the best ways to bring it down to a normal level.

 If none of the fixes above lower CPU consumption, your last resort should be to uninstall Valorant (or any other game) and reinstall it fresh.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/seamless-system-controls-learn-how-to-use-4-techniques-for-disk-editor-on-win11/"><u>Seamless System Controls: Learn How to Use 4 Techniques for Disk Editor on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-toggle-smartscreen-filters-in-windows-11/"><u>Steps to Toggle SmartScreen Filters in Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-sony-xperia-10-v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-step-by-step-guide-for-capturing-fb-streams/"><u>[Updated] 2024 Approved  Step-by-Step Guide for Capturing FB Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-tasks-the-power-of-flow-launcher-in-windows/"><u>Optimize Tasks: The Power of Flow Launcher in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-subnet-shift-a-guide-to-win11-networks/"><u>Master the Subnet Shift: A Guide to Win11 Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fix-guide-combatting-a-non-active-wsresetexe/"><u>The Ultimate Fix Guide: Combatting a Non-Active WSReset.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powershell-command-for-extracting-ip-and-mac-addresses/"><u>PowerShell Command for Extracting IP & MAC Addresses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-git-operations-github-desktop-and-windows-11-explained/"><u>Simplifying Git Operations: GitHub Desktop and Windows 11 Explained</u></a></li>
<li><a href="https://discord-videos.techidaily.com/social-expansion-the-desktop-and-mobile-guide-for-2024/"><u>Social Expansion  The Desktop & Mobile Guide for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/the-ultimate-guide-to-removing-tiktok-watermarks-online-for-2024/"><u>The Ultimate Guide to Removing TikTok Watermarks Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-sudden-security-hurdles/"><u>Overcoming Windows 11'S Sudden Security Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-subtle-art-of-windows-11s-user-information-extraction/"><u>The Subtle Art of Windows 11'S User Information Extraction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-grandmas-old-computer-for-better-use/"><u>Transform Your Grandma’s Old Computer for Better Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synchronizing-sound-pathways-resolving-paudio-in-winaudacity/"><u>Synchronizing Sound Pathways: Resolving PAudio in WINAudacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-chrome-blackouts/"><u>Taming Windows Chrome Blackouts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-step-by-step-blueprint-crafting-engaging-youtube-content-via-windows-movie-maker/"><u>[Updated] Step-by-Step Blueprint  Crafting Engaging YouTube Content via Windows Movie Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-fury-not-frustration-fixing-lag-in-sw-battlefront-2/"><u>Unleash Fury, Not Frustration: Fixing Lag in SW Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redressing-invisible-lan-windows-network-guide/"><u>Redressing Invisible LAN: Windows Network Guide</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-captivating-clips-incorporating-text-deformation-artistry/"><u>In 2024, Captivating Clips  Incorporating Text Deformation Artistry</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-visual-vaults-expert-tips-on-capturing-and-storing-twitter-video/"><u>In 2024, Visual Vaults  Expert Tips on Capturing and Storing Twitter Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-event-viewer-issues-on-windows-11/"><u>Solving Event Viewer Issues on Windows 11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-orchestrating-originality-top-8-schools-for-story-innovation-for-2024/"><u>[New] Orchestrating Originality  Top 8 Schools for Story Innovation for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-high-quality-video-webcams-top-5-combos-with-sound/"><u>[Updated] In 2024, High-Quality Video Webcams - Top 5 Combo's With Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-pc-top-winners-from-microsofts-store/"><u>Revolutionize Your PC: Top Winners From Microsoft's Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-low-usb-controller-limitation-error/"><u>Remedying “Low USB Controller Limitation” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-net-core-not-installed-app-issue-in-windows/"><u>Overcoming .NET Core Not Installed App Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-speaker-functionality-in-computers-abruptly/"><u>Restore Speaker Functionality in Computers Abruptly</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-premiere-pro-excellence-through-fs-views/"><u>[Updated] Premiere Pro  Excellence Through FS Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-how-to-engage-telnet-securely/"><u>Windows 11: How to Engage Telnet Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-keyboard-functionality-embedding-commands-for-wordpad-into-context-bar/"><u>Optimizing Keyboard Functionality: Embedding Commands for Wordpad Into Context Bar</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-securing-perfection-top-10-free-mac-screen-recorders-unveiled/"><u>[New] In 2024, Securing Perfection  TOP 10 FREE Mac Screen Recorders Unveiled</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-capturing-attention-striking-shots-for-youtube-success/"><u>[New] 2024 Approved  Capturing Attention  Striking Shots for YouTube Success</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-androids-finest-10-movie-maker-apps-you-need-to-try/"><u>In 2024, Androids Finest 10 Movie Maker Apps You Need to Try</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-techniques-for-live-broadcasting-recorded-videographies-on-fb/"><u>2024 Approved  Techniques for Live Broadcasting Recorded Videographies on FB</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-find-your-digital-companion-the-top-6-youtube-personality-puzzles/"><u>In 2024, Find Your Digital Companion  The Top 6 YouTube Personality Puzzles</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ace-windows-10-tricks-to-save-time-and-energy-for-2024/"><u>Ace Windows 10 Tricks to Save Time & Energy for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-effortless-zoom-edge-management-your-visual-companion/"><u>[Updated] 2024 Approved  Effortless Zoom Edge Management  Your Visual Companion</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-critical-analysis-of-vsdc-highlighting-best-software/"><u>[New] 2024 Approved  Critical Analysis of VSDC, Highlighting Best Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-streamlining-display-with-adjusted-desk-icons/"><u>Title: Streamlining Display with Adjusted Desk Icons</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-core-strategies-for-android-video-capture/"><u>[New] Core Strategies for Android Video Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-lan-access-blockades-in-winmc/"><u>Overcoming LAN Access Blockades in WinMC</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-iphone-x-secure-access-restoring-biometric-lock/"><u>2024 Approved  Mastering iPhone X Secure Access  Restoring Biometric Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-problem-solving-in-windows-1011-with-shortcuts/"><u>Personalizing Problem-Solving in Windows 10/11 with Shortcuts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-dive-deep-into-sims-4-gameplay-with-videography-for-2024/"><u>[Updated] Dive Deep Into Sims 4 Gameplay with Videography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-authorization-snags-head-on/"><u>Tackling Windows Authorization Snags Head-On</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-purchase-pitfalls-steering-clear-from-the-seduction-of-false-subscribers/"><u>[New] In 2024, Purchase Pitfalls  Steering Clear From the Seduction of False Subscribers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-error-resolution-guide-for-windows-enthusiasts/"><u>OneDrive Error Resolution Guide for Windows Enthusiasts</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-crafting-winning-collaboration-plans-on-youtube/"><u>[New] 2024 Approved  Crafting Winning Collaboration Plans on YouTube</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-unlock-tiktoks-potential-with-our-sizzling-template-selection/"><u>2024 Approved  Unlock TikTok’s Potential with Our Sizzling Template Selection</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-get-more-views-with-the-best-youtube-thumbnail-ideas/"><u>[New] Get More Views with the Best YouTube Thumbnail Ideas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-faded-bios-boot-options/"><u>Remedy for Faded BIOS Boot Options</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-the-best-binge-worthy-series-on-twittersphere/"><u>2024 Approved  The Best Binge-Worthy Series on Twittersphere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-wi-fi-potential-in-windows-11-with-these-tips/"><u>Unlock Full Wi-Fi Potential in Windows 11 with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-system-crafting-a-custom-uninstall-menu-for-win/"><u>Simplify Your System: Crafting a Custom Uninstall Menu for Win</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-harness-the-power-of-yt-green-screens-for-imaginative-projects/"><u>2024 Approved  Harness the Power of YT Green Screens for Imaginative Projects</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-vivo-x100-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Vivo X100 to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-printer-settings-in-windows-environment/"><u>Seamless Integration of Printer Settings in Windows Environment</u></a></li>
<li><a href="https://games-able.techidaily.com/cutting-edge-ddr5-gaming-boards-2024/"><u>Cutting-Edge DDR5 Gaming Boards 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-errors-fixing-loadlib-failure-87/"><u>Navigating Windows Errors: Fixing LoadLib Failure 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-eliminating-no-servers-found-in-apex-legends-(156-chars/"><u>Troubleshooting: Eliminating 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-operation-failure-in-windows-11-error-0x0000011b/"><u>Overcoming Operation Failure in Windows 11 (Error 0X0000011B)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-digital-life-winning-crypto-apps-ranked-150-chars/"><u>Secure Your Digital Life: Winning Crypto Apps Ranked (150 Chars)</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-discover-chilling-screech-impact/"><u>Updated In 2024, Discover Chilling Screech Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-how-to-reinstall-java-correctly/"><u>Unlocking Windows: How to Reinstall Java Correctly</u></a></li>
<li><a href="https://extra-tips.techidaily.com/audiences-favorites-top-10-mobility-friendly-players/"><u>Audience's Favorites  Top 10 Mobility-Friendly Players</u></a></li>
</ul></div>
