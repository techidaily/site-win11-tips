---
title: 4 Ways to Change Boot Menu Timeout in Windows 11
date: 2024-07-03T12:44:54.107Z
updated: 2024-07-04T12:44:54.107Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Change Boot Menu Timeout in Windows 11
excerpt: This Article Describes 4 Ways to Change Boot Menu Timeout in Windows 11
keywords: Win11 BootChangeTime,SetBootTimeoutWin11,DelayWindowsBootStartup,ExtendBootMenuDelay,ShortenWindowsBoot,WindowsBootAdjustment,ModifyBootTimeoutWins
thumbnail: https://thmb.techidaily.com/eeef901d1f6e0f72044944aeb5612974e0f0cbfc3a23bf93996d4e40618dadce.jpeg
---

## 4 Ways to Change Boot Menu Timeout in Windows 11

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
<li><a href="https://win11-tips.techidaily.com/avoiding-add-ons-for-disk-image-duality-on-pc/"><u>Avoiding Add-Ons for Disk Image Duality on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-qt-plugin-during-software-application-initiation/"><u>Overcoming Missing Qt Plugin During Software Application Initiation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-snip-and-sketch-shortcut/"><u>Launching Windows 11'S Snip & Sketch Shortcut</u></a></li>
<li><a href="https://win11-tips.techidaily.com/foster-robust-windows-application-connections-with-simple-fixes/"><u>Foster Robust Windows Application Connections with Simple Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-window-11-interface-for-maximum-efficiency-and-satisfaction/"><u>Tailor Your Window 11 Interface for Maximum Efficiency and Satisfaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-0x8024800c-in-windows-update/"><u>Steps to Resolve 0X8024800C in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-virtualbox-usb-connection-issue-on-windows-devices/"><u>Overcoming VirtualBox USB Connection Issue on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-obstacles-for-secure-memory-settings-in-new-windows-11/"><u>Clearing Obstacles for Secure Memory Settings in New Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-establish-java-development-kit-in-windows-11/"><u>A Complete Walkthrough to Establish Java Development Kit in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338830306-windows-lacks-drive-letters-why-and-how-to-rectify-this-issue/"><u>Windows Lacks Drive Letters: Why and How to Rectify This Issue</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-m54-5g-bootloader-easily-by-drfone-android/"><u>How to Unlock Samsung Galaxy M54 5G Bootloader Easily</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/boost-engagement-by-personalizing-your-twitter-videos-with-new-thumbnails-for-2024/"><u>Boost Engagement by Personalizing Your Twitter Videos with New Thumbnails for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-from-recording-to-revealing-uploading-high-quality-vr-on-fb/"><u>[Updated] From Recording to Revealing  Uploading High-Quality VR on FB</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-turn-on-and-use-automatic-hdr-high-dynamic-range-in-windows-11/"><u>[New] How to Turn On and Use Automatic HDR (High Dynamic Range) in Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-effortless-video-rotation-discover-the-top-10-online-tools/"><u>New 2024 Approved Effortless Video Rotation Discover the Top 10 Online Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/screen-recorder-pro-for-windows-11-for-2024/"><u>Screen Recorder Pro for Windows 11 for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-mastering-windows-graphics-the-top-9-tools-for-capturing-animation-gifs/"><u>2024 Approved  Mastering Windows Graphics  The Top 9 Tools for Capturing Animation GIFs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-pro-max-without-passcode-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 12 Pro Max Without Passcode? 4 Easy Methods</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-motorola-moto-g84-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Motorola Moto G84 5G | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-captured-moment-to-moving-picture/"><u>[New] From Captured Moment to Moving Picture</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>