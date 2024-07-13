---
title: Setting Up Hidden Time Display on Window's Bar
date: 2024-07-12T16:37:57.822Z
updated: 2024-07-13T16:37:57.822Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Up Hidden Time Display on Window's Bar
excerpt: This Article Describes Setting Up Hidden Time Display on Window's Bar
keywords: Hidden Time Show Windows,Discreet Clock Bar,Stealthy Timeline Display,Secretive Status Timer,Concealed Window Clock,Obscured Bar Monitor,Unseen Clock Indicator
thumbnail: https://thmb.techidaily.com/20c69587162d153f03eefa64dab5fb5356740a9d42978b0299a0a4d322290d05.jpeg
---

## Setting Up Hidden Time Display on Window's Bar

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://video-capture.techidaily.com/investigating-the-top-10-cost-effective-video-collaboration-tools-in-corporateedu-settings-for-2024/"><u>Investigating the Top 10 Cost-Effective Video Collaboration Tools in Corporate/Edu Settings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-combination-of-files-in-windows-1011/"><u>Seamless Combination of Files in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-most-reliable-brightness-tools-for-windows-multi-display-users/"><u>The 6 Most Reliable Brightness Tools For Windows Multi-Display Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-to-windows-birthplace-points/"><u>Trailblazing to Windows' Birthplace Points</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/free-10-best-online-music-makers-for-2024/"><u>FREE 10 Best Online Music Makers for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/sustained-sky-exploration-the-best-drones-for-distance/"><u>Sustained Sky Exploration  The Best Drones for Distance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-synapse-functionality-with-razer-devices-on-windows/"><u>Restoring Synapse Functionality with Razer Devices on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-permission-errors-a-step-by-step-guide-on-windows/"><u>Resolving Permission Errors: A Step-by-Step Guide on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-changing-app-size-using-pc-keys-on-windows-11/"><u>Tips for Changing App Size Using PC Keys on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boost-creativity-with-free-unique-slideshow-templates-for-inspiration/"><u>Boost Creativity with Free, Unique Slideshow Templates for Inspiration</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/exploring-hololens-by-microsoft-a-3d-dream-come-true/"><u>Exploring HoloLens by Microsoft  A 3D Dream Come True</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-mastering-zoom-video-quality-a-step-by-step-guide/"><u>[New] In 2024, Mastering Zoom Video Quality  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-11s-default-touch-panel-settings-and-positioning/"><u>Restoring Windows 11'S Default Touch Panel Settings & Positioning</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-explore-the-best-0-image-editing-tools-on-smartphones-today/"><u>[New] Explore the Best $0 Image Editing Tools on Smartphones Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-restoration-techniques-to-reactivate-virus-protection-in-windows/"><u>Quick Restoration Techniques to Reactivate Virus Protection in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-errors-in-win1011-0x8007045d/"><u>Solving Common Errors in Win10/11 - 0X8007045D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-intelligent-assistant-protocol-on-windows/"><u>Stopping Intelligent Assistant Protocol on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-infinix-gt-10-pro-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Infinix GT 10 Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-audio-tracking-on-windows-powered-screencasts/"><u>Strategies for Audio Tracking on Windows-Powered Screencasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tech-companion-asus-vivobook-s-15-review/"><u>The Ultimate Tech Companion: Asus Vivobook S 15 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-top-5-grievances-from-windows-11-users/"><u>Unveiling the Top 5 Grievances From Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-xbox-game-pass-error-0x000-on-windows-11-systems/"><u>Understanding and Correcting Xbox Game Pass Error 0X000_ on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-battery-alert-strategies-for-win-users/"><u>Proactive Battery Alert Strategies for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-cyber-voyage-checking-stable-connections-on-pc/"><u>Securing Your Cyber Voyage: Checking Stable Connections on PC</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/unlock-the-power-of-mp3-conversion-why-you-need-to-read-this-article-for-2024/"><u>Unlock the Power of Mp3 Conversion Why You Need to Read This Article for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lowering-cpu-intensity-in-gaming-windows/"><u>Solutions for Lowering CPU Intensity in Gaming Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-maximize-impact-priority-list-of-highlight-tweaks/"><u>In 2024, Maximize Impact  Priority List of Highlight Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-backup-routine-for-nvidia-panel-configurations/"><u>Re-Establishing Backup Routine for Nvidia Panel Configurations</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-simple-guide-to-effective-and-smooth-iphone-screen-recordings/"><u>[New] In 2024, Simple Guide to Effective & Smooth Iphone Screen Recordings</u></a></li>
<li><a href="https://extra-information.techidaily.com/effortless-image-blur-for-iphones-top-4-methods-revealed/"><u>Effortless Image Blur for iPhones  Top 4 Methods Revealed</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotting-large-files-and-drives-in-windows-storage-soup/"><u>Spotting Large Files & Drives in Windows Storage Soup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-workflow-programmatic-shortcuts-in-winos/"><u>Streamline Workflow: Programmatic Shortcuts in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unanticipated-error-messages-in-wins-secure/"><u>Tackling Unanticipated Error Messages in WINS Secure</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-soundcloud-to-mp3-conversion-made-easy-top-tips-and-tricks-for-2024/"><u>Updated Soundcloud to MP3 Conversion Made Easy Top Tips and Tricks for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-key-tips-to-capture-youtube-streams-effectively-for-2024/"><u>[New] Key Tips to Capture YouTube Streams Effectively for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-discord-installer-errors-on-windows-devices/"><u>Resolving Discord Installer Errors on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhindered-wi-fi-on-your-desktop-9-strategies-for-win11-users/"><u>Unhindered Wi-Fi on Your Desktop: 9 Strategies for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-path-upgrading-your-vm-software-from-virtualbox-v6-to-v7-in-win11/"><u>Step-by-Step Path: Upgrading Your VM Software From VirtualBox v6 to v7 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-your-schedule-how-to-reset-windows-time-service/"><u>Sync Your Schedule: How to Reset Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-setup-a-closer-look/"><u>Windows 11 Setup: A Closer Look</u></a></li>
</ul></div>
