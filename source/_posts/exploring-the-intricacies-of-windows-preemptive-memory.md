---
title: Exploring the Intricacies of Windows' Preemptive Memory
date: 2024-11-30T20:57:54.085Z
updated: 2024-12-06T23:43:35.925Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exploring the Intricacies of Windows' Preemptive Memory
excerpt: This Article Describes Exploring the Intricacies of Windows' Preemptive Memory
keywords: WinMemoryPreemption,MemoryAllocationWin,WindowsPreemptiveRAM,RAMManagementWindows,PreemptiveMemWin,OSMemorySchedWin,SchedulerMemoryWin
thumbnail: https://thmb.techidaily.com/e12cb801e0d6f6813ed277d29658e5821adadea3db742df23467e5bb2d5168a7.jpg
---

## Exploring the Intricacies of Windows' Preemptive Memory

 There’s no doubt that when it comes to a computer's performance, one of the most important roles is played by RAM (or Random Access Memory). However, Windows can’t use the amount of RAM mentioned in your computer specifications. This is because some of it is “reserved” by your system.

 But what is Hardware Reserved Memory? Can you check how much memory is reserved on your computer and can you adjust the value?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is Hardware Reserved Memory?

 Windows saves a part of the available RAM, so your hardware components have enough resources to work properly. This is known as Hardware Reserved Memory, and Windows allocates it to hardware devices such as the network adapter, Bluetooth devices, sound card, and GPU, among other hardware devices.

 This way, Windows makes sure these components function as expected when you need them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Your Hardware Reserved Memory

 Windows makes it quite easy to check the amount of hardware reserved memory. Press**Ctrl + Shift + Esc** to bring up Task Manager. There, open the**Performance** tab and select**Memory** . Check the value next to**Hardware reserved** .

![Check hardware reserved memory on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-reserved-memory-1.jpg)

## How Your PC's Hardware Reserved Memory Impacts Performance

 If your system allocates too much of the RAM to the Hardware Reserved Memory, it will negatively impact your computer performance. Especially if you don’t have a lot of RAM to start with.

 Also, certain hardware components, such as high-end Graphics Processing Units or sound cards, need more memory to manage their assigned tasks. Moreover, Windows uses reserved memory to store drivers for peripheral devices, even if you don’t use them that often.

 If Windows reserves too much of your RAM, you might deal with longer boot-up times or even Windows crashing and freezing as it doesn’t have enough resources to keep all processes running.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Adjust the Hardware Reserved Memory on Windows

 In general, the value for Hardware Reserved Memory should be a few hundred megabytes. The 32-bit version of Windows can reserve up to 3.5 GB of RAM, while the 64-bit system usually needs around 1GB. If the value is around a couple of GB, or even more, you’ll have to adjust the value. Fortunately, Windows has a few ways you can do it.

### 1\. Update Your Drivers

 Outdated or corrupt[computer drivers](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) will increase the amount of memory Windows reserves to keep your hardware devices running smoothly. Updating the drivers, especially the GPU drivers, might help Windows reduce the amount of reserved memory.

 Additionally, it might help to disable drivers for devices that you no longer use, as Windows will keep managing them. Launch Device Manager, go through the list, then locate any unneeded drivers. Click them and select**Disable device** .

![Disable device through Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-1.jpg)

 When disabling hardware devices, make sure you no longer need them, as you might be causing issues within your system.

### 2\. Install 64-Bit Windows

 There are a few[differences between 32-bit and 64-bit Windows](https://www.makeuseof.com/tag/difference-32-bit-64-bit-windows/) , including the amount of Hardware Reserved Memory. As we’ve mentioned, a 64-bit Windows assigns less RAM to the Hardware Reserved Memory, so updating from 32-bit to the 64-bit Windows version should reduce the amount of reserved memory.

 If you’re not sure which version you’re currently running, press**Windows key + I** to bring up the Settings menu. There, head to**System** , scroll to the bottom of the page, and click**About** . Check the value next to**System type** to check if your system is 32 or 64-bit.

![Check Windows version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-64bit-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Set a Preferred GPU

 There’s a chance your computer has two GPUs, and one of them is better when managing high-intensive graphics tasks. Instead of using the integrated graphics card to process complex tasks, you should[choose a preferred GPU for games or editing software](https://www.makeuseof.com/windows-10-choose-preferred-gpu/) to reduce the memory reserved by Windows.

### 4\. Run the Hardware and Devices Troubleshooter

 If one of your connected devices isn’t working properly, Windows might reserve more of your system memory. To fix it, you should run Windows’ Hardware and Devices troubleshooter. Here’s how you can do it:

1. Launch Command Prompt with administrative rights.
2. Type**msdt.exe -id DeviceDiagnostic** and press**Enter** .
3. In the Hardware and Devices window, click**Advanced** , and check the**Apply repairs automatically** option.
4. Click**Next** to start the process.

![Running the hardware and devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hardware-devices-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Keep in mind this will have a direct impact on how much memory Windows reserves to keep your system running properly. Don’t set a value too low to make sure Windows has enough resources.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/ed-decoding-the-core-contrasts-between-youtube-and-dailymention-for-2024/"><u>[Updated] Decoding the Core Contrasts Between YouTube and DailyMention for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-innovative-metaverse-humor-generating-unique-memes/"><u>[Updated] In 2024, Innovative Metaverse Humor Generating Unique Memes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-linking-to-windows-shared-drives/"><u>Android Linking to Windows Shared Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blockchain-against-breaches-7-windows-strategies/"><u>Blockchain Against Breaches: 7 Windows Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boltgun-playtime-maximized-overcoming-computer-delays-in-warhammer-40k/"><u>Boltgun Playtime Maximized: Overcoming Computer Delays in Warhammer 40K</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-by-mastering-task-management-on-a-windows-11-pc/"><u>Boost Productivity by Mastering Task Management on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-copy-pasting-expertise/"><u>Boost Your Typing, Copy-Pasting Expertise</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-latest-hot-deals-on-amazon-for-september-24-featured-by-zdnet/"><u>Discover the Latest Hot Deals on Amazon for September '24 Featured by ZDNet</u></a></li>
<li><a href="https://article-posts.techidaily.com/essential-software-for-animation-and-3d-models-for-2024/"><u>Essential Software for Animation & 3D Models for 2024</u></a></li>
<li><a href="https://win-rankings.techidaily.com/mastering-the-art-of-recording-anywhere-saving-your-favorite-shows-from-amazons-library/"><u>Mastering the Art of Recording Anywhere: Saving Your Favorite Shows From Amazon's Library</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-unlock-the-power-of-animation-converting-videos-into-cartoons-for-2024/"><u>New Unlock the Power of Animation Converting Videos Into Cartoons for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/syncing-social-media-post-videos-on-twitter-and-tumblr-for-2024/"><u>Syncing Social Media Post Videos on Twitter and Tumblr for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-3d-paint-keys/"><u>The Ultimate List of 3D Paint Keys</u></a></li>
<li><a href="https://techidaily.com/unlock-a-disable-iphone-15-plus-without-itunes-or-icloud-by-drfone-ios-unlock-ios-unlock/"><u>Unlock a disable iPhone 15 Plus without itunes or icloud</u></a></li>
</ul></div>

