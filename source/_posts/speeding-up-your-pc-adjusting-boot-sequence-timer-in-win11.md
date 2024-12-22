---
title: "Speeding Up Your PC: Adjusting Boot Sequence Timer in Win11"
date: 2024-12-17T23:48:28.762Z
updated: 2024-12-21T18:40:57.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Speeding Up Your PC: Adjusting Boot Sequence Timer in Win11"
excerpt: "This Article Describes Speeding Up Your PC: Adjusting Boot Sequence Timer in Win11"
keywords: SpeedUpPCWin11BootSeq,BoostWin11BootTime,AccelerateWindowsBoot,OptimizeWin11Startup,FastenPCBootProcess,Win11BootSpeedBoost,QuickWindowsBootSetup
thumbnail: https://thmb.techidaily.com/3186e4df3cd85f5548d507c683f3aba596cb59805e7e3afa70cfb9fc8a32b29d.jpg
---

## Speeding Up Your PC: Adjusting Boot Sequence Timer in Win11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-anymp4-screen-recorder-review/"><u>[New] 2024 Approved AnyMP4 Screen Recorder Review</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-the-secrets-of-powerful-titles/"><u>[New] Unveiling the Secrets of Powerful Titles</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/1716069887375-updated-2024-approved-capturing-screens-with-internal-recorder-on-mate-1020-and-p-series-p20-p10-smartphones/"><u>[Updated] 2024 Approved Capturing Screens with Internal Recorder on Mate 10/20 & P Series (P20, P10) Smartphones.</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-inside-look-at-vimeo-and-youtubes-market-strategies/"><u>2024 Approved Inside Look at Vimeo and YouTube’s Market Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/connecting-cloud-drives-onedrive-meets-microsoft-live-on-windows/"><u>Connecting Cloud Drives: OneDrive Meets Microsoft Live on Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/disabling-unwanted-chimes-keep-your-ipad-quiet-when-your-iphone-receives-a-call/"><u>Disabling Unwanted Chimes: Keep Your iPad Quiet When Your iPhone Receives a Call</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-into-classic-diablo-key-moves-and-strategies/"><u>Diving Into Classic Diablo: Key Moves and Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-windows-11-aesthetics-the-ultimate-backdrop-guide/"><u>Elevating Windows 11 Aesthetics: The Ultimate Backdrop Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-xbox-sound-output-on-windows-11-system/"><u>Enhancing Xbox Sound Output on Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-flip-mkv-to-mp4-in-windows-os/"><u>How to Flip MKV to MP4 in Windows OS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-youtube-channel-art-how-to-make-banners-icons-and-thumbnails/"><u>In 2024, YouTube Channel Art How to Make Banners, Icons, and Thumbnails?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mobile-masterpieces-phones-ideal-for-media-makers/"><u>Mobile Masterpieces Phones Ideal for Media Makers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimized-workspace-setup-multi-window-harmony-in-win1110/"><u>Optimized Workspace Setup: Multi-Window Harmony in Win11/10</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Tecno Spark 10C? | Dr.fone</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/top-rated-lenovo-os-transition-tool-for-seamless-upgrades-to-windows-111087/"><u>Top Rated Lenovo OS Transition Tool for Seamless Upgrades to Windows 11/10/8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-update-hurdle-remedy-for-error-0x80246007/"><u>Windows Update Hurdle: Remedy for Error 0X80246007</u></a></li>
</ul></div>

