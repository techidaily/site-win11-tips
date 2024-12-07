---
title: "Trimming Wait Durations: Changing Boot Menu Delay on Win11"
date: 2024-12-01T00:51:06.653Z
updated: 2024-12-06T19:07:53.121Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Trimming Wait Durations: Changing Boot Menu Delay on Win11"
excerpt: "This Article Describes Trimming Wait Durations: Changing Boot Menu Delay on Win11"
keywords: Reduce Boot Delay (W10/Win11),Win11 Boot Acceleration,Boot Menu Optimization,Minimize W11 Wait Time,Trim Win11 Load Speed,Adjust Boot Menu Delay,Enhance W11 Boot Sequence
thumbnail: https://thmb.techidaily.com/8ea49d46a7efdbdbce7ce2f715d9bd1879477faba848022dab03800aadbcadb1.jpg
---

## Trimming Wait Durations: Changing Boot Menu Delay on Win11

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-reestablishing-connection-with-dormant-obs-camera/"><u>[New] 2024 Approved Reestablishing Connection with Dormant OBS Camera</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-fostering-fandom-creating-jujutsu-kaisen-content-for-tiktok/"><u>2024 Approved Fostering Fandom Creating Jujutsu Kaisen Content for TikTok</u></a></li>
<li><a href="https://fox-glue.techidaily.com/crafting-a-symphony-of-sights-and-sounds-in-video/"><u>Crafting a Symphony of Sights & Sounds in Video</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-common-issues-troubleshooting-a-non-functional-corsair-keyboard/"><u>Fixing Common Issues: Troubleshooting a Non-Functional Corsair Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-dll-not-loading-error-in-windows-steam-client/"><u>Fixing Dll Not Loading Error in Windows Steam Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11s-revamped-widget-interface/"><u>Implementing Windows 11'S Revamped Widget Interface</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-iphone-13-pro-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>In 2024, Unlocking iPhone 13 Pro Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/iphone-xr-asking-for-passcode-after-ios-1714-update-what-to-do-drfone-by-drfone-ios/"><u>iPhone XR Asking for Passcode after iOS 17/14 Update, What to Do? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/learn-photoshops-core-techniques-for-shade-adjustment/"><u>Learn Photoshop's Core Techniques for Shade Adjustment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimalist-workstations-with-windows-os/"><u>Minimalist Workstations with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-manipulate-text-illumination-in-windows-11/"><u>Quickly Manipulate Text Illumination in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-error-0x80300024-in-winxp/"><u>Steps for Rectifying Error 0X80300024 in WinXP</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ech-to-record-your-live-video-feeds-online/"><u>Top Tech to Record Your Live Video Feeds Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-csgo-in-w11/"><u>Unlocking the Power of CS:GO in W11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-cut-and-split-wmv-videos-for-free-top-software-picks/"><u>Updated 2024 Approved Cut and Split WMV Videos for Free Top Software Picks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    