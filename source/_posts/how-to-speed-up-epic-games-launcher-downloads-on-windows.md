---
title: How to Speed Up Epic Games Launcher Downloads on Windows
date: 2024-07-12T17:12:03.034Z
updated: 2024-07-13T17:12:03.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Speed Up Epic Games Launcher Downloads on Windows
excerpt: This Article Describes How to Speed Up Epic Games Launcher Downloads on Windows
keywords: Win XP Launcher Speedup,Accelerate Launcher Download,Fasten Epic Games Loader,Boost Launcher Performance,Optimize Launcher Download,Quick Launcher Setup,Enhance Game Launch Time
thumbnail: https://thmb.techidaily.com/c3ba901f926249b24c063d003163e0cc5d148f0772ca21d903055c2189241e19.jpg
---

## How to Speed Up Epic Games Launcher Downloads on Windows

 Does the Epic Games Launcher take a long time to download games? In general, download speeds drop due to other devices or processes hogging network resources, leaving little bandwidth for the Epic Games client to use.

 Besides that, a piled-up launcher cache, a backend issue with Epic Games servers, some Windows-specific issues, or forcing the client to throttle downloads can also slow down download speeds.

 If you want to speed up your downloads on the Epic Games Launcher, here are a few tweaks you may want to check out.

## 1\. Check for Problems With the Backend

 It's possible to get super slow download speeds in Epic Games if there is a backend issue with the client or any other Epic Games service. Therefore, if your download speed has dropped unexpectedly, ensure all Epic Games servers and systems are up and running and the cause of the problem is not there.

 You can check that in several ways, but here's the easiest: go to [Epic Games' status page](https://status.epicgames.com/) and check if everything is up and running, shown as green. If any outages are listed there, represented by a red or yellow color, wait for Epic Games to resolve the backend problem, and the download speed will return to normal.

![All Systems Showing as Operational on the Epic Games Status Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/all-systems-showing-as-operational-on-the-epic-games-status-page.jpg)

 If all systems appear to function correctly, then there's nothing wrong with the backend. In that case, move on to the next fix.

## 2\. Basic Steps to Perform Before Optimizing the Epic Games Launcher

 Once you've confirmed that there are no backend issues impacting download speeds, take the following steps before optimizing the Epic Games Launcher:

* Slow or unstable internet connections can also slow down downloads. Therefore, [use speed checking websites to check the speed of your internet connection](https://www.makeuseof.com/best-free-websites-test-internet-speed/), and if it is slower than usual, take the necessary steps to speed it up.
* Close all processes on your primary device that could be straining your bandwidth resources, and disconnect other devices connected to the same internet connection. Consequently, the Epic Games Launcher will have access to the maximum bandwidth.
* Disable any VPN or proxy server you use to make your browsing more private. Such connections protect our privacy but can seriously slow the download process.

 After performing the above checks and fixes, move on to the main fixes.

## 3\. Disable Downloads Throttling

 The Epic Games client allows users to throttle downloads when playing games or using network resources for something more substantial. This handy setting prevents the launcher from overstressing your bandwidth during a game update or installation.

 When this option is enabled, the Epic Games Launcher will not let the download speed reach its maximum potential, which leads to slower download speeds. As such, you should ensure this feature is not enabled in the client's settings. To check that, follow these steps:

1. Launch the Epic Games Launcher.
2. Click the **profile icon** in the top right corner and select **Settings**.  
![Open Settings in the Epic Games Launcher](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/2-open-settings-in-the-epic-games-launcher.jpg)
3. Make sure that the box beside **Throttle Downloads** isn't checked.
4. If it was checked before, click the box once to uncheck it.  
![Disable the Throttle Downloads Option in the Epic Games Launcher Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/3-disable-the-throttle-downloads-option-in-the-epic-games-launcher-settings.jpg)

## 4\. Prioritize the Epic Games Launcher Over Everything Else

 The Windows operating system prioritizes essential system processes over third-party ones. Consequently, it allocates the most resources to prioritized processes to improve efficiency. As Epic Games processes are also third-party, they are also viewed as low priority. Hence fewer resources are allocated to them.

 To ensure that the system prioritization isn't slowing down the downloads, you should set the launcher's processes as high-priority. This way, the system will allocate maximum bandwidth resources to the Epic Games Launcher, allowing it to download files faster. To make Epic Games processes a priority, follow these steps:

1. Type **"Task Manager"** in Windows Search and open **Task Manager**.
2. Navigate to the **Details** tab of the Task Manager.
3. Locate the **EpicGamesLauncher.exe** process.
4. Right-click on this process, navigate to **Set Priority,** and select **High**.  
![Change the Priority of the Epic Games Launcher Process in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/4-change-the-priority-of-the-epic-games-launcher-process-in-task-manager.jpg)

## 5\. Clear Epic Games Launcher's Cache

 The Epic Games Launcher keeps some data in its cache, which makes it easier for the client to find and load necessary information faster. If not cleared timely, the accumulated cache can lead to unforeseen problems, including slow download speeds. Therefore, it is imperative to clear the cache, especially if it hasn't been cleared in a while.

 To delete the Epic Games Launcher's cache, follow these steps:

1. Press **Win+R**, type **"%appdata%"** and press **Enter**.
2. Navigate to **Local > EpicGamesLauncher > Saved** folders.
3. Delete each **webcache** folder you find.  
![Delete the Webcache Folder in the Epic Games Launcher Installation Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/5-delete-the-webcache-folder-in-the-epic-games-launcher-installation-folder.jpg)

## 6\. Reconfigure the Engine.ini File

 According to Reddit users and numerous YouTubers, modifying the Engine.ini file in the Epic Games installation folder can also make the download process faster. Follow these steps to reconfigure the file:

1. Press **Win+R**, type **"%appdata%"** and press **Enter**.
2. Navigate to **Local > EpicGamesLauncher > Saved > Config > Windows** folders.
3. Here, right-click the **Engine.ini** file and open it with Notepad or any other text editor.  
![Open the Engine.ini File in Notepad From the Epic Games Installation Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/6-open-the-engine-ini-file-in-notepad-from-the-epic-games-installation-folder.jpg)
4. Delete all the content in this file and add the following code instead:  
`[HTTP]  
HttpTimeout=10  
HttpConnectionTimeout=10  
HttpReceiveTimeout=10  
HttpSendTimeout=10  

[Portal.BuildPatch]  
ChunkDownloads=3  
ChunkRetries=20  
RetryTime=0.5`
5. Press **CTRL+S** to save the file. After that, close it.  
![Save the Engine.ini File After Adding Few Commands in It](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/7-save-the-engine-ini-file-after-adding-few-commands-in-it-1.jpg)
6. Restart the Epic Games Launcher again.

 If tweaking Engine.ini starts to adversely affect download speed, as some users have reported, you should revert the changes.

## 7\. Perform Some Windows-Specific Changes to Speed Up Downloads

 Here're a few Windows-specific changes that can speed up downloads in the Epic Games Launcher:

* Changing your DNS settings to Google's public DNS is well-known for boosting download speeds for most apps and clients. So, [switch your DNS server](https://www.makeuseof.com/tag/change-dns-increase-internet-speed/) and see whether the download speed improves.
* [Whitelist the Epic Games Launcher from Microsoft Defender](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) and any third-party antivirus you use. This will prevent security suites from restricting or limiting download activity in any way.

## Speed Up the Epic Games Launcher Downloads

 Waiting hours to install a game or update an existing one can ruin our day. Hopefully, the above steps will help you optimize the Epic Games Launcher and speed up downloads. If nothing works and downloads keep lagging, remove the existing launcher installation and reinstall it again from scratch.

 If your internet connection is slow, the above checks may not significantly increase download speed. If this is the case for you, switch to a different service provider or internet package.

 Besides that, a piled-up launcher cache, a backend issue with Epic Games servers, some Windows-specific issues, or forcing the client to throttle downloads can also slow down download speeds.

 If you want to speed up your downloads on the Epic Games Launcher, here are a few tweaks you may want to check out.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/trailblazing-to-windows-birthplace-points/"><u>Trailblazing to Windows' Birthplace Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-setup-a-closer-look/"><u>Windows 11 Setup: A Closer Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-transform-personal-experiences-through-direct-webcam-capture-using-vlc/"><u>[New] Transform Personal Experiences Through Direct Webcam Capture Using VLC</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-visionary-writing-spanning-eight-cinematic-divisions/"><u>2024 Approved  Visionary Writing Spanning Eight Cinematic Divisions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-errors-in-win1011-0x8007045d/"><u>Solving Common Errors in Win10/11 - 0X8007045D</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-dodging-the-invisible-block-unshade-your-tiktok-presence/"><u>[New] Dodging the Invisible Block  Unshade Your TikTok Presence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-changing-app-size-using-pc-keys-on-windows-11/"><u>Tips for Changing App Size Using PC Keys on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-your-schedule-how-to-reset-windows-time-service/"><u>Sync Your Schedule: How to Reset Windows Time Service</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-motorola-moto-g14-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Motorola Moto G14 Devices | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-xsplit-compendium-download-and-review-archive/"><u>[Updated] In 2024, XSplit Compendium  Download & Review Archive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-cyber-voyage-checking-stable-connections-on-pc/"><u>Securing Your Cyber Voyage: Checking Stable Connections on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-path-upgrading-your-vm-software-from-virtualbox-v6-to-v7-in-win11/"><u>Step-by-Step Path: Upgrading Your VM Software From VirtualBox v6 to v7 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unanticipated-error-messages-in-wins-secure/"><u>Tackling Unanticipated Error Messages in WINS Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-combination-of-files-in-windows-1011/"><u>Seamless Combination of Files in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-workflow-programmatic-shortcuts-in-winos/"><u>Streamline Workflow: Programmatic Shortcuts in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tech-companion-asus-vivobook-s-15-review/"><u>The Ultimate Tech Companion: Asus Vivobook S 15 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-xbox-game-pass-error-0x000-on-windows-11-systems/"><u>Understanding and Correcting Xbox Game Pass Error 0X000_ on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhindered-wi-fi-on-your-desktop-9-strategies-for-win11-users/"><u>Unhindered Wi-Fi on Your Desktop: 9 Strategies for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-top-5-grievances-from-windows-11-users/"><u>Unveiling the Top 5 Grievances From Windows 11 Users</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-your-starting-guide-to-tiktok-macos-basics/"><u>[New] 2024 Approved  Your Starting Guide to TikTok (macOS) Basics</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-tiktok-edits-unleashed-crafting-engaging-video-reactions-with-filmoras-pro-mode/"><u>In 2024, TikTok Edits Unleashed  Crafting Engaging Video Reactions with Filmora's Pro Mode</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-screener-solution-for-flawless-youtube-content-creation/"><u>In 2024, Top Screener Solution  For Flawless YouTube Content Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-most-reliable-brightness-tools-for-windows-multi-display-users/"><u>The 6 Most Reliable Brightness Tools For Windows Multi-Display Users</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-decoding-facebooks-algorithm-the-way-to-access-vids/"><u>[Updated] In 2024, Decoding Facebook's Algorithm  The Way to Access Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-step-by-step-guide-to-saving-google-meet-interactions/"><u>[Updated] Step-by-Step Guide to Saving Google Meet Interactions</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-step-by-step-process-for-extracting-rhythmic-grooves-from-tracks/"><u>Updated 2024 Approved Step-by-Step Process for Extracting Rhythmic Grooves From Tracks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-dailymotion-vs-youtube-monetization-which-is-more-profitable/"><u>[Updated] In 2024, Dailymotion vs YouTube Monetization  Which Is More Profitable?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/fastest-iphoneandroid-apps-for-enhanced-music/"><u>Fastest iPhone/Android Apps for Enhanced Music</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-audio-tracking-on-windows-powered-screencasts/"><u>Strategies for Audio Tracking on Windows-Powered Screencasts</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-biggest-buzz-stars-youtube-creators-with-highest-views/"><u>In 2024, The Biggest Buzz Stars  YouTube Creators with Highest Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lowering-cpu-intensity-in-gaming-windows/"><u>Solutions for Lowering CPU Intensity in Gaming Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotting-large-files-and-drives-in-windows-storage-soup/"><u>Spotting Large Files & Drives in Windows Storage Soup</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-melodic-freedom-fbs-music-library/"><u>[New] 2024 Approved  Melodic Freedom  FB's Music Library</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-melodic-mobile-alerts-download-classical-ringtones-here/"><u>[Updated] Melodic Mobile Alerts  Download Classical Ringtones Here</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/green-screen-mastery-seamless-yt-integration/"><u>Green Screen Mastery  Seamless YT Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-intelligent-assistant-protocol-on-windows/"><u>Stopping Intelligent Assistant Protocol on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Nubia Red Magic 8S Pro? | Dr.fone</u></a></li>
</ul></div>
