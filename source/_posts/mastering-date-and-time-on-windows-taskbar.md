---
title: Mastering Date & Time on Windows Taskbar
date: 2024-10-25T19:44:01.378Z
updated: 2024-11-01T18:35:51.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Date & Time on Windows Taskbar
excerpt: This Article Describes Mastering Date & Time on Windows Taskbar
keywords: Windows Taskbar Dates,Timers Control Panel,Adjust Date Display,Taskbar Date View,Manage WinDtTime,Time Bar Settings,Taskbar Scheduling
thumbnail: https://thmb.techidaily.com/6fd0cef62e823c305fb86e64196b6559e3c33c787060e717fb517085eb725bc3.jpg
---

## Mastering Date & Time on Windows Taskbar

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934183/19272" target="_top" id="1934183">
  <img src="//a.impactradius-go.com/display-ad/19272-1934183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934183/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934292/19272" target="_top" id="1934292">
  <img src="//a.impactradius-go.com/display-ad/19272-1934292" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934292/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/updated-reclaim-lively-sounds-in-muted-video-tweets-for-2024/"><u>[Updated] Reclaim Lively Sounds in Muted Video Tweets for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/749-apple-macbook-air-with-m2-chip-now-available-during-amazons-prime-day-zdnet-coverage/"><u>$749 Apple MacBook Air with M2 Chip Now Available During Amazon's Prime Day - ZDNet Coverage</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-chromatic-excellence-program/"><u>2024 Approved Chromatic Excellence Program</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-windows-11-is-operational-3-strategies/"><u>Ensuring Windows 11 Is Operational: 3 Strategies</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/essential-arsenal-for-modern-enterprise-top-trending-gadgets-and-tech-to-own-for-2024/"><u>Essential Arsenal for Modern Enterprise Top Trending Gadgets and Tech To Own for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-windows-11-key-purchases/"><u>Essential Guide to Windows 11 Key Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-the-sid-of-any-user-in-windows-11/"><u>How to Find the SID of Any User in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-itel-a05s-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Itel A05s Phone and Remove Locked Screen</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pioneers-of-haptic-technology-unveiled/"><u>In 2024, Pioneers of Haptic Technology Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-preview-hurdles-in-windows-version-of-office-mail/"><u>Removing Preview Hurdles in Windows Version of Office Mail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-windows-11s-ccleaner-functionality/"><u>Revitalizing Windows 11'S CCleaner Functionality</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-game-pass-showdown-psplus-vs-xbox/"><u>The Ultimate Game Pass Showdown: PS+ VS Xbox</u></a></li>
</ul></div>

