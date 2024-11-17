---
title: How to Hide or Show the Clock and Date From the Taskbar in Windows 11 and 11
date: 2024-11-12T19:10:24.248Z
updated: 2024-11-17T16:02:31.720Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Hide or Show the Clock and Date From the Taskbar in Windows 11 and 11
excerpt: This Article Describes How to Hide or Show the Clock and Date From the Taskbar in Windows 11 and 11
keywords: Hide Windows Clock,Show/Hide Taskbar Clock,Taskbar Time Display,Adjust Taskbar Date,Disable Windows Clock,Change Taskbar Settings,Control Windows 11 Clock
thumbnail: https://thmb.techidaily.com/ccdf50131a6b9e5675eea00d8176eeb8be6c7d5597ded286e2b977dc206141e5.jpg
---

## How to Hide or Show the Clock and Date From the Taskbar in Windows 11 and 11

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471">
  <img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/updated-digital-splendor-on-youtube-the-hue-harmonization-way-for-2024/"><u>[Updated] Digital Splendor on YouTube The Hue Harmonization Way for 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/138603396-9781788172271-connecting-with-the-angels-made-easy/"><u>Connecting with the Angels Made Easy | Free Book</u></a></li>
<li><a href="https://driver-download.techidaily.com/find-and-install-updated-drivers-for-your-canon-mg2900-easily/"><u>Find and Install Updated Drivers for Your Canon MG2900 Easily</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-play-40c-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Play 40C?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Vivo V29? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrate-keyboard-indicators-numlock-capslock-in-taskbar/"><u>Integrate Keyboard Indicators: NumLock, CapsLock in Taskbar</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/lenovo-x1-carbon-software-updates-secure-driver-downloads-for-win-10win-n7-systems/"><u>Lenovo X1 Carbon Software Updates – Secure Driver Downloads for Win 10/Win N7 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-resolve-microsoft-store-error-code-0x80072f30/"><u>Quick Steps to Resolve Microsoft Store Error Code 0X80072F30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-uninstallation-tips-for-non-functioning-printers-on-win-1011/"><u>Quick Uninstallation Tips for Non-Functioning Printers on Win 10/11</u></a></li>
<li><a href="https://games-able.techidaily.com/rapid-recreation-compile-your-favorite-quick-game-titles/"><u>Rapid Recreation: Compile Your Favorite Quick Game Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-connection-errors-with-unidentified-usb-ports/"><u>Resolving Connection Errors with Unidentified USB Ports</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-misidentified-gaming-feature-within-discord-windows-edition/"><u>Resolving Misidentified Gaming Feature Within Discord, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rewriting-windows-script-policy-top-4-strategies-for-enabling-ps-loading/"><u>Rewriting Windows Script Policy: Top 4 Strategies for Enabling PS Loading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-steam-video-playback-on-pc/"><u>Strategies to Improve Steam Video Playback on PC</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-new-possibilities-how-apples-integration-of-nfc-in-iphones-with-third-party-apps-enhances-your-experience-techinsights/"><u>Unlocking New Possibilities: How Apple's Integration of NFC in iPhones with Third-Party Apps Enhances Your Experience | TechInsights</u></a></li>
</ul></div>

