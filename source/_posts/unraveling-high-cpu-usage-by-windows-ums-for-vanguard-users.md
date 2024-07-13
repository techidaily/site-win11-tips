---
title: Unraveling High CPU Usage by Windows’ UMS for Vanguard Users
date: 2024-07-12T16:58:02.144Z
updated: 2024-07-13T16:58:02.144Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling High CPU Usage by Windows’ UMS for Vanguard Users
excerpt: This Article Describes Unraveling High CPU Usage by Windows’ UMS for Vanguard Users
keywords: UMS CPU Spikes,Windows CPU Overuse,Vanguard System Hurdles,High PC Utilization,Vanguard UMS Issue,Resource-Intensive Windows,Optimize UMS Usage
thumbnail: https://thmb.techidaily.com/2d67e14b0eb8d4077153a676b64f0ce1665316566b80f80c4fccfcd9a772edaa.jpg
---

## Unraveling High CPU Usage by Windows’ UMS for Vanguard Users

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
<li><a href="https://win11-tips.techidaily.com/simplifying-the-steps-msoffice-installation-on-windows-11/"><u>Simplifying the Steps: MSOffice Installation on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-system-operations-via-terminal-commands/"><u>Streamlining System Operations via Terminal Commands</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-immediate-silence-sudden-deletion-fears/"><u>[Updated] In 2024, Immediate Silence  Sudden Deletion Fears</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-managing-wins-ram-cache/"><u>Understanding and Managing Win's RAM Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-generation-inquiry-on-windows-8-efficient-approaches/"><u>CPU Generation Inquiry on Windows – 8 Efficient Approaches</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-music-files-from-oppo-a58-4g-by-fonelab-android-recover-music/"><u>How To  Restore Missing Music Files from Oppo A58 4G</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-sync-halt-on-microsoft-operating-systems/"><u>Assisting with uTorrent Sync Halt on Microsoft Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-keyspace-perfection-on-windows-11/"><u>Configuring Keyspace Perfection on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-best-digital-audio-amplifiers-the-ultimate-guide-to-loudness-boosting/"><u>In 2024, Best Digital Audio Amplifiers The Ultimate Guide to Loudness Boosting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-screen-organization-multi-window-mastery-with-win1110/"><u>Simplified Screen Organization: Multi-Window Mastery with Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-how-to-alter-file-extensions-on-windows/"><u>Step by Step: How to Alter File Extensions on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-power-of-placement-comments-in-windows-explorer/"><u>Unveiling the Power of Placement Comments in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-travelled-titles-tamed-the-power-of-retroarcs-visual-shapers/"><u>Time-Travelled Titles Tamed: The Power of RetroArc's Visual Shapers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-diablo-secrets-basic-techniques/"><u>Unlocking Diablo Secrets: Basic Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-windows-experience-with-customized-fn-keys-settings/"><u>Tailor Your Windows Experience with Customized FN Keys Settings</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-leading-speech-recording-software-for-mac-discovering-our-five-favorites/"><u>[Updated] Leading Speech Recording Software for Mac  Discovering Our Five Favorites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-user-adjustments-to-windows-screensaver/"><u>Avoiding User Adjustments to Windows Screensaver</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/leveraging-twitters-visual-content-on-snapchat/"><u>Leveraging Twitter's Visual Content on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-boot-efficiency-with-windows-11-programs/"><u>Boosting Boot Efficiency with Windows 11 Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-unresponsive-delete-button-issue-on-pcs/"><u>Solving Unresponsive Delete Button Issue on PCs</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-essential-directories-the-premier-10-sites-for-acquiring-montage-soundtracks/"><u>New Essential Directories The Premier 10 Sites for Acquiring Montage Soundtracks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-realme-gt-neo-5-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Realme GT Neo 5 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373707174-check-physical-connections-make-sure-cables-are-firmly-connected-if-you-have-external-monitors-or-projectors-with-separate-brightness-controls/"><u>Check Physical Connections: Make Sure Cables Are Firmly Connected if You Have External Monitors or Projectors with Separate Brightness Controls.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-11-integrity-through-activation-verification/"><u>Assessing Windows 11 Integrity Through Activation Verification</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-expert-tips-on-adding-yt-playlists-to-your-website-content/"><u>[New] Expert Tips on Adding YT Playlists to Your Website Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-life-to-your-calendar-the-windows-outlook-customization-journey/"><u>Bring Life to Your Calendar: The Windows Outlook Customization Journey</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-goovision-xtreme-cam-high-res-screen-capturer/"><u>In 2024, GooVision Xtreme Cam  High-Res Screen Capturer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compute-discerning-window-systems-origins/"><u>Compute: Discerning Window Systems' Origins</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Samsung Galaxy A15 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-straightforward-approach-to-discovering-ram-in-windows/"><u>A Straightforward Approach to Discovering RAM in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-revolutionize-your-talking-skills-with-these-no-cost-audio-modifications/"><u>2024 Approved  Revolutionize Your Talking Skills with These No-Cost Audio Modifications</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-vivo-y100a-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Vivo Y100A FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-windows-potential-get-the-outlook-preview-installed/"><u>Unveil Windows' Potential: Get the Outlook Preview Installed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-no-alert-settings-for-windows-11-cameras/"><u>Circumventing No-Alert Settings for Windows 11 Cameras</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-understanding-the-basics-of-motion-design/"><u>2024 Approved  Understanding the Basics of Motion Design</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-a-comprehensive-guide-to-online-podcast-recording/"><u>[Updated] 2024 Approved  A Comprehensive Guide to Online Podcast Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-device-names-candd-a-clear-breakdown/"><u>Dissecting Device Names (C&D): A Clear Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-ethernet-restoring-lost-internet-signal/"><u>Win Ethernet: Restoring Lost Internet Signal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windowsapps-get-inside/"><u>Demystifying WindowsApps: Get Inside</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-boosting-video-engagement-using-zooms-snap-feature-for-2024/"><u>[Updated] Boosting Video Engagement Using Zoom's Snap Feature for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodge-the-null-error-resolving-win11-problems/"><u>Dodge the Null Error: Resolving Win11 Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-process-chrome-windows-11-link-up/"><u>Unveiling the Process: Chrome, Windows 11 Link-Up</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-capturing-imagination-best-shot-tips/"><u>[New] The Art of Capturing Imagination  Best Shot Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-concepts-a-guide-to-obsidian-visualization/"><u>Captivating Concepts: A Guide to Obsidian Visualization</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-the-path-to-perfected-video-covers-update-guide-and-tips/"><u>[New] 2024 Approved  The Path to Perfected Video Covers  Update Guide & Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-11-remedy-six-steps-to-resurrect-lost-panes/"><u>The Ultimate Windows 11 Remedy: Six Steps to Resurrect Lost Panes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-a-dynamic-and-user-friendly-windows-interface/"><u>Create a Dynamic and User-Friendly Windows Interface</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Apple iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/social-media-spotlight-top-twitters-for-2024/"><u>Social Media Spotlight  Top Twitters for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-speeding-up-youtube-quick-video-rendering-and-transfer-tips/"><u>In 2024, Speeding Up YouTube  Quick Video Rendering & Transfer Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-core-variations-between-exe-and-msi-formats/"><u>Analyzing the Core Variations Between EXE and Msi Formats</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-mastering-video-spin-vlcs-rotation-guide/"><u>[Updated] Mastering Video Spin  VLC's Rotation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-stranded-xbox-on-win11-quick-troubleshooting-guide/"><u>Solving Stranded Xbox on Win11: Quick Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microphone-issues-live-recording-fixes-in-obs-w11/"><u>Troubleshooting Microphone Issues: Live Recording Fixes in OBS, W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-tech-game-with-these-top-7-windows-tips/"><u>Skyrocket Your Tech Game with These Top 7 Windows Tips</u></a></li>
</ul></div>
