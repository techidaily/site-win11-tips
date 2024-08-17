---
title: "Windows Reserve Memory: An Overview"
date: 2024-08-16T02:41:47.991Z
updated: 2024-08-17T02:41:47.991Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Reserve Memory: An Overview"
excerpt: "This Article Describes Windows Reserve Memory: An Overview"
keywords: Windows RAM Usage,System Reserves,Memory Allocation,OS Performance,Reserved Cache,Memory Management,Windows Efficiency
thumbnail: https://thmb.techidaily.com/f1e60caa3e6b666a54baaa6c3e17dd97a81f74bfc14a37bcb509db67f36be2c1.jpg
---

## Windows Reserve Memory: An Overview

 There’s no doubt that when it comes to a computer's performance, one of the most important roles is played by RAM (or Random Access Memory). However, Windows can’t use the amount of RAM mentioned in your computer specifications. This is because some of it is “reserved” by your system.

 But what is Hardware Reserved Memory? Can you check how much memory is reserved on your computer and can you adjust the value?

## What Is Hardware Reserved Memory?

 Windows saves a part of the available RAM, so your hardware components have enough resources to work properly. This is known as Hardware Reserved Memory, and Windows allocates it to hardware devices such as the network adapter, Bluetooth devices, sound card, and GPU, among other hardware devices.

 This way, Windows makes sure these components function as expected when you need them.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## How to Check Your Hardware Reserved Memory

 Windows makes it quite easy to check the amount of hardware reserved memory. Press**Ctrl + Shift + Esc** to bring up Task Manager. There, open the**Performance** tab and select**Memory** . Check the value next to**Hardware reserved** .

![Check hardware reserved memory on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-reserved-memory-1.jpg)

## How Your PC's Hardware Reserved Memory Impacts Performance

 If your system allocates too much of the RAM to the Hardware Reserved Memory, it will negatively impact your computer performance. Especially if you don’t have a lot of RAM to start with.

 Also, certain hardware components, such as high-end Graphics Processing Units or sound cards, need more memory to manage their assigned tasks. Moreover, Windows uses reserved memory to store drivers for peripheral devices, even if you don’t use them that often.

 If Windows reserves too much of your RAM, you might deal with longer boot-up times or even Windows crashing and freezing as it doesn’t have enough resources to keep all processes running.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## How to Adjust the Hardware Reserved Memory on Windows

 In general, the value for Hardware Reserved Memory should be a few hundred megabytes. The 32-bit version of Windows can reserve up to 3.5 GB of RAM, while the 64-bit system usually needs around 1GB. If the value is around a couple of GB, or even more, you’ll have to adjust the value. Fortunately, Windows has a few ways you can do it.

### 1\. Update Your Drivers

 Outdated or corrupt[computer drivers](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) will increase the amount of memory Windows reserves to keep your hardware devices running smoothly. Updating the drivers, especially the GPU drivers, might help Windows reduce the amount of reserved memory.

 Additionally, it might help to disable drivers for devices that you no longer use, as Windows will keep managing them. Launch Device Manager, go through the list, then locate any unneeded drivers. Click them and select**Disable device** .

![Disable device through Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->

 When disabling hardware devices, make sure you no longer need them, as you might be causing issues within your system.

### 2\. Install 64-Bit Windows

 There are a few[differences between 32-bit and 64-bit Windows](https://www.makeuseof.com/tag/difference-32-bit-64-bit-windows/) , including the amount of Hardware Reserved Memory. As we’ve mentioned, a 64-bit Windows assigns less RAM to the Hardware Reserved Memory, so updating from 32-bit to the 64-bit Windows version should reduce the amount of reserved memory.

 If you’re not sure which version you’re currently running, press**Windows key + I** to bring up the Settings menu. There, head to**System** , scroll to the bottom of the page, and click**About** . Check the value next to**System type** to check if your system is 32 or 64-bit.

![Check Windows version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-64bit-1.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Set a Preferred GPU

 There’s a chance your computer has two GPUs, and one of them is better when managing high-intensive graphics tasks. Instead of using the integrated graphics card to process complex tasks, you should[choose a preferred GPU for games or editing software](https://www.makeuseof.com/windows-10-choose-preferred-gpu/) to reduce the memory reserved by Windows.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
### 5\. Restore the BIOS to Its Default Settings

 You can use your computer for years without thinking of BIOS. But it plays an important role in your computer’s stability. If you notice your system assigns too many resources to the Hardware Reserved Memory, the problem might be caused by improper BIOS settings. In this case, reverting it to its default settings should fix the issue.

 First, press**Del** or**F2** to enter BIOS during the Windows startup screen. From the bottom of the page, click Load Defaults (or Restore Settings) and confirm the action. Then, exit BIOS, restart your computer, and check the Hardware Reserved Memory value.

 If you can’t access BIOS during the startup screen, there are more[methods you could try to enter BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) and reset it.

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-insiders-guide-to-overwatch-game-recording/"><u>[New] 2024 Approved  The Insider's Guide to Overwatch Game Recording</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-how-to-add-the-date-to-photo/"><u>[New] How to Add the Date to Photo</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-how-to-layer-melodies-into-instagram-media-content-for-2024/"><u>[New] How to Layer Melodies Into Instagram Media Content for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-charting-a-course-through-youtubes-maker-domain/"><u>[New] In 2024, Charting a Course Through YouTube's Maker Domain</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-from-theory-to-practice-mastering-instagram-livestreams-through-obs/"><u>[New] In 2024, From Theory to Practice  Mastering Instagram Livestreams Through OBS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-incredible-inexpensive-stopwatch-solutions/"><u>[New] Incredible Inexpensive Stopwatch Solutions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-groundbre-folio-of-gaming-loggers-alternatives-to-fbx-for-2024/"><u>[Updated] Groundbre Folio of Gaming Loggers Alternatives to FBX for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-switch-showdown-top-10-arcade-combat-classics-for-2024/"><u>[Updated] Switch Showdown  Top 10 Arcade Combat Classics for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sticky-context-menus-in-windows-11-edition/"><u>Addressing Sticky Context Menus in Windows 11 Edition</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/are-there-connectivity-issues-with-the-psn-service-or-problems-on-your-end/"><u>Are There Connectivity Issues with the PSN Service or Problems on Your End?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitfort-fractured-stay-the-course-before-change/"><u>BitFort Fractured: Stay the Course Before Change</u></a></li>
<li><a href="https://extra-resources.techidaily.com/budget-friendly-flight-machines-the-cheapest-drone-list/"><u>Budget-Friendly Flight Machines  The Cheapest Drone List</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-self-initiating-open-of-search-bar-win11-help/"><u>Cease Self-Initiating Open of Search Bar, Win11 Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compelling-case-for-continuing-with-windows-10-win10/"><u>Compelling Case for Continuing with Windows 10 (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-time-and-date-on-windows-11-taskbar/"><u>Configuring Time and Date on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364670351-create-a-gratis-local-gptclone-with-gpt4all-for-windows/"><u>Create a Gratis, Local GPTClone with GPT4All for Windows.</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>Detailed guide of ispoofer for pogo installation On Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-route-to-recent-windows-documents/"><u>Direct Route to Recent Windows Documents</u></a></li>
<li><a href="https://article-posts.techidaily.com/dynamic-editing-mastering-effects-on-tiktok-content-for-2024/"><u>Dynamic Editing  Mastering Effects on TikTok Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-smart-color-settings-in-windows-11-programs/"><u>Enable Smart Color Settings in Windows 11 Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-security-modifying-the-reset-counter-post-failed-logon-attempts-win-11/"><u>Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-printer-disconnection-in-windows-10-and-11-systems/"><u>Fast Track Printer Disconnection in Windows 10 & 11 Systems</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-samsung-galaxy-a23-5g-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-end-task-feature-for-efficient-task-execution-windows-11/"><u>How to Configure End Task Feature for Efficient Task Execution (Windows 11)</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-find-lost-iphone-15-backup-files-on-windows-pc-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to find lost iPhone 15 Backup files on Windows PC? | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreachable-status-for-malwarebytes-services-in-win11/"><u>How to Fix Unreachable Status for Malwarebytes' Services in Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-oppo-reno-11-pro-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Oppo Reno 11 Pro 5G</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-6s-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>How to Unlock iPhone 6s With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-8-budget-friendly-cross-platform-video-conferencing-tools-revealed/"><u>In 2024, 8 Budget-Friendly, Cross-Platform Video Conferencing Tools Revealed</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-realme-11-pro-by-drfone-android/"><u>In 2024, How to Bypass FRP from Realme 11 Pro?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-samsung-galaxy-s23-tactical-edition-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Samsung Galaxy S23 Tactical Edition Phone FRP Lock</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-masterful-collage-techniques-for-instagram-excellence/"><u>In 2024, Masterful Collage Techniques for Instagram Excellence</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-masterful-moment-captures-with-expert-photo-frames-online/"><u>In 2024, Masterful Moment Captures with Expert Photo Frames Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-ram-essential-tweaks-for-enhanced-windows-performance/"><u>Maximizing RAM: Essential Tweaks for Enhanced Windows Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screen-phenomenon-in-webcams/"><u>Overcoming Black Screen Phenomenon in Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-boot-options-modifying-windows-11s-startup-delay/"><u>Quick Boot Options: Modifying Windows 11'S Startup Delay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-ailing-xbox-controllers/"><u>Restoring Functionality to Ailing Xbox Controllers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/silverleaf-studio-exploring-lightroom-substitutes/"><u>Silverleaf Studio  Exploring Lightroom Substitutes</u></a></li>
<li><a href="https://driver-error.techidaily.com/steering-through-technical-hiccups-elan-and-win10/"><u>Steering Through Technical Hiccups: Elan & Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reactivate-apps-hindered-by-qt-plugin-issue/"><u>Steps to Reactivate Apps Hindered by Qt Plugin Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-active-directory-related-printer-crashes-on-w11/"><u>Strategies for Resolving Active Directory-Related Printer Crashes on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-definitive-window-by-window-walkthrough-of-hdr-in-windows-11/"><u>The Definitive Window-by-Window Walkthrough of HDR in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-gateway-how-to-enter-os-settings/"><u>The Gateway: How to Enter OS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unable-to-open-geforce-experience-error/"><u>Troubleshooting Unable to Open GeForce Experience Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-printer-access-for-windows-users/"><u>Unblocking Printer Access for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-windows-error-code-0x80071a90/"><u>Understanding and Correcting Windows Error Code: 0X80071A90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unplugging-problems-addressing-frequent-ps4-disconnection-in-pc/"><u>Unplugging Problems: Addressing Frequent PS4 Disconnection in PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-recurring-anydesk-windows-anomalies/"><u>Unraveling Recurring AnyDesk Windows Anomalies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mysteries-of-microsofts-copilot-key-in-windows-11/"><u>Unveiling the Mysteries of Microsoft's Copilot Key in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/web-accessibility-in-the-absence-of-built-in-browser/"><u>Web Accessibility in the Absence of Built-In Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-gaming-experience-boosted-by-solving-directdraw-errors/"><u>Windows 11 & 11 Gaming Experience Boosted by Solving DirectDraw Errors</u></a></li>
</ul></div>
