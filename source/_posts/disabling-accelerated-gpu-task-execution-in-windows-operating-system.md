---
title: Disabling Accelerated GPU Task Execution in Windows Operating System
date: 2025-01-29T15:33:05.917Z
updated: 2025-02-01T14:50:50.999Z
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

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-how-to-make-vimeo-videos/"><u>[Updated] 2024 Approved How to Make Vimeo Videos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-diverse-designs-at-your-fingertips-from-these-6-websites/"><u>[Updated] In 2024, Diverse Designs at Your Fingertips From These 6 Websites</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-best-subtitle-converters-reviewed-the-top-8-win-osx-sbt-to-srts-software/"><u>2024 Approved Best Subtitle Converters Reviewed The Top 8 Win-OSX SBT to SRTS Software</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-direct-link-between-spotify-and-youtube-the-top-tools-for-music-sharing/"><u>2024 Approved Direct Link Between Spotify and YouTube The Top Tools for Music Sharing</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-step-by-step-guide-to-elevating-video-presence-through-thumbnails/"><u>2024 Approved Step-by-Step Guide to Elevating Video Presence Through Thumbnails</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/apples-m1-processor-showdown-m1-pro-versus-m1-max-differences-for-2024/"><u>Apple’s M1 Processor Showdown M1 Pro versus M1 Max Differences for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-character-mapping-errors-on-windows/"><u>Decoding and Correcting Character Mapping Errors on Windows</u></a></li>
<li><a href="https://article-files.techidaily.com/free-webm-viewers-the-ultimate-comparison-of-options-for-2024/"><u>Free WebM Viewers The Ultimate Comparison of Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-clipboard-functionality-within-microsoft-written-assurance-mode-windows-11/"><u>How to Configure Clipboard Functionality Within Microsoft' Written Assurance Mode, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-no-available-display-options-on-pc/"><u>How to Correct No Available Display Options on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-camera-unavailable-issue-on-windows-11/"><u>How to Solve Camera Unavailable Issue on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-zte-axon-40-lite-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from ZTE Axon 40 Lite to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-realme-12plus-5g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Realme 12+ 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-maze-of-typical-anydesk-issues-on-windows/"><u>Navigating Through the Maze of Typical AnyDesk Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnect-your-printer-to-regain-printing-power/"><u>Reconnect Your Printer to Regain Printing Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-incessant-pause-windows-errors/"><u>Remedy for Incessant Pause Windows Errors</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/story-1-the-misunderstanding-of-dupuytrens-contracture/"><u>Story 1: The Misunderstanding of Dupuytren's Contracture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-executing-clean-boots-on-windows-11/"><u>Understanding and Executing Clean Boots on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-status-audit-top-3-strategies/"><u>Windows 11 Status Audit: Top 3 Strategies</u></a></li>
</ul></div>

