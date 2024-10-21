---
title: "Transitioning Smoothly: Set Up Windows Subsystem for Linux"
date: 2024-10-19T20:46:05.898Z
updated: 2024-10-20T22:11:58.778Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Transitioning Smoothly: Set Up Windows Subsystem for Linux"
excerpt: "This Article Describes Transitioning Smoothly: Set Up Windows Subsystem for Linux"
keywords: WSL Setup Guide,WinLinux Integration,Windows-Linux Transition,WSL Installation Steps,Linux on Windows System,Enhancing PC with WSL,Streamlining Windows for Linux
thumbnail: https://thmb.techidaily.com/8b36213cf3c4388b8515bed526f0d42f540b1ba9bd34731fb80416cf28c2a508.jpg
---

## Transitioning Smoothly: Set Up Windows Subsystem for Linux

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

## How to Enable Windows Subsystem for Linux

 In order to install the Linux bash shell on Windows 10, you first have to enable Windows Subsystem for Linux.

 You’ll know if WSL isn't enabled because you’ll run into the error: “The Windows Subsystem for Linux optional component is not enabled. Please enable it and try again.”

 Here’s how to enable WSL in Windows 10:

 You first need to get into Windows **Programs and Features**.

1. Open Windows 10 **Settings** and select **Apps**.
2. On the right side of the window, under **Related settings**, click on **Programs and Features**.

![Programs and Features option under the Related settings section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/program-and-features-option-in-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-unmasking-falsified-follower-fabrications-on-feeds-for-2024/"><u>[New] Unmasking Falsified Follower Fabrications on Feeds for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-trailblazing-towards-top-instagram-minds-a-niche-journey/"><u>[Updated] 2024 Approved Trailblazing Towards Top Instagram Minds A Niche Journey</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-discovering-the-ins-and-outs-of-youtube-shorts-capital/"><u>[Updated] In 2024, Discovering the Ins and Outs of YouTube Shorts Capital</u></a></li>
<li><a href="https://fox-that.techidaily.com/10-effective-strategies-to-correct-persistent-touch-malfunctions-on-your-iphone/"><u>10 Effective Strategies to Correct Persistent Touch Malfunctions on Your iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aac-m4r-mp3-moveavi/"><u>AAC M4R 음성 파일에서 MP3로의 무료 인터넷 전송 변환: MoveAVi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-gratuite-des-images-bmp-vers-ligne-movavi/"><u>Conversion Gratuite Des Images BMP Vers Ligne - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-video-converter-convert-mka-and-aac-files-using-movavi/"><u>Free Online Video Converter - Convert MKA & AAC Files Using Movavi</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-vivo-y78-5g-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to Vivo Y78 5G Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-twitters-videography-policy-including-aspect-ratios-is-crucial/"><u>In 2024, Twitter's Videography Policy Including Aspect Ratios Is Crucial</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/movavi-audio-converter-seamlessly-switching-between-flac-and-alac-formats/"><u>Movavi Audio Converter: Seamlessly Switching Between FLAC and ALAC Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-swf-file-transformation-no-cost-easy-steps-by-movavi/"><u>Online SWF File Transformation: No Cost, Easy Steps by Movavi</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/speak-and-stun-on-snapchat-voice-change-made-simple/"><u>Speak and Stun on Snapchat Voice Change Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windowshoz-atlagos-kepernyokep-keszitesi-rendszer-movavi-17-edekot-legjobb-gyermeki-szemugyek-vedoi/"><u>Windowshoz: Átlagos Képernyőkép Készítési Rendszer Movavi, 17 Edeköt Legjobb Gyermeki Szemügyek Védői</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    