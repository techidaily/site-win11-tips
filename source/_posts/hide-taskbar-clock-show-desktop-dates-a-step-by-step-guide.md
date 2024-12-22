---
title: "Hide Taskbar Clock, Show Desktop Dates: A Step-by-Step Guide"
date: 2024-12-19T21:43:33.771Z
updated: 2024-12-22T03:53:25.965Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-http.techidaily.com/new-excellence-in-viewing-10-preeminent-iphoneipad-videos/"><u>[New] Excellence in Viewing 10 Preeminent iPhone/iPad Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/eachers-handbook-building-a-successful-youtube-channel-10-must-dos-for-2024/"><u>[New] Teachers' Handbook Building a Successful YouTube Channel – 10 Must-Dos for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-global-stage-excellent-live-soundscape/"><u>[Updated] Global Stage Excellent Live Soundscape</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-top-5-best-3d-intro-makers-for-youtube/"><u>2024 Approved Top 5 Best 3D Intro Makers for YouTube</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-vivo-y78-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Vivo Y78 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/constructing-premium-canon-chrono-images/"><u>Constructing Premium Canon Chrono Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debugging-problematic-code-x0001-on-windows-11-and-11/"><u>Debugging Problematic Code X0001 on Windows 11 & 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-closing-chapter-on-instagram-how-to-discard-account-permanently/"><u>In 2024, Closing Chapter on Instagram How to Discard Account Permanently</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-seamless-browsing-try-these-7-android-adblockers/"><u>In 2024, Seamless Browsing? Try These 7 Android AdBlockers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-non-initialized-drive-recovery-in-windows-os/"><u>Mastering Non-Initialized Drive Recovery in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-phone-link-app-what-is-it-and-how-do-you-use-it/"><u>Microsoft's Phone Link App: What Is It and How Do You Use It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-webp-conversion-alter-chromee-images-on-your-pc/"><u>Prevent WebP Conversion: Alter Chrome’e Images on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-excel-and-windows-notepad-compatibility/"><u>Reconciling: Excel and Windows Notepad Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-through-efficiency-top-7-strategies-with-windows-11/"><u>Skyrocketing Through Efficiency: Top 7 Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spiritual-command-center-unveiled-windows-11-edition/"><u>Spiritual Command Center Unveiled: Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-implement-autodelete-feature-in-winos/"><u>Streamline Your System: Implement AutoDelete Feature in WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-acoustics-your-guide-to-windows-11s-features/"><u>Tailoring Acoustics: Your Guide to Windows 11'S Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-against-wow-fatal-crash-fix-guide/"><u>Winning the Battle Against WOW Fatal Crash: Fix Guide</u></a></li>
</ul></div>

