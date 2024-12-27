---
title: "Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer"
date: 2024-12-26T22:50:55.448Z
updated: 2024-12-27T18:21:36.175Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer"
excerpt: "This Article Describes Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer"
keywords: FastWakeBoot,QuickStartPC,ReduceBootTime,AccelerateBoot,SpeedyStartup,WakeUpFaster,OptimizeBootTimer
thumbnail: https://thmb.techidaily.com/272951d0a7f7a1f53c7ee474aec14f4b7a67f49064e3845b52b4ea1d0a9fa3cd.png
---

## Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**
5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-tips-and-tricks-for-recording-ps3-games-with-flawless-results/"><u>[New] In 2024, Tips and Tricks for Recording PS3 Games with Flawless Results</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-revolutionize-your-social-media-strategy-use-free-video-creation-kit/"><u>[New] Revolutionize Your Social Media Strategy – Use Free Video Creation Kit</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-balancing-act-weaving-b-roll-into-main-scenes/"><u>[Updated] 2024 Approved Balancing Act Weaving B Roll Into Main Scenes</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/chatbots-unveiled-the-ai-enthusiasts-guide/"><u>Chatbots Unveiled: The AI Enthusiast's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disable-win-11-mobility-center-effortlessly/"><u>Disable Win 11 Mobility Center Effortlessly</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/effizientes-ubertragen-von-backups-unter-windows-11-zu-einem-neu-gekauften-pc-schritt-fur-schritt-anleitung/"><u>Effizientes Übertragen Von Backups Unter Windows 11 Zu Einem Neu Gekauften PC - Schritt-Für-Schritt-Anleitung</u></a></li>
<li><a href="https://techtrends.techidaily.com/identifying-and-repairing-issues-with-a-non-responsive-car-radio/"><u>Identifying and Repairing Issues with a Non-Responsive Car Radio</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tiny-tale-telling-framework/"><u>In 2024, Tiny Tale Telling Framework</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-critical-application-hiccups-on-pc/"><u>Mitigating Critical Application Hiccups on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-directx-download-update-seamlessly/"><u>Navigating DirectX: Download, Update Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-spec-limits-on-windows-game-capturing/"><u>Overcoming Spec Limits on Windows Game Capturing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resizing-photos-made-simple-the-top-6-tricks-for-windows-11-users/"><u>Resizing Photos Made Simple: The Top 6 Tricks for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smart-scheduling-merging-to-do-with-ifttt-services/"><u>Smart Scheduling: Merging To-Do with IFTTT Services</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/stay-active-with-these-top-rated-motion-tracking-apps/"><u>Stay Active with These Top-Rated Motion Tracking Apps</u></a></li>
</ul></div>

