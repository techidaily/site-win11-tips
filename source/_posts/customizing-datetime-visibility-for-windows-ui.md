---
title: Customizing Date/Time Visibility for Window's UI
date: 2024-12-05T23:59:13.349Z
updated: 2024-12-12T21:26:07.575Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Date/Time Visibility for Window's UI
excerpt: This Article Describes Customizing Date/Time Visibility for Window's UI
keywords: UI DateTime Customization,Windows UI Time Display,Time Control UI Settings,Date View UI Customize,UI Time Visibility Adjust,Windows Calendar Interface,Dynamic Date/Time UI Shift
thumbnail: https://thmb.techidaily.com/655813b140cebedb2250090e80755301611474980aff8421c8d4c222923ee3bc.jpg
---

## Customizing Date/Time Visibility for Window's UI

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
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-techniques.techidaily.com/new-how-to-keep-viewers-engaged-with-these-videos/"><u>[New] How to Keep Viewers Engaged with These Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-premier-select-mac-dvd-editors/"><u>[New] In 2024, Premier Select Mac DVD Editors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exclusive-lineup-all-angle-recorders/"><u>[Updated] Exclusive Lineup All-Angle Recorders</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-math-behind-making-money-youtubes-viewer-insights-for-2024/"><u>[Updated] The Math Behind Making Money YouTube’s Viewer Insights for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/mp4playstation/"><u>対応していないMP4ファイルの視聴方法：PlayStationプラットフォーム全体における解決策</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/comprehensive-guide-to-adding-music-icons-in-instagram-posts-for-2024/"><u>Comprehensive Guide to Adding Music Icons in Instagram Posts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-development-utilizing-windows-11s-dev-drive-tools/"><u>Empowering Development: Utilizing Windows 11'S Dev Drive Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/establishing-an-interactive-update-protocol-in-system-ui/"><u>Establishing an Interactive Update Protocol in System UI</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-google-pixel-fold-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Google Pixel Fold in Minutes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increase-efficiency-the-top-5-win-folder-strategies-to-use-on-windows/"><u>Increase Efficiency: The Top 5 Win Folder Strategies to Use on Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/new-hardware-smart-moves-the-primary-5-procedures-for-new-pc-owners/"><u>New Hardware, Smart Moves: The Primary 5 Procedures for New PC Owners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-edges-webview2-for-better-memory-performance/"><u>Optimizing Edge's WebView2 for Better Memory Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outpace-your-connection-surpassing-100mbps-on-windows-pcs/"><u>Outpace Your Connection: Surpassing 100Mbps on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-nvidias-geforce-experience-error-on-pcs/"><u>Quick Fix for Nvidia's GeForce Experience Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-disabled-deltat-directive-for-windows-sys/"><u>Reinstating Disabled DeltaT Directive for Windows Sys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-addressing-error-code-0x80070522-enhancing-privileges/"><u>Tactics for Addressing Error Code 0X80070522: Enhancing Privileges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-serenity-of-an-unadvertised-windows-start-menu/"><u>The Serenity of an Unadvertised Windows Start Menu</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-picks-for-professional-video-opening-tools-for-2024/"><u>Top Picks for Professional Video Opening Tools for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-excessive-ram-use-by-chrome-tips-included/"><u>Troubleshooting Excessive RAM Use by Chrome [Tips Included]</u></a></li>
</ul></div>

