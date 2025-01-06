---
title: "Swift System Awakening: Alter Boot Timer for Efficiency"
date: 2025-01-03T20:49:29.492Z
updated: 2025-01-05T18:35:14.086Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Swift System Awakening: Alter Boot Timer for Efficiency"
excerpt: "This Article Describes Swift System Awakening: Alter Boot Timer for Efficiency"
keywords: Boost Swift Performance,Quick Time Adjustment,Enhance Swift Boot,Optimize Operating Speed,Improve System Efficiency,Swift Boot Timer Tweaks,Swift Startup Acceleration
thumbnail: https://thmb.techidaily.com/8358f47af5ec8aff78eb055a676b098baa58d37b0eb3993597fb253da585f204.jpg
---

## Swift System Awakening: Alter Boot Timer for Efficiency

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

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
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-audiovisual-power-evaluating-mirrorless-vs-dslr-cameras/"><u>[Updated] 2024 Approved Audiovisual Power Evaluating Mirrorless vs DSLR Cameras</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-notable-industry-players-driving-vr-growth/"><u>[Updated] 2024 Approved Notable Industry Players Driving VR Growth</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-the-ultimate-guide-to-iphonedesktop-video-change-top-8-recommendations/"><u>[Updated] 2024 Approved The Ultimate Guide to iPhone/Desktop Video Change Top 8 Recommendations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-c-span-broadcasts-unlocked-tips-for-fee-free-download/"><u>2024 Approved C-Span Broadcasts Unlocked Tips for Fee-Free Download</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-transform-your-viewership-with-immersive-360-livestreams-on-youtube/"><u>2024 Approved Transform Your Viewership with Immersive 360° Livestreams on YouTube</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-nokia-c210-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Nokia C210</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-windows-app-connectivity-with-top-fixes-and-troubleshooting-steps/"><u>Enhance Windows App Connectivity with Top Fixes and Troubleshooting Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-startup-experience-for-csgo-in-w11/"><u>Enhancing the Startup Experience for CS:GO in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-faulty-dual-monitor-configuration/"><u>Fixing Faulty Dual Monitor Configuration</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721470864018-fixing-the-hidden-iphone-making-it-visible-in-itunesfinder-once-again/"><u>Fixing the Hidden iPhone: Making It Visible in iTunes/Finder Once Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-missing-ssdhdd-drives/"><u>How to Find Missing SSD/HDD Drives?</u></a></li>
<li><a href="https://facebook.techidaily.com/methodology-of-removing-spam-from-online-discussions/"><u>Methodology of Removing Spam From Online Discussions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-camera-access-conflict-with-error-0xa00f4243/"><u>Resolving Camera Access Conflict with Error 0xA00F4243</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streaming-mastery-real-time-capture-of-games-via-windows-intel-hub/"><u>Streaming Mastery: Real-Time Capture of Games via Windows Intel Hub</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-why-is-lost-ark-still-not-launching/"><u>Troubleshooting Tips: Why Is Lost Ark Still Not Launching ?</u></a></li>
</ul></div>

