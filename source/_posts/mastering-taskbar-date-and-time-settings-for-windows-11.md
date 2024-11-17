---
title: Mastering Taskbar Date & Time Settings for Windows 11
date: 2024-11-13T18:56:53.259Z
updated: 2024-11-17T16:00:16.962Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Taskbar Date & Time Settings for Windows 11
excerpt: This Article Describes Mastering Taskbar Date & Time Settings for Windows 11
keywords: Win11 Taskbar Controls,Adjust D&T Window Menu,Windows Setup Dates/Times,Windows 11 Date Time Tweaks,Customize Win11 Dates,Taskbar Timestamps Settings,Alter DTC Windows
thumbnail: https://thmb.techidaily.com/a5249e9b13fd437412102feed5c7841b8ccf98fdf0188fbbf3a215fd35680a08.JPG
---

## Mastering Taskbar Date & Time Settings for Windows 11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144310/7443" target="_top" id="2144310">
  <img src="//a.impactradius-go.com/display-ad/7443-2144310" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144310/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2043855/7443" target="_top" id="2043855">
  <img src="//a.impactradius-go.com/display-ad/7443-2043855" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043855/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<span id="1982499">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982499.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982499">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982499.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982499%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982499/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-framingfraction-analysis/"><u>[New] 2024 Approved FramingFraction Analysis</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-turning-views-into-cash-secrets-to-successful-facebook-video-money-making/"><u>[Updated] In 2024, Turning Views Into Cash Secrets to Successful Facebook Video Money-Making</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-art-of-inverted-investigation-finding-true-sources-on-instagram-photos/"><u>[Updated] The Art of Inverted Investigation Finding True Sources on Instagram Photos</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-unlock-iphone-se-2020-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>3 Ways to Unlock iPhone SE (2020) without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/maciphoneipadapple-tvitunes-mp4mov/"><u>最適な動画変換ソフトウェアでMacからiPhone/iPad/Apple TV/iTunes用ビデオ: MP4/MOVへのシームレス変換</u></a></li>
<li><a href="https://change-location.techidaily.com/all-you-need-to-know-about-mega-greninja-for-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-read-locks-free-up-files-in-win-os/"><u>Disabling Read Locks: Free Up Files in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-epic-launcher-backups/"><u>Essential Tips for Epic Launcher Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-stuck-gpsvc-loop-in-windows-systems/"><u>Fixing the Stuck GPSVC Loop in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-remote-procedure-calls-5-fixes-for-errors/"><u>Mastering Remote Procedure Calls: 5 Fixes for Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconfiguring-your-start-menu-directly-access-file-explorer-via-onedrive/"><u>Reconfiguring Your Start Menu: Directly Access File Explorer via OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-windows-mic-testing/"><u>Step-by-Step: Windows Mic Testing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/sweet-surveillance-guide-to-recording-summer-treats/"><u>Sweet Surveillance Guide to Recording Summer Treats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-work-around-the-third-party-av-blockade-on-defender/"><u>Tips to Work Around the Third-Party AV Blockade on Defender</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unpacking-hps-bold-move-with-a-new-portable-all-in-one-device-the-unexpected-twists-in-tech-news-zdnet/"><u>Unpacking HP's Bold Move with a New Portable All-in-One Device – The Unexpected Twists in Tech News | ZDNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-you-shouldnt-turn-off-windows-11s-notifications/"><u>Why You Shouldn't Turn Off Windows 11'S Notifications</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Samsung Galaxy A23 5G | Dr.fone</u></a></li>
</ul></div>

