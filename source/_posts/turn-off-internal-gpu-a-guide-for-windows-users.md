---
title: "Turn Off Internal GPU: A Guide for Windows Users"
date: 2024-12-26T22:29:04.467Z
updated: 2024-12-27T17:09:39.290Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Turn Off Internal GPU: A Guide for Windows Users"
excerpt: "This Article Describes Turn Off Internal GPU: A Guide for Windows Users"
keywords: Disable Windows GPU,Turn Off CPU Graphics,Stop Internal Graphics,Quit Windows GPU,End GPU in WinOS,Deactivate GPU Windows,GPU Offset Guide Win
thumbnail: https://thmb.techidaily.com/88d3ccdcb9182fe6ab85d78619b5ff79c9f842144c7f0589af82188a3ec75add.jpg
---

## Turn Off Internal GPU: A Guide for Windows Users

 Your Windows computer probably has integrated graphics, especially if it's a laptop. The problem with this type of GPU, which is built into the motherboard, is that it's usually less powerful than a dedicated GPU. So, if you have a dedicated GPU, which is usually more powerful, it makes sense that you might want it to take over the graphical performance of your computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Check If You Have A Dedicated GPU

 Before you disable your integrated GPU (iGPU), you need to verify that your computer has a dedicated GPU installed and that it's working properly. To do that, right-click an empty part of the Taskbar and select **Task Manager**.

![Task Manager Option in the Taskbar Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Task-Manager-Option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Task Manager, select the **Performance** tab on the left and look at the number of GPUs available for your PC on the right. If there is more than one, then the other one is the dedicated GPU. In our case, **GPU 1** is the dedicated GPU, and if we click on it and scroll to the bottom, we can see that it says **Dedicated GPU Memory** in the rightmost panel.

![the Performace tab of Task Manager with the dedicated GPU selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/performace-tab-of-task-manager-with-gpu-selected-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you confirm you have an extra GPU on your computer, you can disable the iGPU.

## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Use Your Dedicated Graphics Card When You Need It

 All in all, you're better off using your dedicated graphics card, especially if you are into graphically demanding applications. But if your computer doesn't have a dedicated GPU, disabling integrated graphics is not an option. The decision depends on what you're ultimately trying to achieve on your Windows computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-advanced-techniques-for-convincing-ppt-presentations-on-gmeet/"><u>[Updated] 2024 Approved Advanced Techniques for Convincing PPT Presentations on GMeet</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-exploring-high-speed-action-a-top-5-game-list/"><u>[Updated] 2024 Approved Exploring High-Speed Action A Top 5 Game List</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-easily-store-linkedin-videos-here-are-6-optimal-tools-for-it/"><u>[Updated] Easily Store LinkedIn Videos - Here Are 6 Optimal Tools for It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-remote-device-sharing-options-google-vs-windows/"><u>Deciphering Remote Device Sharing Options: Google Vs. Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-nokia-c22-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Nokia C22 FRP In 3 Different Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/limiting-unauthorized-insider-build-access/"><u>Limiting Unauthorized Insider Build Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-search-functionality-an-alternative-to-ls/"><u>Mastering Windows' Search Functionality: An Alternative to LS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-nokia-g310-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Nokia G310 – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/perfecting-ai-written-content-infusing-chatgpt-with-your-unique-writing-flair/"><u>Perfecting AI Written Content: Infusing ChatGPT with Your Unique Writing Flair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-initiating-windows-media-player/"><u>Quick Guide: Initiating Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/save-your-sound-levels-windows-mixer-recovery-guide/"><u>Save Your Sound Levels: Windows Mixer Recovery Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-complete-tutorial-for-setting-up-wake-on-lan-on-your-windows-11-device/"><u>The Complete Tutorial for Setting up Wake-on-LAN on Your Windows 11 Device</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlocking-iphone-sim-slot-with-everyday-objects-a-step-by-nstep-process/"><u>Unlocking iPhone SIM Slot with Everyday Objects - A Step-by-nStep Process</u></a></li>
</ul></div>

