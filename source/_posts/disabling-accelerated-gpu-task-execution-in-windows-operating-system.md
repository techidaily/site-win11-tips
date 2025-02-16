---
title: Disabling Accelerated GPU Task Execution in Windows Operating System
date: 2025-02-09T16:04:06.406Z
updated: 2025-02-16T02:12:35.904Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Accelerated GPU Task Execution in Windows Operating System
excerpt: This Article Describes Disabling Accelerated GPU Task Execution in Windows Operating System
keywords: Disable GPU Acceleration,Stop GPU Tasks,End Windows GPU Process,Windows GPU Execution Halt,Cease GPU Operation (Win OS),Turn Off GPU Tasking (Windows),Inhibit GPU Activity in Win OS
thumbnail: https://thmb.techidaily.com/4c64599e932018a17c352685488bbe982ee82f5fc1c73b73894ec43a1b1c5c03.jpg
---

## Disabling Accelerated GPU Task Execution in Windows Operating System

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disable Hardware Accelerated GPU Scheduling Through Windows Settings

 The easiest way to disable the Hardware Accelerated GPU Scheduling feature is through Windows Settings. Here’s how you can do it on a Windows 11 computer:

1. Press **Win + I** to bring up the Settings menu.
2. Go to **System > Display**.
3. From the **Related settings** list, click on **Graphics**.
4. Click **Change default graphics settings**.
5. At the top of the page, turn off the toggle for **Hardware-accelerated GPU scheduling**.
6. Reboot your system.

![The Optimizations for windowed games setting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/optimizations-for-windowed-games-setting.jpg)

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disable Hardware Accelerated GPU Scheduling Through Windows Registry

 If your graphics driver is outdated or corrupted, the hardware accelerated feature might be missing from the Settings menu. If you don’t have the time to replace or [update the graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) right now, you can still disable hardware-accelerated GPU scheduling through Windows Registry.

1. Press **Win + R** to bring up a Run dialog.
2. Type **regedit** and press **Enter**.
3. In the Registry Editor window, head to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > GraphicsDrivers**.
4. In the right pane, open the **HwSchMode** value.
5. Set **Value data** to **1**.
6. Click **OK** and restart your computer.

![How to disable hardware accelerated GPU scheduling through Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/registry-acc-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-premium-panzoid-structure-packs/"><u>[New] Premium Panzoid Structure Packs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-transforming-gameplay-discovering-the-seven-stars-of-stardew-updates/"><u>[Updated] 2024 Approved Transforming Gameplay Discovering the Seven Stars of Stardew Updates</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comparing-wav-and-mp3-files-a-comprehensive-guide-on-whats-best-for-you/"><u>Comparing WAV and MP3 Files - A Comprehensive Guide on What's Best for You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-to-uninstall-printers-in-win11/"><u>Effective Techniques to Uninstall Printers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-paste-errors-in-windows-11-software/"><u>Eliminating Paste Errors in Windows 11 Software</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-xs-max-to-ipad-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone XS Max to iPad? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-solving-a-driverirqlnotlessorequal-error/"><u>Mastering the Art of Solving 'A DRIVER_IRQL_NOT_LESS_OR_EQUAL' Error</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-top-rated-mts-video-editors-expert-reviews-for-2024/"><u>New Top-Rated MTS Video Editors Expert Reviews for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016860083-reactivate-voice-chat-in-fortnite-expert-advice-and-easy-steps/"><u>Reactivate Voice Chat in Fortnite - Expert Advice & Easy Steps!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-path-failure-in-win10/"><u>Steps to Rectify PATH Failure in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-conflicts-start-peace-opt-for-one-antivirus-in-windows/"><u>Stop Conflicts, Start Peace: Opt for One Antivirus in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-windows-update-notifications/"><u>Stopping Windows Update Notifications</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-strategy-guide-to-digital-video-enhancement/"><u>The Ultimate Strategy Guide to Digital Video Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-drive-space-management-the-art-of-utilizing-windows-diskusage-commands/"><u>Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unleashing-potential-professional-tips-to-transform-your-social-media-presence/"><u>Unleashing Potential Professional Tips to Transform Your Social Media Presence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-potential-file-type-changes/"><u>Unlocking Windows' Potential: File Type Changes</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-most-essential-free-comedy-tunes-a-selection-for-online-content-creators/"><u>Updated Most Essential Free Comedy Tunes A Selection for Online Content Creators</u></a></li>
</ul></div>

