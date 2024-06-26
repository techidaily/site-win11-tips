---
title: How to Speed Up Epic Games Launcher Downloads on Windows
date: 2024-06-25T16:42:53.073Z
updated: 2024-06-26T16:42:53.073Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-user-profile-control-with-cmd/"><u>In-Depth Analysis of User Profile Control with CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/should-you-block-yourphoneexe-on-home-editions/"><u>Should You Block YourPhone.exe on Home Editions?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hazards-of-cheap-windows-key-purchases/"><u>Navigating the Hazards of Cheap Windows Key Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-net-core-not-installed-app-issue-in-windows/"><u>Overcoming .NET Core Not Installed App Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ifttt-and-microsoft-to-dot-synergy-explained/"><u>IFTTT & Microsoft To-Dot Synergy Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-overcapacity-alerts-for-gpt-service/"><u>Counteracting Overcapacity Alerts for GPT Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-online-gaming-prevent-lol-disconnections-in-windows/"><u>Secure Online Gaming: Prevent LoL Disconnections in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-troubleshooting-steps-for-internal-error-on-windows-1111-pro/"><u>Essential Troubleshooting Steps for Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-infinix-zero-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Infinix Zero 30 5G? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-mastering-the-art-of-filter-and-music-integration-in-windows-10-photos/"><u>[Updated] In 2024, Mastering the Art of Filter & Music Integration in Windows 10 Photos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/finding-purpose-in-film-our-selection-of-top-motivational-titles-for-2024/"><u>Finding Purpose in Film  Our Selection of Top Motivational Titles for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-premiere-cameras-to-document-the-next-wave-of-concert-videos/"><u>[Updated] Premiere Cameras to Document the Next Wave of Concert Videos</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-iphone-11-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your iPhone 11 and iPad</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-elevate-your-content-with-the-best-free-video-translator-apps-for-2024/"><u>Updated Elevate Your Content with the Best Free Video Translator Apps for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-guide-to-extracting-srt-from-a-zip-archive-for-2024/"><u>[New] Guide to Extracting SRT From a ZIP Archive for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-battle-for-asgard-the-ragnarok-chronicles/"><u>2024 Approved  Battle for Asgard  The Ragnarök Chronicles</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-the-ultimate-guide-to-open-source-screencasting-tools/"><u>[Updated] 2024 Approved  The Ultimate Guide to Open-Source Screencasting Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>