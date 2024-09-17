---
title: Concealing Clock, Show Dates on Windows Interface
date: 2024-09-12T09:33:49.525Z
updated: 2024-09-17T09:25:39.973Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Concealing Clock, Show Dates on Windows Interface
excerpt: This Article Describes Concealing Clock, Show Dates on Windows Interface
keywords: Windows Date Display,Hidden Clock Widgets,Customize Windows UI,Show Dates Feature,Interface Time Concealment,Window Timing Settings,Date Indicator Adjustment
thumbnail: https://thmb.techidaily.com/18d1ae3b93316df7253b6d9ca3430e2e7b9da85a6ae22dbb42da5be064fc57fa.png
---

## Concealing Clock, Show Dates on Windows Interface

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

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-exploring-stardews-best-modifications-a-list-of-the-top-7-for-2024/"><u>[New] Exploring Stardew's Best Modifications A List of the Top 7 for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-revealed-the-best-videos-from-facebooks-pages/"><u>[Updated] In 2024, Revealed The Best Videos From Facebook’s Pages</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-tecno-phantom-v-flip-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Tecno Phantom V Flip</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>Fixing Foneazy MockGo Not Working On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-80-pro-straight-screen-edition-phone-without-google-account-by-drfone-android/"><u>How to Unlock Honor 80 Pro Straight Screen Edition Phone without Google Account?</u></a></li>
<li><a href="https://extra-support.techidaily.com/inspiring-podcast-artwork-essential-design-insights-for-2024/"><u>Inspiring Podcast Artwork Essential Design Insights for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unresponsive-gpsvc-delay-in-windows/"><u>Overcoming Unresponsive GPSVC Delay in Windows</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/raid-rebound-hardware-haven/"><u>RAID Rebound: Hardware Haven</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/simplified-guide-from-camera-roll-capture-to-snapchat-posting-for-2024/"><u>Simplified Guide From Camera Roll Capture to Snapchat Posting for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-3d-art-process-with-indispensable-keyboard-shortcuts/"><u>Streamline Your 3D Art Process with Indispensable Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-cmd-connoisseurs-guide-to-five-fun-hacks/"><u>The Cmd Connoisseur's Guide to Five Fun Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ethernet-fix-guide-for-disconnection/"><u>Windows Ethernet Fix Guide for Disconnection</u></a></li>
</ul></div>

