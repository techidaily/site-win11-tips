---
title: Customizing Clock and Dates Visibility on Windows Bar
date: 2024-10-16T04:56:19.263Z
updated: 2024-10-20T18:04:11.391Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Clock and Dates Visibility on Windows Bar
excerpt: This Article Describes Customizing Clock and Dates Visibility on Windows Bar
keywords: Visible Clock Windows,Custom Date Display PC,Windows Bar Time Adjust,Set Clock Appearance WIN,Personalize Date View Win,Clock Window Settings PC,Date Window Customization Windows
thumbnail: https://thmb.techidaily.com/1e95a148d850ecdd275c10a51292b0ccb900f6b4eff5c9989165ba5b957b7575.jpg
---

## Customizing Clock and Dates Visibility on Windows Bar

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
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-chuckle-campaign-7-ingenious-ideas-for-funny-youtube-videos-for-2024/"><u>[Updated] Chuckle Campaign 7 Ingenious Ideas for Funny YouTube Videos for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-savvy-flyers-selection-least-expensive-drone-brands/"><u>2024 Approved Savvy Flyers' Selection Least Expensive Drone Brands</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722186023609-ai-at-your-fingertnails-get-chatgpt-for-android-phones-today/"><u>AI at Your Fingertnails: Get ChatGPT for Android Phones Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-how-to-use-microsofts-phone-link-for-devices/"><u>Decoding How to Use Microsoft's ‘Phone Link’ for Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-infinite-scroll-loop-in-microsoft-excel-windows/"><u>End Infinite Scroll Loop in Microsoft Excel (Windows)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgotten-the-voicemail-password-of-xiaomi-redmi-note-12-4g-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Xiaomi Redmi Note 12 4G? Try These Fixes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-instagram-edge-vertical-footage-editing-techniques-on-final-cut-x/"><u>In 2024, The Instagram Edge Vertical Footage Editing Techniques on Final Cut X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-zoom-operation-and-troubleshooting-error-1132/"><u>Mastering Windows Zoom Operation and Troubleshooting Error 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-malfunctional-windows-troubleshooting/"><u>Optimizing Malfunctional Windows Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-removal-of-login-details-a-stepwise-approach/"><u>Safe Removal of Login Details: A Stepwise Approach</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/seamless-compatibility-downloading-and-updating-ch340-microcontroller-usb-drivers-in-windows-10/"><u>Seamless Compatibility: Downloading & Updating CH340 Microcontroller USB Drivers in Windows 10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-the-dilemma-effective-solutions-for-your-androids-permanent-darkness/"><u>Solving the Dilemma: Effective Solutions for Your Android's Permanent Darkness</u></a></li>
<li><a href="https://fox-blue.techidaily.com/the-ultimate-list-of-10-vectors-stock-pics-websites-for-2024/"><u>The Ultimate List of 10 Vectors Stock Pics Websites for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/unstick-silent-messages-on-iphone-discover-20plus-strategies-to-restore-sound-alerts/"><u>Unstick Silent Messages on iPhone: Discover 20+ Strategies to Restore Sound Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-file-locations-top-6-ways-to-copy-paths-in-windows-11-systems/"><u>Unveiling File Locations: Top 6 Ways to Copy Paths in Windows 11 Systems</u></a></li>
</ul></div>

