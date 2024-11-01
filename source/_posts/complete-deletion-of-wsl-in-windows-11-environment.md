---
title: Complete Deletion of WSL in Windows 11 Environment
date: 2024-10-28T17:56:22.345Z
updated: 2024-11-01T17:18:02.947Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Complete Deletion of WSL in Windows 11 Environment
excerpt: This Article Describes Complete Deletion of WSL in Windows 11 Environment
keywords: WinWSLDeletionProcess,RemoveWSLEnvWindows11,DeleteWSLinWin11OS,EradicateWSLWindows11,EliminateWSL11Windows,WSLRemovalStepsWindows,CompletelyRemoveWSLWin11
thumbnail: https://thmb.techidaily.com/f0f1add4f06bedd9b4441c0d9e38e221d87204ef26ea2cde0e10ae3ca9b9c9f6.jpg
---

## Complete Deletion of WSL in Windows 11 Environment

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532">
  <img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134248/18498" target="_top" id="2134248">
  <img src="//a.impactradius-go.com/display-ad/18498-2134248" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134248/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068439/7443" target="_top" id="2068439">
  <img src="//a.impactradius-go.com/display-ad/7443-2068439" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068439/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-hero-vs-hero-a-technological-comparison-for-2024/"><u>[New] Hero Vs Hero A Technological Comparison for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pixelprodigy-smart-ai-driven-photo-edits/"><u>2024 Approved PixelProdigy Smart AI-Driven Photo Edits</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-the-art-of-flawless-audio-capture-mic-free/"><u>2024 Approved The Art of Flawless Audio Capture, Mic-Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-time-before-next-login-after-failure-in-win-1011/"><u>Customizing Time Before Next Login After Failure in Win 10/11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/delight-in-these-top-10-insta-memes-that-spark-joy-and-sobs/"><u>Delight in These Top 10 Insta Memes That Spark Joy & Sobs</u></a></li>
<li><a href="https://win-studio.techidaily.com/how-to-safely-perform-system-backups-on-your-windows-server-2008-instance/"><u>How to Safely Perform System Backups on Your Windows Server 2008 Instance</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/instantly-share-selfies-the-step-by-step-walkthrough/"><u>Instantly Share Selfies The Step-by-Step Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-printer-network-setup-a-windows-guide/"><u>Mastering Printer Network Setup: A Windows Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/max-networks-hottest-series-and-programmes-of-the-moment/"><u>Max Network’s Hottest Series and Programmes of The Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-bsod-interrupt-exception-troubleshoot/"><u>Preventing BSOD: Interrupt Exception Troubleshoot</u></a></li>
<li><a href="https://buynow-info.techidaily.com/real-world-testing-of-asus-rt-ac88u-a-game-changing-wireless-router-evaluation/"><u>Real World Testing of Asus RT-AC88U - A Game Changing Wireless Router Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-pc-7-tricks-to-revitalize-windows-update/"><u>Reclaim Your PC: 7 Tricks to Revitalize Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconfigure-win11s-subnet-settings/"><u>Reconfigure Win11's Subnet Settings</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/revolutionize-your-learning-journey-with-mondly-app/"><u>Revolutionize Your Learning Journey with Mondly App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-new-dimensions-of-windows-11-usefulness/"><u>Unlock New Dimensions of Windows 11 Usefulness</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    