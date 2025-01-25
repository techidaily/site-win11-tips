---
title: "Brisk Startups in Win11: Adjusting Boot Delay Period"
date: 2025-01-20T00:42:10.036Z
updated: 2025-01-24T20:35:54.332Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Brisk Startups in Win11: Adjusting Boot Delay Period"
excerpt: "This Article Describes Brisk Startups in Win11: Adjusting Boot Delay Period"
keywords: Win11 Boot Speed,Boost Win11 Performance,Shorten Windows Boot,Optimize Win11 Startup,Quick Win11 Launch,Enhance Boot Delay Win11,Tweak Boot Time Win11
thumbnail: https://thmb.techidaily.com/ccd36b11fe822cf8edc40f8a572a80b6d8bbf0e625e60ce40fafebff8828fa14.jpeg
---

## Brisk Startups in Win11: Adjusting Boot Delay Period

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-techniques.techidaily.com/new-ideal-avi-viewer-mobile-and-desktop-edition/"><u>[New] Ideal AVI Viewer Mobile & Desktop Edition</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-leap-into-fitness-a-curated-selection-of-vr-treadmill-pros/"><u>[New] Leap Into Fitness A Curated Selection of VR Treadmill Pros</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-record-internal-audio-in-android-without-root-4-ways-for-2024/"><u>[New] Record Internal Audio in Android without Root [4 Ways] for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/cookiebot-driven-success-enhancing-your-websites-user-experience/"><u>Cookiebot-Driven Success: Enhancing Your Website's User Experience</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-update-and-synchronization-service/"><u>Decoding Windows Update and Synchronization Service</u></a></li>
<li><a href="https://program-issues.techidaily.com/detailed-solutions-for-players-experiencing-stalled-load-screens-during-dota-2-startup/"><u>Detailed Solutions for Players Experiencing Stalled Load Screens During Dota 2 Startup</u></a></li>
<li><a href="https://fox-pages.techidaily.com/die-besten-aomei-backup-software-produkte-handbucher-und-angebote-entdecken-ihre-schritt-fur-schritt-anleitung/"><u>Die Besten AOMEI Backup Software Produkte, Handbücher Und Angebote Entdecken - Ihre Schritt-Für-Schritt Anleitung!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-drive-downloads-streamlined-access-to-dropbox-and-google-drive/"><u>Direct Drive Downloads: Streamlined Access to Dropbox and Google Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-common-blue-screen-errors-vmware-win11-edition/"><u>Fixing Common Blue Screen Errors: VMware, Win11 Edition</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-honor-v-purse-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Honor V Purse Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-limited-usb-controller-space-on-pcs/"><u>Resolving Limited USB Controller Space on PCs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/resolving-missing-sound-in-obs/"><u>Resolving Missing Sound in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tools-to-enhance-your-desktop-writing-skills-windows/"><u>Top Tools to Enhance Your Desktop Writing Skills (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-mechanics-of-law-filters-on-windows-os/"><u>Understanding the Mechanics of LAW Filters on Windows OS</u></a></li>
</ul></div>

