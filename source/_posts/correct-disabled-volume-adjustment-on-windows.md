---
title: Correct Disabled Volume Adjustment on Windows
date: 2024-08-16T01:30:11.107Z
updated: 2024-08-17T01:30:11.107Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correct Disabled Volume Adjustment on Windows
excerpt: This Article Describes Correct Disabled Volume Adjustment on Windows
keywords: Fix Windows Sound Levels,Disable Noise Compensation,Tweak Audio Settings Windows,Adjust Windows Volume Bug,Resolve Muted Windows PC,Enhance Windows Hearing Control,Optimize Windows Sounds Playback
thumbnail: https://thmb.techidaily.com/3707ff184ff67962a6b219b0ce3645aba18b53d2162e7b2d2d4b3ce7e2a13800.jpg
---

## Correct Disabled Volume Adjustment on Windows

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The formatting process may take some time, depending on the amount of data on the partition. Once done, restart your computer and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.
7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->

 Once the wizard completes, you will see the partition size has been increased.

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-avoid-boredom-learn-to-shuffle-youtube-lists-for-2024/"><u>[New] Avoid Boredom  Learn to Shuffle YouTube Lists for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-empowering-remote-teams-with-google-meets-whiteboard-features-on-various-devices/"><u>[New] Empowering Remote Teams with Google Meet's Whiteboard Features on Various Devices</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-forgotten-frames-to-captivating-clip-sequences/"><u>[New] From Forgotten Frames to Captivating Clip Sequences</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-essential-guide-to-posting-vimeo-on-instagram/"><u>[New] In 2024, The Essential Guide to Posting Vimeo on Instagram</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-omniview-app-critical-look-over/"><u>[New] OmniView App Critical Look-Over</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-photosynth-pros-a-quick-snapchat-peek/"><u>[New] Photosynth Pros  A Quick Snapchat Peek</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-blurring-the-focus-bokeh-wonders-in-stories/"><u>[Updated] 2024 Approved  Blurring the Focus  Bokeh Wonders in Stories</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-decoding-vimeo-where-creative-videos-meet/"><u>[Updated] 2024 Approved  Decoding Vimeo  Where Creative Videos Meet</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-fundamental-blueprints-to-enhance-facebook-ad-engagement/"><u>[Updated] 2024 Approved  Fundamental Blueprints to Enhance Facebook Ad Engagement</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-capturing-crisp-sound-a-guide-to-superior-audio-recording/"><u>[Updated] In 2024, Capturing Crisp Sound  A Guide to Superior Audio Recording</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-tailored-instagram-filters-a-step-by-step-process/"><u>[Updated] Tailored Instagram Filters  A Step-by-Step Process</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-capture-attention-top-10-grids-for-stunning-pics/"><u>2024 Approved  Capture Attention  Top 10 Grids for Stunning Pics</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-explore-6-alternative-platforms-for-high-quality-youtube-graphics/"><u>2024 Approved  Explore 6 Alternative Platforms for High-Quality YouTube Graphics</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-hilarityhub-design-memes-with-ease-and-speed/"><u>2024 Approved  HilarityHub  Design Memes with Ease and Speed</u></a></li>
<li><a href="https://extra-hints.techidaily.com/audience-engagement-the-most-excellent-webcams-for-podcasts-for-2024/"><u>Audience Engagement  The Most Excellent Webcams for Podcasts for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-photos-from-a2-by-fonelab-android-recover-photos/"><u>Best Android Data Recovery - Retrieve Lost Photos from A2.</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/beyond-words-the-power-of-foreign-languages-unveiled/"><u>Beyond Words: The Power of Foreign Languages Unveiled</u></a></li>
<li><a href="https://extra-resources.techidaily.com/bring-a-chuckle-to-life-generating-text-memes-for-2024/"><u>Bring a Chuckle to Life  Generating Text Memes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-addressing-non-installed-hdd-in-windows-11/"><u>Comprehensive Guide to Addressing Non-Installed HDD in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-windows-11-taskbar-end-task-ability/"><u>Configuring Windows 11 Taskbar: End Task Ability</u></a></li>
<li><a href="https://extra-information.techidaily.com/craft-a-compelling-metaverse-presence-with-these-tools/"><u>Craft a Compelling Metaverse Presence with These Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-universe-awaits-essential-key-collectors-612lifetime-windows-11-sale/"><u>Digital Universe Awaits: Essential Key Collector's $6.12/Lifetime Windows 11 Sale</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-configuring-a-triplet-of-tiles-in-windows-11-ui/"><u>Dive Deep: Configuring a Triplet of Tiles in Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-to-enhance-windows-high-dpi-scaling/"><u>Effective Fixes to Enhance Windows High DPI Scaling</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/essential-strategies-for-ppt-on-google-meet-laptopiosandroid/"><u>Essential Strategies for PPT on Google Meet  Laptop/iOS/Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-your-way-through-uptime-verification-in-windows-11-with-these-tips/"><u>Guide Your Way Through Uptime Verification in Windows 11 with These Tips</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-beat-coffee-stain-effects-with-ioss-complimentary-red-eye-fix-app/"><u>In 2024, Beat Coffee Stain Effects with iOS's Complimentary Red-Eye Fix App</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-capturing-the-unseen-9-must-have-camgear-for-aspiring-vloggers/"><u>In 2024, Capturing the Unseen  9 Must-Have CamGear for Aspiring Vloggers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-inshot-alternatives-for-laptop-editors/"><u>In 2024, Inshot Alternatives for Laptop Editors</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovation-unbound-ais-impact-on-windows-tech-advances/"><u>Innovation Unbound: AI's Impact on Windows Tech Advances</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fix-for-windows-11s-erroneous-update-code-0x80246007/"><u>Mastering Fix for Windows 11'S Erroneous Update Code 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-memos-best-tablet-apps-for-windows/"><u>Mastering Memos: Best Tablet Apps for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigate-malwares-memory-footprint-in-your-system/"><u>Mitigate Malware's Memory Footprint in Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-woes-with-simple-fixes/"><u>Navigate Through Windows Woes with Simple Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-shared-device-conflicts-in-win11/"><u>Navigating Shared Device Conflicts in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-storage-estimation-using-powershell/"><u>Navigating Windows Storage Estimation Using PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimized-glare-the-top-software-picks-for-windows-multitouch-monitors/"><u>Optimized Glare: The Top Software Picks for Windows Multitouch Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/practicality-meets-elegance-with-the-new-asus-s15-oled/"><u>Practicality Meets Elegance with the New Asus S15 OLED</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-your-digital-footprint-windows-login-guide/"><u>Removing Your Digital Footprint: Windows Login Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reveal-the-hidden-conceal-for-clarity-in-windows-11/"><u>Reveal the Hidden, Conceal for Clarity in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revisiting-user-permissions-for-regular-windows-users/"><u>Revisiting User Permissions for Regular Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/set-thumbnail-dimensions-on-desktop-pics-w11/"><u>Set Thumbnail Dimensions on Desktop Pics W11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/y-film-maker/"><u>Snappy Film Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-remedy-windows-11s-afc-camera-bug/"><u>Steps to Remedy Windows 11'S AFC Camera Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reactivate-frozen-resource-monitors-in-windows-11/"><u>Strategies to Reactivate Frozen Resource Monitors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-storage-with-ntfs-compression-in-win11/"><u>Streamline Storage with NTFS Compression in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-faulty-drives-in-windows/"><u>Streamlining Faulty Drives in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedy-dealing-with-roblox-error-code-262/"><u>Swift Remedy: Dealing with Roblox Error Code 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taskbar-evolution-a-timeline-from-85-to-present/"><u>Taskbar Evolution: A Timeline From '85 To Present</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-pc-doesnt-meet-game-bar-issue/"><u>Troubleshooting PC Doesn't Meet Game Bar Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-off-smartscreen-protection-in-win11-and-11/"><u>Turning Off SmartScreen Protection in Win11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-list-best-windows-photo-organizers/"><u>Ultimate List: Best Windows Photo Organizers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncloaking-stealthy-storage-issues-on-windows/"><u>Uncloaking Stealthy Storage Issues on WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-power-down-on-windows-machines/"><u>Understanding Power Down on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-viewing-9-methods-to-sharpen-video-playback-on-windows/"><u>Uninterrupted Viewing: 9 Methods to Sharpen Video Playback on Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/whats-your-potential-income-from-youtube-sponsored-videos-in-2024/"><u>What's Your Potential Income From YouTube Sponsored Videos, In 2024</u></a></li>
</ul></div>
