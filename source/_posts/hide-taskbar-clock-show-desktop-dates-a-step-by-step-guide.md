---
title: "Hide Taskbar Clock, Show Desktop Dates: A Step-by-Step Guide"
date: 2025-02-11T21:20:18.006Z
updated: 2025-02-15T23:49:33.395Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Hide Taskbar Clock, Show Desktop Dates: A Step-by-Step Guide"
excerpt: "This Article Describes Hide Taskbar Clock, Show Desktop Dates: A Step-by-Step Guide"
keywords: Taskbar Hide Tips,Clock Hide Methods,Desktop Date View,Taskbar Control Steps,Windows Shortcut Guide,Customize Taskbar Options,Manage Display Settings
thumbnail: https://thmb.techidaily.com/d63b36b5c666fd9de9fccce4561bf07299ad84d3949b489b0214f6877268e346.png
---

## Hide Taskbar Clock, Show Desktop Dates: A Step-by-Step Guide

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-unlocking-videos-on-fb-with-2023-mobile-utility/"><u>[New] 2024 Approved Unlocking Videos on FB with 2023 Mobile Utility</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/assessing-the-build-and-speed-of-netgears-powerline-1200-when-substantial-architecture-impacts-network-efficiency/"><u>Assessing The Build And Speed Of Netgear's Powerline 1200: When Substantial Architecture Impacts Network Efficiency</u></a></li>
<li><a href="https://technical-tips.techidaily.com/beyond-just-portables-unveiling-the-extended-impact-of-m3-apple-silicon-on-tech-innovation/"><u>Beyond Just Portables: Unveiling the Extended Impact of M3 Apple Silicon on Tech Innovation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-stubborn-windows-printers-a-swift-guide/"><u>Eliminating Stubborn Windows Printers: A Swift Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-entryways-four-slick-steps-to-disable-a-user-on-win11/"><u>Eradicate Entryways: Four Slick Steps to Disable a User on Win11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-meizu-21-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-the-taskbar-bigger-or-smaller-on-windows-11/"><u>How to Make the Taskbar Bigger or Smaller on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-xiaomi-13t-pro-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Xiaomi 13T Pro Phone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-master-the-art-of-zooming-in-snapchat-photos-and-videos/"><u>In 2024, Master the Art of Zooming in Snapchat Photos & Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-top-10-igtv-channels-you-should-start-following/"><u>In 2024, Top 10 IGTV Channels You Should Start Following</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-driver-verifier-via-control-panel-on-w11/"><u>Launching Driver Verifier via Control Panel on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-basic-window-aids-for-beginners/"><u>Mastering Basic Window Aids for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-procedure-for-restoring-icons-on-windows-11s-search-bar/"><u>The Procedure for Restoring Icons on Windows 11'S Search Bar</u></a></li>
</ul></div>

