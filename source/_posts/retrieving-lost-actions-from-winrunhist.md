---
title: Retrieving Lost Actions From WinRunHist
date: 2024-06-25T16:10:51.277Z
updated: 2024-06-26T16:10:51.277Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Retrieving Lost Actions From WinRunHist
excerpt: This Article Describes Retrieving Lost Actions From WinRunHist
keywords: WinRunHist Recovery,Action Retrieval WinR-H,Restore WinRun Hist Actions,WinRunLostActions Fix,WinRunHistory Cleanup,WinRun Hist Errors Resolve,WinRunRestore Missing Actions
thumbnail: https://thmb.techidaily.com/09d90f71aa46b1fd9d4bcc7810bb203ff9683f8d93c042d20e109ab131454cc4.jpg
---

## Retrieving Lost Actions From WinRunHist

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/unleash-language-potential-with-windows-1011-hotkey-techniques/"><u>Unleash Language Potential with Windows 10/11 Hotkey Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-footage-excellence-with-these-best-apps-for-windows-11/"><u>Enhance Footage Excellence with These Best Apps for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-failed-cloud-operations-on-windows-devices/"><u>Solutions for Failed Cloud Operations on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-dark-theme-in-windows-calculator/"><u>Implementing Dark Theme in Windows Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-context-menu-quick-uninstall-in-win-1110/"><u>Mastering Context Menu: Quick Uninstall in Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-disk-space-safely-preserving-data-on-your-windows-11-local-drive-max-156-chars/"><u>Boost Your Disk Space Safely: Preserving Data on Your Windows 11 Local Drive (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-mouse-game-with-cross-border-powertoys-techniques/"><u>Elevate Your Mouse Game with Cross-Border PowerToys Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-split-display-frustrations-in-windows/"><u>Overcoming Split Display Frustrations in WIndows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-with-windows-11-safe-boot-tips/"><u>Troubleshoot With Windows 11 Safe Boot Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-variability-in-windows-protocols-for-cloud-and-local-reinstallation/"><u>Understanding Variability in Windows Protocols for Cloud and Local Reinstallation</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-the-ultimate-list-of-top-tier-digital-volume-enhancers-online/"><u>New In 2024, The Ultimate List of Top-Tier Digital Volume Enhancers Online</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-enhance-tv-broadcasts-with-seamless-video-loops-from-youtube/"><u>2024 Approved  Enhance TV Broadcasts with Seamless Video Loops From YouTube</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-techniques-to-silence-audio-streams-from-new-mkv-file-versions/"><u>New In 2024, Techniques to Silence Audio Streams From New MKV File Versions</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-scripting-stimulating-screen-grabbers/"><u>[New] Scripting Stimulating Screen-Grabbers</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-honor-x50-gt-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Honor X50 GT</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-transformation-tips-applying-japans-favorite-on-screen-effects/"><u>2024 Approved  Transformation Tips  Applying Japan's Favorite On-Screen Effects</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-free-avi-video-rotation-tools-top-picks-for-windows-mac-android-and-iphone/"><u>Updated Free AVI Video Rotation Tools Top Picks for Windows, MAC, Android, and iPhone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-videofetcher-download-from-social-sites-for-2024/"><u>[Updated] VideoFetcher  Download From Social Sites for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-obs-optimization-for-seamless-fb-broadcasting-for-2024/"><u>[Updated] OBS Optimization for Seamless FB Broadcasting for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>