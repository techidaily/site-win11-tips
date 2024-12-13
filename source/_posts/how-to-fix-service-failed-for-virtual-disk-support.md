---
title: How to Fix Service Failed for Virtual Disk Support
date: 2024-12-09T01:20:25.693Z
updated: 2024-12-13T02:03:22.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Service Failed for Virtual Disk Support
excerpt: This Article Describes How to Fix Service Failed for Virtual Disk Support
keywords: Fixing Virtual Disk Errors,Resolving VDS Issues,Correcting Disks Failure,Addressing VDS Service Fault,Solutions for VDS Support Problems,Troubleshooting VDS Loss,Fixing Failed Virtual Disk Support
thumbnail: https://thmb.techidaily.com/37b56893bb3f0e1aebfa5ebfbca34f8037db29ed8a731b991532309ef68ee1fd.jpg
---

## How to Fix Service Failed for Virtual Disk Support

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-no-frills-screensaver-windows-compatible-for-2024/"><u>[New] No Frills Screensaver - Windows Compatible for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-10-best-lightroom-alternatives-free-and-paid/"><u>[Updated] 2024 Approved 10 Best Lightroom Alternatives [Free & Paid]</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-boost-efficiency-learning-free-timers-functionality-for-2024/"><u>[Updated] Boost Efficiency Learning FREE Timers' Functionality for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-gonetflixgo-master-screenrecording-on-mac-with-ease-and-excellence/"><u>[Updated] In 2024, GoNetflixGo Master ScreenRecording on Mac, With Ease & Excellence</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-premier-choices-high-quality-free-screen-recorder-software-for-2024/"><u>[Updated] Premier Choices High-Quality Free Screen Recorder Software for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/bridging-worlds-of-sound-and-social-media-the-genesis-of-project-boombox/"><u>Bridging Worlds of Sound and Social Media: The Genesis of Project Boombox</u></a></li>
<li><a href="https://some-approaches.techidaily.com/comprehensive-guide-updating-wonderfox-dvd-ripper-to-newest-release/"><u>Comprehensive Guide: Updating WonderFox DVD Ripper to Newest Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decision-making-guide-for-choosing-right-windows-n-edition/"><u>Decision-Making Guide for Choosing Right Windows N Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-to-tackle-disallowed-sign-ins-on-win/"><u>Essential Strategies to Tackle Disallowed Sign-Ins on Win</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-photos-from-honor-by-fonelab-android-recover-photos/"><u>How to get back lost photos from Honor .</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-power-schemes-back-to-windows-default/"><u>How To Reset Power Schemes Back to Window's Default</u></a></li>
<li><a href="https://fox-search.techidaily.com/mastering-the-art-of-cryptocurrency-trading-insights-from-yl-computing-and-yl-software/"><u>Mastering the Art of Cryptocurrency Trading: Insights From YL Computing and YL Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-disk-space-via-archiving-in-windows-11/"><u>Maximize Disk Space via Archiving in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-matters-quick-ways-to-check-your-pcs-ram-on-windows/"><u>Memory Matters: Quick Ways to Check Your PC's RAM on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-unblock-valorants-in-game-voice-channel-windows/"><u>Quick Steps to Unblock Valorant's In-Game Voice Channel (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surface-studio-2-review-closer-to-the-perfection-in-creativity/"><u>Surface Studio 2 Review: Closer to the Perfection in Creativity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-potential-with-powerrename-tool/"><u>Unleash Windows Potential with PowerRename Tool</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    