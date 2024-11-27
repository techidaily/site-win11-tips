---
title: Controlling Clock/Date Visibility in Windows 11 Bar
date: 2024-11-21T17:18:33.088Z
updated: 2024-11-27T17:25:37.008Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Clock/Date Visibility in Windows 11 Bar
excerpt: This Article Describes Controlling Clock/Date Visibility in Windows 11 Bar
keywords: Win11 Clock Control,Date Visibility Windows,Window Settings Adjust,Time Display Windows 11,Clock Configurations Windows,Windows Bar Time Change,Windows 11 Date Manager
thumbnail: https://thmb.techidaily.com/265c34a9ea730206243923e3674c50a6adee1664031b51ad4dc762eeccdfd025.jpg
---

## Controlling Clock/Date Visibility in Windows 11 Bar

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-expertly-curated-top-15-android-virtualization-tools-macpc/"><u>[New] 2024 Approved Expertly Curated Top 15 Android Virtualization Tools (Mac/PC)</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-10-best-free-video-conferencing-with-screen-sharing/"><u>[New] In 2024, 10 Best Free Video Conferencing With Screen Sharing</u></a></li>
<li><a href="https://win-ratings.techidaily.com/sandisk-backup-manager/"><u>絕無價值的優良替代品: SanDisk Backup Manager自由版本</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-adding-kali-to-your-windows-os/"><u>Expert Advice for Adding Kali to Your Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-mastering-windows-customization-via-alomware/"><u>Expert Tips for Mastering Windows Customization via AlomWare</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-ensure-stable-playback-of-palworld-without-interruptions-on-your-laptop-or-pc/"><u>How to Ensure Stable Playback of Palworld Without Interruptions on Your Laptop or PC</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-google-pixel-fold-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Google Pixel Fold in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-perform-a-hard-reset-on-samsung-televisions/"><u>How to Perform a Hard Reset on Samsung Televisions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-b-footage-techniques-for-creating-engaging-video-content/"><u>In 2024, B-Footage Techniques for Creating Engaging Video Content</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-top-15-youtube-channels-for-stock-market-to-follow/"><u>In 2024, Top 15 YouTube Channels for Stock Market to Follow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-text-customization-using-win-11s-snip-tool/"><u>In-Depth Text Customization Using Win 11'S Snip Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventive-measures-for-unrecognized-hard-drives-in-windows-11-systems/"><u>Preventive Measures for Unrecognized Hard Drives in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-stop-video-driver-restarts/"><u>Quick Guide to Stop Video Driver Restarts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-cybersecurity-adding-trusted-websites-in-windows-11/"><u>Streamline Cybersecurity: Adding Trusted Websites in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-oppo-reno-10-pro-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Oppo Reno 10 Pro 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-must-knows-thriving-as-a-manager-free-on-your-windows-pc/"><u>Top 10 Must-Knows: Thriving as a Manager, Free on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-to-clear-server-not-found-in-apex-legends-(156-chars/"><u>Top Strategies to Clear Server Not Found in Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-tips-fixing-microphone-issues-with-your-sony-wh-1000xm3-or-wh-1000xm4-headphones/"><u>Troubleshooting Tips: Fixing Microphone Issues with Your Sony WH-1000XM3 or WH-1000XM4 Headphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-users-guide-6-premier-activity-tracker-tools/"><u>Win Users' Guide: 6 Premier Activity Tracker Tools</u></a></li>
</ul></div>

