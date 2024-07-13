---
title: Understanding Windows' Approach to Allocated RAM
date: 2024-07-12T16:44:28.781Z
updated: 2024-07-13T16:44:28.781Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding Windows' Approach to Allocated RAM
excerpt: This Article Describes Understanding Windows' Approach to Allocated RAM
keywords: RAM Windows Usage,RAM Allocation Windows,RAM Management Windows,System RAM in Windows,RAM Efficiency Windows,Windows RAM Utilization,Memory Settings Windows
thumbnail: https://thmb.techidaily.com/5648c434c12cbf88b15506d6d23b8724252689511d16fa18d7a28833e2a6d9c5.jpg
---

## Understanding Windows' Approach to Allocated RAM

 There’s no doubt that when it comes to a computer's performance, one of the most important roles is played by RAM (or Random Access Memory). However, Windows can’t use the amount of RAM mentioned in your computer specifications. This is because some of it is “reserved” by your system.

 But what is Hardware Reserved Memory? Can you check how much memory is reserved on your computer and can you adjust the value?

## What Is Hardware Reserved Memory?

 Windows saves a part of the available RAM, so your hardware components have enough resources to work properly. This is known as Hardware Reserved Memory, and Windows allocates it to hardware devices such as the network adapter, Bluetooth devices, sound card, and GPU, among other hardware devices.

 This way, Windows makes sure these components function as expected when you need them.

## How to Check Your Hardware Reserved Memory

 Windows makes it quite easy to check the amount of hardware reserved memory. Press**Ctrl + Shift + Esc** to bring up Task Manager. There, open the**Performance** tab and select**Memory** . Check the value next to**Hardware reserved** .

![Check hardware reserved memory on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-reserved-memory-1.jpg)

## How Your PC's Hardware Reserved Memory Impacts Performance

 If your system allocates too much of the RAM to the Hardware Reserved Memory, it will negatively impact your computer performance. Especially if you don’t have a lot of RAM to start with.

 Also, certain hardware components, such as high-end Graphics Processing Units or sound cards, need more memory to manage their assigned tasks. Moreover, Windows uses reserved memory to store drivers for peripheral devices, even if you don’t use them that often.

 If Windows reserves too much of your RAM, you might deal with longer boot-up times or even Windows crashing and freezing as it doesn’t have enough resources to keep all processes running.

## How to Adjust the Hardware Reserved Memory on Windows

 In general, the value for Hardware Reserved Memory should be a few hundred megabytes. The 32-bit version of Windows can reserve up to 3.5 GB of RAM, while the 64-bit system usually needs around 1GB. If the value is around a couple of GB, or even more, you’ll have to adjust the value. Fortunately, Windows has a few ways you can do it.

### 1\. Update Your Drivers

 Outdated or corrupt [computer drivers](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) will increase the amount of memory Windows reserves to keep your hardware devices running smoothly. Updating the drivers, especially the GPU drivers, might help Windows reduce the amount of reserved memory.

 Additionally, it might help to disable drivers for devices that you no longer use, as Windows will keep managing them. Launch Device Manager, go through the list, then locate any unneeded drivers. Click them and select**Disable device** .

![Disable device through Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-1.jpg)

 When disabling hardware devices, make sure you no longer need them, as you might be causing issues within your system.

### 2\. Install 64-Bit Windows

 There are a few [differences between 32-bit and 64-bit Windows](https://www.makeuseof.com/tag/difference-32-bit-64-bit-windows/) , including the amount of Hardware Reserved Memory. As we’ve mentioned, a 64-bit Windows assigns less RAM to the Hardware Reserved Memory, so updating from 32-bit to the 64-bit Windows version should reduce the amount of reserved memory.

 If you’re not sure which version you’re currently running, press**Windows key + I** to bring up the Settings menu. There, head to**System** , scroll to the bottom of the page, and click**About** . Check the value next to**System type** to check if your system is 32 or 64-bit.

![Check Windows version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-64bit-1.jpg)

### 3\. Set a Preferred GPU

 There’s a chance your computer has two GPUs, and one of them is better when managing high-intensive graphics tasks. Instead of using the integrated graphics card to process complex tasks, you should [choose a preferred GPU for games or editing software](https://www.makeuseof.com/windows-10-choose-preferred-gpu/) to reduce the memory reserved by Windows.

### 4\. Run the Hardware and Devices Troubleshooter

 If one of your connected devices isn’t working properly, Windows might reserve more of your system memory. To fix it, you should run Windows’ Hardware and Devices troubleshooter. Here’s how you can do it:

1. Launch Command Prompt with administrative rights.
2. Type**msdt.exe -id DeviceDiagnostic** and press**Enter** .
3. In the Hardware and Devices window, click**Advanced** , and check the**Apply repairs automatically** option.
4. Click**Next** to start the process.

![Running the hardware and devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hardware-devices-1.jpg)

### 4\. Edit Your System Configuration

 In general, Windows is the only one deciding how much of your system memory it reserves. However, you can control the maximum amount of reserved memory through System Configuration. Here’s how you can do it:

1. Press**Win + R** to bring up a Run box.
2. Type**msconfig** and press**Enter** .
3. In the System Configuration window, open the**Boot** tab.
4. Click**Advanced options** .
5. Check**Maximum memory** and edit the value.
6. Click**OK** .

![Change boot settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/boot-settings-1.jpg)

 Keep in mind this will have a direct impact on how much memory Windows reserves to keep your system running properly. Don’t set a value too low to make sure Windows has enough resources.

### 5\. Restore the BIOS to Its Default Settings

 You can use your computer for years without thinking of BIOS. But it plays an important role in your computer’s stability. If you notice your system assigns too many resources to the Hardware Reserved Memory, the problem might be caused by improper BIOS settings. In this case, reverting it to its default settings should fix the issue.

 First, press**Del** or**F2** to enter BIOS during the Windows startup screen. From the bottom of the page, click Load Defaults (or Restore Settings) and confirm the action. Then, exit BIOS, restart your computer, and check the Hardware Reserved Memory value.

 If you can’t access BIOS during the startup screen, there are more [methods you could try to enter BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) and reset it.

## Manage the Hardware Reserved Memory on Windows

 Hopefully, our guide helped you know more about your computer’s hardware reserved memory. The truth is, you may not even think about it until it negatively impacts your system’s performance, but if this happens, the tips above should help you manage the situation.

 But there are so many system tricks that you could use to avoid having Windows take too much of your resources. If you’re looking for a permanent fix, you might have to upgrade your computer’s hardware.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/quick-collage-assembly-tips-for-instant-sharing-for-2024/"><u>Quick Collage Assembly Tips for Instant Sharing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-hypervisor-on-windows-sandbox/"><u>Addressing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-pcs-problems-4-top-pct-strategies/"><u>Ace Your PC's Problems: 4 Top PCT Strategies</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-peeksnapper-a-critical-examination-of-micro-recording-tools/"><u>[Updated] In 2024, PeekSnapper  A Critical Examination of Micro-Recording Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-x80049dd3-for-smooth-typing-on-windows-11/"><u>Addressing Error X80049DD3 for Smooth Typing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-cluttered-symbol-groups-on-windows-shell/"><u>Addressing Cluttered Symbol Groups on Windows Shell</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-optimal-obs-configurations-for-thrifty-computers/"><u>[Updated] 2024 Approved  Optimal OBS Configurations for Thrifty Computers</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-oppo-find-n3-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Oppo Find N3 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-methods-for-subtle-volume-reduction-in-fl-studio/"><u>2024 Approved  Methods for Subtle Volume Reduction in FL Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-crucial-windows-apps-making-mac-to-windows-swap-a-breeze/"><u>5 Crucial Windows Apps Making Mac to Windows Swap a Breeze</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-copyrights-demystified-understanding-and-managing-strikes-for-2024/"><u>YouTube Copyrights Demystified  Understanding and Managing Strikes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-privileges-and-permissions-panel/"><u>Activating Windows 11 Privileges and Permissions Panel</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-nokia-130-musicmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Nokia 130 MusicMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-bypass-the-required-apple-store-verification-for-apple-iphone-6-by-drfone-ios/"><u>In 2024, How To Bypass the Required Apple Store Verification For Apple iPhone 6</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-huawei-p60-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Huawei P60 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363856500-unfreeze-reset-and-restore-shift-key/"><u>Unfreeze, Reset, and Restore Shift Key</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-the-ultimate-list-of-3d-video-software-you-cant-miss/"><u>New 2024 Approved The Ultimate List of 3D Video Software You Cant Miss</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-dynamic-duo-enhancing-fb-live-with-monitor-sharing-capabilities/"><u>[Updated] 2024 Approved  Dynamic Duo  Enhancing Fb Live with Monitor Sharing Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-microsofts-bluetooth-app/"><u>A Step-by-Step Guide to Using Microsoft's Bluetooth App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/20-tactics-for-disabling-windows-11/"><u>20 Tactics for Disabling Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-8-iphone-accessories-elevate-your-selfies-today/"><u>[New] Top 8 iPhone Accessories - Elevate Your Selfies Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-index-view-options/"><u>Accessing Windows Index View Options</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-new-wave-of-livestream-software-outshining-obs-for-2024/"><u>The New Wave of Livestream Software Outshining OBS for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/choosing-the-right-time-for-music-top-rated-mp3-to-karaoke-tools-on-and-offline/"><u>Choosing the Right Time for Music Top-Rated MP3 to Karaoke Tools, On and Offline</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-visuals-in-webcams/"><u>Addressing Absence of Visuals in Webcams</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-proven-strategies-for-smooth-recording-in-google-meethangouts-platforms-for-2024/"><u>[New] Proven Strategies for Smooth Recording in Google Meet/Hangouts Platforms for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-honor-play-8t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-why-pcs-take-the-lead-over-macs-9/"><u>A Closer Look at Why PCs Take the Lead over Macs (#9)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-stalled-downloads-with-qbittorrent-fixes/"><u>Accelerating Stalled Downloads with qBittorrent Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-restore-missing-windows-time-service/"><u>6 Ways to Restore Missing Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-timeout-issue-windows-1110-semaphore-error-0x80070079/"><u>Addressing Timeout Issue - Windows 11/10 Semaphore Error 0X80070079</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381461685-unlock-hidden-features-in-windows-snipping-tool-for-flawless-screen-shots/"><u>Unlock Hidden Features in Windows Snipping Tool for Flawless Screen Shots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-efficiency-program-troubleshooting-tool-inclusion/"><u>Adding Efficiency: Program Troubleshooting Tool Inclusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-solutions-for-streamlining-windows-display-issues/"><u>5 Solutions for Streamlining Windows Display Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358270699-reclaim-shift-control-with-easy-fixes/"><u>Reclaim Shift Control with Easy Fixes.</u></a></li>
</ul></div>
