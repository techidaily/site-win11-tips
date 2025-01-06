---
title: "Faster Start-Up Methods: Modify Windows 11'S Booting Timeout"
date: 2025-01-01T18:38:54.447Z
updated: 2025-01-05T23:21:10.800Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Faster Start-Up Methods: Modify Windows 11'S Booting Timeout"
excerpt: "This Article Describes Faster Start-Up Methods: Modify Windows 11'S Booting Timeout"
keywords: Speed Up Boot Windows,Reduce Win11 Boot Time,Accelerate OS Startup,Shorten PC Boot Delay,Quickboot Windows 11,Fast Boot Windows,Optimize Boot Windows 11
thumbnail: https://thmb.techidaily.com/9530a6a7ae2d76ba480cbada332a623fd47509bd2903fa4cfebcaa0c3ca3de95.jpg
---

## Faster Start-Up Methods: Modify Windows 11'S Booting Timeout

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-a-detailed-list-of-top-free-cross-platform-mobile-video-chats/"><u>[New] 2024 Approved A Detailed List of Top Free, Cross-Platform Mobile Video Chats</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-essential-mic-selection-for-podcasters-the-top-10/"><u>[New] 2024 Approved Essential Mic Selection for Podcasters The Top 10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-sierras-cloud-essentials-drives-full-access-guide/"><u>[New] 2024 Approved Sierra's Cloud Essentials Drives Full Access Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-how-to-remove-jello-effect-from-an-aerial-video/"><u>[New] How to Remove Jello Effect From an Aerial Video</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-igniting-interest-how-to-elevate-your-instagram-contents-impact-for-2024/"><u>[Updated] Igniting Interest How to Elevate Your Instagram Content's Impact for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-airwaves-dismissing-error-a00f4289-in-win11-webcam/"><u>Clearing the Airwaves: Dismissing Error A00F4289 in Win11 Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-gaming-on-windows-11-mastering-amd-graphics-driver-updates/"><u>Cutting-Edge Gaming on Windows 11: Mastering AMD Graphics Driver Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-file-clarity-committing-comments-in-windows-11/"><u>Elevating File Clarity: Committing Comments in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/faster-fixes-eliminating-wwe-2k23-hitches-on-windows-11/"><u>Faster Fixes: Eliminating WWE 2K23 Hitches on Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-ios-system-of-iphone-15-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System of iPhone 15 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Xiaomi Redmi Note 12R? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-file-management-via-powertoys-lockmaster/"><u>Optimizing File Management via PowerToys Lockmaster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicken-your-load-time-at-ms-store-purchases/"><u>Quicken Your Load Time at MS Store Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-start-the-best-new-pc-toolkit/"><u>Seamless Start: The Best New PC Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-sound-checks-in-powerpoint-presentations/"><u>Techniques for Sound Checks in PowerPoint Presentations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-future-of-tech-tips-fees-unveiled-could-paying-up-to-20-monthly-for-exclusive-apple-analysis-become-a-trend-insights/"><u>The Future of Tech Tips Fees Unveiled: Could Paying Up to $20 Monthly for Exclusive Apple Analysis Become a Trend? Insights</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-10-free-whiteboard-animation-tools-for-windows-and-mac/"><u>Top 10 Free Whiteboard Animation Tools for Windows and Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-10-quick-methods-for-converting-ts-files-to-mp4-with-superior-quality/"><u>Top 10 Quick Methods for Converting TS Files to MP4 with Superior Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unclutter-your-screen-memory-with-these-methods/"><u>Unclutter Your Screen Memory with These Methods</u></a></li>
</ul></div>

