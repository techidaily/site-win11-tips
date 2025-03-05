---
title: Disabling Accelerated GPU Task Execution in Windows Operating System
date: 2025-02-25T19:16:22.742Z
updated: 2025-03-04T21:43:48.944Z
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

### Disable Hardware Accelerated GPU Scheduling Through Windows Registry

 If your graphics driver is outdated or corrupted, the hardware accelerated feature might be missing from the Settings menu. If you don’t have the time to replace or [update the graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) right now, you can still disable hardware-accelerated GPU scheduling through Windows Registry.

1. Press **Win + R** to bring up a Run dialog.
2. Type **regedit** and press **Enter**.
3. In the Registry Editor window, head to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > GraphicsDrivers**.
4. In the right pane, open the **HwSchMode** value.
5. Set **Value data** to **1**.
6. Click **OK** and restart your computer.

![How to disable hardware accelerated GPU scheduling through Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/registry-acc-1.jpg)

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
<li><a href="https://article-files.techidaily.com/new-in-2024-revolutionary-guide-to-iphone-x-animoji-mastery/"><u>[New] In 2024, Revolutionary Guide to iPhone X Animoji Mastery</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-sky-dominance-top-5-fpv-glasses-for-pilots/"><u>[New] Sky Dominance Top 5 FPV Glasses for Pilots</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-fundamental-codex-for-online-video-communities/"><u>[Updated] Fundamental Codex for Online Video Communities</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-get-savvy-with-io-screener-a-primer/"><u>[Updated] Get Savvy with IO Screener A Primer</u></a></li>
<li><a href="https://fox-glue.techidaily.com/could-a-switch-to-macos-sonoma-benefit-my-workflow/"><u>Could a Switch to macOS Sonoma Benefit My Workflow?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-dim-aesthetic-in-power-options-menu/"><u>Enabling/Disabling Dim Aesthetic in Power Options Menu</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-becoming-a-pro-at-iphone-hdr-imaging/"><u>In 2024, Becoming a Pro at iPhone HDR Imaging</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/meet-your-pcs-eligibility-for-windows-11/"><u>Meet Your PC's Eligibility for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-halt-unlock-code-x80131500/"><u>Microsoft Store Halt: Unlock Code X80131500</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-maze-of-error-80080300-in-teams-w11-edition/"><u>Navigating Through the Maze of Error 80080300 in Teams W11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-prevent-desktop-icon-shrinkage/"><u>Win 11: Prevent Desktop Icon Shrinkage</u></a></li>
</ul></div>

