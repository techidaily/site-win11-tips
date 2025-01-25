---
title: "Boosting Startup Efficiency: Altering Boot Menu Delay"
date: 2025-01-17T20:51:06.564Z
updated: 2025-01-24T19:48:09.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Startup Efficiency: Altering Boot Menu Delay"
excerpt: "This Article Describes Boosting Startup Efficiency: Altering Boot Menu Delay"
keywords: Startup Efficiency Tips,Reduce Boot Time,Optimize Boot Process,Boot Menu Speed Up,Enhance System Launch,Delay-Free Boot,Fast Boot Configuration
thumbnail: https://thmb.techidaily.com/daa4ddbb9dc17599c8cc745fc4daad052ccf0ddb620b28a0347c7de8e4fb4249.jpg
---

## Boosting Startup Efficiency: Altering Boot Menu Delay

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.
5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  
![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/new-expert-mac-animation-saver-for-2024/"><u>[New] Expert Mac Animation Saver for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-chuckle-trail-your-guide-to-hilarious-online-stars/"><u>[New] In 2024, Chuckle Trail Your Guide to Hilarious Online Stars</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-from-script-to-spectacle-independent-effect-innovation-for-2024/"><u>[Updated] From Script to Spectacle Independent Effect Innovation for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-vfx-artisan-suite/"><u>2024 Approved VFX Artisan Suite</u></a></li>
<li><a href="https://blog-min.techidaily.com/6-ways-to-transfer-contacts-from-itel-p40plus-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>6 Ways To Transfer Contacts From Itel P40+ to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-drive-errors-a-windows-guide/"><u>Clearing Drive Errors: A Windows Guide</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-samsung-galaxy-m14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-the-ultimate-macos-experience-with-screenflow-reviewed/"><u>In 2024, The Ultimate MacOS Experience with ScreenFlow Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-stop-video-driver-restarts/"><u>Quick Guide to Stop Video Driver Restarts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-keys-triggering-without-intent/"><u>Remedying Windows Keys Triggering without Intent</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-operation-failure-0x0000011b-in-windows-11/"><u>Solving Operation Failure 0X0000011B in Windows 11</u></a></li>
<li><a href="https://techidaily.com/some-mp4-won-t-play-on-my-xiaomi-redmi-note-13-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Some MP4 won't play on my Xiaomi Redmi Note 13 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-must-knows-thriving-as-a-manager-free-on-your-windows-pc/"><u>Top 10 Must-Knows: Thriving as a Manager, Free on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-corrected-display-sharing-after-connection-issues/"><u>Unlocking Corrected Display Sharing After Connection Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-users-guide-6-premier-activity-tracker-tools/"><u>Win Users' Guide: 6 Premier Activity Tracker Tools</u></a></li>
</ul></div>

