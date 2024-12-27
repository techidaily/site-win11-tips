---
title: Disabling Accelerated GPU Task Execution in Windows Operating System
date: 2024-12-20T19:28:15.795Z
updated: 2024-12-27T17:19:07.128Z
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

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-video-capture.techidaily.com/new-postmycam-seeking-top-notch-alternatives/"><u>[New] PostMyCam Seeking Top-Notch Alternatives</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-compre-habits-of-top-reddit-posters-explained/"><u>2024 Approved The Compre Habits of Top Reddit Posters Explained</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210410214-9780760368763-ayurveda-for-life/"><u>Ayurveda for Life | Free Book</u></a></li>
<li><a href="https://win-blog.techidaily.com/gratis-online-m4a-to-flac-omzetten-professioneel-en-gemakkelijk-met-movavi-audioshare/"><u>Gratis Online M4A-to-FLAC Omzetten - Professioneel en Gemakkelijk Met Movavi Audioshare</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-interventions-nine-fixes-to-stop-wwe-crashes/"><u>Immediate Interventions: Nine Fixes to Stop WWE Crashes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-elite-5-non-twitter-channels-online/"><u>In 2024, Elite 5 Non-Twitter Channels Online</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-system-prerequisites-for-running-big-sur-on-macs/"><u>In 2024, System Prerequisites for Running Big Sur on Macs</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-the-ultimate-checklist-for-selecting-prime-streaming-services-of-cricket/"><u>In 2024, The Ultimate Checklist for Selecting Prime Streaming Services of Cricket</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-to-leverage-copymove-the-win-11-guide-for-efficiency/"><u>Learn to Leverage Copy/Move: The Win 11 Guide for Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-hardware-detection-alerts/"><u>Navigating Through Hardware Detection Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reduce-windows-surrounders-for-better-control/"><u>Reduce Windows Surrounders for Better Control</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/review-is-the-high-cost-worth-it-a-detailed-look-at-the-new-apple-studio-display-for-mac-users-zdnet-perspectives/"><u>Review: Is the High Cost Worth It? A Detailed Look at the New Apple Studio Display for Mac Users | ZDNet Perspectives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-share-failures-on-geforce/"><u>Strategies for Resolving Share Failures on GeForce</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-infinix-hot-40-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Infinix Hot 40</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unravel-word-mysteries-quickly-with-windows-11/"><u>Unravel Word Mysteries Quickly with Windows 11</u></a></li>
</ul></div>

