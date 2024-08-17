---
title: Understanding Windows' Approach to Allocated RAM
date: 2024-08-16T02:23:04.252Z
updated: 2024-08-17T02:23:04.252Z
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
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## How Your PC's Hardware Reserved Memory Impacts Performance

 If your system allocates too much of the RAM to the Hardware Reserved Memory, it will negatively impact your computer performance. Especially if you don’t have a lot of RAM to start with.

 Also, certain hardware components, such as high-end Graphics Processing Units or sound cards, need more memory to manage their assigned tasks. Moreover, Windows uses reserved memory to store drivers for peripheral devices, even if you don’t use them that often.

 If Windows reserves too much of your RAM, you might deal with longer boot-up times or even Windows crashing and freezing as it doesn’t have enough resources to keep all processes running.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## How to Adjust the Hardware Reserved Memory on Windows

 In general, the value for Hardware Reserved Memory should be a few hundred megabytes. The 32-bit version of Windows can reserve up to 3.5 GB of RAM, while the 64-bit system usually needs around 1GB. If the value is around a couple of GB, or even more, you’ll have to adjust the value. Fortunately, Windows has a few ways you can do it.

### 1\. Update Your Drivers

 Outdated or corrupt [computer drivers](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) will increase the amount of memory Windows reserves to keep your hardware devices running smoothly. Updating the drivers, especially the GPU drivers, might help Windows reduce the amount of reserved memory.

 Additionally, it might help to disable drivers for devices that you no longer use, as Windows will keep managing them. Launch Device Manager, go through the list, then locate any unneeded drivers. Click them and select**Disable device** .

![Disable device through Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-1.jpg)

 When disabling hardware devices, make sure you no longer need them, as you might be causing issues within your system.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
### 2\. Install 64-Bit Windows

 There are a few [differences between 32-bit and 64-bit Windows](https://www.makeuseof.com/tag/difference-32-bit-64-bit-windows/) , including the amount of Hardware Reserved Memory. As we’ve mentioned, a 64-bit Windows assigns less RAM to the Hardware Reserved Memory, so updating from 32-bit to the 64-bit Windows version should reduce the amount of reserved memory.

 If you’re not sure which version you’re currently running, press**Windows key + I** to bring up the Settings menu. There, head to**System** , scroll to the bottom of the page, and click**About** . Check the value next to**System type** to check if your system is 32 or 64-bit.

![Check Windows version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-64bit-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

### 3\. Set a Preferred GPU

 There’s a chance your computer has two GPUs, and one of them is better when managing high-intensive graphics tasks. Instead of using the integrated graphics card to process complex tasks, you should [choose a preferred GPU for games or editing software](https://www.makeuseof.com/windows-10-choose-preferred-gpu/) to reduce the memory reserved by Windows.

### 4\. Run the Hardware and Devices Troubleshooter

 If one of your connected devices isn’t working properly, Windows might reserve more of your system memory. To fix it, you should run Windows’ Hardware and Devices troubleshooter. Here’s how you can do it:

1. Launch Command Prompt with administrative rights.
2. Type**msdt.exe -id DeviceDiagnostic** and press**Enter** .
3. In the Hardware and Devices window, click**Advanced** , and check the**Apply repairs automatically** option.
4. Click**Next** to start the process.

![Running the hardware and devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hardware-devices-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->

### 4\. Edit Your System Configuration

 In general, Windows is the only one deciding how much of your system memory it reserves. However, you can control the maximum amount of reserved memory through System Configuration. Here’s how you can do it:

1. Press**Win + R** to bring up a Run box.
2. Type**msconfig** and press**Enter** .
3. In the System Configuration window, open the**Boot** tab.
4. Click**Advanced options** .
5. Check**Maximum memory** and edit the value.
6. Click**OK** .

![Change boot settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/boot-settings-1.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-activity-recording.techidaily.com/new-the-screen-savers-strategy-top-recording-tactics/"><u>[New] The Screen Saver's Strategy  Top Recording Tactics</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-expert-advice-to-recover-missing-thumbnails-from-videos-for-2024/"><u>[Updated] Expert Advice to Recover Missing Thumbnails From Videos for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-social-media-summit-twitters-top-10-tweets/"><u>[Updated] Social Media Summit  Twitter’s Top 10 Tweets</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-customization-embedding-text-in-youtube-cards/"><u>[Updated] Unlocking Customization  Embedding Text in YouTube Cards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-10-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 10 Blue Screen Error</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-elevate-your-cinematography-mastering-transitions-in-kinemaster/"><u>2024 Approved  Elevate Your Cinematography  Mastering Transitions in Kinemaster</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-iphoneandroid-integrating-playlists-into-your-fb-music/"><u>2024 Approved  IPhone/Android  Integrating Playlists Into Your FB Music</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-practical-solutions-for-gpeditmsc-not-found-crisis/"><u>3 Practical Solutions for Gpedit.msc Not Found Crisis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-make-the-windows-terminal-your-default-terminal-app/"><u>3 Ways to Make the Windows Terminal Your Default Terminal App</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-infinix-note-30-vip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-10-step-guide-to-windows-health-reports/"><u>A 10-Step Guide to Windows Health Reports</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-and-understanding-windows-component-services-interface/"><u>Accessing & Understanding Windows Component Services Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-11-safe-mode-6-routes-covered/"><u>Accessing Windows 11 Safe Mode: 6 Routes Covered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-another-app-uses-same-speaker-windows-edition/"><u>Addressing Error: Another App Uses Same Speaker, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-glitch-nvidias-x0001-on-windows-w11/"><u>Addressing Glitch: Nvidia's X0001 on Windows W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-gpu-thermal-spikes-during-play/"><u>Addressing GPU Thermal Spikes During Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steams-offline-content-servers-problem-in-windows/"><u>Addressing Steam's Offline Content Servers Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/app-aesthetics-overshadowing-computational-efficiency-issues/"><u>App Aesthetics Overshadowing Computational Efficiency Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-printer-frustration-in-the-latest-os-win11-guide/"><u>Avoid Printer Frustration in the Latest OS: Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-unwanted-updates-in-windows-11-with-proactive-measures/"><u>Avoid Unwanted Updates in Windows 11 with Proactive Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-immediate-help-tool-on-windows-modern-os/"><u>Beginning Immediate Help Tool on Windows Modern OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-the-basics-excellent-replacements-for-windows-11-defaults/"><u>Beyond the Basics: Excellent Replacements for Windows 11 Defaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-organization-in-windows-discover-5-key-folder-insights/"><u>Boost Organization in Windows - Discover 5 Key Folder Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-security-with-vbox-turn-onoff-secure-boot-and-tpm/"><u>Boost Security with VBox: Turn On/Off Secure Boot & TPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-computers-space-on-windows-using-these-free-tools/"><u>Boost Your Computer's Space on Windows Using These Free Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-outlook-speed-quick-tricks-for-win/"><u>Boost Your Outlook Speed: Quick Tricks for WIN</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/enhance-your-audio-visual-experience-with-these-6-apps-for-2024/"><u>Enhance Your Audio-Visual Experience with These 6 Apps for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-focusrite-scarlett-2i4-drivers-installed-on-windows-pcs/"><u>Get Your Focusrite Scarlett 2I4 Drivers Installed on Windows PCs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/googles-next-big-thing-the-pixel-fold-2-revealed-price-predictions-release-schedule-and-exciting-rumored-features/"><u>Google's Next Big Thing: The Pixel Fold 2 Revealed! Price Predictions, Release Schedule & Exciting Rumored Features</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-navigating-the-maze-a-comprehensive-guide-to-mov-capture-in-win10/"><u>In 2024, Navigating the Maze  A Comprehensive Guide to MOV Capture in Win10</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-revealing-the-best-of-both-worlds-1-tiktoks-on-twitter/"><u>In 2024, Revealing the Best of Both Worlds  #1 TikToks on Twitter</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-gaomon-pd1560-touchscreen-drawing-pad-evaluation-the-ideal-graphic-artists-companion/"><u>In-Depth Gaomon PD1560 Touchscreen Drawing Pad Evaluation: The Ideal Graphic Artist's Companion</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-combine-multiple-avi-files-into-one-top-10-free-avi-merger-tools/"><u>New 2024 Approved Combine Multiple AVI Files Into One Top 10 Free AVI Merger Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719301459575-the-keys-to-free-jumpstart-your-pc-with-unbeatable-windows-11-612lifetime/"><u>The Keys to Free: Jumpstart Your PC with Unbeatable Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-low-cost-cameras-list/"><u>The Ultimate Low-Cost Cameras List</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-guide-9-premier-video-translators-for-accurate-global-communication-for-2024/"><u>Ultimate Guide  9 Premier Video Translators for Accurate Global Communication for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719241162172-update-drivers-make-sure-your-graphics-card-drivers-are-up-to-date-for-optimal-performance/"><u>Update Drivers: Make Sure Your Graphics Card Drivers Are up to Date for Optimal Performance.</u></a></li>
</ul></div>
