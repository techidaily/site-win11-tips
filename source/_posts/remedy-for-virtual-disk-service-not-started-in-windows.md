---
title: Remedy for Virtual Disk Service Not Started in Windows
date: 2024-07-12T17:36:13.485Z
updated: 2024-07-13T17:36:13.485Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for Virtual Disk Service Not Started in Windows
excerpt: This Article Describes Remedy for Virtual Disk Service Not Started in Windows
keywords: Windows Virtual DSC Startup,Virtual Disk Issue Windows,DVCS Services Failure Fix,Windows Disk Service Boot,Remedy Disk Service No Start,VDisk Service Not Functional,Resolve Windows Disk Errors
thumbnail: https://thmb.techidaily.com/d2f76001c4f2646491c0fc840a81d8218602e492050e0d16896d960da5c49a16.png
---

## Remedy for Virtual Disk Service Not Started in Windows

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://techidaily.com/how-to-exit-recovery-mode-on-apple-iphone-8-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-newbies-guide-to-easier-access/"><u>Windows Newbies' Guide to Easier Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-restarting-non-responsive-resource-monitors-in-windows-11/"><u>Strategies for Restarting Non-Responsive Resource Monitors in Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sky-sprints-guide-to-excellence-plus-ultimate-fpv-drones-for-speed/"><u>In 2024, Sky Sprints Guide to Excellence + Ultimate FPV Drones for Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-solutions-hiding-zips-within-computer-photos/"><u>Sneaky Storage Solutions: Hiding ZIPs Within Computer Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-file-explorer-freezes-in-win11-with-these-fixes/"><u>Stop File Explorer Freezes in Win11 With These Fixes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-meizu-21-pro-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Meizu 21 Pro to iPod | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circuit-breakers-fixes-to-power-up-your-photoshop/"><u>Circuit Breakers: Fixes to Power Up Your PhotoShop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-efficiency-expert-tips-for-optimizing-bar-use/"><u>Boosted Efficiency: Expert Tips for Optimizing Bar Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-audio-software-performance-on-windows-with-error-9999/"><u>Streamlining Audio Software Performance on Windows with Error 9999</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ipad-timelapse-essentials-for-beginners/"><u>[Updated] IPad Timelapse Essentials for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-mass-rename-with-powertoys/"><u>Automate Mass Rename with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-tips-for-sticky-note-backup/"><u>The Essential Tips for Sticky Note Backup</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-ultimate-showdown-adobe-premiere-vs-after-effects-for-video-creators/"><u>New 2024 Approved The Ultimate Showdown Adobe Premiere vs After Effects for Video Creators</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-poco-x5-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Poco X5 Phone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-the-significance-of-analytics-in-youtube-rank-enhancement/"><u>[Updated] 2024 Approved  The Significance of Analytics in YouTube Rank Enhancement</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-magic-behind-the-lens-iphone-xs-groundbreayer-camera-tech/"><u>In 2024, The Magic Behind the Lens  IPhone X's Groundbreayer Camera Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-games-again-steams-achievement-reboot/"><u>Unlocking Games Again: Steam's Achievement Reboot</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-hitching-a-ride-in-high-flying-tiktok-live-shows-for-2024/"><u>[Updated] Hitching a Ride in High-Flying TikTok Live Shows for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-simple-swift-and-superior-voice-tweaks-for-pubg-players/"><u>[New] Simple, Swift, and Superior Voice Tweaks for PUBG Players</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-little-wheelmens-game-festivals/"><u>In 2024, Little Wheelmen's Game Festivals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-memory-limitation-indicators-on-windowsvmware-systems/"><u>Correcting Memory Limitation Indicators on Windows/VMware Systems</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-apple-iphone-14-by-name-drfone-by-drfone-virtual-ios/"><u>4 Most-Known Ways to Find Someone on Tinder For Apple iPhone 14 by Name | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-synchronizing-airwaves-for-audience-gain/"><u>2024 Approved  Synchronizing Airwaves for Audience Gain</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-essential-steps-in-logging-youtube-live-content/"><u>[New] 2024 Approved  Essential Steps in Logging YouTube Live Content</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-enhancing-visual-focus-techniques-to-remove-unwanted-audio-elements-from-videos-in-desktop-settings-and-online-media-for-2024/"><u>New Enhancing Visual Focus Techniques to Remove Unwanted Audio Elements From Videos in Desktop Settings and Online Media for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-to-youtube-comment-sections-swiftly/"><u>In 2024, Navigating to YouTube Comment Sections Swiftly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigning-fast-the-quintessential-wins-performance-aids/"><u>Reigning Fast: The Quintessential Win's Performance Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-email-setup-connecting-your-gmail-to-outlook-windows/"><u>Simplifying Email Setup: Connecting Your Gmail to Outlook Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-vimeo-profits-unleashed-strategies-for-creative-entrepreneurs/"><u>[Updated] 2024 Approved  Vimeo Profits Unleashed  Strategies for Creative Entrepreneurs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-effect-of-eliminating-windows-11-taskbar-chat-on-you/"><u>Understanding the Effect of Eliminating Windows 11 Taskbar Chat on You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-manual-for-chrome-and-windows-11/"><u>The Ultimate Manual for Chrome and Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-vivo-y100a-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Vivo Y100A Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-chromes-firewallantivirus-denial-error-on-pc/"><u>Resolving Chrome's Firewall/Antivirus Denial Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-resource-tracking-efficiency-via-windows-interfaces/"><u>Upgrade Resource Tracking Efficiency via Window's Interfaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-elusive-link-finding-missing-launcher/"><u>Re-Establishing Elusive Link: Finding Missing Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivate-your-windows-11-explore-with-ease/"><u>Reactivate Your Windows 11 Explore with Ease</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-boost-traffic-elevate-rankings-essential-youtube-seo/"><u>[New] 2024 Approved  Boost Traffic, Elevate Rankings - Essential YouTube SEO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-audio-device-isolation-explained/"><u>Windows Audio Device Isolation Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-error-unsigned-update-files-fix-guide/"><u>Windows Error: Unsigned Update Files; Fix Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-call-recorder-iphone-captures-all-calls/"><u>In 2024, Call Recorder  IPhone Captures All Calls</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-top-rated-free-vob-video-editing-tools/"><u>2024 Approved Top-Rated Free VOB Video Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mechanism-disabling-dim-display-option/"><u>Unveiling the Mechanism: Disabling 'Dim Display' Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resetting-graphics-drivers-on-latest-oses/"><u>Quick Guide to Resetting Graphics Drivers on Latest OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719336383556-mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-w11w10s-refusal-to-open-folders-after-double-clicks/"><u>Resolving W11/W10's Refusal to Open Folders After Double-Clicks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-enhancing-video-success-top-8-yt-thumbnail-strategies-for-2024/"><u>[Updated] Enhancing Video Success  Top 8 YT Thumbnail Strategies for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-smartest-podcast-renaming-options-through-ai-technology/"><u>2024 Approved  The Smartest Podcast Renaming Options Through AI Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-updater-error-code-0xca00a009/"><u>Addressing Windows Updater Error Code: 0XCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reintroducing-versatility-beyond-win-1110s-s-mode/"><u>Reintroducing Versatility Beyond Win 11/10'S S Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-keys-to-a-cleaner-windows-experience/"><u>Three Keys to a Cleaner Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-server-execution-failed-in-wmp/"><u>Unraveling 'Server Execution Failed' In WMP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-pc-vram-with-windows-1011-tips-and-tricks/"><u>Turbocharging PC VRAM with Windows 10/11 Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-cr2-conversion-to-jpg-in-windows-environment/"><u>Streamline CR2 Conversion to JPG in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-browser-security-with-trusted-site-listing/"><u>Upgrade Browser Security with Trusted Site Listing</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-blueprint-of-crafting-digital-collaboration-spheres/"><u>[Updated] The Blueprint of Crafting Digital Collaboration Spheres</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-connect-quest-reestablish-your-screens-signal/"><u>Quick-Connect Quest: Reestablish Your Screen's Signal</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-premium-console-emulation-choosing-the-top-5-for-windows/"><u>2024 Approved  Premium Console Emulation  Choosing the Top 5 for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-fixes-conquer-the-windows-update-hurdles/"><u>7 Essential Fixes: Conquer the Windows Update Hurdles</u></a></li>
</ul></div>
