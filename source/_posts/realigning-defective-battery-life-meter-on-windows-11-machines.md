---
title: Realigning Defective Battery Life Meter on Windows 11 Machines
date: 2025-01-02T10:41:01.379Z
updated: 2025-01-06T03:30:00.176Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Realigning Defective Battery Life Meter on Windows 11 Machines
excerpt: This Article Describes Realigning Defective Battery Life Meter on Windows 11 Machines
keywords: Battery Lifemeter Windows 11 Fix,Realign Battery Meter Issue,Enhance Defective W11 Battery,Correct Battery Metric Errors,Resolve Power Meter Malfunction,Optimize W11 Battery Health,Improve Battery Life Detection
thumbnail: https://thmb.techidaily.com/517296fb76b2495d3ca7ac9af3e02d36cfd22dc3a1d76f74a4f77913c7df7881.jpg
---

## Realigning Defective Battery Life Meter on Windows 11 Machines

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-maximizing-video-quality-enabling-av1-on-youtube/"><u>[New] Maximizing Video Quality Enabling AV1 on YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-enhance-video-to-fit-instagrams-visual-taste/"><u>2024 Approved Enhance Video to Fit Instagram's Visual Taste</u></a></li>
<li><a href="https://win-unique.techidaily.com/6-effective-solutions-to-resolve-the-my-laptop-deletes-all-files-problem/"><u>6 Effective Solutions to Resolve the 'My Laptop Deletes All Files' Problem</u></a></li>
<li><a href="https://facebook.techidaily.com/dissecting-the-top-5-technological-missteps-of-recent-times/"><u>Dissecting the Top 5 Technological Missteps of Recent Times</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/early-launch-of-pixel-n-pro-unveiled-by-google-arriving-sooner-than-expected/"><u>Early Launch of Pixel N Pro Unveiled by Google, Arriving Sooner Than Expected!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-opengl-problems-code-3-and-windows-nvidia/"><u>Eradicating OpenGL Problems: Code 3 & Windows Nvidia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-explorer-crashes-in-win11-top-fix-tips-to-try/"><u>File Explorer Crashes in Win11: Top Fix Tips to Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-rdp-restore-visibility-and-color-to-your-windows-pc/"><u>Fixing RDP: Restore Visibility and Color to Your Window's PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-streaming-snags-determining-if-your-netflix-service-is-down/"><u>Fixing Streaming Snags: Determining if Your Netflix Service Is Down</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microphone-not-working-with-the-xbox-app-on-windows-10-and-11/"><u>How to Fix the Microphone Not Working With the Xbox App on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-minimize-programs-to-the-windows-system-tray-with-hotkeys/"><u>How to Minimize Programs to the Windows System Tray With Hotkeys</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-samsung-galaxy-s24-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Samsung Galaxy S24 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-terminal-in-quake-setting/"><u>Mastering Windows Terminal in Quake Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-with-commented-organization-in-explorer/"><u>Maximizing Efficiency with Commented Organization in Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win-10-closed-caption-challenges/"><u>Overcoming Win 10 Closed Caption Challenges</u></a></li>
<li><a href="https://win-blog.techidaily.com/preventing-game-crashes-proven-strategies-for-a-smoother-among-us-experience-updated-2/"><u>Preventing Game Crashes: Proven Strategies for a Smoother Among Us Experience (Updated 2</u></a></li>
<li><a href="https://games-able.techidaily.com/unleashing-the-web-slinger-a-ps5-mars-spiderman-2-strategy/"><u>Unleashing The Web Slinger: A PS5 Mar's Spiderman 2 Strategy</u></a></li>
</ul></div>

