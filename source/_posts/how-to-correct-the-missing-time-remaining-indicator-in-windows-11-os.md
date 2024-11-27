---
title: How to Correct the Missing Time Remaining Indicator in Windows 11 OS
date: 2024-11-21T16:00:19.155Z
updated: 2024-11-27T17:26:19.928Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct the Missing Time Remaining Indicator in Windows 11 OS
excerpt: This Article Describes How to Correct the Missing Time Remaining Indicator in Windows 11 OS
keywords: Fix Missing Time Reminder,Windows 11 Time Alert Fix,Correct Time Display Issue,Time Indicator Reset in Win11,Update Time Feature Win11,Remaining Time Monitor Setup,Fix Time Reminder Indicator
thumbnail: https://thmb.techidaily.com/fd844f53885e2c32c9ef30bfaf7233832cc28d58125ca084d49daf8878117921.png
---

## How to Correct the Missing Time Remaining Indicator in Windows 11 OS

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-beat-the-hype-30-tiktok-inspired-deals-at-amazon/"><u>[New] 2024 Approved Beat the Hype - 30 TikTok-Inspired Deals at Amazon</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-melodies-meet-graphics-adding-soundtracks-to-powerpoint/"><u>[New] Melodies Meet Graphics Adding Soundtracks to PowerPoint</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-streamline-your-vlog-with-video-length-optimization/"><u>[Updated] 2024 Approved Streamline Your Vlog with Video Length Optimization</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-swift-capture-full-spectrum-viewing/"><u>[Updated] 2024 Approved Swift Capture Full Spectrum Viewing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-art-and-science-of-compelling-headlines/"><u>2024 Approved The Art & Science of Compelling Headlines</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/bridge-your-computer-and-television-casting-windows-to-a-smart-tv-via-chromecast/"><u>Bridge Your Computer and Television: Casting Windows to a Smart TV via Chromecast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-discord-fatal-javascript-error-in-windows-10-and-11/"><u>How to Fix the Discord Fatal Javascript Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-windows-update-error-0x8024800c/"><u>Mitigating Windows Update Error 0X8024800C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritizing-safety-with-top-10-free-software-choices/"><u>Prioritizing Safety with Top 10 Free Software Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-team-video-sharing-glitches/"><u>Reclaim Team Video Sharing Glitches</u></a></li>
<li><a href="https://data-wizards.techidaily.com/rescuing-ailing-digital-film-formats-on-mac-computers/"><u>Rescuing Ailing Digital Film Formats on Mac Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/searching-for-browser-with-lowest-resource-footprint-on-multiple-oses/"><u>Searching for Browser with Lowest Resource Footprint on Multiple OSes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlock-creative-potential-smart-b-roll-incorporation/"><u>Unlock Creative Potential Smart B Roll Incorporation</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-best-toolbox-to-translate-youtube-videos-to-english-subtitles-for-2024/"><u>Updated Best Toolbox to Translate YouTube Videos to English Subtitles for 2024</u></a></li>
</ul></div>

