---
title: Hide or Reveal Window 11'S Clock & Date
date: 2024-11-01T01:43:32.741Z
updated: 2024-11-07T08:44:06.569Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hide or Reveal Window 11'S Clock & Date
excerpt: This Article Describes Hide or Reveal Window 11'S Clock & Date
keywords: Hide Clock Window 11,Reveal Dates Window 11,Hide Time Windows,Unhide Clocks 11,Show Date Windows 11,Concealed Clock 11,Expose Dates 11
thumbnail: https://thmb.techidaily.com/6368130d53d4726baee2d761c0d301b46230227e22c8ccd434c4356090bf9d54.jpg
---

## Hide or Reveal Window 11'S Clock & Date

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925484/19272" target="_top" id="1925484">
  <img src="//a.impactradius-go.com/display-ad/19272-1925484" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925484/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136627/26400" target="_top" id="2136627">
  <img src="//a.impactradius-go.com/display-ad/26400-2136627" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136627/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-twitter-titans-the-most-shared-tweets/"><u>[Updated] 2024 Approved Twitter Titans The Most Shared Tweets</u></a></li>
<li><a href="https://discover-help.techidaily.com/1-best-screen-recording-apps-manycam-obs-studio-and-more/"><u>1. Best Screen Recording Apps: ManyCam, OBS Studio & More</u></a></li>
<li><a href="https://techtrends.techidaily.com/before-you-buy-a-dash-cam-understanding-9-crucial-considerations-first/"><u>Before You Buy a Dash Cam: Understanding 9 Crucial Considerations First</u></a></li>
<li><a href="https://facebook.techidaily.com/connect-or-date-understanding-facebooks-new-feature/"><u>Connect or Date? Understanding Facebook’s New Feature</u></a></li>
<li><a href="https://fox-access.techidaily.com/elevate-your-gaming-experience-discovering-kinemasters-potential/"><u>Elevate Your Gaming Experience - Discovering KineMaster's Potential</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/intel-uhd-graphics-driver-download-and-update-windows-1111/"><u>Intel UHD Graphics Driver Download & Update - Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obtaining-public-address-the-cmd-key/"><u>Obtaining Public Address: The CMD Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opening-windows-11-privilege-management-hub/"><u>Opening Windows 11 Privilege Management Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-education-aesthenasics-in-win-11/"><u>Personalized Education Aesthenasics in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-solutions-stop-wwe-2k23-crashing-on-new-windows-os/"><u>Quick Solutions: Stop WWE 2K23 Crashing on New Windows OS</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-mystery-repairing-msvcr100dll-file-absence-issues/"><u>Solving the Mystery: Repairing MSVCR100.DLL File Absence Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-enhancing-old-games-with-retroarch-achievements/"><u>Step-by-Step Guide to Enhancing Old Games with Retroarch Achievements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-overcoming-dxgidll-missing-file-issue/"><u>Win11: Overcoming Dxgi.dll Missing File Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-password-reset-timing-alteration/"><u>Windows 10/11 Password Reset Timing Alteration</u></a></li>
</ul></div>

