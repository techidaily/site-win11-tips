---
title: "Quick Boot Options: Modifying Windows 11'S Startup Delay"
date: 2024-06-25T16:26:53.980Z
updated: 2024-06-26T16:26:53.980Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Boot Options: Modifying Windows 11'S Startup Delay"
excerpt: "This Article Describes Quick Boot Options: Modifying Windows 11'S Startup Delay"
keywords: Win 11 Quick Boot,Shorten Startup Time,Adjust Windows Delay,Optimize System Launch,Reduce Booting Latency,Tweak Boot Speed,Minimize Load Time
thumbnail: https://thmb.techidaily.com/80bf249edf159410e9b0aa240c01664195ceb40e24ab3ca2d1256f5edd3745fb.jpg
---

## Quick Boot Options: Modifying Windows 11'S Startup Delay

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

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
![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/step-into-the-world-of-windows-11-home/"><u>Step Into the World of Windows 11 Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-hacks-bypassing-windows-account-verification/"><u>Advanced Hacks: Bypassing Windows Account Verification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-simple-fixes-for-your-non-operational-windows-notepad/"><u>Five Simple Fixes for Your Non-Operational Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-lock-pattern-creation-guide-for-windows-11-pcs/"><u>Personalized Lock Pattern Creation Guide for Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-skip-out-of-s-mode-with-ease-for-your-pc/"><u>Swiftly Skip Out of S Mode with Ease for Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-the-way-you-search-on-windows-11/"><u>Revamp the Way You Search on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-disabling-xbox-game-pass-error/"><u>Mastering the Art of Disabling Xbox Game Pass Error</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-get-hd-quality-facebook-videos-on-pcmobile/"><u>2024 Approved  Get HD Quality Facebook Videos on PC/Mobile</u></a></li>
<li><a href="https://fox-blue.techidaily.com/avatar-architecture-your-uncomplicated-guide-to-virtual-existence/"><u>Avatar Architecture  Your Uncomplicated Guide to Virtual Existence</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabling-apple-iphone-se-2020-parental-restrictions-withwithout-password-by-drfone-ios/"><u>In 2024, Disabling Apple iPhone SE (2020) Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/need-to-find-the-best-video-editing-apps-to-edit-video-on-your-ipad-we-can-help-from-here-this-guide-lists-the-best-video-editors-for-ipad-for-2024/"><u>Need to Find the Best Video Editing Apps to Edit Video on Your iPad? We Can Help From Here. This Guide Lists the Best Video Editors for iPad for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-directory-where-to-download-youtube-ringtones/"><u>In 2024, Ultimate Directory  Where to Download YouTube Ringtones?</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-10-leading-video-resizing-and-cropping-solutions/"><u>Updated 2024 Approved 10 Leading Video Resizing and Cropping Solutions</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/mind-puzzling-stats-a-graphed-journey-through-yt-17/"><u>Mind-Puzzling Stats  A Graphed Journey Through YT '17</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ultimate-home-theatre-devices-top-10-list-24/"><u>Ultimate Home Theatre Devices - Top 10 List '24</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-giggle-grind-exploring-twitters-comedy-gold-for-2024/"><u>[Updated] Giggle Grind  Exploring Twitters' Comedy Gold for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>