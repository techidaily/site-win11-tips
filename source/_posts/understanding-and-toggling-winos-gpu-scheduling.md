---
title: Understanding & Toggling WinOS GPU Scheduling
date: 2024-10-23T18:22:10.252Z
updated: 2024-10-26T19:20:09.204Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding & Toggling WinOS GPU Scheduling
excerpt: This Article Describes Understanding & Toggling WinOS GPU Scheduling
keywords: GPU Scheduling OS,WinOS GPU Control,Graphics Scheduler Windows,Optimizing WinGPU,Toggle WinGPU Settings,Advanced Windows Scheduling,WinOS GPU Performance
thumbnail: https://thmb.techidaily.com/35db44591f3dcbc09fec63cf1897abe760727c167b28e2d4a0f6ad0bbea5b61b.jpg
---

## Understanding & Toggling WinOS GPU Scheduling

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

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105863/7443" target="_top" id="2105863">
  <img src="//a.impactradius-go.com/display-ad/7443-2105863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105863/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105866/7443" target="_top" id="2105866">
  <img src="//a.impactradius-go.com/display-ad/7443-2105866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-best-free-youtube-video-editing-apps-for-iphone-and-ipad-and-how-tos/"><u>[New] 2024 Approved Best Free YouTube Video Editing Apps for iPhone & iPad & How-Tos</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-advanced-ai-voice-to-text-apps/"><u>[Updated] In 2024, Advanced AI Voice to Text Apps</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-the-budget-friendly-filmmakers-dream-for-2024/"><u>[Updated] The Budget-Friendly Filmmaker's Dream for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/benq-sw320-monitor-review-a-leap-into-4k-territory/"><u>BenQ SW320 Monitor Review A Leap Into 4K Territory</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/clearing-up-confusion-a-guide-to-understanding-youtube-strikes-for-2024/"><u>Clearing Up Confusion A Guide to Understanding YouTube Strikes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-perfect-windows-sandbox-experience-in-11/"><u>Configuring the Perfect Windows Sandbox Experience in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-11-effective-methods-to-overcome-windows-11-bluescreen/"><u>Dive Into 11 Effective Methods to Overcome Windows 11 Bluescreen</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-vivo-y78plus-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Vivo Y78+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-off-spotify-playback-at-os-boot/"><u>How To Turn Off Spotify Playback at OS Boot</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-se-2022-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone SE (2022) without iTunes? | Dr.fone</u></a></li>
<li><a href="https://win-info.techidaily.com/is-using-the-migration-assistant-feasible-on-windows-11-exploring-alternatives/"><u>Is Using the Migration Assistant Feasible on Windows 11? Exploring Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mac-identification-on-windows-11-platform/"><u>Mastering MAC Identification on Windows 11 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-adjusting-reset-account-lockout-post-failed-logins-win-11/"><u>Mastering the Art of Adjusting Reset Account Lockout Post Failed Logins, Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-window-11-search-top-5-must-have-tips/"><u>Maximize Your Window 11 Search: Top 5 Must-Have Tips</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/respecting-copyrights-when-converting-youtube-to-mp4-for-2024/"><u>Respecting Copyrights When Converting YouTube to MP4 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-pc-with-a-tailored-lock-pattern-on-windows-11/"><u>Secure Your PC with a Tailored Lock Pattern on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-virtual-achievements-epic-save-strategies/"><u>Securing Your Virtual Achievements: Epic Save Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-graphics-performance-in-windows-11-pcs/"><u>Tailor Graphics Performance in Windows 11 PCs</u></a></li>
<li><a href="https://win-popular.techidaily.com/windows-11-uefi/"><u>Windows 11 UEFI選項不存在？詳細解析設定中的暗藏問題</u></a></li>
</ul></div>

