---
title: Resetting Run History Loss Issue
date: 2024-09-12T00:01:14.839Z
updated: 2024-09-16T20:24:31.524Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Run History Loss Issue
excerpt: This Article Describes Resetting Run History Loss Issue
keywords: Fix Run History Loss,Reset Tracking Errors,Clear Run Data Issues,Run History Recovery,Address Running Gaps,Restore Run Logs,Solve Run History Problems
thumbnail: https://thmb.techidaily.com/f8f467b332b89dbb4d8c51eef116fbbce4476e735f93f6027b47c78945bb4e75.jpg
---

## Resetting Run History Loss Issue

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115942/19272" target="_top" id="2115942">
  <img src="//a.impactradius-go.com/display-ad/19272-2115942" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115942/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-clip-curator-platform/"><u>[New] 2024 Approved Clip Curator Platform</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-thinkers-playground-top-10-mind-bending-rooms/"><u>[New] 2024 Approved Thinkers' Playground Top 10 Mind-Bending Rooms</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-audiovisual-synergy-infusing-music-into-vimeo-creations-for-2024/"><u>[New] Audiovisual Synergy Infusing Music Into Vimeo Creations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-package-fail-message-a-windows-10-11-solution-guide/"><u>Decoding the 'Package Fail' Message: A Windows 10, 11 Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-android-software-for-windows-desktop-owners/"><u>Essential Android Software for Windows Desktop Owners</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-dead-iphone-14-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to recover data from dead iPhone 14 | Stellar</u></a></li>
<li><a href="https://win-blog.techidaily.com/iphone-unrecognized-by-itunes-on-your-windows-10-machine-how-to-resolve-it/"><u>IPhone Unrecognized by iTunes on Your Windows 10 Machine - How to Resolve It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revisiting-past-times-altering-windows-file-timestamps/"><u>Revisiting Past Times: Altering Windows File Timestamps</u></a></li>
<li><a href="https://driver-install.techidaily.com/sync-drivers-windows-and-hp-printer-jetpro400-compatibility/"><u>Sync Drivers: Windows and HP Printer JetPro400 Compatibility</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/tips-for-crafting-an-engaging-fb-timeline-memory/"><u>Tips for Crafting an Engaging FB Timeline Memory</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    