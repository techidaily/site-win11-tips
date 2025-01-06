---
title: Disabling Accelerated GPU Task Execution in Windows Operating System
date: 2025-01-05T03:16:39.626Z
updated: 2025-01-06T05:25:18.200Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-crafting-powerful-video-titles-and-sizes/"><u>[New] 2024 Approved Crafting Powerful Video Titles & Sizes</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-reno-8t-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo Reno 8T 5G</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/effective-strategies-for-avoiding-windows-memory-malfunctions-tips-from-yl-software-experts/"><u>Effective Strategies for Avoiding Windows Memory Malfunctions: Tips From YL Software Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-juggling-made-easy-automated-transfer-on-w11/"><u>File Juggling Made Easy: Automated Transfer on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-the-something-went-wrong-error-with-ios-photos/"><u>Fixes for the 'Something Went Wrong' Error with iOS Photos</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-oppo-a1-5g-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Oppo A1 5G Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-malwarebytes-runtime-error-could-not-call-proc-issue-in-windows-1110/"><u>How to Fix the Malwarebytes Runtime Error: Could Not Call Proc Issue in Windows 11/10</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-integrate-twitter-and-snapchat-posting-tweets-as-snaps/"><u>In 2024, Integrate Twitter & Snapchat Posting Tweets as Snaps</u></a></li>
<li><a href="https://techtrends.techidaily.com/install-handbrake-with-libdvdcss-on-windows-and-macos-catalinabig-sur-a-guide-for-legal-rip-and-convert-dvds/"><u>Install Handbrake with Libdvdcss on Windows & macOS Catalina/Big Sur: A Guide for Legal Rip and Convert DVDs</u></a></li>
<li><a href="https://facebook.techidaily.com/navigating-through-business-page-discontinuation-on-facebook/"><u>Navigating Through Business Page Discontinuation on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-power-of-connectedness-wp-galaxy-via-flow-app/"><u>The Power of Connectedness - WP-Galaxy via Flow App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-teams-screen-sharing-on-windows/"><u>Troubleshoot Teams Screen Sharing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-toolkit-keyboard-cars-for-optimal-tasks/"><u>Ultimate Toolkit: Keyboard Cars for Optimal Tasks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/windows-1011mp4wma/"><u>Windows 10/11でMP4ファイルをWMA形式に簡単に変換するガイド</u></a></li>
</ul></div>

