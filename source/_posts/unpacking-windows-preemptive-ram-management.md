---
title: Unpacking Windows' Preemptive RAM Management
date: 2024-10-23T17:54:48.817Z
updated: 2024-10-26T17:37:18.925Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unpacking Windows' Preemptive RAM Management
excerpt: This Article Describes Unpacking Windows' Preemptive RAM Management
keywords: RAM Control in Win,Window RAM Prefere,RAM Optimization Win,Preemptive Ram Win,Managing RAM Win,Windows RAM Handling,Memory Management Win
thumbnail: https://thmb.techidaily.com/ef8036d25906bf8bc672642e846b12e7bf455ea76b0df7385d290b38eb25840e.jpg
---

## Unpacking Windows' Preemptive RAM Management

 There’s no doubt that when it comes to a computer's performance, one of the most important roles is played by RAM (or Random Access Memory). However, Windows can’t use the amount of RAM mentioned in your computer specifications. This is because some of it is “reserved” by your system.

 But what is Hardware Reserved Memory? Can you check how much memory is reserved on your computer and can you adjust the value?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Hardware Reserved Memory?

 Windows saves a part of the available RAM, so your hardware components have enough resources to work properly. This is known as Hardware Reserved Memory, and Windows allocates it to hardware devices such as the network adapter, Bluetooth devices, sound card, and GPU, among other hardware devices.

 This way, Windows makes sure these components function as expected when you need them.

## How to Check Your Hardware Reserved Memory

 Windows makes it quite easy to check the amount of hardware reserved memory. Press**Ctrl + Shift + Esc** to bring up Task Manager. There, open the**Performance** tab and select**Memory** . Check the value next to**Hardware reserved** .

![Check hardware reserved memory on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-reserved-memory-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Your PC's Hardware Reserved Memory Impacts Performance

 If your system allocates too much of the RAM to the Hardware Reserved Memory, it will negatively impact your computer performance. Especially if you don’t have a lot of RAM to start with.

 Also, certain hardware components, such as high-end Graphics Processing Units or sound cards, need more memory to manage their assigned tasks. Moreover, Windows uses reserved memory to store drivers for peripheral devices, even if you don’t use them that often.

 If Windows reserves too much of your RAM, you might deal with longer boot-up times or even Windows crashing and freezing as it doesn’t have enough resources to keep all processes running.

## How to Adjust the Hardware Reserved Memory on Windows

 In general, the value for Hardware Reserved Memory should be a few hundred megabytes. The 32-bit version of Windows can reserve up to 3.5 GB of RAM, while the 64-bit system usually needs around 1GB. If the value is around a couple of GB, or even more, you’ll have to adjust the value. Fortunately, Windows has a few ways you can do it.

### 1\. Update Your Drivers

 Outdated or corrupt[computer drivers](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) will increase the amount of memory Windows reserves to keep your hardware devices running smoothly. Updating the drivers, especially the GPU drivers, might help Windows reduce the amount of reserved memory.

 Additionally, it might help to disable drivers for devices that you no longer use, as Windows will keep managing them. Launch Device Manager, go through the list, then locate any unneeded drivers. Click them and select**Disable device** .

![Disable device through Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-1.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1030129/11832" target="_top" id="1030129">
  <img src="//a.impactradius-go.com/display-ad/11832-1030129" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1030129/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When disabling hardware devices, make sure you no longer need them, as you might be causing issues within your system.

### 2\. Install 64-Bit Windows

 There are a few[differences between 32-bit and 64-bit Windows](https://www.makeuseof.com/tag/difference-32-bit-64-bit-windows/) , including the amount of Hardware Reserved Memory. As we’ve mentioned, a 64-bit Windows assigns less RAM to the Hardware Reserved Memory, so updating from 32-bit to the 64-bit Windows version should reduce the amount of reserved memory.

 If you’re not sure which version you’re currently running, press**Windows key + I** to bring up the Settings menu. There, head to**System** , scroll to the bottom of the page, and click**About** . Check the value next to**System type** to check if your system is 32 or 64-bit.

![Check Windows version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-64bit-1.jpg)

### 3\. Set a Preferred GPU

 There’s a chance your computer has two GPUs, and one of them is better when managing high-intensive graphics tasks. Instead of using the integrated graphics card to process complex tasks, you should[choose a preferred GPU for games or editing software](https://www.makeuseof.com/windows-10-choose-preferred-gpu/) to reduce the memory reserved by Windows.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. Run the Hardware and Devices Troubleshooter

 If one of your connected devices isn’t working properly, Windows might reserve more of your system memory. To fix it, you should run Windows’ Hardware and Devices troubleshooter. Here’s how you can do it:

1. Launch Command Prompt with administrative rights.
2. Type**msdt.exe -id DeviceDiagnostic** and press**Enter** .
3. In the Hardware and Devices window, click**Advanced** , and check the**Apply repairs automatically** option.
4. Click**Next** to start the process.

![Running the hardware and devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hardware-devices-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529">
  <img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
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

### 5\. Restore the BIOS to Its Default Settings

 You can use your computer for years without thinking of BIOS. But it plays an important role in your computer’s stability. If you notice your system assigns too many resources to the Hardware Reserved Memory, the problem might be caused by improper BIOS settings. In this case, reverting it to its default settings should fix the issue.

 First, press**Del** or**F2** to enter BIOS during the Windows startup screen. From the bottom of the page, click Load Defaults (or Restore Settings) and confirm the action. Then, exit BIOS, restart your computer, and check the Hardware Reserved Memory value.

 If you can’t access BIOS during the startup screen, there are more[methods you could try to enter BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) and reset it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-examining-the-unique-features-of-youtubes-and-dailymentions/"><u>[New] 2024 Approved Examining the Unique Features of YouTubes and DailyMentions</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-9-solutions-to-facebook-video-black-screen-issues-on-chromesafarifirefox/"><u>[New] 9 Solutions to Facebook Video Black Screen Issues on Chrome/Safari/Firefox</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-crafting-snug-winter-atmospheres-for-engaging-online-content/"><u>[New] Crafting Snug Winter Atmospheres for Engaging Online Content</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-top-6-youtube-outros-made-easy-and-free-guide/"><u>[New] In 2024, Top 6 YouTube Outros Made Easy & FREE (Guide)</u></a></li>
<li><a href="https://win-rankings.techidaily.com/1-seamless-steps-preserving-your-iphone-conversations-with-5-simple-archiving-techniques/"><u>1. Seamless Steps: Preserving Your iPhone Conversations with 5 Simple Archiving Techniques</u></a></li>
<li><a href="https://fox-metric.techidaily.com/windows-1011-bitlocker/"><u>专为 Windows 10/11 设计的顶级 Bitlocker 救回工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-and-irreversible-file-removal-creating-a-customizable-desktop-bin-windows-11/"><u>Effortless and Irreversible File Removal: Creating a Customizable Desktop Bin (Windows 11)</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-exploring-the-metaverse-and-omniverse-distinctions/"><u>In 2024, Exploring the Metaverse and Omniverse Distinctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-operation-failed-on-win-1011-systems/"><u>Preventing 'Operation Failed' On Win 10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-directx-download-errors-on-pcs/"><u>Rectifying DirectX Download Errors on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-onedrive-for-microsoft-live-users/"><u>Setting Up OneDrive for Microsoft Live Users</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/top-rated-mobile-streaming-format-player-for-macos-fixed-issue-with-movie-files/"><u>Top Rated Mobile Streaming Format Player for macOS: Fixed Issue with Movie Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-defender-log-cleanse-a-practical-approach-for-users/"><u>Win 11'S Defender Log Cleanse: A Practical Approach for Users</u></a></li>
</ul></div>

